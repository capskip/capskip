<div align="center">

<img src="banner.png" alt="CapSkip, Unlimited Captcha Solver" width="100%">

### Unlimited captcha solving, right on your own machine

High accuracy, low latency, and one flat price. No per-solve fees, no throttling, no limits.

[![Download for Windows](https://img.shields.io/badge/Download%20for%20Windows-2ea44f?style=for-the-badge&logo=windows&logoColor=white)](https://capskip.com/download/CapSkipInstaller.msi)
[![Chrome Extension](https://img.shields.io/badge/Chrome%20Extension-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)](https://chromewebstore.google.com/detail/capskip-%E2%80%93-unlimited-captc/mgciphejglphomemchljofgoeakdfccl)
[![Firefox Add-on](https://img.shields.io/badge/Firefox%20Add--on-FF7139?style=for-the-badge&logo=firefoxbrowser&logoColor=white)](https://addons.mozilla.org/en-US/firefox/addon/capskip-captcha-solver/)

</div>

---

## What is CapSkip?

<div align="center">

<a href="https://www.youtube.com/watch?v=Wu-M0wBTEkY">
  <img src="https://img.youtube.com/vi/Wu-M0wBTEkY/maxresdefault.jpg" alt="Watch the CapSkip demo" width="720">
</a>

<sub>▶️ Watch the demo</sub>

</div>

The [CapSkip Captcha Solver](https://capskip.com) is a desktop app that solves captchas right on your own computer. It runs quietly in the background and exposes a standard captcha-solver HTTP API (the familiar `in.php` and `res.php` endpoints), so your scripts, bots, and apps can solve captchas through one simple local endpoint.

- ♾️ **Unlimited solving.** Solve as many captchas as you want, with no limits and no throttling. This is the whole point.
- 🖥️ **Runs locally.** Captchas are solved on your machine, not on someone else's server.
- 🎯 **High accuracy, low latency.** AI-powered solving that is tuned for speed.
- 💸 **One flat price.** A simple subscription instead of paying for every solve.
- 🔌 **Drop-in HTTP API.** Standard `in.php` and `res.php` endpoints that just work.
- 🧩 **Browser extensions and SDKs.** Chrome and Firefox extensions, plus official libraries for Python, Node.js, .NET, and PHP.

## What it solves

| Captcha type | Supported |
|---|:---:|
| Image CAPTCHA (distorted text) | ✅ |
| reCAPTCHA v2 (checkbox, invisible, enterprise) | ✅ |
| reCAPTCHA v3 | ✅ |
| Cloudflare Turnstile (widget and challenge page) | ✅ |

## Browser extensions

Prefer to solve captchas straight from your browser? Grab the extension:

[![Chrome Web Store](https://img.shields.io/badge/Chrome%20Web%20Store-Install-4285F4?logo=googlechrome&logoColor=white)](https://chromewebstore.google.com/detail/capskip-%E2%80%93-unlimited-captc/mgciphejglphomemchljofgoeakdfccl)
&nbsp;
[![Firefox Add-ons](https://img.shields.io/badge/Firefox%20Add--ons-Install-FF7139?logo=firefoxbrowser&logoColor=white)](https://addons.mozilla.org/en-US/firefox/addon/capskip-captcha-solver/)

## Official SDKs

First-party clients that wrap the CapSkip local API with clean, familiar methods:

| Language | Package | Source |
|---|---|---|
| **Python** | [![PyPI](https://img.shields.io/pypi/v/capskip?label=capskip&logo=pypi&logoColor=white)](https://pypi.org/project/capskip/) | [capskip-python](https://github.com/capskip/capskip-python) |
| **Node.js** | [![npm](https://img.shields.io/npm/v/capskip?label=capskip&logo=npm&logoColor=white)](https://www.npmjs.com/package/capskip) | [capskip-node](https://github.com/capskip/capskip-node) |
| **.NET** | [![NuGet](https://img.shields.io/nuget/v/CapSkip?label=CapSkip&logo=nuget&logoColor=white)](https://www.nuget.org/packages/CapSkip) | [capskip-dotnet](https://github.com/capskip/capskip-dotnet) |
| **PHP** | [![Packagist](https://img.shields.io/packagist/v/capskip/capskip?label=capskip%2Fcapskip&logo=packagist&logoColor=white)](https://packagist.org/packages/capskip/capskip) | [capskip-php](https://github.com/capskip/capskip-php) |

```python
# Python, solve a reCAPTCHA in a few lines
from capskip import CapSkip

solver = CapSkip(host="127.0.0.1", port=8080)
result = solver.recaptcha(sitekey="YOUR_SITEKEY", url="https://example.com")
print(result["code"])   # the g-recaptcha-response token
```

## Resources

- ⬇️ **Download for Windows**: [CapSkipInstaller.msi](https://capskip.com/download/CapSkipInstaller.msi)
- 📚 **API documentation**: [capskip.com/api-docs](https://capskip.com/api-docs/)
- 📬 **Support**: [support@capskip.com](mailto:support@capskip.com)

<div align="center">
<sub>Solve captchas locally, without limits.</sub>
</div>
