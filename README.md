# 📸 Guía de Fotos - Invitación Graduación Amina Isabela

## ¿Dónde subo mis fotos?

### **Opción 1: Subir fotos directamente a GitHub (Recomendado)**

1. Ve a tu repositorio: https://github.com/amisavara963-oss/graduation-amina
2. Haz clic en **Add file** → **Upload files**
3. Arrastra y suelta tus 3 fotos en la ventana
4. Las fotos se guardarán en una carpeta llamada `images/`
5. Después de subir, haz clic en **Commit changes**

### **Opción 2: Crear una carpeta para las fotos**

1. En tu repositorio, haz clic en **Add file** → **Create new file**
2. Escribe: `images/foto1.jpg` (o el nombre de tu foto)
3. Luego sube los archivos en esa carpeta

---

## 📝 Cómo editar el archivo HTML para mostrar tus fotos

Una vez que tengas las fotos subidas en la carpeta `images/`, edita el `index.html`:

1. Ve a tu repositorio
2. Abre `index.html`
3. Haz clic en el icono de lápiz (✏️) para editar
4. Busca esta sección (línea ~370):

```html
<div class="gallery" id="gallery">
    <div class="gallery-item">
        <span>🖼️</span>
    </div>
    <div class="gallery-item">
        <span>🖼️</span>
    </div>
    <div class="gallery-item">
        <span>🖼️</span>
    </div>
</div>
```

5. **Reemplázalo con esto** (cambia `foto1.jpg`, `foto2.jpg`, `foto3.jpg` por los nombres de tus fotos):

```html
<div class="gallery" id="gallery">
    <div class="gallery-item">
        <img src="images/foto1.jpg" alt="Foto 1">
    </div>
    <div class="gallery-item">
        <img src="images/foto2.jpg" alt="Foto 2">
    </div>
    <div class="gallery-item">
        <img src="images/foto3.jpg" alt="Foto 3">
    </div>
</div>
```

6. Haz clic en **Commit changes** para guardar

---

## ✅ Listo!

Tu invitación ahora mostrará tus 3 fotos en la galería. 

**Ejemplo de estructura:**
```
graduation-amina/
├── index.html (tu invitación)
├── images/
│   ├── foto1.jpg
│   ├── foto2.jpg
│   └── foto3.jpg
└── README.md (este archivo)
```

¿Preguntas? ¡Avísame! 🎓✨
