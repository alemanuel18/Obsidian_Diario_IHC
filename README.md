# 📝 Vault de Obsidian

Bienvenido a este vault de Obsidian. Este documento te guiará a través del proceso de descarga y configuración para comenzar a utilizarlo.

## 📋 Requisitos Previos

Antes de comenzar, asegúrate de tener instalado:

- **Obsidian**: Descarga la aplicación desde [obsidian.md](https://obsidian.md)
- **Git** (opcional): Para clonar el repositorio. Descárgalo desde [git-scm.com](https://git-scm.com)

## 🚀 Métodos de Descarga

### Opción 1: Descargar como ZIP (Recomendado para principiantes)

1. Navega al repositorio de GitHub donde se encuentra el vault
2. Haz clic en el botón verde **Code** (Código)
3. Selecciona **Download ZIP**
4. Descarga el archivo y descomprímelo en la ubicación de tu preferencia
5. Renombra la carpeta si lo deseas (elimina el sufijo `-main` o `-master` que GitHub añade automáticamente)

### Opción 2: Clonar con Git

Si tienes Git instalado, abre tu terminal y ejecuta:

```bash
git clone https://github.com/USUARIO/NOMBRE-DEL-REPOSITORIO.git
```

Reemplaza `USUARIO` y `NOMBRE-DEL-REPOSITORIO` con los datos correspondientes del repositorio.

## 📂 Abrir el Vault en Obsidian

Una vez descargado el vault, sigue estos pasos:

1. Abre la aplicación **Obsidian**
2. En la ventana de inicio, haz clic en **Open folder as vault** (Abrir carpeta como vault)
3. Navega hasta la carpeta que descargaste/clonaste
4. Selecciona la carpeta y haz clic en **Abrir**
5. Si Obsidian te pregunta sobre confiar en los plugins o configuraciones, revisa las opciones y acepta según tu preferencia

## ⚙️ Configuración Adicional

### Plugins de Comunidad

Si el vault incluye plugins de la comunidad:

1. Ve a **Configuración** (ícono de engranaje) → **Opciones de comunidad**
2. Activa **Plugins de comunidad**
3. Los plugins incluidos en el vault deberían aparecer en la lista
4. Actívalos según sea necesario

### Temas Personalizados

Si el vault incluye temas personalizados, deberían aplicarse automáticamente. Para cambiarlos:

1. Ve a **Configuración** → **Apariencia**
2. Selecciona el tema de tu preferencia en el menú desplegable

## 🔄 Mantener el Vault Actualizado

### Si descargaste como ZIP:

Deberás descargar nuevamente el ZIP cuando haya actualizaciones y reemplazar los archivos (ten cuidado de no sobrescribir tus notas personales).

### Si clonaste con Git:

Puedes actualizar el vault ejecutando en la terminal:

```bash
cd ruta/a/tu/vault
git pull origin main
```

**Nota**: Si has realizado cambios locales, es recomendable crear una rama separada o hacer un fork del repositorio.

## 📝 Notas Importantes

- **Respaldo**: Considera hacer copias de seguridad regulares de tus notas
- **Conflictos**: Si modificas el vault y también quieres recibir actualizaciones del repositorio original, familiarízate con Git para manejar conflictos
- **Privacidad**: Si planeas sincronizar con tu propio repositorio, asegúrate de configurarlo como privado si contiene información sensible

## 🆘 Solución de Problemas

**El vault no abre correctamente:**
- Verifica que hayas seleccionado la carpeta raíz del vault
- Asegúrate de que la carpeta contenga un directorio `.obsidian`

**Los plugins no funcionan:**
- Verifica que los plugins de comunidad estén activados en la configuración
- Algunos plugins pueden requerir configuración adicional

**Error de permisos:**
- Asegúrate de tener permisos de lectura/escritura en la carpeta del vault

## 📚 Recursos Adicionales

- [Documentación oficial de Obsidian](https://help.obsidian.md)
- [Foro de la comunidad](https://forum.obsidian.md)
- [Discord de Obsidian](https://discord.gg/obsidianmd)

---

¡Disfruta organizando tus notas! 🎉
