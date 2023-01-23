## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
2. Git ile GitHub arasında ne fark var?
3. Neden bir branch oluşturuyoruz? 
4. Pull Request'in amacı nedir?
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
7. Merge conflict nedir?
8. Merge conflict'i nasıl çözeriz?

1-Git, sürüm kontrol sistemi olarak kullanılır. Yerel bilgisayarda dosyaların değişikliklerini izlenebilir ve değişiklikleri geri alınabilir.
2-Git ve GitHub, aynı amaç için kullanılan ancak farklı şeylerdir. Git sürüm kontrol sistemi kullanılırken, GitHub dosyaları ve kodları depolamaya ve paylaşmaya olanak tanır.
Ayrıca GitHub, kodlarınızın önceki sürümlerini görüntülemeyi ve değişikliklerin izlemensini sağlar.
3-Çoklu çalışma ortamı oluşturur. Bir proje üzerinde çalışan kişilerin çalışmaları birbirlerinden etkilenmez.
Kodların önceki sürümlerinin korunması için önemlidir.
Kısacası branch oluşturmak işleri kolaylaştıran bir yöntemdir.
4-Pull Request, kodların kontrol edilmesi, test edilmesi ve onaylanması için önemlidir. Bu sayede, proje sahibi veya yöneticiler kodların kalitesini ve güvenliğini sağlar ve katkıda bulunanların yaptığı değişiklikleri denetler. Ayrıca, Pull Request ile proje sahibi veya yöneticiler katkıda bulunanlar ile işbirliği yapabilir ve kodların daha iyi hale gelmesine katkıda bulunabilir.
5-git checkout <branch_name>
örneğin, git checkout <main branch>
Ayrıca git switch komutu da aynı işlemi gerçekleştirir: git switch <branch_name>
6-git fetch komutu, remote repository'den yerel repository'e dosyaları indirir. Bu komut, sadece remote repository'de yapılan değişiklikleri indirir ve yerel repository'e yansıtmasa da, yerel repository'de bir branch oluşturur. Bu branch ile yerel repository'inizde çalışabilirsiniz.

git merge komutu, iki branch arasındaki değişiklikleri birleştirir. Örneğin, yerel repository'de çalıştığınız branch ile remote repository'den indirdiğiniz branch arasındaki değişiklikleri birleştirmek için kullanılabilir.

git pull komutu, git fetch ve git merge komutlarının birleşimidir. Bu komut, remote repository'den yerel repository'e dosyaları indirir ve iki branch arasındaki değişiklikleri birleştirir. Bu komut, remote repository'de yapılan değişiklikleri yerel repository'e yansıtır ve iki repository'i senkronize eder.
7-Merge conflict, Git sürüm kontrol sistemi için kullanılan bir terimdir. Bu terim, iki branch arasında aynı dosyaların veya aynı satırların değiştirilmesi sonucu oluşan çakışmayı ifade eder.
8-Merge conflict oluştuğunda, Git sistemi otomatik olarak çakışan satırları işaretler ve kullanıcıya çözüm yolları sunar. Kullanıcının çözüm yolunu seçmesi ve manual olarak çakışan satırları çözmesi gerekir.
Merge conflict çözmek için kullanılabilecek komutlar:

git mergetool komutu ile çakışan satırları görsel olarak görüntüleyebilirsiniz.
git diff komutu ile çakışan satırların değişikliklerini görebilirsiniz.
git add ve git commit komutları ile çözüm yolunu kaydedebilirsiniz.
Merge conflict çözmek için yapabileceğiniz işlemler arasında, çakışan satırları silmek, çakışan satırları düzenlemek, çakışan satırların tümünü silmek veya çakışan satırların tümünü kabul etmek gibi seçenekler vardır.


