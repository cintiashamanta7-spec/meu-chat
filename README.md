# Chat LLM

Aplicativo de chat em Flask integrado à API da Groq.

## Executar no Windows (PowerShell)

1. Crie e ative o ambiente virtual:

   ```powershell
   python -m venv .venv
   .\.venv\Scripts\Activate.ps1
   ```

2. Instale as dependências:

   ```powershell
   pip install -r requirements.txt
   ```

3. Crie o arquivo local de configuração e edite-o com uma chave nova da Groq:

   ```powershell
   Copy-Item .env.example .env
   notepad .env
   ```

4. Inicie o servidor:

   ```powershell
   python app.py
   ```

Abra `http://127.0.0.1:5000` no navegador. Não compartilhe nem envie o arquivo
`.env`; ele está excluído do Git.
