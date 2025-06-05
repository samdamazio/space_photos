# 📸 space_photos

**Clone do projeto Alura Space** desenvolvido para fins de aprendizado e prática com o framework Django.

## 🚀 Sobre o Projeto

Este projeto é uma reprodução do Alura Space, adaptado para estudo e aprimoramento das habilidades em desenvolvimento web utilizando Django.

## 🛠️ Tecnologias Utilizadas

- Python  
- Django  
- HTML  
- CSS  
- JavaScript  

## 📁 Estrutura do Projeto

- `apps/` – Aplicações Django do projeto  
- `scripts/` – Scripts auxiliares para automação e suporte  
- `setup/` – Configurações iniciais e arquivos de instalação  
- `static/` – Arquivos estáticos como CSS, JS e imagens  
- `templates/` – Templates HTML utilizados nas views  
- `manage.py` – Utilitário de linha de comando do Django  
- `requirements.txt` – Lista de dependências do projeto  

## ⚙️ Como Executar o Projeto

1. Clone o repositório:

   ```bash
   git clone https://github.com/samdamazio/space_photos.git
   cd space_photos
   ```

2. Crie e ative um ambiente virtual:

   ```bash
   python -m venv venv
   source venv/bin/activate  # No Windows use `venv\Scripts\activate`
   ```

3. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

4. Execute as migrações:

   ```bash
   python manage.py migrate
   ```

5. Inicie o servidor de desenvolvimento:

   ```bash
   python manage.py runserver
   ```

6. Acesse o projeto em: [http://localhost:8000](http://localhost:8000)

## 📌 Observações

Este projeto é destinado exclusivamente para fins educacionais e não deve ser utilizado em ambientes de produção.
