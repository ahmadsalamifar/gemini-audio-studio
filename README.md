Gemini Audio Studio 🎙️

English | فارسی

<a name="english"></a>

🇺🇸 English

Gemini Audio Studio is a powerful, client-side web application designed to leverage Google's latest Gemini 2.5 models for advanced audio generation (TTS) and analysis (STT).

It acts as a "Voice Director" interface, allowing you to script multi-character dialogues with precise control over emotion, tone, and pacing, or upload audio files for deep multimodal analysis.

✨ Key Features

🗣️ Voice Director (Text-to-Speech)

Multi-Speaker Scripting: Create complex dialogues with multiple characters.

Gemini 2.5 Powered: Utilizes gemini-2.5-flash-preview-tts and pro models for human-like speech.

Director Controls:

30+ Voices: Choose from a wide range of voices (Zephyr, Puck, Kore, etc.) with distinct personalities.

Tone Control: Set emotions like Cheerful, Sad, Serious, Whispering, Angry, etc.

Pace Control: Adjust speaking speed (Fast, Slow, Normal).

Card-Based Editor: Each line of dialogue is a card, making it easy to manage long scripts.

Export Project: Download your entire session as a ZIP file containing individual .wav files for each line and a script.json file.

🎧 Audio Analysis (Speech-to-Text & Multimodal)

Advanced Analysis: Uses gemini-2.0-flash-exp (and other models) to understand audio.

Flexible Inputs: Support for MP3, WAV, AAC, and MP4 files.

Custom Prompts: Ask the AI to transcribe, translate, summarize, detect emotions, or extract specific data from the audio.

Markdown Support: View formatted results directly in the app.

⚙️ General

Client-Side Only: No server required. Runs directly in your browser.

Bilingual UI: Fully supported English and Persian (Farsi) interfaces (RTL support).

Secure: Your API Key is stored locally in your browser (localStorage) and never sent to a third-party server.

🚀 Getting Started

Prerequisites

A modern web browser (Chrome, Edge, Firefox).

An active internet connection.

A Google Gemini API Key. You can get one for free at Google AI Studio.

Installation

Since this is a static web application, no installation is required!

Download the gemini-audio-studio.html file.

Double-click the file to open it in your browser.

📖 Usage Guide

1. Setup

Open the app.

Click on API Settings.

Paste your Gemini API Key.

Click Save & Verify Connection.

2. Generating Audio (TTS)

Go to the Voice Director (TTS) tab.

Add Speakers: Click "Add New Speaker" in the sidebar to define your cast. Assign a voice (e.g., Puck, Kore) to each character.

Write Script: Enter your dialogue in the main editor. Format: Name: Text.

Example:

Narrator: Once upon a time in a digital world.
Sarah: Wait, is this real?


Refresh Cards: Click "Refresh Cards" to generate control cards for each line.

Direct: Use the dropdowns on each card to change the Tone or Speed.

Generate: Click the Play button (▶) on a card to generate and listen to the audio.

Export: Click "Download Files (ZIP)" to save everything.

3. Analyzing Audio (STT)

Go to the Audio Analysis (STT) tab.

Upload: Drag and drop an audio file into the box.

Prompt: Enter instructions for the AI (e.g., "Transcribe this and list the speakers").

Analyze: Click "Start Analysis" and wait for the result.

<a name="persian"></a>

🇮🇷 فارسی

استودیوی صوتی جمینای (Gemini Audio Studio) یک برنامه تحت وب قدرتمند و سمت کاربر (Client-side) است که برای استفاده از جدیدترین مدل‌های Google Gemini 2.5 جهت تولید پیشرفته صدا (TTS) و تحلیل فایل‌های صوتی (STT) طراحی شده است.

این برنامه مانند یک "دستیار کارگردان" عمل می‌کند و به شما اجازه می‌دهد سناریوهای چند نفره را با کنترل دقیق روی احساسات، لحن و سرعت بنویسید، یا فایل‌های صوتی را برای تحلیل عمیق آپلود کنید.

✨ ویژگی‌های کلیدی

🗣️ کارگردان صوتی (تبدیل متن به گفتار)

سناریو نویسی چند گوینده: دیالوگ‌های پیچیده با چندین کاراکتر مختلف بسازید.

قدرت گرفته از Gemini 2.5: استفاده از مدل‌های gemini-2.5-flash-preview-tts برای تولید صدای بسیار طبیعی.

ابزارهای کارگردانی:

بیش از ۳۰ صدا: انتخاب از بین طیف وسیعی از صداها (مانند Puck, Kore, Zephyr) با شخصیت‌های متفاوت.

