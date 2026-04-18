# 📝 Cómo editar una tarjeta para un nuevo cliente

**Tiempo estimado:** 5 minutos por cliente

---

## 🎯 Paso 1: Crear repositorio para el cliente

En GitHub:
1. Ve a `github.com/ProsperoSoft`
2. Haz clic en **"Use this template"** desde `fernando-araujo`
3. Nombre: `cliente-[nombre-del-cliente]`
4. Visibilidad: **Public**
5. Crear repositorio

---

## ✏️ Paso 2: Editar index.html

Abre `index.html` y cambia estas líneas:

| Línea | Elemento | Buscar | Reemplazar con |
|-------|----------|--------|----------------|
| 30 | `<h1>` | `Fernando Araujo` | Nombre del cliente |
| 33 | `.prof` | `Desarrollador Web` | Profesión del cliente |
| 36 | `.bio` | `Soluciones web limpias...` | Descripción personalizada |
| 44 | WhatsApp | `584169798397` | Teléfono (con 58 código país) |
| 47 | Email | `elprospero@gmail.com` | Email del cliente |
| 50 | Portafolio | `#` | URL del sitio web |
| 80-95 | vCard script | Todos los datos | Actualizar FN, TEL, EMAIL |

---

## 📇 Paso 3: Generar nuevo vCard

Crea un archivo `cliente.vcf` con este formato:

```vcard
BEGIN:VCARD
VERSION:3.0
FN:[NOMBRE COMPLETO]
N:[APELLIDO];[NOMBRE];;;
TITLE:[PROFESIÓN]
TEL;TYPE=WORK,CELL:[TELÉFONO]
EMAIL;TYPE=WORK:[EMAIL]
URL;TYPE=WORK:[PORTFOLIO]
NOTE:[DESCRIPCIÓN CORTA]
END:VCARD
