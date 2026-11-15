# Kurs Godota
## Wstęp do Edytora
### Stworzenie nowego projektu
Cały Godot zawiera się w jednym pliku wykonywalnym  
Odpalenie tego pliku otwiera Menadżera Projektów – jak odpalimy w nim projekt dopiero wtedy odpali się pełny Godot.  
Ustawiamy Compatibility przy tworzeniu nowego projektu, aby odpalił się na starych kartach graficznych tj. Stare Integry Intela (HD 3000)  

### UI Godota - Dock
UI Godota Składa się z panelu głównego oraz tabów, które nazywają się „Dock”. Można je przemieszczać pomiędzy dostępnymi pozycjami i do oddzielnego okna. Dostępne pozycje mogą się rożnić w zależności od docka. Przykłądem jest dock Output i Debugger, który ma dostępne pozycje tylko na dole.

Dock’a możemy przenieść intuicyjnie myszką. 
Mozemy również go przenieść w alternatywny sposób jak poniżej. Prawym przyciskiem na nazwie Docka otwieramy menu. Biały kolor oznacza aktualną pozycję. Bardziej szare opcje oznaczają miejsca gdzie już znajdują się inne dock’i

Dla niektórych dock’ów są dostępne tylko niektóre pozycje, które są oznaczone przez szare opcje

### UI Godota – Główny Panel
Po środku jest główny panel który rządzi się innymi zasadami – go się przełącza przyciskami na samej górze i nie mają opcji personalizacji.  
Od przyszłej wersji Godot 4.8 (która teraz jest w becie), taby w głównym panelu, dostaną opcje personalizacji tj. ukrycie tab’u i floating window.

### Node
Aby wyjaśnić okno Scene, trzeba najpierw znać koncept Node’a  
Node to w skrócie jest Instancja skryptu, który dziedziczy po godotowym skrypcie „Node”. Dzięki temu dziedziczeniu każdy node ma swoją nazwę, może posiadać swoich dzieci i rodziców oraz może wywoływać callback’i godota.

Instancja - to jest termin z OOP (Object Oriented Programming) – w skrócie oznacza konkretny zestaw danych (tj. konkretny obiekt fizyki) na których dany skrypt oddziałuje (Dane są połączone z funkcjami w danym skrypcie)  
Dziedziczenie – też termin z OOP – służy do rozszerzenie funkcjonalności skryptu poprzez dodanie do niego nowej funkcjonalności i zmiany zachowania skryptu dziedziczonego. Przykład z Godota – Node3D dziedziczy po Nodzie – wtedy Node3D zawiera funkcjonaność Node’a, ale też dodatkowa posiada koordynaty w trzech wymiarach.  


 Teraz aby utworzyć pierwszego Node. Trzeba nacisnąć na 2D Scene w oknie Scene. Utworzy się wtedy Node o typie Node2D


