- python3 -m venv venv
- source venv/bin/activate
- pip install -r requirements.txt
- cat > .env << EOF
  OPENAI_API_KEY=your-api-key
  EOF
- python app/server.py
