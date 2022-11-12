# git-egitim-sonrasi-test
Bu repo IEEE Marmara bünyesinde vermiş olduğum Git eğitiminin ardından kullanıcıların anlama seviyelerini test edebilmemiz için açılmıştır.

Bu repodaki "anladim.txt" dosyasının içine GitHub kullanıcı adınızı yazıp (ayrı bir branch içinde tabi ki:) Pull Request göndermeniz gerekmektedir.

## Nasıl yapılır?
1. Öncelikle sizlere atmış olduğum dokümanda yazan `git clone` komutu ile bu repoyu bilgisayarınıza istediğiniz bir adrese indirin ve `cd` ile içine girin.
2. Ardından yeni bir branch açın ve o branchin içine girin. (Hatırlatma: `git branch` ve `git checkout` komutları)
3. Gerekli düzenlemeyi ister kullandığınız not defteri ile isterseniz size öğretmiş olduğum `echo "gitub_kullanciiniz" >> anladim.txt` komutu ile ekleyiniz.
4. Yaptığınız bu değişikliği **git**in görebilmesi için (yeşil alana çekmek için) `git add` komutunu kullanınız.
5. Daha sonra bu değişikliği commitleyiniz (history'e kaydediniz). (Hatırlatma: `git commit`)
6. En son olarak ise dokümanda yazılmış olan `git push` komutu aracılığı ile açmış olduğunuz branch'i GitHub sunucusuna gönderiniz. (Not: Clone edilmiş repoolar, remote ile tekrar referans atamasına ihtiyaç duymazlar. Otomatik olarak origin referansı atanmıştır.)
7. Bu aşamalar bittikten sonra GitHub arayüzüne dönüp pull requestinizi açabilirsiniz. (O sarı banner gelmediği takdirde, Repo'nun adının altındaki Pull Request sayfasına tıklayınız ve yeni oluştur deyiniz.)

İyi eğlenceler!
