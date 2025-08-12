# CSS Basics (Pronunciation: See-Ess-Ess)

Bu README.md fayli CSS (Cascading Style Sheets) haqida asosiy ma'lumotlarni o'z ichiga oladi. Har bir terminning oldiga inglizcha talaffuzi qo'shilgan (masalan, "CSS" - "see-ess-ess"). Tushuntirishlar qisqa va aniq, o'zbek tilida.

## CSS nima uchun kerak (Pronunciation: See-Ess-Ess)
CSS veb-sahifalarning ko'rinishini (rang, o'lcham, joylashuv) boshqarish uchun ishlatiladi. HTML struktura beradi, CSS esa dizayn qiladi.

## CSS ni versiyasi (Pronunciation: See-Ess-Ess Version)
CSS ning hozirgi asosiy versiyasi CSS3. Eski versiyalar: CSS1 (1996), CSS2 (1998). CSS4 rasmiy emas, lekin modullar orqali yangilanadi.

## CSS ishlatishni nechi xil usuli bor (Pronunciation: See-Ess-Ess Usage Methods)
CSS ni ishlatishning 3 ta usuli bor: Internal, Inline, External.

### Internal usuli (Pronunciation: In-Ter-Nal)
HTML faylining ichida `<style>` tegi orqali yoziladi. Sahifaga xos stil uchun.

### Inline usuli (Pronunciation: In-Line)
Elementning `style` atributida to'g'ridan-to'g'ri yoziladi. Masalan: `<p style="color: red;">Matn</p>`. Tez o'zgartirish uchun.

### External usuli (Pronunciation: Ex-Ter-Nal)
Alohida .css faylida yoziladi va HTML ga `<link>` tegi bilan bog'lanadi. Ko'p sahifali saytlar uchun ideal.

## color nima qiladi (Pronunciation: Kuh-Ler)
Matn rangini o'zgartiradi. Qiymati: rang nomi, HEX, RGB va hokazo.

## font-size nima qiladi (Pronunciation: Font-Size)
Matn o'lchamini belgilaydi. Qiymati: px, em, rem va hokazo.

## CSS Selectorlar nima uchun kerak (Pronunciation: See-Ess-Ess Se-Lek-Ters)
Selectorlar HTML elementlarini tanlash va stil qo'llash uchun kerak. 5 ta kategoriya: Simple, Combinator, Pseudo-class, Pseudo-element, Attribute Selector.

### Simple Selector (element, id, class) (Pronunciation: Sim-Ple Se-Lek-Ter)
- Element: Teg nomi bo'yicha (masalan, `p` - paragraf).
- ID: `#id` bilan (noyob element).
- Class: `.class` bilan (bir nechta element).

### Combinator Selector (Descendant, Child, Adjacent, General Sibling) (Pronunciation: Com-Bi-Na-Tor Se-Lek-Ter)
- Descendant: Bo'shliq bilan (masalan, `div p` - div ichidagi p).
- Child: `>` bilan (to'g'ridan-to'g'ri bola).
- Adjacent: `+` bilan (keyingi aka-uka).
- General Sibling: `~` bilan (barcha aka-uka).

### Pseudo-class Selector (Pronunciation: Soo-Doh-Class Se-Lek-Ter)
Element holatini tanlaydi (masalan, `:hover` - sichqoncha ustida).

### Pseudo-element Selector (Pronunciation: Soo-Doh-El-E-Ment Se-Lek-Ter)
Element qismini tanlaydi (masalan, `::before` - oldidan qo'shish).

### Attribute Selector (Pronunciation: At-Tri-Byoot Se-Lek-Ter)
Atribut bo'yicha tanlaydi (masalan, `[href]` - href'li elementlar).

## Universal Selector (Pronunciation: Yoo-Ni-Ver-Sal Se-Lek-Ter)
`*` bilan barcha elementlarni tanlaydi.

## Grouping Selector (Pronunciation: Groo-Ping Se-Lek-Ter)
Virgul bilan bir nechta selectorlarni birlashtiradi (masalan, `h1, h2`).

## Color (Pronunciation: Kuh-Ler)
Ranglarni belgilash usullari:

- Color names: Oddiy nomlar (masalan, red, blue). 140+ nom bor, qiymat: 1 ta so'z.
- RGB: rgb(red, green, blue). Har biri 0-255. Masalan, rgb(255, 0, 0) - qizil. 3 ta qiymat.
- RGBA: rgb + alpha (shaffoflik). rgba(red, green, blue, alpha). Alpha: 0-1. 4 ta qiymat.
- HEX: #RRGGBB. Har biri 00-FF. Masalan, #FF0000 - qizil. 6 ta belgi.
- HSL: hsl(hue, saturation, lightness). Hue: 0-360, S/L: 0-100%. 3 ta qiymat.
- HSLA: hsl + alpha. hsla(hue, saturation, lightness, alpha). Alpha: 0-1. 4 ta qiymat.

