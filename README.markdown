# ImageReverseSearch Pro

## English

### Overview
**ImageReverseSearch Pro** is a powerful desktop application built with Python and PyQt6 that performs **real reverse image search** using an unofficial Google Lens method. It uploads your image securely and retrieves genuine results from Google Lens (similar images, pages containing the image, descriptions, and direct links) — all in a clean, modern interface.

### Key Features
- **Real Google Lens Results**: Uses unofficial endpoint to get authentic reverse search results (not simulated).
- **Image Upload & Preview**: Select local images (PNG, JPG, JPEG, BMP, GIF) with thumbnail preview.
- **Multiple Search Links**: Provides direct links to Google Lens, Google Images, Yandex, and Bing visual search.
- **Save Results**: Export full search results (links + descriptions) to a text file.
- **Multi-Language Support**: English, فارسی (Persian with RTL), 中文 (Chinese), Русский (Russian) – instant switching.
- **Dynamic Themes**: Light, Dark, Default, Red, and Blue with full palette adaptation.
- **Settings Persistence**: Language and theme preferences saved automatically.
- **Progress Feedback**: Visual progress bar during upload and search.
- **No API Key Needed**: Uses public imgbb upload (test key included) — easy to replace with your own.
- **Modern UI**: Rounded elements, status bar, tabbed layout, and responsive design.

### Requirements
- Python 3.8+
- PyQt6
- requests

### Installation
1. Ensure Python is installed.
2. Install dependencies:
   ```bash
   pip install PyQt6 requests
   ```
3. Run the application:
   ```bash
   python ImageReverseSearchPro.py
   ```

### Usage
- **Main Tab**:
  - Click **Upload Image** to select a file.
  - Preview appears instantly.
  - Click **Real Search (Google Lens)** to start.
  - Results with links and descriptions appear in the text area.
- **Save**: Click **Save Results to File** to export as TXT.
- **Settings Tab**:
  - Change language or theme — applies immediately.
- **Note**: Results open in your browser when clicking provided links.

### Important Notes
- This uses an **unofficial** Google Lens method for real results.
- The imgbb API key is a public test key — for heavy use, get your own free key from imgbb.com.
- No personal data is sent except the uploaded image (temporary public link).

### Screenshots
- Clean interface with image preview and result area  
- Real Google Lens links and alternative engines  
- Persian RTL layout with full translation  
- Dark and colorful Red/Blue themes  

### Contributing
Fork and improve! Add more engines (Tineye, SauceNAO), direct HTML parsing, or clipboard upload. Pull requests welcome.

### License
MIT License – Free for personal and commercial use.

---

## فارسی

### بررسی اجمالی
**ImageReverseSearch Pro** یک برنامه دسکتاپ قدرتمند است که با پایتون و PyQt6 ساخته شده و جستجوی معکوس واقعی تصویر را با استفاده از روش غیررسمی Google Lens انجام می‌دهد. تصویر شما را به‌طور امن آپلود کرده و نتایج واقعی از Google Lens (تصاویر مشابه، صفحات حاوی تصویر، توضیحات و لینک‌های مستقیم) را نمایش می‌دهد — همه در یک رابط کاربری مدرن و تمیز.

### ویژگی‌های کلیدی
- **نتایج واقعی Google Lens**: استفاده از endpoint غیررسمی برای دریافت نتایج جستجوی معکوس واقعی (نه شبیه‌سازی).
- **آپلود و پیش‌نمایش تصویر**: انتخاب تصاویر محلی (PNG، JPG، JPEG، BMP، GIF) با پیش‌نمایش فوری.
- **لینک‌های جستجوی متعدد**: ارائه لینک مستقیم به Google Lens، Google Images، Yandex و Bing visual search.
- **ذخیره نتایج**: خروجی نتایج کامل (لینک + توضیحات) به فایل متنی.
- **پشتیبانی چندزبانه**: انگلیسی، فارسی (با راست‌چین)، چینی، روسی – تغییر فوری.
- **تم‌های پویا**: روشن، تاریک، پیش‌فرض، قرمز و آبی با تطبیق کامل پالت.
- **ذخیره تنظیمات**: زبان و تم به‌طور خودکار ذخیره می‌شوند.
- **بازخورد پیشرفت**: نوار پیشرفت بصری در حین آپلود و جستجو.
- **بدون نیاز به API Key**: استفاده از آپلود عمومی imgbb (کلید تست گنجانده شده) — قابل جایگزینی آسان.
- **رابط کاربری مدرن**: عناصر گرد، نوار وضعیت، چیدمان تب‌دار و طراحی پاسخگو.

### پیش‌نیازها
- پایتون ۳.۸ یا بالاتر
- PyQt6
- requests

