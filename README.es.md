# Universal RenPy Translator

**Leer en otros idiomas:** [English](README.md) | [Русский](README.ru.md) | [简体中文](README.zh.md) | **Español** | [Français](README.fr.md) | [日本語](README.ja.md) | [العربية](README.ar.md)

Universal RenPy Translator es una potente aplicación de escritorio multiplataforma diseñada para la traducción offline de novelas visuales de Ren'Py. Utiliza modelos de IA locales a través de **Ollama** para ofrecer traducciones de alta calidad y sin censura, sin enviar tu texto a servidores de terceros.

Este repositorio es para las versiones compiladas. El código fuente es cerrado.

---

## ✨ Características

- **100% Offline e Ilimitado:** No se requieren claves API ni hay límites de caracteres. Tus textos nunca salen de tu ordenador y la traducción nunca se interrumpirá por errores del servidor.
- **Traducción 18+ Sin Censura:** Utiliza potentes modelos de IA locales (HY-MT1.5 y Hy-MT2) y un glosario de palabras malsonantes para preservar el tono original, la jerga y el contenido para adultos sin suavizar.
- **Inyección de Overlay en el Juego:** Inyecta un selector de idioma flotante directamente en el juego, permitiendo cambiar sin problemas entre el texto original y el traducido.
- **Todo en Uno y Configuración en 2 Clics:** Descomprime automáticamente los archivos RPA, descompila los archivos `.rpyc` y te permite lanzar el juego traducido directamente desde la aplicación.
- **Amplio Soporte para Ren'Py:** Funciona a la perfección con los motores Ren'Py 6, 7 y 8+.
- **Detección del Idioma de Origen:** Detecta automáticamente el idioma de los archivos originales del juego para evitar errores de traducción.
- **Control del Tamaño de Fuente en el Juego:** Ajusta dinámicamente el tamaño del texto en el juego para adaptarlo a cualquier diseño de UI.
- **Contexto Inteligente (CTX):** Pasa las líneas de diálogo anteriores a la IA para mantener la coherencia narrativa y el uso correcto de los pronombres.
- **Traducción Incremental (Diff):** Actualiza las traducciones para los nuevos capítulos del juego sin tener que retraducir el juego completo desde cero.
- **Detección de Género de los Personajes:** Detecta automáticamente el género del hablante para aplicar las formas gramaticales correctas (crucial para el ruso y otros idiomas con género).
- **Verificador de QA Integrado:** Escanea automáticamente el archivo traducido en busca de etiquetas perdidas, corchetes desbalanceados y cadenas demasiado largas.
- **Editor CAT:** Un editor visual basado en tablas para modificar manualmente las traducciones y solucionar problemas de QA directamente dentro de la aplicación.
- **7 Idiomas de UI:** Inglés, Ruso, Español, Francés, Japonés, Chino y Árabe.

---

## 📸 Capturas de pantalla

![Ventana Principal](https://github.com/user-attachments/assets/50a0b3f5-87cb-477e-aff9-148df7f95fa3)
*Interfaz principal con bloque de soporte y configuración*

![Traducción en curso](https://github.com/user-attachments/assets/e23cb011-6eb3-4133-b6a5-d8e3f7ba1936)
*Proceso de traducción con registros en tiempo real*

![Verificador QA](https://github.com/user-attachments/assets/cc3f0656-74a0-4421-afbb-b4a1538a0e17)
*Inspector de QA integrado*

![Editor CAT](https://github.com/user-attachments/assets/c72db98c-8328-4012-9888-109f3c63ea69)
*Editor CAT para ajustes manuales de traducción*

![Botón Overlay en el Juego](https://github.com/user-attachments/assets/9957d66c-9e50-4090-890d-b15431c4fd97)
*Botón selector de idioma en el juego*

![Menú Overlay en el Juego](https://github.com/user-attachments/assets/e1cc6345-1d4f-4439-a06f-0f448f193874)
*Menú de selección de idioma y tamaño de fuente en el juego*

---

## 📥 Descarga e Instalación

1. Ve a la sección **[Releases](../../releases/latest)** en el lado derecho de esta página.
2. Descarga el archivo `Universal-RenPy-Translator.zip` más reciente.
3. Extrae el archivo en cualquier carpeta de tu PC (no ejecutes el `.exe` directamente desde el archivo comprimido).
4. Ejecuta `Universal RenPy Translator.exe`.

### Requisitos previos
Debes tener **Ollama** instalado y en ejecución en tu ordenador.
1. Descarga e instala Ollama desde [ollama.com](https://ollama.com).
2. El programa te pedirá que descargues el modelo de IA requerido (`huihui_ai/hy-mt1.5-abliterated:7b`) en la primera ejecución.

---

## ⚠️ Importante: Falsos Positivos de Antivirus

Debido a que esta aplicación está compilada usando PyInstaller y **no tiene una firma digital de pago**, Windows Defender y algunos programas antivirus pueden mostrar un falso positivo (por ejemplo, "Trojan:Win32/Wacatac" o "Wacapew").

**Este es un problema conocido para todos los ejecutables basados en Python.** La aplicación es completamente segura y no contiene código malicioso.

**Cómo solucionarlo:**
1. Permite el archivo en tu antivirus (añade la carpeta a las Exclusiones).
2. Si estás usando Windows Defender, puedes enviar el archivo a Microsoft como un falso positivo. Normalmente, lo solucionan en 24 horas.

---

## 💖 Apoya el Proyecto

Universal RenPy Translator es completamente gratis y abierto para todos. Si te resulta útil y quieres apoyar el desarrollo continuo, puedes hacerlo aquí:

- **[Boosty](https://boosty.to/universal_renpy_translator)**
- **[DonationAlerts](https://www.donationalerts.com/r/urtranslator)**
- **Cripto (USDT TRC-20):** [TTL4jWvaS21qEKur1i92Tv7G3h1LWbARTQ](https://link.trustwallet.com/send?asset=c195_tTR7NHqjeKQxGTCi8q8ZY4pL8otSzgjLj6t&address=TTL4jWvaS21qEKur1i92Tv7G3h1LWbARTQ)

¡Gracias por tu apoyo! ❤️

---

## 📄 Licencia y Créditos

- El modelo de traducción **HY-MT1.5 7B Abliterated** está desarrollado por el equipo Tencent Hunyuan bajo la Licencia de Código Abierto Hunyuan v1.0.
- El modelo **Hy-MT2-7B-Abliterated** se basa en el modelo de Tencent y se distribuye bajo la **Licencia Apache 2.0** (abliteración y conversión a GGUF por la comunidad de código abierto).
- Este producto incluye modelos desarrollados por el equipo Tencent Hunyuan.
- Enlaces de licencia: [Hunyuan License](https://hunyuan.tencent.com/license) y [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).
- Ren'Py es una marca registrada de Tom Rothamel. Esta aplicación no está afiliada al equipo oficial de Ren'Py.
