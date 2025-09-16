# Transportation Data Analysis & ML Dashboard

## پروژه
این پروژه شامل تحلیل داده‌ها و مدل‌سازی ماشین لرنینگ روی دیتاست اطلاعات بارنامه استان قم در سال 1403 (حمل ونقل) است. هدف، استخراج بینش‌های کلیدی، پیش‌بینی، تشخیص ناهنجاری و ارائه داشبورد مدیریتی برای داده‌های حمل‌ونقل می‌باشد.

## محتویات پروژه
- نوت‌بوک‌ها (.ipynb):
  - Transport_Dataset_Doing_EDA.ipynb  
    تحلیل اکتشافی داده‌ها (EDA) و پاکسازی.
  - continuation1_of_Transport_dataset.ipynb  
    مدل‌سازی رگرسیون، طبقه‌بندی و خوشه‌بندی.
- فایل (.zip):  
  - continuation2_of_Transport_dataset (1).zip
    به صورت جزئی تر به مدل های رگرسیون ، خوشه بندی ، تشخیص ناهنجاری ، تحلیل زمانی و تحلیل مکانی و تحلیل کالاها پرداخته شده است

  - Fast_text_embedding_transportation.ipynb  
    انجام word-embedding به روش Fast-Text تحلیل متن مرتبط با داده‌های حمل‌ونقل صورت گرفته است.البته این روش فقط بر روی دیتاست مربوط به ماه بهمن انجام شده است.
## مراحل انجام پروژه
1. EDA (Exploratory Data Analysis)
    -آشنایی اولیه با داده ها
    -بررسی مقادیر گمشده و تکراری
    -بررسی نوع و تعداد داده ها
    -تحلیل تک متغیره
    -تحلیل دو متغیره
    -تحلیل چند متغیره
    -بررسی و پاکسازی داده های پرت
    -بررسی آماری داده‌ها، نمودارهای توزیع و روابط بین ویژگی‌ها.  

2. Machine learning models
3. مدل‌سازی ماشین لرنینگ (ML)
   - رگرسیون خطی (Linear Regression) و XGBoost برای پیش‌بینی مقادیر عددی.
   - بدست آوردن ضریب تعیین (R2-Score) و تابع هزینه به کمک دو معیار میانگین مربعات خطا (MSE) و ماینگین قدرمطلق خطا (MAE)
   - طبقه‌بندی (Classification) با الگوریتم‌های KNN و SVM.
   - خوشه‌بندی (Clustering) با KMeans و GMM.
   - تشخیص ناهنجاری (Anomaly Detection) با Z-Score و Isolation Forest.

4. ویژوالیزیشن به کمک کتابخانه های پایتون 
   - نمودارهای Matplotlib، Seaborn و Plotly برای تحلیل داده‌ها.
5.ایجاد داشبورد مدیریتی 
   - داشبورد مدیریتی ساخته شده با برنامه Power BI (تصاویر نمایش داده شده، فایل اصلی به دلیل حجم بالا در ریپو موجود نیست).  

## اسکرین‌شات داشبورد
![Dashboard Screenshot 1]([screenshots-dashboard/Screenshot 2025-09-05 212552.png](https://github.com/zeinab82jafarzadeh82-star/transport-data-analysis-ml-dashboard/blob/80fd73195999701d1fa93e207f8bd889de29aee9/screenshots-dashboard/Screenshot%202025-09-05%20212552.png)).

![Dashboard Screenshot 2]([[screenshots/dashboard2.png](https://github.com/zeinab82jafarzadeh82-star/transport-data-analysis-ml-dashboard/blob/211a7efca419f5c06bca12a4245f8954fb98a93a/screenshots-dashboard/Screenshot%202025-09-05%20212611.png)](https://github.com/zeinab82jafarzadeh82-star/transport-data-analysis-ml-dashboard/blob/80fd73195999701d1fa93e207f8bd889de29aee9/screenshots-dashboard/Screenshot%202025-09-05%20212611.png)).
![Dashboard Screenshot 3]()

> جایگزین کردن این تصاویر با اسکرین‌شات‌های واقعی داشبورد توصیه می‌شود.

## نتایج کلیدی
- ارائه مدل‌های پیش‌بینی و طبقه‌بندی با دقت مناسب.
- تشخیص ناهنجاری‌ها و شناسایی الگوهای غیرمعمول در داده‌ها.
- ارائه داشبورد مدیریتی برای بررسی سریع داده‌ها و شاخص‌ها.

## نحوه اجرا
1. نوت‌بوک‌ها را در Google Colab باز کنید یا محلی اجرا کنید.
2. دیتاست را از فایل ZIP در مسیر مناسب قرار دهید.
3. کتابخانه‌های مورد نیاز:  
   `bash
   pip install pandas numpy matplotlib seaborn plotly scikit-learn
