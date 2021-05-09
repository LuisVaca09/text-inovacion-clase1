# Acordeon de estudio AZ-900
## Inteligencia artificial


# Indice
1. [Consejos para el uso de GitHub](#crear-un-repositorio)
2. [Conceptos utiles](#conceptos-utiles)
3. [Modelos de servicio en la nube](#modelos-de-servicio-en-la-nube)
4. [Modelos de implementación en la nube](#modelos-de-implementacon-en-la-nube)
5. [Gastos de capital y de operaciones](#gastos-de-capital-y-de-operaciones)


## Consejos para el uso de GitHub

#### Conservar cambios de un repositorio
- Una vez se a creado nuestro repositorio y hemos logrado realizar nuestro primer commit y vinvularlo a la nube de GitHub, debemos de seguir algunos pasos para conservar los futuros cambios que generemos al archivo de manera local.
- Hay que guardar el archivo README.md mediante un CTR+S.
- Despues debemos cargar el archivo .md con los cambios que deseemos conservar mediante el uso de add. *Ejemplo*: git add .
- Realizar un commit para hacer el corte de lo que tenemos modificado. *Ejemplo*: git commit -m "Modificacion 2"
- Mandar un push para actualizar nuestro GitHub. *Ejemplo*: git push -u origin main
- Con esto nuestro repositorio en la nube se actualizara.

#### Uso de corchetes
##### Hipervinculos
Para crear hipervincluloas, poner entre corchetes [] lo que se desea ver en el hipervinculo, despues dentro de unos parentesis () solo colocamos el link o el texto que deseemos ligar al hiperviculo.

##### Insertar imagenes
Para adjuntar alguna imagen, debemos de cerrar un signo de admiracion ! seguido de un par de corchetes, dentro de ellos colocaremos el nombre que identifica a la imagen, y despues un par de parentesis que encierren el link o ubicacion de la imagen a insertar.

## Conceptos utiles
### Nube
Conocido como servicio en la nube, es una tecnologia que permite acceder remoteamente desde cualquier parte del mundo en el momento que se solicite a software, almacenamiento de archivos y procesamiento de datos a traves de internet.
![](https://www.enter.co/wp-content/uploads/2018/09/Cloud-1-768x432.jpg)

*Ejemplos*
![](https://www.grupocarac.es/wp-content/uploads/2020/02/ejemplos_cloud-1024x239.jpg)

### Maquina virtual
Es un software que puede hacerse pasar por una PC. En ella se emula un ordenador completo.
![](https://comofriki.com/wp-content/uploads/2017/09/Maquina_Virtual-201.jpg)

*Ejemplo*
![](https://miracomosehace.com/wp-content/uploads/2020/07/logo-de-computador-virtual.jpg)

### Inteligencia artificial.
Es la combinación de algoritmos planteados con el proposito de crear maquinas que presenten las mismas capacidades que un ser humano.  Su finalidad es el aprendizaje automatico.
*Ejemplo*: Parte de los algoritmos implementados en las recomendaciones de YouTube permite sugerir ese video que se convertira en nuestro nuevo video favorito, mediante predicciones el algoritmo aprende de nuestros gustos y mejora conforme acierta en ellos.
![](https://www.iberdrola.com/wcorp/gc/prod/es_ES/comunicacion/inteligencia_artificial_1_res/Inteligencia_746x419.jpeg)


## Modelos de servicio en la nube.
**IaaS** Infraestructrua como servicio es similar a la administracipon de servidores fisicos. De forma general brinda el acceso a las caracteristicas de conexion en red, a los equipos y al espacio de almacenamiento, pero el mantenimiento del sistema operaitvo y la propia configuración de red correran a cargo del inquilino. Su filosofia es: en luigar de comprar equipo de computo, alquilalo. Su principal ventaja radica en lo sencillo que es implementar nuevos dispositivos de proceso.
**PaaS** Plataforma como servicio quitan esa necesidad de administrar la infraestructura (hardware y sistemas operativos) dejando solo la necesidad de centrarse en la implementación de las aplicaciones. Su filosofia es: Paga por lo que usas y necesitas.
**SaaS**: Software como Servicio proporciona un servicio más completo que los anteriores, da acceso a aun producto el cual solo se ejecuta y administra. Son comunmente empleadas en aplicaciones de usuario final. Su filosofia es: Nosotros te damos lo que necesitas.

![](https://nanobytes.es/web/image/55083/Comparativa%20iaas%20paas%20saas.png?access_token=760263c2-d615-4e27-887f-a463ed1366d0)


## Modelos de implementación en la nube
**Nube publica**: Es un modelo de implementación que se encuentra fuera de las instalaciones de una compañia, con infraestructura de gran escala que se comparten y se implementan en internet para el publico general bajo regimen de autoservicio. Este modelo es preferible cuando se desea flexibilidad de pago y en caso de contar con trafico abundante e impredecible.
**Nube privada**: En este modelo, una infraestructura especifica esta considerada para un solo cliente. Como resultado se tiene una mayor seguridad y la privacidad de los datos almacenados.
**Nube hibrida**: Para este caso, tanto la nube publica como privada se combinanan mediante una red exlcusiva, utilizando la gran flexibilidad que una nube publica otorga con la seguridad y privacidad de datos de la nube privada.

![](https://i.pinimg.com/originals/ad/19/a6/ad19a6e80d464a5293f78b863a041c58.jpg)

##**Servicios interesantes que ofrece Azure**
- Azure Virtual Machines
Brinda maquienas virtuales mediante la plataforma Azure donde podremos tener acceso a un procesamiento con un mejores rendimiento.
- Azure Virtual Network
Nos permite entrar a la red con nuestras maquinas virtuales mediante una VPN, dandonos una mayor seguridad y control de nuestros datos.
- Azure Blod Storage
Proporciona almacenamiento para archivos pesados.
- Azure File storage
Brinda un entorno de recursos compartidos.

###**Ventajas de trabajar en la nube**
**Disponibilidad**: las aplicaciones estaran disponibles en cualquier momento a pesar de presentarse errores.
**Escalabilidad**: Se puede escalar horizaontal y verticalmente.
- Verticalmente: Mejorar las capacidades de proceso que posee una maquina virtual
- Horizontalmente: Añadir mas maquinas virtuales

**Elastiicidad**: Si se desea escalar, las aplicaciones programadas pueden hacerlo de forma automatica y asi asegurar la disponibilidad de recursos.
**Agibilidad**:Impementar y configurar los recursos que se tienen rápidamente.
**Distribucion  geografica**: La distribución de las bases de datos pueden estar en centros regionales para brindar el mejor rendimiento a los usuarios finales.
**Recuperasión de desastres**: Gracias a las copias de seguridad, los datos almacenados en la nube no se perderan ante un desastre en los centros de datos.


## Gastos de capital y de operaciones
**Gastos de capital (CapEx)**: Son los relacionados a la inversión previa de la infraestuctura, se puede deducir conforme el tiempo pasa.
**Gastos de operativos (OpEx)**: Es el capital que se invierte en servicios o productos. Este tipo de gastos se puede deducir al poco tiempo de adquirir el servico. 




