# 📌 Lembretes da Empresa – Aplicativo Desktop (Python + Tkinter + MongoDB)

Aplicativo desktop para gestão de lembretes da empresa, com:

- Login por usuário
- Perfil de **administrador** (criação de usuários)
- Lembretes com **data e hora**
- **Alarme sonoro** no horário do lembrete
- Banco de dados em **MongoDB** (visualizável pelo MongoDB Compass, se desejado)

O foco é uso interno em ambiente corporativo: cada colaborador faz login no seu computador e recebe avisos precisos no horário configurado.

---

## 🧱 Tecnologias utilizadas

- **Python** (Tkinter para interface gráfica)
- **MongoDB** como banco de dados
- **pymongo** – driver do MongoDB para Python
- **werkzeug** – para hash de senha
- **winsound** – para tocar áudio/alarme no Windows (não precisa instalar)

---

## 📂 Estrutura básica do projeto

```text
lembretes_desktop_mongo/
├── main.py         # Aplicativo desktop (ponto de entrada)
├── alarm.wav       # Som do alarme (opcional, formato WAV)
└── README.md
