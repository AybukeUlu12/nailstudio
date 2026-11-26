NAIL STUDIO — RECIPROCITY / NAIL CONSULTANT

KURULUM
ZIP dosyasını çıkarın. index.html dosyasını tarayıcıda açın. İnternet, kurulum veya kütüphane gerekmez.

KULLANIM
1. Beş tırnaktan birini seçin. Renk, şekil ve süsleme uygulayın.
2. Renk seçtiğinizde danışman bir sonraki tırnak için öneri sunar.
3. Accept suggestion önerilen rengi otomatik uygular. Try something else yeni bir öneri ister.
4. Condition A: Reddetme geçmişi sonraki öneriyi değiştirmez.
5. Condition B: Reddetme geçmişi tutulur; sonraki öneri değişir ve reddedilen renk tekrar önerilmez.
6. Koşul değişimi temiz başlangıç yapar. Reset Design, tasarımı ve danışman geçmişini sıfırlar. Mod değişimi de temiz başlangıç yapar.
7. Cancel Selection yalnızca bekleyen süsleme seçimini iptal eder; danışmanın önerisini değiştirmez.

TASARIM AYARLARI
script.js başındaki DESIGN objesinde renkler, şekiller, süslemeler, tırnak konumları, süsleme sınırları ve consultant ayarları değiştirilebilir.
consultant.suggestedOffset: önerilen rengin palet üzerindeki başlangıç uzaklığı.
consultant.rejectionStep: B koşulunda her ret sonrası öneri yönünün kaç renk kayacağı.
consultant.historyLimit: bellekte tutulan son karar sayısı.
consultant.defaultCondition: ilk açılışta A/B.

MANUEL TEST
- Beş tırnak olduğundan ve elin dış kenarında altıncı çıkıntı olmadığından emin olun.
- B koşulunda bir renk seçip iki kez Try something else'e basın: öneriler değişmelidir.
- A koşulunda aynı işlemi deneyin: ret geçmişi öneriyi değiştirmemelidir.
- Accept suggestion'a basın: önerilen renk sıradaki tırnağa uygulanmalıdır.
- Reset Design'a basın: tüm tırnaklar ve danışman geçmişi sıfırlanmalıdır.
- Tab, Enter/Space ve dokunmatik ekranla düğmeleri deneyin.

KARŞILAŞTIRMA
Bir arkadaşınızdan A ve B koşullarında aynı renk seçimi ve iki ret işlemini denemesini isteyin.
Sorun: 'Sistem önceki kararını hatırladı mı? Hangi noktada fark ettin?'
Gözlemi ve sonuçları test yapılmadan yazmayın.

AI KULLANIM NOTU
Kodun geliştirilmesinde yapay zekâ desteği kullanılmıştır. Öğrenci kuralları inceleyip değişiklikleri açıklayabilmeli; kendi test gözlemlerini ayrıca yazmalıdır.
