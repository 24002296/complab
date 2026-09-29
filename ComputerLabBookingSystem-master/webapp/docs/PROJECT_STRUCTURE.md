# Project Structure

```text
ComputerLabBookingSystem-master/
├── webapp/
│   ├── index.html
│   ├── README.md
│   ├── css/
│   │   └── styles.css
│   └── js/
│       └── app.js
├── src/                       # Original Java/MySQL implementation retained for reference
├── pom.xml
└── docs/
    └── PROJECT_STRUCTURE.md
```

The runnable enhanced interface is under `webapp/`.

The original Java source remains in the repository for reference, but the enhanced browser application does not import or call the JDBC/MySQL classes.
