# MerlynPC
Documentación del Script de Configuración De La Aplicacion

Este script de configuración del registro de Windows realiza varias tareas para optimizar y asegurar el sistema. A continuación se detalla cada sección del script y su propósito:

1. **Configuración de CEIP (Customer Experience Improvement Program)**:
   - Deshabilita la telemetría de varios componentes de Windows como CompatTelRunner, AggregatorHost, DeviceCensus, FeatureLoader, BingChatInstaller, BGAUpsell y BCILauncher.

2. **Configuración de Control de Crash**:
   - Deshabilita el reinicio automático después de un crash.
   - Configura la generación de volcados de memoria pequeños (64KB).

3. **Deshabilitar Mantenimiento Automático**:
   - Deshabilita el mantenimiento automático programado.
   - Deshabilita la ejecución programada de diagnósticos.

4. **Deshabilitar Actualizaciones Automáticas de Controladores**:
   - Deshabilita la búsqueda de controladores en Windows Update.
   - Excluye controladores de actualizaciones de calidad.
   - Deshabilita la búsqueda de metadatos de dispositivos desde la red.

5. **Deshabilitar Windows Defender SmartScreen**:
   - Configura el control de instalación de aplicaciones.
   - Deshabilita la evaluación de contenido web.
   - Deshabilita SmartScreen en Microsoft Edge.

6. **Ocultar Icono de Windows Security**:
   - Oculta el icono de Windows Security en la bandeja del sistema.

7. **Deshabilitar Windows Error Reporting**:
   - Deshabilita la aprobación automática de volcados del sistema operativo.
   - Deshabilita el registro y la notificación de errores.

8. **Deshabilitar Telemetría de NVIDIA**:
   - Deshabilita la telemetría de NVIDIA.

9. **Deshabilitar Contenido de la Nube**:
   - Deshabilita varias características de contenido de la nube como Windows Spotlight y sugerencias de terceros.

10. **Deshabilitar CEIP (Customer Experience Improvement Program)**:
    - Deshabilita CEIP para varios componentes de Windows.

11. **Deshabilitar Content Delivery Manager**:
    - Deshabilita la entrega de contenido y sugerencias de aplicaciones.

12. **Deshabilitar Compatibilidad de Aplicaciones**:
    - Deshabilita el motor de compatibilidad de aplicaciones y varias características relacionadas.

13. **Configuración de DirectX Graphics Kernel**:
    - Configura varios parámetros del kernel de gráficos DirectX para mejorar el rendimiento y la estabilidad.

14. **Deshabilitar Actualizaciones de Características**:
    - Deshabilita las actualizaciones de características de Windows.

15. **Deshabilitar Notificaciones de Actualización**:
    - Deshabilita las notificaciones de actualización de Windows.

16. **Deshabilitar Reporte de Datos de Malicious Software Removal Tool**:
    - Deshabilita el reporte de datos de infección de la herramienta de eliminación de software malicioso.

17. **Deshabilitar Descargas de Otras PCs**:
    - Deshabilita la optimización de entrega desde otras PCs.

18. **Deshabilitar Windows Insider Program**:
    - Deshabilita el programa Windows Insider.

19. **Deshabilitar Reserved Storage**:
    - Deshabilita el almacenamiento reservado para mayor control sobre el espacio en disco.

20. **Deshabilitar Actualizaciones Automáticas en Windows Media Player**:
    - Deshabilita las actualizaciones automáticas en Windows Media Player.

21. **Prevenir Actualizaciones para DevHome y Outlook**:
    - Previene las actualizaciones para DevHome y Outlook.

22. **Ocultar Notificaciones de Actualización de Windows**:
    - Oculta las notificaciones de actualización de Windows.

23. **Controlar Visibilidad del Icono de Estado de Windows Update en la Barra de Tareas**:
    - Configura la visibilidad del icono de estado de Windows Update en la barra de tareas.

24. **Deshabilitar UAC (User Account Control)**:
    - Deshabilita el control de cuentas de usuario.

25. **Configuración de Tipos de Archivos de Riesgo Moderado**:
    - Configura la lista de tipos de archivos de riesgo moderado y deshabilita la advertencia de verificación del editor.
26. **Deshabilitar Fault Tolerant Heap (FTH)**:
   - Deshabilita la característica FTH para mejorar la estabilidad de las aplicaciones al evitar correcciones automáticas de compatibilidad relacionadas con la gestión de memoria.

27. **Deshabilitar Core Isolation**:
   - Deshabilita la seguridad basada en virtualización de Windows (VBS) para permitir que el sistema funcione sin esta capa adicional de protección.

28. **Establecer la Política de Ejecución de PowerShell en 'Unrestricted'**:
   - Configura la política de ejecución de PowerShell en 'Unrestricted' para permitir la ejecución de scripts sin restricciones.

29. **Configurar Actualizaciones de Windows**:
   - Deshabilita las actualizaciones automáticas de Windows hasta el año 2038.
   - Deshabilita las notificaciones de actualización y otras características relacionadas con las actualizaciones.

30. **Deshabilitar Sincronización**:
   - Deshabilita varias características de sincronización, incluyendo la sincronización de configuraciones, aplicaciones, credenciales, temas, personalización, menú de inicio y navegador.

31 **Configuración de DirectX Graphics Kernel**:
   - Configura varios parámetros del kernel de gráficos DirectX para mejorar el rendimiento y la estabilidad del sistema.
   - 
31. **Controlar la velocidad del tráfico de red para aplicaciones multimedia**:
   - Establece la velocidad del tráfico de red para aplicaciones multimedia.

