# Clone Disney+

![Disney Plus Logo](disneyplus.svg)

## Sobre o Projeto

Este projeto é um clone da interface do Disney+, desenvolvido com o objetivo de replicar a experiência visual e interativa do serviço de streaming da Disney. O clone foi construído utilizando HTML, SCSS e JavaScript, com automação de tarefas através do Gulp, proporcionando uma experiência semelhante à plataforma original.

O projeto apresenta uma interface responsiva que se adapta a diferentes tamanhos de tela, desde dispositivos móveis até desktops, mantendo a fidelidade visual e a experiência de usuário característica do Disney+.

## Demonstração

O projeto está disponível para visualização em: [clone-disney-plus-murex.vercel.app](https://clone-disney-plus-murex.vercel.app/)

## Tecnologias Utilizadas

O desenvolvimento deste clone do Disney+ foi realizado com as seguintes tecnologias:

### Linguagens e Marcação

- **HTML5**: Estruturação semântica do conteúdo da página
- **SCSS**: Pré-processador CSS para estilização avançada com recursos como variáveis, aninhamento e mixins
- **JavaScript**: Implementação de interatividade e comportamentos dinâmicos

### Ferramentas de Automação

- **Gulp**: Sistema de automação para otimização do fluxo de trabalho de desenvolvimento
  - **gulp-sass**: Compilação de arquivos SCSS para CSS
  - **gulp-uglify**: Minificação de arquivos JavaScript
  - **gulp-imagemin**: Otimização de imagens

### Fonte

- **Avenir**: Fonte utilizada no projeto para manter a fidelidade visual com o Disney+ original

### Hospedagem

- **Vercel**: Plataforma utilizada para deploy e hospedagem do projeto

## Estrutura do Projeto

```
clone_disneyPlus/
│
├── assets/
│   └── fonts/          # Fontes utilizadas no projeto
│
├── src/
│   ├── images/         # Imagens originais
│   ├── scripts/        # Arquivos JavaScript
│   └── styles/         # Arquivos SCSS
│
├── dist/               # Arquivos compilados e otimizados (gerados pelo Gulp)
│   ├── css/
│   ├── js/
│   └── images/
│
├── .gitignore          # Arquivos ignorados pelo Git
├── gulpfile.js         # Configuração do Gulp
├── index.html          # Página principal
├── package.json        # Dependências e scripts
└── package-lock.json   # Versões específicas das dependências
```

## Instalação

Para executar este projeto localmente, siga os passos abaixo:

1. **Clone o repositório**

```bash
git clone https://github.com/joaogriquena/clone_disneyPlus.git
cd clone_disneyPlus
```

2. **Instale as dependências**

```bash
npm install
```

3. **Execute o projeto em modo de desenvolvimento**

```bash
npm run dev
```

Este comando iniciará o Gulp em modo de observação, que compilará os arquivos SCSS, minificará o JavaScript e otimizará as imagens automaticamente sempre que houver alterações.

## Uso

Após a instalação e execução do projeto, você pode acessar a aplicação localmente através do navegador. O projeto inclui:

- **Página inicial**: Réplica da página inicial do Disney+
- **Header responsivo**: Com logo e botões de "Assine agora" e "Entrar"
- **Seção Hero**: Apresentação principal com imagens e informações destacadas
- **Catálogo**: Exibição de conteúdos disponíveis na plataforma

Para visualizar as alterações em tempo real durante o desenvolvimento, o Gulp está configurado para monitorar mudanças nos arquivos fonte e atualizar automaticamente os arquivos compilados.

## Funcionalidades

O clone do Disney+ implementa as seguintes funcionalidades:

- **Layout Responsivo**: Adaptação automática para diferentes tamanhos de tela
- **Navegação**: Menu de navegação com opções semelhantes ao site original
- **Exibição de Conteúdo**: Apresentação de filmes e séries em formato de catálogo
- **Estilização Fiel**: Reprodução fiel das cores, tipografia e elementos visuais do Disney+
- **Otimização de Performance**: Arquivos CSS e JavaScript minificados para carregamento rápido

## Contribuição

Contribuições são bem-vindas! Se você deseja contribuir com este projeto, siga os passos abaixo:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-funcionalidade`)
3. Faça commit das suas alterações (`git commit -m 'Adiciona nova funcionalidade'`)
4. Faça push para a branch (`git push origin feature/nova-funcionalidade`)
5. Abra um Pull Request

## Licença

Este projeto está licenciado sob a licença ISC, conforme especificado no arquivo package.json.

## Contato

João Griquena - [GitHub](https://github.com/joaogriquena)

Link do Projeto: [https://github.com/joaogriquena/clone_disneyPlus](https://github.com/joaogriquena/clone_disneyPlus)

---

Desenvolvido com ❤️ como um projeto de estudo e demonstração de habilidades front-end.
