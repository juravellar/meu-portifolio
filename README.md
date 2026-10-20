# Portfólio · Júllia Avellar

Meu portfólio pessoal: quem sou, com o que trabalho, meus principais projetos, minha trajetória e meus cursos.

🔗 **Acesse:** [portifolio-jullia-r-de-avellar.vercel.app](https://portifolio-jullia-r-de-avellar.vercel.app)

---

## O que tem no site

- **Apresentação:** quem sou e como falar comigo, com um botão para copiar o e-mail.
- **Stack:** as tecnologias que uso, separadas em back-end, front-end, dados e infraestrutura, e práticas.
- **Projetos:** os projetos que mais representam meu trabalho, cada um com descrição, tecnologias e links para o código e para a versão online.
- **Trajetória:** faculdade, estágio, emprego atual e TCC, em ordem.
- **Cursos e certificados:** os cursos que concluí, com instituição e ano.

A identidade visual brinca com o dia a dia de quem desenvolve APIs: cada projeto aparece como uma requisição HTTP (`GET /projetos/...` → `200 OK`).

## Tecnologias

- **HTML, CSS e JavaScript puros**, em um único arquivo e sem nenhuma dependência de build
- **Tema claro e escuro** automático, que segue a configuração do sistema (`prefers-color-scheme`)
- **Layout responsivo**, pensado também para celular
- **Acessibilidade:** HTML semântico, foco visível no teclado e respeito a `prefers-reduced-motion`
- **Fontes:** Bricolage Grotesque, IBM Plex Sans e IBM Plex Mono, pelo Google Fonts
- **Deploy:** Vercel, publicado automaticamente a cada push na `main`

## Como rodar localmente

Como é um site estático, basta abrir o arquivo no navegador:

```bash
git clone https://github.com/juravellar/meu-portifolio.git
cd meu-portifolio
```

Depois abra o `index.html`, ou suba um servidor local se preferir:

```bash
npx serve .
```

## Estrutura

```
meu-portifolio/
├── index.html   # o site inteiro: HTML, CSS e JavaScript
└── README.md
```

## Contato

- LinkedIn: [linkedin.com/in/júllia-r-de-avellar](https://www.linkedin.com/in/j%C3%BAllia-r-de-avellar/)
- GitHub: [github.com/juravellar](https://github.com/juravellar)
- E-mail: julliaravellar@gmail.com