32. **Controlar la prioridad de las aplicaciones multimedia en el sistema**:
   - Establece la prioridad de las aplicaciones multimedia en el sistema.

33. **Deshabilitar la escritura diferida en disco para aplicaciones multimedia**:
   - Deshabilita la escritura diferida en disco para aplicaciones multimedia.

34. **Establecer el tiempo de espera antes de escribir en disco en modo de escritura diferida**:
   - Establece el tiempo de espera antes de escribir en disco en modo de escritura diferida.

35. **Controlar la prioridad de los procesos en el sistema**:
   - Controla la prioridad de los procesos en el sistema.

36. **Deshabilitar la ejecución de programas que se ejecutan al inicio del sistema**:
   - Deshabilita la ejecución de programas que se ejecutan al inicio del sistema.

37. **Deshabilitar Smart App Control**:
   - Deshabilita Smart App Control.

38. **Controlar la desasignación de memoria en el sistema**:
   - Controla la desasignación de memoria en el sistema.

39. **Controlar el tamaño de la caché del sistema de archivos**:
   - Controla el tamaño de la caché del sistema de archivos.

40. **Deshabilitar Intel TSX**:
    - Deshabilita Intel TSX.

41. **Corregir la caída de puntuación de la CPU en benchmarks 24H2**:
    - Corrige la caída de puntuación de la CPU en benchmarks 24H2.

42. **Controlar la distribución de temporizadores en el sistema**:
    - Controla la distribución de temporizadores en el sistema.

43. **Habilitar TRIM para SSDs**:
    - Habilita TRIM para SSDs.

44. **Deshabilitar la compresión automática de archivos NTFS**:
    - Deshabilita la compresión automática de archivos NTFS.

45. **Deshabilitar el cifrado del archivo de paginación**:
    - Deshabilita el cifrado del archivo de paginación.

46. **Deshabilitar la actualización de la marca de tiempo de acceso**:
    - Deshabilita la actualización de la marca de tiempo de acceso.

47. **Establecer el intervalo de notificaciones de cuota de disco**:
    - Establece el intervalo de notificaciones de cuota de disco.

48. **Deshabilitar la creación de nombres de archivo en formato 8.3**:
    - Deshabilita la creación de nombres de archivo en formato 8.3.

49. **Deshabilitar Multi Plane Overlay**:
    - Deshabilita Multi Plane Overlay.

50. **Deshabilitar aplicaciones UWP en segundo plano**:
    - Deshabilita aplicaciones UWP en segundo plano.

51. **Configurar políticas de recursos**:
    - Configura políticas de recursos.

52. **Deshabilitar anuncios en la configuración y el menú de inicio**:
    - Deshabilita anuncios en la configuración y el menú de inicio.

53. **Eliminar anuncios de la aplicación de configuración**:
    - Elimina anuncios de la aplicación de configuración.

54. **Deshabilitar anuncios en la pantalla de bloqueo (Spotlight)**:
    - Deshabilita anuncios en la pantalla de bloqueo (Spotlight).

55. **Deshabilitar 'Mostrarme notificaciones en la aplicación de configuración'**:
    - Deshabilita 'Mostrarme notificaciones en la aplicación de configuración'.

56. **Deshabilitar 'Obtener consejos y sugerencias al usar Windows'**:
    - Deshabilita 'Obtener consejos y sugerencias al usar Windows'.

57. **No mostrarme la experiencia de bienvenida de Windows después de las actualizaciones y ocasionalmente cuando inicie sesión para resaltar lo nuevo y sugerido**:
    - No muestra la experiencia de bienvenida de Windows después de las actualizaciones y ocasionalmente cuando inicia sesión para resaltar lo nuevo y sugerido.

58. **Deshabilitar recomendaciones personalizadas**:
    - Deshabilita recomendaciones personalizadas.

59. **Sugerir formas de aprovechar al máximo Windows y terminar de configurar este dispositivo**:
    - Sugiere formas de aprovechar al máximo Windows y terminar de configurar este dispositivo.

60. **Deshabilitar experiencias personalizadas**:
    - Deshabilita experiencias personalizadas.

61. **Deshabilitar "Incluir información basada en la cuenta, reciente, favorita y recomendada" para OneDrive en el Explorador de archivos**:
    - Deshabilita "Incluir información basada en la cuenta, reciente, favorita y recomendada" para OneDrive en el Explorador de archivos.

62. **Parche simple para el archivo hosts de Windows, que hace que el cliente de Outlook deje de mostrar esos molestos anuncios en tu bandeja de entrada**:
    - Aplica un parche simple para el archivo hosts de Windows, que hace que el cliente de Outlook deje de mostrar esos molestos anuncios en tu bandeja de entrada.

63. **No mostrarme anuncios personalizados usando mi ID de publicidad**:
    - No muestra anuncios personalizados usando mi ID de publicidad.

64. **Deshabilitar IDs de publicidad**:
    - Deshabilita IDs de publicidad.

65. **Deshabilitar la recopilación de datos**:
    - Deshabilita la recopilación de datos.

66. **Deshabilitar la recopilación de datos de Windows Defender**:
    - Deshabilita la recopilación de datos de Windows Defender.

67. **Configurar Autologgers**:
    - Configura Autologgers.

68. **Configurar hosts para bloquear telemetría**:
    - Configura hosts para bloquear telemetría.

69. **Deshabilitar tareas programadas de telemetría**:
    - Deshabilita tareas programadas de telemetría.

70. **Deshabilitar telemetría de DotNet**:
    - Deshabilita telemetría de DotNet.


