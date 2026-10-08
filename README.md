# 📘 Smart Grid Course Repository
# مخزن درس شبکه‌های هوشمند انرژی الکتریکی

A graduate-level course (3 credits, theoretical) designed with a dual focus on **practical implementation** and **research development** in the field of smart grids.

درس ۳ واحدی نظری «شبکه‌های هوشمند انرژی الکتریکی» در مقطع کارشناسی ارشد مهندسی برق (قدرت / سیستم‌های انرژی)، با تمرکز ویژه بر دو هدف اصلی: (۱) کاربرد عملی و (۲) تولید ایده و موضوع پژوهشی.

---

## 📋 Course Overview | مشخصات کلی درس

| Item | Details |
|------|---------|
| **Course Title** | Intelligent Electric Energy Networks (شبکه‌های هوشمند انرژی الکتریکی) |
| **Level** | M.Sc. in Electrical Engineering (Power / Energy Systems) |
| **Credits** | 3 Theoretical Units (۳ واحد نظری) |
| **Prerequisites** | None (Basic familiarity with power system analysis and Python/MATLAB recommended) |
| **Duration** | 16 Weeks (۱۶ هفته) |
| **Language** | Persian (فارسی) with English technical terms |

### 🎯 Main Objectives | اهداف کلان

1. **Practical Goal:** Ability to implement and simulate smart grid concepts using modern tools.  
   توانایی پیاده‌سازی و شبیه‌سازی مفاهیم شبکه هوشمند با ابزارهای روز.
2. **Research Goal:** Ability to extract research gaps and write proposals/review or research papers.  
   توانایی استخراج شکاف تحقیقاتی (Research Gap) و نگارش پروپوزال/مقاله مروری یا پژوهشی.

### 📐 Course Structure | ساختار درس

هر مبحث نظری، بلافاصله با یک بخش عملی (شبیه‌سازی/کدنویسی) و یک بخش پژوهشی (شناسایی شکاف تحقیقاتی) همراه است.

---

## 🗓️ Weekly Schedule | ساختار هفتگی دوره (۱۶ هفته)

