# 🏥 Sistema para Clínica de Psiquiatria

Este é um projeto full stack desenvolvido com **Django** e **HTML/CSS**, criado para facilitar o gerenciamento de pacientes e consultas em uma clínica de psiquiatria.

## 🚀 Tecnologias Utilizadas

### Backend:
- 🐍 **Python** (Django para desenvolvimento web)
- 🗄️ **Django ORM** (interação com banco de dados)
- 🏛️ **Banco de Dados** (SQLite, MySQL ou PostgreSQL)

### Frontend:
- 🌐 **HTML5 & CSS3**
- 🎨 **TailwindCSS** (para estilização responsiva)

## 🎯 Funcionalidades Principais

- 🏥 **Cadastro de Pacientes**: Registre informações como nome, e-mail, telefone e motivo da consulta.
  
  ![projeto_clinica](https://github.com/user-attachments/assets/0c38a5e5-1f0b-4c2c-92d1-0196d9da3839)

- 📅 **Gerenciamento de Consultas**: Agendamento de consultas com anotações e observações.

- 🎥 **Disponibilização de Recursos**: Envio de links com vídeos e práticas recomendadas para os pacientes.
  

https://github.com/user-attachments/assets/866338fb-1918-4896-81eb-63ee296187fd


- 📱 **Interface Responsiva**: Design moderno e adaptável para diferentes dispositivos.

## 📌 Como Executar o Projeto

### 1️⃣ Clone o repositório:
```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio
```

### 2️⃣ Crie um ambiente virtual e ative-o:
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate  # Windows
```

### 3️⃣ Instale as dependências:
```bash
pip install -r requirements.txt
```

### 4️⃣ Configure o Banco de Dados e aplique as migrações:
```bash
python manage.py migrate
```

### 5️⃣ Execute o servidor:
```bash
python manage.py runserver
```

### 🔗 Acesse o sistema:
Abra o navegador e entre em `http://127.0.0.1:8000`

## 📂 Estrutura do Projeto

```
├── manage.py
├── backend
│   ├── settings.py
│   ├── urls.py
│   ├── models.py
│   ├── views.py
│   ├── templates/
│   │   ├── base.html
│   │   ├── pacientes.html
│   │   ├── paciente.html
│   │   ├── consulta_publica.html
│   ├── static/
│   │   ├── css/
│   │   ├── js/
│   ├── migrations/
│
├── README.md
├── requirements.txt
```

## 🔍 Diferenciais do Projeto

- 🏥 **Solução Especializada**: Focado no atendimento psiquiátrico e suporte ao paciente.
- 🔄 **Fácil Manutenção**: Estrutura modular que permite melhorias futuras.
- ⚡ **Alto Desempenho**: Utiliza Django e TailwindCSS para carregamento rápido e responsivo.

## 🤝 Contribuição

Sinta-se à vontade para contribuir com melhorias! Basta fazer um **fork** do repositório e enviar um **pull request**. 🚀

---
**👤 Autor:** Seu Nome  
**📧 Contato:** [Seu Email / LinkedIn / GitHub]



