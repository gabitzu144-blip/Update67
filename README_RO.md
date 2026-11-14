# MoonCity X (Forge 1.20.1)

## Compilare
1. Instaleaza JDK 17.
2. Descarca Forge MDK 1.20.1-47.3.0 (files.minecraftforge.net) si copiaza din el `gradlew`, `gradlew.bat` si folderul `gradle/` in acest proiect.
3. `gradlew build`  ->  `build/libs/mooncityx-1.20.1-1.0.0.jar`
4. Pune jar-ul in `mods/` (client + server).

## Iteme
`/give @s mooncityx:phone`  |  `/give @s mooncityx:jbl`

## Comenzi
- Jucatori: `/claim` `/unclaim` `/plot add|remove <nume>` `/plot list` `/waypoint <x> <z>` `/waypoint clear`
- Admin: `/plot pos1`, `/plot pos2`, `/plot create <nume>`, `/plot delete <nume>`
         `/zone create <nume> bad|city` (pos1/pos2 la fel), `/zone delete|list`
         `/mafia create|delete|add|remove|list`, `/police add|remove <nume>`, `/bank give <nume> <suma>`
- Politie: `/mdt`
