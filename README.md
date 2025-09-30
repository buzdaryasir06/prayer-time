# Global Prayer Times Calendar

A modern, responsive web app for viewing daily and monthly prayer times for major cities in the UK and USA. This project is built as a **single HTML file** containing all HTML, CSS, and JavaScript—making it easy to use, share, and deploy.

## Features

- **Monthly Calendar View:** See prayer times for every day of the selected month.
- **Daily Prayer Details:** Click any day to view all 5 prayer times with Hijri and Gregorian dates.
- **Show More Button:** Calendar cells show Fajr and Maghrib by default; expand to see all prayers.
- **Hijri & Gregorian Dates:** Both Islamic and Western dates are shown for each day and in the header.
- **Location Selection:** Choose from major cities in the UK and USA, or use your current location.
- **Calculation Methods:** Select from popular prayer time calculation methods.
- **Responsive Design:** Works beautifully on desktop, tablet, and mobile.
- **Countdown Timer:** Shows time remaining for the next prayer.
- **Modern UI:** Clean, professional look with smooth transitions and easy navigation.

## How It Works

- All code (HTML, CSS, JS) is in a single file: `home.html`.
- Prayer times and Hijri dates are fetched from the [Aladhan API](https://aladhan.com/prayer-times-api).
- No API keys are required or exposed.
- The calendar and daily prayer info update automatically as you change city, country, or calculation method.

## Usage

1. **Download or clone this repository.**
2. **Open `home.html` in your browser.**
3. **Select your country, city, and calculation method.**
4. **Browse the calendar and click any day for details.**

## Customization

- To add more cities, update the `cities` object in the JavaScript section.
- To change styles, edit the `<style>` block in the `<head>` section.

## Credits

- Prayer times powered by [Aladhan API](https://aladhan.com/prayer-times-api).
- Icons from [Font Awesome](https://fontawesome.com/).

---

**Made with ❤️ for the global Muslim community.**
