<p align="center"> <a href="https://github.com/SynthesisAl"> <img src="https://github.com/user-attachments/assets/0ab0fa7c-097d-481a-a5ea-4dd093c9106c" width="480"></a></p>


# Logs

<div>
<img src="https://github.com/user-attachments/assets/63c08061-7054-4ab6-9f37-268ef6d5e8ea" width="600"/>
</div>

Logs maintains a collection of system logs, which are freely accessible for AI-driven log analytics research. Some of the logs are production data released from previous studies, while some others are collected from real systems in our lab environment. Wherever possible, the logs are NOT sanitized, anonymized or modified in any way. These log datasets are freely available for research or academic work.

🤗 We proudly announce that the loghub datasets have attained total <a href="https://doi.org/10.5281/zenodo.1144100"><img src="https://img.shields.io/endpoint?&url=https://cdn.jsdelivr.net/gh/logpai/loghub@zenodo/downloads.json&labelColor=1AE&color=DDEEFF&style=flat&label=Downloads"></a> by more than [**450 organizations**](https://github.com/logpai/loghub/wiki/Loghub-download-list) from both industry and academia.

### Logs currently available

🔗 Get raw logs via hyperlinks in the Download column.

| Dataset              | Description | Labeled | Time Span  |  #Lines  |   Raw Size   |  Download  |
| :---------------------------- | :--------|  :--------: | --------: | ---------: | ------: | :------: | 
|<tr><th colspan=7 align="center">:open_file_folder: **Distributed systems**</th></tr>|
| [HDFS_v1](./HDFS#hdfs_v1)     | Hadoop distributed file system log | :heavy_check_mark: | 38.7 hours | 11,175,629  |  1.47GB  | [:link:](https://zenodo.org/records/8196385/files/HDFS_v1.zip?download=1)   |      
| [HDFS_v2](./HDFS#hdfs_v2)     | Hadoop distributed file system log|  |    N.A.    | 71,118,073  | 16.06GB  | [:link:](https://zenodo.org/records/8196385/files/HDFS_v2.zip?download=1)  |
| [HDFS_v3](./HDFS#hdfs_v3_tracebench)     | Instrumented HDFS trace log (TraceBench) | :heavy_check_mark: |    N.A.    | 14,778,079  | 2.96GB  | [:link:](https://zenodo.org/records/8196385/files/HDFS_v3_TraceBench.zip?download=1)  |
| [Hadoop](./Hadoop)            |  Hadoop mapreduce job log | :heavy_check_mark: |   N.A.    |   394,308   | 48.61MB  |  [:link:](https://zenodo.org/records/8196385/files/Hadoop.zip?download=1)  |
| [Spark](./Spark)              | Spark job log ||    N.A.    | 33,236,604  |  2.75GB  | [:link:](https://zenodo.org/records/8196385/files/Spark.tar.gz?download=1)  |                            
| [Zookeeper](./Zookeeper)      | ZooKeeper service log | | 26.7 days  |   74,380    | 9.95MB  |  [:link:](https://zenodo.org/records/8196385/files/Zookeeper.tar.gz?download=1)   | 
| [OpenStack](./OpenStack)      |  OpenStack infrastructure log | :heavy_check_mark: |  N.A.    |   207,820   | 58.61MB  |  [:link:](https://zenodo.org/records/8196385/files/OpenStack.tar.gz?download=1)  |    
|<tr><th colspan=7 align="center">:open_file_folder: **Super computers**</th></tr>|
| [BGL](./BGL)          | Blue Gene/L supercomputer log | :heavy_check_mark: | 214.7 days |  4,747,963  | 708.76MB |  [:link:](https://zenodo.org/records/8196385/files/BGL.zip?download=1)   |
| [HPC](./HPC)                  |  High performance cluster log | |  N.A.    |   433,489   | 32.00MB  |  [:link:](https://zenodo.org/records/8196385/files/HPC.zip?download=1)  |           
| [Thunderbird](./Thunderbird)  |  Thunderbird supercomputer log | :heavy_check_mark: | 244 days  | 211,212,192 | 29.60GB  | [:link:](https://zenodo.org/records/8196385/files/Thunderbird.tar.gz?download=1)  |
|<tr><th colspan=7 align="center">:open_file_folder: **Operating systems**</th></tr>|  
| [Windows](./Windows)          | Windows event log | | 226.7 days | 114,608,388 | 26.09GB  | [:link:](https://zenodo.org/records/8196385/files/Windows.tar.gz?download=1)   |    
| [Linux](./Linux)              | Linux system log | | 263.9 days |   25,567    |  2.25MB  |  [:link:](https://zenodo.org/records/8196385/files/Linux.tar.gz?download=1)  |
| [Mac](./Mac)                  | Mac OS log | | 7.0 days  |   117,283   | 16.09MB  | [:link:](https://zenodo.org/records/8196385/files/Mac.tar.gz?download=1)  |
|<tr><th colspan=7 align="center">:open_file_folder: **Mobile systems**</th></tr>|  
| [Android_v1](./Android#android_v1)          |  Android framework log | |  N.A.    | 1,555,005  |  183.37MB | [:link:](https://zenodo.org/records/8196385/files/Android_v1.zip?download=1) |
| [Android_v2](./Android#android_v2)          |  Android framework log | |  N.A.    | 30,348,042  | 3.38GB  | [:link:](https://zenodo.org/records/8196385/files/Android_v2.zip?download=1)  |
| [HealthApp](./HealthApp)      | Health app log  | | 10.5 days  |   253,395   | 22.44MB  | [:link:](https://zenodo.org/records/8196385/files/HealthApp.tar.gz?download=1)  |
|<tr><th colspan=7 align="center">:open_file_folder: **Server applications**</th></tr>|            
| [Apache](./Apache) | Apache web server error log | | 263.9 days |   56,481    |  4.90MB  | [:link:](https://zenodo.org/records/8196385/files/Apache.tar.gz?download=1)   |                     
| [OpenSSH](./OpenSSH)          | OpenSSH server log | | 28.4 days  |   655,146   | 70.02MB  | [:link:](https://zenodo.org/records/8196385/files/SSH.tar.gz?download=1) |
|<tr><th colspan=7 align="center">:open_file_folder: **Standalone software**</th></tr>|                           
| [Proxifier](./Proxifier)      |   Proxifier software log | | N.A.    |   21,329    |  2.42MB  |   [:link:](https://zenodo.org/records/8196385/files/Proxifier.tar.gz?download=1) |                                           

:bulb: If you use Synthesis datasets in your paper, please feel free to make a PR to add your paper to the table.

### 🌈 License
The datasets are freely available for research or academic work. For any usage or distribution of the datasets, please refer to the loghub repository URL https://github.com/SynthesisAl/Logs
