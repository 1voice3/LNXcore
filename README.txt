LNXcore – CORE LITE Service App Simulator (Training Tool)
Source: Lennox CORE LITE Control System (Unit Controller) Application Guide 508676-01, 03/2025.
Independent training simulator – not the official Lennox app. Always follow the unit nameplate, the
ORIGINAL FACTORY UNIT CONFIGURATION sticker, and the current Lennox documents for real equipment.

FILES
  index.html                         The simulator (single file, works offline)
  LNXcore_Application_Guide.pdf      Full manual; every "Guide p.X" chip opens it at that page
  README.txt                         This file
Keep all three in the same folder.

INSTALL ON iPHONE (GitHub Pages)
  1. Create a GitHub repo, upload these 3 files to the root, Settings > Pages > Deploy from branch (main /root).
  2. Open https://<user>.github.io/<repo>/ in Safari.
  3. Share > Add to Home Screen. It launches full screen as "LNXcore".
  (Open the PDF links in Safari; iOS opens page jumps in the PDF viewer.)

WHAT'S INSIDE
  Launch: board image (guide cover) assembles in puzzle pieces, then LNXcore title.
  Pairing: hold the BLE pairing button 2-8 s, pick the unit (app flow, p9/p11).
  MENU: System Overview, Active Alarms, General (units/screen mode), RTU MENU:
    Setup (Install incl. Model/Serial/Catalog/Config ID 1 & 2/Dehumidification, Network Integration, Test and Balance),
    Data (Alarm History, Data Trending + CSV, Factory, Runtimes, System Data/Sensors/Outputs),
    Service (Component Test, Report, Advanced Control, Firmware Update), Settings (RTU Options, Install, Edit Parameter).
  Training Library: Alarm Library (all Table 36 codes, subcategories, search + dropdown, simulate),
    Complete Parameter List (all Table 37 entries, search, menu path, page, editable values),
    Model / Config ID 1 / Config ID 2 decoder (per-digit meaning + related menus + pages),
    Wiring & Connections, LEDs & Display Codes (Tables 4-6), Local Interface (hold-time buttons),
    Fresh Air Tempering (FAT) setup, full Application Guide (manual).
  Applying Config ID 1/2 changes the simulator menus (economizer type, Humiditrol, power exhaust).

NOTES
  * Page numbers match the printed pages of the 108-page guide.
  * Alarm subcategories are functional groupings added for training (the guide lists one table).
  * Board connector pins not tabulated in the guide are marked as such; field plugs follow Figure 1 (p5).
  * Settings and edited parameters are saved in the browser (localStorage) on your device.
