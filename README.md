# AI-Powered Finance Software (v1.0-beta)

This is a smart finance web app for managing ledgers, trial balances, invoices, and transaction classification using AI and OCR.

## 🚀 Features
- Upload bank statements and invoices (JPG/PNG)
- AI-powered classification using GPT
- OCR invoice text extraction
- Trial Balance generation
- Supabase login and file storage
- Streamlit dashboard interface

## 📦 Setup

```bash
pip install -r requirements.txt
streamlit run ui/dashboard.py
```

Add your credentials to `.env`:
```
SUPABASE_URL=https://your-project.supabase.co
SUPABASE_KEY=your-service-role-key
OPENAI_API_KEY=sk-xxx
```

## 📤 Deployment
Deploy to [Streamlit Cloud](https://streamlit.io/cloud) with:
- Python 3.9+
- `requirements.txt`
- `.streamlit/config.toml`

## 📊 Next Steps
- Add manual journal entry UI
- Export reports to PDF/Excel
- Add AI explanations for entries
- SARS VAT201 and iXBRL support

Enjoy building the future of finance!