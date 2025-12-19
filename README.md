# Cartão Havan - Confirmação de Dados

Este projeto é um formulário de confirmação de dados com header da Havan, desenvolvido para integração com Typebot.

## Características

- Header azul com texto "HAVAN" centralizado
- Formulário de confirmação com dados dinâmicos
- Suporte para variáveis: `nome`, `cpf`, `data_nascimento`
- Design responsivo e profissional
- Integração perfeita com Typebot

## Como Usar

### Com parâmetros de URL:
```
https://seu-dominio.com/?nome={{nome}}&cpf={{cpf}}&data_nascimento={{data_nascimento}}
```

### Com iframe no Typebot:
```html
<iframe 
  src="https://seu-dominio.com/?nome={{nome}}&cpf={{cpf}}&data_nascimento={{data_nascimento}}"
  width="100%" 
  height="500" 
  frameborder="0"
  style="border-radius: 10px;">
</iframe>
```

## Variáveis Dinâmicas

- `nome`: Nome do usuário
- `cpf`: CPF do usuário
- `data_nascimento`: Data de nascimento do usuário

## Deploy no Railway

1. Conecte este repositório ao Railway
2. Configure as variáveis de ambiente conforme necessário
3. Deploy automático será acionado a cada push

## Autor

Desenvolvido para Havan
