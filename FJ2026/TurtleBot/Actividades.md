# 🧠 Servicio Becario  
# Programación de Robot Móvil TurtleBot con ROS  
### Modalidad: Proyecto en Equipos (definidos por el profesor)

---

## 👥 Organización del Proyecto

- El proyecto se desarrollará en **equipos definidos por el profesor**.
- Cada equipo deberá:
  - Distribuir roles técnicos internos.
  - Mantener un repositorio colaborativo (Git).
  - Documentar decisiones técnicas.
  - Entregar avances semanales.
  - Realizar pruebas integradas periódicamente.

### Roles sugeridos dentro del equipo

- 🔧 **Líder técnico:** Arquitectura del sistema y navegación.
- 🧭 **Responsable de SLAM y localización.**
- 💻 **Responsable de interfaz y experiencia de usuario.**
- 📄 **Responsable de documentación e integración.**


---

## 🎯 Objetivo General

Desarrollar un sistema completo y funcional para un TurtleBot utilizando ROS, de manera que:

- El robot pueda mapear, localizarse y navegar.
- El sistema sea robusto y tolerante a fallos básicos.
- Cualquier persona pueda usarlo mediante una interfaz sencilla.
- El sistema pueda instalarse siguiendo un manual claro.

---

# 📅 Plan de Trabajo – 12 Semanas

---

## 🔹 Semana 1 – Fundamentos y Arquitectura del Sistema

**Objetivo:** Comprender la arquitectura de ROS y definir la estructura del proyecto.

**Actividades:**
- Instalación y verificación de ROS.
- Repaso de nodos, topics, servicios y launch files.
- Definir arquitectura modular del sistema.
- Crear repositorio del equipo.

**Entregable:**
- Documento: Arquitectura propuesta del sistema.
- Repositorio inicial estructurado.
- Video corto mostrando comunicación entre nodos.

**Fecha Entregable:** 03 de marzo 2026

---

## 🔹 Semana 2 – Control Básico del Robot

**Objetivo:** Lograr control manual y crear un nodo propio de movimiento.

**Actividades:**
- Uso de `teleop`.
- Publicación en `/cmd_vel`.
- Desarrollo de nodo propio de control.

**Entregable:**
- Nodo funcional documentado.
- Video demostración de movimiento controlado.

**Fecha Entregable:** 10 de marzo 2026

---

## 🔹 Semana 3 – Sensores y Visualización

**Objetivo:** Integrar y analizar datos del LiDAR y/o cámara.

**Actividades:**
- Suscripción a `/scan`.
- Visualización en RViz.
- Procesamiento básico de datos.

**Entregable:**
- Nodo que detecte distancia mínima.
- Documento técnico explicando el flujo de datos.

**Fecha Entregable:** 17 de marzo 2026
---

## 🔹 Semana 4 – Evasión Autónoma de Obstáculos

**Objetivo:** Implementar comportamiento reactivo.

**Actividades:**
- Desarrollo de algoritmo de evasión.
- Validación experimental.
- Pruebas iterativas.

**Entregable:**
- Nodo autónomo funcional.
- Video demostración de navegación reactiva.

**Fecha Entregable:** 24 de marzo 2026

---

## 🔹 Semana 5 – Mapeo (SLAM)

**Objetivo:** Generar mapa del entorno.

**Actividades:**
- Uso de `gmapping` o `slam_toolbox`.
- Generación y guardado del mapa.

**Entregable:**
- Archivos `.pgm` y `.yaml`.
- Documento explicando el procedimiento.

**Fecha Entregable:** 07 de abril 2026

---

## 🔹 Semana 6 – Localización (AMCL)

**Objetivo:** Ubicar el robot dentro del mapa generado.

**Actividades:**
- Configuración de AMCL.
- Ajuste de parámetros.
- Validación en RViz.

**Entregable:**
- Demostración funcional de localización.
- Documento técnico de configuración.

**Fecha Entregable:** 14 de abril 2026

---

## 🔹 Semana 7 – Navegación Autónoma

**Objetivo:** Navegar hacia metas definidas.

**Actividades:**
- Configuración de `move_base`.
- Envío de goals.
- Pruebas en entorno real.

**Entregable:**
- Video navegando a múltiples destinos.
- Launch file completo de navegación.

**Fecha Entregable:** 21 de abril 2026

---

## 🔹 Semana 8 – Desarrollo de Interfaz de Usuario

**Objetivo:** Permitir uso sencillo por terceros.

**Opciones:**
- Interfaz web (ROSBridge + Flask).
- Interfaz gráfica (PyQt / rqt).
- Dashboard simplificado.

**La interfaz debe incluir:**
- Botón iniciar sistema.
- Botón detener sistema.
- Envío de destino.
- Visualización básica de estado.

**Entregable:**
- Interfaz funcional.
- Manual rápido de uso (1 página).

**Fecha Entregable:** 28 de abril 2026

---

## 🔹 Semana 9 – Automatización del Sistema

**Objetivo:** Arranque completo con un solo comando.

**Actividades:**
- Launch maestro.
- Script de inicio automático.
- Gestión de dependencias.

**Entregable:**
- Script único de ejecución.
- Documento `INSTALL.md` detallado.

**Fecha Entregable:** 05 de mayo 2026

---

## 🔹 Semana 10 – Robustez y Manejo de Fallos

**Objetivo:** Hacer el sistema tolerante a errores.

**Actividades:**
- Manejo de pérdida de sensor.
- Validación de estados del sistema.
- Registro de logs.

**Entregable:**
- Documento de pruebas realizadas.
- Sistema estable bajo pruebas controladas.

**Fecha Entregable:** 12 de mayo 2026

---

## 🔹 Semana 11 – Documentación y Replicabilidad

**Objetivo:** Que cualquier persona pueda instalar y usar el sistema.

**Estructura mínima del repositorio:**
turtlebot_project/ <br>
│<br>
├── src/<br>
├── launch/<br>
├── maps/<br>
├── config/<br>
├── scripts/<br>
├── ui/<br>
├── README.md<br>
├── INSTALL.md<br>
└── USER_GUIDE.md<br>


**Entregable:**
- Repositorio final organizado.
- Manual técnico completo.
- Manual de usuario no técnico.

**Fecha Entregable:** 19 de mayo 2026

---

## 🔹 Semana 12 – Validación Final y Presentación

**Objetivo:** Validar usabilidad con usuario externo.

**Actividades:**
- Prueba con estudiante ajeno al equipo.
- Corrección de errores detectados.
- Preparación de presentación final.

**Entregables finales:**
- Robot completamente funcional.
- Interfaz operativa.
- Documentación completa.
- Video demostración final.
- Presentación técnica (20 minutos).

**Fecha Entregable:** 26 de mayo 2026

---

# 📊 Criterios de Evaluación

| Criterio | Porcentaje |
|----------|------------|
| Funcionamiento general | 30% |
| Navegación autónoma | 20% |
| Interfaz usable | 15% |
| Documentación y replicabilidad | 20% |
| Trabajo colaborativo y control de versiones | 10% |
| Presentación final | 5% |

---

# 🏁 Resultado Esperado

Al finalizar el servicio becario:

- ✔ El TurtleBot mapea el entorno.
- ✔ Se localiza correctamente.
- ✔ Navega de forma autónoma.
- ✔ Puede usarse con una interfaz sencilla.
- ✔ Puede instalarse siguiendo un manual.
- ✔ Puede ser operado por cualquier persona sin conocimientos avanzados de ROS.
