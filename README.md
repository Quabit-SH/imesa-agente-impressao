# Agente de Impressão iMesa

Programa para Windows que liga as impressoras térmicas do restaurante ao iMesa. Com ele instalado, os pedidos feitos no iMesa saem impressos na cozinha, no bar e no caixa.

## O que você precisa

- Windows 10 (versão 22H2) ou Windows 11, 64 bits.
- Um computador que fique ligado durante todo o expediente, na mesma rede das impressoras.
- Internet.

## Como instalar

1. Acesse a página de [Releases](../../releases/latest) e baixe o arquivo `iMesa-AgenteImpressao-Setup-0.1.1.exe`.
2. Execute o arquivo baixado.
3. Durante o piloto, o Windows pode mostrar o aviso "editor desconhecido". Isso é esperado. Clique em **Mais informações** e depois em **Executar assim mesmo**.
4. No painel do iMesa, vá em **Configurações → Agente de impressão** e gere o código de pareamento. Digite esse código no programa quando ele pedir.
5. Na janela que abrir, configure as impressoras.
6. Pronto. Quando o ícone perto do relógio estiver **verde**, o agente está funcionando.

## Como conferir o arquivo (SHA-256)

Para ter certeza de que o arquivo baixado está íntegro, abra o PowerShell na pasta do download e rode:

```powershell
(Get-FileHash .\iMesa-AgenteImpressao-Setup-0.1.1.exe).Hash
```

O resultado deve ser igual a:

```
51dafb197449ce9523a3bdb86cbef409438631fd36af16d569336188c39d5982
```

## Suporte

Fale com o suporte do iMesa.
