# Ejercicio - Seguimiento del uso de datos de ejemplo con Microsoft 365 Copilot

En el resto del módulo, crearemos mensajes para Microsoft 365 Copilot que hagan referencia a los archivos siguientes:

- [Graphic Design Institute - Employee Benefits.docx](https://go.microsoft.com/fwlink/?linkid=2268825)
- [Mystic Spice Premium Chai Market Analysis Presentation.pptx](https://go.microsoft.com/fwlink/?linkid=2268768)
- [Fabrikam Q1 marketing campaigns.xlsx](https://go.microsoft.com/fwlink/?linkid=2269124)

**Nota**: estos son los archivos a los que se hace referencia en todo el módulo. Sin embargo, para este laboratorio, empezaremos cargando todos los archivos en **OneDrive** para asegurarnos de que son accesibles para los mensajes de Copilot más adelante.

## Cargar archivos en OneDrive

Sigue los pasos siguientes para cargar todos los archivos necesarios en **OneDrive**:

1. Inicia sesión en la máquina virtual proporcionada por el proveedor de inquilinos con la cuenta de **administrador** local con la contraseña `Pa55w.rd`.
2. En la barra de tareas de Windows, selecciona **Microsoft Edge**.
3. En la barra de direcciones, escribe `https://www.office.com`.
4. En **Bienvenido a Microsoft 365**, selecciona **Iniciar sesión**.
5. En la **solicitud de inicio de sesión**, escribe `userx@yourtenant.onmicrosoft.com` (nombre de usuario e inquilino proporcionado por el inquilino proporcionado) y selecciona **Siguiente**.

    [![Captura de pantalla del panel de recursos](../media/lab_resources_password.png)](../media/lab_resources_password.png#lightbox)

6. En la pantalla **Escribir contraseña**, escribe la contraseña (proporcionada por el proveedor de inquilinos) para la cuenta de usuario y selecciona **Iniciar sesión**.
7. Si se te pide **Mantener la sesión iniciada**, selecciona **No volver a mostrar** y **Sí**.
8. En **Microsoft 365**, selecciona **Aplicaciones**.
9. En **Aplicaciones**, selecciona **OneDrive**.
10. En **OneDrive**, en la esquina superior izquierda, selecciona **+** (agregar nuevo) > **Carga de archivo**.
11. En **Explorador de archivos**, selecciona **Este equipo** > ** Disco local (C:)** y abre la carpeta **ResourceFiles**.
12. Selecciona todos los archivos de la carpeta **ResourceFiles** y, después, selecciona **Abrir** para cargarlos en **OneDrive**.
13. Una vez completada la carga, deberías ver **Se han cargado 29 elementos en Mis archivos** en el centro inferior de la pantalla.
14. Deja **Edge** abierto y ve a la siguiente tarea.

### Hacer referencia a archivos

Al hacer referencia a archivos de Copilot, es posible que no encuentres algunos archivos de las sugerencias proporcionadas. Esto ocurre porque ciertas experiencias de Copilot solo hacen referencia a archivos de la lista de utilizado recientemente, mientras que otros permiten examinar OneDrive directamente. Agregarlos a esa lista es tan fácil como abrirlos en la aplicación adecuada de Microsoft 365.  Una vez que se hayan abierto, deben aparecer en la lista de utilizado recientemente.

> [!IMPORTANT]
> Microsoft 365 Copilot solo funcionará con archivos guardados en OneDrive. Los archivos almacenados localmente en el equipo deberán moverse a OneDrive para activar Copilot.

A medida que avances a través del módulo, tendrás la oportunidad de probar otras indicaciones en estos archivos y se recomienda que lo hagas para explorar y mejorar tus habilidades.
