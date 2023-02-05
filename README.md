# CTF-Extra-Question
<br>
<br>

## Cryptography

この暗号文を解読してください  
暗号方式はシーザー暗号(Caeser Cipher)です  
シフト回数は５回です

```
pvrvyv
```
<details>
<summary>ヒント</summary>

この暗号文はシーザー暗号(Caeser Cipher)を使って暗号化しています  
シーザー暗号は文字を特定の回数分右にずらすことで、本来の文字を変える暗号です。  
ここでいう右にずらす特定の回数のことをシフトと言います  
例えば、abcという文字をシフトを３にして暗号化するとdefとなります。
<br>
<br>
**アルファベット:** ```a b c d e f g h i j k l m n o p q r s t u w v x y z```
</details>  

<details>
<summary>答え</summary>

**答え:** kqmqtq
</details>  

<details>
<summary>解説</summary>

シーザー暗号は文字を右に特定の回数ずらす（この回数をシフトと言う）ことで文字を暗号化します  
今回はシフトが５なので、元の文字を５回右にずらした文字になっています  
なので、元の文字に戻すには５回左にずらす必要があります  
左にずらしてみるとkqmqtqとなるので、答えはkqmqtqです
</details>
