# Built-in features for daymarks-os

Purpose: journaling

1. **organize a personal routine** — run daymarks-os-workspace. It creates ~/Documents/daymarks-os-workspace/ with Plans, Journal, Reference folders.
2. **plan a personal session** — run daymarks-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/daymarks-os-session-plans/.
3. **check routine readiness** — run daymarks-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/daymarks-os-workspace features/daymarks-os-plan features/daymarks-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for journaling:

1. **GNOME Calendar** — org.gnome.Calendar
2. **Audacity** — org.audacityteam.Audacity
3. **Foliate** — com.github.johnfactotum.Foliate

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for journaling:

1. **Zotero** — manage research sources and citations (org.zotero.Zotero)
2. **Calibre** — organize ebooks and convert documents (com.calibre_ebook.calibre)
3. **Anki** — create spaced-repetition study decks (net.ankiweb.Anki)
4. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
5. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
6. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
7. **Document Scanner** — digitize paper notes and forms (org.gnome.SimpleScan)
8. **GNOME Contacts** — organize partner and team contacts (org.gnome.Contacts)
9. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
10. **GNOME Maps** — look up places and plan routes (org.gnome.Maps)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **JabRef** (org.jabref.jabref) — organize BibTeX references and research citations.
2. **Xournal++** (com.github.xournalpp.xournalpp) — annotate PDFs and take handwritten notes.
3. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
4. **Evolution** (org.gnome.Evolution) — manage email, calendars, and contacts.
5. **Gitg** (org.gnome.gitg) — review Git history and branches graphically.
6. **GeoGebra Classic** (org.geogebra.GeoGebra) — explore geometry, algebra, graphing, and 3D math.
7. **Stellarium** (org.stellarium.Stellarium) — explore a planetarium sky for astronomy learning.
8. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
9. **Shotwell** (org.gnome.Shotwell) — import, sort, and make quick edits to photo libraries.
10. **DBeaver Community** (io.dbeaver.DBeaverCommunity) — browse, query, and manage SQL databases.
11. **MuseScore Studio** (org.musescore.MuseScore) — write, play back, and print sheet music.
12. **LibreCAD** (org.librecad.librecad) — draft precise 2D technical drawings.
13. **GNOME Boxes** (org.gnome.Boxes) — test workflows in virtual machines.
14. **GNOME Weather** (org.gnome.Weather) — check local weather conditions.
15. **GNOME Logs** (org.gnome.Logs) — inspect logs during troubleshooting.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.
