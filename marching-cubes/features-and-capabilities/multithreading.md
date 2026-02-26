# Multithreading

GeoForge fully utilizes the Unity Jobs System. Every backend operation large enough to justify a Job is implemented as IJobParrallelFor and parallelized automatically, or an IJob and parallelized alongside other IJobs.\
\
A user need not know anything about the Jobs system but will benefit from its incredible performance.&#x20;
