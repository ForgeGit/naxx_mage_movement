# Mage movement by boss - Naxx 25 man Wrath of the Lich King

This is a somewhat extensive analysis I did on mage movement for Naxx 25 bosses some time ago.

I won't go into too many details of how I processed/extracted/cleaned data due to time, but feel free to ask me for any specifics or the raw/processed data to recreate this graphics (or verify them).

# Table of Contents
1. [SPACE](#hardmodes-wipes-and-kills-) <br>
        1.8. [SPACE](#algalon-)<br>
        1.9. [SPACE-0](#yogg-0-)<br>
2. [SPACE Tables](#overall-tables---boss-encounters-)<br>
3. [SPACE](#methodology-)<br>
        3.1 [SPACE](#hardmode-classification-)<br>
        3.2 [SPACE](#limitations-)<br>
## Average movement per boss

"Movement" of a mage is being measured as the total distance you moved during the encounter, measured on every action you do. 

idk on what units this distance is measured, yet, and these measurements aren't "adjusted for" blink usage, whether you were casting while moving or not,  or if you had a good parse/speed or encounter duration. However, it is (now) excluding those who died during the encounter.

Each encounter (boss) is ordered from those who had, on average, higher movement vs those who do not.

It is nice to see that what we know as a "patchwerk fight" (basically, sim conditions of a standstill tank and spank fight) can be perfectly seen and measured with irl data.

<img src="img/preview_v5_scaled_again.png" />

## Movement top 100 parses

The following plot measures the same "movement" metric, this time with the 100 top parses per boss at the time

<img src="img/plot3_v2.png" />

Using the same y-axis scale as the first graphic, and ordering each boss, we get the following

<img src="img/plot3_v1.png" />

Comparing both we can see top parses, on average, had considerably less "movement" during the encounter.

## Ok, and?

This in practice allows you to measure your movement vs the movement of the "average" mage or the "average top 100" mage. Or simply, quantify how much movement there is on each boss (which is important to know in order to minimize downtime as a caster)

Here we have a log of "Ntx", who had a really high parse on his encounters

<img src="img/preview_v4_Ntx.png" />

Here we have a log of "Epiloof", who had a speedrun. He parsed high for each encounter, however, he had to move a lot more because the aim of the run was the speed metric.

<img src="img/preview_v4_Epiloof.png" />

# Other analysis done

- Check other things I have done here: https://github.com/ForgeGit?tab=repositories

