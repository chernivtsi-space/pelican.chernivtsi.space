# Pelican Guest House & Hostel

Live site: https://pelican.chernivtsi.space

## About
Pelican Guest House & Hostel — гостьовий дім і хостел у Чернівцях. Односторінковий лендинг без фото (`photos_source: null`): типографіка та CSS/SVG-графіка.

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

## Reviews
Booking.com 8.9/10 (1018), Google 4.6/5 (256). Знімок на 30.09.2026, платформи окремо, без aggregateRating.

## Contact
- Phone: +380 50 999 6141
- Booking.com: https://www.booking.com/hotel/ua/pelican-hostel.uk.html
- Google Maps: https://maps.google.com/?cid=5318888560342341008
- Address: вул. Миколи Гоголя, 7А, Чернівці

## Not published
Кількість кімнат і ліжок, типи дормів, зірковість (Google Hotels показує 3★, але це хостел), email, сайт, Instagram. Телефон +380 50 999 6141 (один варіант Google Hotels мав +380 95 048 4543) — бажано підтвердити.

## Forms
HotelOS (`kp-pelican`): `stay-request` (хостельний варіант зі статтю гостей). Документ `hotels/kp-pelican` у Firestore треба створити вручну, інакше правила відхилять заявки.

## SEO
Title і description з маніфесту, canonical, Open Graph, `geo.*`, JSON-LD `Hostel` лише з підтвердженими полями (без numberOfRooms, starRating, aggregateRating), `robots.txt`, `sitemap.xml`, `404.html`.
