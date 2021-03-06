---
title: Introduction
type: docs
---

## معرفی

راستش ایده این نوت-بلاگ از جایی شروع شد که من باید کتاب
*python tricks the book*
رو برای تقویت پایتونم می‌خوندم.

و دوست داشتم از این کتاب نوت برداری هم بکنم جوری که هر زمان که نیاز دارم
بیام سراغش. ابزار های
second mind
یا
second brain
هم هستند اما خب من نوشتن بلاگ رو ترجیح می‌دم چون به دیگران هم می‌تونه کمک کنه.

من از قبل یک
[بلاگ](https://bit-orbit.github.io/)
دارم. اما تفاوت این بلاگ در اینه که یک کتاب هست
و می‌تونم به راحتی همه فصل ها و کتاب های دیگه رو از هم مجزا کنم.

محتوایی که اینجاست ممکنه خلاصه‌ای از فصل های یک کتاب یا شاید ترجمه کاملی از
یک کتاب باشه.

## ساختار

داخل نوار سمت راست هر منویی که باز میشه یک کتاب رو
در بر می‌گیره.

توی هر کتاب فصل **صفر** وجود داره که توضیحات مربوط به کتاب توی این فصل نوشته می‌شه.
مثلا مشخص می‌شه کتاب ترجمه‌ست و یا خلاصه نویسی یک کتابه.
همچنین نحوه مشارکت، نویسندگان و ... داخل این فصل توضیح داده می‌شه.
با این روش به راحتی مشخص می‌شه اصل محتوای کتاب کجا قرار داره.


## مشارکت

اگر هر کتابی رو ترجمه و یا نوت برداری می‌کنید، ما را خیلی خوشحال می‌کنید اگر از
اینجا برای نوشتن استفاده کنید.

خیلی ساده‌ست کافیه با چند چیز آشنا باشید
*git*, *markdown*, *hugo*__!__

[ریپازیتوری]()
رو کلون کنید 
و یک دایرکتوری به نام کتاب مد نظرتون در مسیر 
`content/docs/`
بسازید.

سپس فایلی به نام
*index.md_*
درون اون دایرکتوری ایجاد کنید و این محتوا رو داخل فایل کپی کنید

<div dir='ltr'>

    ---
    title: 'نام کتاب'
    bookCollapseSection: true
    weight: 20
    ---
</div>

</br>

هر فصل یک فایل داخل دایرکتوری که ایجاد کرده‌اید است.
نام فصل ها با کلمه
**chapter**
شروع می‌شود، اما شما باید شماره فصل را در ادامه این کلمه بنویسید. مثلا
**chapter00**.
فراموش نکنید که فایل ها باید با پسوند
*md*
باشند.

درکل این ساختاری است که برای کتابی مثلا با سه فصل باید وجود داشته باشد:

<div dir='ltr'>

    ├── content
    │   └── docs
    │   |   └── the-book-dir-name
    │   |       ├── chapter00.md
    │   |       ├── chapter01.md
    |   |       ├── chapter02.md
    │   |       └── chapter03.md
</div>
