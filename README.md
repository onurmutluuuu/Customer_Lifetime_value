1. Giriş ve Tanım
	1.1 Müşteri Yaşamboyu Değeri(MYBD) Nedir?
	İşletmelerin varlık sebepleri müşteriler olduğundan, stratejik boyutta yapılacak her türlü planlama ve bu planlama öncesinde yer alacak analizlerde müşteriler dikkate alınmaya başlanmıştır. Dolayısıyla işletmeler için müşterilerinin ne kadar değerli olduğunu ölçmek önemli konulardan biri olmuştur. Çünkü Pareto prensibine göre, müşterilerin yüzde 20’lik küçük dilimi tüm firma için 15 kar elde etme eğilimindedir. Bu nedenle, yöneticiler elde tutma ve yeni müşteri edinme için hedef alınan müşteri kitlesini bilmek zorundadır. Bugünkü pazarlamacılarının karşılaştığı sorun RFM gibi (En son satın alma, satın alma sıklığı, satın almaların parasal değerinin analizi) geleneksel yöntemlerin, en iyi müşteriyi tespit edememesi ve müşterinin durumunun gelecekte ne olacağına ilişkin bilgi verememesidir.[1]
	Başka bir deyişle, Müşteri yaşam boyu değeri (CLV) müşterilerden elde edilecek tüm karın bugünkü değeri  olarak tanımlanabilir.


1.2. Müşteri Yaşam Boyu Müşteri Değerinin Kullanım Amaçları
	Yaşam boyu müşteri değeri kullanılırken, pazarlama tabanlı olarak ‘bir müşteri için ne kadar harcama yapmalıyım?’; ürün tabanlı olarak ‘en değerli müşterilerime en iyi hizmeti nasıl sunabilirim?’; müşteri tabanlı olarak ‘Bir müşteriye hizmet vermek için ne kadar yatırım yapmam gerekli?’; satış tabanlı olarak ‘satış temsilcileri hangi tür müşterileri kazanmak için, en çok vakit harcamalıdır?’ gibi sorularına yanıt arayan tüm firma ve sektör içerisindeki alanlarda yaşam boyu müşteri değerinin hesaplanması önemli bir yere sahiptir.[2]
 Firmaların satışlarını artırabilmek ve kendi ömürlerini uzatabilmek için yeni müşteriler elde etmek ve var olan müşterilerini korumak zorundadırlar. Bu denklemde müşteri, onlar için en değerli pazarlama aracı olmaktadır.[2]


2. Projenin Adımları
Bu projemizde uçtan uca veri analizini yapabilmek için takip ettiğimiz bir süreç vardır. Bu süre CRISP-DM (Cross Industry Standard Process Model for Data Mining) olarak adlandırılır.
2.1 CRISP-DM
CRISP-DM (Cross-Industry Standard Process for Data Mining), iş problemlerinin veri tabanlı çözümlerle nasıl çözümlendiğini anlatmak ve iş uygulamalarının verimliliğini arttırmak amacıyla kullanılan standartlaştırılmış bir metodolojidir. CRISP-DM 6 aşamalıdır ve bu aşamaları sırasıyla uygulanması halinde projenizin doğru bir veri analiz sonucuna götürmesi mümkündür.


![image](https://user-images.githubusercontent.com/80683129/122205005-6e94b880-cea8-11eb-9181-a3d437a54a46.png)  
Grafik 1 - CRISP-DM


2.1.1 İşin Anlaşılması (Business Understanding)
İşin Anlaşılması, CRISP-DM sürecinin ilk aşamasıdır. Bu aşamada proje hedeflerini ve gereksinimlerini iş perspektifinden değerlendirmek ve daha sonra bu değerlendirmeyi belirlenmiş problem tanımına ve hedeflere ulaşmak için tasarlanmış bir ön plan oluşturmaktır.


2.1.2 Verinin Anlaşılması (Data Understanding)
Verinin Anlaşılması, ilk veri toplama işlemiyle başlar ve verileri tanımak, veri kalitesi sorunlarını tanımlamak, verilerle ilgili ilk bilgileri keşfetmek veya gizli bilgiler için hipotezler oluşturmak üzere tasarlanmış etkinliklerle devam eder. Bu projedeki verilere https://www.kaggle.com/pankajjsh06/ibm-watson-marketing-customer-value-data sitesinden ulaşabilirsiniz.


2.1.3 Verinin Hazırlaması (Data Preprocessing)
	Verinin Hazırlanmsı, genellikle veriler beklendiği gibi temiz olmayabilir ve ya yapısal olarak bozuk olabilir.Örneğin,veri setindeki eksik verilerle nasıl başa çıkılacağına dair strateji geliştirmek,aykırı ve gürültülü verilerle başa çıkılması,değişkenlerin kategorik hale getirilmesi ya da sıralanması gibi işlemler bu aşama yapılır.


2.1.4 Modelleme (Modeling)
	Modelleme, hazırlanan veri sonucunda hangi modellemeye uygun olduğu kararlaştırılan bölümdür. Bu seçimde model tekniği, test tasarımı, parametreleri ve model inceleme gerçekleştirilir.


2.1.5 Değerlendirme (Evalutaion)
	Değerlendirme, projenin sonuçlarının, daha önceden belirlenen projenin amaçlarına uygun olup olmadığı, test değerleri de göz önünde bulundurularak değerlendirilir. Eğer çıkan sonuçlar bizim elde etmek istediğimiz cevapları vermiyorsa CRISP – DM aşamalarından ilki olan İşin Anlaşılması aşamasına geri dönüp ortada ki sorun anlaşılmaya çalışılır.


2.1.6 Uygulama (Deployment)
Uygulama, hazırlanan projenin günlük hayat içerisindeki kullanımına odaklanılır. Bu adım için, değerlendirme aşamasında yer alan sonuçlardan yola çıkılarak yapılması gerekenler planlanır.
