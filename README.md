# 💰 Meus Gastos

<div align="center">

![Logo Meus Gastos](public/favicon.ico)

Uma aplicação web moderna para controle de despesas pessoais, desenvolvida com as melhores tecnologias do mercado.

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![Supabase](https://img.shields.io/badge/Supabase-181818?style=for-the-badge&logo=supabase&logoColor=white)](https://supabase.com/)

</div>

## 🚀 Funcionalidades

- ✨ Interface moderna e responsiva
- 📊 Gráficos interativos para visualização de gastos
- 💾 Armazenamento seguro com Supabase
- 🔒 Autenticação robusta
- 📱 Design mobile-first

## 🛠️ Tecnologias

Este projeto foi desenvolvido com as seguintes tecnologias:

- [React](https://react.dev/) - Biblioteca JavaScript para construção de interfaces
- [TypeScript](https://www.typescriptlang.org/) - Superset JavaScript com tipagem estática
- [Vite](https://vitejs.dev/) - Build tool e dev server
- [Tailwind CSS](https://tailwindcss.com/) - Framework CSS utility-first
- [Radix UI](https://www.radix-ui.com/) - Biblioteca de componentes UI primitivos
- [React Query](https://tanstack.com/query/latest) - Gerenciamento de estado e cache
- [React Hook Form](https://react-hook-form.com/) - Gerenciamento de formulários
- [Supabase](https://supabase.com/) - Backend as a Service
- [React Router DOM](https://reactrouter.com/) - Roteamento
- [Zod](https://zod.dev/) - Validação de esquemas
- [Framer Motion](https://www.framer.com/motion/) - Animações
- [Recharts](https://recharts.org/) - Biblioteca de gráficos

## 📋 Pré-requisitos

Antes de começar, verifique se você tem os seguintes requisitos:

- Node.js (versão 18 ou superior)
- npm ou yarn
- Git

## 🚀 Instalação

1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/meus-gastos.git
```

2. Entre no diretório do projeto

```bash
cd meus-gastos
```

3. Instale as dependências

```bash
npm install
# ou
yarn
```

4. Configure as variáveis de ambiente

```bash
cp .env.example .env
```

Edite o arquivo `.env` com suas configurações:

```env
VITE_SUPABASE_URL=sua_url_do_supabase
VITE_SUPABASE_ANON_KEY=sua_chave_anonima_do_supabase
```

## 🎮 Usando

Para iniciar o servidor de desenvolvimento:

```bash
npm run dev
# ou
yarn dev
```

Para criar uma build de produção:

```bash
npm run build
# ou
yarn build
```

## 📁 Estrutura do Projeto

```
src/
├── assets/      # Arquivos estáticos (imagens, fontes, etc)
├── components/  # Componentes React reutilizáveis
│   ├── ui/     # Componentes de interface básicos
│   └── forms/  # Componentes de formulário
├── contexts/    # Contextos React
├── hooks/      # Hooks personalizados
├── lib/        # Configurações e utilitários
│   ├── supabase.ts  # Configuração do Supabase
│   └── utils.ts     # Funções utilitárias
├── pages/      # Componentes de página
└── types/      # Definições de tipos TypeScript
```

## 🤝 Contribuindo

Contribuições são sempre bem-vindas! Para contribuir:

1. Fork o projeto
2. Crie uma branch para sua feature

```bash
git checkout -b feature/NomeFantastico
```

3. Commit suas mudanças

```bash
git commit -m 'feat: Adicionando um recurso fantástico'
```

4. Push para a branch

```bash
git push origin feature/NomeFantastico
```

5. Abra um Pull Request

## 📝 Convenções de Commit

Seguimos o padrão [Conventional Commits](https://www.conventionalcommits.org/):

- `feat`: Nova funcionalidade
- `fix`: Correção de bug
- `docs`: Alteração em documentação
- `style`: Alterações que não afetam o código
- `refactor`: Refatoração de código
- `test`: Adição ou modificação de testes
- `chore`: Alterações em arquivos de build

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 📧 Contato

Se você tiver alguma dúvida ou sugestão, por favor:

- Abra uma issue no GitHub
- Entre em contato através do email: pedropaulobrasca@gmail.com

---

<div align="center">
Feito com ❤️ por Pedro Brasca
</div>
