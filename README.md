# Analisis de datos de ENACOM (Ente Nacional de Comunicaciones) 
![Logo](https://github.com/Colombo02/Data-Analysis-ENACOM/blob/main/_src/Enacom.jpg) 

## Contexto  
  
Las telecomunicaciones se refieren a la transmisión de información a través de medios electrónicos, como la telefonía, la televisión, la radio y, más recientemente, el internet. Estos medios de comunicación permiten la transmisión de información entre personas, organizaciones y dispositivos a largas distancias.  
El internet, por su parte, es una red global de computadoras interconectadas que permite el intercambio de información en tiempo real. Desde su creación, ha tenido un impacto significativo en la vida de las personas, transformando la manera en que nos comunicamos, trabajamos, aprendemos y nos entretenemos.  
La industria de las telecomunicaciones ha jugado un papel vital en nuestra sociedad, facilitando la información a escala internacional y permitiendo la comunicación continua incluso en medio de una pandemia mundial. La transferencia de datos y comunicación se realiza en su mayoría a través de internet, líneas telefónicas fijas, telefonía móvil, y en casi cualquier lugar del mundo. 

## Rol a Desarrollar 
La principal actividad es brindar acceso a internet. Realicé un análisis que permite reconocer el comportamiento de este sector a nivel nacional pudiendo asi mejorar calidad de sus servicios, identificar oportunidades de crecimiento y poder plantear soluciones personalizadas a sus posibles clientes.  
  
Se comenzo con un **ETL (Extracción, transformación y carga de los datos)** sobre los diversos datasets brindados por la pagina oficial de **ENACOM** (https://datosabiertos.enacom.gob.ar/dashboards/20000/acceso-a-internet/) para que sean posibles analizarlos. En terminos generales se hicieron cambios de datos, relleno de nulos, reemplazo de caracteres y union de dataframes (para ver mas en detalle vaya al archivo ETL). Tambien se trabajo con un dataset brindado por la pagina del gobierno de Argentina (https://datos.gob.ar) para obtener el **valor del dolar** y realizar la conversion de pesos a dolares para que los ingresos no se vean afectados por la inflación.  
  
Se continuo con un **EDA (Analisis Exploratorio de los Datos)** con el objetivo de adquirir una comprensión inicial de los datos, revelar patrones, relaciones y tendencias, y generar ideas y preguntas adicionales para explorar en estudios más detallados. 
Una vez realizado se pudieron obtener diversas conclusiones como: 
* A lo largo de los años se **incrementa el acceso y uso de internet** en los habitantes mediante distintas tecnologias que se van desarrollando.
* Las tecnologias mas empleadas para acceder a internet son **ADSL, Cablemodem y Fibra optica.**
* Todos los **barrios de CABA** tienen acceso a internet por todas las tecnologias disponibles.
* En **provincias mas rurales** se utiliza mas el tipo de tecnologia Wireless o Satelital para acceder a internet.
* La **velocidad media de bajada** a medida que pasan los años aumenta.
* Los **ingresos economicos tienen fluctuaciones fuertes** a pesar que las velocidades y accesos a internet aumentan.

# Dashboard  
  
Se reliazo un Dashboard en **Power BI** con el fin de visualizar los graficos que mas nos interesan y se establecieron **3 KPIs** que nos guiarán hacia el logro de nuestros objetivos estratégicos.  

**Los KPIs se enfocan en:**  
  
**Aumentar el ingreso anual a $1,600,000**   
**Aumentar los accesos a Internet por hogar a 12,000,000**  
**Aumentar el acceso a Internet por Fibra Óptica a nivel nacional a un 0.40**  
  
![Dashboard](https://github.com/Colombo02/Data-Analysis-ENACOM/blob/main/_src/Dashboard.png)  

**Aumento del Ingreso Anual**  
  
El primer KPI se centra en **aumentar nuestros ingresos anuales a usd$1.600.000 en el tiempo de un año**, lo que representa un crecimiento del **8.63% respecto al valor actual.**  

El primer pensamiento que se le puede venir a alguien es: **¿Queres generar mas ingresos? Llega a mas gente**, entre otros este es un pensamiento valido, pero esto por lo menos en Argentina no es tan asi. Si nos vamos al año **2017**, podemos ver como los **ingresos anuales son mayores a usd$2.000.000** y los **accesos por hogar son menores a 8.000.000**, esto se debe a, como es de publico conocimiento, la devaluacion del peso argentino y las politicas economicas de congelar los precios que decidio el gobierno. Esto lo que produce es que no se puedan hacer aumentos en las tarifas a cada usuario a medida que sube el dólar, lo que provoca un **claro descenso de los ingresos.**  

![Ingresos 2017](https://github.com/Colombo02/Data-Analysis-ENACOM/blob/main/_src/Ingresos_2017.png)
  
**Aumento de los Accesos a Internet por Hogar**   

El segundo KPI se enfoca en **aumentar los accesos a Internet por hogar a 12.000.000**, lo que requerirá un incremento del **7.57% en comparación con la cifra actual.**  
  
Como mencione antes, los accesos a internet no se ven directamente impactados en los ingresos de las empresas de comunicaciones, por lo menos en un corto plazo de algunos años. Hace 20 años, las personas se preguntaban ¿Que se puede hacer con el internet? Hoy en dia, la pregunta es **¿Que no se hace con el internet?** Hoy se compite por internet, se estudia, se trabaja, un medico te puede atender por internet, te podes comunicar, entre muchisimas mas cosas. Por estos motivos es necesario que **las personas puedan acceder a intenet** y cada vez mas, como podemos ver todos los años aumenta ya que hoy en dia, **si no tenes internet, te quedas afuera de muchas cosas en sentido social.** Hay provincias donde el acceso a internet fijo no pasa los 50 hogares cada 100, como lo son Corrientes, Santiago del Estero, Chaco, Formosa y Santa Cruz, en estas provincias hay que hacer un enfasis y mejorar estos numeros que nos van a permitir llegar al objetivo. 

**Aumento del Acceso a Internet por Fibra Óptica** 

El tercer KPI apunta a **aumentar el acceso a Internet por Fibra Óptica a nivel nacional a un 0.40**, lo que implica un incremento del **5.82% frente al valor actual.**  
  
La fibra optica permite una **excelente velocidad y estabilidad de internet**, lo cual perimite una mejor experiencia de los usuarios a la hora de acceder a internet fijo. 
Para alcanzar este objetivo, se evaluado la **penetración de la fibra óptica** en diferentes regiones y hemos identificado áreas donde se requieren mejoras en la infraestructura y el despliegue como por ejemplo Catamarca,  Corrientes, San juan, San luis, Tierra del fuego.  
  
## Conclusión  
  
Nuestros objetivos parecen ambiciosos dada las politicas economicas del pais pero **son alcanzables**. Queremos que las empresas de comunicaciones generen **mas ingresos y que la poblacion pueda acceder a un internet de calidad en cualquier lugar del pais.** 
**Soluciones propuestas** 
* Implementación de **promociones y descuentos estratégicos** para atraer nuevos clientes y retener a los existentes. 
* Desarrollo de nuevos paquetes de **servicios personalizados.**
* Expansión de la **infraestructura de banda ancha** en áreas con baja cobertura para llegar a más hogares y comunidades.
* Campañas de concientización sobre la **importancia y los beneficios del acceso a Internet** en el hogar para fomentar la adopción en áreas con baja penetración.
* Campañas de promoción y educación dirigidas a informar al público sobre las **ventajas de la fibra óptica** y su disponibilidad en sus regiones.

Estos KPIs nos guiarán a **mejorar el internet en todo el pais y en todos los aspectos**. Con la implementación de soluciones sólidas se puede conseguir e ir subiendo el objetivo de nuestros KPIs. 

## Herramientas Utilizadas 
**Python:** Lenguaje de programación principal utilizado en el desarrollo del proyecto.  
**Numpy:** Utilizado para realizar operaciones numéricas y manipulación de datos.   
**Pandas:** Utilizado para la manipulación y análisis de datos estructurados.   
**Matplotlib/Seaborn:** Utilizado para la visualización de datos y generación de gráficos en el EDA.   
**Power BI :** Generacion del Dashboard y analisis.  
  
## Linedin:  
[Linkedin](https://linkedin.com/in/tomascolombo/)  

**Tomás Colombo**
