# DrawCraft V7

## Opravy v této verzi
- Opravené rozměry a transformace stěn krychle a kvádru.
- Přepnutí na kouli nyní používá samostatný kulový vzhled; po výběru krychle nebo kvádru se stěny znovu zobrazí.
- Funkce **2D → 3D** nyní vezme vybraný objekt (nebo poslední nakreslený objekt) a vytvoří 3D náhled s hloubkou. Obdélník a kruh dostanou odpovídající přední plochu; trojúhelník má zjednodušený 3D náhled. Tahy, čáry a text se převádějí podle ohraničení, nikoli na přesnou 3D síť.
- Přidaný stavový popisek v 3D režimu. Otáčení funguje tažením myší nebo prstem.

## Nasazení na GitHub Pages
1. Zálohuj si aktuální `index.html` v repozitáři.
2. Nahraď ho souborem `index.html` z tohoto balíčku a commitni změnu.
3. Po nasazení otestuj na PC i mobilu: krychli → kvádr → kouli → krychli, pak kresli obdélník/kruh, vyber ho a použij **2D → 3D**.

## Důležité: Supabase přihlášení a cloud
V této kopii jsou `DC_SUPABASE_URL` a `DC_SUPABASE_ANON_KEY` prázdné, protože zdroj, který jsme měli k dispozici, neobsahoval funkční klíč. Pokud máš na současném webu přihlášení a cloudové ukládání funkční, **nepřepisuj svou konfiguraci prázdnými hodnotami**: přenes do nového souboru své stávající hodnoty těchto dvou konstant, případně porovnej sekci Supabase se současnou funkční verzí. Používej pouze veřejný anon/publishable klíč, nikdy `service_role` klíč.

Tato verze je stále prototyp. Převod do 3D je vizuální náhled tělesa, ne profesionální modelovací nástroj ani přesná extruze libovolného volného tahu.
