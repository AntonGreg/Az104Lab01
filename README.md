# AzureLab01

*14 de Enero de 2023*

## Objetivos

- **Tarea 1**: Crear y configurar usuarios de Azure AD.
- **Tarea 2**: Crear grupos de Azure AD con pertenencia dinámica y asignada.
- **Tarea 3**: Crear un Azure Active Directory (AD) tenant.
- **Tarea 4**: Administrar usuarios invitados de Azure AD.

## Instrucciones

### Tarea 1: Crear y configurar usuarios de Azure AD.

1. Iniciamos sesión en el [portal de Azure](https://portal.azure.com/) .
2. En Azure Portal, buscamos y seleccionamos **Azure Active Directory** .
3. En la página de Azure Active Directory, en la parte izquierda clicamos en **Users** y seleccionamos nuestra cuenta principal para ver nuestra configuración.

![](img/img 2.png)

4. Hacemos clic en **Edit properties** y cambiamos nuestra **Usage location** a **United States** y le damos a **Save** para guardar el cambio.

   ![](img/img3.png)

5. Volvemos a la página de **Users - All Users** y luego hacemos clic en **+ New user**.

6. Creamos un **nuevo usuario** con la siguiente configuración (dejamos lo demás con sus valores predeterminados):

| Setting                    | Value                         |
| -------------------------- | ----------------------------- |
| User name                  | **az104-01a-aduser1**         |
| Name                       | **az104-01a-aduser1**         |
| Let me create the password | Enabled                       |
| Initial password           | **Provide a secure password** |
| Usage location             | **United States**             |
| Job title                  | **Cloud Administrator**       |
| Department                 | **IT**                        |

![](img/img4.png)

7. En la lista de usuarios, hacemos clic en la cuenta de usuario recién creada para mostrar su información.

8. Tendremos que copiar el **User Principal Name** ya que lo necesitaremos mas tarde.

   ![](img/img5.png)

9. Hacemos clic en **Assigned roles**, y clicamos en el botón **+ Add assignment** :

   ![](img/img6.png)