## width, height, min-width, max-width, min-height, max-height (Pronunciation: Width, Height, Min-Width, Max-Width, Min-Height, Max-Height)
- Width: Element kengligi (px, %, em).
- Height: Element balandligi (px, %, em).
- Min-width: Minimal kenglik.
- Max-width: Maksimal kenglik.
- Min-height: Minimal balandlik.
- Max-height: Maksimal balandlik.

## margin (Pronunciation: Mar-Jin)
Element atrofidagi bo'shliq. Qiymatlar:
- 4 ta: Top, right, bottom, left (masalan, 10px 20px 30px 40px).
- 3 ta: Top, horizontal (right/left), bottom.
- 2 ta: Vertical (top/bottom), horizontal (right/left).
- 1 ta: Barcha tomonlar.

## padding (Pronunciation: Pad-Ding)
Element ichidagi bo'shliq. Margin kabi: 4, 3, 2, 1 qiymat.

## border, border-style, border-width, border-color (Pronunciation: Bor-Der, Bor-Der-Style, Bor-Der-Width, Bor-Der-Kuh-Ler)
- Border: Chegara (width style color).
- Border-style: Chegara turi (solid, dashed, dotted).
- Border-width: Chegara qalinligi (px, thin, medium).
- Border-color: Chegara rangi.

## Box-model (Pronunciation: Box-Mod-El)
Element strukturasini tavsiflaydi: Content (ichki), Padding (ichki bo'shliq), Border (chegara), Margin (tashqi bo'shliq). Umumiy o'lcham: content + padding + border + margin.

## border-radius (Pronunciation: Bor-Der-Ray-Dee-Us)
Burchaklarni yumaloqlashtiradi.
- 4 ta qiymat: Top-left, top-right, bottom-right, bottom-left.
- 3 ta: Top-left, top-right/bottom-left, bottom-right.
- 2 ta: Top-left/bottom-right, top-right/bottom-left.
- 1 ta: Barcha burchaklar.

## outline nima va nima uchun ishlatiladi, border bilan farqi, outline-offset (Pronunciation: Out-Line, Out-Line-Off-Set)
Outline - element atrofidagi qo'shimcha chegara, fokus uchun ishlatiladi (masalan, tugmalar). Farqi: Outline box-modelga ta'sir qilmaydi, border esa qiladi. Outline-offset: Outline va element orasidagi masofa.

## text-decoration-line (required), text-decoration-color, text-decoration-style, text-decoration-thickness (Pronunciation: Text-Dec-O-Ray-Shun-Line, etc.)
- Text-decoration-line: Chiziq turi (underline - ostiga, overline - ustiga, line-through - o'rtasiga, none - yo'q). Required.
- Text-decoration-color: Chiziq rangi.
- Text-decoration-style: Chiziq uslubi (solid - to'la, double - ikkita, dotted - nuqta, dashed - chiziqcha, wavy - to'lqinli).
- Text-decoration-thickness: Chiziq qalinligi (px, auto).

## text-transform nima uchun kerak (Pronunciation: Text-Trans-Form)
Matn registrini o'zgartirish uchun. Qiymatlar:
- Uppercase: Barcha harflarni katta qiladi (HELLO).
- Lowercase: Barcha harflarni kichik qiladi (hello).
- Capitalize: Har so'zning birinchi harfini katta qiladi (Hello World).
- None: O'zgartirmaydi.

## text-align (Pronunciation: Text-A-Line)
Matnni joylashtirish: left (chap), right (o'ng), center (o'rta), justify (ikkala tomonga).

## text-indent (Pronunciation: Text-In-Dent)
Birinchi qatorni chetga suradi (px, em).

## line-height (Pronunciation: Line-Height)
Qatorlar orasidagi masofa (px, em, raqam - font-size ko'paytmasi).

## letter-spacing (Pronunciation: Let-Ter-Spay-Sing)
Harflar orasidagi masofa (px, em).

## word-spacing (Pronunciation: Word-Spay-Sing)
So'zlar orasidagi masofa (px, em).

## font-family (Pronunciation: Font-Fam-I-Lee)
Shrift turi (masalan, Arial, sans-serif). Bir nechta variant, zaxira sifatida.

## font-weight (Pronunciation: Font-Wait)
Shrift qalinligi: normal (400), bold (700), lighter, bolder, 100-900.

## font-style (Pronunciation: Font-Style)
Shrift uslubi: normal, italic (kursiv), oblique (egri).
