# Guia do Mochileiro Universitário (Monorepo)

Bem-vindo ao repositório oficial do **Guia do Mochileiro Universitário**, um projeto dedicado a melhorar a experiência dos estudantes da Escola Politécnica de Pernambuco (POLI-UPE).

## 📂 Estrutura do Projeto

Este repositório está organizado como um monorepo contendo tanto o back-end quanto o front-end da aplicação.

```
Guia_Mochileiro_Universitario/
├── backend/            # API e lógica do servidor (Django)
├── frontend/           # Interface do usuário (React + Vite)
└── README.md           # Este arquivo
```

## 🚀 Módulos

### [Frontend (Mochileiro)](./frontend/mochileiro)
A interface web moderna e interativa onde os alunos navegam pelo mapa 3D, consultam horários e eventos.

- **Tecnologias**: React, TypeScript, Vite, TailwindCSS.
- **Destaque**: Integração com POLIMAP (Mapa 3D).
- **Como rodar**:
  ```bash
  cd frontend/mochileiro
  npm install
  npm run dev
  ```

### [Backend](./backend)
A API robusta que gerencia dados de usuários, eventos, horários e locais.

- **Tecnologias**: Django (Python), Django REST Framework.
- **Banco de Dados**: PostgreSQL (recomendado para produção).

## 🤝 Como Contribuir

1.  Faça um fork do projeto.
2.  Crie uma branch para sua feature (`git checkout -b feature/MinhaFeature`).
3.  Commit suas mudanças (`git commit -m 'Adiciona MinhaFeature'`).
4.  Faça o push para a branch (`git push origin feature/MinhaFeature`).
5.  Abra um Pull Request.

## 👥 Autores

Este projeto é mantido por um grupo dedicado de estudantes da UPE.

- Arthur Marcelino
- José Alves
- José Mario da Silva
- Laís Oliveira
- Pedro Henrique França
- Vinícius Moura

---
*Construindo o futuro da POLI, linha por linha.* 🚀
