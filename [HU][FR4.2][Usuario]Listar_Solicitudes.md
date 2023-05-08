
|                  |                              |
| ---------------- | ---------------------------- |
| Type             | User Story 12		  |
| Document Status  | Reviewed                     |
| Version          | 0.1                          |
| Author           | Jesus R Lopez Martin         |
| Date of creation | 18/03/2023                   |
| Reviewed by      | Bruno M Coello Garrido       |
| Reviewing date   | 22/03/2023                   |
| Approved by      | Bruno M Coello Garrido       |
| Date of Approval | 22/03/2023    		  |



# **Scenario**

**As a** *Usuario*

**I want**  *Listar solicitudes relacionadas al mi usuario*

**So that** *Gestionarlas*

# **Business rules**

1. No se identificaron reglas de negocio.



# **Preconditions**

1. Se debe estar autentucado en el sistema como usuario.



# **Wireframe or Mockup**

Ver [mockup](https://www.figma.com/file/eFanSMyakuYfprgAsLxg0w/Sistema-de-Gestion-de-Modulos?type=design&node-id=0%3A1&t=YAkqHfjOU8GOXbKu-1).



# **Descripción de los elementos de la vista**

| **No** | **Nombre**        | **Tipo**               | **Requerido (Si/No)** | Valores por defecto | **Descripción /Validación**                                      |
| ------ | ----------------- | ---------------------- | --------------------- | ------------------- | ---------------------------------------------------------------- |
| **1**  | Numero 	     | Nuemro		      | Si                    |                     |  Se muestra en numero de la solictud en el sistema               |
| **2**  | Fecha 	     | Fecha		      | Si                    |                     |  Se mustra la fecha en la que se realizo la solicitud            |
| **3**  | Estado	     | Texto		      | Si                    |                     |  Se muestra el estado de la solicitud                            |
| **4**  | Detalles 	     | Boton		      | Si                    |                     |  Despliega un Modal con los detalles de la solicitud             |
| **5**  | Acciones  	     | Boton		      | Si                    |                     |  Despliega un menu con las acciones dispoibles para la solicitud |



# **Acceptance criteria**

| **No** | **Given**                                                    | **When**                                        | **Then**                                                        |
| ------ | ------------------------------------------------------------ | ----------------------------------------------- | --------------------------------------------------------------- |
| **1**  | Se esta en la vista de listar solicitudes     	        | Se hace click en el boton `Detalles`	          | El sistema despliega un modal conlos detalles de la solicitud   |
| **2**  | Se esta en la vista de listar solicitudes     	        | Se hace click en el boton `Acciones`	          | El sistema muestra un menu con las posibles accionea a realizar |