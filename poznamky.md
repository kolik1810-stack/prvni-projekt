# Co jsem se dnes naučil

## Git
- Git je systém pro správu verzí: zaznamenává historii změn v souborech.
- Repozitář vznikne příkazem `git init`; skrytá složka `.git` obsahuje celou historii.
- Větev (branch) je samostatná linie vývoje. Hlavní větev se dnes obvykle jmenuje `main` (dříve `master`).
- Větev přejmenuji příkazem `git branch -m main`.
- Výchozí název větve pro nové repozitáře nastavím globálně: `git config --global init.defaultBranch main`.
- `git status` ukáže stav pracovní složky, `git commit` uloží změny do historie.

## Claude Code
- Claude Code je AI asistent pro programování, který běží v terminálu nebo v aplikaci.
- Umí číst a upravovat soubory, spouštět příkazy a pracovat s gitem.
- Pracuje v rámci pracovní složky projektu a využívá nástroje (čtení, zápis, shell).

## Režimy oprávnění
- Určují, co smí Claude dělat bez ptaní a co vyžaduje schválení.
- Zamítnutí akce znamená, že ji uživatel odmítl. Claude pak zvolí jiný postup.
- Čím přísnější režim, tím větší kontrola nad změnami, ale víc potvrzování.

## Plan mode
- Režim, ve kterém Claude nejdřív navrhne plán a teprve po schválení něco mění.
- Hodí se u větších nebo rizikových úprav, kde chci vědět, co se bude dít.
- V plánování může klást doplňující otázky, aby si ujasnil zadání.

## T3 Code
- Aplikace, ve které Claude Code běží a která nabízí rozhraní s vlákny (threads).
- Umí pracovat s projekty, pracovními stromy (worktrees), náhledy a delegováním úkolů.
