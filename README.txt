ChemHub by Narek Tech Lab — starter website

HOW TO RUN
1. Extract the ZIP folder.
2. Open index.html in a modern browser (Chrome, Edge, Firefox).
3. For PWA/offline installation, serve this folder over localhost or HTTPS; service workers do not work from file://.
   Simple option on Windows: open the folder in VS Code and use Live Server, or run `python -m http.server 8000` in the folder, then visit http://localhost:8000.

INCLUDED
- All 118 periodic-table elements with atomic numbers, symbols, approximate standard atomic masses, categories and a reference electron-configuration field.
- Search by element name/symbol/atomic number and by common molecular formulas.
- English, Armenian, Russian, Spanish and Catalan interface selector.
- Common molecule/compound starter database.
- Molar mass calculator with parentheses, subscripts, atom counts and step-by-step arithmetic.
- Local favorites, recent searches, light/dark theme, responsive layout and PWA service-worker files.

IMPORTANT LIMITATIONS
- This is a working first version, not a professionally validated chemistry database. Some element names and electron configurations are not fully localized or independently verified, and calculated neutron counts are approximate because isotopes differ.
- The molecule database is a starter selection, not every known compound.
- Advanced tools (equation balancing, oxidation states, solubility, 3D molecule editor) are listed as planned modules, not yet implemented.
- Use trusted scientific sources to verify values for graded work or laboratory use.
