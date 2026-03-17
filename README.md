# 📦 Repositorio de Desarrollos PLC

Repositorio centralizado con documentación, esquemas y códigos de ejemplo para los distintos controladores y módulos de expansión. Los archivos están organizados para ser descargados y cargados directamente a cada dispositivo.

---

## 📁 Estructura del repositorio

```
📦 Repositorio GitHub
├── 📁 Controladores/
│   ├── 📁 BizSync/
│   │   ├── 📁 codigos/
│   │   ├── 📁 esquema/
│   │   ├── 📁 notas/
│   │   ├── 📁 changelog/
│   │   └── 📄 README.md
│   ├── 📁 NM32/
│   │   ├── 📁 codigos/
│   │   ├── 📁 esquema/
│   │   ├── 📁 notas/
│   │   ├── 📁 changelog/
│   │   └── 📄 README.md
│   └── 📁 NM32-IOT/
│       ├── 📁 codigos/
│       ├── 📁 esquema/
│       ├── 📁 notas/
│       ├── 📁 changelog/
│       └── 📄 README.md
├── 📁 NM_Uploader/
│   ├── 📁 installer/
│   ├── 📁 docs/
│   └── 📁 releases/
├── 📁 Expansiones/
│   ├── 📁 [nombre-expansion]/
│   │   ├── 📁 codigos/
│   │   ├── 📁 esquema/
│   │   └── 📄 README.md
│   └── ...
└── 📄 README.md  ← este archivo
```

---

## 🎮 Controladores

### BizSync
> Descripción breve del controlador BizSync.

| Recurso | Descripción |
|---|---|
| `codigos/` | Archivos fuente listos para cargar al controlador |
| `esquema/` | Diagrama de conexiones y pinout |
| `notas/` | Advertencias de instalación y consideraciones especiales |
| `changelog/` | Historial de versiones del código |

🔗 [Ver documentación completa → Controladores/BizSync/README.md](./Controladores/BizSync/README.md)

---

### NM32
> Descripción breve del controlador NM32.

| Recurso | Descripción |
|---|---|
| `codigos/` | Archivos fuente listos para cargar al controlador |
| `esquema/` | Diagrama de conexiones y pinout |
| `notas/` | Advertencias de instalación y consideraciones especiales |
| `changelog/` | Historial de versiones del código |

🔗 [Ver documentación completa → Controladores/NM32/README.md](./Controladores/NM32/README.md)

---

### NM32-IOT
> Descripción breve del controlador NM32-IOT.

| Recurso | Descripción |
|---|---|
| `codigos/` | Archivos fuente listos para cargar al controlador |
| `esquema/` | Diagrama de conexiones y pinout |
| `notas/` | Advertencias de instalación y consideraciones especiales |
| `changelog/` | Historial de versiones del código |

🔗 [Ver documentación completa → Controladores/NM32-IOT/README.md](./Controladores/NM32-IOT/README.md)

---

## 🛠️ NM_Uploader

Herramienta para cargar código a los controladores.

| Carpeta | Contenido |
|---|---|
| `installer/` | Ejecutable de instalación (.exe) |
| `docs/` | Manual de uso de la herramienta |
| `releases/` | Versiones anteriores y actuales |

---

## 🔌 Expansiones

Módulos de expansión compatibles con los controladores. Cada expansión tiene su propia carpeta con documentación y códigos.

| Expansión | Descripción |
|---|---|
| *(agregar expansión)* | *(descripción)* |

Cada carpeta de expansión contiene:
- `codigos/` — archivos fuente
- `esquema/` — diagrama de conexiones
- `README.md` — descripción y modo de uso

---

## 🚀 ¿Cómo usar este repositorio?

1. Navegá a la carpeta del controlador o expansión que necesitás.
2. Revisá el `README.md` interno para instrucciones específicas.
3. Descargá los archivos de `codigos/`.
4. Usá **NM_Uploader** para cargar el código al dispositivo.
5. Consultá `esquema/` para el diagrama de conexiones correspondiente.

---

## 📝 Contribución y actualizaciones

Para agregar un nuevo controlador o expansión, replicar la estructura de carpetas existente y completar el `README.md` interno con la descripción del dispositivo.

---

*Repositorio mantenido por RiskElectro.*
