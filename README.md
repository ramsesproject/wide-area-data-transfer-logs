# wide-area-data-transfer-logs
Data used in our paper entitled "An Online, Machine Learning-Based Wide Area Data Transfer Performance Predictor". Some features are defined in paper: https://doi.org/10.1145/3078597.3078605

___Please contact Zhengchun Liu <zhengchun.liu-AT-anl.gov> if you have any questions about the data.___

Data explanation: 

__src__: The source endpoint name. It has been anonymized. In which, GCP denotes Globus Connect Personal and GCS represents Globus Connect Server.

__dst__: The destination endpoint name. It has been anonymized. In which, GCP denotes Globus Connect Personal and GCS represents Globus Connect Server. 

__request_time__: the time when transfer was initiated by user. The minute and second have been anonymized to zero. 

__R__: transfer throughput

__Ksout__: Contending outgoing transfer rate on source endpoint

__Kdin__: Contending incoming transfer rate on destination endpoint

__C__: Concurrency: Number of GridFTP processes

__P__: Parallelism: Number of TCP channels per process

__D__: Pipeline depth

__Ssout__: Number of outgoing TCP streams on source endpoint

__Ssin__: Number of incoming TCP streams on source endpoint

__Sdout__: Number of outgoing TCP streams on destination endpoint

__Sdin__: Number of incoming TCP streams on destination endpoint

__Ksin__: Contending incoming transfer rate on source endpoint

__Kdout__: Contending outgoing transfer rate on destination endpoint

__Nd__: Number of directories transferred.

__Nb__: Total number of bytes transferred. 

__Qsout__: Contending outgoing transfer rate on the institution of the source endpoint

__Qdin__: Contending incoming transfer rate on the institution of the destination endpoint

__Qsin__: Contending incoming transfer rate on the institution of the source endpoint

__Qdout__: Contending outgoing transfer rate on the institution of the destination endpoint

__Gsrc__: GridFTP instance count on source endpoint

__Gdst__: GridFTP instance count on destination endpoint

__Nf__: Number of files transferred.

All values are normalized to zero-mean, by each source-to-destination endpoint pair. 

Please contact zhengchun.liu-AT-anl.gov if you have any questions about the data.
