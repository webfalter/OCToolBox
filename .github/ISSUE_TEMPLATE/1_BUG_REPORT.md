name: Bug report
description: Erstellen Sie einen Fehlerbericht zu einem reproduzierbaren Problem..
labels: bug
body:
- type: checkboxes
  id: searched-discussions
  attributes:
    label: Please Confirm
    options:
      - label: Ich habe die **[Issues](https://github.com/webfalter/OCToolBox/issues?q=is%3Aissue)** durchsucht, um zu sehen, ob die gleiche Frage bereits gestellt wurde.
        required: true
- type: dropdown
  id: operating-system
  attributes:
    label: "macOS Version(s) Used to Build"
    description: The operating system version being used to build (not the target runtime OS version).
    multiple: true
    options:
      - "macOS 26.x Tahoe"
      - "macOS 15.x Sequoia"
      - "macOS 14.x Sonoma"
      - "macOS 13.x Ventura"
      - "Other"
  validations:
    required: true
- type: dropdown
  id: xcode-version
  attributes:
    label: "Xcode Version(s)"
    multiple: true
    options:
      - "Xcode 26.x"
      - "Xcode 16.x"
      - "Xcode 15.x"
      - "Other"
  validations:
    required: true
- type: textarea
  id: bug-description
  attributes:
    label: Description
    description: "Eine klare Beschreibung des Fehlers, Schritte zur Reproduktion, Konsolenprotokolle, Screenshots usw."
  validations:
    required: true