| Week | Topic | Theoretical | Practical | Research |
|------|-------|-------------|-----------|----------|
| 1 | مفاهیم اولیه و سیر تکاملی شبکه‌های هوشمند | تعاریف، معماری‌های مرجع (NIST, IEEE)، گذار از شبکه سنتی به هوشمند | آشنایی با دیتاست‌های باز (Pecan Street, Smart City) و بارگذاری در `Python` | بررسی مقالات مروری ۳ سال اخیر (۲۰۲۴–۲۰۲۶) و استخراج ۳ روند نوظهور |
| 2 | اندازه‌گیری، کنترل و ارتباطات هوشمند (AMI, IoT) | زیرساخت AMI، پروتکل‌های `IEC 61850`, `DNP3`، نقش `5G/6G` | شبیه‌سازی ساده شبکه حسگر IoT و تحلیل داده کنتور هوشمند با `Pandas/Python` | چالش‌های تأخیر (Latency) و مقیاس‌پذیری در شبکه‌های توزیع بزرگ |
| 3 | مدیریت سمت تقاضا (DSM) و پاسخگویی بار (DR) | برنامه‌های DR، قیمت‌گذاری پویا، بهینه‌سازی مصرف | مدل بهینه‌سازی DR با `Pyomo` (Python) یا `MATLAB Optimization Toolbox` | پاسخگویی بار رفتاری (Behavioral DR) و انرژی تراکنشی (Transactive Energy) |
| 4 | شبکه هوشمند در ساختمان و خانه‌های هوشمند (BEMS/HEMS) | مدیریت انرژی در سطح خانگی، ادغام منابع تولید پراکنده (DER)، ذخیره‌سازها | شبیه‌سازی مدیریت انرژی خانه هوشمند با الگوریتم‌های ابتکاری یا یادگیری تقویتی (RL) | تجارت همتا-به-همتا (P2P) در یک میکروگرید محلی |
| 5 | ریزشبکه‌ها (Microgrids) و روش‌های مدلسازی و کنترل | انواع ریزشبکه، استراتژی‌های کنترل (`Droop Control`)، حالت متصل/جزیره‌ای | شبیه‌سازی دینامیکی یک ریزشبکه AC در `MATLAB/Simulink` یا `OpenDSS` | کنترل ریزشبکه‌های ۱۰۰٪ مبتنی بر اینورتر و چالش‌های اینرسی پایین |
| 6 | شبکه‌های توزیع فعال (ADN) و مدیریت DERها | چالش‌های نفوذ بالای PV، تنظیم ولتاژ، مدیریت توان راکتیو | تحلیل قابلیت میزبانی (Hosting Capacity) با `OpenDSS` یا `DigSILENT` | بازارهای انعطاف‌پذیری (Flexibility Markets) و نقش تجمیع‌کننده‌ها (Aggregators) |
| 7 | **ارائه پروپوزال (میان‌ترم)** | دانشجویان باید یک «ایده پژوهشی» با «طرح شبیه‌سازی اولیه» ارائه دهند | — | — |
| 8 | کارآیی مصرف‌کنندگان نهایی و تحلیل داده‌های انرژی | شاخص‌های کارایی، هوشمندی انرژی، `Big Data` | پیش‌بینی کوتاه‌مدت بار با `Scikit-learn` یا `PyTorch` | کاربرد هوش مصنوعی توضیح‌پذیر (XAI) در تصمیم‌گیری‌های عملیاتی |
| 9 | شبکه‌های هوشمند و خودروهای برقی (EVs) | چالش‌های بارگذاری EV، فناوری‌های `V2G` و `G2V` | شبیه‌سازی بارگذاری هماهنگ/غیرهماهنگ EV روی پروفیل ولتاژ و تلفات فیدر | مدل‌سازی تخریب باتری (Battery Degradation) و بهینه‌سازی V2G |
| 10 | سیستم‌های پایش، کنترل و حفاظت گسترده (WAMPAC) و PMU | اصول سینکروفازور (PMU)، معماری WAMS، پایش دینامیکی | تحلیل داده‌های PMU واقعی/شبیه‌سازی‌شده برای تشخیص رویداد (Event Detection) | کاربرد PMU در شبکه‌های توزیع فعال (D-PMU) و تخمین حالت |
| 11 | امنیت سایبری-فیزیکی و سایر سیستم‌های هوشمند | تهدیدات سایبری، حملات تزریق داده کاذب (FDIA)، خرابکاری فیزیکی | شبیه‌سازی حمله FDIA و پیاده‌سازی مدل تشخیص مبتنی بر یادگیری ماشین | هماهنگی حملات سایبری و استفاده از دوقلوی دیجیتال (Digital Twin) برای امنیت |
| 12 | هوش مصنوعی و یادگیری ماشین در شبکه‌های هوشمند (مبحث تکمیلی) | مروری بر `Deep Learning` و `Reinforcement Learning` در بهره‌برداری شبکه | کارگاه کدنویسی: آموزش یک عامل RL برای مدیریت باتری در ریزشبکه | چالش‌های استقرار AI در محیط‌های واقعی (Data Scarcity, Generalization) |
| 13 | دوقلوی دیجیتال (Digital Twins) و تحلیل‌های پیشرفته | مفهوم دوقلوی دیجیتال، همگام‌سازی داده‌های انرژی، بلادرنگ | طراحی مفهومی یک دوقلوی دیجیتال برای یک ساختمان یا فیدر توزیع | شکاف‌های استانداردسازی و امنیت داده در دوقلوی دیجیتال شبکه |
| 14 | حامل‌های انرژی نوین و آینده شبکه‌های هوشمند | بازارهای محلی انرژی، بلاکچین در انرژی، شبکه‌های هوشمند نسل بعد (Smart Grid 2.0) | شبیه‌سازی تسویه بازار (Market Clearing) با استفاده از بهینه‌سازی خطی | ادغام بخش‌های انرژی (Sector Coupling): برق، حرارت، هیدروژن |
| 15 | **ارائه پروژه‌های نهایی دانشجویی** | ارائه پروژه‌ها در قالب یک مقاله کنفرانسی ۶ صفحه‌ای (شامل مقدمه، روش، نتایج شبیه‌سازی، نتیجه‌گیری) | — | — |
| 16 | **جمع‌بندی و بررسی مسیرهای پژوهشی آینده** | مرور کلی درس، معرفی ژورنال‌های هدف (IEEE Trans. Smart Grid, Applied Energy) و نکات کلیدی نگارش مقاله | — | — |

---

## 📊 Assessment (Suggested) | سیستم ارزشیابی

| Activity | Weight | Description |
|----------|--------|-------------|
| حضور و مشارکت | 10% | مشارکت در بحث‌های پژوهشی و کارگاه‌ها |
| تکالیف عملی | 30% | حداقل ۴ تمرین — ارزیابی توانایی کار با ابزارها و پیاده‌سازی مفاهیم |
| ارائه مقاله (سمینار پژوهشی) | 20% | ارزیابی توانایی تحلیل و نقد مقالات معتبر علمی |
| پروژه نهایی | 40% | ارزیابی جامع از توانایی انجام یک کار عملی و پژوهشی |

---

## 🛠️ Tools & Software | ابزارهای نرم‌افزاری پیشنهادی

### Power System Analysis | تحلیل سیستم‌های قدرت
- **OpenDSS** (Free & Open Source) — Distribution system analysis
- **MATLAB/Simulink** — Dynamic simulation
- **DigSILENT PowerFactory** — Advanced power system analysis

