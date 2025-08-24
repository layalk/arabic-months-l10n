# Arabic Month Names — PO Files (L10N)

**Three localized variants of Arabic month names** packaged as GNU Gettext `.po` files.  
Each file includes **24 entries**:  
- 12 with `msgctxt "Long month name"`  
- 12 with `msgctxt "Abbreviated month name"`

> Originally created for the **Localize.Drupal.org (LDO) Arabic team**, and now general‑purpose for any platform that supports PO files.  
> Wiki page: https://localize.drupal.org/node/64212

---

## Variants

- **Egypt / Gulf**: “يناير، فبراير، مارس…”  
  Abbreviations intentionally **duplicate** the long names for consistency.
- **Levant**: “كانون ٢، شباط، آذار… تشرين ١، تشرين ٢، كانون ١”  
  Note: **January = كانون ٢**, **December = كانون ١**.  
  Abbreviations are the same visible strings (e.g., “تشرين ١”).
- **Maghreb**: “جانفي، فيفري، مارس… جويلية، أوت…”  
  Abbreviations intentionally **duplicate** the long names for consistency.

### Files

```
months-egypt-gulf.po
months-levant.po
months-maghreb.po
```

### Direct downloads (latest release)

- Egypt / Gulf:  
  https://github.com/layalk/arabic-months-l10n/releases/latest/download/months-egypt-gulf.po
- Levant:  
  https://github.com/layalk/arabic-months-l10n/releases/latest/download/months-levant.po
- Maghreb:  
  https://github.com/layalk/arabic-months-l10n/releases/latest/download/months-maghreb.po

---

## Usage

These PO files are **generic** and can be used anywhere PO translations are supported.

### Drupal (example)

1. Download the `.po` file that matches your target locale variant.
2. In the admin UI, go to: `Configuration » Regional and language » User interface translation » Import`.
3. Choose **Arabic** as the language, upload the `.po`, and import.
4. Clear caches if needed.

### Generic Gettext

- Edit with **Poedit** or similar tools.
- Compile to `.mo` when needed:
  ```bash
  msgfmt -o months-egypt-gulf.mo months-egypt-gulf.po
  ```

---

## Format Notes

- Each entry uses one of these contexts:
  - `msgctxt "Long month name"`
  - `msgctxt "Abbreviated month name"`
- In **Egypt/Gulf** and **Maghreb**, abbreviated names are **identical** to long names by design.
- In **Levant**, “الأول/الثاني” are represented as **1/2** (e.g., “تشرين ١”, “تشرين ٢”).

---

## Contributing

PRs welcome! If you spot regional nuances, spelling preferences, or need additional variants, please open an issue or submit a pull request.

**Acknowledgements**  
Thanks to the **Localize.Drupal.org Arabic team** for initiating this work and providing guidance:
- Language page: https://localize.drupal.org/translate/languages/ar
- Repo: https://github.com/layalk/arabic-months-l10n
- Project wiki entry: https://localize.drupal.org/node/64212

---

## License

**CC0 1.0 Universal** (Public Domain).  
You can copy, modify, distribute, and use the files, even for commercial purposes, without asking permission.

---

# 🇸🇦🇱🇧🇪🇬🇲🇦 النسخة العربية

**حزم ترجمة لأسماء الأشهر بالعربية** بصيغة Gettext `.po`.  
يحتوي كل ملف على **24 مدخلًا**:
- 12 بسياق `msgctxt "Long month name"`
- 12 بسياق `msgctxt "Abbreviated month name"`

> أُنشئت هذه الحزمة أصلًا لفريق **الترجمة العربية في Localize.Drupal.org (LDO)**، وهي عامة للاستخدام مع أي نظام يدعم ملفات PO.  
> صفحة الويكي: https://localize.drupal.org/node/64212

---

## المتغيرات (Variants)

- **مصر / الخليج**: «يناير، فبراير، مارس…»  
  الاختصارات **مطابقة** للأسماء الكاملة عمدًا للحفاظ على الاتساق.
- **بلاد الشام**: «كانون ٢، شباط، آذار… تشرين ١، تشرين ٢، كانون ١»  
  ملاحظة: **يناير = كانون ٢**، **ديسمبر = كانون ١**.  
  الاختصارات هي نفس الصيغ المرئية (مثل «تشرين ١»).
- **المغرب العربي**: «جانفي، فيفري، مارس… جويلية، أوت…»  
  الاختصارات **مطابقة** للأسماء الكاملة عمدًا للحفاظ على الاتساق.

### الملفات

```
months-egypt-gulf.po
months-levant.po
months-maghreb.po
```

### تنزيل مباشر (آخر إصدار)

- مصر / الخليج:  
  https://github.com/layalk/arabic-months-l10n/releases/latest/download/months-egypt-gulf.po
- بلاد الشام:  
  https://github.com/layalk/arabic-months-l10n/releases/latest/download/months-levant.po
- المغرب العربي:  
  https://github.com/layalk/arabic-months-l10n/releases/latest/download/months-maghreb.po

---

## طريقة الاستخدام

### Drupal

1. نزّلي ملف `.po` المناسب.
2. من الواجهة الإدارية: `الإعدادات » الإقليم واللغة » ترجمة واجهة المستخدم » الاستيراد`.
3. اختاري **العربية**، ثم ارفعي الملف ونفّذي الاستيراد.
4. امسحي الكاش عند الحاجة.

### Gettext عام

- يمكن التحرير عبر **Poedit**.
- للتحويل إلى `.mo`:
  ```bash
  msgfmt -o months-egypt-gulf.mo months-egypt-gulf.po
  ```

---

## ملاحظات تنسيقية

- كل مدخل يستخدم أحد السياقين:
  - `msgctxt "Long month name"`
  - `msgctxt "Abbreviated month name"`
- في **مصر/الخليج** و**المغرب العربي**: الاختصار = الاسم الكامل (عن قصد).
- في **بلاد الشام**: استُبدلت «الأول/الثاني» بـ **1/2** (مثل «تشرين ١»، «تشرين ٢»).

---

## الإسهام

نرحّب بالمشاركة! أي فروق محلية أو تفضيلات إملائية أو متغيرات إضافية—افتحي Issue أو أرسلي Pull Request.

**شكر خاص**  
لفريق **الترجمة العربية في Localize.Drupal.org**:
- صفحة اللغة: https://localize.drupal.org/translate/languages/ar
- المستودع: https://github.com/layalk/arabic-months-l10n
- صفحة الويكي: https://localize.drupal.org/node/64212

---

## الترخيص

**CC0 1.0 Universal** (الملك العام).  
الاستخدام والتعديل والتوزيع لأي غرض — بما في ذلك التجاري — مسموح دون قيود.
