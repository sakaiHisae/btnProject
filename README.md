# btn_project
枠がホバーアニメーションするグラデーションボタンです。  

### [DEMO](https://sakaihisae.github.io/btn_project/)

### 導入方法
btn_project/src/componentsフォルダの中にあるvueファイルから  
使用したいボタンを個人のcomponentsフォルダに追加して使用してください。  
<br>
### ボタン機能
```html
<LineAnimation00 msg="lineAnimation00" url="#"/>
```
テキストとリンク先を指定。  
<br>
### オプション
```html
<LineAnimation00 :fontSize="'12px'"/>
```
フォントサイズの指定。  
<br>
```html
<LineAnimation00 :Color="'#000'"/>
```
文字色の指定。  
<br>
```html
<LineAnimation00 :borderColor="'#fff'"/>
```
外枠の色指定。  
<br>
```html
<LineAnimation00 bgGradation="'linear-gradient(45deg, #8cced2 5%,#c09cdd 45%, #ecbeca 95%)'"/>
```
背景グラデーションの色指定。
