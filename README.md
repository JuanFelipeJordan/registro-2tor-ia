# Página de Registro para 2Tor-IA

Este proyecto implementa una página de registro que permite a los usuarios acceder a la plataforma 2Tor-IA desde WhatsApp.

## 🚀 Funcionalidad
Formulario web que envía los datos del usuario (nombre, teléfono y curso) al backend de 2Tor-IA. Una vez registrado, el usuario recibirá un mensaje por WhatsApp.

## ✨ Tecnologías utilizadas
- HTML5 + CSS3
- JavaScript vanilla
- Fetch API para consumo de endpoint

## 📩 Endpoint Backend
- URL: `https://wa.toolia.site/add_user`
- Método: `POST`
- Tipo: `application/x-www-form-urlencoded`

## 📚 Cursos disponibles
- Manipulación de alimentos → `alimentos`
- Tips de IA generativa → `tips-ia`

## ✅ Mensaje de éxito esperado
```
✅ Usuario {nombre} agregado con éxito. Ingresa al WhatsApp de la línea registrada para comenzar. En aproximadamente 2 minutos te llegará un mensaje.
```

---

Desarrollado para el reto de conocimiento **Business Support I+D+I** 🚀
