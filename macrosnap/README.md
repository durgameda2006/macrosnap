# 🥗 MacroSnap

A Streamlit chat app: enter your name and WhatsApp number once, chat with an AI nutrition buddy
(text or meal photo) powered by Gemini, and send a full summary to WhatsApp via Twilio.

## Setup
1. `python -m venv venv` and activate it
2. `pip install -r requirements.txt`
3. Copy `.streamlit/secrets.toml.example` to `.streamlit/secrets.toml` and fill in your keys
   (Gemini API key, Twilio SID/token, WhatsApp sandbox number, Content SID)
4. Join the Twilio WhatsApp sandbox from your phone (re-join after ~72h of inactivity)

## Run
`streamlit run app.py`

## Deploy
Push to GitHub (never commit `secrets.toml`), then create an app on share.streamlit.io and paste
your secrets in Settings → Secrets.
