
|                  |                              |
| ---------------- | ---------------------------- |
| Type             | User Story 02		  |
| Document Status  | Reviewed                     |
| Version          | 0.1                          |
| Author           | Jesus R Lopez Martin         |
| Date of creation | 18/03/2023                   |
| Reviewed by      | Bruno M Coello Garrido       |
| Reviewing date   | 22/03/2023                   |
| Approved by      | Bruno M Coello Garrido       |
| Date of Approval | 22/03/2023    		  |



# **Scenario**

**As a** *Administrador*

**I want**  *Lsitar todos los usuarios regsitrados*

**So that** *Gestionarlos*

# **Business rules**

1. No se identificaron reglas de negocio.



# **Preconditions**

1. Se debe estar autentucado en el sistema como administrador.



# **Wireframe or Mockup**

Ver [mockup](https://www.figma.com/file/eFanSMyakuYfprgAsLxg0w/Sistema-de-Gestion-de-Modulos?type=design&node-id=0%3A1&t=YAkqHfjOU8GOXbKu-1).



# **Descripción de los elementos de la vista**

| **No** | **Nombre**        | **Tipo**               | **Requerido (Si/No)** | Valores por defecto | **Descripción /Validación**                 |
| ------ | ----------------- | ---------------------- | --------------------- | ------------------- | ------------------------------------------- |
| **1**  | Nombre y apellido | Texto		      | Si                    |                     |  Se mustra el nombre y apellido del usuario |
| **2**  | Nombre de usuario | Texto		      | Si                    |                     |  Se nombre de usuario			  |
| **3**  | Boton Editar      | Boton 		      | Si                    |                     |  Se mustra un boton para ediat el usuario	  |
| **3**  | Boton Eliminar    | Boton 		      | Si                    |                     |  Se mustra un boton para eliminar el usuario|


# **Acceptance criteria**

| **No** | **Given**                                                    | **When**                                | **Then**                                                      |
| ------ | ------------------------------------------------------------ | --------------------------------------- | ------------------------------------------------------------- |
| **1**  | Se esta en la pantalla de listar usuario	                | Se carga la vista 			  | El sistema mustra una lista con todos lo usuarios registrados |