<h1 align=center> Proyecto de Data Analytics</h1>
<h2 align=center><strong>Siniestros Viales</strong></h1>
<hr><p align=center><img src="./data/assets/sin-vial-jpg.png" height=200></p>
<hr></hr>

<p> En este proyecto analizaremos los siniestro viales que tuvieron lugar en la Ciudad de Buenos Aires entre 2016-2021. Los datos con los que se hace el análisis de este proyecto se pueden obtener en la <em><a href="https://databuenosairesgobardatasetvictimas-siniestros-viales">página oficial de la Ciudad de Buenos Aires</a></em>.</p>

<p align=center><img src="./data/assets/caba-logo.png" height=200></p>

<h2 align=center>Contenido</h2>
<li><a href="#introduccion">Introducción.</a></li>
<li><a href="#instalacion">Instalación.</a></li>
<li><a href="#uso">Uso.</a></li>
<li><a href="#repositorio">Repositorio.</a></li>
<li><a href="#contacto">Contacto.</a></li>

<hr><h3 id="introduccion"><strong>Introducción</strong></h3>
<p>Para analizar este proyecto sobre los siniestros viales sucedidos en la Ciudad de Buenos Aires tenemos que conocer un poco el contexto de la ciudad la cual analizaremos.</p>
<p>Esta ciudad se encuentra en Argentina, tiene una superficie de 200km, tiene más de tres millones de habitantes. La infraestructura vial de la ciudad es "segura", según un <a href="https://buenosaires.gob.ar/movilidad/plan-de-seguridad-vial/infraestructura-segura"> posteo en la página oficial de la ciudad</a>, en el cual nos informan de la forma en la que la ciudad está diseñada para prevenir la cantidad de víctimas mortales en accidentes.</p>
<p align=center><img src="./data/assets/logo-buenos-aires-ciudad-vectores.webp" height=200></p>
<p><em>Otros links de interés:</em></p>
<li><a href="https://twitter.com/batransito">Twitter de BA-Tránsito</a></li>
<li><a href="https://buenosaires.gob.ar/movilidad/plan-de-seguridad-vial">Portal de la Ciudad de Buenos Aires</a></li>
<hr>
<h3 id='instalacion'><strong>Instalación</strong></h3>
<p>Para poder acceder a este proyecto, debe tener <strong>GIT</strong> en su dispositivo.</p>
<p>Navegue en su computadora a través de la terminal con:</p>
<code>cd Escritorio/Mi-Carpeta/Mis-Proyectos</code>
<p>Dentro de la terminal con <strong>GIT</strong> instalado, ejecute el siguiente comando: </p>
<code>git clone https://github.com/Mariagustin-Prg/Siniestros-PIDA</code>
<li>Si no tiene instalado <strong>GIT</strong>, acceda a su instalación a través de la <a href="https://git-scm.com/downloads">página de descarga de GIT</a>.</li>

<p align=center><img src="./data/assets/logo@2x.png" height= 20></p>

<hr>
<h3 id="uso">Uso</h3>
<p>Puede acceder a este repositorio utilizando su editor de código favorito. Puede hacer su propio análisis con jupyter notebooks u otros archivos.</p>
<p><em><strong>Recomendación:</strong> Cree un entorno virtual que contenga las librerías necesarias que se utilizan en este proyecto.</em></p>
<p><em>Para poder crear un entorno virtual:</em></p>
<code>py -m venv entorno-virtual
</code>
<p><em>Para instalar las librerías necesarias:</em></p>
<code>pip install -r requirements.txt
</code>
<p>Las herramientas que se utilizan:</p>
<p align=center><img src="./data/assets/jupyter-icon.png" height=60>  <img src="./data/assets/py-icon.png" height=60>  <img src="./data/assets/pandas-logo.png" height= 60>  <img src="./data/assets/plt-logo.png" height=40>  <img src="./data/assets/seaborn-icon.png" height=60></p>
<hr>
<h3 id="repositorio">Repositorio</h3>
<p>En este repositorio hay diferentes archivos, a continuación describiremos que contiene cada uno.</p>
<h4><em>.gitignore</em></h4>
<p>En este archivo podemos encontrar el nombre de la carpeta del entorno virtual con el que se hizo este proyecto.</p>

<h4><em><a href="Exploratory-Data-Analysis.ipynb">Exploratory-Data-Analysis.ipynb</a></em></h4>
<p>Este es el archivo principal del repositorio. En este notebook está todo el análisis de los datos, con los KPI's incluidos en la última sección del notebook.

<h4><em><a href="homicidios.xlsx">homicidios.xlsx</a></em></h4>
<p>Este es la base de la cual se sacaron construyó todo el proyecto. El archivo del cual se obtuvieron todos los datos que luego se analizaron y utilizaron en el resto de archivos.</p>

<h4><em><a href="intro.ipynb">intro.ipynb</a></em></h4>
<p>En este notebook se hace la apertura del excel, también la segmentación de los datos en la carpeta <a href="./data"><em>data</em></a>.

<h4><em><a href="Pre-analysis.ipynb">Pre-Analysis.ipynb</a></em></h4>
<p>En este notebook se hacen consultas a los archivos csv, que sirvieron para entender los datos y posteriormente analizarlos en el <a href="Exploratory-Data-Analysis.ipynb">EDA</a>.</p>

<h4><em><a href="requirements.txt">requirements.txt</a></em></h4>
<p>Aquí se encuentran las librerías que fueron utilizadas en este proyecto. También es util para instalar todas las librerías juntas que se utilizaron desde una terminal</p>

<hr>
<h3 id="contacto">Contacto</h3>
<p><img src="./data/assets/Gmail-Logo.png" height=20><a href="mariagustin.acosta1703@gmail.com">Gmail</a></p>

<p><img src="./data/assets/Linkedin-logo-on-transparent.png" height=30><a href="https://www.linkedin.com/in/mariano-agust%C3%ADn-acosta-chico-b67584266">Mariano Agustín Acosta Chico</a></p>

<p><img src="./data/assets/instagram-logo.png" height=30><a href="https://www.instagram.com/mariagustin_017/">@mariagustin_017</a></p>

<p><img src="./data/assets/github-logo.jfif" height=25><a href="https://github.com/Mariagustin-Prg">@Mariagustin-Prg</a></p>
