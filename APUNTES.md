
# UNIDAD I. Introducción a la graficación por computadora.  
# 1.1. Historia y evolución de la graficación por computadora.

La graficación por computadora es una rama de la informática que se encarga de crear, modificar y representar imágenes mediante el uso de sistemas digitales. Su origen se remonta a la década de 1950, cuando las primeras computadoras comenzaron a mostrar gráficos simples en pantallas especiales. Uno de los avances más importantes ocurrió en 1963, cuando Ivan Sutherland desarrolló Sketchpad en el MIT, considerado uno de los primeros sistemas interactivos de diseño gráfico. Este programa permitió dibujar figuras geométricas usando un lápiz óptico, marcando el inicio del diseño asistido por computadora.



![2e239aaad977b0a7c8f0f082140c6557](https://github.com/user-attachments/assets/27371b3b-e95f-4ffa-8d0d-58ee3c6d70c1)


Durante las décadas de 1970 y 1980, la graficación por computadora comenzó a expandirse hacia el ámbito industrial y comercial. Centros de investigación como Xerox PARC desarrollaron tecnologías que influyeron en las interfaces gráficas modernas. En el cine, la película Tron fue pionera en el uso de imágenes generadas por computadora, demostrando el potencial artístico y visual de esta tecnología. En esta etapa también surgieron mejoras en el modelado tridimensional y en los algoritmos de sombreado, lo que permitió crear imágenes más complejas y realistas.

En la década de 1990, la graficación 3D experimentó un crecimiento acelerado gracias a los avances en hardware y software especializado. Un momento clave fue el estreno de Toy Story, producida por Pixar, que se convirtió en el primer largometraje completamente animado por computadora. Este logro marcó el inicio de una nueva era en la animación digital y consolidó el uso del renderizado realista, el texturizado avanzado y la animación por computadora como herramientas fundamentales en la industria del entretenimiento.

En el siglo XXI, la graficación por computadora ha alcanzado niveles de realismo impresionantes, integrando tecnologías como motores gráficos avanzados, renderizado en tiempo real y captura de movimiento. Películas como Avatar demostraron hasta dónde puede llegar el realismo digital. Actualmente, esta tecnología se aplica en videojuegos, arquitectura, ingeniería, medicina, educación y simulación científica, convirtiéndose en una herramienta esencial en múltiples áreas del conocimiento y la industria.

# 1.2. Áreas de aplicación.
La graficación por computadora tiene múltiples áreas de aplicación que han transformado distintos sectores productivos, científicos y educativos. Gracias al desarrollo del hardware y software especializado, hoy en día es una herramienta fundamental en diversos campos.

<img width="300" height="168" alt="image" src="https://github.com/user-attachments/assets/ad9e578e-1f21-4d5c-b3a4-6d84f4b6cc24" />

Una de las principales áreas es el **entretenimiento**, especialmente en el cine, la animación y los videojuegos. Películas como Toy Story y Avatar demostraron el potencial del modelado 3D, la animación digital y la captura de movimiento para crear mundos virtuales realistas. En los videojuegos, motores gráficos como Unreal Engine permiten generar entornos interactivos en tiempo real con alto nivel de detalle.
<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/f0684706-34e8-4b6e-b471-76108d32d70f" />


Otra área importante es la **ingeniería y la arquitectura**, donde se utilizan sistemas CAD (Diseño Asistido por Computadora) para diseñar planos, estructuras y modelos tridimensionales antes de su construcción. Programas como AutoCAD permiten realizar diseños precisos, simulaciones estructurales y visualizaciones realistas de proyectos.

En el campo de la **medicina**, la graficación por computadora se usa para crear imágenes médicas tridimensionales, simulaciones quirúrgicas y modelos anatómicos digitales. Esto facilita diagnósticos más precisos y mejora la planificación de procedimientos médicos.

También tiene gran impacto en la **educación y la investigación científica**, donde se emplea para simulaciones, visualización de datos complejos y recreaciones virtuales de fenómenos físicos, químicos o biológicos. Estas herramientas permiten comprender mejor conceptos abstractos mediante representaciones visuales interactivas.

Ademas en el ámbito de la **industria y la manufactura**, se utiliza para diseñar productos, realizar prototipos virtuales y simular procesos antes de la producción real, lo que reduce costos y errores. En conjunto, estas aplicaciones demuestran que la graficación por computadora no solo es una herramienta artística, sino también una tecnología esencial para el desarrollo científico, tecnológico y social.


# 1.3. Aspectos matemáticos de la graficación.
La graficación por computadora se fundamenta en diversos conceptos matemáticos que permiten representar objetos, transformarlos y visualizarlos en un entorno digital. Las matemáticas son esenciales para modelar formas, calcular posiciones, generar movimiento y producir imágenes realistas en dos y tres dimensiones.

Uno de los pilares fundamentales es el álgebra lineal, especialmente el uso de vectores y matrices. Los vectores permiten representar puntos, direcciones y movimientos en el espacio, mientras que las matrices se utilizan para realizar transformaciones como traslaciones, rotaciones y escalados. Mediante la multiplicación de matrices se pueden combinar varias transformaciones en una sola operación, lo que resulta fundamental en el modelado y la animación 3D.

Otro aspecto importante es la geometría analítica, que permite describir figuras mediante ecuaciones matemáticas. Por ejemplo, líneas, planos, circunferencias y superficies pueden representarse mediante fórmulas que la computadora interpreta para dibujar objetos. En gráficos 3D, los objetos suelen construirse a partir de polígonos (generalmente triángulos), definidos por coordenadas en el espacio tridimensional (x, y, z).
<img width="667" height="445" alt="image" src="https://github.com/user-attachments/assets/daebae8a-5b31-439a-93b5-f2fbfe04e8ce" />


La geometría proyectiva también juega un papel clave, ya que permite convertir escenas tridimensionales en imágenes bidimensionales mediante proyecciones (como la proyección en perspectiva). Esto hace posible simular la profundidad y la distancia, tal como las percibe el ojo humano.

Además, el cálculo diferencial e integral interviene en procesos como el suavizado de curvas (splines y superficies paramétricas), la simulación de movimiento y los efectos físicos. Por ejemplo, las ecuaciones diferenciales se emplean para simular fenómenos como la gravedad, el movimiento de partículas o la iluminación avanzada.

La trigonometría es esencial para calcular ángulos, rotaciones y direcciones, especialmente en animaciones y cámaras virtuales. Finalmente, la estadística y los métodos numéricos se utilizan en técnicas modernas como el renderizado estocástico y la simulación de iluminación global.

# 1.4. Modelos del color: RBG, CMY, HSV y HSL.
Los modelos de color son sistemas matemáticos que permiten representar colores de manera numérica en medios digitales o impresos. En la graficación por computadora, comprender estos modelos es fundamental para trabajar con iluminación, materiales y renderizado.

RGB (Red, Green, Blue)

El modelo RGB es un modelo aditivo, utilizado principalmente en pantallas (monitores, televisores, celulares).
Se basa en la combinación de tres colores primarios de luz:

Rojo (Red)

Verde (Green)

Azul (Blue)

Cada color se representa mediante valores que generalmente van de 0 a 255.
Por ejemplo:

(255, 0, 0) = Rojo puro

(0, 255, 0) = Verde puro

(0, 0, 255) = Azul puro

(255, 255, 255) = Blanco

Al combinar los tres colores en diferentes intensidades se generan millones de colores.

 CMY (Cyan, Magenta, Yellow)

El modelo CMY es un modelo sustractivo, utilizado en impresión.
Sus colores base son:

Cian

Magenta

Amarillo

Se llama sustractivo porque los colores funcionan absorbiendo (restando) luz. En impresión comercial se usa la versión extendida CMYK (agregando negro).

Relación básica:

CMY es el complemento de RGB.

Más tinta = menos luz reflejada.

 HSV (Hue, Saturation, Value)

El modelo HSV organiza el color de forma más intuitiva para los humanos:

Hue (Tono): el tipo de color (rojo, azul, verde), medido en grados (0°–360°).

Saturation (Saturación): intensidad o pureza del color.

Value (Valor): brillo o luminosidad.

Es muy usado en diseño digital porque facilita ajustar colores sin modificar su naturaleza principal.

HSL (Hue, Saturation, Lightness)

El modelo HSL es similar al HSV, pero usa:

Hue (Tono)

Saturation (Saturación)

Lightness (Luminosidad)

La diferencia principal es cómo se interpreta el brillo. HSL es más utilizado en diseño web y edición gráfica porque ofrece mejor control sobre la claridad del color.

Tutorial: Cómo iluminar un cubo y sus caras en Blender
Paso 1: Crear el cubo

Abrir Blender.

Presionar Shift + A → Mesh → Cube.

El cubo aparecerá en el centro de la escena.

Paso 2: Asignar colores diferentes a cada cara

Selecciona el cubo.

Presiona Tab para entrar en Edit Mode.

Cambia a selección de caras (tecla 3).

Selecciona una cara.

Ve al panel de Materiales (icono de esfera).

Presiona + para agregar un nuevo material.

Haz clic en New.

En el apartado Base Color, ajusta el color (modelo RGB o HSV).

Presiona Assign para aplicar el color a esa cara.

Repite el proceso con cada cara usando distintos colores.

 Paso 3: Agregar iluminación

Presiona Shift + A → Light → Point (o Sun).

Mueve la luz con la tecla G.

En el panel de propiedades de la luz:

Ajusta la Power (potencia).

Cambia el color si deseas.

Cambia a modo Rendered View para ver el resultado.
Paso 4: Mejorar el sombreado
Selecciona el cubo.
Clic derecho → Shade Smooth.

En el material, aumenta el valor de Roughness para hacerlo más mate.

Reduce Roughness para un efecto más brillante.
<img width="1310" height="816" alt="image" src="https://github.com/user-attachments/assets/3d8b94d9-b251-4212-90f9-67349eee2d59" />

# 1.5. Representación y trazo de líneas y polígonos.

En la graficación por computadora, las líneas y los polígonos son elementos básicos para construir imágenes y modelos en 2D y 3D.

Representación de líneas

Una línea se representa mediante dos puntos en el plano o en el espacio:

En 2D: (x₁, y₁) y (x₂, y₂)

En 3D: (x₁, y₁, z₁) y (x₂, y₂, z₂)

La computadora no dibuja una línea continua perfecta, sino que la forma usando píxeles (pequeños puntos en la pantalla). Para hacerlo, utiliza algoritmos matemáticos que determinan qué píxeles deben encenderse para que la línea se vea recta.

Uno de los algoritmos más conocidos es el algoritmo de Bresenham, que permite dibujar líneas de manera eficiente usando solo operaciones simples.

Representación de polígonos

Un polígono es una figura formada por varias líneas conectadas.
Está definido por una lista de vértices (puntos).

Ejemplo:

Un triángulo tiene 3 vértices.

Un cuadrado tiene 4 vértices.

En gráficos 3D, los objetos complejos se construyen principalmente con triángulos, porque son más fáciles de procesar matemáticamente.

  1.5.1 Formatos de imagen.
  <img width="1918" height="1023" alt="flor1" src="https://github.com/user-attachments/assets/0f82489e-555c-4e57-877b-32e5b53059a9" />

  
  <img width="1913" height="1022" alt="Flor 2" src="https://github.com/user-attachments/assets/0d5000f8-d160-4280-a78a-8526c10fc382" />

  
  <img width="1911" height="1019" alt="poligono" src="https://github.com/user-attachments/assets/0460c70a-3958-435c-830e-a4abee913f2b" />


# 1.6. Procesamiento de mapas de bits. 

El procesamiento de mapas de bits es una parte muy importante dentro de la graficación por computadora, ya que se encarga de trabajar con imágenes digitales formadas por píxeles. Un mapa de bits está compuesto por una cuadrícula de pequeños puntos llamados píxeles, y cada uno de ellos contiene información de color. La combinación de millones de estos píxeles permite formar fotografías, imágenes digitales y texturas que vemos en la pantalla. A diferencia de los gráficos vectoriales, que se basan en fórmulas matemáticas, los mapas de bits dependen directamente de la resolución, lo que significa que si se amplían demasiado pueden perder calidad y verse pixelados.

En este tipo de procesamiento se realizan diferentes modificaciones a nivel de píxel. Por ejemplo, se pueden ajustar el brillo y el contraste para mejorar la visibilidad de una imagen, cambiar los colores, aplicar filtros como desenfoque o nitidez, o convertir una imagen a escala de grises. Todos estos cambios se hacen mediante operaciones matemáticas que alteran los valores numéricos de cada píxel. También es común aplicar técnicas de compresión para reducir el tamaño del archivo sin perder demasiada calidad, lo cual es importante para ahorrar espacio y facilitar la transmisión de imágenes en internet.
<img width="266" height="189" alt="image" src="https://github.com/user-attachments/assets/e6dbd60f-8d10-44c2-81fb-2efa730c884e" />


El procesamiento de mapas de bits es muy utilizado en áreas como la edición fotográfica, el diseño gráfico, la animación y los videojuegos. En el modelado 3D, por ejemplo, las imágenes bitmap se usan como texturas que se colocan sobre objetos tridimensionales para darles mayor realismo. En conclusión, el procesamiento de mapas de bits permite mejorar, modificar y optimizar imágenes digitales, siendo una herramienta fundamental en la producción visual moderna.


<img width="296" height="171" alt="image" src="https://github.com/user-attachments/assets/2ef16d6d-9c92-410f-9c70-49382ab80409" />


# BIBLIOGRAFIAS
Hughes, J. F., van Dam, A., McGuire, M., Sklar, D. F., Foley, J. D., & Feiner, S. K. (2014). 

Computer graphics: Principles and practice (3rd ed.). Addison-Wesley.

Angel, E., & Shreiner, D. (2015). Interactive computer graphics: A top-down approach with 

WebGL (7th ed.). Addison-Wesley.

Shirley, P., Marschner, S., & otros. (2021). Fundamentals of computer graphics (4th ed.). CRC Press.

Sutherland, I. E. (1963). Sketchpad: A man-machine graphical communication system (Doctoral 
dissertation, Massachusetts Institute of Technology).

Hughes, J. F., van Dam, A., McGuire, M., Sklar, D. F., Foley, J. D., & Feiner, S. K. (2014). 

Computer graphics: Principles and practice (3rd ed.). Addison-Wesley.

Shirley, P., Marschner, S., & otros. (2021). Fundamentals of computer graphics (4th ed.). CRC Press.
Angel, E., & Shreiner, D. (2015). Interactive computer graphics: A top-down approach with WebGL (7th ed.). Addison-Wesley.

Hughes, J. F., van Dam, A., McGuire, M., Sklar, D. F., Foley, J. D., & Feiner, S. K. (2014). Computer graphics: Principles and practice (3rd ed.). Addison-Wesley.

Foley, J. D., van Dam, A., Feiner, S. K., & Hughes, J. F. (1996). Computer graphics: Principles and practice (2nd ed.). Addison-Wesley.

Shirley, P., Marschner, S., & otros. (2021). Fundamentals of computer graphics (4th ed.). CRC Press.

Angel, E., & Shreiner, D. (2015). Interactive computer graphics: A top-down approach with WebGL (7th ed.). Addison-Wesley.
