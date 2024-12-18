# Aleon Senado Federal Analytics

## O que foi usado para desenvolver as análises

1. Versão Python:

   - 3.10

2. Versionamento:

   - Git

3. Bibliotecas:

   - requests: para realizar chamadas a api do senado
   - pandas: processamento das tabelas
   - xmltodict: fazer o `parser` dos resultados advindos da api
   - matplotlib: exibir os gráficos
   - networkx: construir grafos e exibi-los
   - numpy: manipulação extra de alguns dados vetoriais

   para instalar as dependências:

   ```bash
   pip install -r requirements.txt
   ```

4. Análises

**Histogramas que mostram a porcentagem de matérias legislativas feitas pelos congressistas:**

- Pode-se analisar a baixa adesão dos congressistas (senadores e deputados) com relação ao trabalho de autoria e relatoria de matérias legislativas no congresso.
  ![Matérias Legislativas por senadores](histograma_congressistas.png)

**Histograma que mostra o número de senadores por cada partido**

- Pode-se analisar que o partido que possui maior influência no senado é o PSD.
  ![Senadores por partido](senadores_por_partido.png)

**Histograma que mostra a quantidade de matérias legislativas por partido**

- Pode-se analisar que os partidos que mais participam dessa atividade são PL, PT e PSD.
  ![Matérias Legislativas por partido](materias_legislativas_por_partido.png)

**Histograma que mostra o número de assuntos específicos para cada assunto geral discutido no congresso**

- Pode-se analisar que o assunto com mais desdobramentos é o econômico.
  ![Assuntos especificos](assuntos_especificos_por_geral.png)

**Grafo de proximidade que mostra os partidos mais relacionados com base em blocos políticos no congresso**

- Pode-se analisar nesse grafo a proximidade dos partidos de esquerda e direita como dois grafos separados, em que os vértices representam o bloco que os partidos se ligam e os nós a sigla do partido.
  ![Blocos Políticos](grafo_proximidade.png)

**Histograma com a participação dos partidos nas votações de matérias legislativas em 2024**

- Pode-se analisar que todos os partidos tem uma participação relevante nas votações, acima de 90%, sendo os partidos NOVO, PSB, PSDB e REPUBLICANOS os que acumulam 100% de participação.
  ![Participação em votação](porcentagem_participacao_partido.png)
