---
title: "โ๏ธ GetType() typeof()"
date: 2022-06-29. 13:01
categories: โ๏ธProgramming ๐ฏ๏ธProgramming-Memo
---

## ๐

---

https://stackoverflow.com/questions/11312111/when-and-where-to-use-gettype-or-typeof


๋ ๋ค Meta-Information ์ ํฌํจํ System.Type ์ ๊ฐ์ ธ์ด

typeof()

() ์์ ํ์ ์ด๋ฆ์(๋ฌธ์์ด์ด ์๋๋ผ ์๋ณ์ Identifier) ๋ฃ๊ณ , ํ์์ ๊ฐ์ ธ์ค๋ ํค์๋ (์ปดํ์ผ ํ์ ์์  => ์ ์ ์ธ ํ์)
ex )
typeof(int) => Int32
typeof(string) => string

GetType()

() ์์ ์ธ์คํด์ค๋ฅผ ๋ฃ๊ณ , ํ์์ ๊ฐ์ ธ์ค๋ ํจ์ (๋ฐํ์ ์์ )
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
ํ์ ์๋ณ์ Testing ์ด๋ผ๊ณ  ํํํ๋ ๋ฏ?

if (mycontrol is TextBox)                       // ==> true
!=
if (mycontrol.GetType() == typeof(TextBox))     // ==> false

์ด๋ ๊ฐ์ง ์๋ค
์๋ํ๋ฉด mycontrol์ด TextBox์๊ฒ derived ํ์๋์ด์ก์ ์ ์๊ธฐ ๋๋ฌธ
์ด ๊ฒฝ์ฐ ์ฒซ ๋ฒ์งธ ์ผ์ด์ค๋ true, ๋ ๋ฒ์งธ ์ผ์ด์ค๋ false ์กฐ๊ฑด์์

TextBox์ ๋ชจ๋  inherit ์์๋ฐ์ ์น๊ตฌ๋ค์ ๊ฐ์ ธ์ ๋น๊ตํ๋ ค๋ฉด is

public class MySpecializedTextBox : TextBox
{
}

MySpecializedTextBox specialized = new MySpecializedTextBox();
if (specialized is TextBox)       ==> true

if (specialized.GetType() == typeof(TextBox))        ==> false

Casting
