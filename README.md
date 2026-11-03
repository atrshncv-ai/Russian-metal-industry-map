# Russian Metal Industry Map

An interactive map of the Russian metallurgy industry — a research/coursework project built with **Next.js + React + TypeScript**.

> **Status: experiment** — research project, not a production service.

## Features

- Interactive map of Russian regions with switchable indicators
- Click a region to see detailed statistics for all indicators
- Indicator gradation via blue shading + legend with integer intervals
- Export the map to PNG together with title and legend
- Full alphabetical list of all 89 regions
- Federal cities (Moscow, Saint Petersburg, Sevastopol) marked on the map

## Data & map

- Data: [`public/data/map-data.json`](public/data/map-data.json)
- SVG map: [`public/data/russia-map-clean.svg`](public/data/russia-map-clean.svg)

## Local run

```bash
npm install
npm run dev
```

Open `http://localhost:3000`. Build: `npm run build && npm run start`.

---

# Russian Metal Industry Map

Интерактивная карта металлургии России — исследовательский/учебный проект на **Next.js + React + TypeScript**.

> **Статус: experiment** — исследовательский проект, не production-сервис.

## Возможности

- Интерактивная карта регионов РФ с переключением показателей
- Клик по региону открывает подробную статистику по всем индикаторам
- Градация показателей заливкой оттенками синего + легенда с целыми интервалами
- Экспорт карты в PNG вместе с названием и легендой
- Полный список всех 89 регионов (алфавитный порядок)
- Города федерального значения (Москва, Санкт-Петербург, Севастополь) — маркерами

## Данные и карта

- Данные: [`public/data/map-data.json`](public/data/map-data.json)
- SVG-карта: [`public/data/russia-map-clean.svg`](public/data/russia-map-clean.svg)

## Локальный запуск

```bash
npm install
npm run dev
```

Откройте `http://localhost:3000`. Сборка: `npm run build && npm run start`.

## License / Лицензия

Released under the MIT License. See [LICENSE](LICENSE).
Проект распространяется по лицензии MIT. См. [LICENSE](LICENSE).
