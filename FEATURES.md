# Built-in features for quest-journal-os

Purpose: tabletop roleplaying

1. **organize a personal routine** — run quest-journal-os-workspace. It creates ~/Documents/quest-journal-os-workspace/ with Plans, Journal, Reference folders.
2. **plan a personal session** — run quest-journal-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/quest-journal-os-session-plans/.
3. **check routine readiness** — run quest-journal-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/quest-journal-os-workspace features/quest-journal-os-plan features/quest-journal-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for tabletop roleplaying:

1. **GIMP** — org.gimp.GIMP
2. **OBS Studio** — com.obsproject.Studio
3. **Kdenlive** — org.kde.kdenlive

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for tabletop roleplaying:

1. **Zotero** — manage research sources and citations (org.zotero.Zotero)
2. **Calibre** — organize ebooks and convert documents (com.calibre_ebook.calibre)
3. **Foliate** — read EPUB books (com.github.johnfactotum.Foliate)
4. **Anki** — create spaced-repetition study decks (net.ankiweb.Anki)
5. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
6. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
7. **GNOME Calendar** — schedule sessions, deadlines, and events (org.gnome.Calendar)
8. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
9. **Document Scanner** — digitize paper notes and forms (org.gnome.SimpleScan)
10. **GNOME Contacts** — organize partner and team contacts (org.gnome.Contacts)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **Pixelorama** (com.orama_interactive.Pixelorama) — draw pixel-art sprites and frame-based animations.
2. **Synfig Studio** (org.synfig.SynfigStudio) — create vector-based 2D animations.
3. **OpenToonz** (io.github.OpenToonz) — produce hand-drawn and cutout 2D animation.
4. **RawTherapee** (com.rawtherapee.RawTherapee) — develop RAW photo files with tone and color controls.
5. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
6. **Shotwell** (org.gnome.Shotwell) — import, sort, and make quick edits to photo libraries.
7. **MuseScore Studio** (org.musescore.MuseScore) — write, play back, and print sheet music.
8. **LMMS** (io.lmms.LMMS) — compose electronic music and loops.
9. **Hydrogen** (org.hydrogenmusic.Hydrogen) — program drum patterns and percussion tracks.
10. **Guitarix** (org.guitarix.Guitarix) — shape guitar tone with amp and effects processing.
11. **JabRef** (org.jabref.jabref) — organize BibTeX references and research citations.
12. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
13. **Krita** (org.kde.krita) — paint digital illustrations.
14. **Blender** (org.blender.Blender) — create 3D assets and animations.
15. **Audacity** (org.audacityteam.Audacity) — edit audio recordings.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.
