#### Unix-like
```
clojure -M -m cljs.main -co build.edn -c
node dist/index.js
```
---
#### Windows
```
curl -LO https://github.com/clojure/clojurescript/releases/download/r1.10.866/cljs.jar
java.exe -cp "cljs.jar;src" cljs.main -co build.edn -c
node dist\index.js
```
