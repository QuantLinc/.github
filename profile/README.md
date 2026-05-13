<div align="center">

# Quantl

**ML pipeline + trading platform. Built for finance, not against it.**

End-to-end quant: data collection, model training, signal generation, position monitoring.

[**🌐 quantl.click**](https://quantl.click)&nbsp;&nbsp;·&nbsp;&nbsp;[**🏠 GitHat platform**](https://githat.io)

</div>

---

## What Quantl is

A trading + research platform on the [GitHat](https://githat.io) platform. ML pipeline + FastAPI backend + Next.js frontend running on a single AWS box with real production load.

- **ML pipeline** — continuous data collection + model training
- **Signal generation** — alpha + risk scoring on equities and crypto
- **Position monitor** — live PnL, risk exposure, paper-trade mode
- **WebSockets** for streaming quotes + signals
- **Subscriptions** via [Sebastn](https://github.com/SebasTN-Rhys)
- **Auth** by [GitHat](https://github.com/GitHat-IO)

## Stack

- Backend: Python (FastAPI), PostgreSQL, AWS S3 model storage
- Frontend: Next.js standalone
- Edge: Route 53 → CloudFront (ACM) → EC2

## Security

- ✅ Verified domain (`quantl.click`, `www.quantl.click`)
- ✅ AWS-native edge with ACM certs
- ✅ Same-origin auth proxy + httpOnly cookies
- ✅ Models stored in versioned S3 with KMS encryption
- ✅ CAA records, signed commits

## Contact

Security: [security@quantl.click](mailto:security@quantl.click)
Support: [hello@quantl.click](mailto:hello@quantl.click)
