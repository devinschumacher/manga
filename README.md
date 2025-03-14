# README

Prompt to chat:


## OVERVIEW

You will be provided a screenshot from a manga (Japanese comic). It may be written in hiragana, katakana, kanji, or a combination. Your task is to perform a series of translation steps to help an English speaker who is a beginner at learning Japanese have an easier time reading, learning & understanding Japanese through mangas.


## INSTRUCTIONS

For the provided screenshot, perform each of the following tasks:

1. ORIGINAL: Write the original message from the screenshot
2. KANA: Write the kana version (aka, convert the kanji into hiragana for readability)
3. ROMAJI (letters): Write the kana character + romaji character side by side (so it is easy for a beginner to learn each character)
4. ROMAJI (words): Write the romaji words
5. TRANSLATION (literal): Write the literal English translation of each word (so the English reader can feel the "Japanese intent" behind it) and then the sentence. This keeps the word order and feeling close to the original Japanese, helping English readers get a sense of how the sentence is structured in Japanese thinking.
6. TRANSLATION (natural): Write the natural English translation based on the context (so the English reader can understand what it probably best translates to)
7. COMBINED: Put it all together into a markdown table
8. EDITORIAL: Add in any helpful editorialization about the scene that helps the reader understand it, or learn something more about Japanese


## EXAMPLE

In this example, the provided screenshot had the following writing:
```
あー
怪物のなかから
へんな妖怪が
でた！
```


Your response should be formatted similar to this:

1. ORIGINAL 
```
あー
怪物のなかから
へんな妖怪が
でた！
```

2. KANA
```
あー
かいぶつのなかから
へんなようかいが
でた！
```

3. ROMAJI (letters)
```
あー    aー  
か    ka  
い    i  
ぶ    bu  
つ    tsu  
の    no  
な    na  
か    ka  
か    ka  
ら    ra  

へ    he  
ん    n  
な    na  

よ    yo  
う    u  
か    ka  
い    i  
が    ga  

で    de  
た    ta  
！   
```

4. ROMAJI (words)
```
あー             ā  
かいぶつ       kaibutsu  
の              no  
なかから       nakakara  

へんな         henna  
ようかい       yōkai  
が              ga  

でた           deta  
！  
```

5. TRANSLATION (literal)
```
あー             ā            → Ah—  
かいぶつ       kaibutsu      → Monster  
の              no           → (possessive: "of" / "from")  
なかから       nakakara      → From inside  

へんな         henna         → Strange / Weird  
ようかい       yōkai         → Yokai (supernatural creature)  
が              ga           → (subject marker: "a" yokai)  

でた           deta         → Came out / Appeared  
！  

# “Ah— from inside the monster, a weird yokai came out!”
```



6. TRANSLATION (natural)
```
"Ah! A weird yokai just came out of the monster!"
```

7. COMBINED
```
| Japanese | Romaji     | Translation (literal)          | Translation (natural) |
|-----------------|-----------|-------------------------|----------------------|
| あー           | ā         | Ah—                      | Ah!                 |
| 怪物 (かいぶつ) | kaibutsu  | Monster                 | A monster           |
| の             | no        | (possessive: "of")      | of the              |
| 中から (なかから) | nakakara | From inside             | came out of         |
| 変な (へんな)   | henna     | Strange / Weird         | A weird             |
| 妖怪 (ようかい) | yōkai     | Yokai (supernatural being) | yokai               |
| が             | ga        | (subject marker: "a")   | (implied subject)   |
| 出た (でた)    | deta      | Came out / Appeared     | just came out       |
| ！             | !         | (Exclamation)           | !                   |
```

8. EDITORIAL

In this scene, Goku is surprised to see a "weird yokai" coming out of a monster, which suggests it’s some kind of unusual or unexpected supernatural creature!

In modern media (like anime and manga), yokai are often depicted as fantastical beings with supernatural abilities, sometimes scary and sometimes comedic.

The term can refer to many kinds of mysterious beings, including ghosts, demons, goblins, and even shape-shifters.

**Some famous examples of yokai include:**
- Kappa (河童) – A water-dwelling creature that can be mischievous or dangerous.
- Tengu (天狗) – A long-nosed, bird-like creature often associated with mountains and martial arts.
- Kitsune (狐) – A fox spirit known for its intelligence and ability to shape-shift.
- Oni (鬼) – Large, ogre-like demons that often appear in myths and legends.

