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
