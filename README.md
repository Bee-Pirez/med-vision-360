## 💭 Descrição

<p>Um projeto frontend desenvolvido para o desafio Global Solution da Graduação na Fiap em Sistemas para Internet</p>

### Deploy
https://medvision.vercel.app/

## 💡 Informações do projeto

### Normativa do desafio:

"Pense em uma solução dentro do escopo da área da saúde e desenvolva o protótipo de
uma plataforma web utilizando React e realize sua hospedagem. A plataforma deve conter
recursos de acessibilidade para pessoas com deficiência."

### Solução:

O MedVision 360 é apenas um protótipo frontend que nasceu da convicção fundamental de que a educação médica
deve ser acessível, envolvente e prática desde o início. Dessa forma, a plataforma ofereceria uma
abordagem 360 graus para a aprendizagem médica. 

### Funcionalidades que idealizamos:

- Exploração Imersiva: Alunos teriam acesso a uma galeria de aulas,
proporcionando uma visão detalhada da anatomia e procedimentos cirúrgicos;
- Aulas Interativas com Professores Registrados: Professores, devidamente
registrados pelas instituições, poderiam conduzir aulas ao vivo, compartilhando
conhecimento em tempo real e proporcionando interação direta com os
alunos;
- Integração com Med Vision (Futuros Óculos Inteligentes): Nossa plataforma
teria integração com óculos para gravação (que estão sendo testados e
idealizados, com uma webcam encaixada em um óculos), permitindo,
futuramente, que professores gravem procedimentos médicos em tempo real,
proporcionando, uma experiência de aprendizado imersiva para os alunos.

OBS: claro que questões de lesgislação, proteção de dados, regulamentações...devem ser levadas em consideração, porém esse projeto visa apenas a criação da ideia e prática das técnologias aprendidas.

### 💻 Recursos de acessibilidade:

- Tema Apropriado para Daltônicos (Verificado em Adobe Color):
Ao utilizar um tema apropriado, garantimos que a interface seja perceptível e
compreensível para todos os usuários. Melhorando a legibilidade e facilitando
a navegação, criando assim, uma experiência mais inclusiva.
- Atributo "Alt" para Imagens:
Incluir atributos "alt" em imagens permite que leitores de tela descrevam o
conteúdo visual para usuários com deficiência visual. Oferecendo
informações contextuais sobre as imagens presentes na plataforma.
- Navegação Simplificada:
Oferecer uma navegação clara e lógica para facilitar a compreensão e a
utilização do site por usuários com deficiências cognitivas.


### 👨‍💻 Principais tecnologias:

- [React]
  - Framework Front-End Javascript
  - Uso dos Hooks
- [Vite]
  - Biblioteca que ajuda com o processo de build de aplicações web
- [Javascript])
- [React Router]
  - Roteador do React
- [styled-components]
- [react-webcam]
  - Pacote de componente de webcam para react



## 🛠️ Modificando o projeto Windows

### Siga as seguintes instruções para instalar e poder modificar o projeto em sua máquina:

### 📋 Pré-requisitos:

Para baixar, executar e modificar o projeto, você precisa ter instalado em sua máquina: 
* ambiente de tempo de execução JavaScript [Node](https://nodejs.org/en/)
* Gerenciador de pacotes que vem junto ao Nodejs [Npm](https://www.npmjs.com/)
* [Git](https://git-scm.com/downloads)
* Editor de código ou IDE, como o [VSCode](https://code.visualstudio.com/Download)

### 🔧 Instalação e execução

1. Clone o repositório
```
git clone https://github.com/Bee-Pirez/med-vision-360.git
```
2. Acesse a pasta do projeto
```
cd med-vision-360
```
3. Instale as depedências
```
// Com o Npm
npm i // Ou npm install

```
4. Inicie o servidor de desenvolvimento do projeto
```
// Com o Npm:
npm run dev

Obs: o servidor iniciará - acesse por: <http://localhost:porta que ele executar/>


```



# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
