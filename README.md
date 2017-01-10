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

All files (Size / Gzipped)
```
$ for i in libs/*/*; do du -sh $i | tr -d '\n' | sed -e 's/\s.*$//'; echo -en "\t"; tar -cz $i | wc -c | numfmt -z --to=iec --format="%.2f"; echo -e "\t\t$i"; done | column -t
624K  122.43K  libs/Angular-2/angular-2.0.0-beta.17.min.js
164K  56.68K   libs/Angular/angular-1.6.1.min.js
32K   7.05K    libs/FontAwesome-4.6.3/font-awesome-4.7.0.min.css
132K  108.13K  libs/FontAwesome-4.6.3/FontAwesome.otf
164K  96.37K   libs/FontAwesome-4.6.3/fontawesome-webfont.eot
436K  132.98K  libs/FontAwesome-4.6.3/fontawesome-webfont.svg
164K  96.28K   libs/FontAwesome-4.6.3/fontawesome-webfont.ttf
96K   95.77K   libs/FontAwesome-4.6.3/fontawesome-webfont.woff
76K   75.53K   libs/FontAwesome-4.6.3/fontawesome-webfont.woff2
84K   29.18K   libs/jQuery-2/jquery-2.2.4.min.js
88K   29.41K   libs/jQuery-3/jquery-3.1.1.min.js
24K   7.34K    libs/React-15/react-15.4.1.min.js
124K  36.96K   libs/React-15/react-dom-15.4.1.min.js
52K   13.56K   libs/React-15/ReactRouter-3.0.0.min.js
8.0K  1.65K    libs/React-15/ReactRouterRedux-4.0.7.min.js
8.0K  2.55K    libs/React-15/redux-3.6.0.min.js
56K   15.66K   libs/React-15-util/immutable-3.8.1.min.js
48K   11.11K   libs/React-15-util/react-router-4.0.0-alpha.6.min.js
32K   5.28K    libs/React-15-util/recompose-0.21.2.min.js
72K   25.87K   libs/Vue-2/vue-2.1.8.min.js
76K   26.24K   libs/Vue/vue-1.0.28.min.js
```
