En el resto del módulo, crearemos mensajes para Microsoft 365 Copilot que hagan referencia a los archivos siguientes:

- [Contoso CipherGuard Product Specification.docx](https://go.microsoft.com/fwlink/?linkid=2269123)
- [Contoso CipherGuard project plan.docx](https://go.microsoft.com/fwlink/?linkid=2268924)
- [Market Trend Report- Protein shake.docx](https://go.microsoft.com/fwlink/?linkid=2268827)

**Nota**: estos son los archivos a los que se hace referencia en todo el módulo. Sin embargo, para este laboratorio, empezaremos cargando todos los archivos en **OneDrive** para asegurarnos de que son accesibles para los mensajes de Copilot más adelante.

### Cargar archivos en OneDrive

Sigue los pasos siguientes para cargar todos los archivos necesarios en **OneDrive**:

1. Inicia sesión en la máquina virtual proporcionada por el proveedor de inquilinos con la cuenta de **administrador** local con la contraseña `Pa55w.rd`.
2. En la barra de tareas de Windows, selecciona **Microsoft Edge**.
3. En la barra de direcciones, escribe `https://www.office.com`.
4. En **Bienvenido a Microsoft 365**, selecciona **Iniciar sesión**.
5. En la **solicitud de inicio de sesión**, escribe `userx@yourtenant.onmicrosoft.com` (nombre de usuario e inquilino proporcionado por el inquilino proporcionado) y selecciona **Siguiente**.
6. En la pantalla **Escribir contraseña**, escribe la contraseña (proporcionada por el proveedor de inquilinos) para la cuenta de usuario y selecciona **Iniciar sesión**.
7. Si se te pide **Mantener la sesión iniciada**, selecciona **No volver a mostrar** y **Sí**.
8. En **Microsoft 365**, selecciona **Aplicaciones**.
9. En **Aplicaciones**, selecciona **OneDrive**.
10. En **OneDrive**, en la esquina superior izquierda, selecciona **+** (agregar nuevo) > **Carga de archivo**.
11. En **Explorador de archivos**, selecciona **Este equipo** > ** Disco local (C:)** y abre la carpeta **ResourceFiles**.
12. Selecciona todos los archivos de la carpeta **ResourceFiles** y, después, selecciona **Abrir** para cargarlos en **OneDrive**.
13. Una vez completada la carga, deberías ver **Se han cargado 29 elementos en Mis archivos** en el centro inferior de la pantalla.
14. Deja **Edge** abierto y ve a la siguiente tarea.

### Hacer referencia a archivos en Copilot

Al usar Copilot, es posible que descubras que algunos archivos no están disponibles inmediatamente en las sugerencias. Esto ocurre porque ciertas experiencias de Copilot solo hacen referencia a archivos de la lista de **Utilizado recientemente (MRU),** mientras que otros te permiten examinar **OneDrive** directamente. Para asegurarte de que un archivo aparece en la lista **MRU**, basta con abrirlo en la aplicación de Microsoft 365 pertinente y se agregará automáticamente.

> [!IMPORTANT]
> Microsoft 365 Copilot solo funcionará con archivos guardados en **OneDrive**. Los archivos almacenados localmente en el equipo deberán moverse a **OneDrive** para que Copilot pueda acceder a ellos.

A medida que avanzas en el módulo, tendrás oportunidades de probar varios mensajes en estos archivos. No dudes en probar diferentes enfoques para mejorar tus aptitudes con Copilot.