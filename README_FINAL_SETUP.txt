ANIMEVAULT v8 - CLEAN BUILD

IMPORTANT:
Upload the CONTENTS of this folder directly into the ROOT of a brand-new GitHub repository.
Do not upload the AnimeVault-FINAL-V8-ROOT folder itself.

Repository root must show exactly:
  codemagic.yaml
  pubspec.yaml
  lib/
  assets/
  BUILD_VERSION.txt

There must be only ONE codemagic.yaml.

Codemagic:
  Project type: Flutter (Workflow Editor)
  Then switch to YAML configuration.
  Branch: main
  Workflow: android-debug

What changed in v8:
  - Normal Browse/Search uses Jikan first, with AniList fallback.
  - Browse has real pagination and Load more.
  - Mature Browse uses AniList pagination and Load more.
  - Saved library cards use +1 episode / Rewatch instead of the old Update toggle.
  - Dark action buttons explicitly use white text.
  - Settings shows AnimeVault v8 so the installed APK can be verified.
