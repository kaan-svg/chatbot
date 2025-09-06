# 🤖 Python Chatbot (NLP & Deep Learning)

Bu proje, **Python + NLP (Natural Language Processing)** kullanılarak geliştirilmiş basit bir **chatbot uygulamasıdır**.  
Amaç: Chatbot geliştirme sürecini öğrenmek isteyenlere örnek bir temel sağlamaktır.  

⚠️ Not: Eğitim sonrası oluşan model dosyaları (`.pkl`, `.h5`) bu repoya dahil edilmemiştir.  
Kullanıcıların **kendi bilgisayarlarında eğitmesi** gerekmektedir.  

---

## ✨ Özellikler
- Kullanıcı cümlesini tokenize etme ve lemmatization (NLTK ile)  
- Bag of Words yaklaşımı  
- TensorFlow/Keras tabanlı basit yapay sinir ağı modeli  
- intents.json üzerinden kolayca yeni cevaplar ekleme  

---

## 🚀 Kurulum
1. Bu repoyu indir veya klonla:
   ```bash
   git clone https://github.com/kullanici-adi/chatbot.git
   cd chatbot
   ```

2. Gerekli kütüphaneleri yükle:
   ```bash
   pip install -r requirements.txt
   ```

---

## 🧠 Modeli Eğitme
1. Eğitim scriptini çalıştır:
   ```bash
   python train.py
   ```
   Bu adımda aşağıdaki dosyalar oluşur:
   - `words.pkl`
   - `classes.pkl`
   - `chatbot_model.h5`

2. Eğitim tamamlandıktan sonra chatbot'u başlatabilirsin.

---

## 💬 Chatbot'u Çalıştırma
```bash
python chatbot.py
```

Ardından terminalde bot ile sohbet edebilirsin:

```
Kullanıcı: Merhaba
Bot: Merhaba! Sana nasıl yardımcı olabilirim?
```

---

## 📂 Proje Yapısı
```
📦 chatbot
 ┣ 📜 chatbot.py         # Ana chatbot dosyası
 ┣ 📜 train.py           # Modeli eğitmek için kullanılan script
 ┣ 📜 intents.json       # Kullanıcı niyetleri ve cevaplar
 ┣ 📜 requirements.txt   # Gerekli kütüphaneler
 ┣ 📜 README.md          # Proje açıklaması
 ┗ 📜 .gitignore         # Gereksiz dosyaları gizler
```

---

## ⚙️ Gereksinimler
- Python 3.8+  
- TensorFlow / Keras  
- NLTK  
- NumPy  

---

## 📌 Katkıda Bulunma
- Yeni intentler ekleyerek chatbot'u geliştirebilirsin.  
- Pull request gönderebilirsin.  

---

## 📜 Lisans
Bu proje öğrenme amaçlıdır, serbestçe kullanılabilir.  
