 Rastgele Sayı Üreteci (Hash Tabanlı)

Bu projede bilgi sağlığı dersi kapsamında,
kriptografik hash fonksiyonları kullanılarak
rastgele bit üreten bir algoritma geliştirilmiştir.

 Algoritmanın Amacı
- Pattern içermeyen rastgele sayı üretmek
- İstatistiksel olarak dengeli (0 ≈ 1) bit dizileri elde etmek

 Kullanılan Yöntem
- SHA-256 hash fonksiyonu
- Seed (başlangıç değeri) + sayaç yaklaşımı
- Hash çıktılarının bit dizisine çevrilmesi

 Algoritmanın Çalışma Mantığı
1. Seed ve sayaç birleştirilir
2. SHA-256 ile hash alınır
3. Hash çıktısı binary formata çevrilir
4. Yeterli bit elde edilene kadar işlem tekrarlanır

 İstatistiksel Sonuçlar
Üretilen 100.000 bit için:
- 0 sayısı ≈ 50.000
- 1 sayısı ≈ 50.000

Bu sonuçlar algoritmanın istatistiksel kalite şartını
sağladığını göstermektedir.
