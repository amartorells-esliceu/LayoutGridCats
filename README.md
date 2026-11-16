# Grid Cats

Galeria responsive de gats implementada amb CSS Grid i Vite. El layout no
utilitza llibreries CSS.

## Requisits

- Node.js `20.19+` o `22.12+`
- npm

## Executar el projecte

Instal·la les dependències i inicia el servidor:

```bash
npm install
npm run dev
```

Obre l'adreça que apareix al terminal (per defecte,
[http://localhost:5173](http://localhost:5173)).

## Ordres disponibles

| Ordre                  | Descripció                                                     |
| ---------------------- | -------------------------------------------------------------- |
| `npm run dev`          | Inicia el servidor de desenvolupament amb recàrrega en calent. |
| `npm run lint`         | Comprova JavaScript, CSS, JSON i Markdown amb ESLint.          |
| `npm run format`       | Formata els fitxers amb Prettier.                              |
| `npm run format:check` | Comprova el format sense modificar fitxers.                    |
| `npm run build`        | Genera els fitxers de producció a `dist/`.                     |
| `npm run preview`      | Serveix localment la build. Executa abans `npm run build`.     |
| `npm run check`        | Executa format, lint i build.                                  |

## Fitxers principals

- `index.html`: idioma, títol, descripció i metadades de la pàgina.
- `src/style.css`: estils i breakpoints de la galeria CSS Grid.
- `public/`: fitxers estàtics servits des de l'arrel del lloc.
- `vite.config.js`: configuració de Vite.

Per afegir variables d'entorn locals, crea un fitxer `.env.local` (ja ignorat
per Git). Les variables exposades al navegador han de començar per `VITE_` i
no hi posis mai secrets: el seu valor queda inclòs al codi enviat al navegador.

## Estructura

```text
.
├── index.html
├── public/
│   └── favicon.svg
├── src/
│   ├── main.js
│   └── style.css
├── eslint.config.js
├── vite.config.js
├── package.json
└── package-lock.json
```
