# Ping Pong Hra 🎮

### 📝 Přehled
Toto je jednoduchá **Ping Pong hra** implementovaná v jazyce Python s použitím knihovny `pygame`. Hra napodobuje klasickou retro verzi stolního tenisu s černým pozadím a bílými pálkami. Hrají dva hráči — **levý hráč** ovládá pálku pomocí kláves `W` a `S` a **pravý hráč** ovládá pálku pomocí šipek `↑` a `↓`.

---

## 🛠️ Funkce
- Hra pro dva hráče s ovládáním na klávesnici.
- Jednoduchá grafika s černým pozadím a bílými pálkami/míčkem.
- Zobrazení skóre v horní části obrazovky.
- Míček se odráží od pálky a od stěn.
- Míček se po získání bodu vrací na střed.
- Možnost přizpůsobení rychlosti hry a rozměrů pálky/míčku.

---

## 📋 Požadavky
Před spuštěním hry se ujistěte, že máte na svém systému nainstalovaný Python a knihovnu `pygame`.

### Instalace `pygame`
```bash
pip install pygame
```
### Spuštění hry
1. Naklonujte si tento repositář.
2. Otevřete příkazový řádek nebo terminál ve složce, kde máte soubor uložený.
3. Spusťte následující příkaz:
   ```bash
   python ping_pong.py


## 🎮 Ovládání
- **Levý hráč**:
  - `W` - pohyb nahoru
  - `S` - pohyb dolů
- **Pravý hráč**:
  - `↑` - pohyb nahoru
  - `↓` - pohyb dolů

---

## 🔄 Jak hra funguje
1. Míček se začne automaticky pohybovat po spuštění hry.
2. Hráči ovládají své pálky pomocí klávesnice a snaží se odrazit míček zpět.
3. Pokud míček projde za levou pálku, bod získává **pravý hráč**.
4. Pokud míček projde za pravou pálku, bod získává **levý hráč**.
5. Po dosažení bodu se míček resetuje do středu hrací plochy.

---

## 📈 Úpravy
- **Rychlost míčku**: Rychlost můžete přizpůsobit změnou hodnot `BALL_SPEED_X` a `BALL_SPEED_Y`.
- **Rychlost pálky**: Upravte hodnotu `PADDLE_SPEED` pro rychlejší nebo pomalejší pohyb.
- **Velikost hrací plochy**: Můžete změnit rozměry okna úpravou proměnných `WIDTH` a `HEIGHT`.

---

## 💡 Tipy pro další rozšíření
- **Zvukové efekty**: Přidejte zvukové efekty při odrazu míčku pro větší herní zážitek.
- **Single-player mód**: Přidejte AI, aby hráč mohl hrát proti počítači.
- **Obtížnost hry**: Upravte obtížnost podle úrovně hráče změnou rychlosti míčku a velikosti pálky.
- **Scoring limit**: Přidejte možnost nastavit maximální počet bodů pro vítězství.

---

🎉 **Užijte si hru!** 🚀


