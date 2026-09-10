# Brief para colaboradores — Landing ReVibe

Cópienlo/péguenlo como contexto cuando empiecen a trabajar (sirve como prompt para su asistente de IA o como onboarding rápido).

---

## El proyecto

Estamos armando **ReVibe**, un marketplace para vender y comprar ropa de segunda mano en México. Esto que van a tocar es la **landing de lista de espera** del pre-lanzamiento: una sola página cuyo trabajo es convencer a alguien de dejar su nombre y correo antes de que salga la app.

El mensaje central es **"Tu clóset vale más"**: la idea de que la ropa que ya no usas tiene valor y ReVibe te lo paga, sin comisión para los primeros usuarios.

## Qué necesitamos de ustedes

Van a hacer modificaciones sobre la página (`index.html`). Puede ser copy, secciones, ajustes visuales o de animación — según lo que se les asigne. Trabajen sobre el archivo `index.html`; todo (HTML, estilos y JavaScript) está adentro de ese único archivo, sin build ni dependencias.

## Cómo arrancar (5 minutos)

1. **Descarguen el repo**: botón verde **Code → Download ZIP**, o `git clone <URL>`.
2. Abran `index.html` con doble clic para verla, y con **VS Code** para editarla.
3. Hagan su cambio, guarden, refresquen el navegador. Listo — así de simple.

Lean el `README.md` para la estructura del archivo y las reglas de marca antes de mover cosas.

## Lo que NO se toca

- La tipografía y el kerning del logo **ReVibe** (letra por letra).
- La paleta de marca: coral, naranja, teal. Nada de otros colores sin avisar.
- Las constantes del formulario (`FORM_ENDPOINT`, `F_EMAIL`, `F_NOMBRE`, `F_REF`): están conectadas a la base de datos real de registros. Si las cambian, dejamos de recibir a la gente que se apunta.

## Regla de oro del copy

**Poco texto, que pegue.** La página no es un folleto: es un gancho. Si una frase se puede decir en menos palabras, se dice en menos palabras.

## Cuando terminen

No publiquen ustedes. Manden su `index.html` modificado o su Pull Request y Adrián coordina el deploy a Cloudflare (donde está hospedada la página en vivo).
