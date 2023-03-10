![Badge em Desenvolvimento](https://img.shields.io/badge/HADOOP-blue)
![Badge em Desenvolvimento](https://img.shields.io/badge/HDFS-green)
![Badge em Desenvolvimento](https://img.shields.io/badge/Jupyter-Notebook-blue)
### FRANCISCO JAIME DA SILVA


## Projeto Engenharia de dados Datalake Simples Hadooop/HDFS


<p align="center"><img src="./imagens/AwsERM.png" width="500"></p>


O projeto consiste em criar um data lake no Hdaoop HDFS, fazer upload de dados para atestar o funcionamento.

---

### Etapas do Projeto

1. Foi Instalado e configurado ambeinte Hadoop Single node.
2 . Foram criados o diretórios abaixo no HDFS
<ul>
  <li>landing - Landing zone ou Zona de Pouso(dados em formato bruto)</li>
  - hadoop dfs -mkdir -p /usr/local/hadoop/data/dados/landing
  <li>processing - Processing zone(dados pre-processados)</li>
  - hadoop dfs -mkdir -p /usr/local/hadoop/data/dados/landing
  <li>curated - Curated zone(Dados limpos, agregados e prontos para análises)</li>  
</ul> 
<p align="center"><img src="./imagens/backetsaws.png" width="500"></p>
2.Foi realizado o upload dos arquivos de dados na zona de pouso(landing), extraídos do kaggle
https://www.kaggle.com/datasets/yelp-dataset/yelp-dataset
<ul>
  <li>yelp_academic_dataset_businessjson</li>  
  <li>Tyelp_academic_dataset_checkin.json</li>
  <li>yelp_academic_dataset_review.json</li>
  <li>yelp_academic_dataset_tip.json</li>
  <li>yelp_academic_dataset_user.json</li>
</ul> 

3. Foi feita a listagem dos arquivos
<p align="center"><img src="./imagens/SparkCompletado.png" width="500"></p>


