Trafik Güvenliği ve Nesne Tespiti Projesi (YOLOv8)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1TrzR3WzneDhdcSw-lnCz9_aAYqeLGkMe?usp=sharing)

Bu proje,Bitirme Projesi dersi kapsamında **YOLOv8** kullanılarak geliştirilmiştir. Projede, karmaşık trafik senaryolarında nesneleri tespit etmek amacıyla **iki farklı model** eğitilmiş ve birleştirilmiştir (Ensemble Learning).

Proje Demo Videosu
Test sonuçlarını ve modelin çalışma performansını izlemek için aşağıdaki linke tıklayınız:

[👉 YouTube Videosunu İzlemek İçin Tıklayın](https://www.youtube.com/playlist?list=PLoe6SaaOuGLO7R84H8P-MemU9CfB9ZvCq)

Kullanılan Modeller ve Yöntem
Proje başarısını artırmak için iki özelleştirilmiş model kullanılmıştır:
1.  **`model_isiklar.pt`**: Levhalar ve yaya geçitleri üzerine eğitilmiştir.
2.  **`model_araclar.pt`**: Araçları tespit etmek için özelleştirilmiştir.
