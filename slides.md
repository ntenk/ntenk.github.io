---
theme: mint
---


# Vererbung

Präsentation von *Noah Tenk & Manuel Lukic*

---
Layout: image-right
---
# Inhaltsverzeichnis


- Was ist eine Vererbung?
- Was muss ich dafür können?
- Wann wendet man sie an?
- Welche Vorteile habe ich damit?
- Wie Verwende ich eine Vererbung?

---

# Die Vererbung

- Verbindung zweier Klassen
- Oberklasse verebt Eigenschaften und Methoden an Unterklasse
- überschreiben - override
- Ziel: Code wiederverwenden


---

# Vererbung - Fähigkeiten

- *Kentnisse der Programiersprache*
- *Objektorientierte Programmierung (OOP)*
- *Grundlagen der Vererbung*

---

# Wann wendet man die Vererbung an

- bei mehrmaliger Nutzung von Methoden

---

# Vorteile der Vererbung

- Weniger Aufwand
- Zeitsparend
- Effizient

---

# Wie verwende ich eine Vererbung?

```csharp
try
{
 namespace Vererbung_1;

//Ein Buch ist ein Produkt
//Der Doppelpunkt bedeutet "Vererbung" 
//Unterklasse

public class Buch : Produkt
{
    protected string _isbn = string.Empty;

    public override void Ausgabe()
    {
        Console.WriteLine($"Das Buch kostet EUR {_preis}.");
        //base.Ausgabe();
    }

    public Buch(string isbn, double preis) : base(preis) 
    {
        _isbn = isbn;
    }
}
```






