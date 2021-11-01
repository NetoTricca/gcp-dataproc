![image](https://user-images.githubusercontent.com/68438464/139738297-80b506c3-1553-4ba5-8d75-c6e63f1b3729.png)

# gcp-dataproc
Desafio DIO GCP DATAPROC HADOOP

O desafio faz parte do BootCamp Cloud Data Engineer:

Criando um ecossistema Hadoop totalmente gerenciado com Google Cloud Platform

O desafio consiste em efetuar um processamento de dados utilizando o produto Dataproc do GCP. 
Esse processamento irá efetuar a contagem das palavras de um livro e informar quantas vezes cada palavra aparece no mesmo.

Etapas do Desafio
Criar um bucket no Cloud Storage
Atualizar o arquivo contador.py 
Fazer o upload dos arquivos contador.py e livro.txt para o bucket criado
Utilizar o código em um cluster Dataproc, executando um Job do tipo PySpark chamando contador.py

O Job irá gerar uma pasta no bucket chamada resultado. Dentro dessa pasta o arquivo part-00000 irá conter a lista de palavras e quantas vezes ela é repetida em todo o livro.

Entrega do Resultado esta nesse repositório do GitHub com o arquivo resultado.txt.
Dentro desse arquivo estão as 10 palavras que mais são usadas no livro, de acordo com o resultado do Job.
