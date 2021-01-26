LeetCode
Resolver problemas de LeetCode en VS Code



   

Documento en inglés |中文 文档
Requisitos
VS Code 1.30.1+
Node.js 8+
NOTA: asegúrese de que Nodeesté en su PATHvariable de entorno. También puede utilizar la configuración leetcode.nodePathpara especificar la ubicación de su Node.jsejecutable.

Inicio rápido
manifestación

Caracteristicas
Iniciar / Cerrar sesión
Registrarse

Simplemente haga clic Sign in to LeetCodeen LeetCode Explorerle permitirá iniciar sesión con su cuenta de LeetCode.

También puede utilizar el siguiente comando para iniciar o cerrar sesión:

LeetCode: Iniciar sesión
LeetCode: Cerrar sesión
Cambiar punto final
Cambiar punto final

Al hacer clic en el botón btn_endpointen la barra de navegación del explorador , puede cambiar entre diferentes puntos finales.

Los puntos finales admitidos son:

leetcode.com
leetcode-cn.com
Nota: las cuentas de diferentes puntos finales no se comparten. Asegúrese de estar utilizando el punto final correcto. La extensión se utilizará leetcode.comde forma predeterminada.

Elige un problema
Elige un problema

Haga clic directamente en el problema o haga clic con el botón derecho en el problema LeetCode Explorery seleccione Preview Problempara ver la descripción del problema.

Seleccione Show Problempara abrir directamente el archivo con la descripción del problema.

Nota: Puede especificar la ruta de la carpeta del espacio de trabajo para almacenar los archivos problemáticos actualizando la configuración leetcode.workspaceFolder. El valor predeterminado es: $ HOME / .leetcode / .

Puede especificar si incluye la descripción del problema en los comentarios o no actualizando la configuración leetcode.showCommentDescription.

Se puede cambiar el idioma por defecto al activar el comando: LeetCode: Switch Default Language.

Accesos directos del editor
Accesos directos del editor

La extensión admite 4 atajos de editor (también conocido como Code Lens):

Submit: Envíe su respuesta a LeetCode.
Test: Pruebe su respuesta con casos de prueba personalizados.
Solution: Muestra la solución más votada para el problema actual.
Description: Muestra la página de descripción del problema.
Nota: Puede personalizar los accesos directos que utilizan la configuración: leetcode.editor.shortcuts. De forma predeterminada, solo están habilitados los accesos directos Submity Test.

Problemas de búsqueda por palabras clave
Problemas de búsqueda por palabras clave

Al hacer clic en el botón btn_searchen la barra de navegación del explorador , puede buscar los problemas por palabras clave.
Administrar sesión
Administrar sesión

Para administrar sus sesiones de LeetCode, simplemente haga clic LeetCode: ***en en la parte inferior de la barra de estado. Puede cambiar entre sesiones o crear , eliminar una sesión.
Configuraciones
Nombre de configuración	Descripción	Valor por defecto
leetcode.hideSolved	Especificar para ocultar los problemas resueltos o no	false
leetcode.showLocked	Especifique para mostrar los problemas bloqueados o no. Solo los usuarios Premium pueden abrir los problemas bloqueados	false
leetcode.defaultLanguage	Especifique el idioma predeterminado utilizado para resolver el problema. Los idiomas soportados son: bash, c, cpp, csharp, golang, java, javascript, kotlin, mysql, php, python, python3, ruby, rust, scala,swift	N/A
leetcode.useWsl	Especifique si usar WSL o no	false
leetcode.endpoint	Especifique el punto final activo. Puntos finales soportados son: leetcode,leetcode-cn	leetcode
leetcode.workspaceFolder	Especifique la ruta de la carpeta del espacio de trabajo para almacenar los archivos problemáticos.	""
leetcode.filePath	Especifique la ruta relativa en el espacio de trabajo y el nombre del archivo para guardar los archivos problemáticos. Puede encontrar más detalles aquí .	
[Obsoleto] Úselo en su leetcode.filePathlugar leetcode.outputFolder	Especifique la ruta relativa para guardar los archivos problemáticos. Además de usar una ruta personalizada, también hay varias palabras reservadas que se pueden usar aquí:
${tag}: Categorice el problema según sus etiquetas.
${language}: Categoriza el problema de acuerdo con su idioma.
${difficulty}: Categoriza el problema según su dificultad.
Por ejemplo: problem-${tag}-${difficulty}	N / A
leetcode.enableStatusBar	Especifique si se mostrará o no la barra de estado de LeetCode.	true
[Obsoleto] Úselo en su leetcode.editor.shortcutslugar leetcode.enableShortcuts	Especifique si enviar y probar accesos directos en el editor o no.	true
leetcode.editor.shortcuts	Especifique los accesos directos personalizados en los editores. Los valores admitidos son: submit, test, solutiony description.	["submit, test"]
leetcode.enableSideMode	Especificar si preview, solutiony submissionlengüeta debe ser agrupada en la segunda columna el editor cuando se resuelve un problema.	true
leetcode.nodePath	Especifique la Node.jsruta ejecutable. por ejemplo, C: \ Archivos de programa \ nodejs \ node.exe	node
leetcode.showCommentDescription	Especifique si desea incluir la descripción del problema en los comentarios	false
¿Quiero ayuda?
Cuando encuentre algún problema, puede consultar primero la Solución de problemas y las Preguntas frecuentes .

Si su problema aún no se puede resolver, no dude en comunicarse con nosotros en el canal de Gitter o presentar un problema .

Notas de lanzamiento
Consulte CHANGELOG

Reconocimiento
Esta extensión se basa en @skygragon 's leetcode-cli proyecto de código abierto.
Un agradecimiento especial a nuestros colaboradores .
