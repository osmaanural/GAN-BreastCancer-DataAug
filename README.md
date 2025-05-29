# GAN-BreastCancer-DataAug

Medikal görüntülerdeki görüntü sayısının az olması, derin öğrenem modellerinin sınıfı tanımlamasında zorluk çıkarmaktadır. Görüntü sayımız ne kadar fazla ise model daha iyi öğrenebilmektedir. Bu nedenle Meme Mamografi görüntülerinin GAN ile arttılıması sağlanmıştır. Bu aşamada  50 tanne görüntü üretilmiştir. Görüntü sayısı arttırılabilir.

🟥 GAN - Generative Adversarial Networks (Çekişmeli Üretici Ağ)

Birbirine karşı çalışan iki yapay sinir ağı kullanılarak eğitilen bir derin öğrenme modelidir. Bu ağlardan Üretici Ağ (Generator) veri üretir, Ayırt Edici Ağ (Discriminator) ise üretilen verinin gerçek mi yoksa sahte mi olduğunu ayırt etmek için değerlendirir.

Eğitim sürecinde:

⚫ Generator, gürültü vektöründen sahte veriler üretir.

⚫ Discriminator, bu görüntünün gerçek mi yoksa sahte mi olduğunu ayırt etmeye çalışır.

⚫ Generator, Discriminator’ı kandırmaya çalışır.

⚫ Discriminator, daha iyi ayırt etmeye çalışır.

Böylelikle iki ağ birbirini geliştirir.

Generator’ın amacı, Discriminator’ın daha fazla hata yapmasını sağlayacak fotoğraflar üretmek iken; Discriminator’un amacı, gerçek fotoğrafları sahte olanlardan daha iyi ayırt etmektir. 
