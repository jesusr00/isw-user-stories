
|                  |                              |
| ---------------- | ---------------------------- |
| Type             | User Story 01                |
| Document Status  | Reviewed                     |
| Version          | 0.1                          |
| Author           | Bruno Manuel Coello          |
| Date of creation | 15/03/2023                   |
| Reviewed by      | Jesus R Lopez Martin         |
| Reviewing date   | 18/03/2023                   |
| Approved by      | Jesus R Lopez Martin         |
| Date of Approval | 18/03/2023                   |



# **Scenario**

**As a** *Administrador*

**I want**  *Crear un nuevo usuario en el sistema*

**So that** *Que el usuario pueda acceder al sistema*

# **Business rules**

1. No se identificaron reglas de negocio.



# **Preconditions**

1. Se debe estar autenticado en el sistema como administrador.



# **Wireframe or Mockup**

Ver [mockup](https://www.figma.com/file/eFanSMyakuYfprgAsLxg0w/Sistema-de-Gestion-de-Modulos?type=design&node-id=0%3A1&t=YAkqHfjOU8GOXbKu-1).



# **Descripción de los elementos de la vista**

| **No** | **Nombre**        | **Tipo**               | **Requerido (Si/No)** | Valores por defecto | **Descripción /Validación**     |
| ------ | ------------------| ---------------------- | --------------------- | ------------------- | ------------------------------- |
| **1**  | Nombre de usuario | Texto                  |  Si                   |                     | Admite caracteres alfanumericos |
| **1**  | Nombre y apellido | Texto                  |  Si                   |                     | Admite caracteres alfanumericos |
| **2**  | Rol               | Menu de seleccion      |  Si                   |                     |                                 |
| **3**  | Crear usuario     | Boton                  |  Si                   |                     |                                 |



# **Acceptance criteria**

| **No** | **Given**                                                    | **When**                                | **Then**                                                     |
| ------ | ------------------------------------------------------------ | --------------------------------------- | ------------------------------------------------------------ |
| **1**  | Que se esta en la pantalla de crear usuario                  | todos los datos esten creados correctamente | Se debe crear el usuario                                 |