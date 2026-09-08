# Instituto Raízes do Amanhã

Primeira versão da plataforma web acadêmica de uma ONG fictícia, estruturada em **HTML5 semântico**.

O conteúdo (nome da instituição, endereços, projetos e números) é inventado e serve apenas para estudo.

## Como visualizar

Não há servidor nem dependências. Abra o arquivo no navegador:

```
html/index.html
```

A partir daí, use o menu para ir a **Projetos** e **Cadastro**.

## Estrutura de pastas

```
ong-plataform/
??? html/
?   ??? index.html      # Página inicial institucional e contato
?   ??? projetos.html   # Iniciativas solidárias
?   ??? cadastro.html   # Formulário de voluntários e doadores
??? img/                # Ilustrações SVG com atributo alt nas páginas
??? README.md
```

## Páginas

| Arquivo | Função |
|---------|--------|
| `index.html` | Apresentação da ONG, missão, visão, valores e dados de contato |
| `projetos.html` | Projetos *Raízes na Mesa*, *Sala Aberta* e *Cuidar em Rede* |
| `cadastro.html` | Cadastro com validação HTML5 e máscaras de CPF, telefone e CEP |

## Recursos HTML5 utilizados

- Estrutura semântica: `header`, `nav`, `main`, `section`, `article`, `aside` e `footer`
- Hierarquia de títulos de `h1` a `h6`
- Imagens com `alt` descritivo
- Formulário com `fieldset`, `legend`, `label` e validações nativas (`required`, `type="email"`, `type="tel"`, `pattern`, entre outras)
- Máscaras de entrada em `cadastro.html` para CPF (`000.000.000-00`), telefone (`(11) 98765-4321`) e CEP (`00000-000`)

## Validação

Os três arquivos HTML foram conferidos no [Nu Html Checker (W3C)](https://validator.w3.org/nu/).

Para validar de novo, envie cada arquivo da pasta `html/` no validador.

## Observações

Esta versão ainda não inclui CSS. O visual é o padrão do navegador; a marcação está pronta para uma etapa posterior de estilo.
