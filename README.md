<div align="center">

# <span style="color:#25D366;">PROFESSOR COOLGUY TECH WRLD</span>
# <span style="color:#25D366;">WhatsApp Ban Checker</span>

<img src="https://files.catbox.moe/fz2wom.jpg" width="230" style="border-radius:50%; border:3px solid #25D366;" alt="PROFESSOR COOLGUY" />

### <span style="color:#25D366;">● LIVE · API CONNECTED</span>

<br>

[[Open Live Checker](https://img.shields.io/badge/OPEN_LIVE_CHECKER-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://davidmurungi114-ctrl.github.io/COOLGUY-NAN-CHEKER-API/)
[[Official Channel](https://img.shields.io/badge/OFFICIAL_CHANNEL-0088cc?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/PROFESSORCOOLGUY)
[[Owner](https://img.shields.io/badge/OWNER-PROFESSOR_COOLGUY-black?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/PROFESSORCOOLGUY)

</div>

---

This repository contains the GitHub Pages frontend and documentation for the existing hosted status API. Browser requests use a proxy because the upstream API does not accept browser CORS preflight requests.

- Upstream: `https://wastatus-8mg57tmn.manus.space/v1/status`
- Browser proxy: configured to forward to the upstream URL

The site prefills `+256753984038` as an example but sends no request on load. A lookup is sent only after a visitor presses **CHECK STATUS**. The page renders all returned fields, unknown/null values and errors, and preserves raw JSON.

## Request

Send an international number you own or are authorized to check:

```http
POST https://wastatus-8mg57tmn.manus.space/v1/status
Content-Type: application/json
