# Transportation Data Analysis & ML Dashboard

## پروژه
این پروژه شامل تحلیل داده‌ها و مدل‌سازی ماشین لرنینگ روی دیتاست اطلاعات بارنامه استان قم در سال 1403 (حمل ونقل) است. هدف، استخراج بینش‌های کلیدی، پیش‌بینی، تشخیص ناهنجاری و ارائه داشبورد مدیریتی برای داده‌های حمل‌ونقل می‌باشد.

### دیتاست اطلاعات بارنامه استان قم در سال 1403
این دیتاست دارای 43 ویژگی و ستون است و تعداد رکوردهای این دیتاست حدود 600000 است. نام ستون های این دیتاست به شرح زیر است :
Value added insurance , premium	Received from the driver , Scale fee	Evacuation fee	, added value	Complications of moving goods	, Bill of lading registration time	, Tracking code watch	Date of interception	, Company commission ,	Insurance amount ,	Loading fee ,	Total fare	, Recipient's national ID	, Sender's National ID	, Postal code of recipient	, Postal code of the sender	Interception	, Device smart card	, Driver smart card ,	Packaging code ,	License plate code ,	Serial code	, License plate number	,	Delivery date ,	Date of issue ,	Loader code	, The name of the destination city ,	Destination city code ,	Name of the city of origin ,	Code of the city of origin ,	product name ,	Product code ,	distance ,	weight ,	Calculation fare	, rent ,	bill of lading number ,	Bill of lading series ,	Company name ,	Company code ,	year.
<img width="345400" height="1330" alt="image" src="https://github.com/user-attachments/assets/afd37fab-dbbc-4506-a170-94fa0fc285f2" />


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

3. Machine learning models
   - رگرسیون خطی (Linear Regression) و XGBoost برای پیش‌بینی مقادیر عددی.
   - بدست آوردن ضریب تعیین (R2-Score) و تابع هزینه به کمک دو معیار میانگین مربعات خطا (MSE) و ماینگین قدرمطلق خطا (MAE)
   - طبقه‌بندی (Classification) با الگوریتم‌های KNN و SVM.
   - خوشه‌بندی (Clustering) با KMeans و GMM.
   - تشخیص ناهنجاری (Anomaly Detection) با Z-Score و Isolation Forest.

4. ویژوالیزیشن به کمک کتابخانه های پایتون 
   - نمودارهای Matplotlib، Seaborn و Plotly برای تحلیل داده‌ها.
4.ایجاد داشبورد مدیریتی 
   - داشبورد مدیریتی ساخته شده با برنامه Power BI (تصاویر نمایش داده شده، فایل اصلی به دلیل حجم بالا در ریپو موجود نیست).  

