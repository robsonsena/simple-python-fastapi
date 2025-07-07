# simple-python-fastapi

1. **Crie um ambiente virtual:**
   ```sh
   python3 -m venv ./venv
   ```

2. **Ative o ambiente virtual:**
   - No Linux/Mac:
     ```sh
     source venv/bin/activate
     ```
   - No Windows, abra um terminal no modo administrador e execute o comando:
   ```sh
   Set-ExecutionPolicy RemoteSigned
   ```

     ```sh
     venv\Scripts\activate
     ```

3. **Instale as dependências:**
   ```sh
   pip install -r requirements.txt
   ```

4. **Execute a aplicação:**
   ```sh
   uvicorn app:app --reload
   ```

5. **Acesse a documentação interativa:**

   Abra o navegador e acesse: 
   [http://127.0.0.1:8000/docs](http://127.0.0.1:8000)

   Aqui você pode testar todos os endpoints da API .

---

## Estrutura do Projeto

- `app.py`: Arquivo principal da aplicação FastAPI.
- `models.py`: Modelos do banco de dados (SQLAlchemy).
- `requirements.txt`: Lista de dependências do projeto.
