# Projeto ProCivIA - Assistente de IA para Proteção Civil

  !ProCivIA Banner (https-user-images.githubusercontent.com/12345/67890.png) <!-- Placeholder para um futuro
  banner -->

  Bem-vindo ao hub central do Projeto ProCivIA. Este repositório serve como a porta de entrada para o
  ecossistema de ferramentas de Inteligência Artificial desenvolvidas para apoiar as operações de proteção
  civil em Portugal.

  ## Missão

  O ProCivIA visa potenciar a capacidade de análise, previsão e resposta a emergências através da automação da
  recolha de dados, da análise de inteligência de múltiplas fontes (OSINT) e da coordenação de agentes
  especializados.

  ---

  ## Arquitetura do Ecossistema

  O projeto está estrategicamente dividido em duas vertentes principais, cada uma com o seu próprio repositório
   e propósito:

  ### 1. ProCivIA-Web

  ![Versão 
  (https://img.shields.io/badge/Version-v0.1.0-blue.svg)](https://github.com/jnabais-glitch/ProCivIA-Web)
  ![Estado 
  (https://img.shields.io/badge/Estado-Ativo-brightgreen.svg)](https://github.com/jnabais-glitch/ProCivIA-Web)

  A face pública e acessível do projeto. É uma aplicação web "cloud-native" com uma API e uma interface de
  chat, desenhada para ser facilmente implementada em qualquer serviço de cloud.

     Propósito:* Análise de fontes abertas, demonstração de capacidades e interação com o utilizador.
     Tecnologias:* FastAPI, Docker, HTML/CSS/JS.
     Aceda ao Repositório: 
  [github.com/jnabais-glitch/ProCivIA-Web](https://github.com/jnabais-glitch/ProCivIA-Web)*

  ### 2. ProCivIA-CLI

  ![Versão 
  (https://img.shields.io/badge/Version-v0.5.0-blue.svg)](https://github.com/jnabais-glitch/ProCivIA-CLI)
  ![Estado 
  (https://img.shields.io/badge/Estado-Pausado-lightgrey.svg)](https://github.com/jnabais-glitch/ProCivIA-CLI)

  A ferramenta de análise profissional para operadores locais. É a versão completa do ProCivIA, que tira
  partido de integrações profundas com software de desktop para automação e geração de relatórios complexos.

     Propósito:* Análise avançada, automação de tarefas locais e integração com sistemas legados.
     Tecnologias:* Python, PyWin32 (Outlook), Integração QGIS.
     Aceda ao Repositório: 
  [github.com/jnabais-glitch/ProCivIA-CLI](https://github.com/jnabais-glitch/ProCivIA-CLI)*

  ---

  ## Roteiro (Roadmap)

     [ ] Q3 2025:* Deploy da v0.1.0 do ProCivIA-Web num serviço de cloud (Render).
     [ ] Q4 2025:* Integração do agente Elysia (RAG) no ProCivIA-Web.
     [ ] 2026:* Retomar o desenvolvimento do ProCivIA-CLI com foco na integração de novas fontes de dados
  locais.
