Description
This project is a classic Tic-Tac-Toe game featuring a graphical user interface (GUI) built with pygame. 
It supports local two-player matches, automatic win/draw detection, and persistent storage of match results in a local text file.

Implemented Functions and Methods
draw_lines(): Draws the 3x3 grid lines on the game window.

draw_figures(board): Renders "X" and "O" figures based on the current board state.

save_result(result): Appends the game outcome to results.txt using UTF-8 encoding.

main(): The core game loop that manages mouse events, turn-based logic, and session termination.

Testing and Standards
PEP 8: The source code strictly adheres to PEP 8 style guidelines.

Testing: Business logic (located in gameparts) is verified using the pytest framework.
_________________________________________________________________________________________
Beschreibung
Dieses Projekt ist ein klassisches „Tic-Tac-Toe“-Spiel mit einer grafischen Benutzeroberfläche auf Basis der pygame-Bibliothek.
Das Programm unterstützt den Spielmodus für zwei Personen, die automatische Erkennung von Sieg oder Unentschieden sowie die Speicherung der Spielergebnisse in einer Textdatei.

Implementierte Funktionen und Methoden
draw_lines(): Zeichnet das Gitternetz des Spielfelds.

draw_figures(board): Visualisiert die Zeichen „X“ und „O“ entsprechend dem aktuellen Zustand des Spielfelds.

save_result(result): Speichert das Endergebnis des Spiels in der Datei results.txt (UTF-8 kodiert).

main(): Die Hauptschleife des Spiels, die Mauseingaben verarbeitet, Züge wechselt und die Spielbeendigung steuert.

Tests und Standards
PEP 8: Der Code wurde gemäß den PEP 8-Richtlinien für Python-Entwicklung erstellt.

Tests: Die Spiellogik (Modul gameparts) wird durch das pytest-Framework validiert.
