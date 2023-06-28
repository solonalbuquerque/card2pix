# card2pix

Repositório mostrando como implementar o https://usepix.com.br sem precisar fazer cadastro!

## O UsePIX
Facilita e muito o recebimento de pagamentos via PIX.
É gratuito, não precisa de cadastro e funciona 24h com vários gateways conectados.

## Personalizar no index.html
```
const urlBase = "https://usepix.com.br/", // url base do checkout
      valorMinimo = 1, // limite mínimo para conversão
      valorMaximo = 1200, // limite máximo para conversão (verificar o seu limite com o suporte)
      pixParceiro = "email@dominio.com.br", // sua chave pix para receber as comissões
      telefoneSuporteWhatsapp = "5511999999999"; // seu telefone público para suporte via whatsapp
```

## Comissões
Para cada transação o pixParceiro irá receber uma comissão.

## Alterações
Pode fazer um fork, clone ou alterar como desejar.