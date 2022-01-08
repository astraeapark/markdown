# 제목 1  

## 제목 2

### 제목 3

#### 제목 4
##### 제목 5
###### 제목 6  

Title1 with Equal Sign
========
Title 2 with Hyphen
------

문자강조 (Text Emphasis)  
---
Italic 이탈릭체: Use *Asterisks* or _Under Score_  
Bold 두껍게: Use **Double Asterisks** or __Double Under Score__  
Cancel 중간줄: Use ~~Tilder~~   
UnderLine 밑줄 : User <u>Under Line</u>

목록 (List)
---
1. Order List1
1. Order List2
2. Order List3
    - Unordered Sub List
    + Unordered Sub List
    * Unordered Sub List
3. Ordered List4
   1. Ordered Sub List1
   2. Ordered Sub List2
  
## 링크(Link)
Format: `[Display Text](Link)`

- Simple Format Link: [GOOGLE](https://google.com)

- Link with guidement: [NAVER](https://naver.com "링크 설명(title)을 작성하세요.")

- Relative reference: `[상대적 참조](later...)`
  
- Reference Link :  
  - [Google][Google link]  
  - [GitHub][1]  
  - inline reference [Reference Link]  

[Google link]: https://google.com
[1]: https://github.com "git link"
[Reference Link]:  https://github.com  

- Auto Link: 일반적인 URL주소와 괄호 안의 주소(Nomal URL and URL in the Angel Brackets`< >`)  
    구글 홈페이지: https://google.com  
    네이버 홈페이지: <https://naver.com>  


## 코드 (Code) === `<pre> <code>` : ``
`
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
`

## 블록 코드 : \``` ```
```html
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
```
```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function func() {
  var a = 'AAA';
  return a;
}
```

```bash
$ vim ./~zshrc
```