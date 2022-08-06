# Oath calculator

Shameless copy from [rocalc.com](https://www.rocalc.com) adapted for OathRO

## Objective

- Change every javascript file to a typescript file
- Add typing
- Make the code readable
- Add enums and populate them on the code to get a better understanding (race: 0 is Race.Formless)
- Make it easy to add new mobs, items and maps

## How to start developing
```
npm install
npm run dev
```

## Pending modifications
!!! This list is incomplete
### Class rebalance (wiki page from top to bottom)
- Knight
    - ~~Bowling bash new damage formula~~
    - Check brandish spear damage

- Crusader
    - ~~Spear quicken new formula~~

- Acolyte
    - ~~Demon bane new stats~~
    - Holy light new formula and cast time (can't seem to find this calculation at a first glance)

- Priest
    - ~~Battle mastery new formula~~ and add aspd +12% if skill is lvl 10 (don't know how to apply it correctly, maybe at the same time as spear quicken calculation ?)
    - ~~Turn undead new damage on failure formula~~
    - ~~Remove slow poison skill~~
    - Add renew skill ? (has no effect, just heals and stops the heal reduction of poison)

- Monk
    - ~~Dodge new flee formula~~
    - Mental strength new formula
    - ~~Iron fists new formula~~
    - Iron fist extra aspd increase
    - ~~Raging quadruple blow damage increase by 30%~~
    - ~~Raging thrust damage increase~~ (and 15% attack buff ?)
    - ~~Throw spirit sphere new formula~~

- Hunter
    - ~~Blast mine new formula~~
    - ~~Land mine new formula (can't seem to find this calculation at a first glance)
    - Freezing trap new formula
    - ~~Claymore trap new formula~~
    - ! These traps damage can be increased by some cards, investigate how to implement this correctly

- Bard/Dancer
    - Musical lesson increase attack by 5 and add 1% aspd per lvl
    - Dancing lesson increase attack by 5 and add 1% aspd per lvl
    - Throw arrow new formula
    - Musical strike new formula

- Wizard
    - Add sense to skills and calculate it's 2% reduction
    
- Sage
    - Add sense to skills and calculate it's 2% reduction
    - Advanced book new formula and +1% matk per lvl
    - Investigate auto spell new changes and how to implement them in the battle calculation

- Thief
    - Double attack increased chance
    - Envenom new formula

- Assassin
    - Right hand mastery increase values
    - Left hand mastery increase values
    - Enchant poison increased chance ?
    - Katar mastery +1 atk per lvl and 0.5% crit per lvl

- Rogue
    - Strip skills affect combat on the calculator ?
    - Sword mastery now has double attack chance
    - Back stab cast delay
    - Raid new formula

- Merchant 
    - Cart revolution always does max damage, remove weight input

- Blacksmith
    - Skin tempering new formula

- Alchemist
    - Axe mastery +5 atk and +0.8% aspd per lvl

- Super novice
    - Extra HP and SP calculations