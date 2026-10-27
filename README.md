# Portal PMSC — protótipo para demonstração

Protótipo estático e responsivo para apresentação interna. Desenvolvido para ser publicado rapidamente na Vercel.

## Publicar na Vercel
1. Descompacte o ZIP.
2. Acesse https://vercel.com/new e importe/crie um projeto.
3. Envie a pasta `pmsc-portal-demo` para um repositório Git (GitHub, GitLab ou Bitbucket) e importe-o na Vercel. Alternativamente, use a CLI da Vercel na pasta.
4. Como é um site estático, não exige build command. O arquivo de entrada é `index.html` na raiz.

## O que já está no protótipo
- Cabeçalho estadual com links oficiais e barra própria da PMSC fixa durante a rolagem.
- Menu lateral acessível por teclado e com controle de foco básico.
- Banner de destaque, notícias, atalhos de serviços, área institucional e rodapé responsivo.
- Cores de referência do Guia SC: verde `#336633`, vermelho `#C4000B`, texto `#333333`, fundo branco e cinza `#F8F8F8`.
- Recursos demonstrativos de acessibilidade: aumento de texto, contraste e destaque de links.
- Aviso de cookies com aceitar, negar e salvar preferências.

## Importante antes de produção
- Este é um protótipo de apresentação, não um portal oficial em produção.
- Manchetes e notícias são conteúdo demonstrativo. Validar todos os textos, destinos, telefones e redes sociais antes de publicar.
- Algumas imagens são carregadas de URLs externas e exigem conexão à internet.
- O logotipo estadual usa a imagem publicada pelo portal do Governo de SC. Validar marca, brasão e aplicação oficial da PMSC com a Comunicação Social.
- O aviso de cookies é apenas demonstrativo; integrar com solução aprovada e configurar consentimento conforme orientação institucional/LGPD.
- Os controles de acessibilidade ilustram recursos básicos, mas não substituem auditoria WCAG/eMAG, testes com leitor de tela, teclado, contraste e avaliação ASES/Lighthouse.
- A implementação final deverá validar o padrão institucional e a acessibilidade com os responsáveis do Governo do Estado.
