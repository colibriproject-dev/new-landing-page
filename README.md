# Landing Page Beija-Flor 🦜

Uma landing page moderna e responsiva criada com Vue 3 e Vuetify 3, replicando fielmente o design fornecido. O projeto apresenta o SDK em Golang "Beija-Flor" para desenvolvimento de aplicações.

## 🚀 Tecnologias Utilizadas

- **Vue 3** - Framework JavaScript progressivo
- **Vuetify 3** - Framework de componentes Material Design
- **Vite** - Build tool rápido e moderno
- **JavaScript** - Linguagem de programação
- **SVG** - Gráficos vetoriais escaláveis para ícones e ilustrações

## 📋 Pré-requisitos

Certifique-se de ter instalado em sua máquina:

- [Node.js](https://nodejs.org/) (versão 16 ou superior)
- [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/)

## 🛠️ Instalação

1. **Clone o repositório ou extraia o arquivo ZIP:**
   ```bash
   git clone <url-do-repositorio>
   cd landing-page-colibri
   ```

2. **Instale as dependências:**
   ```bash
   npm install
   ```
   ou
   ```bash
   yarn install
   ```

## 🎯 Executando o Projeto

### Ambiente de Desenvolvimento

Para executar o projeto em modo de desenvolvimento:

```bash
npm run dev
```
ou
```bash
yarn dev
```

O projeto estará disponível em: `http://localhost:5173`

### Build para Produção

Para criar uma versão otimizada para produção:

```bash
npm run build
```
ou
```bash
yarn build
```

### Preview da Build de Produção

Para visualizar a build de produção localmente:

```bash
npm run preview
```
ou
```bash
yarn preview
```

## 📱 Funcionalidades

### ✅ Seções Implementadas

- **Header** - Navegação com logo e botão de contato
- **Hero Section** - Apresentação principal com ilustração SVG
- **Características** - 6 recursos principais do SDK
- **5 Motivos** - Argumentos para escolher o SDK em Golang
- **Comunidade** - Chamada para participação
- **Planos** - Comparação entre plano gratuito e avançado
- **Propósito** - Missão, visão e valores
- **Contato** - Formulário de contato com ilustração
- **Footer** - Informações finais e logo

### 🎨 Recursos Visuais

- **Design Responsivo** - Adapta-se a diferentes tamanhos de tela
- **Ícones SVG Customizados** - Todos os ícones criados em SVG
- **Ilustrações Originais** - Ilustrações SVG para hero, propósito e contato
- **Animações Suaves** - Transições e hover effects
- **Cores Consistentes** - Paleta de cores profissional

## 🎨 Estrutura de Cores

```css
Primary: #3B4A6B (Azul escuro)
Secondary: #5E72E4 (Azul médio)
Accent: #11CDEF (Ciano)
Success: #2DCE89 (Verde)
Error: #F5365C (Vermelho)
Warning: #FB6340 (Laranja)
```

## 📁 Estrutura do Projeto

```
src/
├── components/
│   └── icons/               # Componentes SVG customizados
│       ├── BeijaFlorLogo.vue
│       ├── DeveloperIllustration.vue
│       ├── SecurityIcon.vue
│       ├── MessageIcon.vue
│       ├── DatabaseIcon.vue
│       ├── EmailIcon.vue
│       ├── WebIcon.vue
│       ├── DevelopmentIcon.vue
│       ├── PurposeIllustration.vue
│       ├── ContactIllustration.vue
│       ├── MissionIcon.vue
│       ├── VisionIcon.vue
│       └── ValuesIcon.vue
├── App.vue                  # Componente principal
└── main.js                  # Configuração do Vue e Vuetify
```

## 🌐 Compatibilidade

### Navegadores Suportados

- ✅ Chrome (versão 87+)
- ✅ Firefox (versão 78+)
- ✅ Safari (versão 14+)
- ✅ Edge (versão 88+)

### Responsividade

- 📱 Mobile (320px+)
- 📱 Tablet (768px+)
- 💻 Desktop (1024px+)
- 🖥️ Large Desktop (1440px+)

## 🔧 Customização

### Alterando Cores

Para alterar as cores do tema, edite o arquivo `src/main.js`:

```javascript
const vuetify = createVuetify({
  theme: {
    themes: {
      light: {
        colors: {
          primary: '#SUA_COR_AQUI',
          // ... outras cores
        },
      },
    },
  },
})
```

### Modificando Conteúdo

O conteúdo principal está localizado em `src/App.vue`. Cada seção é claramente marcada com comentários para facilitar a edição.

### Adicionando Novos Ícones SVG

1. Crie um novo arquivo `.vue` em `src/components/icons/`
2. Adicione o template SVG
3. Importe e registre no `App.vue`

## 📝 Scripts Disponíveis

- `npm run dev` - Inicia o servidor de desenvolvimento
- `npm run build` - Gera build de produção
- `npm run preview` - Visualiza a build de produção

## 🚀 Deploy

### Netlify

1. Faça build do projeto: `npm run build`
2. Faça upload da pasta `dist` para o Netlify

### Vercel

1. Conecte seu repositório ao Vercel
2. Configure o comando de build: `npm run build`
3. Configure o diretório de output: `dist`

### Servidor Web Tradicional

1. Execute `npm run build`
2. Copie o conteúdo da pasta `dist` para seu servidor web

## 🐛 Solução de Problemas

### Erro de dependências

```bash
rm -rf node_modules package-lock.json
npm install
```

### Erro de porta em uso

O Vite automaticamente procura uma porta disponível. Se necessário, especifique uma porta:

```bash
npm run dev -- --port 3000
```

## 🤝 Contribuindo

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## 👨‍💻 Desenvolvido com ❤️

Landing page criada seguindo as melhores práticas de desenvolvimento Vue 3 e design responsivo.

---

**Nota:** Este projeto foi desenvolvido como uma réplica fiel do design fornecido, utilizando tecnologias modernas e seguindo as melhores práticas de desenvolvimento web. 