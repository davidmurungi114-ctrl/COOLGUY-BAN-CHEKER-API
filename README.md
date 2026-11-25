<div align="center">

![PROFESSOR COOLGUY TECH WRLD](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=32&pause=1000&color=25D366&center=true&vCenter=true&width=600&lines=PROFESSOR+COOLGUY+TECH+WRLD;WhatsApp+Ban+Checker)

<img src="https://files.catbox.moe/fz2wom.jpg" width="230" alt="PROFESSOR COOLGUY" />

![LIVE](https://img.shields.io/badge/%E2%97%8F_LIVE-API_CONNECTED-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)
![PROFESSOR COOLGUY](https://img.shields.io/badge/PROFESSOR_COOLGUY-TECH_WRLD-25D366?style=for-the-badge)

<br><br>

[![OPEN LIVE CHECKER](https://img.shields.io/badge/OPEN_LIVE_CHECKER-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://davidmurungi114-ctrl.github.io/COOLGUY-NAN-CHEKER-API/)
[![OFFICIAL CHANNEL](https://img.shields.io/badge/OFFICIAL_CHANNEL-0088cc?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/PROFESSORCOOLGUY)
[![OWNER](https://img.shields.io/badge/OWNER-PROFESSOR_COOLGUY-black?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/PROFESSORCOOLGUY)

</div>

---

This repository contains the GitHub Pages frontend and documentation for the hosted status API. Browser requests use a proxy because the upstream API does not accept browser CORS preflight requests.

The site prefills `+256753984038` as an example but sends no request on load. A lookup is sent only after a visitor presses **CHECK STATUS**.

## What it does
- Check WhatsApp number status
- Shows ban info, validation, formatting
- Shows appeal eligibility and timestamps
- Shows full API response, no guessed fields

## Validation

A missing `number` was observed as HTTP `422`:

```json
{"ok":false,"error":{"code":"missing_number","message":"Provide an international phone number with its country calling code."}}
