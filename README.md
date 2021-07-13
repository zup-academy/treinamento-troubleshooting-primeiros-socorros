# Treinamento Troubleshooting para Aplicações Performáticas: Primeiros Socorros

## Resumo

* Seja capaz de diagnosticar e resolver vazamentos de memória em aplicações Java
* Seja capaz de identificar e resolver os principais gargalos de performance na sua camada de persistência
* Seja capaz de gerar testes de estresse e de carga com relatórios detalhados para suas aplicações Java
* Seja capaz de diagnosticar e resolver problemas de concorrência e fazer tuning no pool de threads da sua aplicação Java
* Seja capaz de monitorar, identificar e resolver problemas e gargalos em aplicações distribuídas

## Ementa

1. Diagnosticando gargalos na sua aplicação Java
    - Revisitando a JVM
    - Gerenciamento e modelo de memória na JVM
    - Os diferentes tipos de Garbage Collector (GC)
    - Monitorando sua aplicação Java com JMX e jConsole
    - Tuning de memória e análise do ciclo de coletas do GC
    - Detectando vazamento de memória na aplicação
    - Ferramentas de profiling: analisando problemas de performance na aplicação com jVisualVM
    - Gerando e analisando dump de memória da aplicação (heap dump)
    - Docker: cuidados ao empacotar aplicações Java em containers

2. Diagnosticando gargalos na camada de acesso a dados
    - Como um banco de dados relacional funciona
    - Identificando as queries SQL mais lentas e custosas da aplicação
    - Plano de execução e índices: analisando gargalos em queries SQL
    - Domine seu framework ORM: JPA e Hibernate
    - Habilitando o log SQL do Hibernate
    - Tunando o pool de conexões da aplicação
    - Detectando vazamento de conexões na aplicação
    - Identificando e resolvendo problemas de Select N+1
    - Habilitando cache de segundo nível do Hibernate
    - Quando o cache é o culpado da performance
    - Habilitando estatísticas do Hibernate

3. Usando ferramentas de testes de estresse e de carga
    - Relação entre throughput e response time
    - Estressando a aplicação com jMeter, Apache A/B e K6
    - Trabalhando com workload mais próximo da produção
    - Monitorando a JVM e o sistema operacional
    - Encontrando o throughput máximo da minha aplicação
    - Gerando relatórios com métricas e gráficos para sua equipe
    
4. Diagnosticando gargalos de concorrência
    - Concorrência na JVM e ciclo de vida de uma thread
    - O custo de uma thread e a importância de um pool de threads
    - Monitorando as threads na aplicação
    - Tunando o pool de threads para latência
    - Não esqueça do pool de threads do servidor de aplicação
    - Tunando o pool de threads para throughput
    - Tratamento de erros em operações assíncronas
    - O perigo e os cuidados ao compartilhar estado entre threads
    - Trabalhando com Concurrent Collections

5. Diagnosticando gargalos em sistemas distribuídos
    - As 8 falácias dos sistemas distribuídos
    - Perigo das integrações: quando esperar demais sobrecarrega a aplicação
    - Fail Fast: falhe rápido e libere recursos da aplicação
    - Monitoramento: minha aplicação está no ar? Quais as taxas de sucesso e erros das requisições?
    - Habilitando métricas RED e USE com Prometheus e Grafana
    - Monitoramento: identificando o gargalo em chamadas remotas
    - Habilitando o tracing distribuído na aplicação
    - Ocorreu um erro: mas em qual serviço e qual a mensagem de erro?
    - Habilitando logging distribuído na aplicação
    - Mensageria: revisando conceitos
    - Monitorando a produção e consumo de mensagens
    - Poison messages: quando o consumidor não consegue processar uma mensagem
    - Definindo políticas de retries e dead-letter queues
    - Identificando gargalos no processamento de mensagens

## Quem está criando?

Temos dois zuppers focados na criação deste treinamento. Rafael Ponte(príncipe do oceano) e Yuri Matheus(o nosso jovem que de tanta tranquilidade parece o mestre ancião). Sinta-se a vontade para falar com eles e falar sobre qualquer ponto que eventualmente você ache importante relacionado ao que será apresentado no treinamento.

## Está interessado ?

A primeira versão deste treinamento está prevista para ser lançada no dia 06/09/2021. Ela vai poder ser consumido no modelo que chamamos de self-paced, ou seja você faz no seu tempo respeitando o seu contexto. Ele virá recheado de conteúdo teórico autoral e muitas atividades que vão realmente te desafiar. 

Acreditamos que um treino realmente bem feito acelera demais seu desenvolvimento e te deixa cada vez mais preparado(a) para os desafios que você vai encontrar no campo de jogo. Se 

Para ser notificado(a) do lançamento, pedimos que deixe seu email aqui neste [formulário](https://forms.gle/HPxoh4AJA2DdWzud8). 