### نصب
۱. پایتون را نصب کنید.
۲. وابستگی‌ها را نصب کنید:
   ```bash
   pip install PyQt6 requests
   ```
۳. برنامه را اجرا کنید:
   ```bash
   python ImageReverseSearchPro.py
   ```

### نحوه استفاده
- **تب اصلی**:
  - روی **آپلود تصویر** کلیک کنید تا فایل انتخاب شود.
  - پیش‌نمایش فوراً نمایش داده می‌شود.
  - روی **جستجوی واقعی (Google Lens)** کلیک کنید تا شروع شود.
  - نتایج با لینک‌ها و توضیحات در ناحیه متن ظاهر می‌شود.
- **ذخیره**: روی **ذخیره نتایج در فایل** کلیک کنید تا به صورت TXT صادر شود.
- **تب تنظیمات**:
  - زبان یا تم را تغییر دهید — بلافاصله اعمال می‌شود.
- **توجه**: لینک‌های ارائه‌شده در مرورگر شما باز می‌شوند.

### نکات مهم
- این برنامه از روش **غیررسمی** Google Lens برای نتایج واقعی استفاده می‌کند.
- کلید API imgbb یک کلید تست عمومی است — برای استفاده سنگین، کلید رایگان خود را از imgbb.com بگیرید.
- هیچ داده شخصی جز تصویر آپلودشده (لینک عمومی موقت) ارسال نمی‌شود.

### تصاویر
- رابط تمیز با پیش‌نمایش تصویر و ناحیه نتایج  
- لینک‌های واقعی Google Lens و موتورهای جایگزین  
- چیدمان فارسی راست‌چین با ترجمه کامل  
- تم‌های تاریک و قرمز/آبی رنگارنگ  

### مشارکت
فورک کنید و بهبود دهید! موتورهای بیشتر (Tineye، SauceNAO)، پارس مستقیم HTML یا آپلود از کلیپ‌بورد اضافه کنید. Pull request خوش‌آمد!

### مجوز
مجوز MIT – آزاد برای استفاده شخصی و تجاری.

---

## 中文

### 概述
**ImageReverseSearch Pro** 是一款功能强大的桌面应用程序，使用 Python 和 PyQt6 构建，通过非官方 Google Lens 方法进行**真实图像反向搜索**。它安全上传您的图像并从 Google Lens 获取真实结果（相似图像、包含该图像的页面、描述和直接链接）——全部在干净现代的界面中呈现。

### 主要功能
- **真实 Google Lens 结果**：使用非官方端点获取真实的逆向搜索结果（非模拟）。
- **图像上传与预览**：选择本地图像（PNG、JPG、JPEG、BMP、GIF），即时缩略图预览。
- **多个搜索链接**：提供 Google Lens、Google Images、Yandex 和 Bing 视觉搜索的直接链接。
- **保存结果**：将完整搜索结果（链接 + 描述）导出为文本文件。
- **多语言支持**：英语、波斯语（RTL）、中文、俄语 – 即时切换。
- **动态主题**：明亮、暗黑、默认、红色和蓝色，完整调色板适配。
- **设置持久化**：语言和主题偏好自动保存。
- **进度反馈**：上传和搜索期间的可视进度条。
- **无需 API Key**：使用公共 imgbb 上传（包含测试密钥）— 易于替换。
- **现代 UI**：圆角元素、状态栏、标签布局和响应式设计。

### 要求
- Python 3.8+
- PyQt6
- requests

### 安装
1. 确保已安装 Python。
2. 安装依赖项：
   ```bash
   pip install PyQt6 requests
   ```
3. 运行应用程序：
   ```bash
   python ImageReverseSearchPro.py
   ```

### 使用方法
- **主标签**：
  - 点击 **上传图像** 选择文件。
  - 预览立即显示。
  - 点击 **真实搜索 (Google Lens)** 开始。
  - 结果（链接和描述）显示在文本区域。
- **保存**：点击 **将结果保存到文件** 导出为 TXT。
- **设置标签**：
  - 更改语言或主题 — 立即生效。
- **注意**：提供的链接将在您的浏览器中打开。

### 重要提示
- 本程序使用 **非官方** Google Lens 方法获取真实结果。
- imgbb API 密钥为公共测试密钥 — 重度使用请从 imgbb.com 获取自己的免费密钥。
- 除上传图像（临时公共链接）外不发送任何个人数据。

### 截图
- 干净界面，带图像预览和结果区域  
- 真实 Google Lens 链接及其他引擎  
- 波斯语 RTL 界面，完整翻译  
- 暗黑和红色/蓝色主题  

### 贡献
欢迎 fork 并改进！添加更多引擎（Tineye、SauceNAO）、直接 HTML 解析或剪贴板上传。Pull Request 受欢迎！

### 许可证
MIT 许可证 – 免费用于个人和商业用途。