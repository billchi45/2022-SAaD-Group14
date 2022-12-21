# 系統分析與設計 小組專題 作業4

## UML 類別圖
```mermaid
classDiagram
    Gameplay "1"--"1" ControlManager
    ControlManager "1"--"1" Motorcycle
    Gameplay "1"--"1" RoadsManager
    
    class Gameplay{
        -time : float
        -distance : float
        +StartGame()
        +GameOver()
    }
    
    class Motorcycle{
        -defaultSpeed : float
        -currentSpeed : float
        -hasCrashed : bool
        -UpdatePosition()
        -CheckCollision()
        +Accelerate()
        +Brake()
        +Steer(in toLeft : bool)
    }
    
    class ControlManager{
        +EnterInput()
    }
    
    class RoadsManager{
        -prefabs_roads : GameObject[]
        -currentRoads : GameObject[]
        -UpdateRoads()
        -GenerateRoads()
        -RemoveRoads()
    }
```

## 循序圖與活動圖
(1) 玩遊戲

![sequencediagram1](sequencediagram1.png)
![flowchart1](flowchart1.png)

(2) 選擇機車

![sequencediagram2](sequencediagram2.png)
![flowchart2](flowchart2.png)

(3) 觀看安全駕駛知識

![sequencediagram3](sequencediagram3.png)
![flowchart3](flowchart3.png)

(4) 查看自己成績

![sequencediagram3](sequencediagram4.png)
![flowchart3](flowchart4.png)
