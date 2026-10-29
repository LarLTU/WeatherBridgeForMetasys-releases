# Third-party notices

Weather Bridge for Metasys is proprietary software (see [LICENSE](LICENSE)). It includes the open-source components
below, each under its own licence, and uses the data services listed after them. These notices are installed with the
program (`THIRD-PARTY-NOTICES.md` in the install folder) and summarised in the built-in Help under *About, trademarks
and licenses*.

## Trademarks

Weather Bridge for Metasys is an independent product. It is not affiliated with, sponsored by, endorsed by or promoted
by Johnson Controls International plc or its subsidiaries (JCI). Metasys is a registered trademark of Johnson Controls;
all other trademarks belong to their owners. This software is not a JCI product, is not supported by JCI, and has no
ties to JCI. It interacts with Metasys only through its published API.

OpenWeather is a trademark of OpenWeather Ltd. Windows, .NET and ASP.NET are trademarks of Microsoft Corporation.
GitHub is a trademark of GitHub, Inc. Names are used only to identify the systems and services the software works with.

## Software components shipped with the program

| Component | Version | Licence | Copyright |
|---|---|---|---|
| .NET runtime and ASP.NET Core (including Blazor, Kestrel and ASP.NET Core Identity), installed privately with the program | 10.0 | MIT | © .NET Foundation and Contributors |
| Microsoft.EntityFrameworkCore, Microsoft.EntityFrameworkCore.Relational, Microsoft.EntityFrameworkCore.Sqlite, Microsoft.EntityFrameworkCore.Abstractions | 10.0.12 | MIT | © Microsoft Corporation |
| Microsoft.AspNetCore.Identity.EntityFrameworkCore | 10.0.12 | MIT | © Microsoft Corporation |
| Microsoft.Data.Sqlite | 10.0.12 | MIT | © Microsoft Corporation |
| Microsoft.Extensions.Hosting.WindowsServices | 10.0.13 | MIT | © Microsoft Corporation |
| Microsoft.Extensions.Http.Resilience, .Resilience, .Telemetry and related Microsoft.Extensions packages | 10.10.0 | MIT | © Microsoft Corporation |
| System.Security.Cryptography.ProtectedData, System.ServiceProcess.ServiceController | 10.0.13 | MIT | © Microsoft Corporation |
| Markdig | 1.5.1 | BSD-2-Clause | © Alexandre Mutel |
| Polly.Core, Polly.Extensions, Polly.RateLimiting | 8.4.2 | BSD-3-Clause | © 2024 App vNext |
| Serilog, Serilog.AspNetCore, Serilog.Extensions.Hosting, Serilog.Extensions.Logging, Serilog.Formatting.Compact, Serilog.Settings.Configuration, Serilog.Sinks.Console, Serilog.Sinks.Debug, Serilog.Sinks.File | 4.3.0 / 10.0.0 / 7.0.0 | Apache-2.0 | © Serilog Contributors |
| Serilog.Sinks.EventLog | 4.0.0 | Apache-2.0 | © Serilog Contributors |
| SQLitePCLRaw (core, provider, bundle and the e_sqlite3 native library build) | 2.1.12 | Apache-2.0 | © 2014-2024 SourceGear, LLC |
| SQLite (inside e_sqlite3.dll) | 3.x | Public domain | D. Richard Hipp and the SQLite developers |
| Bootstrap (CSS, `wwwroot/lib/bootstrap`) | 5.3.3 | MIT | © 2011-2024 The Bootstrap Authors |
| WiX Toolset runtime (installer dialogs and custom action framework, inside the MSI only) | 5.0.2 | MS-RL | © .NET Foundation and contributors |

Packages used only to build or test the program (for example Microsoft.EntityFrameworkCore.Design, the Roslyn
compilers, xUnit and the WiX build tools) are not shipped and are not listed.

The .NET runtime's own third-party notices are at
<https://github.com/dotnet/runtime/blob/main/THIRD-PARTY-NOTICES.TXT> and ASP.NET Core's at
<https://github.com/dotnet/aspnetcore/blob/main/THIRD-PARTY-NOTICES.txt>.

## Licence texts

### MIT

> Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated
> documentation files (the "Software"), to deal in the Software without restriction, including without limitation the
> rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit
> persons to whom the Software is furnished to do so, subject to the following conditions:
>
> The above copyright notice and this permission notice shall be included in all copies or substantial portions of the
> Software.
>
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE
> WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
> COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR
> OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

### BSD-2-Clause (Markdig)

> Copyright (c) 2018-2019, Alexandre Mutel. All rights reserved.
>
> Redistribution and use in source and binary forms, with or without modification, are permitted provided that the
> following conditions are met:
>
> 1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following
>    disclaimer.
> 2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the
>    following disclaimer in the documentation and/or other materials provided with the distribution.
>
> THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES,
> INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
> DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
> SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
> SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY,
> WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
> OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

### BSD-3-Clause (Polly)

> Copyright (c) 2015-2024, App vNext. All rights reserved.
>
> Redistribution and use in source and binary forms, with or without modification, are permitted provided that the
> following conditions are met:
>
> 1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following
>    disclaimer.
> 2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the
>    following disclaimer in the documentation and/or other materials provided with the distribution.
> 3. Neither the name of App vNext nor the names of its contributors may be used to endorse or promote products derived
>    from this software without specific prior written permission.
>
> THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES,
> INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
> DISCLAIMED. IN NO EVENT SHALL APP VNEXT BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
> CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA,
> OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT
> LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF
> ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

### Apache License 2.0 (Serilog, SQLitePCLRaw)

These components are licensed under the Apache License, Version 2.0 (the "License"); you may not use them except in
compliance with the License. A copy of the License is at <https://www.apache.org/licenses/LICENSE-2.0>. Unless required
by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language
governing permissions and limitations under the License. The components are used unmodified.

### Microsoft Reciprocal License (WiX Toolset)

The WiX Toolset runtime parts embedded in the installer are licensed under the Microsoft Reciprocal License (MS-RL),
<https://opensource.org/license/ms-rl>. Their source code is available at <https://github.com/wixtoolset/wix>. They
are used unmodified.

### SQLite

SQLite is in the public domain (<https://sqlite.org/copyright.html>).

## Data sources

The bridge reads weather data from these services. Each has its own terms; the site operator must follow them,
including holding any key or subscription they require.

| Source | Used for | Licence and terms | What the bridge does to meet them |
|---|---|---|---|
| OpenWeather (<https://openweathermap.org/>): Current Weather, 5 Day / 3 Hour Forecast, One Call 3.0, Air Pollution | Current conditions, forecasts, alerts, air quality | Governed by OpenWeather's terms of service and the operator's price plan (<https://openweather.co.uk/storage/app/media/Terms/Openweather_terms_and_conditions_of_sale.pdf>), which take precedence. OpenWeather's site also describes open licences (CC BY-SA 4.0 for data, ODbL for databases) for some plans; check which apply to the operator's plan. OpenWeather asks for attribution with a link to openweathermap.org. | Uses the operator's own API key. The dashboard credits "Weather data from OpenWeather" with a link; Help credits it too. |
| MET Norway Locationforecast (<https://api.met.no/>) | Backup current conditions and forecast | Norwegian Licence for Open Government Data (NLOD) 2.0 and Creative Commons Attribution 4.0 (CC BY 4.0), <https://api.met.no/doc/License>; terms of service <https://api.met.no/doc/TermsOfService>. Attribution to "The Norwegian Meteorological Institute (MET Norway)" is required. | Sends an identifying User-Agent with the operator's contact, honours If-Modified-Since / Expires caching and the request rate limits. While it is in use, the dashboard credits "Data from The Norwegian Meteorological Institute (MET Norway), CC BY 4.0" with links; Help credits it too. |
| US National Weather Service API (<https://api.weather.gov/>) | Optional measured current conditions and alerts for US sites | Information produced by the US government's National Weather Service is in the public domain in the United States (<https://www.weather.gov/disclaimer>). The API requires an identifying User-Agent. Use does not imply NWS endorsement. | Sends an identifying User-Agent with the operator's contact. The dashboard names the NWS station in use. |
| GitHub releases API (<https://api.github.com/>) | Optional update check (off by default) | GitHub Terms of Service | Sends a User-Agent and reads the latest release only. |

Values the bridge calculates (wet bulb, enthalpy, dew point, daily totals) are derived from these sources.
