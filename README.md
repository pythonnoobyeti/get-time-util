# How to install
```
npm i onpoint-backend-test-filenko --save
```

# How to use
```
const myDateModule = require("onpoint-backend-test-filenko");

myDateModule.main();
```

# Options
* current - return current date on UTF format;
* current -y(--year)/-m(--month)/-d(--date) - return current year/month/day;
* current add -y(--year) value/-m(--month) value/-d(--date) value - return the increased date;
* current add -y(--year) value/-m(--month) value/-d(--date) value - return the reduced date;
