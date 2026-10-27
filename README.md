# YouTube Browser

Ilova faqat `https://m.youtube.com` saytini WebView ichida ochadi. Foydalanuvchi o'zi video yoki musiqa yuklamaydi; barcha kontent YouTube'dan keladi.

## Ilova nima qiladi
- YouTube saytini WebView ichida ochadi.
- Orqa fonda ovoz davom etadi.
- "Boshqa ilovalar ustida ko'rsatish" (overlay) oynasi mavjud.
- Picture-in-Picture (PiP) rejimi mavjud.
- Android 13+ da bildirishnoma ruxsati so'raladi.

## APK ni qanday yuklab olish mumkin
1. GitHub repositoriyadagi `Actions` bo'limiga o'ting.
2. Oxirgi `build-apk` workflow ishini tanlang.
3. `Artifacts` bo'limida `YouTubeBrowser-debug-apk` faylini yuklab oling.
4. Yoki agar tag (`v*`) qo'yilgan bo'lsa, `Releases` sahifasidan APK ni yuklab oling.

## Telefonda "Noma'lum manbalardan o'rnatish" ni yoqish
- Android 8+ da: `Sozlamalar` → `Ilova va bildirishnomalar` → `Maxsus kirish` → `Noma'lum manbalar` yoki `Ilovalarni o'rnatish` → ushbu manbani yoqing.
- Keyin APK faylini oching va o'rnatishni tasdiqlang.

## Overlay ruxsati
- Ilova overlay (suzuvchi oyna) ishlatish uchun telefon sozlamalaridan "Qo'shimcha oynalar" / "Boshqa ilovalar ustida ko'rsatish" ruxsatini bering.
- Ayni paytda `Oyna` tugmasi ishlatilganda bu ruxsat talab qilinadi.

## Batareya optimizatsiyasini "Cheklovsiz" qilish
- `Sozlamalar` → `Batareya` → `Ilova quvvatini optimallashtirish` yoki `Batareya optimizatsiyasi` → ilova uchun `Cheklovsiz` / `Optimallashtirishsiz` tanlang.
- Bu YouTube fon ijrosini yanada barqaror qilishga yordam beradi.

## Cheklov
Bu ilova YouTube veb-saytini ishlatadi, shuning uchun YouTube xizmatining siyosati bilan bog'liq sabablar tufayli fon ijrosi va avtomatik ijro cheklanishi mumkin. Ayniqsa Premium bo'lmagan akkauntlarda. Ilova shaxsiy foydalanish uchun mo'ljallangan.
