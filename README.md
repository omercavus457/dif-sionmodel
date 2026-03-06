# dif-sionmodel
🛠️ Kullanılan Teknolojiler ve Kütüphaneler
Proje tamamen Python ekosistemi üzerinde geliştirilmiş olup aşağıdaki kütüphaneleri kullanmaktadır:

Diffusers: UNet2DModel mimarisi ve eğitim döngüsü için.

Transformers (Hugging Face): Swin2SR pre-trained upscaler modelinin entegrasyonu için.

PyTorch: Derin öğrenme altyapısı ve GPU optimizasyonu (TF32/CUDNN) için.

Gradio: Kullanıcı dostu bir Web arayüzü sunmak için.

BitsAndBytes: 8-bit Adam optimizer ile bellek tasarrufu ve hız artışı için.

OpenCV & Pillow: Görüntü onarma, keskinleştirme ve post-processing işlemleri için.

Accelerate: Donanım hızlandırma desteği için.

🔗 Çalıştırma (Google Colab)
Projeyi doğrudan Google Colab üzerinde denemek için aşağıdaki bağlantıyı kullanabilirsiniz:

https://colab.research.google.com/drive/174z6c-aE2R4I81Mt3eoemh4NFw_133lh?usp=sharing

📋 Nasıl Kullanılır?
Colab linkine tıklayın ve tüm hücreleri çalıştırın.

Gradio tarafından oluşturulan public URL bağlantısına tıklayın.

Inference Steps slider'ını kullanarak detay seviyesini ayarlayın (Öneri: 80+).

"Yüz Üret" butonuna basarak yapay zeka tarafından oluşturulan ve onarılan sonucu görün.
