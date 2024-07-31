<!-- inizializza node bypassando tutte le domande-->
npm init -y 
<!-- installa typescript local come dev dep -->
npm i typescript --save-dev
<!-- check ts version -->
npx tsc -v
<!-- compilare il codie del file .ts (secondo le caratteristiche di es6) -->
<!-- demo.ts e' il nome del file esempio -->
npx tsc demo.ts --target es6
<!-- attivare la watchmode del sistema di compilazione -->
npx tsc demo.ts --target es6 -w