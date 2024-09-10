# TicTacToe-Game

## Projektbeschreibung

Dieses Projekt implementiert ein interaktives Tic-Tac-Toe-Spiel, das sowohl gegen menschliche Gegner als auch gegen einfache und fortgeschrittene KI-Gegner gespielt werden kann. Das Spiel verwendet eine modulare Struktur zur Trennung der Spiel- und KI-Logik und bietet eine benutzerfreundliche Oberfläche zur Auswahl des Spielmodus und zur Interaktion mit dem Spielbrett. Die KI nutzt einfache Heuristiken für die Zugauswahl und kann sowohl zufällige als auch strategische Züge ausführen, um das Spielerlebnis zu bereichern.


## Inhaltsverzeichnis

1. [Installation](#installation)
2. [Verwendung](#verwendung)
3. [Dateistruktur](#dateistruktur)
4. [Funktionen](#funktionen)
5. [Beitrag](#beitrag)


## Installation

  Um das Projekt lokal auszuführen, stellen Sie sicher, dass Python 3 installiert ist. 
  Klonen Sie das Repository und führen Sie die Hauptdatei aus:


  git clone https://github.com/philip-hackl/TicTacToe-Game.git
  
  cd TicTacToe-Game
  
  python main_tictactoe.py


## Verwendung

  1. **Starten Sie das Spiel**: Führen Sie das Skript `main_tictactoe.py` aus.
     
  2. **Moduswahl**:
     - **1 vs 1**: Zwei Spieler spielen gegeneinander.
     - **1 vs KI**: Ein Spieler spielt gegen eine einfache KI.
     - **1 vs KI Pro**: Ein Spieler spielt gegen eine verbesserte KI.
  
  3. **Spielablauf**: Die Spieler geben ihre Züge durch Eingabe von Zahlen von 1 bis 9 ein. Das Spielbrett wird nach jedem Zug aktualisiert, und das Ergebnis wird angezeigt, wenn ein   
                      Spieler gewinnt oder ein Unentschieden eintritt.

## Dateistruktur

  - **`main_tictactoe.py`**: Die Hauptspiel-Logik und Benutzerinteraktion.
  - **`board_tictactoe.py`**: Funktionen zum Zeichnen des Spielbretts, Überprüfen der Gültigkeit der Züge und Erkennen von Gewinnbedingungen.
  - **`KI_tictactoe.py`**: Funktionen für die KI, um Züge zu machen. Beinhaltet sowohl zufällige Züge als auch strategische Züge für eine verbesserte KI.

## Funktionen

  ### `main_tictactoe.py`
  - **`main()`**: Startet das Spiel, ermöglicht die Auswahl des Modus, initialisiert die Spieler und das Spielbrett, und steuert den Spielablauf.
  
  ### `board_tictactoe.py`
  - **`draw_board(position)`**: Zeichnet das aktuelle Spielbrett in der Konsole.
  - **`check_if_valid(position, move)`**: Überprüft, ob der eingegebene Zug gültig ist.
  - **`check_win_condition(position, player)`**: Überprüft, ob der angegebene Spieler gewonnen hat.
  - **`clear_board()`**: Leert das Spielbrett und fragt, ob das Spiel fortgesetzt werden soll.
  
  ### `KI_tictactoe.py`
  - **`make_random_move(position)`**: Führt einen zufälligen Zug durch.
  - **`make_better_move(board)`**: Führt einen strategisch besseren Zug aus, um den Gegner zu blockieren oder zu gewinnen.

## Beitrag

  Beiträge zu diesem Projekt sind willkommen! Bitte senden Sie einen Pull-Request oder eröffnen Sie ein Issue, um Vorschläge oder Fehlerberichte zu teilen.

