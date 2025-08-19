# 🌍 QS World University Rankings 2025 Analizi

Bu proje, **QS World University Rankings 2025** verilerini kullanarak üniversitelerin performans metriklerini incelemeyi amaçlamaktadır.  
Çalışmada kategorik değişkenler (**RES., SIZE, FOCUS, STATUS**) ile sayısal skorlar (**Academic Reputation, Employer Reputation, Citations per Faculty, Faculty Student Ratio, International Faculty, International Students, International Research Network, Employment Outcomes, Sustainability**) arasındaki ilişkiler **keşifsel veri analizi (EDA)** ve **görselleştirmeler** ile araştırılmıştır.

---

## 📂 Veri Seti
- **Kaynak:** QS World University Rankings 2025  
- **Kategorik Değişkenler:**
  - `RES.` → Araştırma yoğunluğu
  - `SIZE` → Üniversite büyüklüğü
  - `FOCUS` → Akademik odak türü
  - `STATUS` → Üniversite statüsü  
- **Sayısal Skorlar:**
  - Academic Reputation  
  - Employer Reputation  
  - Faculty Student Ratio  
  - Citations per Faculty  
  - International Faculty  
  - International Students  
  - International Research Network  
  - Employment Outcomes  
  - Sustainability  

---

## ⚙️ Kullanılan Teknolojiler

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical-orange?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-red?logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-blueviolet)
![Openpyxl](https://img.shields.io/badge/Openpyxl-Excel-lightgreen)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)

---

## 🔎 Analiz Adımları
1. Veri setini yükleme ve ön işleme  
2. Eksik değer analizi  
3. Sayısal skorların dağılımlarını inceleme  
4. Kategorik değişkenlere göre grup karşılaştırmaları  
5. Bulguların görselleştirilmesi (heatmap, boxplot, bar chart)  
6. Veri seti hikâyesi çıkarma  

---

## 📊 Önemli Bulgular
- **Araştırma yoğunluğu (RES.)** ve **üniversite büyüklüğü (SIZE)**, performans skorlarını en çok etkileyen faktörler olarak öne çıkmaktadır.  
- **FOCUS** ve **STATUS**, özellikle itibar skorlarıyla ilişkili farklılıklar göstermektedir.  
- **Uluslararası öğrenci ve fakülte oranları**, bu kategorilere göre belirgin bir farklılık göstermemektedir.  

---

## 📝 Veri Seti Hikayesi
> Araştırma odaklı ve büyük ölçekli üniversiteler, küresel ölçekte görünürlük ve atıf bazlı metriklerde öne çıkarken; küçük ve uzmanlaşmış kurumlar öğrenci deneyimi ve bazı niş alanlarda fark yaratmaktadır. Üniversitenin odak türü ve statüsü itibarı etkileyebilirken, uluslararası öğrenci ve öğretim üyesi oranları daha çok ülke politikaları ve coğrafi faktörlere bağlıdır.
