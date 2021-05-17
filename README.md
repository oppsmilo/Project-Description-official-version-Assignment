# Project-Description-official-version-Assignment
describe my 2D game project in detail
---------------------------------------------------
To make 2D game which has a charactor can move and attack monsters.
object sketch:https://github.com/oppsmilo/Project-Description-official-version-Assignment/blob/main/object%20sketch.pdf

illustrate plan:

(1)charactor:
             1.only one performance,
             2.doesn't has ability value.
             3.when charactor per level up(highest lv is 5),and him  earn a new skill.

(2)level(關卡):
               1.total 4 levels,there are normal monsters in 1~3 levels,level 4 has boss.
               2.one scenes only has one equipment,you finish this game after you defeat the boss,
               you still can go back to level 1 to level 4.

(3)monsters:
            1.automatically move to the player until die.
            2.after monster be killed,which has posibility to generate a equipment.
            3.when monsters touch player,whose hp lower.
--------------------------------------------------------------------------------------------------------------
what to do:                                                                          how to do:
                                                                                    
(1)charactor:                                                                         
             1.get keyboard .                                                        |finished GetKey(KeyCode.arrow)
             2.body shaking when move or attack.                                     |animation control
             3.when change left and right arrow,contral charactor facing director.   |code
             4.jump must be attached floor.                                          |finished
                                                                                     |
(2)monster:                                                                          |
           1.when change left and right arrow,contral monsters facing director.      |code
           2.automatically move to the player.                                       |code
                                                                                     |
(3)boss:                                                                             |
        1.automatically move to the player.                                          |code
        2.release skills at regular intervals.                                       |code
        3.if hp drop to fixed value,strengthen skill.                                |code
----------------------------------------------------------------------------------------------------------------
needed but unknown(continued search information)
1.scense swich
2.music and copyright
3.GUI method
