# Pelican Guest House & Hostel

Live site: https://pelican.chernivtsi.space

## About
Pelican Guest House & Hostel — гостьовий дім і хостел у Чернівцях. Односторінковий лендинг. Фото закладу немає (`photos_source: null`), тому hero типографічний (CSS/SVG), а єдині фото — міста Чернівців з Pexels (див. Photos).

## Hero concept
Поштова марка: перфорований край, стилізований пелікан над хвилями, «Чернівці · Гоголя, 7А» і поштовий штемпель PELICAN · ЧЕРНІВЦІ.

## Amenities (verified, list.json)
- Безкоштовний Wi‑Fi
- Спільна кухня
- Сад
- Тераса
- Спільний лаунж
- Сімейні номери
- Туристичне бюро
- Номери для некурців

## Check-in / check-out
Заїзд 13:00–23:00; Виїзд 06:00–11:00

## Rooms (Booking.com room table; T&S and Панський Двір 2 from the official site)
- Ліжко-місце в загальному номері — Змішаний номер для гостей обох статей
- Стандартний двомісний номер — 1 двоспальне ліжко
- Двомісний номер з 2 односпальними ліжками — 2 односпальні ліжка
- Сімейний номер — Двоспальне й двоярусне ліжко або 5 односпальних, до 5 гостей

## House rules (Booking.com)
- Хто може заселитися? Мінімальний вік для реєстрації заїзду — 18 років. Діти будь-якого віку можуть проживати разом із дорослими.
- Чи є дитячі ліжечка й додаткові ліжка? Ні, їх не надають.
- Чи можна з домашньою твариною? Ні, розміщення з тваринами заборонене.
- Як оплатити проживання? Готівкою.
- Коли повідомити про приїзд? Заїзд з 13:00 до 23:00 — повідомте адміністрації заздалегідь, о котрій приїдете.

## Reviews
Booking.com 8.9/10 (1018), Google 4.6/5 (256). Знімок на 30.09.2026, платформи окремо, без aggregateRating.

## Contact
- Phone: +380 50 999 6141
- Booking.com: https://www.booking.com/hotel/ua/pelican-hostel.uk.html
- Google Maps: https://maps.google.com/?cid=5318888560342341008
- Address: вул. Миколи Гоголя, 7А, Чернівці

## Sources
Booking.com listing text (description, rooms, breakfast, house rules; guest reviews ignored), captured 30.09.2026, plus the official site where there is one. Verbatim quotes: `facts.json` in the build scratchpad.

## Not published
Кількість кімнат і ліжок, типи дормів, зірковість (Google Hotels показує 3★, але це хостел), email, сайт, Instagram. Телефон +380 50 999 6141 (один варіант Google Hotels мав +380 95 048 4543) — бажано підтвердити.

## Forms
HotelOS (`ch-pelican`): `stay-request` (хостельний варіант зі статтю гостей). Документ `hotels/ch-pelican` у Firestore треба створити вручну, інакше правила відхилять заявки.

## Photos
Лише фото міста (не готелю), з Pexels, підключені за прямими посиланнями images.pexels.com (без копій у репо), з підписами та авторами на сторінці:

- Резиденція буковинських митрополитів, нині Чернівецький університет: pexels.com/photo/39176014 (Tetiana Boriskova)
- Чернівецький дворик: pexels.com/photo/17265321 (Андрій Копічевський)
- Храм у Резиденції митрополитів: pexels.com/photo/20074400 (Anastasiia Kalushka)

## SEO
Title і description з маніфесту, canonical, Open Graph, `geo.*`, JSON-LD `Hostel` лише з підтвердженими полями (без numberOfRooms, starRating, aggregateRating), `robots.txt`, `sitemap.xml`, `404.html`.
