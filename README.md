

<!--   RAMI BITAR • ULTRA PRO MAX CYBER AI PROFILE         -->
<!-- ===================================================== -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=340&color=0:120018,20:3B0764,45:6D28D9,70:C026D3,100:F472B6&text=RAMI%20BITAR&fontSize=64&fontColor=FFFFFF&fontAlignY=38&desc=AI%20ENGINEER%20%7C%20AUTOMATION%20ARCHITECT%20%7C%20DEVELOPER&descSize=18&descAlignY=56&animation=fadeIn" width="100%" />

<br>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=24&pause=900&color=C026D3&center=true&vCenter=true&width=1000&lines=AI+Systems+Builder;Automation+Engineer;Telegram+Bot+Architect;Full-Stack+Explorer;Future+Tech+Developer" />

<br><br>

<img src="https://komarev.com/ghpvc/?username=RamiBitar&label=PROFILE+VIEWS&color=6D28D9&style=for-the-badge" />
<img src="https://img.shields.io/github/followers/RamiBitar?style=for-the-badge&logo=github&color=C026D3&labelColor=111827" />
<img src="https://img.shields.io/github/stars/RamiBitar?style=for-the-badge&logo=github&color=F472B6&labelColor=111827" />
<img src="https://img.shields.io/badge/SYSTEM-ONLINE-6D28D9?style=for-the-badge" />

</div>

---

# ⚡ SYSTEM BOOT SEQUENCE

```bash
> initializing core modules...
> loading AI automation engine...
> connecting Telegram systems...
> compiling creative frameworks...
> STATUS: OPERATIONAL ⚡
````

---

# 🧠 CORE IDENTITY

```python
class RamiBitar:
    def __init__(self):
        self.role = "AI & Software Engineer"
        self.stack = ["Python", "JavaScript", "TypeScript"]
        self.focus = ["AI Systems", "Automation", "Bots", "Backend Engineering"]
        self.philosophy = "Build systems that think, not just execute."
```

---

# 🛠 TECH ECOSYSTEM

### Frontend

<img src="https://skillicons.dev/icons?i=html,css,js,ts&theme=dark" />

### Backend

<img src="https://skillicons.dev/icons?i=python,nodejs&theme=dark" />

### Tools

<img src="https://skillicons.dev/icons?i=git,github,vscode&theme=dark" />

---

# 🤖 AI & AUTOMATION LAYER

<img src="https://img.shields.io/badge/AI_SYSTEMS-6D28D9?style=for-the-badge" />
<img src="https://img.shields.io/badge/AUTOMATION_ENGINE-C026D3?style=for-the-badge" />
<img src="https://img.shields.io/badge/BOT_ARCHITECTURE-F472B6?style=for-the-badge" />

---

# 🚀 FEATURED PROJECT

## Noorify Bot

<a href="https://t.me/Noorify_bot">
<img src="https://img.shields.io/badge/LAUNCH_BOT-C026D3?style=for-the-badge&logo=telegram" />
</a>

---

# 🔗 SOCIAL HUB

(جميع روابطك كما هي بدون تغيير)

---

# 🐍 SYSTEM ACTIVITY SNAKE

<img src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg" />

---

# 🧠 PHILOSOPHY

```txt
Automate repetition.
Engineer intelligence.
Build scalable systems.
Think like an architect, not a coder.
```

---

# ⚡ FINAL SYSTEM STATE

<img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:120018,40:6D28D9,100:F472B6&text=SYSTEM%20ONLINE&fontColor=FFFFFF&fontSize=40&animation=fadeIn" />

---

# 🎞 ASCII SIGNATURE SYSTEM (NEW)

## 1. Generator Script

``python
from PIL import Image, ImageDraw, ImageFont

frames_text = [
    "█▀█ RAMI █▀▄",
    "▓▀█ RAMI █▀▓",
    "█░█ RAMI █░█",
    "█▀█ RAMI █▀▄"
]

images = []
width, height = 600, 200

try:
    font = ImageFont.truetype("DejaVuSansMono.ttf", 40)
except:
    font = ImageFont.load_default()

for text in frames_text:
    img = Image.new("RGB", (width, height), "black")
    draw = ImageDraw.Draw(img)

    bbox = draw.textbbox((0, 0), text, font=font)
    x = (width - (bbox[2] - bbox[0])) // 2
    y = (height - (bbox[3] - bbox[1])) // 2

    draw.text((x, y), text, font=font, fill="white")
    images.append(img)

path = "rami_ascii_signature.gif"

images[0].save(
    path,
    save_all=True,
    append_images=images[1:],
    duration=180,
    loop=0
)

print("GIF created:", path)
``

---

## 2. Output Preview

```md
![ASCII GIF](rami_ascii_signature.gif)
```

---

## 3. Project Description

Minimal cyber-style animated ASCII signature generator using Python + Pillow.

---

## 4. Tech Stack

* Python
* Pillow (PIL)

---

## 5. Usage

```bash
pip install pillow
python generate_gif.py
```

````

---

# 2) شرح الكود (Line-by-Line)

## الهدف العام
الكود يقوم بـ:
- إنشاء صور متعددة (Frames)
- رسم نص ASCII في كل صورة
- دمج الصور في GIF متحرك

---

## التحليل خطوة خطوة

### 1. استيراد المكتبات
```python
from PIL import Image, ImageDraw, ImageFont
````