### Data Science & AI | علم داده و هوش مصنوعی
- **Python**: `Pandas`, `Scikit-learn`, `PyTorch/TensorFlow`
- **Pyomo** — Optimization

### Datasets | دیتاست‌های باز
- UCI Machine Learning Repository (Smart Homes)
- Pecan Street
- Dataport
- IEEE PES Test Feeders

---

## 📚 Course References | منابع درس

### Primary References
1. M. Parsa Moghaddam, R. Zamani, H.H. Alhelou, P. Siano (eds.), *Decentralized Frameworks for Future Power Systems: Operation, Planning and Control Perspectives*. Academic Press, 2022.
2. C. W. Gellings, *The Smart Grid: Enabling Energy Efficiency and Demand Response*. The Fairmont Press, 2009.
3. J. Momoh, *Smart Grid: Fundamentals of Design and Analysis*. Wiley-IEEE Press, 2012.
4. G. Gharehpetian, M. Shahidehpour, B. Zaker, *Smart Grids and Microgrids*. Amirkabir University of Technology Press, 3rd Edition, 1400 (2021).

### New References (Updated) | منابع جدید
5. F. Blaabjerg et al., "Artificial Intelligence and Machine Learning in Smart Grids: Recent Advances and Future Trends." *IEEE Transactions on Smart Grid*, 2024.
6. A. Anvari-Moghaddam et al., "Cyber-Physical Security and Resilience in Smart Grids: A Comprehensive Review." *Applied Energy*, 2025.
7. *IEEE PES Smart Grid: The Role of Digital Twins and Transactive Energy*. IEEE Press, 2023.

---

## 🎓 Final Project | پروژه پایانی

Students in groups of 2–3 define a project with two distinct phases:

### Phase 1 — Practical Goal | فاز اول (هدف اول)
Implementation of a specific module on a simulation platform (e.g., implementing a demand response strategy for a building or designing a control system for a microgrid).  
اجرای یک ماژول مشخص بر روی یک پلتفرم شبیه‌سازی.

### Phase 2 — Research Goal | فاز دوم (هدف دوم)
Writing a technical report similar to a paper, including:
- Literature review (مرور ادبیات)
- Problem definition (تعریف مسئله)
- Proposed methodology (روش پیشنهادی)
- Results analysis (تحلیل نتایج)
- **At least one innovative idea** compared to reviewed papers (حداقل یک ایده نوآورانه)

**Final Output | خروجی نهایی:** Oral presentation and submission of final report (IEEE format).

---

## 🧠 Session Structure | جلسات هفتگی (۳ ساعت در هفته)

| Section | Duration | Description |
|---------|----------|-------------|
| **بخش اول — مبانی نظری** | ۶۰ دقیقه | ارائه مفاهیم اصلی با تأکید بر «چرایی» و «چگونگی» عملکرد سیستم |
| **بخش دوم — کارگاه عملی** | ۶۰ دقیقه | حل مسائل واقعی، کار با نرم‌افزارها، کدنویسی یا شبیه‌سازی سناریوها |
| **بخش سوم — سمینار پژوهشی** | ۶۰ دقیقه | معرفی و نقد یک مقاله جدید + طوفان فکری ایده‌های پژوهشی |

---

## 📁 Repository Structure | ساختار مخزن

```
smart-grid-course/
├── README.md
├── requirements.txt
├── syllabus/
│   ├── course_outline.pdf
│   └── weekly_schedule.md
├── lectures/
│   ├── week01/
│   │   ├── slides.pdf
│   │   └── notes.md
│   ├── week02/
│   └── ...
├── assignments/
│   ├── assignment01/
│   │   ├── problem_statement.md
│   │   └── solution/
│   └── ...
├── projects/
│   ├── sample_projects.md
│   └── templates/
│       ├── proposal_template.md
│       └── paper_template.md
├── code/
│   ├── python/
│   │   ├── load_forecasting.py
│   │   ├── dr_optimization.py
│   │   └── ...
│   └── matlab/
│       ├── microgrid_sim.m
│       └── ...
├── datasets/
│   └── README.md
└── resources/
    ├── papers/
    └── tools.md
```

---

## 🚀 Getting Started | شروع به کار

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/smart-grid-course.git
   cd smart-grid-course
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Explore weekly materials:**
   - Navigate to `lectures/` for slides and notes
   - Check `assignments/` for practical exercises
   - Review `projects/` for final project guidelines

---

## 🤝 Contributing | مشارکت

Contributions, suggestions, and improvements are welcome!

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

---

## 📄 License | مجوز

This course material is provided for educational purposes. Please respect the copyright of all referenced papers and materials.

---

## 📧 Contact | تماس

For questions or further information, please contact the course instructor.

---

**⭐ If you find this repository useful, please give it a star!**
