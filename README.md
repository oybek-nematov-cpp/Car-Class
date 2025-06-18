# 🚗 C# OOP Project: Car, PassengerCar, and CargoCar

✅ Bu loyiha C# dasturlash tilida yozilgan va **obyektga yo‘naltirilgan dasturlash (OOP)** konseptlarini — ya'ni **meros olish (inheritance)**, **property**, va **metod overriding**ni namoyish etadi.

---

## 📦 Loyiha mazmuni

Ushbu dasturda quyidagi klasslar mavjud:

### 1. `Car` (Asosiy klass)
- Xususiyatlar:
  - `Brend`
  - `Name`
  - `Speed`
  - `Price`
- Metod:
  - `ShowInfo()` — mashina haqida umumiy ma’lumotni chiqaradi.

### 2. `PassangerCar` (Voris klass)
- `Car` klassidan meros oladi.
- Qo‘shimcha xususiyat:
  - `Soni` — yo‘lovchilar soni
- `ShowInfo()` metodi `Car` metodini kengaytiradi va yo‘lovchi sonini chiqaradi.

### 3. `CargoCar` (Voris klass)
- `Car` klassidan meros oladi.
- Qo‘shimcha xususiyat:
  - `YukUchun` — yuk tashishga mosligini bildiradi
- `ShowInfo()` metodi yuk uchun mosligini ko‘rsatadi.

---

## ▶️ Ishga tushirish

### ⚙️ Talablar:
- .NET SDK (6.0 yoki yuqoriroq)
- Visual Studio yoki VS Code

### 🏁 Ishga tushirish uchun:
```bash
dotnet run
```
[t.me/Oybek_FN](https.//t.me//Oybek_FN)
