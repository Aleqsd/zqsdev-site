# 🌐 zqsdev.com – Domain Redirection & CV Hosting

This repository powers the [zqsdev.com](https://zqsdev.com) domain and its subdomains using [Netlify](https://www.netlify.com/). It handles simple redirects and serves a hosted version of Alexandre DO O ALMEIDA's PDF CV.

[![Netlify Status](https://api.netlify.com/api/v1/badges/c51eac08-53e4-4951-a311-8491cb78a4b8/deploy-status)](https://app.netlify.com/sites/zqsdev/deploys)

---

## 🚀 Deployment

- ✅ Hosted on **Netlify** with continuous deployment from GitHub
- 🌐 Domain registered and managed via **Hostinger**
- 🔒 TLS certificates handled automatically by **Let's Encrypt** via Netlify DNS

---

## 🧭 Domains & Behavior

| Domain                                               | Behavior                                                       |
| ---------------------------------------------------- | -------------------------------------------------------------- |
| [`zqsdev.com`](https://zqsdev.com)                   | Redirects to [github.com/aleqsd](https://github.com/aleqsd)    |
| [`cv.zqsdev.com`](https://cv.zqsdev.com)             | Serves a CV viewer displaying the PDF (`cv/index.html`)        |
| [`calendly.zqsdev.com`](https://calendly.zqsdev.com) | Redirects to [Calendly](https://calendly.com/alexandre-zqsdev) |

---

## 📁 Project Structure

```txt
/
├── calendly/
│   └── index.html         # Redirect to Calendly
├── cv/
│   ├── index.html         # HTML page with iframe showing the PDF
│   └── CV_Alexandre_DO_O_ALMEIDA_2025.pdf
├── netlify.toml           # All Netlify redirect rules
```
