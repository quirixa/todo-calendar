
# Ethiopian Calendar (EC) 

A lightweight **Ethiopian Calendar web app** built with **HTML, CSS, and Vanilla JavaScript**.
It displays Ethiopian years, months, and days with accurate date conversion and real Ethiopia time (GMT+3).

---

## Overview

This project:

* Converts **Gregorian dates → Ethiopian dates**
* Uses **Africa/Addis_Ababa (GMT+3)** timezone
* Highlights:

  * **Today**
  * **Past dates**
  * **Future dates**
* Handles **Pagumen (5 or 6 days)** correctly
* Updates automatically at midnight

No frameworks. No APIs. Fully client-side.

---

## Code Structure

* **HTML**

  * Defines the calendar layout, navigation, and containers

* **CSS**

  * Dark theme styling
  * Controls day states (past / today / future / holiday)

* **JavaScript**

  * Ethiopian date conversion using Julian Day logic
  * Real-time clock (GMT+3)
  * Calendar rendering (months, days, Pagumen)
  * Year navigation and state updates

---

## Key Logic

* `gregorianToEthiopian()`
  Converts the current Gregorian date into Ethiopian year, month, and day

* `nowEthiopia()`
  Ensures all date calculations use Ethiopia’s timezone

* Dynamic rendering
  Calendar updates when:

  * The year changes
  * A new day starts (midnight)

---

## Usage

Open `index.html` in a modern browser.
No setup or build steps required.

---

## Notes

* Ethiopian leap year rule: `year % 4 === 3`
* Works offline
* Designed to preserve visual consistency while updating logic only

---


