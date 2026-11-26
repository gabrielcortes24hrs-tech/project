# Lumenzzatto

Landing page estática da marca Lumenzzatto — serviços elétricos residenciais, orçamento e apresentação institucional.

## Stack
- HTML, CSS e JavaScript vanilla em `index.html`
- Sem dependências de build
- Efeitos decorativos de energia/código; não representam telemetria elétrica real

## Configurar WhatsApp
Em `index.html`, procure `CONFIGURE_NUMERO_COMERCIAL` no handler do formulário e substitua pelo número comercial em formato internacional, apenas dígitos (ex.: código do país + DDD + número). Teste o formulário antes de publicar.

## Publicação (GitHub Pages)
1. Abra Settings → Pages no repositório.
2. Configure Source como GitHub Actions.
3. Faça merge da branch de melhoria para `main`; o workflow publica a raiz do repositório.

## Revisão
- Responsivo, skip-link, movimento reduzido e campos com autocomplete.
- Não foi feito teste de navegador nesta etapa; valide em dispositivos reais antes do lançamento.
