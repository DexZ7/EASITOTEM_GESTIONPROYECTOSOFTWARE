# Integración con Setmore

## Descripción

Setmore se utiliza como sistema externo para la gestión de reservas.

## Implementación

La integración actual se realiza mediante redirección directa:

```html
<button onclick="goToBooking()">Reservar</button>

<script>
function goToBooking() {
  window.location.href = "https://setmore.com/tu-link";
}
</script>