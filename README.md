# 🧠 Coach AI

Yapay zeka destekli kişisel fitness koçu.  
Coach AI, kullanıcıların yaş, boy, kilo ve hedeflerine göre günlük antrenman ve motivasyon önerileri sunarak, evde kişisel gelişimi kolaylaştıran bir yapay zeka uygulamasıdır.

---

## 🎯 Amaç

Coach AI'nin temel hedefi:
- Kullanıcıların daha verimli ve hızlı gelişmesini sağlamak
- Antrenör ihtiyacını azaltarak maddi gideri ortadan kaldırmak
- Kişiselleştirilmiş günlük egzersiz planı, motivasyon mesajı ve gelişim takibi sunmak

---

## 🧰 Kullanılan Teknolojiler

- **Python**  
- **FastAPI**  
- **OpenAI GPT-4o (LLM)**  
- **CORS Middleware**  
- **RESTful API** yapısı

---

## 📸 Demo

> Aşağıda örnek bir sohbet isteği ve LLM cevabı yer alır:

**POST /chat**

```json
{
  "message": "Bugün ne çalışayım?",
  "user": {
    "age": 24,
    "height": 178,
    "weight": 74,
    "goal": "kilo vermek"
  }
}

