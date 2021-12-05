# Review
1. 반응형 헤더
2. parcel-bundler
3. scss
4. toggle button
---
<br /><br />

## 반응형 헤더
<br />

```css
@media screen and (max-width: 768px)
```
너비가 768px 이하로 변경될 때  `.togglebtn`햄버거 버튼이 생기고 햄버거 버튼을 누르면 `.nav__menu`와`.nav__links`는  `display:felx`로 나타난다.<br /><br />


---
## toggle button
<br />

```js
const toggleBtn = document.querySelector('.togglebtn')
const menu = document.querySelector('.navbar__menu')
const icons = document.querySelector('.navbar__links')

toggleBtn.addEventListener('click', () => {
  menu.classList.toggle('active')
  icons.classList.toggle('active')
})
```
햄버거 버튼을 클릭하면 `.nav__menu`와`.nav__links`에 `.active`클래스(  `display:felx`)를 생성한다. <br /><br />

---
## parcel-bundler와 scss
<br />
scss를 css로 컴파일할 때 parcel-bundler를 설치하면 편리하다. 기본으로 scss컴파일러가 제공되어 따로 플러그인을 설치하지 않아도 된다.
