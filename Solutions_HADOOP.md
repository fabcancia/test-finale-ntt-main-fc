# Solutions HADOOP


1. 
    * HDFS(Hadoop Distributed File System): È il file system che permette ad Hadoop di distribuire i vari dati nel suo cluster di “salve” servers.

    * MapReduce: È un componente core di Hadoop che permette al sistema l’elaborazione parallela di dati.

    * Yarn: È utilizzato per ottimizzare l’uso delle risorse dell’HDFS.
    
    * Zookeper: permette l'oganizzazione e monitoraggio del cluster 

    * Oozie: permette di creare una scaletta per i vari jobs di Hadoop

    * Pig: linguaggio di scripting per Hadoop

    * Hive: che permette  l'esportazione dei dati 

    * Spark : permette di fare ETL e data  analisi 

    * Hbase : È un databse che funziona sopra HDFS per dati NoSQL

    * Flink e Kanfka: permettono l'input dei dati in Hadoop 


2. MapReduce permette l'elaborazione di grandi mole di dati in maniera efficente grazie al maccanismo di map e reduce. Nella parte di mapping MapReduce crea una mappa con coppie chiavi valore per ogni elemtento. Nella parte di reducing Mapreduce prende in input la mappa creata nel mapping e mischia, ordina per poi accoppiare tutti gli elementi con la stessa chiave.

3. PIG latin è un linguaggio si scripting ad alto livello che permette di processare i dati con MapReduce in maniera molto piu' semplice e intutitiva.

4.
    1.
        Dear 1 <br>
        Bear 1 <br>
        River 1 <br>
        Car 1 <br>
        Car 1 <br>
        River 1 <br>
        Deer 1 <br>
        Car 1 <br>
        Bear 1 <br>
    2.
        Bear [1,1] <br>
        Car [1,1,1] <br>
        Dear [1] <br>
        Deer [1] <br>
        River [1,1] <br>
    3.   
        Bear 2 <br>
        Car 3 <br>
        Dear 1 <br>
        Deer 1 <br>
        River 2 <br>

5.  Zlib è un software usato per la compressione dei dati che permette di comprimere i dati presenti nell' HDFS.

6. K-means è un algoritmo non supervisonato che permette l'aggregazione dei dati in dei clusters in base a criteri di similarita'. Viene usato in machine learning e funziona nel seguento modo:
    1. Vengono inizializati n centri di n clusters
    2. Agli elementi viene assegnato un cluster d'appartenenza in base al centroide piu' vicino
    3. Per ogni cluster il centroide viene ricalcolato in base agli elementi presenti nel cluster
    4. 2 e 3 vengono ripetuti fino a che i centroidi convergono

7. Files di testo, ORC files, Parquet files, RC files, AVRO files




