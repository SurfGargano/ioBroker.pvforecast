![Logo](admin/template.png)
# ioBroker.pvforecast

# Information

Dieser Adapter ersetz das Javascript vom Iobroker Forum https://forum.iobroker.net/topic/26068/forecast-solar-mit-dem-systeminfo-adapter

Der Adapter holt die Grunddaten von https://api.forecast.solar mit folgenden Daten:

1. Account: 
    - Public
    - Personal
    - Proffesional
    - Enterprise
2. Längengrad 
3. Breitengrad
4. Neigung
5. Azimuth
6. Anlagenleistung
7. Link zu Seite

All diese Information werden benötigt um eine saubere Funtkion des Adapters gewährleisten zu können.

Falls der Längen und Breitengrad schon im System hinterlegt ist, trägt das Sysytem die Daten automatisch in die Felder ein.





## Changelog


### 0.0.1
* (Patrick Walther) initial release

## License
The MIT License (MIT)

Copyright (c) 2021 Patrick Walther walther-patrick@gmx.net

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
