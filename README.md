# Documentación del Proyecto: Landing Page

---

## Índice de Contenidos
1. [Introducción](#introducción)
2. [Estructura de la Landing Page](#estructura-de-la-landing-page)
3. [Visualización](#visualización)
4. [Tecnologías Empleadas](#tecnologías-empleadas)
5. [Codificación](#codificación)
6. [Despliegue](#despliegue)

---

## Introducción
"Mochila al hombro y pasaporte en mano, me lanzo a explorar los rincones más remotos del planeta. Desde las vibrantes ciudades hasta los paisajes más salvajes, mi pasión es descubrir nuevos lugares y compartir mis experiencias contigo. ¡Súbete a esta aventura y déjate contagiar por el espíritu viajero!"
---

## Estructura de la Landing Page
En esta seccion se describe la estructura general del blog viajero 
Header
Sección de banner
Sección de productos
Sección de noticias y contactos
Footer

---

## Visualización
Se detallan las consideraciones de diseño y calidady visibilidad del Blog viajeroincluyendo aspectos como:
Diseño responsivo
Paleta de colores
Tipografía
Imagenes y Multimedia



---

## Tecnologías Empleadas
herramientas utilizadas en el proyecto: 
 HTML, 
 CSS,  

---

## Codificación
<div class="travel-blog">
    <div class="travel-card">
        <img src="path-to-destination-image.jpg" alt="Imagen del destino" class="travel-image">
        <div class="travel-content">
            <h2 class="travel-title">Explorando Bali: Una Guía Completa</h2>
            <p class="travel-summary">Descubre lo mejor de Bali con esta guía de lugares imperdibles, consejos locales y todo lo que necesitas saber para tu próxima aventura.</p>
            <a href="#" class="read-more">Leer más</a>
        </div>
    </div>

    <div class="travel-card">
        <img src="path-to-destination-image2.jpg" alt="Imagen del destino" class="travel-image">
        <div class="travel-content">
            <h2 class="travel-title">Escapada a París: Los Mejores Secretos de la Ciudad del Amor</h2>
            <p class="travel-summary">Sumérgete en el encanto de París con recomendaciones exclusivas para explorar sus calles y lugares menos conocidos.</p>
            <a href="#" class="read-more">Leer más</a>
        </div>
    </div>
</div>

/* Sección del blog de viajes */
.travel-blog {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
    padding: 20px;
    background-color: #f0f8ff;
}

.travel-card {
    width: 300px;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s;
    background-color: #fff;
}

.travel-card:hover {
    transform: translateY(-5px);
}

.travel-image {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.travel-content {
    padding: 15px;
}

.travel-title {
    font-size: 1.5em;
    margin: 0;
    color: #2c3e50;
}

.travel-summary {
    font-size: 1em;
    color: #4d4d4d;
    margin: 10px 0;
}

.read-more {
    display: inline-block;
    padding: 8px 15px;
    margin-top: 10px;
    background-color: #ff6b6b;
    color: #fff;
    text-decoration: none;
    border-radius: 4px;
    transition: background-color 0.3s;
}

.read-more:hover {
    background-color: #e14e4e;
}


---

## Despliegue
[Landing page](https://coruscating-nasturtium-35ad4e.netlify.app)