کنترل لحن (Tone): تنظیم احساساتی مانند شاد، غمگین، جدی، پچ‌پچ، عصبانی و هیجان‌زده.

کنترل سرعت (Pace): تنظیم سرعت بیان (سریع، آهسته، عادی).

ویرایشگر کارتی: هر خط دیالوگ به صورت یک کارت نمایش داده می‌شود که مدیریت متن‌های طولانی را آسان می‌کند.

خروجی پروژه: دانلود کل جلسه به صورت یک فایل ZIP شامل فایل‌های صوتی جداگانه .wav و فایل script.json.

🎧 تحلیل صدا (تبدیل گفتار به متن و تحلیل چندوجهی)

تحلیل پیشرفته: استفاده از مدل gemini-2.0-flash-exp (و سایر مدل‌ها) برای درک محتوای صوتی.

ورودی‌های منعطف: پشتیبانی از فایل‌های MP3, WAV, AAC و MP4.

دستورات سفارشی (Prompts): از هوش مصنوعی بخواهید متن را پیاده‌سازی، ترجمه یا خلاصه کند، احساسات را تشخیص دهد و یا اطلاعات خاصی را استخراج نماید.

پشتیبانی از Markdown: نمایش نتایج فرمت‌دهی شده مستقیماً در برنامه.

⚙️ عمومی

بدون نیاز به سرور: برنامه مستقیماً در مرورگر شما اجرا می‌شود (Client-Side).

رابط کاربری دوزبانه: پشتیبانی کامل از رابط کاربری انگلیسی و فارسی (راست‌چین RTL).

امنیت: کلید API شما به صورت محلی در مرورگر (localStorage) ذخیره می‌شود و هرگز به سرور دیگری ارسال نمی‌گردد.

🚀 راهنمای شروع

پیش‌نیازها

یک مرورگر وب مدرن (Chrome, Edge, Firefox).

اتصال فعال اینترنت.

یک کلید API گوگل جمینای. می‌توانید آن را به صورت رایگان از Google AI Studio دریافت کنید.

نصب

از آنجا که این یک برنامه وب استاتیک است، نیازی به نصب ندارد!

فایل gemini-audio-studio.html را دانلود کنید.

فایل را با دابل‌کلیک در مرورگر خود باز کنید.

📖 راهنمای استفاده

۱. تنظیمات اولیه

برنامه را باز کنید.

روی تنظیمات کلید API (API Settings) کلیک کنید.

کلید API خود را وارد کنید.

روی دکمه ذخیره و بررسی اتصال کلیک کنید.

۲. تولید صدا (TTS)

به تب کارگردانی صوتی (TTS) بروید.

افزودن گوینده: روی "افزودن گوینده جدید" در نوار کناری کلیک کنید تا بازیگران خود را تعریف کنید. برای هر نقش یک صدا (مثلاً Puck یا Kore) انتخاب کنید.

نوشتن سناریو: دیالوگ خود را در ویرایشگر اصلی بنویسید. فرمت باید به صورت نام: متن باشد.

مثال:

راوی: یکی بود یکی نبود.
سارا: واقعا این داستان واقعیت داره؟


بروزرسانی کارت‌ها: روی دکمه "بروزرسانی کارت‌ها" کلیک کنید تا پنل‌های کنترل برای هر خط ساخته شود.

کارگردانی: از منوهای کشویی روی هر کارت برای تغییر لحن (Tone) یا سرعت (Speed) استفاده کنید.

تولید: دکمه پخش (▶) روی هر کارت را بزنید تا صدا تولید و پخش شود.

خروجی: برای ذخیره همه فایل‌ها روی "دانلود فایل‌ها (ZIP)" کلیک کنید.

۳. تحلیل صدا (STT)

به تب تحلیل صدا (STT) بروید.

آپلود: فایل صوتی خود را بکشید و در کادر رها کنید.

دستور (Prompt): دستورالعمل خود را بنویسید (مثلاً: "متن این فایل را بنویس و گویندگان را مشخص کن").

تحلیل: روی "شروع تحلیل" کلیک کنید و منتظر نتیجه بمانید.

🛠️ Technologies Used | تکنولوژی‌های استفاده شده

HTML5 / JavaScript (ES6+)

Tailwind CSS (Styling)

JSZip (File export)

Marked.js (Markdown rendering)

FontAwesome (Icons)

📄 License

This project is open-source. Feel free to modify and distribute it.

Created by Ahmad Salami Far