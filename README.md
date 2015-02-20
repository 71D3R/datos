##INSTALACIÓN
1. Del lado derecho seleccione **Download ZIP**.
2. Extraerlo en la carpeta de su preferencia.
3. Abrir la carpeta extraida **solr* **.
4. Buscar el archivo **txt.7z** y extraerlo ahi mismo, usar el password 
> **_Marie cuelga. Antes de salir, descarga la Glock y la deja en el_**

	se creara una carpeta llamada txt.

##CONFIGURACIÓN
###LINUX & MAC OS X
1. Abrir una terminal en la carpeta solr extraida anteriormente y ejecutar el comando _**ls**_, debe mostrar la siguiente estructura
```sh
[71d3r@pc solr-4.10.3]$ ls
bin          contrib  docs     licenses     LUCENE_CHANGES.txt  README.txt               txt
CHANGES.txt  dist     example  LICENSE.txt  NOTICE.txt          SYSTEM_REQUIREMENTS.txt  txt.7z
```
2. Ejecutar el comando 
```sh
bin/solr start -e cloud -noprompt
```
Mostrara una salida en pantalla similar a la siguiente

	```sh
	[71d3r@pc solr-4.10.3]$ bin/solr start -e cloud -noprompt
	which: no lsof in (/usr/local/sbin:/usr/local/bin:/usr/bin:/opt/android-sdk/tools:/usr/lib/jvm/default/bin:/usr/bin/site_perl:/usr/bin/vendor_perl:/usr/bin/core_perl)

	Welcome to the SolrCloud example!

	Starting up 2 Solr nodes for your example SolrCloud cluster.
	Cloning /home/71d3r/git/datos/solr-4.10.3/example into /home/71d3r/git/datos/solr-4.10.3/node1
	Cloning /home/71d3r/git/datos/solr-4.10.3/example into /home/71d3r/git/datos/solr-4.10.3/node2

	Starting up SolrCloud node1 on port 8983 using command:

	solr start -cloud -d node1 -p 8983   

	Started Solr server on port 8983 (pid=7332). Happy searching!
	```
	Si todo salio bien, en este [link](http://localhost:8983/solr/ "solr") se podra ver el panel de administración similar a este
    ![](/solr.png)
3. item



