# ☁️ Backup Multi-Cloud

[![Status](https://img.shields.io/badge/Status-🚧%20Em%20Desenvolvimento-yellow)]()
[![React](https://img.shields.io/badge/React-18-blue)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-5-purple)](https://vitejs.dev/)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3-cyan)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> Sistema de backup automático para AWS S3 e Google Cloud Storage com interface moderna.

---

## ✨ Features

### 🎨 **Interface Moderna**
- Dark theme com cores neon (cyan/purple)
- Glassmorphism cards com backdrop blur
- Layout responsivo mobile-first
- Animações suaves com Framer Motion
- Ícones modernos com Lucide React

### 📊 **Dashboard**
- Status dos provedores cloud em tempo real
- Métricas de storage e backups
- Gráficos de uso
- Lista de backups recentes

### ⚙️ **Configuração**
- Credenciais AWS S3 e Google Cloud
- Agendamento de backups
- Fontes de dados (bancos, arquivos)
- Sistema de logs com filtros

### 🔐 **Segurança** (Planejado)
- Criptografia AES-256
- Gerenciamento seguro de credenciais
- Verificação de checksums
- Upload paralelo para múltiplos clouds

---

## 🛠️ Tech Stack

### **Frontend**
- **React 18** - Framework UI
- **Vite 5** - Build tool
- **TailwindCSS 3** - Utility-first CSS
- **Framer Motion** - Animações
- **Lucide React** - Ícones

### **Backend** (Planejado)
- **Python 3.11** - Scripts de backup
- **AWS SDK (boto3)** - Integração S3
- **Google Cloud SDK** - Integração GCS
- **Cron** - Agendamento

---

## 🚀 Quick Start

### **Pré-requisitos**
- Node.js 18+
- npm ou yarn

### **1. Clone o repositório**
```bash
git clone https://github.com/Sergio-Sena/backup-multicloud.git
cd backup-multicloud
```

### **2. Instale as dependências**
```bash
npm install
```

### **3. Execute em desenvolvimento**
```bash
npm run dev
```

Acesse: http://localhost:3000

### **4. Build de produção**
```bash
npm run build
npm run preview
```

---

## 📁 Estrutura do Projeto

```
backup-multicloud/
├── src/
│   ├── components/
│   │   ├── Dashboard.jsx      # Painel principal
│   │   ├── BackupConfig.jsx   # Configuração de backup
│   │   ├── CloudSettings.jsx  # Configurações cloud
│   │   └── Logs.jsx           # Sistema de logs
│   ├── App.jsx                # Componente principal
│   ├── main.jsx               # Entry point
│   └── index.css              # Estilos globais
├── scripts/                   # Scripts Python (próxima fase)
├── public/                    # Assets estáticos
├── vite.config.js             # Config Vite
├── tailwind.config.js         # Config Tailwind
└── package.json
```

---

## 🎯 Funcionalidades

### ✅ **Implementado**
- [x] Interface moderna e responsiva
- [x] Dashboard com métricas visuais
- [x] Navegação entre páginas
- [x] Componentes de configuração
- [x] Sistema de logs com filtros
- [x] Design system completo

### 🔄 **Em Desenvolvimento**
- [ ] Integração com AWS S3
- [ ] Integração com Google Cloud Storage
- [ ] Scripts Python de backup
- [ ] Sistema de agendamento
- [ ] Criptografia de dados
- [ ] Notificações desktop

---

## 🎨 Design System

### **Cores**
- Background: `#0f0f23` (dark-bg)
- Cards: `rgba(255,255,255,0.1)` (glass effect)
- Neon Cyan: `#00ffff`
- Neon Purple: `#8b5cf6`

### **Componentes**
- `.glass-card` - Cards com glassmorphism
- `.neon-button` - Botões com gradiente neon
- `.cloud-status` - Status dos provedores

---

## 🗺️ Roadmap

### **Fase 2: Backend Integration** (5 dias)
- [ ] Scripts Python para AWS S3
- [ ] Scripts Python para Google Cloud
- [ ] Compressão e criptografia
- [ ] API local para comunicação

### **Fase 3: Advanced Features** (3 dias)
- [ ] Agendamento com cron jobs
- [ ] Interface de agendamento visual
- [ ] Retenção automática de backups
- [ ] Verificação de integridade

### **Fase 4: Desktop App** (2 dias)
- [ ] Conversão para Tauri
- [ ] Notificações do sistema
- [ ] Auto-updater
- [ ] Executável Windows

---

## 🔧 Scripts Disponíveis

```bash
npm run dev      # Servidor de desenvolvimento
npm run build    # Build de produção
npm run preview  # Preview do build
```

---

## 📝 Configuração (Planejado)

### **AWS S3**
```env
AWS_ACCESS_KEY_ID=your_key
AWS_SECRET_ACCESS_KEY=your_secret
AWS_REGION=us-east-1
S3_BUCKET=your-bucket
```

### **Google Cloud Storage**
```env
GCP_PROJECT_ID=your_project
GCP_CREDENTIALS_PATH=/path/to/credentials.json
GCS_BUCKET=your-bucket
```

---

## 🤝 Contribuição

1. Fork o projeto
2. Crie uma branch (`git checkout -b feature/nova-funcionalidade`)
3. Commit suas mudanças (`git commit -m 'feat: nova funcionalidade'`)
4. Push para a branch (`git push origin feature/nova-funcionalidade`)
5. Abra um Pull Request

---

## 📄 Licença

MIT License - veja [LICENSE](LICENSE) para detalhes.

---

## 👨💻 Autor

**Sergio Sena**
- GitHub: [@Sergio-Sena](https://github.com/Sergio-Sena)
- LinkedIn: [Sergio Sena](https://linkedin.com/in/sergio-sena)
- Portfolio: [dev-cloud.sstechnologies-cloud.com](https://dev-cloud.sstechnologies-cloud.com)

---

<div align="center">

**⭐ Se este projeto foi útil, deixe uma estrela!**

[🐛 Issues](../../issues) • [📖 Docs](docs/)

</div>
