Mijozlar xulq-atvori tahlili:
​<img width="1247" height="470" alt="grafiglar" src="https://github.com/user-attachments/assets/b6bdaf0c-860e-4cb2-a31c-357c5b010abe" />
​Rasm: Mijozlarning yoshi, kredit ballari va balans taqsimoti.
​Asosiy xulosalar:
​Mijozlarning aksariyati 30-40 yosh oralig'ida.
​Hisobida 0 mablag'i bo'lgan mijozlar soni sezilarli darajada ko'p (bu model uchun muhim indikator bo'lishi mumkin).
​Target o'zgaruvchi (Ketgan va Qolgan mijozlar):
​<img width="404" height="405" alt="grafig" src="https://github.com/user-attachments/assets/65f53487-363e-41c1-bc98-f9a69d3b2186" />
​Rasm: Bankda qolgan (0) va bankdan ketgan (1) mijozlar nisbati.
​🤖 Ishlatilgan Algoritmlar
​Loyihada eng yaxshi natijani aniqlash uchun ikkita kuchli algoritm sinab ko'rildi:
​Random Forest Classifier: Parallel daraxtlar yordamida yuqori aniqlikni ta'minladi.
​XGBoost: Gradient boosting usuli orqali model xatoliklarini minimallashtirdi.
​📉 Model Natijalari (Evaluation)
​Har ikkala model ham yaxshi natija ko'rsatdi, ayniqsa XGBoost va Random Forest bir-biriga yaqin aniqlik (Accuracy) qayd etdi. Modelning xatoliklarini ko'rish uchun Confusion Matrix tahlil qilindi.
​Confusion Matrix (Model xatoliklarini tekshirish):
​Random Forest (Confusion grafik) <img width="528" height="413" alt="confusion XGBoost" src="https://github.com/user-attachments/assets/034d6eb8-29bb-4fc7-bceb-8d3058661084" />
XGBoost (Confusion grafik) <img width="528" height="413" alt="confusion RF" src="https://github.com/user-attachments/assets/58a6adf5-6c5d-4e19-9fe6-6d992c3e1d11" />
​Rasm: Modelning bashorat qilish aniqligi (Confusion Matrix).
​Asosiy Metrikalar:
​Model Aniqligi (Accuracy): ~85-84%
​F1-Score: Mijozlar oqimini aniqlashda muvozanatli natija ko'rsatildi.
​🛠 O'rnatish va Ishga tushirish
​Loyihani o'z kompyuteringizda ishga tushirish uchun:
1. Repozitoryani yuklab oling

git clone https://github.com/ixloss/bank-customer-churn-prediction.git

3. Kerakli kutibxonalarni o‘rnating

pip install pandas scikit-learn xgboost matplotlib seaborn

📝 Xulosa​
Ushbu model bankka ketish ehtimoli yuqori bo'lgan mijozlarni 85% dan yuqori aniqlikda topish imkonini beradi. Kelgusida modelni SMOTE usuli bilan boyitish orqali Recall ko'rsatkichini yanada oshirish rejalashtirilgan.
​Muallif: [Sizning Ismingiz]
Loyiha sanasi: 2026-yil aprel
