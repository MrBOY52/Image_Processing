Trafik Güvenliği ve Nesne Tespiti Projesi (YOLOv8)

[![Open In Colab](https://colab.research.google.com/drive/1TrzR3WzneDhdcSw-lnCz9_aAYqeLGkMe?usp=sharing)

Bu proje, Görüntü İşleme dersi kapsamında **YOLOv8** kullanılarak geliştirilmiştir. Projede, karmaşık trafik senaryolarında nesneleri tespit etmek amacıyla **iki farklı model** eğitilmiş ve birleştirilmiştir (Ensemble Learning).

Proje Demo Videosu
Test sonuçlarını ve modelin çalışma performansını izlemek için aşağıdaki linke tıklayınız:

[👉 YouTube Videosunu İzlemek İçin Tıklayın](https://www.youtube.com/playlist?list=PLoe6SaaOuGLO7R84H8P-MemU9CfB9ZvCq)

Kullanılan Modeller ve Yöntem
Proje başarısını artırmak için iki özelleştirilmiş model kullanılmıştır:
1.  **`model_isiklar.pt`**: Sadece trafik ışıkları ve levhalar üzerine eğitilmiştir.
2.  **`model_araclar.pt`**: Araçları (Araba, Otobüs, Kamyon, Motosiklet) tespit etmek için özelleştirilmiştir.
