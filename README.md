\# 😊😠 Hugging Face ile Türkçe Duygu Analizi



Bu proje, son teknoloji bir Doğal Dil İşleme (NLP) modeli kullanarak, verilen Türkçe cümlelerin duygu (pozitif/negatif) analizini gerçekleştirmektedir. Projede, \*\*Hugging Face Transformers\*\* kütüphanesi ve bu kütüphane aracılığıyla sunulan, Türkçe için özel olarak eğitilmiş bir \*\*BERT\*\* modeli kullanılmıştır.



\## 🎯 Projenin Amacı



Bu projenin amacı, Transfer Learning'in metin verileri üzerindeki gücünü göstermek ve sadece birkaç satır kod ile karmaşık bir NLP görevinin nasıl çözülebileceğini ortaya koymaktır. Bu teknoloji, müşteri yorumlarını analiz etmek, sosyal medya trendlerini takip etmek veya marka imajını ölçmek gibi birçok ticari uygulamada kullanılabilir.



\## ✨ Kullanılan Model



Projede, `savasy/bert-base-turkish-sentiment-cased` isimli, Hugging Face platformunda paylaşılan ve Türkçe metinler üzerinde duygu analizi yapmak için ince ayar (fine-tuning) yapılmış bir BERT modeli kullanılmıştır. `Transformers` kütüphanesinin `pipeline` aracı sayesinde bu güçlü modeli kullanmak oldukça basittir.



\## 📈 Sonuçlar



Model, test edilen çeşitli cümleler üzerinde yüksek bir başarıyla duygu analizi yapmıştır:



\* \*\*Cümle:\*\* "Bu filme bayıldım, kesinlikle harikaydı!"

&nbsp;   \* \*\*Tahmin:\*\* `POSITIVE` (Skor: ~0.99)

\* \*\*Cümle:\*\* "Hayatımda izlediğim en sıkıcı ve berbat filmdi."

&nbsp;   \* \*\*Tahmin:\*\* `NEGATIVE` (Skor: ~0.99)

\* \*\*Cümle:\*\* "Bu ürün fena değil, işimi gördü."

&nbsp;   \* \*\*Tahmin:\*\* `POSITIVE` (Skor: ~0.85)



\## 💻 Kullanılan Teknolojiler

\* Python

\* PyTorch

\* Hugging Face Transformers (BERT)

