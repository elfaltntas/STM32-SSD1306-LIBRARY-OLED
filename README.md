# 🔧 Mikroişlemciler Uygulama Projesi

Bu depoda, mikroişlemciler dersi kapsamında gerçekleştirilen *OLED Modül ve Tilt Sensörü Uygulaması* projesi yer almaktadır. Proje, I2C haberleşme protokolü, OLED ekran kontrolü ve tilt sensör entegrasyonu gibi temel elektronik ve programlama konularını kapsar.

---

## 📜 Proje Özeti
![](https://github.com/elfaltntas/STM32-SSD1306-LIBRARY-OLED/blob/main/images/urun1-1.jpg)
*Senaryo:* 
- Tilt sensörden alınan değer, OLED ekranında "ÜRÜN: %d" formatında gösterilir.
- Tilt sensörü hareket ettikçe sayaç artar ve yeşil LED yanar.
- Sayaç 6'ya ulaştığında OLED ekranda "SINIR!!" uyarısı görüntülenir, kırmızı LED yanıp sönmeye başlar ve buzzer kesintili olarak çalar.

### Proje Kazanımları
- OLED Modül kullanımı ve kontrolü.
- I2C haberleşme protokolü uygulamaları.
- Tilt sensörlerinin çalışma prensipleri.

---

## 🛠 Kullanılan Malzemeler

- *PinoLab-CodeBoard.Micro*
- *PinARM-STM32F103C8T6*
- *OLED Modül (128x64 piksel, 0.96 inch)*
- *Tilt Sensör*
- *Bağlantı kabloları*

---

## 💡 Proje Adımları

1. *Donanım Ayarları:*
   - Gerekli pinler (PB6, PB7, PB12 vb.) STM32CubeIDE üzerinde yapılandırılmıştır.
   - Clock ve GPIO ayarları tamamlanmıştır.

2. *Kütüphane Kullanımı:*
   - SSD1306 kütüphanesi projeye entegre edilmiştir.
   - .h ve .c dosyaları ilgili klasörlere eklenmiş ve projede kullanılabilir hale getirilmiştir.

3. *Kodlama:*
   - STM32CubeIDE üzerinde main.c dosyasında gerekli kodlar yazılmıştır.
   - HAL GPIO ve I2C fonksiyonları kullanılarak tilt sensör ve OLED ekran kontrolü sağlanmıştır.

4. *Çalıştırma ve Test:*
   - Donanım bağlantıları yapıldıktan sonra proje derlenmiş ve devre üzerinde test edilmiştir.
   - Tilt sensör hareketlerine ve sayaç değerlerine göre OLED ekran çıktıları kontrol edilmiştir.

---

## 📂 Dosya Yapısı


/mikroprocessor_project
├── STM32CubeIDE_Proje_Dosyaları
├── Kütüphaneler
├── Dokümantasyon
└── README.md


---

## 📞 İletişim


- 📧 elfaltntas123@gmail.com
  
