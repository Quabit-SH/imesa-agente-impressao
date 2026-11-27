# Agente de Impressão iMesa

Programa para Windows que liga as impressoras térmicas do restaurante ao iMesa. Com ele instalado, os pedidos feitos no iMesa saem impressos na cozinha, no bar e no caixa.

## O que você precisa

- Windows 10 (versão 22H2) ou Windows 11, 64 bits.
- Um computador que fique ligado durante todo o expediente, na mesma rede das impressoras.
- Internet.

> Quem usa iFood: atualize para a versão 0.1.2. As versões 0.1.0 e 0.1.1 não imprimem o ticket de produção dos pedidos do iFood.

## Como instalar

1. Acesse a página de [Releases](../../releases/latest) e baixe o arquivo `iMesa-AgenteImpressao-Setup-0.1.2.exe`.
2. Execute o arquivo baixado.
3. Durante o piloto, o Windows pode mostrar o aviso "editor desconhecido". Isso é esperado. Clique em **Mais informações** e depois em **Executar assim mesmo**.
4. No painel do iMesa, vá em **Configurações → Agente de impressão** e gere o código de pareamento. Digite esse código no programa quando ele pedir.
5. Na janela que abrir, configure as impressoras.
6. Pronto. Quando o ícone perto do relógio estiver **verde**, o agente está funcionando.

## Como conferir o arquivo (SHA-256)

Para ter certeza de que o arquivo baixado está íntegro, abra o PowerShell na pasta do download e rode:

```powershell
(Get-FileHash .\iMesa-AgenteImpressao-Setup-0.1.2.exe).Hash
```

O resultado deve ser igual a:

```
bd4b302fa0c01fd9d98f7ef74c08193c083dd74093d334994b84c0cdbd49ad0a
```

## Suporte

Fale com o suporte do iMesa.
