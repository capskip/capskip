<div align="center">

# CapSkip

### Desktop AI captcha solver — high accuracy, low latency, flat-rate pricing

Solve captchas **locally** on your own machine. No cloud middleman, no per-solve fees.

[**🌐 Website**](https://capskip.com) &nbsp;·&nbsp; [**📚 API Docs**](https://capskip.com/api-docs/) &nbsp;·&nbsp; [**⬇️ Download**](https://capskip.com)

</div>

---

## What is CapSkip?

**[CapSkip](https://capskip.com)** is a desktop application that solves captchas **locally** on your own computer. It runs in the background and exposes a standard captcha-solver HTTP API (the familiar `in.php` / `res.php` endpoints), so your scripts, bots, and apps can solve captchas through one simple local endpoint.

- 🖥️ **Runs locally** — captchas are solved on your machine, not a remote service
- 🎯 **High accuracy, low latency** — AI-powered solving tuned for speed
- 💸 **Flat-rate pricing** — no per-solve API fees beyond your license
- 🔌 **Drop-in HTTP API** — standard `in.php` / `res.php` endpoints
- 📦 **Official SDKs** for Python, Node.js, .NET, and PHP

👉 **Get CapSkip at [capskip.com](https://capskip.com)**

## What it solves

| Captcha type | Supported |
|---|:---:|
| Image CAPTCHA (distorted text) | ✅ |
| reCAPTCHA v2 — checkbox, invisible, enterprise | ✅ |
| reCAPTCHA v3 | ✅ |
| Cloudflare Turnstile — widget & challenge page | ✅ |

## Official SDKs

First-party clients that wrap the CapSkip local API with clean, familiar methods:

| Language | Package | Source |
|---|---|---|
| **Python** | [![PyPI](https://img.shields.io/pypi/v/capskip?label=capskip&logo=pypi&logoColor=white)](https://pypi.org/project/capskip/) | [capskip-python](https://github.com/capskip/capskip-python) |
| **Node.js** | [![npm](https://img.shields.io/npm/v/capskip?label=capskip&logo=npm&logoColor=white)](https://www.npmjs.com/package/capskip) | [capskip-node](https://github.com/capskip/capskip-node) |
| **.NET** | [![NuGet](https://img.shields.io/nuget/v/CapSkip?label=CapSkip&logo=nuget&logoColor=white)](https://www.nuget.org/packages/CapSkip) | [capskip-dotnet](https://github.com/capskip/capskip-dotnet) |
| **PHP** | [![Packagist](https://img.shields.io/packagist/v/capskip/capskip?label=capskip%2Fcapskip&logo=packagist&logoColor=white)](https://packagist.org/packages/capskip/capskip) | [capskip-php](https://github.com/capskip/capskip-php) |

```python
# Python — solve a reCAPTCHA in a few lines
from capskip import CapSkip

solver = CapSkip(host="127.0.0.1", port=8080)
result = solver.recaptcha(sitekey="YOUR_SITEKEY", url="https://example.com")
print(result["code"])   # the g-recaptcha-response token
```

## Resources

- 🌐 **Website** — [capskip.com](https://capskip.com)
- 📚 **API documentation** — [capskip.com/api-docs](https://capskip.com/api-docs/)
- 📬 **Support** — [support@capskip.com](mailto:support@capskip.com)

<div align="center">
<sub>Solve captchas locally, on your terms. — <a href="https://capskip.com">capskip.com</a></sub>
</div>
