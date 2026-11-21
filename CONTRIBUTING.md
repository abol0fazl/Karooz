<div align="center" dir="rtl">

# مشارکت در کاروز (Karooz)

**راهنمای مشارکت در توسعه‌ی پروژه**

از اینکه می‌خواهی به کاروز کمک کنی، ممنونم! 🙌

</div>

<div dir="rtl">

## قبل از شروع

کد منبع کاروز برای مشاهده و بررسی عمومی است و مشارکت جامعه از طریق Issue و Pull Request انجام می‌شود. نسخه‌ی رسمی پروژه فقط توسط نگهدارنده‌ی آن (**abol0fazl**) منتشر می‌شود.

برای آشنایی با حقوق استفاده و شرایط انتشار، فایل [LICENSE](LICENSE) را بخوان.

## چطور پیشنهاد بدهم؟

1. **اگر فقط یک ایده یا باگ داری:** از تب [Issues](../../issues) یک مورد جدید باز کن و توضیح بده. برای گزارش باگ، مراحل بازتولید و نتیجه‌ی مورد انتظار را بنویس.
2. **اگر می‌خواهی کد را تغییر بدهی:**
   - مخزن را با دکمه‌ی **Fork** برای خودت کپی کن.
   - یک شاخه‌ی جدید بساز؛ مثلا `feat/search-history` یا `fix/monthly-report`.
   - تغییرت را انجام بده و در مرورگر آزمایش کن.
   - از مخزن Fork‌شده‌ی خودت یک **Pull Request** به شاخه‌ی `main` مخزن اصلی باز کن.
   - در توضیح PR بنویس چه چیزی را تغییر داده‌ای، چرا این تغییر لازم است و چطور آن را آزمایش کرده‌ای.

ارسال Pull Request به معنی پذیرش خودکار تغییرات نیست. نگهدارنده‌ی پروژه آن را بررسی می‌کند و درباره‌ی ادغام یا رد آن تصمیم می‌گیرد.

## قواعد کدنویسی

- هر Pull Request فقط یک موضوع مشخص داشته باشد؛ یک قابلیت یا یک رفع اشکال.
- اپلیکیشن با JavaScript خالص نوشته شده است؛ بدون هماهنگی، فریم‌ورک یا وابستگی جدید اضافه نکن.
- طراحی مینیمال، تیره و راست‌چین (`dir="rtl"`) را حفظ کن.
- تاریخ شمسی باید با `Intl.DateTimeFormat('fa-IR-u-ca-persian-nu-latn', …)` محاسبه شود، نه با الگوریتم دستی.
- سازگاری داده‌های ذخیره‌شده در `localStorage` را حفظ کن: کلیدهای قبلی را تغییر نده، فیلدهای قدیمی را حذف نکن و برای فیلدهای جدید مقدار پیش‌فرض در نظر بگیر تا اطلاعات کاربران فعلی از بین نرود.
- لوگوی «کاروز» و کارت تاریخ بالای صفحه رنگ ثابت دارند و نباید تحت‌تأثیر شخصی‌سازی تم قرار بگیرند.
- شماره‌ی نسخه (`APP_VERSION`) و تگ‌های انتشار را تغییر نده؛ نگهدارنده هنگام انتشار نسخه‌ی رسمی آن‌ها را تنظیم می‌کند.

## شرایط حقوقی مشارکت

با ارسال Pull Request تأیید می‌کنی که:

- کد یا محتوای ارسالی را خودت نوشته‌ای یا مجوز قانونی لازم برای ارسال آن را داری.
- مالکیت مشارکت اصلی خود را حفظ می‌کنی، مگر اینکه توافق کتبی دیگری وجود داشته باشد.
- به نگهدارنده‌ی کاروز اجازه می‌دهی مشارکتت را بررسی، اصلاح و در نسخه‌های رسمی پروژه ادغام و منتشر کند.
- شرایط بخش مشارکت در فایل [LICENSE](LICENSE) را می‌پذیری.

ارسال یا پذیرفته‌شدن Pull Request به معنی دریافت اجازه برای انتشار مستقل نسخه‌های تغییر‌یافته‌ی کاروز نیست. برای شرایط کامل، فایل [LICENSE](LICENSE) را مطالعه کن.

</div>

---

<div align="center">

# English

**Guidelines for contributing to the project**

Thank you for your interest in helping improve Karooz! 🙌

</div>

## Before You Start

Karooz source code is publicly available for viewing and inspection. Community contributions are handled through GitHub Issues and Pull Requests. Official releases are published only by the project maintainer (**abol0fazl**).

Read the [LICENSE](LICENSE) file for the terms governing use and redistribution.

## How to Contribute

1. **If you have an idea or found a bug:** Open an item in [Issues](../../issues) and describe it. For bug reports, include reproduction steps and the expected result.
2. **If you want to change the code:**
   - Fork the repository using the **Fork** button.
   - Create a new branch, such as `feat/search-history` or `fix/monthly-report`.
   - Make your changes and test them in a browser.
   - Open a **Pull Request** from your fork to the `main` branch of the original repository.
   - Explain what you changed, why the change is needed, and how you tested it.

Submitting a Pull Request does not guarantee acceptance. The project maintainer will review it and decide whether to merge or reject it.

## Coding Guidelines

- Each Pull Request should address one specific topic: one feature or one bug fix.
- The application uses vanilla JavaScript. Do not add a framework or new dependency without prior coordination.
- Preserve the minimal, dark, right-to-left (`dir="rtl"`) design.
- Solar Hijri dates must be calculated with `Intl.DateTimeFormat('fa-IR-u-ca-persian-nu-latn', …)`, not a hand-written algorithm.
- Preserve backward compatibility for data stored in `localStorage`: do not rename existing keys or remove existing fields. Provide default values for new fields so current users do not lose their data.
- The Karooz logo and the date card at the top of the page use fixed colors and must not be affected by theme customization.
- Do not change the version number (`APP_VERSION`) or release tags. The maintainer manages them when publishing an official release.

## Contribution Terms

By submitting a Pull Request, you confirm that:

- You authored the submitted code or material, or have the legal right to submit it.
- You retain ownership of your original contribution unless otherwise agreed in writing.
- You grant the Karooz maintainer permission to review, modify, incorporate, and publish your contribution in official project releases.
- You agree to the contribution terms in the [LICENSE](LICENSE) file.

Submitting or having a Pull Request accepted does not grant permission to independently distribute modified versions of Karooz. Read the [LICENSE](LICENSE) file for the complete terms.
