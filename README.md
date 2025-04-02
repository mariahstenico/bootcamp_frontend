# ClinAgenda

This project is part of the DEVPIRA + PECEGE 2025 bootcamp. It is designed for those who have never worked with Vue before but already have some web programming knowledge.

In this project, you will learn:

- Vue 3
- Vuetify
- Pinia
- TypeScript

## Usage

If this is your first time, run the following command:

```bash
yarn
```

Now, whenever you want to run this project, simples start the development server with hot-reload, by running the following command:

```bash
yarn dev
```

The server will be accessible at [http://localhost:3000](http://localhost:3000)

### Building for Production

To build your project for production, use:

```bash
yarn build
```

Once the build process is completed, your application will be ready for deployment in a production environment.

# Componente

# Atomic Design

Dividido em cinco componentes que trabalham juntos com o intuito de criar interfaces hierárquicas:

Átomos - São blocos de construção básicos da matéria que formam a interface (Exemplo: um label isolado é um átomo, um input é um átomo, um button é um átomo…)
Moléculas - Grupos simples de elementos da interface do usuário que funcionam juntos como uma unidade. (Exemplo: o label, o input e o button, juntos, formam uma molécula.)
_Organismos_ - Conjuntos de moléculas que funcionam juntas como uma unidade. Uma molécula com outra molécula (ou mais), formam um organismo (Exemplo: um header de um site.)
Templates - Saindo um pouco dos termos da química, os templates são objetos no nível de página, onde colocamos componentes em um layout formando a estrutura de página.
Páginas - É o resultado final, exatamente como o template, só que completa de informações reais. As páginas são o nível de fidelidade mais alto e, por serem as mais tangíveis, normalmente é onde a maioria das pessoas envolvidas em seu processo de criação, passa grande parte do tempo. É em torno dela, também, que gira a maioria das avaliações.
