# markdown-cheatsheet

# ヘッダー
```
# H1
## H2
### H3
#### H4
##### H5
###### H6

H1
======

H2
-
```

# H1
## H2
### H3
#### H4
##### H5
###### H6


H1かH2であれば文字列配下に=か-をつけることで使用可能。なお、何個つけても挙動は変わらない

H1
======

H2
-

# 強調
```
イタリック体: *hogehoge*  _hogehoge_
強調1: **hogehoge**  __hogehoge__
強調2: **hogehoge  _hogehoge_**
取り消し線: ~~hogehoge~~
```
イタリック体 : *hogehoge*  _hogehoge_  
強調1: **hogehoge**  __hogehoge__  
強調2: **hogehoge  _hogehoge_**  
取り消し線: ~~hogehoge~~

# 改行
```
改行(スペース二つ)
するよ
改行
しないよ
```
改行  
するよ

改行
しないよ

# コード
````
```
print("hello")
```
````
```
print("hello")
```
コード部で```を使用したい場合は、外側を以下のように増やす
``````
`````
```
print("hello")
```
`````
``````
`````
```
print("hello")
```
`````
チルダでも可能
~~~~
~~~
print("hello")
~~~
~~~~
~~~
print("hello")
~~~

## インラインコード
```
ここでは```print("hello")```を実行
```
ここでは```print("hello")```を実行

## ハイライト
````
```javascript
var s = "javascript ハイライト";
alert(s);
```
```python
s = "Pyhon ハイライト"
print s
```
````
```javascript
var s = "javascript ハイライト";
alert(s);
```
 
```python
s = "Pyhon ハイライト"
print s
```
# リスト
```-``` or ```+``` or ```*```を以下のように使えばリストが作れる
```
- リスト1
    - リスト1_1
        - リスト1_1_1
        - リスト1_1_2
    - リスト1_2
- リスト2
- リスト3
```
- リスト1
    - リスト1_1
        - リスト1_1_1
        - リスト1_1_2
    - リスト1_2
- リスト2
- リスト3

番号付きは以下
```
番号つきリスト
1. 番号付きリスト1
    1. 番号付きリスト1-1
    1. 番号付きリスト1-2
1. 番号付きリスト2
```
番号つきリスト
1. 番号付きリスト1
    1. 番号付きリスト1-1
    1. 番号付きリスト1-2
1. 番号付きリスト2

# 引用符
```
> 引用するよ
```
> 引用するよ

# 画像
```
Inline-style: 
![alt text](https://github.com/kuro0909/markdown-cheatsheet/raw/master/images/test-img.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/kuro0909/markdown-cheatsheet/raw/master/images/test-img.png "Logo Title Text 2"
```
Inline-style: 
![alt text](https://github.com/kuro0909/markdown-cheatsheet/raw/master/images/test-img.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/kuro0909/markdown-cheatsheet/raw/master/images/test-img.png "Logo Title Text 2"

参考: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#lines
参考: https://gist.github.com/mignonstyle/083c9e1651d7734f84c99b8cf49d57fa
