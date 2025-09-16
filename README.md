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

![Dashboard Screenshot 2]([screenshots-dashboard/Screenshot 2025-09-05 212611.png](https://github.com/zeinab82jafarzadeh82-star/transport-data-analysis-ml-dashboard/blob/42ed9dd3935af8943420f7ba9a5626e2c746b9a8/screenshots-dashboard/Screenshot%202025-09-05%20212611.png)).

![Dashboard Screenshot 3]([screenshots-dashboard/Screenshot 2025-09-05 212620.png](https://github.com/zeinab82jafarzadeh82-star/transport-data-analysis-ml-dashboard/blob/31ac5c85acad91c64e2386181534b50d9996db9c/screenshots-dashboard/Screenshot%202025-09-05%20212620.png))

![Dashboard Screenshot 4]([screenshots-dashboard/Screenshot 2025-09-05 212633.png](https://github.com/zeinab82jafarzadeh82-star/transport-data-analysis-ml-dashboard/blob/1d920e637bd795e0d76dfff26774ab049489e799/screenshots-dashboard/Screenshot%202025-09-05%20212633.png))

![Dashboard Screenshot 5]([screenshots-dashboard/Screenshot 2025-09-05 212646.png](https://github.com/zeinab82jafarzadeh82-star/transport-data-analysis-ml-dashboard/blob/b42353eb532cbf934a45511babfd4bdbb5d402bc/screenshots-dashboard/Screenshot%202025-09-05%20212646.png))

![Dashboard Screenshot 6]([screenshots-dashboard/Screenshot 2025-09-05 212656.png](https://github.com/zeinab82jafarzadeh82-star/transport-data-analysis-ml-dashboard/blob/cda047ba824638912b48543afdf005c7f05d9035/screenshots-dashboard/Screenshot%202025-09-05%20212656.png))


## نتایج کلیدی
- ارائه مدل‌های پیش‌بینی و طبقه‌بندی با دقت مناسب.
- تشخیص ناهنجاری‌ها و شناسایی الگوهای غیرمعمول در داده‌ها.
- ارائه داشبورد مدیریتی برای بررسی سریع داده‌ها و شاخص‌ها.
- توضیح نتایج بدست آمده و توضیح خط به خط کدها در pdfهای باگذاری شده به نام های report1 و report2 ذخیره شده اند.
- ([report1.pdf](https://github.com/zeinab82jafarzadeh82-star/transport-data-analysis-ml-dashboard/blob/f982ee8ecca65d94195dbffc38fe11da06e965fb/report1.pdf)).

- ([report2.pdf](https://github.com/zeinab82jafarzadeh82-star/transport-data-analysis-ml-dashboard/blob/8892b87d6697cb9d29c88f37a2c19d8071494584/report2.pdf)).

## نحوه اجرا
1. نوت‌بوک‌ها را در Google Colab باز کنید یا محلی اجرا کنید.
2. دیتاست را از https://docs.google.com/spreadsheets/d/11P00K5w4Bf0rVSkWlwHUBQkWHT5lY1UW/edit?usp=drive_link&ouid=113637278991604905747&rtpof=true&sd=true  
