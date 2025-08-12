Tushunarli, sen aytgan barcha CSS tushunchalarini **qisqa, aniq** va **README.md** formatida, ingliz tilidagi nomlarini talaffuz (phonetic transcription) bilan yozib chiqaman.
Har bir atamani tushuntirishda **ortiqcha gap yo‘q**, faqat kerakli joylari to‘liq bo‘ladi.

Quyida tayyor README.md:

---

```markdown
# CSS Asosiy Qo'llanma

## CSS nima? *(Cascading Style Sheets [ˈkæskeɪdɪŋ staɪl ʃiːts])*
- **Vazifasi:** HTML elementlarga dizayn, rang, o'lcham va joylashuv berish.
- **Versiyalari:** CSS1, CSS2, CSS2.1, CSS3 (eng ko‘p ishlatiladi).
- **Ishlatish usullari:**
  1. **Inline [ˈɪnˌlaɪn]** – `style` atributida yoziladi.
  2. **Internal [ɪnˈtɜːrnəl]** – `<style>` tegi ichida.
  3. **External [ɪkˈstɜːrnəl]** – alohida `.css` faylda.

---

## Asosiy property'lar

### Rang va o‘lcham
- **color [ˈkʌlər]** – matn rangi.
- **font-size [fɒnt saɪz]** – matn hajmi.

---

## CSS Selector'lar *(tanlovchilar)*

### Nima uchun kerak?
HTML elementlarni tanlab, ularga style berish uchun.

### 5 category:
1. **Simple Selectors** – element, id, class.
2. **Combinator Selectors** – descendant (`space`), child (`>`), adjacent (`+`), general sibling (`~`).
3. **Pseudo-class [ˈsjuːdoʊ klæs]** – `:hover`, `:focus`.
4. **Pseudo-element [ˈsjuːdoʊ ˈɛlɪmənt]** – `::before`, `::after`.
5. **Attribute Selector** – `[type="text"]`.

### Qo‘shimcha:
- **Universal Selector [juːnɪˈvɜːrsəl]** – `*` barcha elementlarni tanlaydi.
- **Grouping Selector [ˈɡruːpɪŋ]** – `h1, h2, p` bir necha elementlarni birga tanlaydi.

---

## Rang formatlari
1. **Color names** – `red`, `blue`.
2. **RGB [ɑːr dʒiː biː]** – `rgb(255, 0, 0)` (0–255 oralig‘i).
3. **RGBA** – `rgba(255, 0, 0, 0.5)` (`a` – transparency, 0–1).
4. **HEX [hɛks]** – `#ff0000` yoki qisqa `#f00` (0–9, a–f).
5. **HSL [eɪtʃ ɛs ɛl]** – `hsl(0, 100%, 50%)` (Hue: 0–360°, Saturation/Lightness: %).
6. **HSLA** – `hsla(0, 100%, 50%, 0.5)` (`a` – transparency).

---

## O‘lcham va joylashuv
- **width** – kenglik.
- **height** – balandlik.
- **min-width / max-width** – minimal / maksimal kenglik.
- **min-height / max-height** – minimal / maksimal balandlik.
- **margin [ˈmɑːrdʒɪn]** – tashqi bo‘shliq:  
  - 4 qiymat: `top right bottom left`  
  - 3 qiymat: `top horizontal bottom`  
  - 2 qiymat: `vertical horizontal`
- **padding [ˈpædɪŋ]** – ichki bo‘shliq (margin qoidalari bilan bir xil).
- **border [ˈbɔːrdər]** – element chegarasi.
  - **border-style** – `solid`, `dashed`, `dotted`.
  - **border-width** – qalinlik (px).
  - **border-color** – rang.

---

## Box Model [bɒks ˈmɒdəl]
Element tuzilishi: **content → padding → border → margin**.

---

## border-radius [ˈbɔːrdər ˈreɪdiəs]
- **4 qiymat:** har bir burchak uchun radius.  
- **3 qiymat:** `top-left`, `top-right/bottom-left`, `bottom-right`.

---

## outline [ˈaʊtlaɪn]
- **Vazifasi:** element atrofida tashqi chiziq (border ichida emas).
- **Farqi:** border layoutga ta'sir qiladi, outline qilmaydi.
- **outline-offset** – outline va element orasidagi masofa.

---

## Matn bezash
- **text-decoration-line** – `underline`, `overline`, `line-through`.
- **text-decoration-color** – rang.
- **text-decoration-style** – `solid`, `dashed`, `wavy`.
- **text-decoration-thickness** – chiziq qalinligi.

---

## Matn o‘zgartirish
- **text-transform**:
  - `uppercase` – barcha harflar katta.
  - `lowercase` – barcha kichik.
  - `capitalize` – har bir so‘z bosh harfi katta.

---

## Matn joylashuvi va oralig‘i
- **text-align** – `left`, `right`, `center`, `justify`.
- **text-indent** – birinchi satrni chetga surish.
- **line-height** – satr balandligi.
- **letter-spacing** – harflar oralig‘i.
- **word-spacing** – so‘zlar oralig‘i.

---

## Shrift sozlamalari
- **font-family** – shrift turi (`Arial`, `Verdana`).
- **font-weight** – qalinlik (`normal`, `bold`, `100–900`).
- **font-style** – `normal`, `italic`, `oblique`.

---
```

---

Agar xohlasang, men bunga **CSS kod misollari** qo‘shib README’ni **vizual** qilib beraman, shunda nazariya bilan amaliyot birga bo‘ladi.
Shunday qilaymi, tayyor qilib beraymi?
