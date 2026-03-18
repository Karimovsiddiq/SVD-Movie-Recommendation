# 🎬 Movie Recommendation System using SVD

Ushbu loyihada MovieLens (100k) ma'lumotlar bazasidan foydalanib, foydalanuvchilarning yashirin didini aniqlovchi Kollaborativ Filtrlash (Collaborative Filtering) tizimi qurildi.

## 🎯 Loyihaning asosiy yutuqlari:
* **SVD Algoritmi:** Scikit-Surprise kutubxonasi yordamida Matrix Factorization amalga oshirildi.
* **Aniqlik (RMSE):** Model 0.93 xatolik darajasi bilan yuqori aniqlikni ko'rsatdi.
* **Tavsiya (Top-10):** Foydalanuvchi hali ko'rmagan kinolar orasidan eng yuqori ball olishi kutilayotgan 10 ta kino (masalan: Casablanca, Schindler's List) saralab berildi.
* **Anti-Tavsiya Eksperimenti:** Modelning adekvatligini tekshirish uchun "Eng yomon 10 ta kino" ham bashorat qilindi va model mantiqan to'g'ri ishlashi (1-2 ballik kinolarni topishi) isbotlandi.

## 🛠 Texnologiyalar:
* Python, Pandas, Numpy
* Scikit-Surprise (SVD, Dataset, Reader)
