# Integración de prueba – Khipu (DemoBank)

Este repositorio contiene la simulación técnica del proceso de integración de pagos utilizando el entorno de pruebas (sandbox) de Khipu y DemoBank, como parte de un proceso de selección.

---

## 🎯 Objetivo

Demostrar el flujo completo de integración API:
- Generación de cobro
- Envío de enlace de pago
- Pago simulado desde cliente
- Confirmación de pago

---

## 🔄 Pasos realizados

1. Ingreso a la cuenta de desarrollador en el portal de Khipu.
2. Creación de un nuevo cobro por $3.000 dirigido al cliente ficticio.
3. Envío automático del enlace de pago al correo del cliente.
4. Acceso al `payment_url` desde la cuenta del cliente.
5. Simulación del pago utilizando DemoBank.
6. Confirmación automática del cobro en la cuenta del desarrollador.
7. Visualización del comprobante y del estado de cobro como “pagado”.

---

## 🧪 Entorno de prueba utilizado

- Plataforma: [https://khipu.com](https://khipu.com)
- Modo: **Desarrollador (sandbox)**
- Banco simulado: **DemoBank**

---

## 🧩 Roles simulados

| Rol                        | Identidad usada                          |
|---------------------------|-------------------------------------------|
| Desarrollador / Intermediario | `henry.lopez.h@gmail.com`              |
| Comercio / Empresa         | `henry.lopez.h@gmail.com` (cuenta ficticia de cobro) |
| Cliente / Pagador          | `henry_16_31@hotmail.com` (Esmeralda Gravlin)    |

---

## 🎬 Video de la simulación

📺 Ver el video completo con subtítulos aquí:  
🔗 [Ver en Google Drive](https://drive.google.com/file/d/1AE1MaDaFR8K_2J0q59gRglFza1y2Dcad/view?usp=sharing)
---

## 📝 Notas

- La simulación fue realizada exclusivamente en entorno sandbox de Khipu.
- No se utilizaron cuentas productivas reales ni se procesaron transacciones monetarias reales.
- Todos los datos (correos, nombres, montos) fueron usados solo con fines demostrativos.

---
