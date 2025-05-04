# Projeto Firebase Hosting + GitHub Actions

## 🔧 Instalação
```bash
npm install
```

## 🚀 Executar local
```bash
npm start
```

## 📦 Build e Deploy manual
```bash
npm run build
firebase deploy
```

## 🔁 CI/CD via GitHub Actions
1. Configure o segredo `FIREBASE_SERVICE_ACCOUNT` no GitHub com a chave JSON da conta de serviço
2. Push para a branch `main` dispara o deploy automático

## 📚 Rollback
```bash
firebase hosting:versions:list
firebase hosting:clone seu-projeto:live@VERSAO seu-projeto:live
```

## 🔍 Logs
Acesse o Google Cloud → Logging → Filtro por `firebase_hosting`
