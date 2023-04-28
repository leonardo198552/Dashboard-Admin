## Instruções Para Rodar

Automatize tarefas demoradas ou repetitivas em seu fluxo de trabalho de desenvolvimento usando Gulp 🥤

> Observe que o uso de Node, Webpack e Gulp e suas configurações avançadas são totalmente opcionais. Você pode usar e personalizar o modelo sem usá-los também.

Instalar o Node & Gulp e executá-lo é super fácil no Sneat, siga estas etapas e você estará pronto para arrasar 🤘

1. Em primeiro lugar, verifique se você instalou o [Node](https://nodejs.org/en/) (LTS). Se o Node.js já estiver instalado em seu sistema, verifique se a versão instalada é `LTS` e pule para a etapa 2

2. Instale o Gulp CLI: Abra Terminal/Prompt de Comando e execute o seguinte comando e aguarde até que ele termine. Se você já instalou o Gulp CLI, pode pular esta etapa e pular para a etapa 3.

```bash
npm install --global gulp-cli
```

3. Navegue até o diretório raiz do Sneat e execute o seguinte comando para instalar nossas dependências locais listadas em `package.json`. Você pode usar `npm` OU `yarn` conforme sua preferência.

> Recomenda-se o uso de yarn

```bash
# Para npm
npm install --legacy-peer-deps

# Para Yarn
yarn
```

4. Agora, você está pronto para executar as tarefas `npm`, o comando abaixo iniciará o servidor e observará o código usando [browsersync](https://browsersync.io/). Abra [http://localhost:3000/](http://localhost:3000/) para verificar seu desenvolvimento 🚀.

```bash
#npm
serviço de execução npm

# yarn
 yarn server
```

## Tarefas disponíveis 🧑‍💻

Abra o console/terminal, vá para o diretório raiz do Sneat e execute `npm run {task_name}`. Ou seja, para gerar a compilação, execute `npm run build`.

Execute uma tarefa com o ambiente especificado (desenvolvimento/produção) apenas execute a tarefa com a opção `--env={environment}`, ou seja, `npm run build --env=production`.

> **Dica:** Use o comando `npm run` para listar todas as tarefas npm predefinidas do arquivo `package.json`.

## O que está incluso 📦

- Painel
- Disposições
   - Sem cardápio
   - Sem barra de navegação
   - Recipiente
   - Fluido
   - Em branco
- Páginas
   - Configurações de Conta
   - Conecte-se
   - Registro
   - Esqueceu sua senha
   - Erro
   - Em manutenção
- Cartões
- Interface de usuário
   - **Todos os componentes do Bootstrap**
- IU estendida
   - Barra de rolagem perfeita
   - Divisor de texto
- Boxicon
- Elementos de formulário
   - Entradas básicas
   - Grupos de entrada
- Esquema do formulário
   - Forma Vertical
   - Forma Horizontal
- Tabelas

## Redes Sociais 🌍

- Twitter: [https://twitter.com/leoandrade1012](https://twitter.com/leoandrade1012)
- Instagram: [https://www.instagram.com/leonardojunioandrade/](https://www.instagram.com/leonardojunioandrade)