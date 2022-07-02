# Intro to HTML&CSS

## Learned
---
- Learned and practied Basic HTML & CSS
- Created simple `Dedenne Profile Card` based on concepts I learned

**HTML**
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dedenne Profile Card</title>
  <link rel="stylesheet" href="./class.css">
</head>
<body>
  <div class="wrap">

    <div class="img"><img src="./데덴네.jpg" alt="Dedenne">Dedenne</div>
    <div class="list">
      <ul>
      <li>Type: electric</li>
      <li>Abilities: Cheek Pouch or Pickup</li>
      <li>Weaknesses: Poison</li>
      </ul>
    </div>

    <div class="hello">Glad to see you :D</div>
  </div>

</body>
</html>
```

**CSS**
```
*{
  font-size: 18px;
}

.wrap {
  border: 1.5px solid black;
  border-radius: 2%;
  width: 300px;
  height: 550px;
}

img{
  width: 300px;
  height: 350px;
}

.img{
  background-color: rgba(233, 250, 246, 0.978);
  height: 400px;
  text-align: center;
  font-weight: bold;
}

.hello{
  border-top-style: solid;
  height: 80px;
  text-align: center;
  padding: 15px 0;
}
```
**RESULT!**

<img width="241" alt="Dedenne Profile Card" src="https://user-images.githubusercontent.com/105934304/176992783-23211df9-abde-43bb-bbbf-8b390915ae82.png">

## TO DO LIST
- MGS강의 Ch.8 CSS속성 공부
- 실습2 연습하기  


