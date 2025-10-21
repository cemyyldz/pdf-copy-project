# 📄 Senile PDF Replikasyon Motoru

Bu depo, mevcut bir PDF dosyasını (`file.pdf`) analiz ederek tüm yapısal ve görsel öğelerini (metin, font, koordinatlar, çizgiler ve görseller) çıkarıp, ReportLab kütüphanesi ile **birebir görsel doğrulukla (senile)** yeniden üreten bir Python çözümüdür.

##Proje Amacı

Orijinal `file.pdf`'in görsel ve yapısal olarak birebir aynı kopyası olan `output.pdf`'i programatik olarak oluşturmaktır.İsterseniz farklı bir dosya yerleştirebilirsiniz.

## Kullanılan Teknolojiler

Proje, ReportLab, `pdfminer.six` (metin/yapı), `pdfplumber` ve `Pillow` (görsel çıkarma ve manipülasyon) kütüphanelerini kullanır.

## Kurulum ve Çalıştırma

1. **Klonlama:** Depoyu yerel ortamınıza klonlayın.
2. **Bağımlılıklar:** `pip install PyPDF2 pdfminer.six reportlab pdfplumber Pillow` komutu ile tüm kütüphaneleri kurun.
3. **Çalıştırma:** Kaynak dosyanız olan **`file.pdf`**'i kök dizine yerleştirin ve ana Python/Colab dosyasını çalıştırın.

Bu işlem sonucunda **`output.pdf`** dosyası oluşturulacaktır.
