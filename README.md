# 🔧 Sistema de Mantenimiento Predictivo Industrial

Plataforma para el **monitoreo de equipos industriales**, detección temprana de fallas mediante **Machine Learning**, gestión de órdenes de trabajo e inventario de repuestos.

## 🎯 Objetivo

- Monitorear el estado de los equipos mediante sensores.
- Detectar anomalías y posibles fallas.
- Reducir paradas no planificadas y costos de mantenimiento.
- Gestionar órdenes de mantenimiento.
- Controlar el inventario de repuestos.
- Generar indicadores para apoyar la toma de decisiones.

## 📌 Módulos principales

### 📡 Monitoreo
- Registro de equipos y sensores.
- Lectura de temperatura, vibración, presión, etc.
- Visualización del estado de los equipos.
- Configuración de alertas y umbrales.

### 🤖 Predicción de fallas
- Análisis de datos de sensores.
- Detección de anomalías con Machine Learning.
- Generación de alertas.
- Predicción de posibles fallas.

### 🛠️ Órdenes de trabajo
- Creación y asignación de órdenes.
- Mantenimiento preventivo, predictivo y correctivo.
- Seguimiento del estado de las órdenes.
- Registro de actividades y repuestos utilizados.

### 📦 Inventario
- Registro de repuestos.
- Control de existencias.
- Descuento automático de repuestos utilizados.
- Alertas por bajo inventario.

### 📊 Indicadores
- MTBF.
- MTTR.
- Disponibilidad de equipos.
- Historial de fallas y mantenimientos.

## 🔐 Seguridad

El sistema contará con **autenticación y control de acceso por roles**, como:

- Administrador
- Técnico
- Supervisor
- Responsable de inventario
- Analista

## 🛠️ Tecnologías

El proyecto contempla el uso de:

- **Backend:** API y lógica de negocio.
- **Base de datos:** Relacional o NoSQL.
- **IoT:** Recepción de datos de sensores.
- **Machine Learning:** Predicción y detección de anomalías.
- **Frontend:** Dashboard para equipos, alertas y órdenes.
- **Notificaciones:** Alertas de fallas y mantenimiento.

## 👥 Ejemplo de funcionamiento

1. Un sensor registra un comportamiento anormal.
2. El sistema analiza los datos mediante Machine Learning.
3. Se genera una alerta de posible falla.
4. El supervisor crea una orden de trabajo.
5. El técnico realiza el mantenimiento.
6. Los repuestos utilizados se descuentan del inventario.
7. Los resultados quedan registrados para futuros análisis.

## 📌 Estado del proyecto

🟡 **En desarrollo**

Actualmente se encuentra en la fase de **diseño funcional y definición de arquitectura**. Posteriormente se implementarán los módulos, base de datos, APIs, Machine Learning e integración con sensores.
