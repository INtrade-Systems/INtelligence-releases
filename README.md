# INtelligence — instaladores

Este repositorio solo publica los instaladores de **INtelligence**, el dashboard
de INtrade. El código fuente está en un repositorio privado.

## Instalar o actualizar

1. Descarga `INtelligence-Setup-<versión>.exe` del [último release](../../releases/latest).
2. Ejecútalo **como administrador** en el servidor del cliente.
   - Instalación nueva: al terminar se abre el asistente de configuración (`/setup`),
     donde se captura la conexión a la base de INtrade.
   - Actualización: conserva la configuración. Respalda la versión instalada y, si
     la nueva no arranca, restaura la anterior automáticamente.

Las instalaciones de INtelligence consultan este repositorio para avisar en
`/setup` que hay una versión nueva. No se envía ningún dato del cliente.
