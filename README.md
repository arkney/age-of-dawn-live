# Arkney: Age of Dawn — live

Bu repo oyunun **kaynak kodunu içermez**. Yalnızca kurulu oyunun okuması
gereken üç şeyi taşır:

| Dosya | Ne söyler |
|---|---|
| `server.json` | Oyun sunucusunun **şu anki** adresi. Host `npm run host` çalıştırdığında yazılır. |
| Releases → `latest.json` | En güncel masaüstü sürümün numarası, imzası ve indirme adresi. |
| Releases → `Arkney_<sürüm>_x64-setup.exe` | Kurulum dosyası ve imzası. |

Public olmasının tek nedeni: dağıtılmış her `.exe` kopyasının bunları
token olmadan okuyabilmesi gerekir.

## Oyunu kurmak

[Releases](../../releases/latest) sayfasından `Arkney_<sürüm>_x64-setup.exe`
dosyasını indir ve kur. Oyun kendini bundan sonra otomatik günceller —
bu sayfaya bir daha gelmen gerekmez.

Sunucu, host'un bilgisayarı açıkken çevrimiçidir. Kapalıysa oyun bağlanmayı
dener ve sunucu geri geldiğinde kendiliğinden bağlanır.
