
|                  |                              |
| ---------------- | ---------------------------- |
| Type             | User Story 07		  |
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

**I want**  *Añadir productos al sistema*

**So that** *Que los usuarios los soliciten*

# **Business rules**

1. No se identificaron reglas de negocio.



# **Preconditions**

1. Se debe estar autentucado en el sistema como administrador o usuario.



# **Wireframe or Mockup**

Ver [mockup](https://www.figma.com/file/eFanSMyakuYfprgAsLxg0w/Sistema-de-Gestion-de-Modulos?type=design&node-id=0%3A1&t=YAkqHfjOU8GOXbKu-1).



# **Descripción de los elementos de la vista**

| **No** | **Nombre**                   | **Tipo**               | **Requerido (Si/No)** | Valores por defecto | **Descripción /Validación**                                    | 
| ------ | ---------------------------- | ---------------------- | --------------------- | ------------------- | -------------------------------------------------------------- |
| **1**  | Nombre 	                | Texto		         | Si                    |                     |  Acepta valores alphanumericos                                 |
| **2**  | Precio 	                | Numero		 | Si                    |                     |  Acepta numeros con punto flotante                             |
| **3**  | Descipcion                   | Texto		         | No                    |                     |  Acepta valores alphanumericos      	                        |
| **4**  | Cantidad	                | Numero		 | Si                    |                     |  Acepta valores naturales          	                        |
| **5**  | Boton `Añadir al carrito`    | Boton 		 | Si                    |                     |  Solo se muestra si el susuario autenticado es `Usuario`       |
| **6**  | Boton `Editar`               | Boton 		 | Si                    |                     |  Solo se muestra si el susuario autenticado es `Administrador` |

# **Acceptance criteria**

| **No** | **Given**                                                    | **When**                                        | **Then**                                                      |
| ------ | ------------------------------------------------------------ | ----------------------------------------------- | ------------------------------------------------------------- |
| **1**  | Se esta en la pantalla de listar producto	                | Se hace click en el boton `Añadir al carrito`	  | El producto se añade al carrito      			  |
| **2**  | Se esta en la pantalla de listar producto	                | Se hace click en el boton `Editar`	          | El sistema te redirecciona a la paguina `Modificar Producto`  |