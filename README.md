# fashiontech-analise-competitiva

#  FashionTech Insights: Análise Competitiva em E-commerce

**Objetivo do Projeto:** Demonstrar a aplicação de Engenharia de Dados e *Business Intelligence* na análise competitiva de gigantes do retalho (C&A, Renner e Riachuelo), com foco no nicho estratégico de **moda consciente e minimalista**.

Este notebook atua como uma montra técnica de análise de sistemas, detalhando o processo de extração de dados brutos e a sua transformação em *insights* de negócio acionáveis.

---

### Arquitetura Tecnológica e Soluções Aplicadas

1. **Web Scraping Avançado (Engenharia Reversa):** - Utilização do **Selenium** (Navegação Headless) para contornar bloqueios de segurança (Erros 403) e renderização dinâmica via JavaScript (APIs ocultas).
2. **Data Cleaning & Estruturação:** - Aplicação de **Expressões Regulares (Regex)** e **Pandas** para higienizar dados não estruturados de HTML e convertê-los numa base de dados relacional.
3. **Análise de Tendências (API Externa):** - Integração com o **pytrends** para cruzar o volume do portefólio interno com a intenção real de busca orgânica no Google (Market Share vs. Mindshare).
4. **Data Storytelling:** - Criação de visualizações de dados estatísticas focadas na experiência do utilizador, utilizando uma paleta cromática minimalista (Marrom Sépia e Bege Quente).

---

### Diagnóstico de Negócio: O Caso C&A

O cruzamento dos dados de precificação interna com o volume de pesquisas externas revelou um cenário claro para tomada de decisão estratégica:

* **Posicionamento de Preço:** A extração comprovou que existe um catálogo bem estruturado para o nicho de moda sustentável.
* **Gargalo de Visibilidade:** A análise do Google Trends revela que a concorrente direta (Renner) domina quase o dobro das intenções de busca do consumidor (Mindshare). 
* **Recomendação Técnica Estratégica:** É imperativo cruzar a atual base de dados de stock sustentável com campanhas focadas em SEO. O portefólio existe e é competitivo, mas necessita de uma ponte tecnológica e de marketing para converter a disponibilidade de produto em tráfego de pesquisa dominante.
