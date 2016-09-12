# know-your-frontend
Useful information about frontend libraries/frameworks

Sizes
```
$ du -sh libs/*
164K    libs/Angular
628K    libs/Angular-2
936K    libs/FontAwesome-4.6.3
88K     libs/jQuery-2
96K     libs/jQuery-3
220K    libs/React-15
88K     libs/React-15-util
84K     libs/Vue
```

Gzipped
```
$ for i in libs/*; do tar -cz $i | wc -c | numfmt -z --to=iec --format="%.2f"; echo -e "\t\t$i"; done
54.99K    libs/Angular
122.46K   libs/Angular-2
552.58K   libs/FontAwesome-4.6.3
29.21K    libs/jQuery-2
29.40K    libs/jQuery-3
59.03K    libs/React-15
20.55K    libs/React-15-util
26.10K    libs/Vue
```

Files
```
$ tree libs/
libs/
├── Angular
│   └── angular-1.5.8.min.js
├── Angular-2
│   └── angular-2.0.0-beta.17.min.js
├── FontAwesome-4.6.3
│   ├── font-awesome-4.6.3.min.css
│   ├── FontAwesome.otf
│   ├── fontawesome-webfont.eot
│   ├── fontawesome-webfont.svg
│   ├── fontawesome-webfont.ttf
│   ├── fontawesome-webfont.woff
│   └── fontawesome-webfont.woff2
├── jQuery-2
│   └── jquery-2.2.4.min.js
├── jQuery-3
│   └── jquery-3.1.0.min.js
├── React-15
│   ├── react-15.3.0.min.js
│   ├── react-dom-15.3.0.min.js
│   ├── react-router-2.6.1.min.js
│   └── redux-3.5.2.min.js
├── React-15-util
│   ├── immutable-3.8.1.min.js
│   └── recompose-0.20.2.min.js
└── Vue
    └── vue-1.0.26.min.js

8 directories, 18 files
```
