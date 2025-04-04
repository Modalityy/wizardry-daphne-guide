# Arboris

**Race**: Elf  
**Gender**: Male  
**Type**: Earth  
**Personality**: Neutral  
**Starting Class**: Thief  
**Class Change**:  
**Role**: Support, Damage

!!! info "Portraits"
    === "Thief"
        ![](../img/arboris-thief.png)

## Skills

!!! info "Unique Skill (Inheritable)"
    === "Astral Break"
        Major earth type physical attack on 1 enemy. Bypasses Defense Power and increases Action Speed of user and allies in front of or behind for 3 turns. Efficacy, Defense Power bypass rate, and Action Speed effect turns are reduced if learned by someone other than Arboris.

!!! info "Unique Skill (Not Inheritable)"
    === "Lord of the Deep Forest's"
        Increases Evasion and Action Speed for user and all adjacent evil and neutral allies.

!!! info "Discipline Skill"
    === "King's Disposition"
        Continuously increases each stat, Accuracy and Stun Tolerance increased further.

## Adventurer Reviews

!!! info "TheAxolotl's Analysis"

    Arboris is our very first limited legendary thief and he is currently broken. I don't mean that in a good way, as there is some really funky behavior going on with his skills.

    First, neither `Lord of the Deep Forest's` nor `Astral Break` seem to actually be changing turn order when applied as expected. It's possible that this is due to the mechanics of how turn order is calculated based on action speed, but it's also possible that it's bugged.

    Second, `Astral Break` is currently bugged with multi-hit weapons and can result in acting as a buff purge for both the user and the party member in front or behind. I'll get to the why in a bit as I talk about the skills themselves.

    `Astral Break` is a major attack skill, which is great. It hits hard and provides a solid damage option for thieves. It's very costly SP-wise, at 20 SP for level 1, and being an elf, he already has a smaller SP pool than Debra, who is going to be his most common competitor. The actions speed buff counts as a buff like you would expect, so it is subject to the 3 buff limit. The issue comes in when it actually knocks buffs off the stack. This is likely a bug, but every hit that this still lands counts as a buff being applied. So if you use this skill with a 1-hit weapon, it gets treated as applying 1 buff, which is expected. If you use this skill with a 2-hit or a 3-hit weapon, it gets treated as applying 2 or 3 buffs respectively, however it only actually applies a single buff icon. This is very problematic, as if you have a buff combination of something like `MACALDIA` and `Warrior's Battle Cry`, using this skill while being in front of or behind the adventurer with three buffs will cause 2 (or all 3 with Cuisinart) buffs to be removed and replaced with a single action speed buff.

    `Lord of the Deep Forest's`, outside of being grammatically weird, at a glance seems like solid evil and neutral support, however it also has some issues. First and foremost is that for the two skills being buffed, it is very hard to evaluate the effectiveness of the buffs. It is a Synergy that behaves similar to Rinne's Surety boost, always applying to him and extending to others that meet the criteria. Since it is a Synergy, that means we are unable to see the exact amount being modified, so it's a bit of a guess to know if it's even providing value.

    I'm generally not a big fan of Discipline skills to begin with, so this will be short - in general, `King's Disposition` is absolute garbage as far as Discipline goes.

    Assuming they fix his bugs, I'm still not very impressed with `Lord of the Deep Forest's`. My big issue with it is that I don't see the passive buff being large enough to make a massive impact. The main scenarios I can picture are:
    
    - You are perfectly speed-tuned to go ahead of most enemies you face and your buffers/debuffers always go before your damage dealers
        - In this scenario, gaining some passive ASPD won't do much for you since it won't change your turn order and it won't make you outspeed enemies more than you're already outspeeding them
    - You have not spent much if any effort on speed tuning your party but you have made it so your party always goes before most enemies
        - In this scenario, the ASPD could be nice, but you probably won't notice much of an impact since you aren't too worried about your party's turn order
    - You have speed tuned your party to go in the order you want but some of your party is still being outsped by enemies
        - In this scenario, you might see some benefit, as the ASPD gains could be enough to finish getting your party going before the enemy, however it'll be variable based on the enemies you face

    In addition, the passive gains are likely not going to be enough to help most players outspeed dangerous enemies such as Vampries.

    There is the possibility that his active skill is supposed to behave like `PORTO` on himself and the adventurer in front or behind him. In this case, there can certainly be some conditional uses for it, however you'd have to be very aware of your party formation and the implications of making just two of your party move faster than the rest.

    In general, having conditional in-battle action speed adjustments can really mess with optimized speed tuning in your equipment if you're not very sure of what you're doing. If you want to really mess with speed turning during a battle, using `BATILGREF` and `PORTO` will likely be both sufficient and a bit more consistent for most players.

    * Pull if:
        * You like Arboris as an adventurer
        * You want a thief to be able to hit water content hard
    * Do not pull if:
        * You do not like Arboris as an adventurer
        * You want to wait to see how or if his bugs get fixed
        * You don't want to mess with conditional in-battle speed tuning
        * You want to save for future, more impactful adventurers
    
## Duplicate Usage

* Increase the efficacy of his Astral Break
* Discipline to get very minor stat boosts