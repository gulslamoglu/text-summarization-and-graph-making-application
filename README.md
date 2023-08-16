
# Application of summarizing text and Displaying text as graph
<table>
<tr>
<td>

Bu proje, metin özetleme ve girdi metni üzerinde çeşitli doğal dil işleme teknikleri kullanarak bir grafik görselleştirme oluşturan bir Python uygulamasıdır.

## Özellikler

- Cümle benzerliği ve TextRank algoritması kullanarak metin özetleme.
- Cümle düğümleri ve benzerlik tabanlı kenarlarla grafik oluşturma.
- PyQt5 ile oluşturulmuş etkileşimli bir kullanıcı arayüzü.

## Nasıl Kullanılır

1. Betiği çalıştırarak uygulamayı başlatın.
2. "Dosya Aç" düğmesine tıklayarak bir metin dosyası yükleyin.
3. Cümle skorları için benzerlik eşiğini belirlemek için "Eşik Ayarla" düğmesini kullanın.
4. Metni temsil eden bir graf oluşturmak için "Graf Oluştur" düğmesine tıklayın.
5. Metin grafiğini görselleştirmek için "Metin Grafiği Oluştur" düğmesini kullanın.
6. Metni özetlemek için "Özetle" düğmesine tıklayın.
7. Özeti ve ROUGE skorlarını uygulama arayüzünde görüntüleyin.

## Kurulum

1. Proje deposunu klonlayın veya indirin.
2. Gerekli kütüphaneleri yüklemek için `pip install networkx matplotlib nltk PyQt5 rouge-score` komutunu kullanın.

## Kullanım

1. Python'u kullanarak uygulama betiğini çalıştırın: `python main.py`.
2. Uygulama penceresi açılacak ve özelliklerle etkileşim kurmanıza izin verecektir.

## Kullanılan Teknolojiler

- Python programlama dili
- PyQt5 kullanıcı arayüzü için
- Graf oluşturma ve manipülasyon için NetworkX
- Doğal dil işleme görevleri için NLTK
- Grafik görselleştirme için Matplotlib
- Özet kalitesini değerlendirmek için ROUGE

## Katkı Sağlama

Bu projeye katkıda bulunmak istiyorsanız, aşağıdaki adımları takip edebilirsiniz:

1. Proje deposunu çatallayın (fork).
2. Yeni bir özellik için yeni bir dal (branch) oluşturun: `git checkout -b yeni-ozellik`.
3. Yaptığınız değişiklikleri commit edin: `git commit -m 'Yeni bir özellik ekledi'`.
4. Dalı uzak sunucuya gönderin (push): `git push origin yeni-ozellik`.
5. Değişikliklerinizle birlikte bir "pull request" oluşturun ve açıklama ekleyin.

## Lisans
Bu proje MIT Lisansı ile lisanslanmıştır. Daha fazla bilgi için [LICENSE](/LICENSE) dosyasına bakabilirsiniz.

---

Bu README dosyası, projenin işlevselliği ve kullanımı hakkında kullanıcıları yönlendirmek ve bilgilendirmek için tasarlanmıştır. Herhangi bir sorunuz veya geri bildiriminiz varsa, bana ulaşmaktan çekinmeyin.

</td>
</tr>
</table>



