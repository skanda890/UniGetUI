#  WingetUI: Bir paket yöneticisi kullanıcı arayüzü

[![Downloads@latest](https://img.shields.io/github/downloads/martinet101/WingetUI/total?style=for-the-badge)](https://github.com/martinet101/WingetUI/releases/latest/download/WingetUI.Installer.exe)
[![Sürüm Rozeti](https://img.shields.io/github/v/release/martinet101/WingetUI?style=for-the-badge)](https://github.com/martinet101/WingetUI/releases)
[![Sorunlar Rozeti](https://img.shields.io/github/issues/martinet101/WingetUI?style=for-the-badge)](https://github.com/martinet101/WingetUI/issues)
[![Kapalı Sorunlar Rozeti](https://img.shields.io/github/issues-closed/martinet101/WingetUI?color=%238256d0&style=for-the-badge)](https://github.com/martinet101/WingetUI/issues?q=is%3Aissue+is%3Aclosed)

<br>Bu projenin temel amacı, [Winget](https://learn.microsoft.com/en-us/windows/package-manager/) ve [Scoop](https://scoop.sh/) gibi Windows 10 ve Windows 11 için en yaygın CLI paket yöneticileri için sezgisel bir GUI oluşturmaktır.  

Bu uygulama ile, desteklenen paket yöneticilerinde yayınlanan tüm yazılımları ve çok daha fazlasını kolayca indirebilir, yükleyebilir, güncelleyebilir ve kaldırabilirsiniz.

<br>**Yasal Uyarı:** Bu projenin resmi [Winget projesi](https://github.com/microsoft/winget-cli) ile hiçbir bağlantısı yoktur - tamamen gayri resmidir. 

Ne Microsoft'un ne de WingetUI'nin yaratıcılarının indirilen uygulamalardan sorumlu olmadığına dikkat edin. 

[![Status](https://img.shields.io/badge/Project%20current%20development%20status-Active-brightgreen?style=for-the-badge)]()

![image](https://user-images.githubusercontent.com/73800734/199359247-c52f6b4c-8019-484c-9f25-ad809c0817f3.png)

#  Özellikler

 - Scoop ve Winget'ten paket yükleme yeteneği (fikir gelecekte daha fazla paket yöneticisi eklemektir).
 - Önceden yüklenmiş paketleri yükseltme ve kaldırma becerisi - yerel PC uygulamalarını kaldırmanın yanı sıra!
 - Gelecekte kolayca yükleyebilmeniz için seçtiğiniz paketleri hem içe hem de dışa aktarma yeteneği.
 - Kullanıcının herhangi bir paket yöneticisi yüklemesine gerek yoktur. (Uygulama sizin için Scoop'u yükleme yeteneğine sahip olsa da!)
 - Scoop kovalarını yönetmek için destek içerir.
 - Kullanıcı herhangi bir uygulamanın yüklemek istediği sürümünü seçebilir.
 - Bir uygulamanın kurulumunun/güncellemesinin/kaldırılmasının başarıyla tamamlanıp tamamlanmadığı kullanıcıya bildirilir.
 - Çakışmaları önlemek için yüklemeleri sıraya koyma yeteneği.
 - Gözlerinizi yakmanızı önlemek için koyu bir tema mevcuttur. :sunglasses:
 - Kurulumdan önce paketle ilgili bilgileri (lisansı, SHA256 hash'i, ana sayfası vb.) gösterme yeteneği.
 - 6800'den fazla paket mevcut ve artıyor!
 - Gelecekte daha fazla özellik geliyor!

# Bana destek olmayı düşün.

**Bu gerçekten büyük bir fark yaratıyor ve çok takdir ediliyor.**

<a href='https://ko-fi.com/martinet101' target='_blank'><img style='border:0px;height:36px;' src='https://az743702.vo.msecnd.net/cdn/kofi3.png?v=0' border='0' alt='ko-fi.com adresinden Bana Bir Kahve Ismarla' /></a>

Teşekkür ederiz! :)

# Kurulum

<p>WingetUI'yi kurmanın birden fazla yolu vardır - hangisini tercih ediyorsanız onu seçin!<br><br></p>

- Birincisi, yükleyicinin en son sürümünü indirmektir:
<br>

<p align="center"><b><a href="https://github.com/martinet101/WingetUI/releases/latest/download/WingetUI.Installer.exe">WingetUI'yı indirmek için buraya tıklayın</a></b></p>
<br>

- İkincisi ise [Winget] (https://learn.microsoft.com/en-us/windows/package-manager/) kullanmaktır:

PowerShell veya Komut İstemi'nde aşağıdaki komutu çalıştırın: `winget install wingetui`

<br>

- Üçüncü yöntem ise [Scoop](https://scoop.sh/) kullanmaktır - aşağıdaki talimatlara bakın.

Daha önce eklenmemiş olması durumunda, önce _Extras_ kovasını eklemek gerekir: `scoop bucket add extras`

Daha sonra WingetUI`yi kurmak için aşağıdaki komutu çalıştırın: `scoop install wingetui`

<br><p align="center"><i>Şuna bir göz atın <a href="https://github.com/martinet101/WingetUI/wiki">Wiki</a> daha fazla bilgi için!</i></p>


## WingetUI'nin diğer dillere çevrilmesi
WingetUI'yi diğer dillere çevirmek veya eski bir çeviriyi güncellemek için lütfen daha fazla bilgi için [Translating WingetUI - WingetUI Wiki] (https://github.com/martinet101/WingetUI/wiki#translating-wingetui) adresine bakın.


### Şu anda Desteklenen diller
<!-- Otomatik oluşturulmuş çeviriler -->
| Dil | Çeviri | |
| :-- | :-- | --- |
| Katalanca - Català | %100 | <img src='https://flagcdn.com/ad.svg' width=20> |
| Almanca - Deutsch | %100 | <img src='https://flagcdn.com/de.svg' width=20> |
| Çince - 中文 | %100 | <img src='https://flagcdn.com/cn.svg' width=20> |
| İngilizce - English | 100% | <img src='https://flagcdn.com/gb.svg' width=20> |
| Fransızca - Français | %100 | <img src='https://flagcdn.com/fr.svg' width=20> |
| Hintçe - हिंदी | %96 | <img src='https://flagcdn.com/in.svg' width=20> |
| İtalyanca - Italiano | %100 | <img src='https://flagcdn.com/it.svg' width=20> |
| Portekizce (Brezilya) | %100 | <img src='https://flagcdn.com/br.svg' width=20> |
| Portekizce (Portekiz) | %100 | <img src='https://flagcdn.com/pt.svg' width=20> |
| Türkçe - Turkish | 100% | <img src='https://flagcdn.com/tr.svg' width=20> |
| Ukraynaca - Yкраї́нська | 85% | <img src='https://flagcdn.com/ua.svg' width=20> |

Son güncelleme: Fri Nov 11 01:16:08 2022
<!-- END Otomatik oluşturulan çeviriler -->


## Katkılar
 WingetUI, değerli katılımcılarımızın yardımı olmadan mümkün olamazdı. Bir yazım hatasını düzelten kişiden kodun yarısını geliştiren kişiye kadar, WingetUI onlarsız mümkün olmazdı! :smile:<br><br>

### Katkı Sağlayanlar:
 [![Sevgili Katılımcılarım](https://contrib.rocks/image?repo=martinet101/WingetUI)](https://github.com/martinet101/WingetUI/graphs/contributors)<br><br>
 
 ### Tercümanlar:
 WingetUI makine tarafından çevrilmemiştir! Aşağıdaki kullanıcılar çevirilerden sorumludur:
- Ahmet Özmetin: Türkçe
- BUGP Derneği: Çince
- Datacra5H: Almanca
- Evans: French
- Operator404: Ukranian
- ppvnf: Portuguese (Portugal and Brazil)
- Satyam Singh Niranjan: Hindi
- Martí Climent: Catalan
 

# Ekran Görüntüleri
 
![image](https://user-images.githubusercontent.com/73800734/199359651-2492f9c1-fc08-4554-8f45-fd236ec5d5fa.png)

![image](https://user-images.githubusercontent.com/73800734/199359788-f5003f4c-92e1-49fc-9a0b-43eb6ba6338d.png)

![image](https://user-images.githubusercontent.com/73800734/199360452-294a57fa-1738-4c0f-9ee5-a92f9a0c3073.png)

![image](https://user-images.githubusercontent.com/73800734/199360606-0b18db79-7ce5-4574-b919-ae91c8b7394a.png)

![image](https://user-images.githubusercontent.com/73800734/199363533-6e11d026-5eca-430a-b15a-1e4e9dd73d67.png)

![image](https://user-images.githubusercontent.com/73800734/199360891-1b26dacb-f3c8-4087-aa00-8a6211340fa0.png)

![image](https://user-images.githubusercontent.com/67732686/195114107-abe537df-3ee4-4d81-8707-a189e83b7abe.png)

![image](https://user-images.githubusercontent.com/73800734/199553170-3d227011-1fcb-4657-b673-a0f80d964e46.png)


# SSS

**Q: Belirli bir Winget paketini yükleyemiyorum veya yükseltemiyorum! Ne yapmam gerekiyor?**<br>

A:  Bu muhtemelen WingetUI'den ziyade Winget ile ilgili bir sorundur. 

Lütfen duruma bağlı olarak `winget upgrade` veya `winget install` komutlarını kullanarak PowerShell veya Komut İstemi aracılığıyla paketi kurmanın/yükseltmenin mümkün olup olmadığını kontrol edin (örneğin: `winget upgrade --id Microsoft.PowerToys`).  

Bu işe yaramazsa, [Winget'in kendi proje sayfası] (https://github.com/microsoft/winget-cli) adresinden yardım istemeyi düşünün.<br>

#

**Q: Bir paketin adı üç nokta ile kesilmiş - tam adını/id'sini nasıl görebilirim?**<br>

A: Bu Winget'in bilinen bir kısıtlamasıdır. 

Daha fazla ayrıntı için https://github.com/microsoft/winget-cli/issues/2603 adresine bakınız.<br>

#

**Q: Antivirüs programım bana WingetUI'nin bir virüs olduğunu söylüyor! / Tarayıcım WingetUI'nin indirilmesini engelliyor!**<br>

A: WingetUI örneğinde olduğu gibi, uygulamaların (yani çalıştırılabilir dosyaların) kötü niyetli olmasa bile engellenmesinin ve/veya virüs olarak algılanmasının yaygın bir nedeni, nispeten çok sayıda kişi tarafından kullanılmıyor olmalarıdır.

Bunu yakın zamanda piyasaya sürülen bir şeyi indiriyor olabileceğiniz gerçeğiyle birleştirdiğinizde, bilinmeyen uygulamaları engellemek çoğu durumda gerçek kötü amaçlı yazılımları önlemek için alınacak iyi bir önlemdir.

WingetUI açık kaynak kodlu ve kullanımı güvenli olduğundan, uygulamayı antivirüs/tarayıcı ayarlarınızda beyaz listeye eklemeniz yeterlidir.<br>

#

**Q: Chocolatey'e destek verilecek mi?**<br>

A: Bu konu üzerinde halen çalışılmaktadır.

Daha fazla ayrıntı için https://github.com/martinet101/WingetUI/issues/56 adresine bakınız.<br>

#

**Q: Uygulamada Winget için kaynak olarak "msstore" ekleyebilir miyim?**<br>

A: Bu mümkün değildir ve yakın gelecekte de planlanmamaktadır. 

Daha fazla ayrıntı için https://github.com/martinet101/WingetUI/issues/87 adresine bakınız.<br>

#

**Q: Winget/Scoop paketleri güvenilir mi?**<br>

A: WingetUI, Microsoft ve Scoop, üçüncü taraflarca sağlanan ve teorik olarak tehlikeye atılabilecek indirilebilir paketlerden sorumlu değildir.

Kötü amaçlı yazılım indirme risklerini azaltmak için Microsoft, Winget'te bulunan yazılımlar için birkaç kontrol uyguladı. Yine de, yalnızca güvendiğiniz yayıncılardan yazılım indirmeniz önerilir. 

<br><p align="center"><i>Şuna bir göz atın <a href="https://github.com/martinet101/WingetUI/wiki">Wiki</a> daha fazla bilgi için!</i></p>
