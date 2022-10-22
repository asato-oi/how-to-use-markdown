# Markdown記法の使い方について
<br><br>

## 見出し
    # H1タグ
    ## H2タグ
    ### H3タグ
    #### H4タグ
    ##### H5タグ
    ###### H6タグ
 ### 結果
 # H1タグ
 ## H2タグ
 ### H3タグ
 #### H4タグ
 ##### H5タグ
 ###### H6タグ
 ---
<br><br>

## 本文
    何もつけずに記入します。  
    段落を分けるためには半角スペースを二つ入れます。
### 結果
何もつけずに記入します。  
段落を分けるためには半角スペースを二つ入れます。
***
<br><br>

## 引用
    >引用本文
    >>改行がされないので、入れ子構造にする場合は>>を入れる
### 結果
>引用本文
>>改行がされないので、入れ子構造にする場合は>>を入れる
---
<br><br>

## リスト
    - リスト１
      - リスト1-2(前にスペースを２つ付ける) 
    - リスト2
    1. リスト3
      2. リスト3-1
    2. リスト4
    <dl>
      <dt>オレオ</dt>
      <dd>クッキー＆クリーム</dd>
      <dt>リッツ</dt>
      <dd>プレーンクラッカー</dd>
    </dl>
### 結果
- リスト１
  - リスト1-2(前にスペースを２つ付ける) 
- リスト2
1. リスト3
  2. リスト3-1
2. リスト4
<dl>
  <dt>オレオ</dt>
  <dd>クッキー＆クリーム</dd>
  <dt>リッツ</dt>
  <dd>プレーンクラッカー</dd>
</dl>

---
<br><br>
## チェックボックス
    - [ ] リスト1
    - [x] リスト2
### 結果
- [ ] リスト1
- [x] リスト2

---
<br><br>
## 水平線
    ***
    * * *
    ---
    - - -
### 結果
***
* * *
---
- - -
---
<br><br>

## リンク

    https://asatooi-portfolio.netlify.app/
    
    [AsatoOiのポートフォリオ](https://asatooi-portfolio.netlify.app/)

### 結果

https://asatooi-portfolio.netlify.app/  

[AsatoOiのポートフォリオ](https://asatooi-portfolio.netlify.app/)

***
<br><br>

## 強調
    *強調(イタリック体)*
    **強調(Bold体)**
    ***強調(イタリック＆Bold体)***
### 結果
*強調(イタリック体)*  
**強調(Bold体)**  
***強調(イタリック＆Bold体)***  
***
<br><br>
## 画像
    ![ダミー画像](https://placehold.jp/150x150.png)
### 結果
![ダミー画像](https://placehold.jp/150x150.png)
---
<br><br>

## 打ち消し
    ~~打ち消し~~
### 結果
~~打ち消し~~
***
<br><br>

## 注釈
    本文本文本文[^1]  
    [^1]:注釈テキスト注釈テキスト注釈テキスト
### 結果
本文本文本文[^1]  
[^1]:注釈テキスト注釈テキスト注釈テキスト
---
<br><br>

## コード
    ```js:sample.js
    const hoge = "codeの挿入の仕方"
    console.log(hoge);
    ```
    ```html:sample.html
    <div class="sample">
      <p>Hello world</p>
    <div>
    ```
    ```diff js:sample.js
    - console.log("hello");
    + console.log("good morning");
    ```  
    `print("hello world");`と書くことでインライ表示することもできます。  
    `` `バッククオート` `` や ``` ``2連続バッククオート`` ``` も記述できます。  
    The background color should be `#ffffff` for light mode and `#0d1117` for dark mode.
```js:sample.js
const hoge = "codeの挿入の仕方" 
console.log(hoge);
```
```html:sample.html
<div class="sample">
  <p>Hello world</p>
<div>
```
```diff js:sample.js
- console.log("hello");
+ console.log("good morning");
```
`print("hello world");`と書くことでインライ表示することもできます。  
`` `バッククオート` `` や ``` ``2連続バッククオート`` ``` を埋め込むことができます。  
`rgb(255,0,0)`や`#ffce44`など、カラーコードも入れられます。  
***
<br><br>

## コメントアウト
    <!-- 公開されません！ -->
### 結果
<!-- 公開されません！ -->
---
<br><br>

## 補足説明
    > **Note**  
    > This is a note

    > **Warning**  
    > This is a warning
### 結果
> **Note**  
> This is a note

> **Warning**  
> This is a warning
***
<br><br>

## 絵文字
    :smiley:
    :smile:
    :laughing:
    :innocent:
    :drooling_face:
    [絵文字一覧](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)
### 結果
:smiley:
:smile:
:laughing:
:innocent:
:drooling_face:  
[絵文字一覧](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)
***
<br><br>

## テーブル
    | Left align | Right align | Center align |
    |:-----------|------------:|:------------:|
    | This       | This        | This         |
    | column     | column      | column       |
    | will       | will        | will         |
    | be         | be          | be           |
    | left       | right       | center       |
    | aligned    | aligned     | aligned      |
***
### 結果
| Left align | Right align | Center align |
|:-----------|------------:|:------------:|
| This       | This        | This         |
| column     | column      | column       |
| will       | will        | will         |
| be         | be          | be           |
| left       | right       | center       |
| aligned    | aligned     | aligned      |
***
<br><br>

## 数式
    ```math
    \left( \sum_{k=1}^n a_k b_k \right)^{\!\!2} \leq
    \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)
    ```
### 結果
 ```math
 \left( \sum_{k=1}^n a_k b_k \right)^{\!\!2} \leq
 \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)
 ```
***
<br><br>

 ## Mermaid
    ```mermaid
    graph TD;
        A-->B;
        A-->C;
        B-->D;
        C-->D;
    ```
### 結果
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```  
