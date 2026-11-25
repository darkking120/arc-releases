# ARC: Airline Refund Calculator

A Python desktop application suite that automates airline refund and reissue/exchange calculations and GDS data entry for travel agency ticketing teams.

Built by **Raza A. Butt**  

## Features

- **Refund calculator**: fare proration, tax handling and non-refundable tax code filtering
- **Reissue / Exchange calculator**: dedicated tab for reissue and exchange cases
- **Galileo automation**: TRNTAX / TRFT / TRNE entry with dot-navigation logic, using `pyautogui` and `win32gui` (no API needed)
- **Modern dark UI**: "Midnight Indigo" theme built with `customtkinter`
- **Reports**: export and import of refund reports

## Tech Stack

| Area | Tools |
|------|-------|
| Language | Python |
| Desktop UI | customtkinter |
| GDS automation | pyautogui, win32gui | 
| Packaging | PyInstaller |

## Supported GDS

Amadeus, Galileo / Travelport Smartpoint

## Installation

```bash
git clone <your-repo-url>
cd <repo-folder>
pip install -r requirements.txt
python main.py
```

> Windows is required for GDS automation (`win32gui`).

## Related Tools

- Landing page: https://arc.freedev.app

## Roadmap
- Auto-update mechanism


## Author

**Raza A. Butt**
Airline ticketing and GDS specialist, Lahore, Pakistan

## License

Proprietary. Developed for HOME WORD . All rights reserved.
