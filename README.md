# 🌿 Planta Fácil – Enterprise Pack

O **Planta Fácil** é um marketplace inteligente de plantas com tecnologias modernas como **IA para diagnósticos**, **notificações em tempo real**, **painel administrativo**, **autenticação via Firebase** e **pagamento com Mercado Pago**.

---

## 🚀 Funcionalidades incluídas

### ✅ Público
- Visualização de produtos com AR/3D
- Diagnóstico de plantas com imagem + IA
- Sistema de login (email/senha + Google)
- Checkout com Mercado Pago

### 🧠 Backend
- Diagnóstico com IA (OpenAI Vision ou HuggingFace)
- API REST segura (Express + MongoDB)
- Email transacional via Nodemailer
- WebSocket (Socket.io) para notificações
- Sistema de estoque e gerenciamento

### 📊 Admin
- Painel com gráficos (Chart.js)
- Gestão de usuários e diagnósticos
- Upload de produtos e controle de estoque
- Firebase Claims para proteção de acesso

---

## 🛠️ Tecnologias Usadas

| Stack         | Descrição                        |
|---------------|----------------------------------|
| Frontend      | React + Vite + TailwindCSS       |
| Backend       | Node.js + Express + MongoDB      |
| Auth          | Firebase Authentication          |
| IA            | OpenAI GPT-4-Vision ou HuggingFace |
| Pagamento     | Mercado Pago Checkout Pro        |
| Notificações  | Socket.IO + Nodemailer           |
| Gráficos      | Chart.js                         |

---

## 📦 Instalação Local

### Backend
```bash
cd backend
cp .env.example .env
npm install
npm start
