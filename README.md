# 📅 Calendari Laboral Personal

Una aplicació web senzilla, lleugera i privada per portar el registre de les hores laborals, vacances, festius i hores de flexibilitat.

## ✨ Característiques

- **Privacitat total:** Les dades es guarden exclusivament al teu navegador mitjançant `localStorage`. No hi ha cap servidor extern ni base de dades.
- **Gestió de colors:** Permet categoritzar els dies per colors (Laborable, C.C., Lliure disposició, Flexibilitat, Vacances).
- **Càlcul d'hores:** Compta automàticament el balanç d'hores segons el tipus de jornada i les variacions introduïdes.
- **Registre del mes:** Llistat detallat de les modificacions horàries fetes durant el mes en curs.
- **Interfície adaptable:** Disseny modern (DM Sans) i optimitzat per a dispositius mòbils.

## 🚀 Com fer-lo servir

1. **Navegació:** Utilitza les fletxes `‹` `›` o el botó `Avui` per moure't pel calendari.
2. **Modificació de dies:**
   - Activa el selector **"Modificar"** i tria el tipus de dia (per exemple, "Vacances").
   - Fes clic sobre el dia al calendari per aplicar el color.
3. **Registre d'hores:**
   - Si has fet hores de més o de menys, activa **"Variar hores"**.
   - Tria el valor (ex: `+2` o `-1`) i clica sobre el dia corresponent.
4. **Comptadors:** A la part inferior podràs veure el resum anual acumulat i ajustar les hores inicials si és necessari.

## 🛠️ Instal·lació i Hostalatge

Aquest projecte consta d'un únic fitxer HTML. Per posar-lo en marxa:

1. Puja el fitxer `calendari.html` a un repositori de GitHub.
2. (Opcional) Canvia el nom a `index.html` per a una càrrega automàtica.
3. Ves a **Settings > Pages** i activa la branca principal per publicar-lo.

## ⚠️ Notes importants sobre les dades

Com que l'aplicació utilitza `localStorage`:
- **Sense sincronització:** Les dades del mòbil no es veuran a l'ordinador.
- **Risc d'esborrat:** Si neteges la memòria cau o l'historial del navegador (dades de llocs web), les dades s'esborraran. 
- **Navegació privada:** No facis servir el calendari en mode d'incògnit, ja que les dades es perdran en tancar la pestanya.

## 📝 Tecnologies utilitzades

- HTML5
- CSS3 (Variables i Grid)
- JavaScript (Vanilla JS)
- Google Fonts (DM Sans / DM Mono)
