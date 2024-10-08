<p align="center">
<picture>
<img width="160" height="160"  alt="Mana SSH" src="https://raw.githubusercontent.com/amna33mcc/mana1.1/master/logo.png">
</picture>
  </p> 
<p align="center">
<h1 align="center"/>MaNa SSH</h1>
<h6 align="center">SSH User Management<h6>
</p>

<p align="center">
<img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/amna33mcc/mana1.1">
</p>

## معرفی <br>

مانا پنل یک نرم افزار تحت وب جهت مدیریت اکانت SSH می باشد.

## امکانات <br>

✔️ ایجاد کاربر بدون محدودیت <br>
✔️ اعمال محدودیت در حجم مصرفی و تاریخ انقضا<br>
✔️ قابلیت محاسبه تاریخ انقضا در اولین اتصال<br>
✔️ اعمال محدودیت در چند کاربره بودن اکانت<br>
✔️ مشاهده کاربران آنلاین<br>
✔️ امکان بکاپ گیری از کاربران و ریستور بکاپ<br>
✔️ تنظیم پورت ورود برای پنل<br>
✔️ تنظیم پورت های UDP , SSH در پنل ادمین<br>
✔️ تنظیم آدرس فیک<br>
✔️ محدودیت IP(جلوگیری از ورود کاربران به برخی سایت ها)<br>
✔️ اتصال API<br>
✔️ اطلاعات سیستم(RAM, CPU, HDD)<br>

#

**سیستم عامل مورد نیاز**

<p align="right">
Ubuntu 18+<br>
پیشنهادی :Ubuntu 20
</p>


# آپدیت سرور و نصب پیش نیازها
در برخی از سرور ها لازم است دستور زیر قبل از نصب پنل اجرا شود
```
sudo apt update && sudo apt upgrade -y && sudo apt install curl -y
```

# نصب
برای نصب دستور زیر را وارد کنید<br>

```
bash <(curl -Ls https://raw.githubusercontent.com/amna33mcc/mana1.1/master/install.sh --ipv4)
```

# آپدیت پنل ادمین

نیازی به نصب مجدد نیست . با این روش فقط پنل ادمین آپدیت می شود . در این روش اطلاعات دیتابیس تغییر نمی کند

```
bash <(curl -Ls https://raw.githubusercontent.com/amna33mcc/mana1.1/master/update-panel.sh --ipv4)
```

# نصب وردپرس

جهت نصب وردپرس دستور زیر را اجرا کنید. بعد از نصب حتما اطلاعات را یادداشت کرده و در مراحل بعدی از آن استفاده کنید

```
bash <(curl -Ls https://raw.githubusercontent.com/amna33mcc/mana1.1/master/install-wp.sh --ipv4)
```

# بلاک کردن آی پی

جهت بلاک کردن آی پی از دستور زیر استفاده کنید

```
bash <(curl -Ls https://raw.githubusercontent.com/amna33mcc/mana1.1/master/block-ir-ip.sh --ipv4)
```
# فعال کردن ssl

جهت فعال کردن sll از دستور زیر استفاده کنید

```
bash <(curl -Ls https://raw.githubusercontent.com/xpanel-cp/XPanel-SSH-User-Management/master/ssl.sh --ipv4)
```

# تانل ریورس tls

جهت فعال کردن تانل از دستور زیر استفاده کنید

```
sudo apt install curl -y && bash <(curl -s https://raw.githubusercontent.com/Azumi67/Reverse_tls/main/go.sh)
```


# آپتیمایزر 

جهت فعال کردن آپتیمایزر از دستور زیر استفاده کنید

```
apt install curl -y && bash <(curl -s https://raw.githubusercontent.com/opiran-club/VPS-Optimizer/main/optimizer.sh --ipv4)
```

# پروکسی تلگرام 

جهت راه اندازی پروکسی از دستور زیر استفاده کنید

```
curl -L -o mtp_install.sh https://git.io/fj5ru && bash mtp_install.sh
```



curl -O https://raw.githubusercontent.com/angristan/openvpn-install/master/openvpn-install.sh


chmod +x openvpn-install.sh


./openvpn-install.sh
