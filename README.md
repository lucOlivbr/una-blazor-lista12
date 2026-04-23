## Identificação
Nome: Lucas Alves Oliveira
Curso: Ciência da Computação
RA: 326129404

## Sobre o Projeto
Sistema de gamificação para a ONG ReCiclo onde o usuário registra ações sustentáveis e acompanha seu impacto em tempo real.

## Heurísticas de Nielsen

1. Visibilidade do Status do Sistema
O contador e a barra de progresso mostram em tempo real os pontos acumulados e o quanto falta para bater a meta.

2. Feedback do Sistema
O botão pisca em verde ao ser clicado e uma mensagem especial aparece ao atingir 100 pontos.

## Como Rodar

git clone https://github.com/seu-usuario/una-blazor-lista12
cd EcoMonitor
dotnet run --launch-profile https


## Como o [Parameter] foi usado

O [Parameter] permite que o componente EcoStatus seja reutilizado com valores diferentes em cada instância. Por exemplo, na Home.razor o mesmo componente é usado três vezes, cada um com seu próprio título e peso. Dentro do componente, as propriedades marcadas com [Parameter] recebem esses valores automaticamente pelo Blazor. Isso evita repetição de código e torna o componente flexível para qualquer tipo de ação ambiental.

## Desafios Extra
 Barra de progresso visual
 Mensagem de conquista ao atingir 100 pontos
