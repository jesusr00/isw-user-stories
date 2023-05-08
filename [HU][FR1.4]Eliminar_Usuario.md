
|                  |                              |
| ---------------- | ---------------------------- |
| Type             | User Story 04		  |
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

**So that** *Eliminarlos*

# **Business rules**

1. No se identificaron reglas de negocio.



# **Preconditions**

1. Se debe estar autentucado en el sistema como administrador.



# **Wireframe or Mockup**

Ver [mockup](https://www.figma.com/file/eFanSMyakuYfprgAsLxg0w/Sistema-de-Gestion-de-Modulos?type=design&node-id=0%3A1&t=YAkqHfjOU8GOXbKu-1).



# **Descripción de los elementos de la vista**

| **No** | **Nombre**        | **Tipo**               | **Requerido (Si/No)** | Valores por defecto | **Descripción /Validación**                 |
| ------ | ----------------- | ---------------------- | --------------------- | ------------------- | ------------------------------------------- |
| **1**  | Cuandro de dialogo| Texto		      | Si                    |                     |  Se mustra texto de advertencia 		  |
| **2**  | Boton `Eliminar`  | Texto		      | Si                    |                     |  Se un boton con el texto Eliminar  	  |
| **3**  | Boton `Cancelar`  | Boton 		      | Si                    |                     |  Se un boton con el texto Cancelar 	  |


# **Acceptance criteria**

| **No** | **Given**                                                    | **When**                                | **Then**                                                      |
| ------ | ------------------------------------------------------------ | --------------------------------------- | ------------------------------------------------------------- |
| **1**  | Se esta en la pantalla de listar usuario	                | Se hace click en el boton `Eliminar`	  | Se mustra en cuadro de dialogo				  |