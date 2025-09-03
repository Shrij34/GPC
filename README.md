# GPC
Gold price calculator
Absolutely, Shrinivas! Here's a polished `README.md` tailored for your jewellery price calculator app — Dockerized, DevOps-ready, and beginner-friendly:

---

A lightweight Python + Tkinter desktop app to calculate the price of gold jewellery based on carat, weight, making charges, wastage, and GST. Ideal for jewellers, buyers, and enthusiasts who want a transparent cost breakdown.

---

### 🖥️ Features

- ✅ Real-time price calculation based on user inputs  
- ✅ Clean GUI built with Tkinter  
- ✅ Input validation for numeric fields  
- ✅ Detailed cost breakdown including purity, wastage, making charges, and GST  
- ✅ Export-ready for web or container deployment  

---

### 📦 Requirements

- Python 3.10+
- `tkinter` (included in standard Python)
- `Docker` (for containerized deployment)

---

### 🚀 Run Locally

```bash
python app.py
```

> Make sure you have Python installed and `tkinter` available.

---

### 🐳 Run with Docker

```bash
docker build -t jewellery-app .
docker run -p 5000:5000 jewellery-app
```

> If you're using a GUI-based app inside Docker, consider using `xhost` or `VNC` for display forwarding (Linux/macOS). For web conversion, see Flask version below.

---

### 🌐 Web Version (Optional)

To deploy as a web app, convert the logic to Flask:

```python
from flask import Flask, request, render_template
# Wrap your calculation logic in a route
```

Then containerize and deploy to Azure using DevOps pipelines.

---

### 🧪 Sample Inputs

| Field             | Example Value |
|------------------|---------------|
| Gold Rate        | ₹6000         |
| Carat            | 22            |
| Weight           | 10 grams      |
| Making Charges   | 10%           |
| Wastage          | 5%            |
| GST              | 3%            |

---

### 📋 Jeweller Checklist (Included in App)

- What is today’s gold rate?
- Is this BIS Hallmarked gold?
- What is the purity and carat?
- What is the making charge?
- Any wastage charges applied?
- Is 3% GST included?
- Can I see hallmark/certificate?
- What is the resale/exchange policy?
- Do you offer discounts?

---

### 🛠 DevOps Ready

- Multi-stage Dockerfile with distroless optimization
- Azure DevOps pipeline YAML available
- Container registry + AKS/Web App deployment supported

---

### 📄 License

MIT — free to use, modify, and share.

---

Let me know if you want to include screenshots, badges (build status, Docker pulls), or a link to your Azure deployment. I can help you make this README sparkle like a well-cut diamond.
