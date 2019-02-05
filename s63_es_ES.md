---
layout: default_es_ES
---
# Condiciones de uso para S-63 UserPermits

- S-63 plugin no está disponible para iOS o Android.

- No vendemos cartas de S-63, sólo ofrecemos el S-63 *UserPermit* como herramienta necesaria para licenciar cartas S-63 de distribuidores como [Chartworld](https://www.chartworld.com/shop/off_enc).

- Para comprar una carta de S-63 de cualquier proveedor, necesita un UserPermit. Cartas licenciadas con el OpenCPN S-63 UserPermit solo se pueden utilizar en OpenCPN según lo establecido en las normas para S-63.

- Puede utilizar cada carta adquirida en 5 *sistemas* simultáneamente o puede guardar copias de seguridad en caso que su sistema falle. Generaremos un OpenCPN *InstallPermit* para cada sistema individual. El InstallPermit vincula un conjunto de cartas S-63 para OpenCPN a un sistema. No confunda el OpenCPN Install Permit mit S-63 cell permits.

- *sistema* es la combinación entre ordenador y sistema operativo. Si alguno de estos elementos cambia, su sistema se presentará como uno nuevo, perderá su licencia y tendrá que usar su copia de seguridad.

- Si ha consumido los 5 posibilidades de instalar las cartas, tiene que comprar un nuevo UserPermit y licenciarlas cartas para este nuevo UserPermit. Como se trata de un nuevo ciclo, tiene otra vez 5 oportunidades de instalación (InstallPermits).

- Su licencia debría sobrevivir a cualquier actualización del Sistema Operativo, OpenCPN o Plugin pero si reinstala su sistema operativo, perderá su licencia.

- Una vez que haya licenciado un UserPermit no podremos reembolsarle.

- Una vez que ha generado un InstallPermit para un sistema no podemos cancelar o moverlo a una combinación dispositivo/OS diferente.

- Compruebe las condiciones de los proveedores de cartas S-63 en cuanto a actualizaciones y caducidad.

# Instalar UserPermits/InstallPermit y cartas S-63

![pasos](./assets/images/s63.png)

1. *sistema* es la computadora que usará para OpenCPN. El juego de cartas suministrado por el VAR y que licencies para un sistema, solo podrá ser usado en dicho sistema. Descarga e instala el [S-63 plugin](https://opencpn.org/OpenCPN/plugins/s63.html) (sólo para versión 4.6 y superiores de OpenCPN).
    
2. Entra en OpenCPN, *Opciones → Plugins → S63* y activa el plugin. A continuación entra en la pestaña *Opciones → Cartas → Cartas S63 → Keys/Permits* y crea un archivo de identificación del sistema (*Fingerprint*) para tu sistema presionando en el botón *Crear archivo de identificación* del sistema.
    
3. Entra en [la tienda de o-charts ](https://o-charts.org/shop) y compra un UserPermit.
    
4. Entra en la página [Mis UserPermits S-63](https://o-charts.org/shop/index.php?fc=module&module=ocpermits&controller=ocpermits) y crea un InstallPermit seleccionando el UserPermit y subiendo el archivo Fingerprint.
    
5. Entra en la tienda de un VAR y compra tantos juegos de cartas S-63 como desees suministrando tu número UserPermit. A veces un VAR a pedir un "HW-ID", puede ignorar la pregunta.
    
6. Descarga y descomprime los archivos del juego de cartas. Contendrá un directorio llamado ROOT_ENC (que contiene las celdas de la carta) y también encontrará un archivo llamado PERMIT.txt con los permisos de la celda.
    
7. En OpenCPN, entra* Opciones → Cartas → Cartas S63 → Keys/Permits.*. Introduce tu UserPermit y compruebalo presionando el botón *Nuevo UserPermit*. Introduce tu InstallPermit y compruebalo presionando el botón *Nuevo InstallPermit*.
    
8. Entra en la pestaña *Opciones → Cartas → Cartas S63 → Celdas de cartas*. Instalar permisos de celdas usando el botón *Importar Permisos de Celdas* para buscar el archivo PERMIT.TXT dentro de tus juegos de cartas S-63. Importa tus juegos de cartas S-63 presionando el botón *Importar Cartas/Actualizaciones* para buscar la carpeta ENC_ROOT dentro de tus juegos de cartas S-63.
    
9. ¡OpenCPN creará los archivos eSENC necesarios y listo!

# Preguntas frecuentes

> **¿Por qué cartas S-63?**
> 
> Son oficiales y generalmente las más actualizadas. Las cartas vectoriales usadas en los plotters en el mercado de recreo son en el mejor de los casos derivadas de estas (algunas incorporarán algunos extras).
> 
> **¿Por qué tengo que pagar para la UserPermit?**
> 
> Necesitamos una infraestructura permanente para poder ejecutar esta operación y responder ante la IHO. Esta estructura y sus costes están reducidos al mínimo. En el caso de conseguir un gran éxito economicamente hablando, los beneficios se reinvertirán en el proyecto OpenCPN.
> 
> **¿Como cuantos sistemas cuenta un sistema dual boot?**
> 
> Cada combinación HW/SW es individual y requiere su propio InstallPermit.
> 
> **¿Y si instalo el software en una máquina Virtual?**
> 
> No funcionará. Tenemos que evitar que el sistema pueda ser clonado para cumplir los términos de la licencia.
> 
> **Tuve que volver a instalar mi sistema operativo. Ahora el InstallPermit ya no es válido**
> 
> Genera un nuevo Installpermit por favor.
> 
> **Mi PC murió. ¿Puedo recuperar las cartas?**
> 
> Sí, pero le "costará" un InstallPermit para su nueva máquina.
> 
> **¿Puedo tener mi InstallPermit y las cartas en una memoria USB y utilizarlos en distintos sistemas?**
> 
> Esto sería una solución de un hardware dongle. Creemos que no es viable para nosotros enviar memorias USB o DVDs por todo el mundo. Por eso optamos por un software dongle. Así pues, por el momento la respuesta es: no.
> 
> **¿Cuánto cuestan las cartas S-63 (y por que son muy caras a veces)?**
> 
> El precio de venta es fijado por los respectivos HOs. Sus clientes pertenecen a la navegación comercial o a organismos oficiales como los gobiernos, no al mercado del ocio. Este es un tema reconocido y la razón por qué, por ahora, hay muy pocos usuarios de cartas S-63 de este grupo. Se necesita mucha presión para conseguir mejores soluciones y mejores precios. Se agradeceria la ayuda o apoyo de quienes tienen los contactos adecuados.
> 
> **Mi licencia temporal caduca. ¿Qué pasará después?**
> 
> Las cartas no desaparecerán, pero se mostrará una advertencia.
> 
> **OpenCPN es open source. ¿Dónde está el código para el plugin?**
> 
> Para trabajar con S-63 tenemos que asegurar que copias de las células sin cifrar no son accesibles durante la ejecución del software. Por lo tanto, el plug-in tiene una parte de código abierto y un binario. Similar a los plug-ins comerciales nv-gráfico o BSB4.
