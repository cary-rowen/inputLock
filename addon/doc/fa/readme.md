# قفل ورودی‌ها (Input Lock) #

* نویسنده: Jose Manuel Delicado
* NVDA compatibility: 2022.4 and beyond
* دانلود [نسخه‌ی پایدار][1]

## مقدمه

آیا توو خونتون بچه کوچولو دارین؟ آیا کوچولوتون دوست داره دستاشو بکوبه رو
صفحه‌کلید؟ آیا وقتی با لپتاپتون کار میکنید، دستتون تصادفی میخوره به صفحه‌ی
موس و بدون اینکه خواسته باشید موس جابجا میشه؟ دیگه تموم شد! این افزونه برای
خودِ خودِ شماست! میتونید با خیال راحت کامپیوترتونو روشن، بدون اینکه خطری
نرم‌افزاری تهدیدش کنه، تنها بذارین!

به محض اینکه افزونه‌ی Input Lock را نصب کنید، میتوانید صفحه‌کلید، صفحه‌ی
لمسی لپتاپ (در صورتی که داشته باشد)، موس و نمایشگر بریلتان را قفل کنید.

## نحوه استفاده

این افزونه، دو فرمان به NVDA اضافه میکند. بطور پیشفرض، کلیدی برای این
فرمان‌ها اختصاص نیافته است؛ لذا باید از پنجره‌ی مدیریت فرمان‌های ورودی،
کلیدهایی به این فرمان‌ها اختصاص دهید. برای کسب اطلاعات بیشتر، راهنمای کاربر
را بخوانید.

وقتی کلیدی را که به فرمان قفل ورودی‌ها اختصاص دادید بزنید، NVDA خواهد گفت:
Input locked. دستگاه‌های ورودی قفل میشوند تا زمانی که دوباره آن کلید را
بزنید. این بار NVDA خواهد گفت: Input unlocked، و همه چیز بطور معمول کار
خواهد کرد.

چنانچه شما کلیدی را که به فرمان قفل موس اختصاص داده بودید بزنید، موس قفل
خواهد شد. فرمان را دوباره اجرا کرده، تا قفل موس را باز کنید. وقتی که موس قفل
است، میتوانید از فرمان‌های NVDA برای حرکت دادن مکان‌نمای موس استفاده کنید و
با دکمه‌های راست و چپ موس کلیک کنید، ولی خود موس را نمیتوانید حرکت
دهید. کلیک‌های موس را هم میتوانید با استفاده از دسته‌ی Input Lock در پنجره‌ی
تنظیمات NVDA (در NVDA 2018.2 به بعد) یا پنجره‌ی تنظیمات افزونه در منوی
تنظیمات (در نسخه‌های قدیمیتر NVDA) غیر فعال کنید. افزون بر این، میتوانید با
استفاده از این تنظیمات، تعیین کنید که موس از ابتدای کار NVDA قفل شود یا نه.

توجه: هنگامی که کلیک‌های موس قفل باشد، نمیتوانید از فرمان‌های NVDA برای کار
با موس استفاده کنید.

## Limitations and known problems

Input Lock has the following known problems:

* The shortcuts control+alt+del and windows+l can be used even when the
  keyboard is locked.
* On some laptops, the touchpad still accepts user input after mouse is
  blocked.

## فهرست تغییرات

### Version 1.11

* Updated compatibility flags for recent NVDA versions.
* Updated translations.
* Now, minimum supported version is 2022.4.

### Version 1.10

* Updated compatibility flags for recent NVDA versions.
* Updated translations.
* Updated documentation.
* Now, minimum supported version is 2021.3.
* The input will remain blocked after waking up from standby mode. Thanks to
  Javi Dominguez.

### Version 1.9

* Updated compatibility flags for recent NVDA versions.
* Updated translations.
* Updated documentation.

### Version 1.8

* Updated compatibility flags for recent NVDA versions.
* Updated translations.

### Version 1.7

* Updated compatibility flags for recent NVDA versions.
* Updated translations.

### Version 1.6

* Now, settings are removed only when the add-on is
  uninstalled. Configuration is nolonger reset when upgrading.
* New and updated translations.

### Version 1.5

* Added compatibility with recent NVDA releases.
* New translations.

### نسخه‌ی ۱.۴

* بطور پیش‌فرض، کلیدی به فرمان‌های افزونه اختصاص داده نمیشود.

### نسخه‌ی ۱.۳

* برای این افزونه، یک پنل تنظیمات به تنظیمات NVDA افزوده شد. برای نسخه‌های
  قدیمی NVDA، یک مورد منو و یک پنجره‌ی محاوره‌ای هم افزوده شده است.
* تنظیمی برای قفل کردن موس هنگام آغاز کار NVDA اضافه شد.
* تنظیمی هم برای مسدود کردن کلیک‌های موس هنگامی که موس قفل میشود افزوده شد.
* مشکلات کوچکی برطرف شد. اندکی بهینه‌سازی در کد افزونه و رشته های کمتر
  تکراری برای مترجم‌ها.

### نسخه‌ی ۱.۲

* حالا موس را هم میتوانید قفل کنید.
* فرمان جدید برای قفل کردن و باز کردن فقط موس

### نسخه‌ی ۱.۱

* اگر افزونه‌ی دیگری از پیش یک کارکرد Capture به مدیریت ورودی‌ها اضافه کرده
  باشد، هنگامی که قفل ورودی‌ها را باز میکنید، دوباره به وضعیت قبلی خود
  برمیگردد.

### نسخه‌ی ۱.۰

* انتشار نخست

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=inputLock
