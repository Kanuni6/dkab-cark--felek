# 🎡 Bilgi Yarışması Oyunu

Bu proje, HTML, CSS ve JavaScript kullanılarak geliştirilmiş, interaktif bir grup bilgi yarışması oyunudur. Oyuncular veya gruplar, puan kazanmak için çarkı çevirir, farklı kategorilerde soruları yanıtlar ve joker haklarını kullanır.

## ✨ Özellikler

* **Çoklu Grup Desteği:** 1 ila 4 grup arasında seçim yapma imkanı.
* **Dinamik Grup Adları:** Gruplar için özelleştirilebilir isimler.
* **İnteraktif Çark Sistemi:** Farklı puan değerleri, jokerler ve ceza segmentleri içeren animasyonlu çark.
* **Çeşitli Soru Tipleri:** Çoktan seçmeli sorular.
* **Joker Hakları:**
    * **50/50 Joker:** İki yanlış seçeneği eleyerek doğru cevabı bulma şansını artırır.
    * **Çift Cevap Joker:** Bir soruya iki farklı cevap verme hakkı tanır.
* **Süre Kısıtlaması:** Soruları yanıtlamak için belirli bir süre.
* **Puan Takibi:** Her grubun puanını anlık olarak gösteren tablo.
* **Responsive Tasarım:** Mobil, tablet ve masaüstü cihazlarda sorunsuz çalışır.
* **Oyun Sonu ve Puan Tablosu:** Oyun bittiğinde grupların final puanlarını sıralı bir şekilde gösterir.
* **Yerel Depolama (LocalStorage):** Oyun durumunu (takımlar, puanlar, kullanılan sorular vb.) tarayıcıda saklar, böylece sayfa yenilense bile oyun kaldığı yerden devam edebilir.

## 🚀 Nasıl Çalıştırılır?

Bu proje, herhangi bir sunucuya ihtiyaç duymayan statik bir HTML dosyasıdır.

1.  **Depoyu Klonlayın (İsteğe Bağlı):**
    Eğer bir git deponuz varsa, aşağıdaki komutla projeyi bilgisayarınıza klonlayabilirsiniz:
    ```bash
    git clone <depo_adresiniz>
    ```
    veya sadece `index.html` dosyasını indirin.

2.  **Dosyayı Açın:**
    `index.html` dosyasını favori web tarayıcınızda (Chrome, Firefox, Edge vb.) açın. Dosyaya çift tıklamanız yeterlidir.

Oyun doğrudan tarayıcınızda başlayacaktır.

## 🕹️ Nasıl Oynanır?

1.  **Grup Sayısını Seçin:** Başlangıç ekranında kaç grubun yarışacağını belirleyin (1-4 arası).
2.  **Grup Adlarını Girin:** Her grup için bir isim belirleyin.
3.  **Oyunu Başlatın:** "Oyunu Başlat" butonuna tıklayarak çark ekranına geçin.
4.  **Çarkı Çevirin:** "ÇEVİR" butonuna tıklayarak çarkı döndürün. Çarkın durduğu segment size puan, joker veya ceza (Pas/İflas) kazandıracaktır.
5.  **Soruyu Yanıtlayın:** Puan veya joker segmenti geldiğinde soru ekranına geçeceksiniz. Soruyu okuyun ve şıklar arasından doğru olduğunu düşündüğünüz cevabı seçin.
6.  **Joker Kullanımı:** Eğer joker kazandıysanız, soru ekranında ilgili joker butonları aktif hale gelecektir. Jokerleri dikkatli kullanın!
    * **50/50 Joker:** İki yanlış şıkkı ortadan kaldırır.
    * **Çift Cevap Joker:** İki şık seçme hakkı verir. Seçtiğiniz iki şıktan biri doğru ise puanı kazanırsınız.
7.  **Sıra Geçişi:** Her grubun sırası geldiğinde çarkı çevirir ve soruya cevap verir. Cevap verildikten veya süre dolduktan sonra sıra otomatik olarak bir sonraki gruba geçer.
8.  **Oyunu Bitir:** Çark ekranında bulunan "Oyunu Bitir" butonuna tıklayarak oyunu istediğiniz zaman sonlandırabilir ve puan tablosunu görebilirsiniz.
9.  **Ana Ekrana Dön:** Oyun bitti ekranında "Ana Ekrana Dön" butonuna tıklayarak oyunu sıfırlayıp yeni bir oyun başlatabilirsiniz.

## ⚙️ Teknik Detaylar

* **HTML:** Oyunun yapısal iskeleti.
* **CSS:** Oyunun görsel tasarımı ve responsive adaptasyonu.
* **JavaScript:** Oyun mantığı, çark animasyonu, soru yönetimi, joker fonksiyonları, skor takibi ve LocalStorage entegrasyonu.
    * **Canvas API:** Çarkın çizimi ve animasyonu için kullanılmıştır.
    * **LocalStorage:** Oyun durumunun kaydedilmesi ve yüklenmesi için kullanılmıştır.

## 🤝 Katkıda Bulunma

Geliştirmeye açıktır! Her türlü katkı, öneri veya hata bildirimi memnuniyetle karşılanır. Lütfen bir "issue" açmaktan veya "pull request" göndermekten çekinmeyin.

## 📄 Lisans

Bu proje, açık kaynak bir lisans altında yayınlanmıştır.

---

**Geliştiren:** Kanuni6
