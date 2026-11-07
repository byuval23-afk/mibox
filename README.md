# mibox — HomeCast TV

מקלט AirPlay ביתי ללא פרסומות עבור Mi Box ו־Android TV.

## הורדה דרך Downloader

[הורדת APK להתקנה](https://github.com/byuval23-afk/mibox/releases/latest/download/mibox.apk)

הזינו ב־Downloader את כתובת ההורדה הישירה, אפשרו התקנה מ־Downloader ופתחו את HomeCast TV. באייפון: מרכז הבקרה ← שיקוף מסך ← Home TV. שני המכשירים צריכים להיות באותה רשת ביתית.

## תאימות ובדיקות

- Android 7 ומעלה; ARMv7 ו־ARM64. אין התקנה ישירה על Samsung Tizen או LG webOS.
- נבדקו שיקוף עם תמונה וקול, מעבר ל־YouTube וחיבור מחדש על MiTV-AFKR0 עם Android 11.
- הותקן והשרת הופעל גם על MIBOX4 עם Android 9; לא בוצעה בו בדיקת שיקוף נפרדת.
- גרסה ביתית חתומה במפתח Debug. אין הבטחת תאימות לכל מכשיר או תוכן DRM.
- HomeCast מקבל AirPlay; לשידור מ־Chrome או מאנדרואיד השתמשו ב־Google Cast המובנה במכשיר.

## קוד מקור ורישיון

[קוד מקור מלא והוראות בנייה](https://github.com/byuval23-afk/mibox/releases/latest/download/HomeCast-TV-Source.zip)

מבוסס על [Android AirPlay Server](https://github.com/jqssun/android-airplay-server/tree/v0.0.17), מנוע [UxPlay](https://github.com/FDH2/UxPlay), ALAC, libplist ו־OpenSSL. קוד האפליקציה תחת GPL-3.0; רישיונות התלויות כלולים במקור.

התאמות HomeCast: שם האפליקציה, חבילת התקנה נפרדת, ברירות מחדל H.264/1080p/30FPS, בנייה ב־Windows ואיפוס מפענח התמונה בשינוי גודל ובניתוק.