## اسکرین‌شات داشبورد
![Dashboard Screenshot 1]([screenshots-dashboard/Screenshot 2025-09-05 212552.png](https://github.com/zeinab82jafarzadeh82-star/transport-data-analysis-ml-dashboard/blob/93e610a5b0217afa7b17f00e114227d3d76c3808/screenshots-dashboard/Screenshot%202025-09-05%20212552.png)).

![Dashboard Screenshot 2]([screenshots-dashboard/Screenshot 2025-09-05 212611.png](https://github.com/zeinab82jafarzadeh82-star/transport-data-analysis-ml-dashboard/blob/42ed9dd3935af8943420f7ba9a5626e2c746b9a8/screenshots-dashboard/Screenshot%202025-09-05%20212611.png)).

![Dashboard Screenshot 3]([screenshots-dashboard/Screenshot 2025-09-05 212620.png](https://github.com/zeinab82jafarzadeh82-star/transport-data-analysis-ml-dashboard/blob/31ac5c85acad91c64e2386181534b50d9996db9c/screenshots-dashboard/Screenshot%202025-09-05%20212620.png))

![Dashboard Screenshot 4]([screenshots-dashboard/Screenshot 2025-09-05 212633.png](https://github.com/zeinab82jafarzadeh82-star/transport-data-analysis-ml-dashboard/blob/1d920e637bd795e0d76dfff26774ab049489e799/screenshots-dashboard/Screenshot%202025-09-05%20212633.png))

![Dashboard Screenshot 5]([screenshots-dashboard/Screenshot 2025-09-05 212646.png](https://github.com/zeinab82jafarzadeh82-star/transport-data-analysis-ml-dashboard/blob/b42353eb532cbf934a45511babfd4bdbb5d402bc/screenshots-dashboard/Screenshot%202025-09-05%20212646.png))

![Dashboard Screenshot 6]([screenshots-dashboard/Screenshot 2025-09-05 212656.png](https://github.com/zeinab82jafarzadeh82-star/transport-data-analysis-ml-dashboard/blob/cda047ba824638912b48543afdf005c7f05d9035/screenshots-dashboard/Screenshot%202025-09-05%20212656.png))


## نتایج کلیدی
- ارائه مدل‌های پیش‌بینی و طبقه‌بندی با دقت مناسب.
- تشخیص ناهنجاری‌ها و شناسایی الگوهای غیرمعمول در داده‌ها.
- ارائه داشبورد مدیریتی برای بررسی سریع داده‌ها و شاخص‌ها.
- مدل Linear Regression (پیش بینی کرایه کل (Total Fare) براساس وزن ، مسافت و نوع محصول): R2 Score = 0.70 , MSE =24632941.75 , MAE  = 1420292186426666.8
- مدل Linear Regression برای تخمین مبلغ بیمه (Insurance Amount): R2 Score = 0.94 , MSE = 1792863055296.0906 , MAE = 117660.76
- خوشه بندی راننده ها به روش KMeans Clustering : رانندگان به 4 خوشه دسته بندی شدند که نام های خوشه ها به این ترتیب است :'راننده متعادل و نرمال' و 'را ننده های سریع و سنگین بار' و 'راننده ها خیلی کند و پراکنده' و 'راننده های سریع و پرکار (سبک بار)'.
- مدل Gaussian Mixture Model (GMM) برای خوشه بندی شرکت ها : شرکت ها به 4 خوشه تقسیم بندی شدند.
- خوشه بندی مسیرها براساس تاخیر ، مسافت و کرایه با استفاده از روش KMeans Clustering : مسیرها به 4 خوشه با نام های مسیر کوتاه و کم کرایه ، مسیر نسبتا کوتاه و نسبتا کم کرایه ، مسیر طولانی و نسبتا کم کرایه ، مسیر نسبتا کوتاه و کرایه زیاد دسته بندی شدند.
- تشخیص ناهنجاری برای پیدا کردن بارهایی با کرایه های بسیار بیشتر و یا کمتر از معمول : حدود 99.7% داده ها ، نرمال تشخیص داده می شوند و فقط 3% از داده ها ، داده های پرت هستند.
- تشخیص ناهنجاری برای کرایه با استفاده از روش جنگل انزوا (Isolation Forest):طبق نموداری که در نوت بوک موجود است داده های پرت با رنگ آبی و نقاط عادی با رنگ زرد نمایش داده شده اند.
- تحلیل فصلی برای حمل بعضی محصولات خاص (در چه فصلی حمل بعضی محصولات بیشتر است؟): بیشترین تعداد حمل برای کالای تخم مرغ است و در فصل پاییز بوده است، در فصل بهار بالاترین تعداد حمل متعلق به سیمان فله تیپ 2 است ، در فصل تابستان کالای سیمان فله تیپ 2 با تعداد حمل 8624 است.در فصل زمستان کالای تخم مرغ با تعداد حمل 8283 است.
- نقشه مسیرهای پرتردد: ، شهر قم به عنوان پرتکرار ترین مبدا و پس از آن نیزار . سلفچگان قرار دارند. شهر تهران به عنوان پرتکرارترین مقصد و پس از آن شهر قم و بندرعباس قرار دارند.
- تحلیل هزینه به ازای کیلومتر برای هر مسیر : مسیر قم-گمرک قم بیشترین مقدار میانگین هزینه برحسب کیلومتر را با 4.33333 میلیون دارد که تعداد حمل حالا هم فقط 1 بوده است. این مسیر یک مسیر خیلی کوتاه است و کرایه به ازای هر کیلومتر خیلی بالاست.
- بیشترین حمل مربوط به چه کالایی است ؟ :  بیشترین حمل کالا مربوط به تخم مرغ با تعداد حمل k30.178 و رتبه ی دوم مربوط به سیمان فله تیپ 2 با تعداد حمل k 29.312 و پس از لوازم خانگی و آهن آلات و ... قرار دارند.
- در فایل Fast_text_embedding_transportation.ipynb  توانستیم با استفاده از fast-text و روش خوشه بندی KMeans ، محصولات را خوشه بندی و محصولات در 12 خوشه دسته بندی شدند. 
- توضیح بیشتر و جامع تر از نتایج بدست آمده و توضیح خط به خط کدها در pdfهای باگذاری شده به نام های report1 و report2 ذخیره شده اند.
- ([report1.pdf](https://github.com/zeinab82jafarzadeh82-star/transport-data-analysis-ml-dashboard/blob/f982ee8ecca65d94195dbffc38fe11da06e965fb/report1.pdf)).

- ([report2.pdf](https://github.com/zeinab82jafarzadeh82-star/transport-data-analysis-ml-dashboard/blob/8892b87d6697cb9d29c88f37a2c19d8071494584/report2.pdf)).

## نحوه اجرا
1. نوت‌بوک‌ها را در Google Colab باز کنید یا محلی اجرا کنید.
2. دیتاست اطلاعت بارنامه استان قم برای سال 1403 را از https://docs.google.com/spreadsheets/d/1kwCukX_VRALxFcDdIfnAxetQiV03LQ_W/edit?usp=drive_link&ouid=113637278991604905747&rtpof=true&sd=true باز کنید.
3.  دیتاست اطلاعات بارنامه استان قم برای ماه بهمن سال 1403 را از https://docs.google.com/spreadsheets/d/11P00K5w4Bf0rVSkWlwHUBQkWHT5lY1UW/edit?usp=drive_link&ouid=113637278991604905747&rtpof=true&sd=true باز کنید. این دیتاست برای بخش Word-Embedding در فایل Fast_text_embedding_transportation.ipynb شده است.
4. کتابخانه های مورد نیاز که باید نصب شوند :
   -  pandas
   -  numpy
   -  scikit-learn
   -  matplotlib
   -  seaborn
   -  plotly
   -  xgboost
   -  jdatetime
   -  fasttext huggingface_hub
   -  umap-learn --quiet
