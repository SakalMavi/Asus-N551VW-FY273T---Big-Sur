# Asus-N551VW-FY273T---Big-Sur
Bu, macOS Big Sur'u Asus N551VW-FY273T'yi yükleyebilmek için bir kılavuzdur.

Anakart Adı Asus N551VW Series Notebook

BIOS Sürümü N551VW.205

CPU Intel(R) Core(TM) i7-6700HQ CPU @ 2.60GHz - Skylake

Anakart Cipseti Intel® HM170 Chipset

Ekran Kartı NVIDIA® GeForce® GTX 960M

Ekran Kartı Intel HD Graphics 530

Ses Kartı Realtek ALC668

Bellek 16247 MB (DDR4-2133 DDR4 SDRAM)

DIMM1: Samsung M471A1G43DB0-CPB 8 GB DDR4-2133 DDR4 SDRAM
DIMM3: Samsung M471A1G43DB0-CPB 8 GB DDR4-2133 DDR4 SDRAM

IDE denetleyici Intel(R) 100 Series/C230 Chipset Family SATA AHCI Controller

Network Wifi Intel(R) Dual Band Wireless-AC 7265

Network Realtek RTL8168/8111 PCI-E

Card Okuyucu Realtek RTS5287 PCI-E Kart Okuyucu

Webcam USB2.0 HD UVC WebCam

I2C HID Aygiti Touchpad ELAN1000

Windows 10 Yüklü bilgisayarımızda Kendi bilgisayarımızın Donanımına özel DSDT.aml ve ACPI Dosyalarını Çıkartmakla başlayacağız bunun için https://github.com/corpnewt/SSDTTime yöntemi kullanılmaktadır.
https://github.com/corpnewt/SSDTTime bu siteden indiriniz
indirdikden sonra 2 tane dosyamız var biri bat uzantılı Windows için diğeri command uzantılı MacOS için. Ben Henüz MacOS kurmadınığınızı düşündüğümden windows üzerinden bat uzantılı dosya ile Uygulamayı çalıştırıyoruz.

Gelen Ekranda Dump DSDT seçiyoruz. - Böylece DSDT.aml Dosyamızı oluşturmuş oluyoruz.
Sonrasında geri dönüp burada uygulama yaparken sistemimizin özelliğine göre seçim yapıyoruz. Mesela laptop için fakeec oluşturan normali seçmeyecek.
USB reset dahil çıkan aml dosyalarını acpiye atıp benim notebook'um Intel(R) Core(TM) i7-6700HQ CPU @ 2.60GHz - Skylake olduğu için buna uygun config dosyanızda OpenConfigurator ile uygulayıp kaydedin.
Bu Sayede Big Sur Sonrunsuz bir Şekilde kurulumu gerçekleştirecekdir.
