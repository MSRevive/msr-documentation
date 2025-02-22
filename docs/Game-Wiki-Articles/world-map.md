# World Map of Leann

A crude representation of the game world, told through a flowchart.

``` mermaid
graph LR
  edana(Edana) <--> thornlands(Thornlands) <--> sfor(Eswen Mallen) & helena(Helena) & heras(Heras) & mscave(Mscave) & thornnorth(Thornlands North);
  thornnorth <--> msquest(MS Quest) & bloodrose(Bloodrose) & ww1(World Walker Series) & nmthornlands(Nightmare Thornlands) & orcfor(Orkat Forest);
  bloodrose <--> mssnow(MS Snow) & aleyesu(Aleyesu);
  mscave <--> goblintown(Goblin Town) & gatecity(Gate City);
  edana <--> edanasewers(Edana Sewers) <--> chapel(Chapel) <--> isle(Isle);
  sfor <--> challs(Halls of Carthane) & thanatos(Thanatos) & calruin2(Calruin) & bcastle(Haunted Castle);
  challs <--> wicardoven(Wicard Oven);
  helena <--> kprelude(Keledros Prelude) & daragoth(Daragoth) & dtemple(Demon Temple);
  helena --> oldhelena(Old Helena);
  kprelude <--> itower(Idemark's Tower) & kboss(Keledros Library) & thekeep(The Keep);
  thekeep <--> dragooncaves(Dragoon Caves);
  daragoth <--> deralia(Deralia) <--> gcape(Gertenheld Cape) & ocrossing(Ocean Crossing) & dsewers(Deralia Sewers);
  daragoth <--> mines(Mines) & lowlands(Curse of the Bear God Series);
  daragoth <-- Hidden --> nash(Nashalrath);
  gcape <--> gforest(Gertenheld Forest);
  ocrossing <--> ara(Port Ara) & islesdread(Isles of Dread) & tundra(Tundra);
  mssnow <--> tundra;
  aleyesu <--> aluhandra(Aluhandra) <--> shadpalace(Shahaddar Palace) <--> sorcvilla(Shahaddar Villa);
  sorcvilla --> aluhandra;
  lodagond(Lodagond);
  thewall(The Wall);
  hswamp(The Hunderswamp);
  shendereast(Shender East);
  hemlock(Hemlock);
  bloodshrine(Bloodshrine);

  click edana "../Regions/Edana/Edana"
  click thornlands "../Regions/Thornlands/Thornlands"
  click edanasewers "../Regions/Edana Sewers/Edana Sewers"
```