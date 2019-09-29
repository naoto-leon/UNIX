# UNIX
コマンドプロントUNIX記載　チートシート


### pwd
現在のディレクトリ  

### cd  
ディレクトリ移動  
(EX) cd Desktop  

### ls  
入っているファイル参照  
(EX) ls Desktop  

### cp-r xxx xxx2  
xxxをxxx2としてコピー  

### mkdir  
新規ファイルを作る  
mkdir -p xxx/xxx2 とした場合xxxも合わせて作られる  

### mv xxx xxx2  
ファイル移動　xxx2をxxxに入れる  

### rmdir  
ファイルの削除  

### rm -r xxx  
xxxの中含めて全て削除。  

### less  
テキストとかの中身見る  
q で閉じる  

### $  
引数の引き渡し  
(EX)  
ls xxx  
cd !$  
!$ == xxx  

### sudo  
管理者権限  


***

## Vim 
編集tool

### vi xxx  
xxxをvimで開く

### i  
insertの開始  

### ESC  
編集終了  

### :w  
保存  

### :q  
閉じる  

### :q!  
保存せずに終了  

### vi ~/.bash_profile  
Bash開く　

## Permission 

アクセス権の変更に関して  

<img width="350" alt="スクリーンショット 2019-09-05 15 05 20" src="https://user-images.githubusercontent.com/43961147/64316126-e143e500-cfee-11e9-96ff-96414e9b5b3b.png">

<img width="450" alt="スクリーンショット 2019-09-05 15 06 23" src="https://user-images.githubusercontent.com/43961147/64316128-e143e500-cfee-11e9-9ef9-ed2df12fd33f.png">

r = 読み込み可能  
w = 書き換え可能  
x = 実行可能  

二進数による表記と変更方法  
<img width="450" alt="スクリーンショット 2019-09-05 15 42 18" src="https://user-images.githubusercontent.com/43961147/64317872-cfb10c00-cff3-11e9-8fbe-0bf9ac8dbc87.png">
