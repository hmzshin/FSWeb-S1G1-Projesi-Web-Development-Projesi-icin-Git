# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

**Git,bir versiyon kontrol sistemidir. Birden fazla kullanıcının aynı proje üzerinde çalışabilmesini kolaylaştıran bir platformdur.

2. Git ile GitHub arasında ne fark var?

**Git repositolara ulaşabileceğimiz ve üzerinde local olarak değişiklikler yapabileceğimiz ve tekrardan bu değişiklikleri server a yükleyebileceğimiz bir sitem, Gitgub ise git dosyalarının depolandığı serverlar.

3. Neden bir branch oluşturuyor?

**Büyük bir projede birden farklı bölümler olabilir,birden fazla özellik ekleme gibi, oluşturulacak iki ayrı branch ile iki farklı özellik üzerinde aynı anda çalışılabilir ve daha sonra bu branchlar birleştirilerek uygulama son haline getirilir.

4. Pull Request'in amacı nedir?

**oluşturulan branch lerin main branch ile birleştirilmesi isteğidir.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

**git checkout main

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

**git fetch ; uzak depodaki repositoları yerel depolara indirir fakat birleştirme yapmaz.
**git merge ; frontend ve backend  olarak ikiayrı yazılan branchleri birleştirmek için kullanılır.
**git clone ; serverde bulunan repositoları indirir ve localde otomatik olarak birleştirir.

**"git clone" komutu, "git fetch" ve "git merge" komutlarının sırası ile çalıştırılması denebilir.

7. Merge conflict nedir?

**merge conflict bir döküman üzerinde aynı satır üzeirnde aynı anda yapılan değişiklik yüzünden oluşan çakışmayı ifade eder.


8. Merge conflict'i nasıl çözeriz?

**merge conflict yaşayan kullanıcılar iletişime geçerek ortak bir kod satırı yazabilir yada proje sorumlusu hangi kodun kullanılacağına karar verebilir.



