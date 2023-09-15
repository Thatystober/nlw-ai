# nlw-ia
![Wallpaper](./wallpaper.png)
Projeto desenvolvido durante a NLW de IA, focado em explorar a API da OpenAI.

## 🚀 Aprendizados

### 📚 Aula 01
- **Tailwind CSS**
  - `leading-relaxed`, `sr-only`, `aspect-video`: Novas classes que ajudam no design responsivo.
  - 🎨 Opacidade de cores: Como ajustar a opacidade usando classes do Tailwind.
- **Componentes Tailwind**
  - 🛠 [UI Shadcn](https://ui.shadcn.com/): Biblioteca que permite importar componentes diretamente para o projeto, facilitando a manutenção.
- **Gerenciador de Pacotes**
  - 📦 pnpm: Descoberta deste gerenciador de pacotes como uma alternativa eficiente ao npm e yarn.
    - **Eficiência de Espaço em Disco**: O pnpm mantém uma única cópia dos arquivos de pacote no disco, o que economiza espaço.
    - **Links Rígidos**: Utiliza links rígidos entre os pacotes, o que acelera o processo de instalação.
    - **Isolamento de Dependências**: Cada pacote tem seu próprio `node_modules`, o que evita conflitos de versão.
    - **Velocidade**: Geralmente mais rápido para instalar pacotes devido ao uso eficiente do cache e do paralelismo.


### 🛠 Aula 02
- **Fastify**
  - 🚀 Utilizado como alternativa ao Express para melhor performance.
- **Ferramentas de Requisição**
  - 🌐 HTTPie, Rest Client Extension: Ferramentas para gerenciar e testar requisições HTTP.
- **Prisma**
  - 🗃 Controle total do banco de dados, integração completa com TypeScript (ele até exibe as colunas do banco e seus tipos no código) e ferramenta nativa para gerenciamento.
- **ZOD**
  - 🛡 Uma das melhores bibliotecas para validação de dados em TypeScript.
- **OpenAI API**
  - 🤖 Primeira experiência com a API da OpenAI, explorando suas funcionalidades e integrações.

### 🎓 Aula 03
- **Tailwind CSS**
  - 📐 `inset-0`: Propriedade que seta `left`, `top`, `right`, `bottom` para 0.
- **FFmpeg Web Assembly**
  - 🎞 Introdução ao uso de FFmpeg em Web Assembly para manipulação de mídia.
- **Pacote AI da Vercel**
  - 🤖 Exploração do pacote AI fornecido pela Vercel, abrindo novas possibilidades para projetos de IA.


### 📦 Como Rodar

O projeto é dividido em duas partes: `API` e `Web`. Siga as instruções abaixo para rodar cada uma delas:

#### 🛠️ API

1. **Instalar Dependências**
    ```bash
    pnpm i
    ```

2. **Configurar Banco de Dados**
    ```bash
    pnpm prisma migrate dev
    ```
    Este comando irá criar todas as tabelas e relações no banco SQLite.

3. **Configurar Variáveis de Ambiente**
    - Preencha o arquivo `.env` com as variáveis necessárias.

4. **Iniciar o Projeto**
    ```bash
    pnpm dev
    ```

#### 🌐 Web

1. **Instalar Dependências**
    ```bash
    pnpm i
    ```

2. **Iniciar o Projeto**
    ```bash
    pnpm dev
    ```

> **Nota**: Você pode utilizar outros gerenciadores de pacotes como `npm` ou `yarn` no lugar do `pnpm`, se preferir.
