
|                  |                              |
| ---------------- | ---------------------------- |
| Type             | User Story 08		  |
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

**I want**  *Modificar un producto existente en el sistema*

**So that** *Que los usuarios lo soliciten*

# **Business rules**

1. No se identificaron reglas de negocio.



# **Preconditions**

1. Se debe estar autentucado en el sistema como administrador.



# **Wireframe or Mockup**

Ver [mockup](https://www.figma.com/file/eFanSMyakuYfprgAsLxg0w/Sistema-de-Gestion-de-Modulos?type=design&node-id=0%3A1&t=YAkqHfjOU8GOXbKu-1).



# **Descripción de los elementos de la vista**

| **No** | **Nombre**        | **Tipo**               | **Requerido (Si/No)** | Valores por defecto | **Descripción /Validación**                     |
| ------ | ----------------- | ---------------------- | --------------------- | ------------------- | ----------------------------------------------- |
| **1**  | Nombre 	     | Texto		      | Si                    |                     |  Acepta valores alphanumericos autopopulado     |
| **2**  | Precio 	     | Numero		      | Si                    |                     |  Acepta numeros con punto flotante autopopulado |
| **3**  | Descipcion        | Texto		      | No                    |                     |  Acepta valores alphanumericos autopopulado     |
| **4**  | Cantidad	     | Numero		      | Si                    |                     |  Acepta valores naturales autopopulado   	      |
| **5**  | Boton `Guardar`   | Boton 		      | Si                    |                     |  Solo se activa si el formulario esta corretto  |


# **Acceptance criteria**

| **No** | **Given**                                                    | **When**                                        | **Then**                                                      |
| ------ | ------------------------------------------------------------ | ----------------------------------------------- | ------------------------------------------------------------- |
| **1**  | Se esta en la pantalla de modifica producto	                | Se hace click en el boton `Guardar`	          | El producto se modifica en el sistema   			  |