# 🚀 Desafío Práctico: "La Landing Page de tu Evento Soñado"

## 📝 Escenario

Eres el desarrollador web principal encargado de lanzar el sitio para el evento más grande del año. Puede ser un concierto de rock, una convención de cómics, un torneo de E-sports o una feria de comida. Tu misión es maquetar una página atractiva, funcional y que se adapte a dispositivos móviles usando Bootstrap.

### 1. Configuración y Navbar
Instrucción:
1) Crea un archivo index.html y enlaza las librerías de Bootstrap (CSS y JS) vía CDN.

2) Implementa una Barra de Navegación (.navbar).

    * Debe tener un logotipo (o texto de marca) y enlaces a secciones como "Inicio", "Invitados", "Entradas" y "Contacto".

    * Requisito: La barra debe ser responsive y colapsar en un botón "hamburguesa" en pantallas pequeñas (usa .navbar-expand-{md|lg}).

    * Creatividad: Elige si usarás un esquema de colores oscuros (.navbar-dark .bg-dark) o claros.

### 2. La Sección Hero & Grid System
Instrucción:

1) Debajo del menú, crea una sección de bienvenida impactante.

2) Utiliza el Sistema de Grillas de 12 columnas.
    * Crea un contenedor (.container o .container-fluid).

    * Define una fila (.row) y divide el contenido en dos columnas para pantallas medianas/grandes (col-md-6 y col-md-6).

    * Columna Izquierda: Título grande del evento y un párrafo descriptivo.

    * Columna Derecha: Una imagen representativa del evento

3) Añade un Botón de "Comprar Entradas" en la columna izquierda. Usa las clases de estilo semántico (ej: `.btn-primary` o `.btn-success`).


### 3. Los Protagonistas (Cards)

Instrucción:

1) Crea una nueva fila para mostrar a los invitados especiales, productos o bandas.

2) Utiliza el componente Cards (.card), ya que son flexibles y extensibles.

3) Debes mostrar 3 tarjetas alineadas horizontalmente.

    * Pista: Recuerda que la suma de columnas debe ser 12. Si quieres 3 tarjetas, ¿de qué tamaño debe ser cada columna (col-md-?)?.

4) Cada tarjeta debe incluir: Imagen superior (.card-img-top), Título (.card-title), Texto breve y un botón de "Ver más".

### 4. Formulario e Interacción

Instrucción:

1) Al final, crea una sección de "Suscríbete a las novedades".
2) Implementa un Formulario sencillo (.form-group) que pida Correo Electrónico y un botón de "Enviar".

3) El Gran Final (JavaScript Components):
    * Haz que el botón de "Comprar Entradas" (del paso 2) o el de "Enviar" (del paso 4) active un Modal.

    * El Modal debe preguntar: "¿Estás seguro que deseas confirmar?" y tener botones de "Cancelar" y "Confirmar".

    * Extra: Añade un Tooltip a alguna imagen o enlace que diga "¡Cupos limitados!" al pasar el mouse por encima. Recuerda inicializarlo con JavaScript.

