# 🛍️ Mini Tienda Online con POO y Patrones de Diseño

Este proyecto es una **demostración educativa** de cómo aplicar los principios de **Programación Orientada a Objetos (POO)** y tres patrones de diseño fundamentales en JavaScript: **Observer**, **Factory Method** y **Strategy**.

## 📁 Estructura del proyecto

Este proyecto está implementado en un solo archivo HTML para facilitar su ejecución y comprensión:


## 🎯 Objetivos

- Aplicar clases, herencia y encapsulación en JavaScript.
- Implementar los patrones de diseño:
  - **Observer**: notificaciones de eventos.
  - **Factory Method**: creación flexible de objetos.
  - **Strategy**: selección dinámica de métodos de pago.

## 🧠 Conceptos aplicados

### ✅ Programación Orientada a Objetos (POO)

- **Clases**: definición de `Producto`, `Libro`, `Laptop`, etc.
- **Herencia**: `Libro` y `Laptop` heredan de `Producto`.
- **Encapsulación**: se usan atributos privados `#nombre`, `#precio`.

### 🧩 Patrones de Diseño

#### 🔔 Observer
> Permite que objetos se suscriban a eventos sin estar acoplados entre sí.
- Clase: `Notificador`
- Método: `suscribir(fn)`, `notificar(mensaje)`
- Uso: Notifica cuando se agregan productos al carrito.

#### 🏭 Factory Method
> Crea objetos sin especificar la clase exacta que se va a instanciar.
- Clase: `FabricaProducto`
- Método: `crear(tipo, ...args)`
- Uso: Crea objetos tipo `Libro` o `Laptop` según el tipo solicitado.

#### 💳 Strategy
> Permite cambiar el algoritmo de pago en tiempo de ejecución.
- Estrategias: `PagoConTarjeta`, `PagoConPaypal`
- Contexto: `MetodoPago`
- Uso: El usuario puede pagar con diferentes métodos.

## ▶️ Cómo ejecutar el demo

1. Descarga o clona el repositorio.
2. Abre el archivo `index.html` en tu navegador.
3. Haz clic en el botón **"Ejecutar Demo"**.
4. Observa cómo se agregan productos, se notifica al usuario y se ejecuta un pago.


## 📚 Créditos y referencias

- [refactoring.guru - Patrones de Diseño](https://refactoring.guru/es/design-patterns)
- Actividad académica – Semana 11: Diseño Orientado a Objetos con UML III

---

⌨️ Desarrollado por: **[Tu Nombre]** – [UIDE / Ingeniería en TI]

