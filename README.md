# Aplicacao-previsao-de-agrupamentos
Esta aplicação tem como objetivo realizar segmentação de usuários em grupos de interesse para campanhas de marketing. Com base em dados fornecidos pelo usuário, ela aplica um pipeline de pré-processamento e um modelo de K-Means para identificar padrões de comportamento e preferências, permitindo a criação de ações mais assertivas e personalizadas.

# Grupos de Interesse para Marketing

Um app interativo em **Streamlit** para segmentação de usuários em grupos de interesse, com base em algoritmos de **K-Means**. Permite direcionar campanhas de marketing de forma mais eficaz, criando perfis de público a partir de dados brutos.

# 🚀 Funcionalidades

- **Upload de CSV**: envie seus dados (incluindo coluna `sexo` e demais atributos numéricos).
- **Pré-processamento automático**:
  - Codificação de variáveis categóricas (`OneHotEncoder`).
  - Padronização de variáveis numéricas (`StandardScaler`).
- **Clusterização K-Means**: classificação dos usuários em 3 grupos de interesse.
- **Descrição dos grupos**: interpretação qualitativa de cada cluster.
- **Visualização**: exibição dos 10 primeiros registros com o rótulo de grupo.
- **Download**: exporte um CSV completo com os resultados.

🎯 Descrição dos Grupos

Grupo 0
Público jovem, com forte interesse em moda, música e estética.

Grupo 1
Perfil esportivo e cultural: futebol americano, basquete, bandas e rock.

Grupo 2
Mix equilibrado de interesses em música, dança e moda.

✉️ Contato
Desenvolvido por William Machado de Oliveira

E-mail: will.m.oliveira@gmail.com
