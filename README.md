# wide-area-data-transfer-logs
Data used in our paper entitled "An Online, Machine Learning-Based Wide Area Data Transfer Performance Predictor". Some features are defined in paper: https://doi.org/10.1145/3078597.3078605

src: The source endpoint name. It has been anonymized. In which GCP denotes Globus Connect Personal and GCS represents Globus Connect Server.

dst: The destination endpoint name. It has been anonymized. In which GCP denotes Globus Connect Personal and GCS represents Globus Connect Server. 

request_time: the time when transfer was initiated by user. The minute and second have been anonymized to zero. 

R: transfer throughput

Ksout: Contending outgoing transfer rate on source endpoint

Kdin: Contending incoming transfer rate on destination endpoint

C: Concurrency: Number of GridFTP processes

P: Parallelism: Number of TCP channels per process

D: Pipeline depth

Ssout: Number of outgoing TCP streams on source endpoint

Ssin: Number of incoming TCP streams on source endpoint

Sdout: Number of outgoing TCP streams on destination endpoint

Sdin: Number of incoming TCP streams on destination endpoint

Ksin: Contending incoming transfer rate on source endpoint

Kdout: Contending outgoing transfer rate on destination endpoint

Nd: Number of directories transferred.

Nb: Total number of bytes transferred. 

Qsout: Contending outgoing transfer rate on the institution of the source endpoint

Qdin: Contending incoming transfer rate on the institution of the destination endpoint

Qsin: Contending incoming transfer rate on the institution of the source endpoint

Qdout: Contending outgoing transfer rate on the institution of the destination endpoint

Gsrc: GridFTP instance count on source endpoint

Gdst: GridFTP instance count on destination endpoint

Nf: Number of files transferred.

All values are normalized to zero-mean, by each source-to-destination endpoint pair. 

Please contact zhengchun.liu-AT-anl.gov if you have any questions about the data.
