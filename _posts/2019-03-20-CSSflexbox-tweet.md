---
title: "CSS Flexbox: Add Flex Superpowers to the Tweet Embed"
date: 2019-03-20
---
### 利用CSS Flexbox的display： flex布局tweet界面
```css
body {
  font-family: Arial,sans-serif;
}
header {
  display: flex;
}
header .profile-thumbnail {
  width: 50px;
  height: 50px;
  border-radius: 4px;
}
header .profile-name {
  display: flex;
  margin-left: 10px;
}
header .follow-btn {
  display: flex;
  margin: 0 0 0 auto;
}
header .follow-btn button {
  border: 0;
  border-radius: 3px;
  padding: 4px;
}
header h3, header h4 {
  display: flex;
  margin: 0;
}
#inner p {
  margin-bottom: 10px;
  font-size: 20px;
}
#inner hr {
  margin: 20px 0;
  border-style: solid;
  opacity: 0.1;
}
footer {
  display: flex;
}
footer .stats {
  display: flex;
  font-size: 15px;
}
footer .stats strong {
  font-size: 18px;
}
footer .stats .like {
  margin-left: 10px;
}
footer .cta {
  margin-left: auto;
}
footer .cta button {
  border: 0;
  background: transparent;
}
```
```html
<header>
  <img src="" alt="profile picture" class="profile-thumbnail">
  <div class="profile-name">
    <h3>
      Quincy Larson
    </h3>
    <h4>
      @ossia
    </h4>
  </div>
  <div class="follow-btn">
    <button>
      Follow
    </button>
  </div>
</header>
<div class="inner">
  <p>i meet so many people who are in search of that on trick that will help them work smart!
</p>
  <span class="date">17:47 PM -12 Jan 2019</span>
  <hr>
</div>
<footer>
  <div class="stats">
    <div class="Retweets">
      <strong>107</strong> Retweets
    </div>
    <div class="likes">
      <strong>431</strong>Likes
    </div>
    </div>
    <div class="cta">
      <button class="share-btn">
        Share
      </button>
      <button class="Retweet-btn">
        Retweet
      </button>
      <button class="like-btn">
        Like
      </button>
    </div>
</footer>
```
