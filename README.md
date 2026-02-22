# Analise-Redes-Sociais-dos-Perfis-Socioeconomicos-dos-Beneficiarios-do-Bolsa-Familia
📊 Análise de Redes Sociais dos Perfis Socioeconômicos dos Beneficiários do Programa Bolsa Família no Brasil
📌 Descrição do Projeto

Este projeto aplica a metodologia de Análise de Redes Sociais (ARS) para investigar a estrutura relacional das características socioeconômicas associadas a domicílios beneficiários e não beneficiários do Programa Bolsa Família no Brasil.

A proposta é complementar abordagens tradicionais de avaliação de políticas públicas, examinando não apenas indicadores médios, mas a organização estrutural das vulnerabilidades socioeconômicas.

🎯 Objetivo

Analisar diferenças na configuração estrutural das características socioeconômicas entre beneficiários e não beneficiários do Bolsa Família por meio de:

Construção de redes de coocorrência

Cálculo de métricas estruturais

Detecção de comunidades (Louvain)

Visualização gráfica das redes

O foco central é investigar se a condição de recebimento do benefício está associada a diferentes padrões de integração, fragmentação e intensidade relacional entre vulnerabilidades.

🧠 Fundamentação Metodológica

A Análise de Redes Sociais permite modelar variáveis socioeconômicas como nós interconectados por relações de coocorrência.

Neste estudo:

Nós → Características socioeconômicas (infraestrutura, raça, escolaridade, condição urbana, insegurança alimentar etc.)

Arestas → Coocorrência entre características

Peso das arestas → Intensidade da associação

Foram estimadas as seguintes métricas:

Número de nós e arestas

Densidade da rede

Componentes conectados

Força média (average strength)

Betweenness média

Modularidade (Louvain)

📈 Principais Resultados
🔹 Comparabilidade

Ambas as redes possuem 22 características socioeconômicas, permitindo comparação direta.

🔹 Conectividade

A rede dos não beneficiários apresentou:

Maior densidade

Maior número de arestas

Estrutura totalmente conectada

A rede dos beneficiários apresentou:

Menor densidade

Dois componentes conectados

Maior dispersão estrutural

🔹 Intensidade Relacional

A força média das conexões foi significativamente maior entre não beneficiários, indicando maior coocorrência estrutural de características.

🔹 Comunidades

A modularidade próxima de zero em ambas as redes indica ausência de clusters fortemente delimitados, sugerindo estruturas densas e pouco segmentadas.

🛠 Tecnologias Utilizadas

Software: R

Manipulação de dados: dplyr, tidyr, Matrix

Análise de redes: igraph, tidygraph

Visualização: ggraph, ggplot2

📊 Visualizações

O projeto inclui:

Rede de coocorrência — Beneficiários

Rede de coocorrência — Não beneficiários

Comunidades (Louvain) — Beneficiários

Comunidades (Louvain) — Não beneficiários

📌 Contribuição

Este estudo demonstra o potencial da Análise de Redes Sociais aplicada a microdados socioeconômicos, oferecendo uma perspectiva estrutural complementar à avaliação tradicional de políticas públicas.

Os resultados sugerem que programas de transferência de renda podem estar associados a uma reconfiguração relacional das vulnerabilidades, reduzindo a acumulação intensa de desvantagens.

📎 Referência

Caso utilize este projeto, cite como:

Meira, Maurício Almeida (2026). Análise de Redes Sociais dos Perfis Socioeconômicos dos Beneficiários do Programa Bolsa Família no Brasil.
