# botbat (نبرد روبات‌ها)

این پروژه با هدف طراحی رابط کاربری تحت وب برای بازی نبرد روبات‌ها است. این کار از طریق اتصال به API این بازی صورت می‌پذیرد و امکاناتی را مانند موارد زیر ایجاد می‌کند
- قابلیت عضویت در بازی با انتخاب زمین و نام کاربری و رنگ تیم (آبی یا قرمز)
- دریافت وضعیت لحظه‌ای بازیکن و زمین از API و نمایش
  - وضعیت استقرار بازیکن
  - نقشه زمین و موقعیت هم تیمی‌ها
  - میزان منابع بازیکن شامل جان و گلوله
  - پیام‌های ارسالی به بازیکن
- کنترل بازی از طریق رابط کاربری با استفاده از تعامل با API جهت تقاضا برای اجرای عملیات از میان عملیات‌های مجاز

رابط کاربری ایجاد شده بایستی با اتصال به API در آدرس [https://botbat.ir/api.php](https://botbat.ir/api.php) ماموریت‌های بالا را انجام دهد

در حال حاضر جهت دریافت اطلاعات پایه برای اتصال به API بایستی از صفحه نخست وب سایت در بازی عضو شوید و اطلاعات لازم برای تعامل با API را بردارید تا نسخه رابط کاربری شما بتواند به تعامل ادامه دهد اما به زودی می‌توان از طریق API عملیات ایجاد زمین و بازیکن را پیش برد

برای آشنائی با چگونگی عملکرد API جهت استفاده می‌توانید متناسب با نسخه انتخابی خود به اسناد موجود در پوشه `docs/api` مراجعه نمائید

پیروز و سربلند باشید

رابط کاربری اولیه ایجاد شده بر مبنای API نسخه 0.0.0

![Screenshot](https://botbat.ir/files/screenshot001.png)

نمایش کلی زمین و بازیکنان ایجاد شده بر مبنای API نسخه 0.0.0

![Screenshot](https://botbat.ir/files/screenshot002.png)

