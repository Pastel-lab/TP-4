# TP 4 - Navegación y Usabilidad

## Datos del Estudiante
- **Nombre y Apellido:** Tomás Brusa
- **Curso:** 6° G
- **Materia:** Laboratorio de Programación
- **Temática elegida:** Boca Juniors

## Principios de Usabilidad de Steve Krug aplicados:
1. **Logo de retorno rápido:** Ubiqué el escudo oficial de Boca arriba a la izquierda. Al clickearlo, redirige siempre al inicio (`index.html`).
2. **"Usted está aquí" visible:** En el menú, utilicé la clase `class="activo"` para destacar con fondo color Oro la sección actual donde está el usuario navegando.
3. **Eliminación del ruido:** No utilicé banners eternos de bienvenida. El contenido va directo a lo importante para que el usuario encuentre todo al instante.

## Estados de los Enlaces en CSS:
Personalicé cada uno de los estados obligatorios para evitar los azules genéricos de internet:
- **`:link` (No Visitado):** Color blanco para el menú principal para destacar de forma limpia.
- **`:visited` (Visitado):** Cambia a un gris sutil (`#e2e8f0`) para guiar la navegación del usuario de manera amigable.
- **`:hover` (Puntero encima):** Aplica un fondo de color Oro y texto Azul con excelente contraste visual.
- **`:active` (Click pulsado):** El color del fondo cambia a un oro más oscuro para dar feedback físico inmediato.
