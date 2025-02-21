# World Map of Leann

A crude representation of the game world, told through a flowchart.

``` mermaid
graph LR
  edana(Edana) <--> thornlands(Thornlands) <--> sfor(Eswen Mallen) & helena(Helena) & heras(Heras) & mscave(Mscave) & thornnorth(Thornlands North);
  edana <--> edanasewers(Edana Sewers) <--> chapel(Chapel) <--> isle(Isle);
  sfor <--> challs(Halls of Carthane) & thanatos(Thanatos) & calruin2(Calruin) & bcastle(Haunted Castle);
  challs <--> wicardoven(Wicard Oven);
  helena <--> kprelude(Keledros Prelude) & daragoth(Daragoth) & dtemple(Demon Temple);
  helena --> oldhelena(Old Helena);
  kprelude <--> itower(Idemark's Tower) & kboss(Keledros Library) & thekeep(The Keep);
  daragoth <--> deralia(Deralia) <--> gcape(Gertenheld Cape) & ocrossing(Ocean Crossing) & dsewers(Deralia Sewers);
  ocrossing <--> ara(Port Ara) & islesdread(Isles of Dread) & tundra(Tundra);
```