---
search:
  exclude: true
tags:
  - Information
---

# **Regions**

Learn about the fine details of all the maps(Regions) you can explore throughout the game world, Leann, and beyond.

## **World Map of Leann**

A crude representation of the game world, told through a flowchart.

### **Explanation of Symbols**

??? info "Flowchart Legend"
    ``` mermaid
    graph LR
        A{Town Maps Have This Diamond Shape!} --> B(A Map With Easy Challenges to Overcome Looks Like This!) --> C(The Color Indicates the Challenge Level, This is Medium.) --> D(Hard!) --> E(Epic!);

        A:::easy
        B:::easy
        C:::medium
        D:::hard
        E:::epic


        classDef easy fill:#026100
        classDef medium fill:#b54a02
        classDef hard fill:#b50202
        classDef epic fill:#8502b5
    ```

### **The World Itself**

``` mermaid
graph LR
  edana{Edana} <--> thornlands(Thornlands) <--> sfor(Eswen Mallen) & helena{Helena} & heras(Heras) & mscave(Mscave) & thornnorth(Thornlands North);
  thornnorth <--> msquest(MS Quest) & bloodrose(Bloodrose) & ww1(World Walker Series) & nmthornlands(Nightmare Thornlands) & orcfor(Orkat Forest);
  bloodrose <--> mssnow(MS Snow) & aleyesu(Aleyesu);
  mscave <--> goblintown(Goblin Town) & gatecity{Gate City};
  edana <--> edanasewers(Edana Sewers) <--> chapel(Chapel) <--> isle(Isle);
  sfor <--> challs(Halls of Carthane) & thanatos(Thanatos) & calruin2(Calruin) & bcastle(Haunted Castle);
  challs <--> wicardoven(Wicard Oven);
  helena <--> kprelude(Keledros Prelude) & daragoth(Daragoth) & dtemple(Demon Temple);
  helena -- Hidden --> oldhelena(Old Helena);
  kprelude <--> itower(Idemark's Tower) & kboss(Keledros Library) & thekeep(The Keep);
  thekeep <--> dragooncaves(Dragoon Caves);
  daragoth <---> deralia{Deralia} <--> gcape(Gertenheld Cape) & ocrossing(Ocean Crossing) & dsewers(Deralia Sewers);
  daragoth <--> mines(Mines) & lowlands(Curse of the Bear God Series);
  daragoth <-- Hidden --> nash(Nashalrath);
  gcape <--> gforest(Gertenheld Forest);
  ocrossing <--> ara(Port Ara) & islesdread(Isles of Dread) & tundra(Tundra);
  mssnow <--> tundra;
  aleyesu <--> aluhandra(Aluhandra) <--> shadpalace(Shahaddar Palace) <--> sorcvilla{Shahaddar Villa};
  sorcvilla --> aluhandra;
  lodagond(Lodagond);
  thewall(The Wall);
  hswamp(The Hunderswamp);
  shendereast(Shender East);
  hemlock(Hemlock);
  bloodshrine(Bloodshrine);

  edana:::easy
  thornlands:::easy
  sfor:::easy
  helena:::easy
  heras:::easy
  mines:::easy
  gcape:::easy
  gforest:::easy
  mscave:::medium
  thornnorth:::easy
  bloodrose:::hard
  ww1:::medium
  nmthornlands:::medium
  orcfor:::hard
  mssnow:::medium
  goblintown:::easy
  gatecity:::easy
  deralia:::easy
  daragoth:::medium
  thekeep:::medium
  lowlands:::medium
  nash:::epic
  lodagond:::hard
  shadpalace:::epic
  msquest:::easy
  thewall:::epic
  hswamp:::hard
  edanasewers:::easy
  chapel:::easy
  isle:::easy
  dtemple:::medium
  challs:::medium
  thanatos:::medium
  calruin2:::medium
  bcastle:::medium
  oldhelena:::hard
  sorcvilla:::epic
  wicardoven:::medium
  dsewers:::hard
  tundra:::hard
  aleyesu:::medium
  aluhandra:::hard
  dragooncaves:::medium
  kprelude:::medium
  kboss:::medium
  itower:::hard
  ocrossing:::medium
  ara:::medium
  islesdread:::medium
  shendereast:::hard
  hemlock:::hard
  bloodshrine:::epic

  classDef easy fill:#026100
  classDef medium fill:#b54a02
  classDef hard fill:#b50202
  classDef epic fill:#8502b5

  click edana "../Regions/Edana/Edana"
  click thornlands "../Regions/Thornlands/Thornlands"
  click edanasewers "../Regions/Edana Sewers/Edana Sewers"
```

## **Regions Tags Index**

??? info "List of Region Articles"
    <!-- material/tags { scope: true } -->