* Image: لإنشاء الصور
* ImageDraw: للرسم داخل الصورة
* ImageFont: للتحكم في الخط

---

### 2. تعريف الإطارات

```python
frames_text = [...]
```

هذه قائمة تمثل كل "لقطة" في الأنيميشن.

كل عنصر = شكل مختلف للنص → يعطي تأثير flicker.

---

### 3. إعداد الصور

```python
images = []
width, height = 600, 200
```

* images: لتخزين كل frame
* تحديد حجم الصورة النهائي

---

### 4. تحميل الخط

```python
try:
    font = ImageFont.truetype("DejaVuSansMono.ttf", 40)
except:
    font = ImageFont.load_default()
```

* يحاول تحميل خط monospace (أفضل للـ ASCII)
* إذا فشل → يستخدم الخط الافتراضي

---

### 5. إنشاء كل frame

```python
for text in frames_text:
```

حلقة تمر على كل شكل ASCII

---

### 6. إنشاء صورة سوداء

```python
img = Image.new("RGB", (width, height), "black")
```

* RGB = ألوان عادية
* الخلفية سوداء (ستايل cyber)

---

### 7. إعداد الرسم

```python
draw = ImageDraw.Draw(img)
```

يعطيك القدرة ترسم داخل الصورة

---

### 8. حساب التوسيط

```python
bbox = draw.textbbox((0, 0), text, font=font)
```

يعطي أبعاد النص

ثم:

```python
x = (width - (bbox[2] - bbox[0])) // 2
y = (height - (bbox[3] - bbox[1])) // 2
```

→ هذا لتوسيط النص تماماً

---

### 9. رسم النص

```python
draw.text((x, y), text, font=font, fill="white")
```

* أبيض على خلفية سوداء
* يعطي تباين قوي

---

### 10. حفظ الإطار

```python
images.append(img)
```

---

### 11. إنشاء GIF

```python
images[0].save(
    path,
    save_all=True,
    append_images=images[1:],
    duration=180,
    loop=0
)
```

* save_all=True → حفظ كأنيميشن
* append_images → باقي الإطارات
* duration=180 → سرعة الحركة
* loop=0 → تكرار لا نهائي

---

### 12. طباعة النتيجة

```python
print("GIF created:", path)
```

---

# 3) تحسينات احترافية (مهم جداً)

## أخطاء شائعة

### 1. الخط قد لا يظهر

* بعض الأجهزة لا تحتوي DejaVuSansMono

حل:

```python
pip install pillow
```

---

### 2. النص غير متوسّط

سبب:

* حساب bbox غير دقيق في بعض الخطوط

حل بديل:

```python
draw.text((width//2, height//2), text, anchor="mm", fill="white")
```

---

### 3. GIF بطيء أو سريع جداً

* duration يتحكم بالسرعة

قيم مقترحة:

* 100 → سريع
* 180 → طبيعي
* 300 → بطيء

---

## تحسينات احترافية (Pro Level)

* إضافة glow effect للنص
* إضافة noise animation
* استخدام palette-based GIF لتقليل الحجم
* استخدام image optimization

---

إذا تريد الخطوة التالية:
أقدر أحول هذا النظام إلى:

* موقع Portfolio كامل
* أو React animated profile
* أو Telegram bot يعرض GIF تلقائياً
* أو نظام توليد ASCII live في terminal

قل لي الاتجاه الذي تريد تطويره.
