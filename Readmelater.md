fintoolhub.github.io/
│
├── index.html                      # Your main portfolio page
├── 404.html                        # Custom 404 page
├── CNAME                           # If using custom domain
├── README.md                       # Project documentation
│
├── assets/                         # Shared assets
│   ├── css/
│   │   └── shared-styles.css      # Common styles if needed
│   ├── js/
│   │   └── theme-manager.js       # Shared theme script
│   ├── icons/                      # SVG/icons
│   └── images/                     # Shared images
│
└── financial-console/              # MAIN FINANCIAL HUB
    │
    ├── index.html                  # Financial Console Dashboard
    │                               # (The one I'll generate first)
    │
    ├── suites/                     # ALL CALCULATOR SUITES
    │   ├── financial-calculators/  # Suite 1: Core Math
    │   │   ├── index.html          # Suite landing page
    │   │   ├── sip-calculator/
    │   │   │   └── index.html
    │   │   ├── swp-calculator/
    │   │   │   └── index.html
    │   │   ├── fd-calculator/
    │   │   │   └── index.html
    │   │   ├── rd-calculator/
    │   │   │   └── index.html
    │   │   ├── compound-interest/
    │   │   │   └── index.html
    │   │   └── simple-interest/
    │   │       └── index.html
    │   │
    │   ├── loans/                  # Suite 2: All Loans
    │   │   ├── index.html
    │   │   ├── home-loan/
    │   │   ├── personal-loan/
    │   │   ├── car-loan/
    │   │   ├── education-loan/
    │   │   ├── gold-loan/
    │   │   └── emi-calculator/
    │   │
    │   ├── investments/            # Suite 3: Wealth Building
    │   │   ├── index.html
    │   │   ├── portfolio-tracker/
    │   │   ├── mutual-funds/
    │   │   ├── stock-calculator/
    │   │   ├── nps-calculator/
    │   │   └── goal-based-investing/
    │   │
    │   ├── taxes/                  # Suite 4: Tax Planning
    │   │   ├── index.html
    │   │   ├── income-tax/
    │   │   ├── capital-gains/
    │   │   ├── gst-calculator/
    │   │   └── tax-saving-planner/
    │   │
    │   ├── currency-tools/         # Suite 5: Forex
    │   │   ├── index.html
    │   │   ├── currency-converter/
    │   │   ├── denomination-calculator/
    │   │   ├── forex-profit/
    │   │   └── travel-currency/
    │   │
    │   ├── gold-metals/            # Suite 6: Commodities
    │   │   ├── index.html
    │   │   ├── gold-rate-calculator/
    │   │   ├── silver-calculator/
    │   │   ├── metal-purity/
    │   │   └── jewelry-making/
    │   │
    │   └── solar-power/            # Suite 7: Energy Finance
    │       ├── index.html
    │       ├── solar-roi/
    │       ├── panel-efficiency/
    │       └── subsidy-calculator/
    │
    ├── tools/                      # STANDALONE TOOLS (No suite)
    │   ├── budget-planner/
    │   ├── net-worth-calculator/
    │   ├── inflation-calculator/
    │   └── retirement-planner/
    │
    ├── templates/                  # REUSABLE COMPONENTS
    │   ├── calculator-base.html    # Base template for calculators
    │   ├── result-display.html     # Standard result format
    │   └── chart-template.html     # Chart/graph template
    │
    ├── data/                       # STATIC DATA FILES
    │   ├── tax-slabs.json          # Current tax rates
    │   ├── interest-rates.json     # Bank rates
    │   ├── gold-rates.json         # Metal prices
    │   └── currency-rates.json     # Forex rates (updated manually)
    │
    └── docs/                       # DOCUMENTATION
        ├── api/                    # If adding APIs later
        ├── user-guide/
        └── formulas.md             # Calculation formulas used