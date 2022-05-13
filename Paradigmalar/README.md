# Paradigmalar

Farklı programlama görevleri farklı şekillerde çözülebilir: bir *işlev* yazmanız veya yöntemlerle ayrı bir *sınıf* oluşturmanız vb. gerekebilir. Tüm bu değişkenler, **paradigma** olarak da adlandırılan farklı programlama yaklaşımlarında birleştirilir. Aşağıda iki ana paradigmayı analiz edeceğiz: **Zorunlu** ve **bildirimsel** ve bunların türevleri.

![gorsel](https://ucarecdn.com/024d46aa-b898-4713-b3a7-2c095c94b00e/)

```
Hemen hemen tüm modern diller çoklu paradigmalardır. Zorunlu ve bildirimsel yaklaşımların yeteneklerini kolayca birleştirirler.
```

## Zorunlu Paradigma

Zorunlu paradigma, en eski programlama paradigmalarından biridir. Makina mimarisi ile yakından ilgilidir. İşlemcinin adım adım yürütmesi gereken bir talimat dizisidir. Bu paradigmanın ana odak noktası, hedefe nasıl ulaşılacağıdır. Paradigma birkaç ifadeden oluşur ve hepsini çalıştırdıktan sonra sonuç saklanır.

Örneğin, "Merhaba <kullanıcıadı>!" ifadesini ekranda görüntülemek istiyoruz. Program bunu aağıdaki adımlarla gerçekleştirir:

- kullanıcı adını sor
- kullanıcı adını oku ve hatırla
- sonucu göster

Zorunlu programlama üç geniş kategoriye ayrılır: 

**1. Prosedürel Programlama Paradigması**

**2. Nesne Yönelimli Programlama**

**3. Paralel İleme Yaklaşımı**

## Prosedürel Programlama Paradigması

Prosedürel programlama paradigması, ifadelerin alt rutinler veya işlevler olarak da bilinen prosedürler halinade yapılandırıldığı prosedür çağrıları kavramına dayanmaktadır. Bilgisayara adım adım ne yapacağını söyleyen talimatların bir listesidir. Başka bir deyişle, bilgisayar girdi verilerini alır ve her yeni değişikliği hatırlayarak sırayla değiştirir. Prosedürel ve zorunlu yaklaşımların arasında hiçbir fark yoktur.

Prosedürel programlama, ortak görevleri tamamlamak için genel amaçlı programlama için uygundur. Dolayısıyla bu, faktöriyel hesaplamak, bir şeklin alanını bulmak veya "Merhaba dünya!" gibi bazı bilgileri/ifadeleri göstermek gibi küçük bir hesaplama problemi olabilir. Ayrıca, kod, kopyalamaya gerek kalmadan, programın farklı bölümlerinde yeniden kullanılabilir.

Bu paradigmada yazılan algoritmanın uygulanması çok basittir, ancak oldukça yavaştır vekarmaşık bir sorunu çözemez.

Prosedürel programlama paradigmasını uygulayan programlama dilleri C, Java, C++, ColdFusion, Pascal'dır.

## Nesne Yönelimli Programlama

Nesne yönelimli programlama veya OOP, programın bir sınıf koleksiyonu olarak yazıldığı paradigmadır. Her sınıfın nesneler olarak adlandırılan örnekleri vardır.

Sınıf, genel olarak bir varlığı tanımlamanın,olağan durumu ve bu duruma bağlı davranışı tanımlamanın yanı sıra bu varlıkla etkileşim için olağan kuralları tanımlamanın bir yoludur. Biçimsel olarak bir sınıf, alanlar, nitelikler, sınıf üyeleri ve işlevler gibi bir sizi veri, yani onlarla çalışma yöntemleri olarak görülür.

Örneğin, bir *kedimiz* var ve onu bir sınıf olarak tanımlamak istiyoruz. Böylece *kedi, ilgiliz Kedi* sınıfının bir nesnesi olacaktır. Bir kedinin bazı özellikleri vardır. Kuyruk, patiler, kulaklar, bıyıklar. Bir kedinin davranışı genellikle yaptığı şeylerdir. Koşabilir, zıplayabilir, miyavlayabilir, yiyebilir ve duvar kağıdını yırtabilir. Bunların hepsi *kedi* yöntemleri olacak.

OOP, tipik nesneleri modellemeniz ve onlarla çalışmanız gereken hemen hemen her türlü yaygın yaşam problemini halledebilir.

OOP uygulayan programlama dilleri Ruby, Java, C++, Python, Simula(ilk OOP dili), Smalltalk, Visual Basic .NET, Objective-C'dir.

## Paralel İşleme Yaklaşımı

Paralel işleme, talimat yürütme süresini azaltmaya yardımcı olur. Bunu, talimatları birden çok işlemci arasında paylaşarak veya paralel hale getirerek yapar. Yaklaşımın anlamı tek bir cümleyle özetlenebilir: "böl ve yönet". Örnekler, NESL(en eskilerden biri) ve C/C++'tır.

## Bildirim Paradigması

Bildirimsel programlama, sorunun ve çözümün beklenen sonucunu belirtmenin önemli olduğu bir programlama paradigmasıdır. Yani, "bu nasıl yapılır?" sorusuna cevap vermenin gerekli olduğu zorunlu paradigmanın aksine, "ne yapılması gerekiyor?" ve "çalışmanın sonucu ne olacak?" sorularını sormamız gerekiyor. Bu nedenle, adım adım talimat vermek yerine, sisteme neye ihtiyacımız olduğunu söyleyin ve bir çözüm bulmaya çalışmasına izin verin.

![gorsel](https://ucarecdn.com/708d0047-47c5-45c6-834b-18db7b1d1865/)

Bildirime dayalı programlama,
- Mantık
- İşlevsel
- Veritabanı

paradigma türlerine ayrılır.

## Mantıksal Programlama Paradigması

Mantıksal programlama, ağırlıklı olarak biçimsel mantığa dayanan bir programlama paradigmasıdır. Mantıksal bir programlama dilinde yazılmış herhangi bir program, belirli bir sorun alanıyla ilgili gerçekleri ve kuralları ifade eden mantıksal biçimdeki bir dizi cümledir.

Bu nedenle, mantıksal programlamanın temel ifadeleri aşağıdaki gibidir:
- **Gerçekler**, "Sokrates bir erkektir." gibi, sorun alanıyla ilgili temel iddialardır.
- **Kurallar**, alandaki gerçeklerle ilgili çıkarımlardır. ("Bütün insanlar ölümlüdür.")
- **Sorgular**, o alanla ilgili sorulardır. ("Sokrates ölümlü müdür?")

Genel olarak, buradaki görev, gerçeklere ve kurallara dayanarak sorgunun cevabını bulmaktır.

Mantıksal programlama dillerinin ana aileleri arasında Prolog, Answer Set Programming (ASP) ve Datalog bulunur.

## Fonksiyonel Programlama Paradigması

Fonksiyonel programlama , hesaplama sürecinin fonksiyonların değerlerinin hesaplanması olarak yorumlandığı bir programlama paradigmasıdır. Bu durumda fonksiyon matematiksel olana benzer. Yani, girdinin değişmeyen bir dizi olduğu ve çıktının yeni veriler içeren yeni bir dizi olduğu bir fonksiyon. Bu, matematiksel bir işlevi, bir işlevin orijinal verileri değiştiren bir eylemler dizisi olduğu prosedürel programlamadaki bir işlevden farklı kılar.

İşte basit bir örnek: Girdi olarak bir sayı listesi alan ve bu sayıların kareleriyle yeni bir liste döndüren bir işleviniz olabilir. Bu, orijinal numara listesini değiştirmez.

İşlevsel programlama paradigmasını uygulayan programlama dilleri JavaScript, Haskell, Scala, Erlang, Lisp, ML, Clojure, OCaml, Common Lisp ve F#'dir.

## Veritabanı Programlama Paradigması

Bu programlama metodolojisi verilerle çalışmaya dayanmaktadır. Veriler veritabanında saklanır ve bu veritabanına özel bir dilde, örneğin SQL'de sorgular yapılır. Bu dillerle filtreleme, dönüştürme, istatistik hesaplama vb. için verilere erişebilirsiniz. Program ifadeleri, sabit kodlanmış bir dizi adımdan ziyade veri tanımlıdır.

Veritabanı programı, iş bilgi sisteminin kalbidir ve dosya oluşturma, veri girişi, güncelleme, sorgulama ve raporlama işlevlerine izin verir.
