# TeleTranslate-AI
A smart Telegram Dictionary bot powered by Groq AI (Llama 3) with Persian voice-to-text translation and SQLite logging.





💻 راهنمای نصب در سیستم‌عامل‌های مختلف
1️⃣ پیش‌نیاز مشترک (FFmpeg)
این پروژه برای تبدیل وویس‌ها به کتابخانه FFmpeg نیاز دارد. نصب آن در هر سیستم‌عامل متفاوت است:

🍎 در مک (macOS):
ابتدا Homebrew را نصب کنید و سپس:


    brew install ffmpeg
🪟 در ویندوز (Windows):
۱. فایل FFmpeg را از سایت رسمی دانلود کنید.

۲. آن را در یک درایو (مثلاً C:\ffmpeg) استخراج کنید.

۳. آدرس پوشه bin آن را به System Environment Variables (Path) اضافه کنید.

🐧 در لینوکس (Linux/Ubuntu):

    sudo apt update
    sudo apt install ffmpeg
2️⃣ نصب پایتون و کتابخانه‌ها
توصیه می‌شود از پایتون ۳.۱۲ استفاده کنید.

در تمام سیستم‌عامل‌ها:

۱. ابتدا کتابخانه‌های اصلی را نصب کنید:

pip install aiogram aiohttp pydub SpeechRecognition
۲. اگر در لینوکس یا مک با خطای externally-managed-environment مواجه شدید، از دستور زیر استفاده کنید:


pip install aiogram aiohttp pydub SpeechRecognition --break-system-packages
3️⃣ نحوه اجرا
۱. مخزن را کلون کنید:


git clone https://github.com/mduvdi89-dot/TeleTranslate-AI_2
cd your-repo-name
۲. توکن‌های خود را در فایل کد قرار داده و آن را اجرا کنید:

ویندوز:

    python Dictionary_bot.py
مک و لینوکس:

    python3 Dictionary_bot.py
