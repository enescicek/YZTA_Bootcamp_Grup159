# Takım ismi

Yapay Zeka Grup 159

# Takım Üyeleri

Safiye Alaca

Hilal Doganer

Oğuz Kuşeli

Emir Efe Yurtseven

Enes Çiçek

# Proje İsmi 

🧠 Coach AI

# Açıklama

Coach AI'nin temel hedefi:
- Kullanıcıların daha verimli ve hızlı gelişmesini sağlamak
- Antrenör ihtiyacını azaltarak maddi gideri ortadan kaldırmak
- Kişiselleştirilmiş günlük egzersiz planı, motivasyon mesajı ve gelişim takibi sunmak

## 🧰 Kullanılan Teknolojiler

- **Python**  
- **FastAPI**  
- **OpenAI GPT-4o (LLM)**  
- **CORS Middleware**  
- **RESTful API** yapısı

#SPRINT 1 

- Temel olarak projede nasıl ilerleneceği konuşuldu.
- Görev dağılımı yapıldı
- proje hazır olmasa da ayağa kaldırıldı.

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
