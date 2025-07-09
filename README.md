<div align="center">
  <p>Motor de Validación CFDI</p> 
  <p>Validación de Comprobantes Fiscales Digitales por Internet</p>

  <h3>Hecho por Luis Felipe Fernández Gurrola <h3>

  
  ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
  ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
  ![Shadcn/UI](https://img.shields.io/badge/Shadcn%2FUI-000000?style=for-the-badge&logo=shadcnui&logoColor=white)
  ![Font Awesome](https://img.shields.io/badge/Font%20Awesome-339AF0?style=for-the-badge&logo=fontawesome&logoColor=white)
  
  ![Version](https://img.shields.io/badge/version-1.0.0-blue.svg?style=flat-square)
  ![License](https://img.shields.io/badge/license-MIT-green.svg?style=flat-square)
  ![Status](https://img.shields.io/badge/status-active-success.svg?style=flat-square)
  ![Responsive](https://img.shields.io/badge/responsive-yes-brightgreen.svg?style=flat-square)
</div>

## Descripción

Sitio web para validar Comprobantes Fiscales Digitales por Internet (CFDI) tanto de manera individual como por lotes.

## Características

- **Validación Individual**: Ingreso manual de datos del CFDI
- **Validación Masiva**: Carga múltiples archivos XML via drag & drop
- **Tabla de Resultados**: Visualización clara de resultados de validación
- **Exportación CSV**: Exporta resultados con codificación UTF-8
- **Responsive**: Adaptado para móviles y desktop
- **Tiempo Real**: Validación instantánea con la API del SAT

## Tecnologías

- **Frontend**: HTML5, CSS3, JavaScript ES6+
- **UI Framework**: Shadcn/UI
- **Iconos**: Font Awesome 6.0
- **Tipografía**: Inter (Google Fonts)
- **API**: factura123.mx SAT validation API

## Uso

### Validación Manual
1. Selecciona la pestaña "Validación Manual"
2. Ingresa los datos del CFDI:
   - RFC Emisor
   - RFC Receptor
   - Total
   - UUID
3. Haz clic en "Validar CFDI"

### Validación por Lotes
1. Selecciona la pestaña "Validación por Archivos"
2. Arrastra archivos XML o haz clic para seleccionar
3. Haz clic en "Validar Archivos"
4. Exporta resultados a CSV si lo deseas

## Campos de Validación

| Campo | Descripción | Ejemplo |
|-------|-------------|---------|
| RFC Emisor | RFC de quien emite el comprobante | `EEC081222FH8` |
| RFC Receptor | RFC de quien recibe el comprobante | `XAXX010101000` |
| Total | Monto total del comprobante | `4182.00` |
| UUID | Identificador único del comprobante | `06632F3-EF6B-4B19-AD7E-6DB4B3BE7EDB` |

## Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

---

<div align="center">
  <p>Hecho por Luis Felipe Fernández Gurrola</p>
  <p>CFDI Validation Engine • Batch & Individual Processing</p>
</div>