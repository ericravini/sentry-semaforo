# Sentry — Semáforo Inteligente

Protótipo demonstrativo desenvolvido para um trabalho escolar de logística, simulando uma empresa fictícia de segurança pública.

## O produto

Em situações de emergência — perseguições policiais, ambulâncias a caminho de um hospital, viaturas de bombeiros — cada segundo perdido em um cruzamento pode significar risco de vida. O sistema proposto detecta a aproximação de um veículo de emergência e libera automaticamente o semáforo do seu trajeto, sem que ela precise parar ou avançar no sinal vermelho.

## A demonstração

Este repositório contém um site estático de página única (`sentry-semaforo.html`) com uma simulação interativa de um cruzamento de quatro vias:

- Um botão despacha uma viatura, que atravessa o cruzamento enquanto o semáforo do seu trajeto abre automaticamente.
- Fora do despacho, esse semáforo permanece sempre fechado — ele só passa a operar de forma automática após a primeira passagem da viatura.
- Os demais semáforos (norte, leste e oeste) seguem um ciclo automático padrão, sincronizados entre si para evitar colisões, e aparecem translúcidos para manter o foco no semáforo da viatura.
- Carros comuns circulam ocasionalmente pelas quatro vias, parando quando o sinal da própria via está fechado.

O objetivo é servir como material visual em um QR code, apresentado no stand do grupo no dia do trabalho.
