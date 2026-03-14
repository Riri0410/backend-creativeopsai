# CreativeOps AI — Backend (Render)

Autonomous brief-to-proposal agent pipeline.

## Deployment on Render
1. Create a **New Web Service**.
2. Connect this repository.
3. **Environment**: Python
4. **Build Command**: `pip install -r requirements.txt`
5. **Start Command**: `uvicorn main:app --host 0.0.0.0 --port $PORT`
6. **Environment Variables**:
   - `OPENAI_API_KEY`: Your key
   - `TAVILY_API_KEY`: Your key
   - `SMTP_HOST`: e.g., smtp.gmail.com
   - `SMTP_USER`: your email
   - `SMTP_PASSWORD`: app password
