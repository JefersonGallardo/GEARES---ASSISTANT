# 🤖 GEARES

**Asistente virtual propio para automatización de tareas de soporte IT**, desarrollado desde cero para eliminar procesos manuales y repetitivos en un entorno de call center / infraestructura IT.

> Proyecto personal construido durante mi rol como Soporte IT en Geatel Telecom. El código y las configuraciones específicas de la empresa no se incluyen en este repositorio por confidencialidad — este es un resumen técnico de la arquitectura y funcionalidad.

---

## 📌 ¿Qué problema resuelve?

Como parte del área de IT, repetía constantemente las mismas tareas manuales: desplegar instalaciones, generar reportes de posiciones, cambiar configuraciones y crear usuarios en el sistema de telefonía VICIdial. GEARES nació para automatizar todo eso desde un solo punto de control, en vez de repetir el mismo procedimiento manual cada vez.

## ⚙️ Cómo funciona

```
 WhatsApp                Bot de              GEARES              VICIdial /
 "/geares ..."  ─────►   escucha    ─────►   (motor de   ─────►   servidores
                         de comandos          tareas)              internos
```

1. Envío un comando desde WhatsApp con el prefijo `/geares`.
2. Un bot de escucha detecta el mensaje y lo interpreta.
3. GEARES ejecuta la acción solicitada (previa autorización) contra los sistemas internos.
4. El resultado se responde directamente por WhatsApp.

## ✅ Funcionalidades

- **Despliegue de instalaciones** sin intervención manual repetida.
- **Generación de reportes** de posiciones de trabajo bajo demanda.
- **Cambios de configuración** en posiciones desde un solo comando.
- **Creación de usuarios en VICIdial** sin entrar manualmente al panel cada vez.
- **Control remoto vía WhatsApp**, con autorización previa antes de ejecutar cualquier acción crítica.
- **Automatización de auditorías básicas** y procesos repetitivos de bajo tiempo pero alta frecuencia.

## 🧪 Estado del proyecto

En pausa — dejé la empresa antes de completar la siguiente fase, que era integrar un modelo de IA local (**Ollama**) para que GEARES pudiera interpretar lenguaje natural en lugar de comandos fijos, y así ir perfilando una personalidad y capacidad de decisión propia.

## 🛠️ Stack técnico

| Componente | Tecnología |
|---|---|
| Lógica principal | Python |
| Mensajería | Integración con WhatsApp (bot de escucha de comandos) |
| Sistemas gestionados | VICIdial, servidores Linux internos |
| Próxima fase (no completada) | Ollama (modelo de IA local) |

## 🔒 Nota sobre el código

Este repositorio es documentación técnica del proyecto. El código fuente completo no se publica porque contiene lógica y datos específicos de la infraestructura de una empresa. Si te interesa el detalle técnico de implementación, escríbeme — con gusto lo conversamos.

---

📫 **Contacto:** [jefersongallardo789@gmail.com](mailto:jefersongallardo789@gmail.com) · [GitHub](https://github.com/JefersonGallardo)
