


## 트러블 슛팅
탭 사이즈가 4칸으로 설정 되어있어서,에러 뜸. ==> 탭 사이즈 2칸으로 수정하면서 에러 수정.  
ctrl + shfit + p  -->  Preferences:Open User Settings(JSON) -->  코드 추가
```js
// The number of spaces a tab is equal to. This setting is overridden
// based on the file contents when `editor.detectIndentation` is true.
"editor.tabSize": 2,
 
// When opening a file, `editor.tabSize` and `editor.insertSpaces`
// will be detected based on the file contents. Set to false to keep
// the values you've explicitly set, above.
"editor.detectIndentation": false
```