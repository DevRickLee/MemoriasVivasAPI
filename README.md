# 🏛️ Memórias Vivas: Trajetórias Artístico-Culturais do IFBA Eunápolis

Este repositório contém a **API REST** do Memorial Virtual, desenvolvida para preservar, organizar e difundir a história das atividades artístico-culturais do campus Eunápolis nos últimos 30 anos. O projeto é uma iniciativa do Núcleo de Arte e Cultura (NAC) e visa valorizar a memória institucional e a formação integral dos estudantes.

## 🚀 Tecnologias e Stack
* **Backend:** Java 17+ com Spring Boot 3.
* **Segurança:** Spring Security (Autenticação via API para o Administrador).
* **Banco de Dados:** MySQL 8.0 (SGBD Relacional).
* **Persistência:** Spring Data JPA / Hibernate.
* **Frontend (Consumidor):** HTML5, CSS3 e JavaScript (integração via endpoints).

## 📋 Funcionalidades (Metas do Projeto)
* **Levantamento e Catalogação:** Registro de documentos, fotografias, cartazes e vídeos arquivados.
* **Memória Oral:** Indexação de pelo menos 10 entrevistas completas com egressos, servidores e artistas.
* **Memorial Virtual:** Plataforma interativa com linha do tempo e galerias multimídia.
* **Acessibilidade:** Estruturação de acervo digital acessível para pessoas com deficiência.

## 🔐 Segurança (Spring Security)
A API implementa um modelo de acesso simplificado focado no gerenciamento único por parte do administrador:
* **Público (GET):** Todos os endpoints de consulta ao acervo são abertos para fomento e difusão cultural.
* **Administrativo (POST, PUT, DELETE):** Operações de escrita são restritas ao usuário `ADMIN` via autenticação por API.
* **Handlers:** Configuração customizada de `successHandler` e `failureHandler` para integração limpa com o Frontend.

## 📅 Cronograma de Execução (2025-2026)
O projeto segue o calendário oficial estabelecido no Plano de Trabalho:
* **Out/2025 - Fev/2026:** Levantamento inicial, digitalização e catalogação (Metas 1 e 2).
* **Nov/2025 - Abr/2026:** Desenvolvimento do Memorial Virtual e Testagem (Meta 3).
* **Abr/2026 - Mai/2026:** Lançamento público e exposição multimídia (Meta 4).
* **Maio/2026 - Jun/2026:** Avaliação final e prestação de contas à PROEX (Meta 5).

## 👥 Equipe e Realização
* **Realização:** Núcleo de Arte e Cultura (NAC) - IFBA Campus Eunápolis.
* **Apoio:** Pró-Reitoria de Extensão (PROEX) via Edital 10/2025.
* **Bolsista:** Werick Henrique Santos Goncalves.
* **Voluntários:** Pedro Wandrey Barbosa Xavier e José Henrique Araújo Ravani.
* **Coordenação:** Eliana Costa Sausmickt.
* **Direção Geral:** Fabiana Zanelato Bertolde.