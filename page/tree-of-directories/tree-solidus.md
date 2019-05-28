# solidus

## structure of directories

```
.
├── api
│   ├── app
│   │   ├── controllers
│   │   │   └── spree
│   │   │       └── api
│   │   ├── helpers
│   │   │   └── spree
│   │   │       └── api
│   │   ├── models
│   │   │   └── spree
│   │   └── views
│   │       └── spree
│   │           └── api
│   │               ├── address_books
│   │               ├── addresses
│   │               ├── adjustments
│   │               ├── config
│   │               ├── countries
│   │               ├── credit_cards
│   │               ├── errors
│   │               ├── images
│   │               ├── inventory_units
│   │               ├── line_items
│   │               ├── option_types
│   │               ├── option_values
│   │               ├── orders
│   │               ├── payments
│   │               │   └── source_views
│   │               ├── product_properties
│   │               ├── products
│   │               ├── promotions
│   │               ├── properties
│   │               ├── return_authorizations
│   │               ├── shared
│   │               ├── shipments
│   │               ├── shipping_rates
│   │               ├── states
│   │               ├── stock_items
│   │               ├── stock_locations
│   │               ├── stock_movements
│   │               ├── store_credit_events
│   │               ├── stores
│   │               ├── taxonomies
│   │               ├── taxons
│   │               ├── users
│   │               ├── variants
│   │               └── zones
│   ├── config
│   │   └── locales
│   ├── db
│   │   └── migrate
│   ├── lib
│   │   └── spree
│   │       └── api
│   │           ├── responders
│   │           └── testing_support
│   ├── script
│   └── spec
│       ├── controllers
│       │   └── spree
│       │       └── api
│       ├── features
│       ├── fixtures
│       ├── models
│       │   └── spree
│       ├── requests
│       │   ├── api
│       │   └── spree
│       │       └── api
│       ├── shared_examples
│       ├── support
│       └── test_views
│           └── spree
│               └── api
│                   └── widgets
├── backend
│   ├── app
│   │   ├── assets
│   │   │   ├── config
│   │   │   ├── images
│   │   │   ├── javascripts
│   │   │   │   └── spree
│   │   │   │       └── backend
│   │   │   │           ├── checkouts
│   │   │   │           ├── collections
│   │   │   │           ├── components
│   │   │   │           ├── images
│   │   │   │           ├── models
│   │   │   │           ├── orders
│   │   │   │           ├── payments
│   │   │   │           ├── promotions
│   │   │   │           ├── returns
│   │   │   │           ├── templates
│   │   │   │           │   ├── orders
│   │   │   │           │   │   └── customer_details
│   │   │   │           │   ├── products
│   │   │   │           │   ├── promotions
│   │   │   │           │   │   ├── calculators
│   │   │   │           │   │   │   └── fields
│   │   │   │           │   │   └── rules
│   │   │   │           │   ├── stock_items
│   │   │   │           │   ├── taxons
│   │   │   │           │   └── variants
│   │   │   │           └── views
│   │   │   │               ├── calculators
│   │   │   │               ├── cart
│   │   │   │               ├── images
│   │   │   │               ├── order
│   │   │   │               ├── payment
│   │   │   │               ├── promotions
│   │   │   │               ├── stock
│   │   │   │               ├── tables
│   │   │   │               └── zones
│   │   │   └── stylesheets
│   │   │       └── spree
│   │   │           └── backend
│   │   │               ├── components
│   │   │               ├── globals
│   │   │               │   └── mixins
│   │   │               ├── plugins
│   │   │               ├── sections
│   │   │               ├── shared
│   │   │               └── themes
│   │   │                   └── blue_steel
│   │   │                       └── globals
│   │   ├── controllers
│   │   │   └── spree
│   │   │       └── admin
│   │   │           └── orders
│   │   ├── helpers
│   │   │   └── spree
│   │   │       └── admin
│   │   ├── models
│   │   │   └── spree
│   │   └── views
│   │       ├── kaminari
│   │       │   └── solidus_admin
│   │       └── spree
│   │           ├── admin
│   │           │   ├── adjustment_reasons
│   │           │   │   └── shared
│   │           │   ├── adjustments
│   │           │   ├── cancellations
│   │           │   ├── customer_returns
│   │           │   ├── dashboards
│   │           │   ├── images
│   │           │   ├── log_entries
│   │           │   ├── option_types
│   │           │   ├── orders
│   │           │   │   ├── confirm
│   │           │   │   └── customer_details
│   │           │   ├── payment_methods
│   │           │   ├── payments
│   │           │   │   ├── source_forms
│   │           │   │   └── source_views
│   │           │   ├── prices
│   │           │   ├── product_properties
│   │           │   ├── products
│   │           │   ├── promotion_actions
│   │           │   ├── promotion_categories
│   │           │   ├── promotion_code_batches
│   │           │   ├── promotion_codes
│   │           │   ├── promotion_rules
│   │           │   ├── promotions
│   │           │   │   ├── actions
│   │           │   │   ├── calculators
│   │           │   │   │   ├── distributed_amount
│   │           │   │   │   ├── flat_rate
│   │           │   │   │   ├── tiered_flat_rate
│   │           │   │   │   └── tiered_percent
│   │           │   │   └── rules
│   │           │   ├── properties
│   │           │   ├── refund_reasons
│   │           │   │   └── shared
│   │           │   ├── refunds
│   │           │   ├── reimbursements
│   │           │   ├── reimbursement_types
│   │           │   ├── return_authorizations
│   │           │   ├── return_reasons
│   │           │   ├── search
│   │           │   ├── shared
│   │           │   │   ├── named_types
│   │           │   │   └── preference_fields
│   │           │   ├── shipping_categories
│   │           │   ├── shipping_methods
│   │           │   ├── stock_items
│   │           │   ├── stock_locations
│   │           │   ├── stock_movements
│   │           │   ├── store_credit_reasons
│   │           │   │   └── shared
│   │           │   ├── store_credits
│   │           │   ├── stores
│   │           │   ├── style_guide
│   │           │   │   └── topics
│   │           │   │       ├── components
│   │           │   │       ├── forms
│   │           │   │       ├── layout
│   │           │   │       ├── messaging
│   │           │   │       ├── tables
│   │           │   │       └── typography
│   │           │   ├── tax_categories
│   │           │   ├── taxonomies
│   │           │   ├── taxons
│   │           │   ├── tax_rates
│   │           │   ├── users
│   │           │   ├── variants
│   │           │   └── zones
│   │           └── layouts
│   ├── config
│   │   └── initializers
│   ├── lib
│   │   └── spree
│   │       └── backend
│   ├── script
│   ├── spec
│   │   ├── controllers
│   │   │   └── spree
│   │   │       └── admin
│   │   │           └── orders
│   │   ├── features
│   │   │   └── admin
│   │   │       ├── configuration
│   │   │       ├── orders
│   │   │       ├── payments
│   │   │       ├── products
│   │   │       │   └── edit
│   │   │       └── promotions
│   │   ├── helpers
│   │   │   └── admin
│   │   ├── javascripts
│   │   │   ├── fixtures
│   │   │   │   └── number_with_currency
│   │   │   ├── support
│   │   │   └── views
│   │   ├── models
│   │   │   └── spree
│   │   │       └── backend_configuration
│   │   ├── support
│   │   │   └── feature
│   │   ├── test_views
│   │   │   └── spree
│   │   │       └── admin
│   │   │           └── widgets
│   │   └── views
│   │       └── spree
│   │           └── admin
│   │               └── shared
│   └── vendor
│       └── assets
│           ├── images
│           │   └── solidus_admin
│           ├── javascripts
│           │   └── solidus_admin
│           │       ├── flatpickr
│           │       └── select2_locales
│           └── stylesheets
│               └── solidus_admin
│                   ├── bootstrap
│                   │   ├── mixins
│                   │   └── utilities
│                   └── flatpickr
├── bin
├── core
│   ├── app
│   │   ├── assets
│   │   │   ├── config
│   │   │   ├── images
│   │   │   │   ├── logo
│   │   │   │   └── noimage
│   │   │   └── javascripts
│   │   ├── controllers
│   │   │   └── spree
│   │   ├── helpers
│   │   │   └── spree
│   │   ├── jobs
│   │   │   └── spree
│   │   ├── mailers
│   │   │   └── spree
│   │   ├── models
│   │   │   ├── concerns
│   │   │   │   └── spree
│   │   │   └── spree
│   │   │       ├── calculator
│   │   │       │   ├── returns
│   │   │       │   └── shipping
│   │   │       ├── gallery
│   │   │       ├── gateway
│   │   │       ├── order
│   │   │       ├── payment
│   │   │       ├── payment_method
│   │   │       ├── product
│   │   │       ├── promotion
│   │   │       │   ├── actions
│   │   │       │   └── rules
│   │   │       ├── promotion_code
│   │   │       ├── promotion_handler
│   │   │       ├── reimbursement
│   │   │       ├── reimbursement_type
│   │   │       ├── return_item
│   │   │       │   ├── eligibility_validator
│   │   │       │   └── exchange_variant_eligibility
│   │   │       ├── stock
│   │   │       │   ├── allocator
│   │   │       │   ├── location_filter
│   │   │       │   ├── location_sorter
│   │   │       │   └── splitter
│   │   │       ├── store_selector
│   │   │       ├── tax
│   │   │       ├── tax_calculator
│   │   │       ├── validations
│   │   │       ├── variant
│   │   │       └── wallet
│   │   └── views
│   │       ├── layouts
│   │       │   └── spree
│   │       └── spree
│   │           ├── carton_mailer
│   │           ├── order_mailer
│   │           ├── promotion_code_batch_mailer
│   │           ├── reimbursement_mailer
│   │           ├── shared
│   │           └── test_mailer
│   ├── config
│   │   ├── initializers
│   │   └── locales
│   ├── db
│   │   ├── default
│   │   │   └── spree
│   │   └── migrate
│   ├── lib
│   │   ├── generators
│   │   │   └── spree
│   │   │       ├── custom_user
│   │   │       │   └── templates
│   │   │       ├── dummy
│   │   │       │   └── templates
│   │   │       │       └── rails
│   │   │       │           └── script
│   │   │       └── install
│   │   │           └── templates
│   │   │               ├── config
│   │   │               │   └── initializers
│   │   │               └── vendor
│   │   │                   └── assets
│   │   │                       ├── javascripts
│   │   │                       │   └── spree
│   │   │                       │       ├── backend
│   │   │                       │       └── frontend
│   │   │                       └── stylesheets
│   │   │                           └── spree
│   │   │                               ├── backend
│   │   │                               └── frontend
│   │   ├── solidus
│   │   │   └── migrations
│   │   ├── spree
│   │   │   ├── core
│   │   │   │   ├── controller_helpers
│   │   │   │   ├── environment
│   │   │   │   ├── importer
│   │   │   │   ├── search
│   │   │   │   └── validators
│   │   │   ├── event
│   │   │   │   ├── adapters
│   │   │   │   └── processors
│   │   │   ├── mailer_previews
│   │   │   ├── permission_sets
│   │   │   ├── preferences
│   │   │   ├── promo
│   │   │   └── testing_support
│   │   │       ├── dummy_app
│   │   │       │   ├── assets
│   │   │       │   │   ├── javascripts
│   │   │       │   │   │   └── spree
│   │   │       │   │   │       ├── backend
│   │   │       │   │   │       └── frontend
│   │   │       │   │   └── stylesheets
│   │   │       │   │       └── spree
│   │   │       │   │           ├── backend
│   │   │       │   │           └── frontend
│   │   │       │   └── views
│   │   │       │       └── layouts
│   │   │       ├── factories
│   │   │       └── shared_examples
│   │   └── tasks
│   │       └── migrations
│   ├── script
│   ├── spec
│   │   ├── fixtures
│   │   ├── helpers
│   │   ├── jobs
│   │   ├── lib
│   │   │   ├── search
│   │   │   ├── spree
│   │   │   │   ├── core
│   │   │   │   │   ├── controller_helpers
│   │   │   │   │   ├── importer
│   │   │   │   │   ├── testing_support
│   │   │   │   │   │   └── factories
│   │   │   │   │   └── validators
│   │   │   │   ├── event
│   │   │   │   └── permission_sets
│   │   │   └── tasks
│   │   │       └── migrations
│   │   ├── mailers
│   │   ├── migrate
│   │   ├── models
│   │   │   └── spree
│   │   │       ├── calculator
│   │   │       │   ├── refunds
│   │   │       │   └── shipping
│   │   │       ├── concerns
│   │   │       ├── gallery
│   │   │       ├── gateway
│   │   │       ├── order
│   │   │       ├── payment
│   │   │       ├── payment_method
│   │   │       ├── permission_sets
│   │   │       ├── preferences
│   │   │       ├── product
│   │   │       ├── promotion
│   │   │       │   ├── actions
│   │   │       │   └── rules
│   │   │       ├── promotion_code
│   │   │       ├── promotion_handler
│   │   │       ├── reimbursement
│   │   │       ├── reimbursement_type
│   │   │       ├── return_item
│   │   │       │   ├── eligibility_validator
│   │   │       │   └── exchange_variant_eligibility
│   │   │       ├── stock
│   │   │       │   ├── allocator
│   │   │       │   ├── location_filter
│   │   │       │   ├── location_sorter
│   │   │       │   └── splitter
│   │   │       ├── store_selector
│   │   │       ├── tax
│   │   │       ├── tax_calculator
│   │   │       ├── validations
│   │   │       └── variant
│   │   ├── shared_examples
│   │   └── support
│   │       ├── concerns
│   │       └── shared_contexts
│   └── vendor
│       └── assets
│           ├── javascripts
│           └── stylesheets
├── frontend
│   ├── app
│   │   ├── assets
│   │   │   ├── config
│   │   │   ├── images
│   │   │   │   ├── credit_cards
│   │   │   │   │   └── icons
│   │   │   │   ├── icons
│   │   │   │   └── spree
│   │   │   │       └── frontend
│   │   │   ├── javascripts
│   │   │   │   └── spree
│   │   │   │       └── frontend
│   │   │   │           └── checkout
│   │   │   └── stylesheets
│   │   │       └── spree
│   │   │           └── frontend
│   │   ├── controllers
│   │   │   └── spree
│   │   ├── helpers
│   │   │   └── spree
│   │   ├── models
│   │   │   └── spree
│   │   └── views
│   │       └── spree
│   │           ├── address
│   │           ├── checkout
│   │           │   ├── existing_payment
│   │           │   └── payment
│   │           ├── content
│   │           ├── coupon_codes
│   │           ├── home
│   │           ├── layouts
│   │           ├── orders
│   │           ├── payments
│   │           ├── products
│   │           ├── shared
│   │           ├── store
│   │           └── taxons
│   ├── config
│   │   └── initializers
│   ├── lib
│   │   ├── generators
│   │   │   └── solidus
│   │   │       └── views
│   │   ├── spree
│   │   │   └── frontend
│   │   │       └── middleware
│   │   └── tasks
│   ├── script
│   └── spec
│       ├── controllers
│       │   └── spree
│       ├── features
│       │   └── caching
│       ├── fixtures
│       ├── generators
│       │   └── solidus
│       │       └── views
│       ├── helpers
│       ├── support
│       │   └── shared_contexts
│       └── views
│           └── spree
│               └── checkout
├── guides
│   ├── data
│   │   └── nav
│   ├── helpers
│   ├── lib
│   └── source
│       ├── assets
│       │   ├── images
│       │   │   ├── favicon
│       │   │   ├── icons
│       │   │   └── social-icons
│       │   ├── javascripts
│       │   │   ├── modernizr
│       │   │   └── vendor
│       │   └── stylesheets
│       │       ├── components
│       │       ├── mixins
│       │       └── vendor
│       │           ├── aos
│       │           ├── bootstrap
│       │           │   └── theme
│       │           │       ├── mixins
│       │           │       └── utilities
│       │           ├── nouislider
│       │           └── prism
│       ├── developers
│       │   ├── adjustments
│       │   ├── api
│       │   ├── assets
│       │   ├── calculators
│       │   ├── events
│       │   ├── extensions
│       │   ├── getting-started
│       │   ├── inventory
│       │   ├── locations
│       │   ├── orders
│       │   ├── payments
│       │   ├── preferences
│       │   ├── products-and-variants
│       │   ├── promotions
│       │   ├── returns
│       │   ├── shipments
│       │   ├── taxation
│       │   ├── upgrades
│       │   ├── users
│       │   └── views
│       ├── layouts
│       ├── partials
│       └── users
│           ├── orders
│           ├── products
│           ├── promotions
│           ├── settings
│           ├── stock
│           └── users
├── lib
│   └── demo
└── sample
    ├── db
    │   └── samples
    │       └── images
    ├── lib
    │   ├── spree
    │   └── tasks
    └── spec
        └── lib
```

578 directories
