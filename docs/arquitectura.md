# Arquitectura

## Estructura del proyecto
El proyecto sigue una arquitectura web estática basada en tecnologías frontend.

- **HTML5**: define la estructura y contenido de la página.
- **CSS3**: controla el diseño visual, estilos, animaciones y diseño responsive.
- **JavaScript**: se utiliza para la interacción del menú en dispositivos móviles.

## Diseño responsive
Se utilizan media queries para adaptar la visualización a:
- Escritorio
- Tablet
- Móvil

En móvil usamos `mobile-header` y en escritorio `nav`:

```html
			<div class="mobile-header">
				<button class="menu-toggle" aria-label="Abrir menú">
					<i class="fa-solid fa-bars"></i>
				</button>
				<div class="logo">
					<img src="Recursos/logo/logo-med.png">
				</div>
			</div>

			<div class="nav">
				<ul>
					<li><a href="#">Bicicletas</a></li>
					<li><a href="#">Accesorios</a></li>
					<li><a href="#">Mis reservas</a></li>
					<li><a href="#">Contacto</a></li>
					<li><a href="#"><i class="fa-solid fa-user"></i> Login</a></li>
				</ul>
			</div>
```


## Tecnologías utilizadas
| Tecnología   | Función                      |
|--------------|------------------------------|
| HTML5        | Estructura del contenido     |
| CSS3         | Estilos, diseño y responsive |
| Font Awesome | Iconos                       |
| JavaScript   | Interacción del menú móvil   |

[⬅ Volver al índice](index.md)



