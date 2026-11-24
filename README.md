# Saat - Saniye Dönüştürücü (`2.5.3LAB.py`)

Bu proje, tanımlanan saat değerinin kaç saniyeye karşılık geldiğini hesaplayan ve sonucu ekrana yazdıran temel bir Python laboratuvar uygulamasıdır.

## Çalışma Mantığı

Program içerisinde iki temel değişken kullanılır:
* **`hours`**: Saniyeye çevrilecek saat miktarını tutar (varsayılan değer: `2`).
* **`seconds`**: 1 saat içerisindeki toplam saniye sayısını (`3600`) tutar.

Program çalıştırıldığında önce tanımlı saat bilgisini, ardından `hours * seconds` işleminin sonucunu ekrana yazdırır.

## Laboratuvar Kapsamında Yapılan İyileştirmeler

Orijinal kod üzerinde okunabilirliği ve işlevselliği artırmak amacıyla şu düzenlemeler yapılmıştır:
* Anlamı belirsiz olan `a` değişkeninin adı **`hours`** olarak güncellendi.
* Hesaplama çıktısının görünmesi için yorum satırı halindeki ikinci `print` ifadesi aktif hale getirildi ve düzeltildi.
* Kod sonundaki yorum satırında yer alan `'3 hours'` ifadesi güncel değere uygun olarak **`'2 hours'`** şeklinde düzeltildi.
* Gereksiz yorum satırları kaldırılarak kodun amacını açıklayan yorumlar eklendi.

## Çalıştırma

Bilgisayarınızda Python 3 kurulu olduğundan emin olduktan sonra proje dizininde şu komutu çalıştırabilirsiniz:

```bash
python 2.5.3LAB.py
