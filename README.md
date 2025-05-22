
# Enhanced Nutrition Data Analysis
تحلیل داده‌های تغذیه‌ی ارتقایافته

## 📌 Project Description | توضیح پروژه
This project focuses on cleaning, analyzing, and visualizing enhanced nutritional data related to early childhood (e.g. weight, age, and feeding). The dataset is prepared and processed using **Python**, specifically **pandas** and **matplotlib**, inside a Jupyter Notebook.

این پروژه بر روی پاک‌سازی، تحلیل و مصورسازی داده‌های تغذیه‌ای در دوران نوزادی و خردسالی تمرکز دارد. داده‌ها با استفاده از زبان پایتون و کتابخانه‌های پاندا و مت‌پلات‌لیب در نوت‌بوک جوپیتر پردازش شده‌اند.

## 📂 File Structure | ساختار فایل‌ها
```
📁 enhanced_nutrition_data/
│
├── enhanced_nutrition_data.ipynb     # Main Jupyter Notebook
├── data/                             # Folder to store raw or cleaned datasets
├── figures/                          # Plots and saved visualizations
└── README.md                         # Project overview and instructions
```

## 🧪 Key Steps Performed | مراحل کلیدی انجام‌شده
- Data import and preview  
  وارد کردن و نمایش اولیه داده‌ها  
- Duplicate removal  
  حذف داده‌های تکراری  
- Column cleaning and renaming  
  پاک‌سازی و اصلاح نام ستون‌ها  
- Data sorting and type conversions  
  مرتب‌سازی داده‌ها و تبدیل نوع  
- Exploratory Data Analysis (EDA)  
  تحلیل اکتشافی داده‌ها  
- Visualizations using scatter plots and line charts  
  مصورسازی با نمودارهای پراکندگی و خطی  

## 📊 Sample Code Highlight | نمونه کد کلیدی
```python
# Sort values by Age and Weight
df_sorted = df.sort_values(by=["Age (months)", "Weight (kg)"])
```

## 🔧 Libraries Used | کتابخانه‌های استفاده‌شده
- pandas  
- matplotlib.pyplot  
- numpy *(optional)*

## 📌 How to Run | نحوه اجرا
1. Clone this repository:
   ```
   git clone https://github.com/your-username/enhanced_nutrition_data.git
   ```

2. Open the notebook:
   ```
   jupyter notebook enhanced_nutrition_data.ipynb
   ```

## 📎 License | مجوز
This project is released under the MIT License.

## 👤 Author | نویسنده
Elham Jofreh  
[GitHub Profile](https://github.com/elham-jofreh)
