
|                  |                              |
| ---------------- | ---------------------------- |
| Type             | User Story 03                |
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

**I want**  *Modificar un usuario*

**So that** *Realizar cambios en un usuario*

# **Business rules**

1. No se identificaron reglas de negocio.



# **Preconditions**

1. Se debe estar autenticado en el sistema como administrador.



# **Wireframe or Mockup**

Ver [mockup](https://www.figma.com/file/eFanSMyakuYfprgAsLxg0w/Sistema-de-Gestion-de-Modulos?type=design&node-id=0%3A1&t=YAkqHfjOU8GOXbKu-1).



# **Descripción de los elementos de la vista**

| **No** | **Nombre**        | **Tipo**               | **Requerido (Si/No)** | Valores por defecto | **Descripción /Validación**                   |
| ------ | ------------------| ---------------------- | --------------------- | ------------------- | --------------------------------------------- |
| **1**  | Nombre de usuario | Texto                  |  Si                   |                     | Admite caracteres alfanumericos, autopopulado |
| **2**  | Nombre y apellido | Texto                  |  Si                   |                     | Admite caracteres alfanumericos, autopopulado |
| **3**  | Rol               | Menu de seleccion      |  Si                   |                     | Autopopulado                                  |
| **4**  | Boton `Guardar    | Boton                  |  Si                   |                     | Solo se activa si el formulario es correcto   |


# **Acceptance criteria**

| **No** | **Given**                                                    | **When**                                | **Then**                                                     |
| ------ | ------------------------------------------------------------ | --------------------------------------- | ------------------------------------------------------------ |
| **1**  | Que se esta en la pantalla de modificar usuario              | Se hace click en el boton `Guardar`     | Se guardar los cambios realizados                            |