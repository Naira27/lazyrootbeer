## Tera proxy module which automatically uses brooch and or rootbeer.

---

## Skillconfiguration
- `useoutofcombat:` [Here you can choose if the module should only work in combat mode or out of combat too].
- `userootbeeron:` [Put the desired skill id in here where you want the module to take effect].
- `usebroochon:` [Put the desired skill id in here where you want the module to take effect].
- `delay:` [Delay in milliseconds between using the skill and using brooch and or rootbeer].

Skillconfiguration file can be found under this path /Additional-Data/Skillconfiguration/skills.json in the modules folder.

---

## Console Command
- Type `/8 lazybeer` to enable or disable auto use of brooch and or rootbeer function. Enabled by default.
- Type `/8 lazydebug` to enable or disable debug function for setting up the module. Disabled by default.
- Type `/8 lazyworld` to enable or disable the zone restriction function. Enabled by default.
    - Enabled is that brooch and or rootbeer will be used everywhere in the game.
	- Disabled is that brooch and or rootbeer will only be used in dungeons.

---

## Interface Command
- Type `/8 lazyconfig` to enable or disable the functions written above.

---

## Skillinfo
- Debug command listed above.
- [Teralore Database](https://teralore.com/en/skills/)

---

## Note
- An list of the default dungeons which are currently added in the dungeons.json file can be found here [Skill Overview](https://github.com/Tera-Shiraneko/lazyrootbeer/tree/master/Additional-Data/Dungeonoverview).
- An list of the default skills which are currently added in the skills.json file can be found here [Skill Overview](https://github.com/Tera-Shiraneko/lazyrootbeer/tree/master/Additional-Data/Skillconfiguration).
- If you got multiple skill id's it will use brooch and or rootbeer on the first skill you use.
- I don't play every class so it's possible you have to edit the skills.json file manually.
	- Which can be found under the path written above.