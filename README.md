# remoteTestProject
This is the remote test project for khedmat az ma:
#رزرو کتاب

## شرح تسک
## مدیریت نسخه ها:
هر کتاب میتواند چندین نسخه با شرایط فیزیکی متفاوت داشته باشد
هر نسخه تاریخچه تعمیرات و وضعیت فیزیکی دارد
امکان جایگزینی یک نسخه با نسخه دیگر در صورت آسیب

## سیستم رزرو هوشمند :
رزرو براساس اولویتبندی کاربران
رزرو زنجیرهای )وقتی کتاب برگشت داده شد، به نفر بعدی در صف به صورت اتوماتیک اطالع داده شود(
محدودیت رزرو براساس سابقه کاربر )تاخیر، خسارت(

## قوانین پیچیده:
اعضای ویژه میتوانند نسخههای خاص را رزرو کنند
سیستم جریمه پویا )افزایش نرخ جریمه با تکرار تخلف(
امکان مبادله کتاب بین شعب مختلف


## سیستم امتیازدهی پیچیده براساس:

▪ تعداد روزهای تاخیر

▪ وضعیت کتاب هنگام برگشت

▪ تعداد رزروهای لغو شده

▪ سابقه درخواست تمدید

### نکات فنی:

▪ در نظر گرفتن SRP در زمان توسعه

▪ در نظر گرفتن inversion Dependency در زمان توسعه

▪ استفاده از Sourcing Event برای ثبت تمام تغییرات وضعیت کتاب

▪ پیادهسازی Locking Optimistic برای مدیریت رزروهای همزمان

▪ استفاده از Tags Cache برای مدیریت کش دادههای مرتبط

▪ پیادهسازی سیستم Notification با قابلیت Retry

▪ تعریف سیستم صف برای عملیاتهای زمانبر


### نکات:

▪ از زمان دریافت تسک دو روز ددالین در نظر بگیرید

▪ پروژه در گیت )گیت لب یا گیت هاب( قرارداده بشه و به این موضوع توجه بشه که برای هر تغییر نیازه یک کامیت در گیت وجود داشته باشه. به عبارت دیگر, کامیت یکباره و نهایی امتیازی دریافت نخواهد شد.

▪ در نظر داشته باشید که هدف از این تسک آشنایی با حل مسئله و دست خط کدی شما میباشد.

▪ انتظار UI در این پروژه نیست و فقط وب سرویس های مربوطه ایجاد شود.

▪ یک خروجی نهایی از وب سرویس ها در postman در گیت وجود دا شته باشه.
