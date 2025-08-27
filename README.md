### 새롭게 배운 것

- Google Fonts와 같이 CDN으로 불러오는 폰트는 html에서 link로 불러오는 것이 가능하지만, assets 폴더에 폰트 파일이 있는 경우는 다르다.
- 이 경우에는 CSS에서 @font-face 를 입력해 주면 된다. font-family와 src: url()을 지정해 주면 된다.