### 2) İşletim Sistemi Temelleri (OS Basics)

İşletim sistemi, donanım ile kullanıcı arasında köprü görevi gören temel yazılımdır.
Bilgisayar üzerindeki tüm donanım kaynaklarının verimli ve güvenli şekilde kullanılmasını sağlar.

---

#### Kernel Nedir?

Kernel, işletim sisteminin en temel ve en önemli parçasıdır.
Donanım ile yazılım arasındaki doğrudan iletişimi sağlar.
CPU, bellek, disk ve giriş-çıkış aygıtlarının yönetimi kernel tarafından yapılır.
Kullanıcı programları donanıma doğrudan erişemez, bu erişim kernel aracılığıyla sağlanır.

---

#### Süreç (Process) ve İş Parçacığı (Thread) Arasındaki Fark

Süreç (process), çalışan bir programın bellekteki aktif halidir.
Her süreç kendine ait bellek alanına sahiptir.
İş parçacığı (thread) ise bir sürecin içindeki daha küçük çalışma birimidir.
Bir süreç içinde birden fazla thread bulunabilir ve bu thread’ler aynı belleği paylaşır.
Thread’ler, süreçlere göre daha hızlı ve daha az maliyetlidir.

---

#### Bellek Yönetimi Nasıl Yapılır?

Bellek yönetimi, RAM’in programlar arasında düzenli ve güvenli şekilde paylaştırılmasını sağlar.
İşletim sistemi, her sürece ihtiyaç duyduğu kadar bellek tahsis eder.
Kullanılmayan bellek alanları geri alınarak başka süreçlere verilir.
Bu sayede bellek taşması ve çakışmalar önlenir.

---

#### CPU Zamanlayıcıları Nedir?

CPU zamanlayıcıları, işlemcinin hangi sürece ne kadar süreyle verileceğini belirleyen mekanizmalardır.
Aynı anda birden fazla program çalışıyormuş gibi görünmesini sağlar.
Her sürece adil bir şekilde CPU zamanı dağıtılır.
Bu mekanizma sayesinde sistem performansı ve kullanıcı deneyimi artar.


