Samozřejmě, zde je jiná verze README souboru:

---

# Převod obrázku na textové umění

Tento skript umožňuje převést obrázek na ASCII Art. Každý pixel obrázku je nahrazen odpovídajícím znakem textu.

## Jak to funguje?

Skript nejprve načte zadaný obrázek a poté ho zmenší podle potřeby. Poté každý pixel obrázku transformuje na odpovídající znak textu podle jasu pixelu.

## Použití

1. **Nainstalujte knihovny:**

   Nejprve si nainstalujte potřebné knihovny pomocí následujícího příkazu:

   ```
   pip install Pillow svgwrite
   ```

2. **Spusťte skript:**

   Stačí spustit skript a vybrat obrázek, který chcete převést.



## Konfigurace

Ve skriptu můžete upravit následující parametry podle potřeby:

- **`scaleFactor`**: Poměr zmenšení původního obrázku před konverzí na textové umění.
- **`oneCharWidth`**: Šířka jednoho znaku textového umění.
- **`oneCharHeight`**: Výška jednoho znaku textového umění.
- **`font_path`**: Cesta k fontu použitému pro textové umění.

