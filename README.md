# Heart-Trail-Animation
<img src="./image.gif">

## 효과 
마우스가 이동을 하면 하트가 생성

## 학습 
### 1. CSS : orphans   
페이지 하단에 출력돼야만 하는 최소의 줄 수를 정의하는 CSS 속성   

*예) 하나의 문단이 두 페이지에 걸쳐 쪼개질 때, 이전 페이지의 하단에 최소 3줄은 표시돼야한다를 의미*
```
@media print {
  orphans: 3;
}
```

### 2. JS : mousemove 이벤트
마우스 포인터가 영역 내에서 움직일 때마다 발생   

*예) 페이지 내에서 마우스 포인터의 위치를 ​​가져옵니다.*
```
$(document).mousemove(function(event){
  $("span").text(event.pageX + ", " + event.pageY);
});
```


## 학습 출처 
- 유튜브   
https://www.youtube.com/@JavaScriptKing   

- 아이콘  
https://www.iconfinder.com/     

- CSS  
https://seungwubaek.github.io/front-end/css/orphans_widows/