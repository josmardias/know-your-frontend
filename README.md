# know-your-frontend
Useful information about frontend libraries/frameworks

Folders (Size / Gzipped)
```
$ for i in libs/*; do du -sh $i | tr -d '\n' | sed -e 's/\s.*$//'; echo -en "\t"; tar -cz $i | wc -c | numfmt -z --to=iec --format="%.2f"; echo -e "\t\t$i"; done | column -t
168K  56.71K   libs/Angular
628K  122.46K  libs/Angular-2
1.1M  613.70K  libs/FontAwesome-4.6.3
88K   29.21K   libs/jQuery-2
92K   29.44K   libs/jQuery-3
220K  59.39K   libs/React-15
140K  31.48K   libs/React-15-util
80K   26.26K   libs/Vue
76K   25.90K   libs/Vue-2
```

Files
```
$ tree libs/
libs/
├── Angular
│   └── angular-1.6.1.min.js
├── Angular-2
│   └── angular-2.0.0-beta.17.min.js
├── FontAwesome-4.6.3
│   ├── font-awesome-4.7.0.min.css
│   ├── FontAwesome.otf
│   ├── fontawesome-webfont.eot
│   ├── fontawesome-webfont.svg
│   ├── fontawesome-webfont.ttf
│   ├── fontawesome-webfont.woff
│   └── fontawesome-webfont.woff2
├── jQuery-2
│   └── jquery-2.2.4.min.js
├── jQuery-3
│   └── jquery-3.1.1.min.js
├── React-15
│   ├── react-15.4.1.min.js
│   ├── react-dom-15.4.1.min.js
│   ├── ReactRouter-3.0.0.min.js
│   ├── ReactRouterRedux-4.0.7.min.js
│   └── redux-3.6.0.min.js
├── React-15-util
│   ├── immutable-3.8.1.min.js
│   ├── react-router-4.0.0-alpha.6.min.js
│   └── recompose-0.21.2.min.js
├── Vue
│   └── vue-1.0.28.min.js
└── Vue-2
    └── vue-2.1.8.min.js

9 directories, 21 files
```
