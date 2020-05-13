# IDEA_Unir
Sobre IDEA versión 11 y el comando Unir. IDEAScript y Python.

Se presenta un ejemplo de ejecución del comando en formato IDEAScript y en Python. El archivo sobre el cual se ejecuta el script es una tabla de IDEA: Ejemplo-Detalle de ventas.IMD como tabla principal y Ejemplo-Clientes.IMD como tabla secundaria.

De esta manera se da un ejemplo de la interacción entre el software de Auditoria IDEA de CASEWARE con Python. Muy útil para automatizar fácilmente las diferentes tablas en formato IMD con las herramientas de machine learning que posee Python.

Mediante este comando se puede unir de diferentes maneras dos tablas.

En línea de task.PerformTask, en el último valor considerar:

##0 = WI_JOIN_MATCH_ONLY

##1 = WI_JOIN_ALL_IN_PRIM

##2 = WI_JOIN_ALL_REC

##3 = WI_JOIN_NOC_SEC_MATCH

##4 = WI_JOIN_NOC_PRI_MATCH
