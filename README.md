# 🔐 Password Strength Assessment

> Proyecto educativo enfocado en la evaluación de la fortaleza de contraseñas utilizadas por los empleados de una empresa. El objetivo es identificar credenciales débiles, comprender los riesgos asociados y promover el uso de contraseñas robustas como una medida fundamental para fortalecer la seguridad de la organización.

![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Blue)
![Password Security](https://img.shields.io/badge/Password-Security-success)
![Authentication](https://img.shields.io/badge/Authentication-red)
![Blue Team](https://img.shields.io/badge/Blue-Team-blueviolet)
![SOC Analyst](https://img.shields.io/badge/SOC-Analyst-orange)

---

# 📖 Descripción

Las contraseñas continúan siendo uno de los principales mecanismos de autenticación utilizados en organizaciones de todo el mundo. Sin embargo, el uso de contraseñas débiles, reutilizadas o fáciles de adivinar incrementa significativamente el riesgo de accesos no autorizados y compromisos de seguridad.

Este proyecto presenta un enfoque para evaluar la fortaleza de una lista de contraseñas de empleados, identificando aquellas que podrían ser vulnerables a técnicas de ataque comunes como fuerza bruta, ataques de diccionario y password spraying.

> **Importante:** Este proyecto tiene fines exclusivamente educativos y de concienciación sobre buenas prácticas de seguridad.

---

# 🎯 Objetivos

- Evaluar la fortaleza de contraseñas.
- Identificar credenciales débiles.
- Reconocer patrones inseguros.
- Comprender las técnicas comunes utilizadas para comprometer contraseñas.
- Promover buenas prácticas de autenticación.
- Reducir el riesgo de accesos no autorizados.

---

# 📝 Prompt

> Evalúa la fortaleza de una lista de contraseñas utilizada por los empleados de una empresa. Identifica aquellas que sean fácilmente vulnerables a ataques de fuerza bruta, ataques de diccionario, password spraying o reutilización de credenciales. Clasifica cada contraseña según su nivel de seguridad (Débil, Media, Fuerte o Muy Fuerte), explica las razones de la clasificación y propone recomendaciones para mejorar su complejidad sin revelar ni almacenar las contraseñas originales.

---

# 🔍 Criterios de Evaluación

Durante el análisis deben considerarse los siguientes aspectos:

## Longitud

- Menos de 8 caracteres.
- Entre 8 y 12 caracteres.
- Más de 12 caracteres.
- Recomendación: mínimo 12 caracteres.

---

## Complejidad

Una contraseña segura debería combinar:

- Letras mayúsculas.
- Letras minúsculas.
- Números.
- Caracteres especiales.

Ejemplo:

```
P@ssw0rd!2026
```

---

## Patrones Comunes

Evitar contraseñas como:

- 123456
- password
- admin
- qwerty
- empresa2025
- nombre123
- fecha de nacimiento
- nombre de la mascota

---

## Reutilización

Verificar si una misma contraseña es utilizada en múltiples cuentas.

La reutilización incrementa el riesgo de compromiso cuando ocurre una filtración de credenciales.

---

## Información Personal

Las contraseñas no deberían contener:

- Nombre del usuario.
- Nombre de la empresa.
- Fecha de nacimiento.
- Número telefónico.
- Información pública.

---

# 🚨 Técnicas de Ataque Comunes

## Fuerza Bruta

Prueba automáticamente múltiples combinaciones hasta encontrar la contraseña correcta.

---

## Ataques de Diccionario

Utilizan listas de palabras y contraseñas comúnmente empleadas.

---

## Password Spraying

Consiste en probar una misma contraseña común contra múltiples cuentas.

---

## Credential Stuffing

Aprovecha credenciales filtradas previamente para intentar acceder a otros servicios.

---

# 📊 Clasificación de Contraseñas

| Nivel | Descripción |
|--------|-------------|
| 🔴 Débil | Fácil de adivinar o muy corta. |
| 🟠 Media | Cumple algunos requisitos, pero puede mejorarse. |
| 🟢 Fuerte | Buena longitud y complejidad. |
| 🔵 Muy Fuerte | Larga, única y resistente a ataques comunes. |

---

# 💡 Recomendaciones

- Utilizar frases de contraseña (passphrases).
- Crear contraseñas únicas para cada servicio.
- Activar autenticación multifactor (MFA).
- Evitar información personal.
- No reutilizar contraseñas.
- Utilizar un gestor de contraseñas.
- Cambiar las credenciales si existe sospecha de compromiso.

---

# 📈 Flujo del Análisis

```text
Lista de Contraseñas
          │
          ▼
 Evaluación de Longitud
          │
          ▼
 Evaluación de Complejidad
          │
          ▼
 Detección de Patrones
          │
          ▼
 Clasificación del Riesgo
          │
          ▼
 Recomendaciones
```

---

# 🛠️ Herramientas Relacionadas

- Have I Been Pwned
- Bitwarden
- KeePassXC
- 1Password
- Microsoft Entra ID Password Protection
- Hashcat (entornos autorizados de laboratorio)
- John the Ripper (entornos autorizados de laboratorio)

---

# 📚 Conceptos Clave

- Password Security
- Authentication
- Multi-Factor Authentication (MFA)
- Password Manager
- Brute Force
- Dictionary Attack
- Password Spraying
- Credential Stuffing
- Identity Security
- Zero Trust

---

# 🎓 Resultados de Aprendizaje

Al completar este proyecto podrás:

- Evaluar la fortaleza de contraseñas.
- Identificar patrones inseguros.
- Comprender cómo funcionan los ataques contra contraseñas.
- Aplicar buenas prácticas para crear credenciales robustas.
- Reducir el riesgo de compromisos por autenticación débil.

---

# 🎯 Conclusión

Las contraseñas fuertes siguen siendo una de las primeras líneas de defensa contra los ataques cibernéticos. Evaluar periódicamente la calidad de las credenciales, fomentar el uso de autenticación multifactor y educar a los usuarios en buenas prácticas contribuye significativamente a fortalecer la postura de seguridad de una organización.

---

# 👨‍💻 Autor

Proyecto desarrollado con fines educativos para fortalecer conocimientos en:

- Ciberseguridad
- Seguridad de Contraseñas
- Gestión de Identidades
- SOC Analyst
- Blue Team
- Security Awareness

---

## ⭐ Apoya este Proyecto

Si este repositorio te resultó útil para comprender la importancia de las contraseñas seguras y las buenas prácticas de autenticación, considera darle una **⭐ Star** y compartirlo con otros estudiantes y profesionales de ciberseguridad.
