# Novaera — Site Institucional

Site institucional para a Novaera, escritório de arquitetura e design de interiores. Página única (home) com showcase, processo, serviços, cases e contato, mais uma página de projetos com grade filtrável e estudos de caso individuais.

## Estrutura

```
index.dc.html        Home (single-page: hero, showcase, sobre, processo, serviços, diferenciais, antes/depois, FAQ, contato)
Projetos.dc.html      Galeria de projetos com filtros + página de estudo de caso
projects-data.js      Dados dos projetos, compartilhados entre as duas páginas
image-slot.js         Componente de imagem (drag-and-drop / troca de imagem)
support.js            Runtime necessário para os arquivos .dc.html
uploads/assets/       Imagens do site
```

## Rodando localmente

Não há build step. Sirva a pasta com qualquer servidor estático e abra `index.dc.html`:

```bash
npx serve .
```

## Stack

HTML + CSS inline + JS, sem framework nem bundler.
