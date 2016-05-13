#Abgabe 02 - TODO Tracker

Andreas Oehlman, Hai Tran

#Wie können wir den Server starten?

Vorrausetzungen: Python 3.4

How To Start:

1. Repository herunterladen.
2. Entpacken und in dem Terminal des OS in das Verzeichnis 'soziale-netzwerke-ha2' wechseln.
3. Eigene Virtual Environment erstellen. command: $ python3 -m venv myvenv      (myvenv ist der Name der Virtual Environment)
4. Virtual Environment aktivieren: $ source myvenv/bin/activate
5. Django installieren: $ pip install django~=1.9.6
6. Dantenbank erstellen. command: $ python manage.py migrate
7. Server laufen lassen: $ python manage.py runserver
8. In den Browser wechseln und 127.0.0.1:8000 aufrufen


Anmerkung: Das Format für das DateTimeField ist mm/dd/jjjj hh:mm


Copyright (c) 2016 Andreas Oehlmann, Hai Tran

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
