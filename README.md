# 🚀 DeikApps - Sitio Web Oficial

Sitio web oficial de **DeikApps**, empresa desarrolladora de aplicaciones móviles innovadoras.

## 🎨 Diseño

Landing page de una sola página con diseño moderno y profesional:
- Fondo oscuro con efectos glassmorphism
- Animaciones suaves y transiciones fluidas
- Navegación por secciones (scroll suave)
- Totalmente responsive

## 📁 Estructura del Proyecto

```
DeikApps/
├── index.html              # Landing page principal (TODO EN UNO)
├── apps.html               # Página de apps (opcional)
├── logo.png                # Logo de DeikApps (agregar aquí)
├── README.md               # Este archivo
└── laikis/                 # Carpeta de la app Laikis CyclePay
    ├── index.html          # Página de la app
    ├── privacy-policy.html # Política de privacidad
    └── delete-account.html # Eliminación de cuenta
```

## 📷 Logo

**IMPORTANTE:** Guarda tu logo como `logo.png` en la carpeta raíz de DeikApps.

El logo debe ser:
- Formato: PNG con fondo transparente
- Tamaño recomendado: 512x512px o similar
- El logo se mostrará en el navbar (50x50px) y en el hero (180x180px)

## 🌐 URLs Publicadas

Una vez publicado en GitHub Pages:

### Principal
- **Landing page:** `https://[usuario].github.io/DeikApps/`

### Laikis CyclePay (URLs para Google Play)
- **Eliminación de cuenta:** `https://[usuario].github.io/DeikApps/laikis/delete-account.html` ⭐
- **Política de privacidad:** `https://[usuario].github.io/DeikApps/laikis/privacy-policy.html`

## 📝 URL para Google Play Console

Cuando Google Play te pida la **URL de eliminación de cuenta**, usa:

```
https://[TU-USUARIO].github.io/DeikApps/laikis/delete-account.html
```

## 🚀 Cómo Publicar en GitHub Pages

### Paso 1: Crear Repositorio
1. Ve a [github.com](https://github.com)
2. Click en "New repository"
3. Nombre: `DeikApps`
4. Marca como **Public**
5. Click en "Create repository"

### Paso 2: Subir Archivos

**Opción A - Por Web (Más Fácil):**
1. En tu repositorio, click en "uploading an existing file"
2. Arrastra todos los archivos de la carpeta DeikApps
3. Asegúrate de incluir `logo.png`
4. Commit changes

**Opción B - Por Terminal:**
```bash
cd /Users/andres.ayala/Desktop/AppAcademy/DeikApps

git init
git add .
git commit -m "DeikApps - Landing page profesional"
git branch -M main
git remote add origin https://github.com/[TU-USUARIO]/DeikApps.git
git push -u origin main
```

### Paso 3: Activar GitHub Pages
1. Ve a **Settings** → **Pages**
2. En **Source** selecciona **main** branch
3. Click en **Save**
4. Espera 2-3 minutos

¡Listo! Tu sitio estará en línea.

## ✨ Características de la Landing Page

### Secciones
1. **Hero** - Presentación principal con logo animado
2. **Valores** - 4 valores clave de la empresa
3. **Apps** - Catálogo de aplicaciones (Laikis + próximamente)
4. **Footer** - Enlaces de contacto y legales

### Navegación
- Menú fijo con scroll suave
- Enlaces directos a secciones: `#inicio`, `#valores`, `#apps`, `#contacto`
- Indicador de scroll animado

### Efectos
- Gradientes animados en el fondo
- Cards con efecto hover 3D
- Animaciones de entrada (fade in + slide up)
- Botones con efectos de brillo
- Logo flotante en hero

## 🧪 Probar Localmente

```bash
cd /Users/andres.ayala/Desktop/AppAcademy/DeikApps
python3 -m http.server 8000
```

Luego abre: `http://localhost:8000/`

## 📱 Aplicaciones

### Laikis CyclePay
Aplicación de gestión de pagos recurrentes.
- iOS y Android
- Recordatorios inteligentes
- Gestión de múltiples monedas
- 100% segura y privada

## 📧 Contacto

- **Email empresa:** deikapps7@gmail.com
- **Soporte Laikis:** deikapps7@gmail.com

## 📄 Licencia

© 2025 DeikApps. Todos los derechos reservados.

---

## 🎯 Checklist antes de Publicar

- [ ] Agregar `logo.png` a la carpeta raíz
- [ ] Verificar que todas las páginas se vean bien localmente
- [ ] Revisar enlaces en el footer
- [ ] Actualizar emails de contacto si es necesario
- [ ] Crear repositorio en GitHub
- [ ] Subir archivos
- [ ] Activar GitHub Pages
- [ ] Verificar el sitio en línea
- [ ] Copiar URL de eliminación de cuenta para Google Play
