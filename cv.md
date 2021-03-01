# 1. Denis Chukhlib
## 2. telegram: **@Chuhleb**
### 3. ***About:*** 
> I'm honest and flexible person. Always have a big hunger for new knowladge. I love to inspire other people around me and get inspired by them. Love to explore and discover something new.

#### 4. [Skills](https://en.wikipedia.org/wiki/Skill): basic knowledge of HTML, CSS, JS, GIT.
#### 5.
```
function getBoard(width = 8, height = 8) {
  const blackFirst= '# ',
        whiteFirst = ' #';
  let strBlackFirst= '',
      strWhiteFirst= '';
  for (let i=0; i<width/2; i++){
    strBlackFirst += blackFirst;
    strWhiteFirst += whiteFirst; 
  }
  strBlackFirst=strBlackFirst.slice(0,width);
  strWhiteFirst=strWhiteFirst.slice(0,width);
  for (let i=0; i<height/2; i++){
    console.log(strBlackFirst);
    if(i*2+1 < height){
       console.log(strWhiteFirst);
    }
  }
}

getBoard(5,5);
```
#### 6. 
- [Code Example](https://denisch88.github.io/Thanos__landing/)

