# Gawęda – wydania

Tu są gotowe instalatory programu **Gawęda** (Windows 10/11, 64-bit).

**Pobierz najnowszą wersję:** gałąź [`kanal`](https://github.com/cytryk1/gaweda-wydania/tree/kanal)
→ plik `Gaweda-Instalator-X.Y.Z.exe` → „Download raw file” → uruchom. Instalacja nad starszą wersją zachowuje konta, historie i filmy.

Program sam sprawdza to repozytorium (plik `aktualizacja.json` na gałęzi `kanal`) i proponuje
administratorowi aktualizację. Instaluje wyłącznie pliki podpisane kluczem autora (Ed25519) i o zgodnej
sumie SHA-256 – podmieniony plik zostanie odrzucony.

Kod źródłowy programu jest w osobnym, prywatnym repozytorium. Składniki na licencjach open source
(m.in. FFmpeg – GPL-3.0) – szczegóły i źródła w folderze `licencje` po instalacji.
