# know-your-frontend
Useful information about frontend libraries/frameworks

Sizes
```
$ du -sh libs/*
168K    libs/Angular
628K    libs/Angular-2
1.1M    libs/FontAwesome-4.6.3
88K     libs/jQuery-2
92K     libs/jQuery-3
208K    libs/React-15
92K     libs/React-15-util
80K     libs/Vue
76K     libs/Vue-2
```

Gzipped
```
$ for i in libs/*; do tar -cz $i | wc -c | numfmt -z --to=iec --format="%.2f"; echo -e "\t\t$i"; done
56.73K    libs/Angular
122.47K   libs/Angular-2
614.10K   libs/FontAwesome-4.6.3
29.21K    libs/jQuery-2
29.46K    libs/jQuery-3
54.96K    libs/React-15
20.75K    libs/React-15-util
26.29K    libs/Vue
25.91K    libs/Vue-2

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
│   ├── react-router-4.0.0-2.min.js
│   └── redux-3.6.0.min.js
├── React-15-util
│   ├── immutable-3.8.1.min.js
│   └── recompose-0.21.2.min.js
├── Vue
│   └── vue-1.0.28.min.js
└── Vue-2
    └── vue-2.1.8.min.js

9 directories, 19 files
```
