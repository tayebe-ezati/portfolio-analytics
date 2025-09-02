# Titanic Analysis  

A simple project for analyzing the Titanic dataset.  

## Project Structure
- `data/` : raw and processed datasets  
- `outputs/` : charts, reports, and results  
- `scripts/` : helper python scripts  
- `titanic_analysis.ipynb` : main Jupyter notebook with analysis  
- `requirements.txt` : dependencies  

## How to Run
1. Clone this repo  
2. Create a virtual environment  
3. Install dependencies:  
   ```bash
   pip install -r requirements.txt
# Titanic Survival Analysis

## 📌 خلاصه مسئله
هدف این پروژه بررسی این است که چه عواملی روی شانس زنده ماندن مسافران کشتی تایتانیک تأثیرگذار بوده است.  
ما بررسی می‌کنیم که جنسیت، کلاس بلیت و سن چه ارتباطی با بقا داشته‌اند.

---

## 📊 دیتاست
داده‌ها شامل ۸۹۱ مسافر کشتی تایتانیک است. ستون‌های اصلی عبارتند از:
- **Survived**: وضعیت بقا (0 = فوت، 1 = نجات یافته)
- **Sex**: جنسیت (مرد یا زن)
- **Pclass**: کلاس بلیت (۱، ۲، ۳)
- **Age**: سن مسافر
- سایر ستون‌ها مانند Ticket, Fare, Cabin

---

## ❓ سوال‌های اصلی
1. آیا جنسیت روی شانس بقا تأثیر داشته است؟
2. آیا کلاس بلیت روی شانس بقا تأثیر داشته است؟
3. آیا سن روی شانس بقا تأثیر داشته است؟

---

## 📈 نمودارها
- Survival Rate by Gender  
- Survival Rate by Passenger Class  
- Survival by Age  

📂 خروجی نمودارها در پوشه `outputs/` ذخیره شده‌اند.

---

## ✅ نتایج
- زن‌ها شانس بیشتری برای بقا داشتن.  
- کودکان بیشتر از بزرگسالان نجات پیدا کردن.  
- مسافران طبقه ۱ شانس بیشتری برای بقا داشتن نسبت به طبقه ۳.
