# مصنع المنشاوي لإعادة التدوير

موقع رسمي لمصنع المنشاوي المتخصص في إعادة تدوير البلاستيك.
تحت إدارة الحاج / صديق طه المنشاوي — تأسس عام 2010.

**Live site:** [https://almenshawy.net](https://almenshawy.net)

---

## محتويات المجلد

| الملف | الغرض |
|------|------|
| `index.html` | الموقع كامل (كل الـ CSS والـ SVG جوّاه) |
| `favicon.svg` | أيقونة الموقع في تاب المتصفح |
| `CNAME` | يربط GitHub Pages بدومين almenshawy.net |
| `.nojekyll` | يمنع GitHub من معالجة الملفات بـ Jekyll |
| `README.md` | هذا الملف |

---

## 1. رفع الملفات على GitHub

1. روح على [github.com](https://github.com) واعمل **New repository**.
2. الاسم: `almenshawy-site` (أو أي اسم). خليه **Public**.
3. **مهم:** متحطش علامة على "Add a README file" (عندنا واحد جاهز).
4. اضغط **Create repository**.
5. في الصفحة الجديدة، اضغط **"uploading an existing file"**.
6. اسحب كل الملفات الـ 5 من المجلد (`index.html`, `favicon.svg`, `CNAME`, `.nojekyll`, `README.md`).
7. اكتب "Initial commit" واضغط **Commit changes**.

---

## 2. تفعيل GitHub Pages

1. من الـ repo: **Settings** → **Pages** (من القائمة اليسار).
2. تحت **"Source"**: اختر **Deploy from a branch**.
3. **Branch:** `main` · **Folder:** `/ (root)` → اضغط **Save**.
4. استنى دقيقة. فوق هيظهر: *"Your site is live at..."*

---

## 3. ربط دومين almenshawy.net

### أ) من مزود الدومين (مثلاً GoDaddy, Namecheap, سعودي.نت):

افتح إعدادات **DNS** للدومين وضيف السجلات دي:

**لربط الدومين الرئيسي (almenshawy.net):**

| Type | Name | Value |
|------|------|-------|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |

**لربط www.almenshawy.net (موصى به):**

| Type | Name | Value |
|------|------|-------|
| CNAME | www | `[username].github.io` |

(استبدل `[username]` باسم مستخدمك على GitHub)

### ب) من GitHub:

1. **Settings** → **Pages** → تحت **"Custom domain"**.
2. اكتب: `almenshawy.net` → اضغط **Save**.
3. استنى حتى يظهر ✅ **DNS check successful** (ممكن ياخد من دقيقة لـ 24 ساعة).
4. علّم على **"Enforce HTTPS"** (مهم للأمان).

---

## 4. التخصيص قبل النشر

افتح `index.html` بأي محرر نصوص وعدّل:

- **رقم التليفون:** ابحث عن `+٢٠ ١٠٠ ٠٠٠ ٠٠٠٠` واستبدله بالرقم الفعلي
- **البريد الإلكتروني:** `info@almenshawy.net` — جاهز (أو عدّل لو عايز)
- **العنوان:** ابحث عن `المنطقة الصناعية` واستبدله بالعنوان الفعلي

---

## الدعم الفني

- **التقنيات:** HTML5 + CSS3 (بدون أي مكتبات خارجية)
- **الخطوط:** IBM Plex Sans Arabic + Inter (من Google Fonts)
- **اللغة:** عربي كامل (RTL)
- **Responsive:** يعمل على كل الأجهزة (ديسكتوب، تابلت، موبايل)
