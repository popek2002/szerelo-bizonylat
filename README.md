> ⚠️ **DISCLAIMER / JOGNYILATKOZAT:**  
> Ez a weboldal egy **képzeletbeli, kizárólag szerepjátékhoz (RolePlay)** készült segédeszköz.  
> **NEM VALÓDI SZÁMLÁZÓ** és **IRL (való életben) nem létező szolgáltatáshoz** kapcsolódik. A rendszer kizárólag a **SeeRPG / FiveM GTA RP** szervereken működő virtuális *ACES Services* szerelőtelep fiktív frakcióközi elszámolásait szolgálja.


# 🔧 ACES Services - Bizonylat Generáló & Elszámoló Rendszer

A weboldal segítségével az **ACES Services** szerelői gyorsan és egyszerűen állíthatnak ki hivatalos elszámoló bizonylatokat a partnerszervezetek (LSPD, BCSO, OMSZ, Flották) számára.

---

## 🚀 Fő Funkciók

* **Gyorsválasztó Kategóriák:** Egy kattintásos beállítások a gyakori partneri kedvezményekhez (pl. Rendőrség 100%, Civil 0%).
* **Automatikus Számítás:** Az eredeti árból és a kedvezmény %-ból azonnal kiszámolja a fizetendő végösszeget.
* **Garantáltan Egyedi Bizonylatszám:** A rendszer az aktuális dátum és időpont alapján generál egyedi azonosítót (`SZ-ÉÉHHNN-ÓÓPP`), így kizárt a duplikáció.
* **Közvetlen Discord Webhook Integráció:** Egyetlen gombnyomással generál egy képet a számláról, és beküldi a beállított Discord csatornába.
* **Beépített In-Game Link Rövidítő:** A Discordról kimásolt kép URL-jét másodpercek alatt átalakítja egy rövid, in-game chatben is könnyen beilleszthető linkké (TinyURL).

---

## 📖 Használati Útmutató Szerelőknek

### 1. Bizonylat Kiállítása
1. Válassz egy **Gyorsválasztó Kategóriát** vagy töltsd ki kézzel a mezőket:
   * **Partner / Szervezet** (pl. Rendőrség (LSPD))
   * **Jármű adatai** (Rendszám + Típus)
   * **Igénybevevő** (Név / Jelvényszám)
   * **Elvégzett Munkák**
   * **Eredeti Ár** és **Kedvezmény %**
   * **Szerelő Neve / Azonosítója**
2. Az előnézetben ellenőrizd a kiállított számlát.

### 2. Beküldés Discordra & Link Rövidítés (In-Game RP)
1. Kattints a **`KÜLDÉS DISCORDRA`** gombra.
2. Lépj be a Discord szobába, kattints az újonnan megjelent számla képére jobb gombbal, majd válaszd a **Kép címének másolása** (*Copy Image Link*) opciót.
3. Illeszd be a kimásolt linket a weboldal alján található **In-Game Link Rövidítő** mezőjébe, és nyomj a **`LINK RÖVIDÍTÉSE & MÁSOLÁSA`** gombra.
4. A rövidített link automatikusan a vágólapodra kerül! Lépj vissza a játékba, és nyomj egy `CTRL + V`-t az OOC chatben.

---

## 📁 Állományok a Repóban

* `index.html` — A teljes bizonylatgeneráló alkalmazás kódja.
* `aces-logo.png` — A szerelőtelep hivatalos logója (fejlécben és vízjelként).
