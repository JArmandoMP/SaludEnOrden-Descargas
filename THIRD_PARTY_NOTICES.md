# Avisos de componentes de terceros

SaludEnOrden incluye componentes de terceros. Sus derechos permanecen en sus
respectivos autores. Este archivo acompaña siempre al instalador y al código
fuente. La licencia proprietary de SaludEnOrden (ver `LICENSE`) **no** cubre estos
componentes.

## Resumen

| Componente | Uso en SaludEnOrden | Licencia |
|---|---|---|
| Lucide Icons | Iconos SVG en `index.html` | ISC (y MIT para iconos derivados de Feather) |
| QR Code Generator for JavaScript (`assets/js/qr.js`) | Generación de QR | MIT · Copyright (c) 2009 Kazuhiko Arase |
| pywebview 6.2.1 | Ventana de escritorio / WebView2 | BSD 3-Clause |
| pythonnet 3.2.1 | Integración con .NET / menú de bandeja | MIT |
| clr_loader 0.3.1 | Carga del runtime de .NET | MIT (ver proyecto) |
| PyInstaller 6.22.3 | Empaquetado del ejecutable | GPL-2.0-or-later con excepción para bootloader |
| Python 3.15 | Runtime incluido en el bundle | PSF License |
| Microsoft WebView2 Loader / ensamblados | Ventana WebView2 | Términos de redistribución de Microsoft |
| OpenSSL (`libcrypto-3.dll`, `libssl-3.dll`) | Soporte TLS de Python | OpenSSL License / Apache License 2.0 |
| libffi (`libffi-8.dll`) | FFI de Python | MIT |
| Microsoft Visual C++ Runtime (`VCRUNTIME140*.dll`) | Runtime de Python | Términos de redistribución de Microsoft |

La palabra **QR Code** es marca registrada de **DENSO WAVE INCORPORATED**.
SaludEnOrden no implica afiliación ni patrocinio con DENSO WAVE, Microsoft, Lucide
ni los demás autores.

---

## Lucide Icons — ISC License

Copyright (c) 2026 Lucide Icons and Contributors

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR
ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF
OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.

### Iconos derivados de Feather — MIT License

Copyright (c) 2013-present Cole Bemis

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Fuente: https://github.com/lucide-icons/lucide/blob/main/LICENSE

---

## QR Code Generator for JavaScript — MIT License

Copyright (c) 2009 Kazuhiko Arase

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Fuente original: http://www.d-project.com/

---

## pywebview 6.2.1 — BSD 3-Clause License

Copyright (c) 2014-2017, Roman Sirokov
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this
  list of conditions and the following disclaimer.

* Redistributions in binary form must reproduce the above copyright notice,
  this list of conditions and the following disclaimer in the documentation
  and/or other materials provided with the distribution.

* Neither the name of the copyright holder nor the names of its
  contributors may be used to endorse or promote products derived from
  this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

---

## pythonnet 3.2.1 — MIT License

Copyright (c) 2006-2021 the contributors of the Python.NET project

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL
THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
DEALINGS IN THE SOFTWARE.

clr_loader 0.3.1 se distribuye bajo MIT; fuente:
https://github.com/pythonnet/clr-loader/blob/master/LICENSE

---

## PyInstaller 6.22.3 — GPL-2.0-or-later con Bootloader Exception

Copyright (c) 2010-2023, PyInstaller Development Team
Copyright (c) 2005-2009, Giovanni Bajo
Basado en trabajo anterior copyright (c) 2002 McMillan Enterprises, Inc.

PyInstaller se licencia bajo GNU General Public License versión 2 o posterior.
El instalador de SaludEnOrden usa únicamente el bootloader empaquetado dentro
del ejecutable, cubierto por la siguiente excepción:

> In addition to the permissions in the GNU General Public License, the
> authors give you unlimited permission to link or embed compiled bootloader
> and related files into combinations with other programs, and to distribute
> those combinations without any restriction coming from the use of those
> files. (The General Public License restrictions do apply in other respects;
> for example, they cover modification of the files, and distribution when
> not linked into a combined executable.)

Texto completo de la licencia GPL-2.0: https://gnu.org/licenses/gpl-2.0.html
Aviso completo de PyInstaller:
https://github.com/pyinstaller/pyinstaller/blob/develop/COPYING.txt

---

## Python 3.15 — PSF License

Python, `python315.dll`, la biblioteca estándar y las extensiones `_*.pyd` se
distribuyen bajo la Python Software Foundation License.

Fuente: https://docs.python.org/3/license.html

## Microsoft WebView2

Los archivos `Microsoft.Web.WebView2.Core.dll`,
`Microsoft.Web.WebView2.WinForms.dll`, `WebBrowserInterop.*.dll` y
`WebView2Loader.dll` son componentes de Microsoft. Se redistribuyen según la
documentación oficial de distribución de WebView2. Windows 11 incluye el Runtime
Evergreen; en Windows 10 puede ser necesario instalarlo desde:
https://developer.microsoft.com/microsoft-edge/webview2/

Fuente: https://learn.microsoft.com/en-us/microsoft-edge/webview2/concepts/distribution

## OpenSSL, libffi y Visual C++ Runtime

- OpenSSL (`libcrypto-3.dll`, `libssl-3.dll`): https://www.openssl.org/source/license.html
- libffi (`libffi-8.dll`): https://github.com/libffi/libffi/blob/master/LICENSE
- Microsoft Visual C++ Runtime (`VCRUNTIME140*.dll`): términos de redistribución
  de Microsoft para Visual C++ Redistributable.

Estos componentes permiten el funcionamiento del runtime de Python y no son
parte del código de SaludEnOrden.
