---
title: "GetType() typeof()"
date: 2022-06-29. 13:01
categories: Programming Normal
---

https://stackoverflow.com/questions/11312111/when-and-where-to-use-gettype-or-typeof



둘 다 Meta-Information 을 포함한 System.Type 을 가져옴

typeof()

() 안에 타입 이름을(문자열이 아니라 식별자 Identifier) 넣고, 타입을 가져오는 키워드 (컴파일 타임 시점 => 정적인 타입)
ex )
typeof(int) => Int32
typeof(string) => string

GetType()

() 안에 인스턴스를 넣고, 타입을 가져오는 함수 (런타임 시점)
ex ) 
int temp = 0;
GetType(temp) => Int32
TempClass temp = new();
GetType(temp) => TempClass

string s = "Hi";
Type t1 = typeof(string);
Type t2 = s.GetType();

t1 == t2                    ==> true

object obj = "Hi";
Type t1  = typeof(object);  // ==> object
Type t2 = obj.GetType();    // ==> string

t1 == t2                    ==> false

Testing Types
타입 식별을 Testing 이라고 표현하는 듯?

if (mycontrol is TextBox)                       // ==> true
!=
if (mycontrol.GetType() == typeof(TextBox))     // ==> false

이는 같지 않다
왜냐하면 mycontrol이 TextBox에게 derived 파생되어졌을 수 있기 때문
이 경우 첫 번째 케이스는 true, 두 번째 케이스는 false 조건식임

TextBox의 모든 inherit 상속받은 친구들을 가져와 비교하려면 is

public class MySpecializedTextBox : TextBox
{
}

MySpecializedTextBox specialized = new MySpecializedTextBox();
if (specialized is TextBox)       ==> true

if (specialized.GetType() == typeof(TextBox))        ==> false




Casting