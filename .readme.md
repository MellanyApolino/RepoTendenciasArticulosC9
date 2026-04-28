# Trabajo Académico II: Prospectivas Tecnológicas de los SI (IA como Núcleo) 🚀

¡Hola equipo! Bienvenidos al repositorio oficial de nuestro artículo académico para el curso de Tendencias de Sistemas de Información. 

Para mantener la calidad de nuestra investigación y evitar los clásicos dolores de cabeza al juntar las partes en Word, trabajaremos este documento usando **LaTeX** con control de versiones en **Git**. Esta guía detalla todo lo necesario para clonar, compilar y subir sus aportes sin romper el documento principal.

---

## 🛠️ 1. Pre-requisitos (Instalación por única vez)

Antes de clonar el repositorio, asegúrense de tener instalado el siguiente stack en sus computadoras:

1. **[Git](https://git-scm.com/downloads):** Para el control de versiones.
2. **[Visual Studio Code](https://code.visualstudio.com/):** Nuestro editor principal.
3. **[MiKTeX](https://miktex.org/download):** El motor de LaTeX para Windows. (Abran *MiKTeX Console* luego de instalar y denle a "Check for updates").
4. **[Strawberry Perl](https://strawberryperl.com/):** ⚠️ **OBLIGATORIO en Windows.** LaTeX usa una herramienta llamada `latexmk` que requiere Perl para compilar automáticamente. (Instalen y luego **reinicien su PC** o VS Code).
5. **Extensión LaTeX Workshop:** Búsquenla en las extensiones de VS Code (autor: James Yu) e instálenla.

---

## 📥 2. Clonar el Repositorio

Abran la terminal en VS Code (`Ctrl + ñ` o `Ctrl + \``) en la carpeta donde guardarán el proyecto y ejecuten:

```bash
git clone [https://github.com/tu-usuario-aqui/prospectiva-sistemas-ia.git](https://github.com/tu-usuario-aqui/prospectiva-sistemas-ia.git)
cd prospectiva-sistemas-ia