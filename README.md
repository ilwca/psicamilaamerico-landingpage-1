# psicamilaamerico-landingpage

Landing page da psicóloga Camila Américo — Astro + CSS puro, site 100% estático.

```sh
npm install
npm run dev      # http://localhost:4321
npm run build    # gera dist/
npm run preview  # serve o build
npm run check    # checagem de tipos
```

- `src/components/` — uma seção por componente (Header, Hero, Sobre, Atendimento, Citacao, Processo, Contato, Footer)
- `src/styles/global.css` — tokens de cor/tipografia e estilos base
- `src/data/site.ts` — dados de contato (WhatsApp, e-mail, Instagram, CRP)
- `src/assets/` — fotos originais; o Astro gera AVIF/WebP/JPG responsivos no build
- `redesign-minimalista-psicamila/` — handoff do Claude Design (referência, não entra no build)
