# inf165-webdev-project
Βασική δομή ενός project για τις ανάγκες της εργασίας 2 του μαθήματος INF165.

```bash
.
├── index.js
├── models
└── public
    ├── index.html
    ├── css
    |   └── style.css
    └── js
        └── main.js
```

Οι απαραίτητες εξαρτήσεις υπάρχουν ήδη στο package.json. 
Μπορείτε να τις εγκαταστήσετε με χρήση της εντολής
```
npm install
```

Για να δοκιμάσετε την εφαρμογή σας μπορείτε να την ξεκινήσετε με την εντολή
```
node index.js
```

Βέβαια, μετά από κάθε αλλαγή στον κώδικα του server θα πρέπει να κάνετε επανεκκίνηση της εφαρμογής. Για διευκόλυνσή σας μπορείτε να ξεκινήσετε την εφαρμογή με τη βοήθεια του εργαλείου nodemon ως εξής:

```
nodemon index.js
```

Κάθε φορά που αλλάζετε τον κώδικα του server, το nodemon επανεκκινεί αυτόματα τον server.

## Χρήση του express-handlebars

Εγκατάσταση του `express-handlebars`

```
npm install express-handlebars --save
```

Προτείνεται η εξής οργάνωση των αρχείων υποδειγμάτων (templates)

```bash
.
├── index.js
└── views
    ├── home.handlebars
    ├── list-contacts.handlebars
    ├── view-contact.handlebars
    ...
    └── layouts
        └── main.handlebars

        
```

