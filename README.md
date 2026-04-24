# 🐾 Sistema Clínico Veterinario - PetVet

<p align="center">
  <img src="https://github.com/Joey-Resende/PetVet/blob/main/PetVet/static/img/faviconII.ico" width="80">
</p>

<p align="center">
  <strong>Sistema web para la gestión de clínicas veterinarias desarrollado en Python con Django</strong>
</p>

---

## 📋 Descripción del Proyecto

**PetVet** es un sistema clínico veterinario desarrollado para digitalizar y optimizar la gestión de una clínica veterinaria.

Surge a partir de la necesidad de reemplazar los registros manuales por un sistema moderno que permita administrar:

* Pacientes (mascotas) 🐶🐱
* Tutores (dueños) 👤
* Veterinarios 🩺
* Atenciones y consultas 📋

El sistema está construido con **Python utilizando el framework Django**, permitiendo una aplicación web robusta y escalable.

---

## 🎯 Objetivo

* Eliminar el uso de registros manuales
* Centralizar la información clínica
* Mejorar la eficiencia en la atención
* Facilitar la gestión de pacientes y consultas

---

## 🚀 Características

* 🐾 Gestión de mascotas (pacientes)
* 👤 Registro de tutores
* 🩺 Gestión de veterinarios
* 📋 Control de atenciones
* 🧪 Registro de exámenes clínicos:

  * Clínico
  * Físico
  * Dermatológico
* 🔐 Sistema de usuarios
* 📊 Visualización de registros
* ✏️ Edición y eliminación de datos

---

## 🛠️ Tecnologías Utilizadas

* 🐍 Python
* 🌐 Django
* 🎨 HTML
* 🎨 CSS
* 🧰 Poetry (gestión de dependencias)

---

## 📦 Dependencias

El proyecto requiere:

* Python
* Poetry
* Django
* django-crispy-forms
* crispy-bootstrap5
* django-braces

Consulta todas las dependencias en:

```bash id="f7m2q1"
pyproject.toml
```

---

## ⚙️ Instalación y Uso

Se recomienda utilizar un entorno virtual para aislar las dependencias.

---

### 1️⃣ Clonar el repositorio

```bash id="a8n4k2"
git clone https://github.com/isairey/tu-repo.git
cd tu-repo
```

---

### 2️⃣ Activar entorno virtual con Poetry

```bash id="p3v9z1"
poetry shell
```

---

### 3️⃣ Instalar dependencias

```bash id="t6k1m8"
poetry install
```

---

### 4️⃣ Ejecutar el servidor

```bash id="x2q7w5"
cd PetVet/
python manage.py runserver
```

---

### 5️⃣ Acceder al sistema

👉 Abrir en navegador:

```
http://127.0.0.1:8000/
```

---

### 6️⃣ Crear usuario administrador

```bash id="n5c8r3"
python manage.py createsuperuser
```

---

## 📁 Estructura del Proyecto

```id="z9k2p6"
PetVet/
 ┣ 📂 static/
 ┣ 📂 templates/
 ┣ 📂 models/
 ┣ 📂 views/
 ┣ 📂 forms/
 ┗ 📄 manage.py
```

---

## 🔌 Funcionalidades

### 🐾 Pacientes (Mascotas)

* Registro y gestión
* Visualización detallada
* Edición y eliminación

---

### 👤 Tutores

* Registro de propietarios
* Asociación con mascotas

---

### 🩺 Veterinarios

* Registro de personal
* Gestión de información

---

### 🧪 Exámenes

* Clínico
* Físico
* Dermatológico

---

## 🔐 Seguridad

* Autenticación de usuarios
* Control de permisos
* Validación de formularios

---

## 🧪 Pruebas

Puedes probar el sistema ejecutando:

```bash id="y4m7c9"
python manage.py runserver
```

Y verificando el funcionamiento de:

* Registro de usuarios
* Creación de mascotas
* Gestión de consultas

---

## 📜 Licencia

Este proyecto está bajo la licencia MIT.

---

## 👨‍💻 Autor

Desarrollado por **Isai Reyes**

---

<p align="center">
  <img src="https://github.com/Joey-Resende/PetVet/blob/main/PetVet/static/img/login_screen.png" width="600">
</p>

O **PetVet** está disponivel sobre os termos do MIT License. Para os termos completos veja [licença](https://github.com/Joey-Resende/PetVet/blob/main/LICENSE).

<img title="" src="https://github.com/Joey-Resende/PetVet/blob/main/PetVet/static/img/login_screen.png" alt="tela_login" data-align="center">
