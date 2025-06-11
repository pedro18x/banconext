


Projeto Banco Horizon - Projeto feito com um vídeo no [Youtube](https://www.youtube.com/watch?v=PuOVqP_cjkE&t=7013s). Utiliza Node.js, Next.js, TypeScript, TailwindCSS e Appwrite.

## 🤸 **Início Rápido**

Siga estes passos para configurar o projeto localmente na sua máquina.

### **Pré-requisitos**

Certifique-se de que você tenha os seguintes programas instalados em sua máquina:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

### **Clonando o Repositório**

```bash
git clone https://github.com/pedro18x/banconext
cd banconext
```

### **Instalação**

Instale as dependências do projeto usando o npm:

```bash
npm install
```

### **Configurar Variáveis de Ambiente**

Crie um novo arquivo chamado `.env` na raiz do seu projeto e adicione o seguinte conteúdo:

```env
#NEXT
NEXT_PUBLIC_SITE_URL=

#APPWRITE
NEXT_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
NEXT_PUBLIC_APPWRITE_PROJECT=
APPWRITE_DATABASE_ID=
APPWRITE_USER_COLLECTION_ID=
APPWRITE_BANK_COLLECTION_ID=
APPWRITE_TRANSACTION_COLLECTION_ID=
APPWRITE_SECRET=

#PLAID
PLAID_CLIENT_ID=
PLAID_SECRET=
PLAID_ENV=
PLAID_PRODUCTS=
PLAID_COUNTRY_CODES=

#DWOLLA
DWOLLA_KEY=
DWOLLA_SECRET=
DWOLLA_BASE_URL=https://api-sandbox.dwolla.com
DWOLLA_ENV=sandbox
```

Substitua os valores de espaço reservado (placeholders) pelas credenciais reais de suas contas. Você pode obter essas credenciais criando uma conta em [Appwrite](https://appwrite.io/?utm_source=youtube&utm_content=reactnative&ref=JSmastery), [Plaid](https://plaid.com/) e [Dwolla](https://www.dwolla.com/).

### **Executando o Projeto**

```bash
npm run dev
```

Abra [http://localhost:3000](http://localhost:3000) no seu navegador para visualizar o projeto.


