#  SaveTheUndead
## 🎇 Team Notion

https://teamsparta.notion.site/05-5-46ce2a45c1e749839bb2fc882e94db92


## 🖥️ Project Introduction
어느 날 당신은 좀비가 되었습니다! 인간들의 공격을 피하며 최대한 오래 살아남으세요!

Unity를 이용한 Dodge like
<br>

## 🕰️ Development Period
* 23.09.09 ~ 23.09.14

### 🧑‍🤝‍🧑 Member
 - 조영오(팀장) / https://github.com/jyo217
 - 김광수(팀원) / https://github.com/kksoo0131
 - 문현우(팀원) / https://github.com/Munch310/
 - 맹주한(팀원) / https://github.com/SanyangForest
 - 이성권(팀원) / http://github.com/LeeSeongGwo

### ⚙️ Development Environment
- **Language** : C#
- **Engine** : Unity 2022.3.2f1
- **IDE** : Visual Studio 2022
- **Framework** : .NET 6.0

### 내가 구현한 기능

1. 탄환을 발사하는 기능
   
   BulletManager - <a href="https://github.com/NBCampUnityA05/SaveTheUndead/wiki/4-%E2%80%90-BulletManager" >상세보기 - WIKI 이동</a>

   Bullet의 생성과 파괴가 너무 많이 발생한다. 개선하기 위해서는 Object Pool을 만들어서 Object Pool로 관리하는 방법이 있다.

   Object Pool에 Bullet이 파괴될 시점에 SetActive(false)로 GameObject를 비활성화한 상태로 보관하고 Object Pool에 객체가 있으면

   Bullet을 새로 생성하지 않고 Object Pool에 보관된 객체를 초기화하여 다시 사용하는 것으로 기능을 개선할 수 있다.
   
   
3. 맵에 적이 겹치지 않게 스폰하는 기능
    
   EnemyManager - <a href="https://github.com/NBCampUnityA05/SaveTheUndead/wiki/5-%E2%80%90-EnemyManager" >상세보기 - WIKI 이동</a>

   처음에는 적이 처치되는 기능을 생각하지 않았지만 나중에 추가한 기능이라 처치된 적의 자리에 다시 몹이 스폰하도록 만들지 못했다.
   
   적이 스폰 될때 자신의 위치정보를 가지고 파괴될때 생성 위치를 다시 List에 추가하는 식으로 기능을 수정 하면 개선할 수 있다고 생각한다.


### 📜 Assets References
- https://assetstore.unity.com/packages/2d/undead-survivor-assets-pack-238068
- https://freesound.org/people/ShadyDave/sounds/608630/
- https://www.pngwing.com/en/free-png-zrzud

## 📌 Main Functions
### GameManager - <a href="https://github.com/NBCampUnityA05/SaveTheUndead/wiki/1-%E2%80%90-GameManger" >상세보기 - WIKI 이동</a>

### PlayerManager - <a href="https://github.com/NBCampUnityA05/SaveTheUndead/wiki/2-%E2%80%90-PlayerManager" >상세보기 - WIKI 이동</a>

### LifeManager - <a href="https://github.com/NBCampUnityA05/SaveTheUndead/wiki/3-%E2%80%90-LifeManager" >상세보기 - WIKI 이동</a>

### BulletManager - <a href="https://github.com/NBCampUnityA05/SaveTheUndead/wiki/4-%E2%80%90-BulletManager" >상세보기 - WIKI 이동</a>

### EnemyManager - <a href="https://github.com/NBCampUnityA05/SaveTheUndead/wiki/5-%E2%80%90-EnemyManager" >상세보기 - WIKI 이동</a>

### UIManager - <a href="https://github.com/NBCampUnityA05/SaveTheUndead/wiki/6-%E2%80%90-UI-Manager" >상세보기 - WIKI 이동</a>

### AudioManager - <a href="https://github.com/NBCampUnityA05/SaveTheUndead/wiki/7-%E2%80%90-AudioManager" >상세보기 - WIKI 이동</a>

### LevelManager - <a href="https://github.com/NBCampUnityA05/SaveTheUndead/wiki/8-%E2%80%90-LevelManager" >상세보기 - WIKI 이동</a>

### MapManger - <a href="https://github.com/NBCampUnityA05/SaveTheUndead/wiki/9-%E2%80%90-MapManager" >상세보기 - WIKI 이동</a>
