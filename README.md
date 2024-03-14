# Ako commitnut
Príklad toho ako commitnúť na GITHUB

## Príklad úplne nového repozitára

**Na stránke Githubu:**
1. Otvorte stránku `https://github.com/`
2. V lavom bočnom panely najdete **zelenú ikonku NEW**
3. Zadajte názov vašeho repozitáru a stlačte **CREATE REPOSITORY**
4. Skopírujte https link
5. Pokračujte na vašom PC

**Na vašom PC**
1. Otvorte folder v ktorom máte projekt
2. Spustite Git Bash `right-click` na prázdne miesto vo foldery
3. Inicializujte Git - `git init`
4. Git pracuje lokálne takže si ho musíte prepojiť s GitHubom - `git remote add origin sem-skopírujte-https-link`
5. Pridajte súbory ktoré chcete uložiť, bodka znamená všetko - `git add .`
6. Vytvorte commit čiže save verzie - `git commit -m "niaky výstižný názov"`
7. Pošlite commit na github môžte použiť **master** alebo **main** - `git push origin master` 
8. Otvorte váš repozitár na GitHub a reloadnite, uistite sa, že vaše zmeny boli úspešne pushnuté.

## Príklad commitu do existujúceho repozitára

**Na stránke Githubu:**
1. Otvorte stránku `https://github.com/`
2. Nájdite existujúci repozitár do ktorého chcete pushnúť
3. Kliknite na zelené tlačidlo **CODE**
4. Skopírujte https link
5. Pokračujte na vašom PC

**Na vašom PC**
1. Nájdite miesto kam chcete vložiť skopírovaný folder/projekt
2. Spustite Git Bash `right-click` na prázdne miesto vo foldery alebo vo vybranom priestore
3. Vložte skopírovaný folder - `git clone skopírovaný-https-link`
4. Vstúpte do skopírovaného foldera - `cd meno-foldera`
5. **Teraz môžte robiť zmeny so skopírovaným projektom**
6. Ak ste so zmenami skončili - `git add .`
7. Vytvorte commit - `git commit -m "niaky výstižný názov"`
8. Pošlite commit na github môžte použiť **master** alebo **main** - `git push origin master`
9. Otvorte váš repozitár na GitHub a reloadnite, uistite sa, že vaše zmeny boli úspešne pushnuté.
