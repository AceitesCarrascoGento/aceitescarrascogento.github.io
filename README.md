# Aceites Carrasco-Gento

App web para llevar el control del aceite: stock (cajas y garrafas), pedidos, cobros (efectivo/Bizum), clientes, gastos y ganancias.

- Funciona en cualquier navegador (móvil, tablet, ordenador) y se puede **instalar como app** con su icono.
- Funciona **sin conexión** (service worker).
- Los datos se guardan en el dispositivo y, si se vincula una cuenta de GitHub, se **sincronizan en la nube** (un Gist privado) entre todos los dispositivos.

## Uso
Abre la app desde GitHub Pages. Para instalarla:
- **Android / Chrome / Edge**: botón «Instalar app» o menú ⋮ → «Instalar aplicación».
- **iPhone / iPad**: en Safari, Compartir → «Añadir a pantalla de inicio».

## Sincronizar entre dispositivos
1. Botón «Guardado» → «Sincronizar entre dispositivos».
2. Crea una clave en <https://github.com/settings/tokens/new?scopes=gist&description=Aceites%20Carrasco-Gento> (solo permiso *gist*).
3. Pégala y pulsa «Vincular». En los demás dispositivos usa «Vincular otro dispositivo» para copiar un enlace que los vincula solos.

La clave solo se guarda en tus dispositivos; los datos van a un Gist **privado** de tu cuenta.
