## Attemption
[Dimbreath/GenshinData](https://github.com/Dimbreath/GenshinData) has been DMCA takedown by miHoYo / Hoyoverse. I will temporarily archives this project util found new soruce. 

Thank you everyone use this project 🙏

M-307

# EnkaNetwork.py (JSON Data)
Repository for fetch data from [Dimbreath/GenshinData](https://github.com/Dimbreath/GenshinData) to use [EnkaNetwork.py](https://github.com/mrwan200/EnkaNetwork.py) python library.

## ❓ Why not use EnkaNetwork store data?
I want some data like Skill name, Constellations data fully, FIGHT_PROP name but In EnkaNetowork prepare not fully served data. So I have to make this.

## ❓ How you fetch raw JSON data?
I fetch JSON data from repo [Dimbreath/GenshinData](https://github.com/Dimbreath/GenshinData)

## ❓ How to get export data?
Yon can see in [exports](./exports/) folder.

## ❓ How do I know this repo has been updated?
In every 00:00 (UTC+7) data will fetch last commit from [Dimbreath/GenshinData](https://github.com/Dimbreath/GenshinData) 
and check if commit is different from last commit. If different, it will update data take a 3 - 5 minutes to update data.

## ❓ Why avatar id has "10000005-503" or "10000007-702"?
In default character player. It's can't be to detect what is character element? so I join AvatarID and ElemenetID (candSkillDepotIds) like picture this:

![ID-ELEMENTS](./ID_ELMENTS.png)

And yeah, I use pattern to detect character element. from repo [EnkaNetwork/API-docs](https://github.com/EnkaNetwork/API-docs) store 😅.

## ❓ Can I use this repo for something else?
Sure.

## ❓ How to link character data like skill, talents and more?
You can see in picture this:

![LINKING CHARACTER](./CHARACTERS.png)

# Enjoy
![KEQING](https://c.tenor.com/6pJ6hH78tq8AAAAM/smol-keqing-what.gif)