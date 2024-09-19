# in.orbit

**in.orbit** é a parte **frontend** de uma aplicação de gerenciamento de metas, desenvolvida em **React.js**, projetada para ajudar os usuários a definir, acompanhar e gerenciar suas metas semanais de forma intuitiva e visualmente atraente. O projeto permite adicionar e editar metas, acompanhar o progresso e visualizar as conquistas da semana.

## Funcionalidades

- Defina e gerencie metas para cada semana.
- Acompanhe o progresso visualmente com uma barra de progresso.
- Marque metas como concluídas e revise o histórico de metas completadas.
- Personalize quantas vezes uma meta deve ser repetida por semana.
- Interface responsiva construída com Tailwind CSS.
- Integração com validação de formulários utilizando Zod e React Hook Form.

## Tecnologias Utilizadas

Este projeto foi desenvolvido utilizando:

- **React.js (v18.3.1)**: Biblioteca JavaScript para construção de interfaces de usuário.
- **React Hook Form (v7.53.0)**: Biblioteca para manipulação de formulários de forma eficiente em React.
- **@tanstack/react-query (v5.56.2)**: Gerencia o estado do servidor e consultas assíncronas.
- **Day.js (v1.11.13)**: Biblioteca JavaScript leve para manipulação de datas.
- **Tailwind CSS (v3.4.11)**: Framework CSS de utilitários para construir rapidamente designs personalizados.
- **Zod (v3.23.8)**: Biblioteca de validação e declaração de esquemas orientada a TypeScript.
- **Radix UI**: Utilizada para componentes como Dialog, Progress e Radio Group.

## Instalação

Este projeto utiliza o Node.js. Para começar, certifique-se de ter o [Node.js](https://nodejs.org/) instalado.

### Passo a passo para instalar o projeto:

1. Clone o repositório:
    
    ```bash
    bash
    Copiar código
    git clone https://github.com/seu-usuario/in-orbit.git
    cd in-orbit
    
    ```
    
2. Instale as dependências usando o npm:
    
    ```bash
    bash
    Copiar código
    npm install
    
    ```
    
3. Execute o servidor de desenvolvimento:
    
    ```bash
    bash
    Copiar código
    npm run dev
    
    ```
    

A aplicação estará rodando em `http://localhost:3333`.

## Scripts Disponíveis

No diretório do projeto, você pode rodar:

### `npm run dev`

Executa a aplicação em modo de desenvolvimento.

### `npm run build`

Constrói a aplicação para produção.

### `npm run lint`

Executa o linter utilizando Biome para verificar a qualidade do código.

## Dependências

Abaixo estão as principais dependências do projeto com links para suas documentações:

| Dependência | Versão | Link |
| --- | --- | --- |
| `@hookform/resolvers` | ^3.9.0 | [Documentação](https://www.npmjs.com/package/@hookform/resolvers) |
| `@radix-ui/react-dialog` | ^1.1.1 | [Documentação](https://www.npmjs.com/package/@radix-ui/react-dialog) |
| `@radix-ui/react-progress` | ^1.1.0 | [Documentação](https://www.npmjs.com/package/@radix-ui/react-progress) |
| `@radix-ui/react-radio-group` | ^1.2.0 | [Documentação](https://www.npmjs.com/package/@radix-ui/react-radio-group) |
| `@tanstack/react-query` | ^5.56.2 | [Documentação](https://www.npmjs.com/package/@tanstack/react-query) |
| `dayjs` | ^1.11.13 | [Documentação](https://www.npmjs.com/package/dayjs) |
| `lucide-react` | ^0.441.0 | [Documentação](https://www.npmjs.com/package/lucide-react) |
| `react` | ^18.3.1 | [Documentação](https://react.dev/) |
| `react-dom` | ^18.3.1 | Documentação |
| `react-hook-form` | ^7.53.0 | [Documentação](https://www.react-hook-form.com/) |
| `tailwind-merge` | ^2.5.2 | [Documentação](https://www.npmjs.com/package/tailwind-merge) |
| `tailwind-variants` | ^0.2.1 | [Documentação](https://www.npmjs.com/package/tailwind-variants) |
| `zod` | ^3.23.8 | [Documentação](https://www.npmjs.com/package/zod) |

### Dependências de Desenvolvimento

| Dependência | Versão | Link |
| --- | --- | --- |
| `@biomejs/biome` | ^1.9.0 | [Documentação](https://www.npmjs.com/package/@biomejs/biome) |
| `@types/react` | ^18.3.3 | [Documentação](https://www.npmjs.com/package/@types/react) |
| `@types/react-dom` | ^18.3.0 | [Documentação](https://www.npmjs.com/package/@types/react-dom) |
| `@vitejs/plugin-react` | ^4.3.1 | [Documentação](https://www.npmjs.com/package/@vitejs/plugin-react) |
| `autoprefixer` | ^10.4.20 | [Documentação](https://www.npmjs.com/package/autoprefixer) |
| `postcss` | ^8.4.47 | [Documentação](https://www.npmjs.com/package/postcss) |
| `tailwindcss` | ^3.4.11 | [Documentação](https://www.npmjs.com/package/tailwindcss) |
| `typescript` | ^5.5.3 | [Documentação](https://www.npmjs.com/package/typescript) |
| `vite` | ^5.4.1 | [Documentação](https://www.npmjs.com/package/vite) |

## Contribuindo

Sinta-se à vontade para enviar issues ou pull requests para melhorias ou correções de bugs.

## Licença

Este projeto está licenciado sob a Licença MIT.
