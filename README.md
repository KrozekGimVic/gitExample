# gitExample
Osnovna spletna stran (html, css), ki jo bomo uporabljali za učenje gita. 

## Prvi del

1. Ustvari Github račun (če ga še nimaš)
2. Lokalno nastavi svoj name in email z ``git config --global``
3. Forkaj ta repozitorij, nato lokalno kloniraj svoj fork
4. Na spletni strani je veliko slovničnih napak, najdi in popravi kakšno
5. Preveri svoje spremembe z ``git diff`` 
6. Commitaj spremembe s slabim commit messageom
7. Popravi commit message z ``git commit --amend``
8. Spremeni še nekaj stvari, ugotovi, da dejansko ne želiš teh sprememb, in jih resetaj (tako cel repozitorij kot file-by-file)
9. Daj pull request
10. Posodobi svoj pull request potem, ko se zgodijo spremembe v tem repozitoriju
11. Počakaj, da je tvoj pull request sprejet ali zavrnjen

## Drugi del (v parih)

1. En v paru naredi prazen github repozitorij (z README), da vse pravice drugemu
2. Oba sklonirata repozitorij
3. En naj v README napiše ime in priimek obeh, drugi šolsko leto in šolo -- tekmujeta, kdo bo prej commital in pushal
4. Počasnejši mora pullat (lokalne unstaged spremembe je treba commitati, stashati ali resetati) in razrešit konflikte, preden lahko pusha
5. Vsak naredi nov branch
6. Vsak na svoj branch v repozitorij doda neko sliko po želji in jo doda v README
7. Vsak pusha svoj branch in odpre pull request
8. Nekdo prek githuba popravi README na master branchu
9. Oba poskusita mergat svoj pull request v masterja, a ne gre
10. Naredita rebase in mergata -- tisti, ki je počasnejši, mora še enkrat rebasati
11. Pogledata zgodovino z ukazi ``git log --stat --summary``, ``git log --graph`` in ``gitk``
12. Pogledata spremembe v nekem commitu z ``git show``
