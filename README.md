# Vitrine Web

Site estático de apresentação da Vitrine Web.

## Arquivos
- `index.html`: página principal responsiva.
- `assets/logo-horizontal.webp`: logotipo horizontal otimizado com transparência.
- O favicon está incorporado em SVG no próprio HTML.

## Fotografias de fundo preservadas
Para manter as fotografias existentes no layout, o site usa os endereços que já eram servidos pela hospedagem anterior:

- `https://steep-disk-57d0.erison-miguel-silva.workers.dev/assets/hero-1920.webp`
- `https://steep-disk-57d0.erison-miguel-silva.workers.dev/assets/detail-1000.webp`

Essas URLs precisam continuar acessíveis. Se o endereço antigo for desativado, copie as fotografias para `assets/hero-1920.webp` e `assets/detail-1000.webp` e ajuste as referências no CSS/HTML.

## Publicação
O workflow `.github/workflows/pages.yml` prepara a publicação automática pelo GitHub Pages quando o Pages estiver habilitado nas configurações do repositório.

1. Abra **Settings → Pages**.
2. Em **Build and deployment → Source**, selecione **GitHub Actions**.
3. Abra **Actions** e confira o workflow **Publish Vitrine Web on GitHub Pages**. Se necessário, execute-o manualmente.
4. Após a publicação bem-sucedida, o site deverá estar em: https://dericksantosdeaquino-glitch.github.io/VitrineWeb/

Contato e links externos foram mantidos no HTML. A seção da pizzaria não faz parte deste site.
