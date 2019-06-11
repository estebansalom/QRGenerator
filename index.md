# Códigos QR

### Definición

Su nombre proviene del inglés “Quick Response Code”. Es un código bidimensional de forma cuadrada que puede almacenar datos codificados. La información se almacena en un módulo formado por una matriz de puntos o en un código de barras bidimensional. Pueden presentarse en forma impresa o en pantalla. Fue creado en 1994 por la compañía japonesa Denso Wave (una subsidiaria de la Toyota), por un grupo de personas dirigidas por Masahiro Hara. Son muy eficientes para codificar caracteres Kanji, lo que los hace muy populares en Japón. Su objetivo era crear un código que fuera de respuesta rápida o sea que se pueda codificar a una alta velocidad.

Su antecesor, el código de barras (creado en los 50) solo es capas de almacenar 20 dígitos. Para el código QR el almacenamiento puede ser de varios miles de dígitos (7.089 caracteres). Tiene además, la característica de ser muy accesible, a diferencia del tradicional, puede funcionar con dispositivos al alcance de la mano, como un móvil o una webcam que ya tienen implementados un programa especial para leerlos. Básicamente cualquier aparato capaz de captar imágenes que cuente con el software adecuado puede leer y acceder a la información de un código QR. Es capaz de codificar todos los caracteres ASCII además de información binaria y es omnidireccional.

Los nuevos códigos son utilizados en cada vez más utilidades y productos, como un pasaje de avión, codificar la información sobre webs, promociones, publicidad, organización de inventarios, entradas a eventos, mensajes, etc. Estos códigos 2D (de información horizontal y vertical) son los denominados: Maxicode, Datamatrix (Semacode), PD417 y el QR.

Una variante de estos códigos 2D son los denominados “shotcode” o códigos de barras circulares, creado en la Universidad de Cambridge en 1999\. Estas secuencias circulares, de bloques blancos y negros, representan URL’s, como por ejemplo un sitio WAP con una promoción o un punto de venta de productos. Pueden leerse de igual forma por dispositivos que tengan integrados el lector de códigos correspondiente y se pueden crear en el sitio http://www.shotcode.org.

### Características Generales y Aplicaciones

Su primer uso dentro de la compañía Denso Wave era la de registrar repuestos en el área de la fabricación de vehículos. Actualmente se usan para administrar los inventarios de innumerables industrias. A pesar de su versatilidad, apenas se está explotando su gran potencial. Los nuevos usos planean estar mas orientados al usuario, dándole la comodidad de almacenar información dentro de sus celulares ya sin tener que realizarlo manualmente. En Japón muchas de las revistas y anuncios los implementas de manera común, en las paradas se utilizan para dar indicación de horarios y en los museos se utilizan para dar información sobre las obras o monumentos. En las tarjetas de visita, los códigos QR simplifican en gran medida la tarea de introducir detalles de cada nuevo cliente en la agenda de un teléfono móvil.

El estándar en Japón para códigos QR (JIS X 0510) fue publicado en enero de 1999 y el estándar ya a nivel internacional ISO (ISO/IEC18004) se aprobó un año después, en junio del 2000\. Su capacidad viene del análisis según el tipo de información que se desea almacenar, puesto que varía según el tipo de caracteres que se quieran implementar.

Capacidad máxima de datos del código QR

<table border="1px">

<thead></thead>

<tbody>

<tr>

<td>Solo numericos</td>

<td>7.089 caracteres</td>

</tr>

<tr>

<td>Alfanumericos</td>

<td>4.296 caracteres</td>

</tr>

<tr>

<td>Binario (8 bits)</td>

<td>2.953 bytes</td>

</tr>

<tr>

<td>Kanji/Kana</td>

<td>1.817 caracteres</td>

</tr>

<tr>

<td>Micro código QR</td>

<td>35 caracteres</td>

</tr>

</tbody>

</table>

Capacidad de corrección de errores

<table border="1px">

<thead></thead>

<tbody>

<tr>

<td>Nivel L</td>

<td>7% de las claves se pueden restaurar</td>

</tr>

<tr>

