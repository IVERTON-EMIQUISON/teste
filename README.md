
## 📝 Sistema de Controle de Tarefas Online

Bem-vindo ao **Sistema de Controle de Tarefas Online**, uma aplicação web para o gerenciamento eficiente de atividades diárias. O sistema permite criar, editar, excluir e organizar tarefas com prazos e prioridades, além de arquivar automaticamente as concluídas.

## 🚀 Tecnologias Utilizadas
- **Backend:** Django + Django REST Framework
- **Frontend:** HTML, CSS, JavaScript
- **Banco de Dados:** SQLite (pode ser adaptado para PostgreSQL ou MySQL)
- **Autenticação:** Django Authentication
- **Estilização:** Bootstrap / TailwindCSS

## 📸 Demonstração
Coloque aqui prints da interface do sistema para ilustrar o funcionamento.

## 🛠️ Como Instalar e Executar
### 1️⃣ Clonar o Repositório
```bash
git clone https://github.com/seu-usuario/sistema-tarefas.git
cd sistema-tarefas
```
### 2️⃣ Criar e Ativar o Ambiente Virtual
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate    # Windows
```
### 3️⃣ Instalar Dependências
```bash
pip install -r requirements.txt
```
### 4️⃣ Aplicar Migrações e Criar um Superusuário
```bash
python manage.py migrate
python manage.py createsuperuser
```
### 5️⃣ Executar o Servidor
```bash
python manage.py runserver
```
Acesse **http://127.0.0.1:8000/** no navegador.

## 📌 Funcionalidades
✅ Criar, editar e excluir tarefas  
✅ Definir prazos e prioridades  
✅ Filtrar por status (pendente, em andamento, concluída)  
✅ Notificações de prazos próximos  
✅ Interface amigável e responsiva  

## 🎯 Como Contribuir
1. Faça um **fork** do projeto
2. Crie uma nova **branch** (`feature/nova-funcionalidade`)
3. Faça as modificações e **commite**
4. Envie um **pull request**

## 📜 Licença
Este projeto está licenciado sob a [MIT License](LICENSE).

💡 Desenvolvido por IVERTON EMIQUISON 🚀


