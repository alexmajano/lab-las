# Laboratorio: Código Seguro y Modelo OWASP

## 1. Datos generales

- **Nombre completo:** Carlos Alexander Cabrera Majano
- **Carné:** N/A
- **Correo institucional:** majano1293@gmail.com
- **Asignatura:** Lenguajes de Programación con aspectos de seguridad.
- **Fecha:** 11/7/2026

## 2. Descripción

Este laboratorio consiste en desarrollar una aplicación web utilizando Python, implementando controles básicos de seguridad basados en buenas prácticas y el modelo OWASP. Se aplican mecanismos de validación de entradas, consultas parametrizadas, protección de contraseñas, registro de eventos de autenticación y detección de incidentes, incluyendo el cálculo de las métricas MTTD y MTTR.

## 3. Estructura del proyecto

```text
lab-las/
├── templates/
│   ├── login.html
│   └── registro.html
├── app.py
├── crearDB.py
├── detector.py
├── eventos.log
├── README.md
├── requirements.txt
├── respuesta.log
└── usuarios.db
```

## 4. Ejecución del proyecto

**Paso 1.** Clonar el repositorio.

```bash
git clone https://github.com/alexmajano/lab-las.git
```

**Paso 2.** Ingresar al proyecto.

```bash
cd lab-las
```

**Paso 3.** Instalar las dependencias.

```bash
pip install -r requirements.txt
```

**Paso 4.** Ejecutar la aplicación.

```bash
python app.py
python detector.py
```



| Prueba | Usuario | MTTD | MTTR |
| :--- | :--- | ---: | ---: |
| 1 | carlos_123 | 39.0 s | 1421.0 s |
| 2 | juan_123 | 43.0 s | 29.0 s |
| 3 | luis_123 | 40.0 s | 18.0 s |
| **Promedio** | — | **40.67 s** | **489.33 s** |




