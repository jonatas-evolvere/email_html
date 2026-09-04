# Assinaturas de e-mail — Evolvere Consultoria

Implementação canônica das assinaturas de Igor Henrique e Jonatas Santos, consolidada a partir das issues #1 a #12.

## Arquivos para uso

- `assinatura_igor.html`
- `assinatura_jonatas.html`
- `assinaturas.json`: fonte estruturada dos dados aprovados
- `assets/*-email.*`: imagens recortadas e otimizadas para e-mail

## Direção de implementação

- Marca: navy `#0F0F50` e laranja `#FF6B00`
- Logo branca sobre navy
- Largura fixa de 600 px, layout por tabelas e estilos inline
- Fontes seguras do sistema; nenhum `@import`
- Sem SVG embutido, flexbox, grid, hover ou dependência de media query
- Imagens servidas por GitHub Raw e fixadas em SHA de commit
- E-mails pessoais omitidos intencionalmente

## Instalação

Abra o HTML correspondente no navegador, copie a assinatura renderizada e cole no editor de assinatura do provedor de e-mail. Depois envie uma mensagem de teste para Gmail, Outlook e Apple Mail e confirme também no celular.

Não altere manualmente os endereços das imagens para `main`: o SHA imutável evita que uma atualização posterior mude assinaturas que já foram instaladas.
