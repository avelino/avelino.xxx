Title: Introdução ao tnsnames.ora
Date: 2010-06-21 21:59
Author: avelino
Category: Avelino
Slug: introducao-ao-tnsnamesora

A Oracle (corporação) é uma empresa mantenedora
do Database Enterprise Oracle. Como o foco da Oracle é business eles
foca em uma documentação mais profissional onde os Certificado consiga
entender com facilidade.

Bom chega de blablabla, vamos para parte de template de TNS:

~~~~ {.brush:python}
XE =
(DESCRIPTION =
(ADDRESS =
(PROTOCOL = TCP)(HOST = localhost)
(PORT = 1521)
)
(CONNECT_DATA =
(SERVER = DEDICATED)
(SERVICE_NAME = XE)
)
)
~~~~

Isso é muito importante quando você tem uma aplicação onde tem que
conectar em um Database remoto.