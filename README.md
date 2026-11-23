# SaludEnOrden · Descargas

Aquí se publican únicamente los **instaladores oficiales** de SaludEnOrden, sus
avisos legales y el canal para reportar fallos. El código fuente se mantiene en un
repositorio privado.

## Descargar la última versión

Ve a **Releases** y descarga el instalador con el número de versión más alto:

`https://github.com/JArmandoMP/SaludEnOrden-Descargas/releases`

> Estado actual: la versión de código es `0.17.0.1`. El instalador de esta versión
> aún no se ha compilado ni publicado; cuando se publique aparecerá en Releases.

## Verificar la descarga

Nadie puede garantizar al 100 % que un archivo esté libre de virus, pero sí puedes
comprobar que descargaste exactamente el archivo publicado:

1. Descarga el `.exe` solo desde este repositorio.
2. Compara su SHA256 con el publicado en la nota de la Release. En PowerShell:

   ```powershell
   Get-FileHash ".\SaludEnOrden-vX.Y.Z.B.exe" -Algorithm SHA256
   ```

3. Si quieres una segunda opinión, sube el instalador a VirusTotal:
   `https://www.virustotal.com/gui/home/upload`.

Si el hash no coincide, **no lo ejecutes** y reporta el problema. El instalador no
está firmado digitalmente; Windows SmartScreen puede mostrar una advertencia.

## Reportar un fallo

Abre un issue aquí y usa la plantilla **Reportar un fallo**:

`https://github.com/JArmandoMP/SaludEnOrden-Descargas/issues`

Incluye la versión (icono de la bandeja → *Acerca de...*), tu Windows, qué pasó y
los pasos para repetirlo. **No pegues datos médicos, nombres, contraseñas ni
respaldos** en el reporte.

## Licencia y avisos

- [`LICENSE`](LICENSE): licencia propietaria con permiso personal y familiar, gratuito y no comercial.
- [`THIRD_PARTY_NOTICES.md`](THIRD_PARTY_NOTICES.md): licencias de los componentes de terceros incluidos.

SaludEnOrden © 2026 Jorge M. Pérez · Todos los derechos reservados.
