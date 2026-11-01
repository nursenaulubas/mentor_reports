# 1. BİLGİSAYAR MİMARİSİ(CPU, RAM, Cache)

## CPU iç yapısı (ALU, kontrol birimi)
*Bilgisayar komutlarını işler ve programların çalışmasını sağlar
*Bilgisayarın beyni olarak düşünülebilir. Hesaplama yapar, mantıksal işlemleri gerçekleştirir, komut yorumlar ve diğer donanımsal bileşenler ile veri alışverişi sağlar
*Temel çalışma mantığı Fetch // Decode // Execute şeklindedir(komutu bellekten getir-çözümle-komutu yürüt)

### CPU'NUN BAŞLICA BİLEŞENLERİ VE GÖREVLERİ

#### 1.CONTROL UNIT (CU)
*Komutların çözülmesi ve işlem koordinasyonu sağlar

 #### ARITHMETIC LOGIC UNIT (ALU)
*Toplama, çıkarma vb. gibi mantıksal işlemleri gerçekleştirir

#### REGISTERS
*CPU içerisindeki hızlı çalışan küçük veri saklama yerleridir

#### CACHE MEMORY (ÖNBELLEK)
Yakın zamanda kullanılan veri ve komutlara erişim sağlar

*NOT: CPU performansı çekirdek sayısı vb. faktörlere bağlı olarak değişir

# 2.RAM
*Bilgisayarın çalışmakta olan programların ihtiyaç duyduğu veri ve komutların GEÇİCİ OLARAK saklandığı yerdir
*Temel amaç CPU nun SSD vey HDD gibi yerlere gitmektense RAM den daha kolay ve hızlı şekilde erişimini sağlamaktır
*Elektrik kesildiğinde vs. RAM deki bilgiler silinir, uçucu bellektir
*RAM kapasitesi bilgisayar hızını her zaman etkiler diyemeyiz
*Bilgisayarın RAM kapasitesi yetersiz ise genellikle işletim sistemi bellekteti bazı kısımları takas alanına taşır ve bu da performansı düşürebilir

# CACHE MEMORY
*CPU nun sık kullandığı komutlara hızla erişmesini sağlar.
*RAM den çok daha hızlı çalışır
*L1, L2, L3 gibi seviyeleri vardır
*Cache hit: veri önbellek seviyesinde
*Cache miss: veri önbellek seviyesinde değil

# SSD VE HDD
*Bilgisayarda işletim sistemi, program ve dosyaları KALICI OLARAK depolar
*Bilgisayar kapatıldığında saklanan veriler kaybolmaz
*SSD ve HDD nin görevi aynıdır fakat veriyi kaydetme ve okuma biçimleri farklıdır

# ANAKART
*Bilgisayardaki donanımları birbirine bağlar ve iletişimini sağlar

*Anakartın mimarisi bağlantı kapasitesini etkiler