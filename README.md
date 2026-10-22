[README.md](https://github.com/user-attachments/files/33799388/README.md)
# FC27 ST Career Editor

**EA SPORTS FC 27** için kariyer modu editörü — takım potansiyeli, genç akademisi, sözleşme, form/morale/fitness, görünüm ve daha fazlası. Oyun içi arayüzden tek tıkla uygulanır (F9).

> Sürüm: **v1.0.0** · Oyun: EA SPORTS FC 27 · Platform: Windows 10/11

---

## Kurulum

1. [Patreon](https://www.patreon.com/st20700) üzerinden abonelik satın al (aboneliğin
   aktifleşmesi 1-2 gün sürebilir).
2. Bu repodaki (veya Patreon dosyalarındaki) zip'i indir ve bir klasöre aç.
   Örn. `C:\FC27 ST CE\`
3. Klasördeki **`Setup.bat`** dosyasını bir kez çalıştır (kopyala-çek yapar,
   pencere kapanabilir).
4. **`Launcher.exe`**'i çalıştır ve Patreon ile giriş yap.
5. Oyunu **Launcher üzerinden** başlat. Menüye geldikten sonra oyun içinde **F9**
   tuşu ile arayüzü aç/kapat.
6. *Miscellaneous Features* panelindeki **Career Cheats / Appearance / Tools**
   bölümlerindeki butonlar kariyer kayıtlarına doğrudan yazılır — her değişiklikten
   sonra oyunda **KAYDET** yapın.

## Sık Sorulan

- **EA AntiCheat / ban?** Launcher, oyunu başlatırken EA sunucu bağlantısını keser;
  launcher'dan başlatılan oyun çevrimdışı sayılır. Normal yoldan (Steam/EA App)
  açtığınızda program devre dışıdır.
- **Kayıtlarımı bozar mı?** Scriptler yalnızca anımsızdaki (RAM) kariyer veritabanını
  yazar; diskteki kaydı ancak siz KAYDET dediğinizde günceller. Yine de önemli
  kayıtlarda yedek alın.
- **Hangi sürümler uyumlu?** FC 27 1.0.141.x ve 1.0.140.x serisi (repodaki
  `version.json` takip edilir).
- **Destek:** [GitHub Issues](https://github.com/stunatasdemir/FC27-Career/issues)
  veya [GitHub](https://github.com/stunatasdemir) üzerinden.

## Belgeler

- [Getting-Started (wiki)](https://github.com/stunatasdemir/FC27-Career/wiki/Getting-Started)
- [LUA-API (wiki)](https://github.com/stunatasdemir/FC27-Career/wiki/LUA-API) — kendi
  scriptinizi yazmak için

## Özellikler (v1.0.0)

**Career Cheats**
- 99 OVR + 99 POT (kadro)
- Set Potential (kadro potansiyel + gelişim)
- Max Fitness/Form/Morale
- Heal Injuries (yara + kart temizliği)
- Extend Contracts +4y
- Stop Retirements
- Delete Generated (AI üretimi oyuncular)
- Modifier = 0
- Youth Optimize (keşfedilen gençlere potansiyel aralığı)
- Youth Academy (akademi puanı + genç oyuncu takviyesi)

**Appearance**
- Unlock All Boots · Untuck Shirts · Medium Socks · Minifaces (kadro) · Fix Headmodels

**Tools**
- Everyone 16 Y.O. · PAP All Playstyles · Transfer Ban All

Ayrıca *autorun* otomasyonu: her gün/maç öncesi otomatik iyileşme + form/morale/
fitness tazeleme, haftalık potansiyel artışı (Setup.bat ile kurulur).
