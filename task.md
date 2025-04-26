# TypeScript - 30 ta test

## Test 1
TypeScript qachon ishlab chiqilgan?
- A) 2010
- B) 2012
- C) 2014
- D) 2016

## Test 2
TypeScript kim tomonidan ishlab chiqilgan?
- A) Google
- B) Facebook
- C) Microsoft
- D) Amazon

## Test 3
TypeScript fayllari qanday kengaytma bilan saqlanadi?
- A) .ts
- B) .tsx
- C) .typescript
- D) .type

## Test 4
TypeScript'dagi "tuple" qanday tip hisoblanadi?
- A) O'zgaruvchan uzunlikdagi bir xil elementlar massivi
- B) Kalit-qiymat juftliklari to'plami
- C) Belgilangan uzunlikdagi va har bir pozitsiyada ma'lum tipdagi elementlar massivi
- D) Obyekt tiplarini bog'lash usuli

## Test 5
`interface` va `type` o'rtasidagi farq nima?
- A) Interfeys faqat obyektlar uchun, tip esa har qanday tip uchun ishlatiladi
- B) Interfeys kengaytirilishi (extend) mumkin, tip esa yo'q
- C) Tip faqat primitive tiplar uchun, interfeys esa murakkab tiplar uchun ishlatiladi
- D) Interfeys bir necha bor e'lon qilinishi va birlashtirishi mumkin, tip esa faqat bir marta e'lon qilinadi

## Test 6
TypeScript'da `any` tipi nimani anglatadi?
- A) Tipdagi barcha ma'lumotlarni qabul qila oladi
- B) Faqat raqamlarni qabul qiladi
- C) Faqat obyektlarni qabul qiladi
- D) Faqat stringlarni qabul qiladi

## Test 7
TypeScript'da `unknown` tipining `any` tipidan farqi nima?
- A) `unknown` tipidagi o'zgaruvchilar faqat `null` va `undefined` qiymatlarni qabul qilishi mumkin
- B) `unknown` tipidagi o'zgaruvchiga har qanday qiymat bog'lash mumkin, lekin uni ishlatishdan oldin tip tekshiruvi kerak
- C) `unknown` faqat TypeScript 4.0 dan boshlab mavjud
- D) `unknown` tipi primitive tiplarni qabul qilmaydi

## Test 8
TypeScript'da `never` tipi qanday qo'llaniladi?
- A) Qiymat aslo qaytarmaydigan funksiyalarga (exception, infinite loop)
- B) Hech qachon o'zgarmaydigan o'zgaruvchilarga
- C) Faqat `null` va `undefined` qiymatlar uchun
- D) Faqat ruxsat berilgan enum qiymatlari uchun

## Test 9
Qaysi holatlarda generiklar ishlatiladi?
- A) Faqat funksiyalarda tiplar uchun
- B) Faqat interfeyslarda tiplar uchun
- C) Ko'p tiplar bilan ishlaydigan komponentlar yaratishda
- D) Faqat enum qiymatlarini aniqlashda

## Test 10
"Index Signatures" TypeScript'da nima uchun ishlatiladi?
- A) Massiv indekslarini belgilash uchun
- B) Obyektdagi barcha maydonlarning bir xil tipda bo'lishi uchun
- C) Kalitlari oldindan noma'lum bo'lgan obyektlarni ifodalash uchun
- D) TypeScript fayllarini indekslash uchun

## Test 11
`keyof` operatori nima vazifani bajaradi?
- A) Obyektning xususiyatlarini topish uchun
- B) Obyektning kalitlaridan iborat union tipni qaytaradi
- C) Obyektning qiymatlarini tekshirish uchun
- D) Obyektning primitive tipini aniqlash uchun

## Test 12
Union tiplar (`|`) va Intersection tiplar (`&`) orasidagi farq nima?
- A) Union bir nechta tiplardan birini, Intersection barcha tiplarning kombinatsiyasini bildiradi
- B) Union faqat oddiy tiplar uchun, Intersection faqat murakkab tiplar uchun
- C) Union tiplar istalgan miqdorda tiplar bilan ishlaydi, Intersection faqat ikki tip bilan
- D) Union tiplar runtime'da tekshiriladi, Intersection compile vaqtida

## Test 13
TypeScript'da enum'lar qanday ishlaydi?
- A) Compile vaqtida tekshiriladi va JavaScript kodiga transpile qilinadi
- B) Faqat string qiymatlarni qabul qiladi
- C) Ularga faqat son qiymatlar berish mumkin
- D) JavaScript'da mavjud emas, shuning uchun TypeScript compile jarayonida ular funksiyalarga aylantiriladi

## Test 14
TypeScript'da "literal tiplar" nima vazifani bajaradi?
- A) Faqat string qiymatlarni cheklash uchun
- B) O'zgaruvchi qiymati aniq bir yoki bir nechta qiymatlar bo'lishini ta'minlash uchun
- C) Faqat constant o'zgaruvchilarni e'lon qilish uchun
- D) Faqat son qiymatlar uchun cheklovlar qo'yish

## Test 15
TypeScript decoratorlari qachon ishlatiladi?
- A) HTML elementlari ustida
- B) Classlar, methodlar, propertylar va parametrlarni kengaytirish uchun
- C) Faqat Angular frameworkida ishlatish uchun
- D) TypeScript kodini JavaScript kodiga transpile qilish jarayonini boshqarish uchun

