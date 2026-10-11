# Screen Time Health Impact AI Predictor

## คำอธิบายโปรเจกต์ (Project Description)
โปรเจกต์นี้เป็นการพัฒนาแบบจำลอง Machine Learning เพื่อวิเคราะห์และทำนายผลกระทบทางสุขภาพที่เกิดจากพฤติกรรมการใช้งานหน้าจอ (Screen Time) โดยประยุกต์ใช้เทคนิค Multi-output Classification และ Regression ในการประเมินความเสี่ยงและวิเคราะห์แนวโน้มสุขภาพจากข้อมูลพฤติกรรมของผู้ใช้งาน

## เทคโนโลยีและไลบรารีที่ใช้ (Technologies & Tools)
* **ภาษาที่ใช้พัฒนา:** Python
* **การจัดการและวิเคราะห์ข้อมูล:** `pandas`, `NumPy`
* **การสร้างแบบจำลอง Machine Learning:** `scikit-learn` 
* **การบันทึกและโหลดโมเดล:** `joblib`
* **ส่วนติดต่อผู้ใช้งานแบบโต้ตอบ (Interactive UI):** `ipywidgets`
* **สภาพแวดล้อมการทำงาน:** Google Colab / Jupyter Notebook

## วิธีการรันโปรเจกต์ (How to Run)
1. เปิดไฟล์ `6710110109_AI_minproject.ipynb` ผ่าน Google Colab
2. ให้อัปโหลดไฟล์ Dataset Indian_Kids_Screen_Time.csv ลงใน Colab
3. รันเซลล์ทั้งหมดเพื่อเทรนโมเดล และใช้งานผ่านอินเทอร์เฟซเพื่อดูผลการทำนาย

## แหล่งอ้างอิง (References)
*American Academy of Pediatrics. (2016). Media use in school-aged children and adolescents. Pediatrics, 138(5), e20162592. https://doi.org/10.1542/peds.2016-2592*

**ที่มาของข้อมูล (Dataset):** 
* Kaggle Dataset. (2024). Indian Kids Screen Time & Health Impacts Dataset.

**เอกสารอ้างอิงทางเทคนิค (Technical Documentation):**
* scikit-learn developers. "scikit-learn: Machine Learning in Python". สืบค้นจาก https://scikit-learn.org/
* The pandas development team. "pandas: powerful Python data analysis toolkit". สืบค้นจาก https://pandas.pydata.org/
* Project Jupyter. "ipywidgets: Interactive HTML widgets for Jupyter notebooks". สืบค้นจาก https://ipywidgets.readthedocs.io/
