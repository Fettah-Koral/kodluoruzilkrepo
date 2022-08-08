# Makine Öğrenmesi :

makine öğrenmesi aslında bilgisayarla bir şekilde iletişim kurup verileri göstererek bu veriler arasında anlamlı bir ilişki kurmasını ve buna yönelik çıkarımlar yapabilmesini beklemektir

tabi bu çıkarımların katma değer yaratacak ve fayda sağlayacak çıkarımlar  yani bilgi olarak sayılabilir nitelikte olmasını isteriz  

elde edilen çıkarımların  ne kadar doğru olduğunun anlaşılabilmesi için 
bu verilerin daha önceden  modelin karşılaşmadığı yeni örneklemlerle (verilerle) test edilmesi gerekir ama veriyi direkt train ve test olarak bölersek burada dolaylı bir  over fitting oluyor çünkü tahminlerin daha iyi sonuçlar vermesi için kullanıcı müdahaleleri söz konusu 
biz burada modelimizin verlileri ezberlemesini istemiyoruz biz modelin verilerin arasındaki ilişki , bağ, korelasyon vb. bağlantıları anlamasını istiyoruz

bu yüzden veriyi 
train ( eğtim), validaton(doğrulama) ve test olmak üzere 3 parçaya bölüp modele daha objektif  tahminler yaptırıyoruz

**hazırlayan:** *muhammet fettah koral*
