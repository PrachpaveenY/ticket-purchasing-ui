# Ticket Purchasing UI
- View my project website = null
- Project : Ticket Purchasing UI
- Tools = Vue.js
</br>

#### Details
- TicketPurchasingFull (complete)
- TicketList (complete)
- Payment (complete)
- SummaryAll (complete)
</br>

- Workflow
    ```
     1. 
    ```
</br>

## Run project
- Run command :
    ```
    $ npm install
    ```
    ```
    $ npm run dev
    ```

</br>

### Structure :
```
📁ticket-purchasing-ui
│
└── 📁.vscode
│
└── 📁backend
│
└── 📁dist			        	    = deploy Vue.js
│
└── 📁node_modules
│
└── 📁public
│
└── 📁src				             = main Vue.js file (์Complete)
│   └── 📁assets
│   └── 📁components
│   │   │
│   │   ├── 📁Auth
│   │   │   ├── 📄Payment.vue                   = Payment section (main file)
│   │   │   ├── 📄SummaryTotal.vue              = Total section (main file)
│   │   │   ├── 📄TicketList-Delivery.vue       = Delivery section (main file)
│   │   │   └── 📄TicketPurchasingFull.vue      = Combine all sections on one page (main file)
│   │   │
│   │   ├── 📁layouts
│   │   │   └── 📄TheHeader.vue                 = Header Pages (main file)
│   │   │
│   │   └── 📁Page
│   │       │
│   │       ├── 📄PageButton.vue                = design CSS for Pages (main file)
│   │       └── 📄PageCard.vue                  = design CSS for Pages (main file)
│   │
│   ├── 📄App.vue
│   └── 📄main.js                               = (main file)
│   └── 📄style.css
│       			
└── 📄.gitignore	
└── 📄index.html
└── 📄package-lock.json
└── 📄package.json					
└── 📄README.md
└── 📄vite.config.js
```

</br></br></br></br>

## Test
### Ticket Purchasing UI
- Create payment page