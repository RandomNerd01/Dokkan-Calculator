# Dokkan Defense Calculator

Instead of hardcoding a multiplier for every unit in the game(Too tedious), I used Python to search through DokkanInfo.com and search through the html file of characters. There, I then find patterns in the HTML file that automatically determine the passive and
calculates the multipliers automatically

## WIP

Characters that Nuke with a certain Type of Ki Sphere instead of general Ki Spheres is not worked into the calculator. (Eg: All 50% type supports)

Currently only shows characters' defense stats when fully built up.

Characters that get Defensive Buffs from being put in a certain slot is not worked into the calculator. (Eg: Int DFE Piccolo Jr)

Certain Characters like int dokkanfest ssj Vegeta(GT) gets their base defense multipliers messed up because they get different percentages both in same line of text

Characters that get multipicative stats per attack or super attack performed in their passive is not worked into the calculator. (Eg: Phy 23rd WT Tien)

## Steps

1)Input Character ID from DokkanInfo


![image](https://github.com/Suiron99/Dokkan-Calculator/assets/142955018/0563585b-4bfb-4f77-857f-8c79e7f97f0e)


2) Input Hidden Potential Defense



![image](https://github.com/Suiron99/Dokkan-Calculator/assets/142955018/073f9e1d-df0f-48bf-846a-1d97658b7294)

3) Optional (Active Skill Defense Buff)
For example, image below 1.58 is representing the 158% Def Buff that LR STR Beast Gohan gets for the Turn.



![image](https://github.com/Suiron99/Dokkan-Calculator/assets/142955018/4779fcd9-127f-43cc-bedb-5e52914ed4a4)


4) Optional (Support Units)
Amount of Support on Rotation(For example, image below represents the 40% Support provided by the LR Gamma 1 & Gamma 2)



![image](https://github.com/Suiron99/Dokkan-Calculator/assets/142955018/3ecc00a1-0259-4b03-8dcf-50a3a1ca4a80)



5) Nuking Passives
Amount of Ki Spheres Obtained by character during the turn. If character has a nuking passive, this will lead to higher defense.



[![Damage points](![image](https://static.wikia.nocookie.net/99c1f08c-645e-4f3f-a08c-d696cbd191ac/scale-to-width/755)
)](https://youtu.be/dExsxVgGntg "Damage points")


![image](https://github.com/Suiron99/Dokkan-Calculator/assets/142955018/4779fcd9-127f-43cc-bedb-5e52914ed4a4)





6) Gives you Final Defense Stat



![image](https://github.com/Suiron99/Dokkan-Calculator/assets/142955018/ba90694b-c956-49b9-a5e7-c5bf8ca31e48)



## Stacked Defense
1) If a Character Stacks Defense(Multiple turns or permanently)



![image](https://github.com/Suiron99/Dokkan-Calculator/assets/142955018/42dfe108-6ff2-42a4-bdb5-d4b163b316be)



2) Stacks Defense on Which Super


![image](https://github.com/Suiron99/Dokkan-Calculator/assets/142955018/9e942248-9802-44a0-baf4-f4eb6550e7fa)



3) How Much Defense Stacked Per Super(Image below shows a normal "Raises Def")
   

![image](https://github.com/Suiron99/Dokkan-Calculator/assets/142955018/b6a18b71-7207-461c-8cbe-7bb4759eba93)




4) How Long Stacks Last(Multiple Turns or Permanent)



![image](https://github.com/Suiron99/Dokkan-Calculator/assets/142955018/9f59c71a-d218-4516-9e8e-86382a948ead)



### Temporary Stacks of Defense
1) Did u Float Character off? (Did u put Character in the 3rd slot in prior rotations?)


![image](https://github.com/Suiron99/Dokkan-Calculator/assets/142955018/e1bf1855-2e25-4784-9ffa-e43fd31cd257)



2) Because I Chose "Floated off" option and I chose my SA effect to last for 5 turns, code will automatically determine that only previous appearance has stacks that translate to this turn

   

![image](https://github.com/Suiron99/Dokkan-Calculator/assets/142955018/e34e1acb-886f-42fb-80d8-6d2dddb988e1)



2.5) Similarly if I choose "Not Floated off" and I chose my SA effect to last for 7 turns, code will automatically determine that 3 previous appearances has stacks that translate to this turn




![image](https://github.com/Suiron99/Dokkan-Calculator/assets/142955018/11d8009a-f682-44f0-ab77-179900c11ef6)






### Permanent Stacks of Defense






1) Number of 12-ki Supers During Current Turn and 12-ki Super SA Multiplier


![image](https://github.com/Suiron99/Dokkan-Calculator/assets/142955018/9b34687d-0f69-4c49-9f35-318db7387fa9)




2) Whether Character Performed 18-ki or Unit-Super and its SA Multiplier



![image](https://github.com/Suiron99/Dokkan-Calculator/assets/142955018/e3742f23-2d35-481c-8eb7-334d5320738b)



2.5) If character doesn't Perform 18-ki or unit super, it skips past asking SA multiplier

![image](https://github.com/Suiron99/Dokkan-Calculator/assets/142955018/02e4f3a5-2312-47fc-9d96-442ed70c94dd)









