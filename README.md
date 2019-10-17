# Checklist: Pronto para Produção

Checklist pronto para produção com base no Apêndice A do livro: Production-Ready Microservices

# Conteúdo

- Estabilidade e Confiabilidade

  ✔ Ele tem um ciclo de desenvolvimento padronizado.<br/>
  ✔ Seu código passa por testes lint, unidade, integração e fim a fim.<br/>
  ✔ Seu processo de teste, empacotamento, versão e liberação é completamente automatizado.
  ✔ Ele tem um pipeline de deployment padronizado.
  ✔ Seus clientes são conhecidos.
  ✔ Suas dependências são conhecidas e existem backups, alternativas,fallback e cache em caso de falhas.
  ✔ Ele tem roteamento e descoberta estáveis e confiáveis.

- Escalabilidade e Alto Desempenho

  ✔ Suas escalas de crescimento qualitativo e quantitativo são conhecidas.
  ✔ Ele usa recursos de hardware de forma eficiente.
  ✔ Seus gargalos e requisitos de recursos foram identificados.
  ✔ O planejamento de capacidade é automatizado efeito de forma programada.
  ✔ Suas dependências escalam com ele.
  ✔ Ele escala com seus clientes.
  ✔ Seus padrões de tráfego são compreendidos.
  ✔ O tráfego pode ser redirecionado em casos de falhas.
  ✔ Ele é escrito em uma linguagem de programação que permite escalabilidade e alto desempenho.
  ✔ Ele trata e processa tarefas com alto desempenho
  ✔ Ele trata e armazenar dados de forma escalável e alto desempenho.

- Tolerante a Falhas e preparado para catástrofe

  ✔ Ele não tem um ponto único de falha.
  ✔ Todos os cenários de falha de possíveis catástrofes foram identificados.
  ✔ Ele é testado para resiliência por meio de teste de código, teste de carga e teste de caos.
  ✔ A detecção e o reparo de falhas foram automatizados.
  ✔ Há procedimentos padronizados de incidente e interrupção dentro da equipe de desenvolvimento do microsserviço e da organização.

- Monitoramento

  ✔ Suas métricas principais são identificadas e monitoradas nos níveis de servidor, infraestrutura e microsserviço.
  ✔ Ele tem um logging adequado, que reflete com precisão os estados passados do microsserviço.
  ✔ Seus dashboards são fáceis de interpretar e contém todas as métricas principais.
  ✔ Seus alertas são acionáveis e definidos por limites sinalizadores.
  ✔ Existe um turno dedicado de plantão responsável por monitorar e responder a quaisquer incidentes e interrupções.
  ✔ Há um procedimento claro, bem definido e padronizado de plantão para tratar incidentes sem interrupções.

- Documentado e Compreendido

  ✔ Ele tem uma documentação abrangente.
  ✔ Sua documentação é atualizada regularmente.
  ✔ Sua documentação contém uma descrição do micro serviço, um diagrama da arquitetura, informações de contato de plantão, links para informações importantes, um guia de bordo e desenvolvimento, informações sobre o fluxo de solicitação, os endpoints e as  dependências do serviço, um roteiro de plantão, FAQ. 
  ✔ Ele é bem compreendido nos níveis de desenvolvedor, equipe e organização.
  ✔ Ele segue um conjunto de padrões de disponibilidade de produção e cumprE os requisitos associados.
  ✔ Sua arquitetura é revisada e auditada frequentemente.
