# 01 Basics

## Einleitung

Das Ziel vom Programieren ist es sich die Rechenleistung des Prozessors zu Nutzen zu machen.

Damit kann man dann:

- Tolle Grafiken generieren
- tatsächlich etwas rechnen
- usw.

### Prozessoren

Es gibt verschiedene Prozessoren die verschiedene Befehlssätze ausführen können, z.B. ist x86 eine bekannte Befehlssatzarchitektur.

Prozessoren verstehen nur Maschienensprache: https://de.wikipedia.org/wiki/Maschinensprache#Beispiel

## Programmiersprachen

Programmiersprachen sind der Versuch es Menschen einfacher zu machen Maschienensprache zu programieren.

Der Programmcode wird zu Maschienencode kompiliert.

Populärsten Progammiersprachen: https://survey.stackoverflow.co/2023/#section-most-popular-technologies-programming-scripting-and-markup-languages

### Skriptsprachen

Skriptsprachen sind Programmiersprachen, die ohne einen extra Kompiliervorgang direkt über einen Interpreter ausgeführt werden können.

### Auszeichnungssprachen

Eine Auszeichnungssprache (englisch markup language, abgekürzt ML) ist eine maschinenlesbare Sprache für die Gliederung und Formatierung von Texten und anderen Daten. Der bekannteste Vertreter ist die Hypertext Markup Language (HTML)

## Datentypen

- Boolean: `true` | `false`
- Integer (int): Ganzzahl `1`, `7`
- Floating Point (float): `1.0`, `3,1415`
- Character (char): Zeichen `a`, `)`
- String (str): Zeichenkette `mehrere Zeichen`
- Array (): Liste `[1, 5, 6]`

## Programm Strukturen

### Variablen

Variablen sind wie in der Mathematik Platzhalter für einen Wert. Ein einfacher Speicher.  
Variablen werden **deklariert** (Benennung) und dann **initialisiert** (Wertzuweisung).

```
int a;

a = 5;

```

### Bedingungen

```
if(Bedingung){
    Wenn dann tu das
}else{
    Andernfalls das
}
```

### Schleifen

Wiederholende Tätigkeiten.

#### While Schleife

```
While(Bedingung){
Solange das gilt tu das
}
```

#### Zählschleife

```
FOR(Anfangswert;Bedingung;Schritt){
Tu das
}
```

#### Abbrechen und Überspringen

```
    {# In einer Schleife
    BREAK
    }
<----
```

```
    {# In einer Schleife <----
    CONTINUE
    }
```
### Funktionen

Funktionen sind benannte Code-Blöcke die man durch Verwendung des Names überall und so oft man will im Programm einsetzen kann.

```
function halbierenUndPlusEins(zahl){
    return (zahl / 2) + 1
}


variable = halbierenUndPlusEins(4)
```

### Errors
Die `Error`-Klasse ist ein wichtiges Werkzeug für das Programmieren. Sie ermöglicht es dir, Fehler in deinen Programmen abzufangen und zu behandeln.
```
throw Error('Hier geht's nicht mehr weiter')
```

```
try{
    # Unsicherer Code
}catch{
    # Falls ein Fehler auftritt führe das hier aus
}
```

