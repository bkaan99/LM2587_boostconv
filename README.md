# LM2587 Boost Converter 24v to 36v
#

![](https://github.com/bkaan99/LM2587_boostconv/blob/main/outputs/rendered_project_pcb.jpeg)

#
### Basit Senaryo
Bu yapmış olduğum devrede , LM2587 Datasheetinde bulunan 20.figürü ele aldım. Devrenin hesaplamaları ve tipik örnek devresi Datasheet'te 16/40 sayfasında bulunmaktadır. 

Devrenin girişine 18V ile 28V uygulanması ortalama 24V civarı uygun görülmüştür. Girişe paralel olarak iki adet Kondansatör yerleştirilmiştir. Bunlar şematikteki c3 ve c4 kapasitörleridir. Görevleri ise giriş ripple 'ını önlemek.
Devre çıkışı sabit 36V ve 2A olarak ayarlanmıştır.
#

![](https://github.com/bkaan99/LM2587_boostconv/blob/main/outputs/pcb3d.png)
#
#### Özellikler
50mm x 35mm 
18V-28V Vin /// 36V @2A Vout
#
### Kaynaklar

LM2587 Datasheet  [LM2587 4-V To 40-V, 5-A Step-Up Wide VIN Flyback Regulator datasheet (Rev. E) (ti.com)](https://www.ti.com/lit/ds/symlink/lm2587.pdf?ts=1644065896405&ref_url=https%253A%252F%252Fwww.google.com%252F)

[Altium'da Beraber PCB Çizelim : Boost Converter - YouTube](https://www.youtube.com/watch?v=SM6gcsjcgYY&t=3s)
