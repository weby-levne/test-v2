# DrawCraft V6

## Co je nového
- Duplikování vybraného objektu (tlačítko v panelu Vlastnosti nebo `Ctrl+D` / `Cmd+D`).
- Posun vybraného objektu ve vrstvách nahoru a dolů.
- Přepínatelná mřížka a pravítka.
- Export kresby do SVG vedle původního exportu do PNG.
- Kapátko pro převzetí barvy vybraného objektu.
- Typy štětce: kulatý, fix a tužka; nastavení průhlednosti.
- Klávesové zkratky pro Zpět/Vpřed a smazání vybraného objektu.
- Zachované původní lokální ukládání, import/export projektu a základní účetní/cloudová obrazovka.

## Nasazení na GitHub Pages
1. Nahraj `index.html` do kořene repozitáře GitHubu.
2. V nastavení repozitáře otevři **Settings → Pages** a zvol nasazení z větve a složky `/ (root)`.
3. Po nasazení otevři stránku a vyzkoušej kreslení, export PNG/SVG, lokální uložení a načtení projektu.

## Supabase
V tomto nahraném zdrojovém souboru jsou `DC_SUPABASE_URL` a `DC_SUPABASE_ANON_KEY` prázdné. Pokud chceš cloudové účty a projekty, doplň do nich URL projektu a veřejný anon/publishable klíč ze své funkční konfigurace Supabase. Nikdy sem nevkládej `service_role` klíč.

## Poznámky
Tato verze je průběžná aktualizace existujícího prototypu, nikoli hotový profesionální editor. 3D režim a převod 2D→3D zůstávají zatím jednoduchým prototypem; vrstvy jsou seznam objektů, ne plnohodnotné nezávislé vrstvy s viditelností/zámkem. Ověř funkce na počítači i mobilu před veřejným nasazením.
