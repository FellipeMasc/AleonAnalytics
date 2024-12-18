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

- **Histogramas que mostram a porcentagem de matérias legislativas feitas pelos congressistas:**
  -Pode-se analisar a baixa adesão dos congressistas (senadores e deputados) com relação ao trabalho de autoria e relatoria de matérias legislativas no congresso.
  ![Matérias Legislativas por senadores](histograma_congressistas.png)

- **Histograma que mostra o número de senadores por cada partido**
  -Pode-se analisar que o partido que possui maior influência no senado é o PSD.
  ![Senadores por partido](senadores_por_partido.png)

- **Histograma que mostra a quantidade de matérias legislativas por partido**
  -Pode-se analisar que os partidos que mais participam dessa atividade são PL, PT e PSD.
  ![Matérias Legislativas por partido](materias_legislativas_por_partido.png)
