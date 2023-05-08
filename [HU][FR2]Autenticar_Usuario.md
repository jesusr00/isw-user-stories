
|                  |                              |
| ---------------- | ---------------------------- |
| Type             | User Story 05		  |
| Document Status  | Reviewed                     |
| Version          | 0.1                          |
| Author           | Jesus R Lopez Martin         |
| Date of creation | 18/03/2023                   |
| Reviewed by      | Bruno M Coello Garrido       |
| Reviewing date   | 22/03/2023                   |
| Approved by      | Bruno M Coello Garrido       |
| Date of Approval | 22/03/2023    		  |



# **Scenario**

**As a** *Administrador, Usuario*

**I want**  *Autenticarme en el sistema*

**So that** *Acceder a sus funcionalidades*

# **Business rules**

1. No se identificaron reglas de negocio.



# **Preconditions**

1. No se identificaron precondiciones.



# **Wireframe or Mockup**

Ver [mockup](https://www.figma.com/file/eFanSMyakuYfprgAsLxg0w/Sistema-de-Gestion-de-Modulos?type=design&node-id=0%3A1&t=YAkqHfjOU8GOXbKu-1).



# **Descripción de los elementos de la vista**

| **No** | **Nombre**        | **Tipo**               | **Requerido (Si/No)** | Valores por defecto | **Descripción /Validación**                 |
| ------ | ----------------- | ---------------------- | --------------------- | ------------------- | ------------------------------------------- |
| **1**  | Nombre de usuario | Texto		      | Si                    |                     |  Acpeta caracteres alphanumericos 		  |
| **2**  | Contraseña 	     | Texto		      | Si                    |                     |  Acpeta caracteres alphanumericos  	  |
| **3**  | Boton `Acceder`   | Boton 		      | Si                    |                     |   	  |


# **Acceptance criteria**

| **No** | **Given**                                                    | **When**                                | **Then**                                                      |
| ------ | ------------------------------------------------------------ | --------------------------------------- | ------------------------------------------------------------- |
| **1**  | Que se introducen correctamente el usuario y la contraseña   | Se hace click en el boton `Acceder`	  | Se redirecciona al homepage					  |
| **2**  | Que se introducen incorrectamente el usuario o la contraseña | Se hace click en el boton `Acceder`	  | Se mustra un mensaje de error				  |