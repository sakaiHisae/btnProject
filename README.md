# btn_project
枠がホバーアニメーションするグラデーションボタンです。  

### [DEMO](https://sakaihisae.github.io/btn_project/)

### 導入方法
btn_project/src/componentsの中にあるvueファイルから  
使用したいボタンを個人のプロジェクトに追加してください。

### ボタン機能
```
<LineAnimation00 msg="lineAnimation00" url="#"/>
```
msg="" : ボタンのテキスト　　　url="" : リンク先  

### オプション
```
<LineAnimation00 :fontSize="'12px'"/>
```
：ボタンのフォントサイズの指定。

```
<LineAnimation00 :Color="'#000'"/>
```
：ボタンの文字色の指定。

```
<LineAnimation00 :borderColor="'#fff'"/>
```
：外枠の色指定。

```
<LineAnimation00 bgGradation="'linear-gradient(45deg, #8cced2 5%,#c09cdd 45%, #ecbeca 95%)'"/>
```
：背景グラデーションの色指定。



------------------------------------
********
________
