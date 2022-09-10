# Prueba Corta 2
## 1. Explique el concepto de shard, replica y partition.
#### Shard
Es la manera de segmentar la base de datos de manera horizontal, se particiona la base de datos principal en bases mas pequeñas con datos similares.
#### Replica
Una replica en base de datos es cuando, se copia una base de datos a otro disco o instancia en la nube, para tener exactamente los mismo datos. Se puede tener una base de datos principal y 1 o mas replicas de estas. Estas copias pueden ser en tiempo real, o se hacen copias cada cierto tiempo.
#### Partition
Es cuando una en una base de datos se particionan las tablas en tablas mas pequeñas, con esto se mejora el tiempo de busqueda al tener tablas mas pequeñas es mas rapida.
## 2. Explique la diferencia entre Strong Consistency Eventual Consistency.
Eventual consistency es cuando en una base de datos con replicas, sus replicas no tienen en ciertos momentos los mismos datos que la base de datos principal, puede que hayan momentos en los que los datos diferan de la principal. En cambio en strong consistency las replicas tienen que tener los mismos datos que la principla siempre.
## 3. ¿En que consiste warm replicas y hot replicas?
Warm replicas es cuando se tiene una copia de una base de datos, pero esta no siempre es igual a la principal puede que hayan momentos en que los daros no son iguales.
Hot replicas es cuando la base de datos principal es siempre igual as su replica en todo momento no hay lapsos en el cual sus datos sean diferentes.
## 4. ¿En que consiste consiste switch over y fail over?
Un Switch over es cuando se cambia la base de datos principal por una de sus respaldos en tiempo real sin perdida de datos.En este caso la base de datos normalmente no falla o deja de operar nada mas queda en stanby.

Un Fail Over se da cuando la base de datos principal falla y una de sus replicas, pasa a ser la principal. En este caso es cuando paso una falla no recuperable.Puede causar perdida de datos.

