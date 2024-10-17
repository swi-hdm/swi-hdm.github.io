# Python Übungsaufgaben: Lösungen und Hinweise für Tutoren

## 1. Variablen und Datentypen

a) Beispiellösung:
```python
name = "Max Mustermann"
alter = 25
groesse = 1.80
print(f"Name: {name}, Alter: {alter}, Größe: {groesse} m")
```
Hinweis: Achten Sie darauf, dass die Studierenden die korrekten Datentypen verwenden.

b) Lösung:
```python
result = 10 / 3
print(type(result))  # <class 'float'>
```
Hinweis: Dies ist eine gute Gelegenheit, den Unterschied zwischen / und // zu erklären.

## 2. Arithmetische Operationen

a) Beispiellösung:
```python
zahl1 = float(input("Erste Zahl: "))
zahl2 = float(input("Zweite Zahl: "))
print(f"Summe: {zahl1 + zahl2}")
print(f"Differenz: {zahl1 - zahl2}")
print(f"Produkt: {zahl1 * zahl2}")
print(f"Quotient: {zahl1 / zahl2}")
```
Hinweis: Ermutigen Sie die Studierenden, über mögliche Fehler (z.B. Division durch Null) nachzudenken.

b) Lösung:
```python
print(17 % 5)  # Ergebnis: 2
```
Hinweis: Erklären Sie, wie der Modulo-Operator funktioniert und wo er nützlich sein kann.

## 3. Eingabe und Ausgabe

a) Beispiellösung:
```python
geburtsjahr = int(input("Ihr Geburtsjahr: "))
alter = 2024 - geburtsjahr
print(f"Sie sind ungefähr {alter} Jahre alt.")
```
Hinweis: Diskutieren Sie mögliche Probleme mit dieser vereinfachten Berechnung.

b) Lösung:
```python
print(f"Sie sind ungefähr {alter}\tJahre alt.")
```
Hinweis: Erklären Sie die Funktion von Escape-Sequenzen wie \t.

## 4. Typumwandlung

a) Beispiellösung:
```python
zahl_string = input("Geben Sie eine Zahl ein: ")
zahl_int = int(zahl_string)
ergebnis = zahl_int * 2
print(ergebnis)
```
Hinweis: Besprechen Sie mögliche Fehler bei der Umwandlung (z.B. bei Eingabe von Buchstaben).

b) Lösung:
```python
num = 42
num_float = float(num)
num_string = str(num_float)
print(type(num_string))  # <class 'str'>
```
Hinweis: Erklären Sie, warum und wann Typumwandlungen nötig sein können.

## 5. Boolesche Operationen

a) Beispiellösung:
```python
zahl = float(input("Geben Sie eine Zahl ein: "))
ergebnis = 10 < zahl < 20
print(ergebnis)
```
Hinweis: Erläutern Sie die Verwendung von zusammengesetzten Vergleichen in Python.

b) Lösung:
```python
passwort = input("Geben Sie das Passwort ein: ")
print(passwort == "python123")
```
Hinweis: Diskutieren Sie die Bedeutung von == vs. = und basic Passwortsicherheit.

## 6. Stringoperationen

a) Beispiellösung:
```python
vorname = "Max"
nachname = "Mustermann"
voller_name = vorname + " " + nachname
print(voller_name)
```
Hinweis: Zeigen Sie alternative Methoden wie f-Strings oder .format().

b) Lösung:
```python
print(voller_name[::-1])
```
Hinweis: Erklären Sie String-Slicing und die Bedeutung von [::-1].

## Bonus-Aufgabe

Beispiellösung:
```python
celsius = float(input("Temperatur in Celsius: "))
fahrenheit = (celsius * 9/5) + 32
print(f"{celsius:.1f}°C entspricht {fahrenheit:.1f}°F")
```
Hinweis: Erläutern Sie die Verwendung von :.1f zur Formatierung von Floats.

Allgemeine Hinweise für Tutoren:
1. Ermutigen Sie die Studierenden, ihre Lösungen zu erklären.
2. Weisen Sie auf gute Programmierpraktiken hin (z.B. aussagekräftige Variablennamen).
3. Diskutieren Sie mögliche Verbesserungen oder alternative Lösungswege.
4. Erklären Sie, wie man mit möglichen Fehleingaben umgehen könnte.
5. Nutzen Sie die Aufgaben, um wichtige Konzepte zu wiederholen und zu vertiefen.

