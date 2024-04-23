# 2023-l4-web-mockupapp-VeronikaLatova
2023-l4-web-mockupapp-VeronikaLatova created by GitHub Classroom
## Habit Journeys
Aplikace "Habit Journeys" slouží k trackování týdenních cílů, týkajících se zdravého životního stylu. Není jen tak ledajaká, celá je zasazená do fantasy prostředí, které uživatele motivuje plnit své cíle. Z povinností se stane dobrodružná hra, která dokáže zvýšit produktivitu (i vy musíte samozřejmě něco dělat, aplikace není schopná za vás uběhnout 5 km).

Jsou zabudovány kategorie činností, které se mohou zaznamenávat. Je to velmi jednoduché, proto je kategorií jen pár: pohyb, zdravá strava, pitný režim, vzdělání a skills, relax, čas v přírodě, kvalitní spánek. Aplikace je vhodná pro ty, kteří si chtějí zlepšit svůj životní styl zajímavějším způsobem.
**[Odkaz na Figmu](https://www.figma.com/file/aKpfvcfIHLjfjn9RtpMse4/Habit-Journeys?type=design&node-id=0-1&mode=design&t=6LlAr8usJtDieCb0-0)**


## Aplikace má několik sekcí (stránek) a to:

### Mainpage (My progress): 
Hlavní stránka, na které se uživatel objeví po otevření aplikace. Na této stránce je vidět progress uživatele s jeho aktivitami, na kterých momentálně pracuje (to se pohybuje v týdenních cyklech). Jedná se totiž o návyky, které si uživatel stanovuje na týden. Jakmile uživatel splní aktivitu, klikne na checkbox, potvrdí svou volbu a kolečko se naplní o určitý kus.

![image](https://github.com/pslib-cz/2023-l4-web-mockupapp-VeronikaLatova/assets/107682367/e233b9ed-23a8-4aa0-a54c-a91edb7a3c14)

![Group 17](https://github.com/pslib-cz/2023-l4-web-mockupapp-VeronikaLatova/assets/107682367/ab89f8be-e3c4-4b03-b72a-d786a4880fa0)

Prázdná stránka vypadá takto:

![My progress - blank page (1)](https://github.com/pslib-cz/2023-l4-web-mockupapp-VeronikaLatova/assets/107682367/e8d2a570-d6e4-44ed-b29f-71d2f76e4fe6)


Na stránce "My progress" se jednotlivé kruhy s aktivitou dají také rozkliknout. Uživatel vidí zpětně co si zadal za konkrétní cíl (čemu se přesně věnuje, kolikrát týdně a jeho motivace). Tato stránka je skoro stejná, jako u zadávání nového cíle, ale má upravená některá slova a chybí tlačítko "done". Místo toho je tam tlačítko "delete", pokud by uživatel chtěl aktivitu smazat.

![My progress - click](https://github.com/pslib-cz/2023-l4-web-mockupapp-VeronikaLatova/assets/107682367/1acaf04d-44e0-40ad-8e36-eb63e984226b)

![My progress - click - delete activity](https://github.com/pslib-cz/2023-l4-web-mockupapp-VeronikaLatova/assets/107682367/1a51c63e-af82-41be-9b25-0dfd17cbfd91)


Co se týče kruhu a jeho naplňování - je rozdělen na úseky podle čísla, které si uživatel stanovil při zapisování nového habitu. Jakmile uživatel dosáhne celého žlutého kruhu, aktivita se ukáže jako dokončená a objeví se v awards jako splněná. Pokud uživatel udělal během měsíce aktivitu vícekrát (což je očekáváno), u daného ocenění se objeví číslo podle toho, kolikrát je aktivita již dokončena. 

![Výstřižek](https://github.com/pslib-cz/2023-l4-web-mockupapp-VeronikaLatova/assets/107682367/92384734-1e6c-4e0b-af9e-e0ee22c2a6a6)

Aktivitu ale během týdne nelze začínat vícekrát. Jakmile ji uživatel jednou má v progressu, ze stránky "New activity" zmízí a není možno ji mít vícekrát než jednou v "My progress". Optimální pro uživatele tedy je vypsat si veškeré cíle týkající se dané aktivity (např. běh i posilování), sečíst, kolikrát bude aktivitu dělat (např. běh 2x, cvičení 3x) a zadá výsledné číslo (tedy 5) do pole "How many times a week am I willing to improve?".

### Achievements and awards:
Stránka s oceněními získanými za poslední měsíc. Stránka se vyčistí právě jednou měsíčně.

![Achievements](https://github.com/pslib-cz/2023-l4-web-mockupapp-VeronikaLatova/assets/107682367/18c40303-cfb3-45fa-82af-261059546437)

Pokud uživatel zatím nemá žádná ocenění, ukáže se obrazovka s "No achievements yet. Keep going!".

![Achievements - blank page](https://github.com/pslib-cz/2023-l4-web-mockupapp-VeronikaLatova/assets/107682367/e7983eec-9f41-4290-b500-23b2dc3dc619)

Seznam všech ocenění je na stránce "List of awards".

![Possible awards](https://github.com/pslib-cz/2023-l4-web-mockupapp-VeronikaLatova/assets/107682367/341b4204-7a06-41e3-a9d9-bba9aaca51b1)


### My motivation:
Motivace uživatele v průběhu zadávání aktivit. Uživatel si může zpětně přečíst, co ho motivovalo danou aktivitu plnit. Do této sekce se zaznamenává motivace za celou dobu používání aplikace. To, jestli si uživatel napíše něco k motivaci, je na něm.

![My motivation](https://github.com/pslib-cz/2023-l4-web-mockupapp-VeronikaLatova/assets/107682367/2e9b3ba3-47cc-4d7e-9113-171412edb9cb)


### Setting a new habit:
Zadávání nového cíle - tato stránka se zobrazí po kliknutí na jednu z aktivit, ve které se chce uživatel zlepšit. Uživatel vyplní, kolikrát týdně se chce aktivitě věnovat, co přesně chce dělat a může (nemusí) napsat motivaci. Po uložení (při ukládání) nového cíle se zobrazí obrazovka s "New goal set!". Po zadání aktivity se uživatel objeví opět na mainpage (progress) stránce, kde se již zobrazí nově zadaná aktivita, zatím bez žlutého progressu (logicky).

![obrazek](https://github.com/pslib-cz/2023-l4-web-mockupapp-VeronikaLatova/assets/107682367/00d1e804-dd55-4ccf-8926-84c0a16a6606)


![Setting a new habit](https://github.com/pslib-cz/2023-l4-web-mockupapp-VeronikaLatova/assets/107682367/b11cf5b2-7ff5-457c-b9ff-11649bb2bbff)


![Set goal](https://github.com/pslib-cz/2023-l4-web-mockupapp-VeronikaLatova/assets/107682367/2d109e90-546d-44a7-a84d-1965c4880403)


### Settings:
Nástřel možného vzhledu a obsahu nastavení. Detaily v nastavení jsou jen pro pokročilé a zaujaté jedince, kteří by měli s aplikací vážnější účely. Pokud by někdo chtěl projekt opravdu rozjet a hodně doladit, kdyžtak mě kontaktujte na emailu: latova.verca@seznam.cz a třeba se domluvíme (:D)

![Settings](https://github.com/pslib-cz/2023-l4-web-mockupapp-VeronikaLatova/assets/107682367/30a64dbc-a24b-4d11-915b-444f63ee6fdd)


### Vizuál a barvy
Vývojář může zvolit využití barev, jak se mu zalíbí. Ve Figmě se nachází doporučená paleta barev, které by se mohly k projektu hodit. Já pro tento projekt ponechám jednoduchý a čistý design.


![image 1](https://github.com/pslib-cz/2023-l4-web-mockupapp-VeronikaLatova/assets/107682367/a88e2cf4-eda6-4bf6-8400-6d5782c9bc81)

### Font
Použitý font písma je Lexend. Podrobnější informace jsou ve Figmě (o tom, jaké písmo je tučně a jaké normální či tenké).

### Přehled ocenění, činností a textů při zadávání aktivity
Je zde také přiložena excelová tabulka "Awards, habits and text", kde jsou vypsané vysvětlivky a podrobnosti aktivity (např. že fighting skills = workout and movement).

### Obrázky
Obrázky jednotlivých aktivit jsou ve složce "images", kde jsou i korektně pojmenovány.

### Menu
Uživatele po celou dobu používání provází jednoduché menu, přičemž je žlutou barvou vyznačena ikonka stránky, na které se nachází.

Pro lepší orientaci v projektu a jeho stránkách se stačí podívat na Figmu, kde je vše přehlednější. Dokonce je přidán i stručný prototype pro jasnější pochopení.
