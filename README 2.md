# 🎁 Amigo Secreto – Challenge

![GitHub repo size](https://img.shields.io/github/repo-size/JorgRodriguez/Challenge-amigo-secreto)
![GitHub last commit](https://img.shields.io/github/last-commit/JorgRodriguez/Challenge-amigo-secreto)
![GitHub issues](https://img.shields.io/github/issues/JorgRodriguez/Challenge-amigo-secreto)
![GitHub stars](https://img.shields.io/github/stars/JorgRodriguez/Challenge-amigo-secreto?style=social)

---

## 📖 Descripción del proyecto  
Este repositorio contiene una **aplicación web** desarrollada con **HTML**, **CSS** y **JavaScript**, cuyo propósito es **realizar un sorteo de amigo secreto**.  

Permite al usuario:  
✅ Registrar una lista de nombres.  
✅ Mostrar a todos los participantes agregados.  
✅ Seleccionar aleatoriamente un “amigo secreto” usando la función `Math.random()`.  

---

## 🖼 Vista previa  
![Interfaz del aplicativo](assets/screenshot.png)  
*(Puedes reemplazar esta imagen por una captura real de tu aplicación dentro de la carpeta `assets/`)*

---

## 🛠 Tecnologías utilizadas  
- **HTML5** → estructura del proyecto  
- **CSS3** → estilos y diseño visual  
- **JavaScript** → lógica de registro, listado y sorteo aleatorio  

---

## ⚙️ Funcionamiento  
1. El usuario **ingresa nombres** en el formulario.  
2. Cada nombre se agrega a una **lista visible en pantalla**.  
3. Al presionar el botón **Sortear amigo**, se ejecuta la lógica en JS:  
   - Se genera un índice aleatorio con `Math.floor(Math.random() * lista.length)`.  
   - Se selecciona y muestra el nombre correspondiente.  

---

## 📂 Estructura del proyecto
📦 Challenge-amigo-secreto
┣ 📂 assets # Imágenes e íconos
┣ 📜 index.html # Página principal
┣ 📜 style.css # Estilos del proyecto
┣ 📜 app.js # Lógica en JavaScript
┗ 📜 README.md # Documentación

---

## 🚀 Instalación y uso local  

1. **Clonar el repositorio**  
   ```bash
   git clone https://github.com/JorgRodriguez/Challenge-amigo-secreto.git
   cd Challenge-amigo-secreto

2. Abrir index.html en tu navegador.

3. Agregar nombres y presionar los botones para listar o sortear.

📌 Posibles mejoras

* Evitar nombres duplicados.
* Usar localStorage para guardar la lista de participantes.
* Interfaz más responsiva con animaciones.
* Exportar/Importar la lista en JSON o CSV.

🤝 Contribuciones

¡Las contribuciones son bienvenidas!

1. Haz un fork del proyecto.
2. Crea una rama (git checkout -b feature/nueva-feature).
3. Realiza los cambios y haz commit (git commit -m 'Agrega nueva feature').
4. Haz push a la rama (git push origin feature/nueva-feature).
5. Abre un Pull Request.

📄 Licencia

Actualmente este proyecto no tiene licencia especificada. Puedes añadir una (ejemplo: MIT).

👤 Autor

Jorge Rodriguez

🔗 Repositorio en GitHub