<td>Nivel M</td>

<td>15% de las claves se pueden restaurar</td>

</tr>

<tr>

<td>Nivel Q</td>

<td>25% de las claves se pueden restaurar</td>

</tr>

<tr>

<td>Nivel H</td>

<td>30% de las claves se pueden restaurar</td>

</tr>

</tbody>

</table>

Al expresar los datos en direcciones, el código se puede representar en una décima del espacio que ocuparía un código tradicional de barras. Pueden corregirse errores y pueden restaurarse los datos si alguna parte del código se daña. Como máximo permite restaurar hasta un 30%. Su rápida decodificación tiene la capacidad innovadora de ser leído desde todas las direcciones en 360°.

<div>![explicacionQR](../QRGenerator/1280px-QR_Format_Information.png)</div>

##### Figure 1 Cómo seer la información de un código QR

Cuando se reproduce un código QR en cualquier superficie, según las especificaciones técnicas de Denso Wave, se debe dejar alrededor del mismo un espacio de reserva conocido como “quite zone” que equivale a 4 módulos ( o sea un cuadrado mínimo presente en cada QR) para que el lector lo ubique y lea correctamente.

<div>![explicacionQR](../QRGenerator/Código_QR_Ejemplo_de_Estructura.svg.png)</div>

##### Figure 2 Estructura de un código QR

### Cómo generar un código QR

Hay una gran cantidad de programas para generarlos de forma automática. Una de estas Webs donde se puede realizar la codificación de cualquier texto, número o URL es Kaywa: http://qrcode.kaywa.com donde también se puede descargar un software en Java para tener un lector en cualquier celular. Es recomendable porque es muy amigable, con un formularios que nos permite configurar casi todos los aspectos, ya sea que queramos codificar una URL, un texto, número de teléfono o un SMS. Tiene desde luego sus limitaciones, pudiendo solo generar un poco más de 250 caracteres.

QRCode para Java http://qrcode.sourceforge.jp es una librería que nos permitirá incluir soporte tanto para codificar como para decodificar códigos QR. Incluye su soporte para la corrección de errores y algunas otras aplicaciones interesantes. PyQrCodec http://www.pedemonte.eu:81/pyqr/index.py/pyqrhome Un módulo para decodificar imágenes con códigos QR en Python. Disponible para Windows y Linux.

QRmaker Pro: Esta es una aplicación diseñada por los creadores del código QR, para crear y controlar este tipo de código en aplicaciones. Funciona por medio de un control de ActiveX.

Invx http://invx.com Crea códigos desde el navegador. Sus opciones son limitadas pero nos da la posibilidad de integrar la conversión con nuestro propio sitio.

### Nu-Get's Utilizados

- MessagingToolkit.QRCode
- AForge
- AForge.Video
- AForge.Video.DirectShow
- ZXing

<div><iframe width="560" height="315" src="https://www.youtube.com/embed/i_yuG9CwzNY" frameborder="0"></iframe></div>

<div><iframe width="560" height="315" src="https://www.youtube.com/embed/j9i1zRJyihY" frameborder="0"></iframe></div>

### QR y Visual Studio

Video-Crear código QR con c# y Visual Studio - rápido y con código incluido:

<nav>[https://www.youtube.com/watch?v=UUr7fjVq9Xg](https://www.youtube.com/watch?v=UUr7fjVq9Xg)</nav>

Este es un pequeño programa que permite generar códigos QR y guardarlos con extensión de imagen .jpg, .png, .bmp, .gif, .tif e .ico.

<nav>[https://mega.nz/#!tRdTGKbS!NwpIXrpfI1e9PXgh5_Ac8DEw51FwhTsCoawjQ_GDtlA](https://mega.nz/#!tRdTGKbS!NwpIXrpfI1e9PXgh5_Ac8DEw51FwhTsCoawjQ_GDtlA)</nav>

Generates QR code and save as transparent GIF

<nav>[https://marketplace.visualstudio.com/items?itemName=Compulim.vscode-qrcode](https://marketplace.visualstudio.com/items?itemName=Compulim.vscode-qrcode)</nav>
