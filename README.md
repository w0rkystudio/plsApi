# plsApi

**Check Please! Demo** için BepInEx modlama API'si · A BepInEx modding API for **Check Please! Demo**

### 📖 [Tutorial / Rehber (TR + EN)](https://w0rkystudio.github.io/plsApi/)

### ⬇️ [İndir / Download (Releases)](https://github.com/w0rkystudio/plsApi/releases/latest)

| Dosya / File | |
|---|---|
| `plsApi-v1.3.0.zip` | API: oyun klasörüne aç / unzip into the game folder |
| `TemplateProject-v1.3.0.zip` | Hazır mod projesi şablonu / ready-made mod project template |
| `ExampleMods-v1.3.0.zip` | Örnek modlar (PizzaMod, CustomerMod) + kaynak kodları / example mods + source |

---

## TR

**Kurulum:** Oyuna [BepInEx 5](https://github.com/BepInEx/BepInEx/releases) (x64, Mono) kur, sonra `plsApi-v1.3.0.zip` dosyasını oyun klasörüne aç. Dosya `BepInEx\plugins\plsApi\plsApi.dll` konumuna gelmeli.

**Neler var:**
- `print_game`: ekranın sol üstüne yazı
- `print_log`: sadece `LogOutput.log`'a kayıt
- `Foods`: kendi sprite'ı ve ismiyle yeni yemekler; müşteriler de sipariş eder
- `Customers`: tek sprite ya da kolları ayrı animasyonlu yeni müşteriler; harita ve yıldıza göre şanslı pencere / şarkıcı tercihleri; komşu seviyeleri (0 iyi anlaşır, 1 hafif öfkeli, 2 kavga eder)
- Karakter defterinde **MOD** sekmesi
- Oyunun Jenerik ekranında "Mod API By W0RKY"

Kod yazmayı, şablonu ve tüm örnekleri [rehberde](https://w0rkystudio.github.io/plsApi/) bulabilirsin.

## EN

**Install:** install [BepInEx 5](https://github.com/BepInEx/BepInEx/releases) (x64, Mono) into the game, then unzip `plsApi-v1.3.0.zip` into the game folder. The file should end up at `BepInEx\plugins\plsApi\plsApi.dll`.

**What's inside:**
- `print_game`: text in the top-left of the screen
- `print_log`: writes only to `LogOutput.log`
- `Foods`: new dishes with their own sprite and name that customers order
- `Customers`: new animated customers (single sprite or separate arms), window / singer seat preferences with chances per map and star, neighbour levels (0 get along, 1 mildly annoyed, 2 fight)
- A **MOD** tab in the character book
- "Mod API By W0RKY" on the game's Credits screen

Writing mods, the template and all examples are covered in the [tutorial](https://w0rkystudio.github.io/plsApi/).

---

Hayran yapımıdır; oyunun geliştiricileriyle bağlantısı yoktur. · Fan-made; not affiliated with the game's developers.

**Mod API By W0RKY**