## Test 16
"Declaration Merging" TypeScript'da nima?
- A) Bir nechta alohida e'lon qilingan interfacelarni birlashtirish
- B) Interfeys va classlarni birlashtirish
- C) Modulelarni birlashtirish
- D) Barcha yuklab olingan modullarni yagona obyektga birlashtirish

## Test 17
TypeScript'da "optional chaining" (`?.`) nima uchun ishlatiladi?
- A) Massivlarni birlashtirish uchun
- B) Obyektlarni birlashtirish uchun
- C) Null yoki undefined bo'lishi mumkin bo'lgan obyekt xususiyatlarining xususiyatlariga xavfsiz kirish uchun
- D) Shartli operatorlar uchun qisqartma ko'rinish sifatida

## Test 18
TypeScript'da "nullish coalescing" (`??`) nima vazifani bajaradi?
- A) Null va undefined qiymatlarni tekshirish va defaultni qaytarish, boshqa falsy qiymatlarni emas
- B) Faqat null qiymatlarni defaultga o'zgartirish
- C) Falsy qiymatlarni defaultga o'zgartirish
- D) Tipni null yoki undefined bo'lishi mumkinligini ko'rsatish

## Test 19
`infer` kalit so'zi qaysi vaziyatda ishlatiladi?
- A) Conditional tiplar ichida, tip parametrlarini chiqarib olish uchun
- B) Interfacelar yaratishda
- C) Tipdagi xatolarni tiklash uchun
- D) TypeScript kompilyatoriga ma'lumotlarni yetkazish uchun

## Test 20
`implements` va `extends` kalit so'zlari o'rtasidagi farq nima?
- A) `implements` faqat interfaceni qo'llash uchun, `extends` esa class yoki interfacelarni kengaytirish uchun
- B) `implements` faqat classlarni, `extends` faqat interfacelarni qo'llash uchun
- C) Ularni almashtirish mumkin, chunki bir xil funksiyani bajaradi
- D) `implements` murakkab tiplarni, `extends` oddiy tiplarni qo'llash uchun

## Test 21
TypeScript'da `readonly` modifikatoring vazifasi nima?
- A) Xususiyatni faqat interfacedan o'qish uchun
- B) Xususiyatni faqat bir marta o'qish uchun
- C) Xususiyatga yangi qiymat berish imkonini yo'q qilish uchun
- D) Xususiyatni protected qilish uchun

## Test 22
`strictNullChecks` kompilator opsiyasi nima qiladi?
- A) Faqat null qiymatlarni tekshiradi
- B) Null va undefined qiymatlar xususiyatlarga kirolmasligini ta'minlaydi
- C) O'zgaruvchi null yoki undefined bo'lishi mumkinligini hisobga olishni majbur qiladi
- D) `null` tipini yo'q qiladi

## Test 23
Non-null assertion operatori (`!`) nima vazifani bajaradi?
- A) O'zgaruvchining null emasligini tekshiradi
- B) O'zgaruvchiga null qiymat beradi
- C) Kompilyatorga qiymat null yoki undefined emasligini ishontiradi
- D) O'zgaruvchini boolean tipga aylantiradi

## Test 24
TypeScript'da Protected modifikatori nima qiladi?
- A) Uni faqat class ichida va voris classlaridan turib kirish mumkin
- B) Uni faqat class ichida kirish mumkin
- C) Uni faqat class ichida va do'st classlardan kirish mumkin
- D) Uni class ichida, voris classlarida va class instance'laridan turib kirish mumkin

## Test 25
Qaysi TypeScript konstruktsiyasi JavaScript'da mavjud emas?
- A) Dekoratorlar
- B) Interfacelar
- C) Arrow funksiyalar
- D) Promise'lar

## Test 26
`Pick<T, K>` utility tipining vazifasi nima?
- A) T tipidan K tipidagi barcha xususiyatlarni olish
- B) T tipidan K nomli barcha xususiyatlarni olish
- C) T tipidan K tipidagi xususiyatlardan boshqa barcha xususiyatlarni olish
- D) T tipidan K bilan belgilangan xususiyatlarni olish

## Test 27
`typeof` TypeScript operatorining JavaScript'dagi `typeof` operatoridan farqi nima?
- A) JavaScript'da `typeof` runtime'da, TypeScript'da compile vaqtida ishlaydi
- B) TypeScript'da `typeof` o'zgaruvchilar tipini o'zgartiradi
- C) JavaScript'da `typeof` faqat primitive tiplar bilan ishlaydi
- D) Farq yo'q, ikkalasi ham bir xil ishlaydi

## Test 28
`ReturnType<T>` utility tipining vazifasi nima?
- A) T tipli funksiya parametrlarini aniqlash
- B) T tipli funksiyaning qaytish qiymatining tipini olish
- C) T tipli funksiyani chaqirish va natijasini qaytarish
- D) T tipli funksiyaga yangi qaytish qiymatini berish

## Test 29
TypeScript'da "discriminated unions" nima?
- A) Bir nechta tipdagi ma'lumotlarni bir o'zgaruvchida saqlash usuli
- B) Bir xil tipli ma'lumotlarni farqlash usuli
- C) Common maydon orqali turli tiplarni aniq farqlash imkonini beruvchi pattern
- D) Funksiyalar va tiplar o'rtasidagi bog'lanishni ta'minlash

## Test 30
TypeScript modullarining qanday importlari bor?
- A) Faqat standart import/export
- B) Faqat kommonJS require/exports
- C) Standart import/export, namespace import, default import, side effect import
- D) Faqat kommonJS va AMD import/export
