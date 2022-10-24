# 系統分析與設計 小組專題 作業1
##  組別
第14組
## 組員名單
- 蔡明智（組長）
- 姚家浩
- 袁顥洋
- 禤蔚灝
- 俞閎譯

## 題目
Unity機車駕駛小遊戲 - 每日路上

## 介紹
以Unity製作的單人休閒遊戲。玩家須在一條大直路上操控自己的機車向前走，並避開路上所有的障礙物以避免交通事故發生；另外加入安全駕駛知識，讓玩家了解如何安全地駕駛。

## 甘特圖
```mermaid
gantt    
    section Concept
    Idea: c1, 2022-10-03, 1w
    
    section Researchs
    Art: r1, 2022-10-03, 1w
    Technical: r2, 2022-10-03, 1w
    
    section Graphics
    Scenes: g1, after r1, 4w
    Objects: g2, after r1, 4w
    User Interfaces: g3, after r1, 4w
    
    section Sounds
    Sounds: s1, after g3, 2w
    
    section Programming
    Scenes: p1, after g1 1w, 2w
    User Interfaces: p2, after g3, 2w    
    Data Handling: p3, after p5, 2w    
    Sounds: p4, after s1, 2w
    Game Logics: p5, after r2, 6w
    
    section Testing
    Testing: f1, after p4, 1w
```

## PERT圖
![PERT](PERT.png)

## 分工表

|任務＼組員|蔡明智|姚家浩|袁顥洋|禤蔚灝|俞閎譯|
|--------|:---:|:---:|:---:|:---:|:---:|
|Concept: Idea|✔|✔|✔|✔|✔|
|Researchs: Art||✔|✔|✔|✔|
|Researchs: Technical|✔|✔|✔|✔|✔|
|Graphics: Scenes|✔|||||
|Graphics: Objects|✔|||||
|Graphics: User Interfaces||✔|✔|||
|Sounds: Sounds||✔|✔|✔|✔|
|Programming: Scenes|✔|✔|✔|✔|✔|
|Programming: User Interfaces|✔|✔|✔|✔|✔|
|Programming: Data Handling|✔|||✔||
|Programming: Sounds|✔|✔|✔|✔|✔|
|Programming: Game Logics|✔||||✔|
|Testing: Testing|✔|✔|✔|✔|✔|
