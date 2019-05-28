# spree

## structure of directories

```
.
├── api
│   ├── app
│   │   ├── assets
│   │   │   └── javascripts
│   │   │       └── spree
│   │   │           └── api
│   │   │               └── storefront
│   │   ├── controllers
│   │   │   ├── concerns
│   │   │   │   └── spree
│   │   │   │       └── api
│   │   │   │           └── v2
│   │   │   │               └── storefront
│   │   │   └── spree
│   │   │       └── api
│   │   │           ├── v1
│   │   │           └── v2
│   │   │               └── storefront
│   │   │                   └── account
│   │   ├── helpers
│   │   │   └── spree
│   │   │       └── api
│   │   │           └── v2
│   │   ├── models
│   │   │   ├── concerns
│   │   │   │   └── spree
│   │   │   └── spree
│   │   ├── serializers
│   │   │   └── spree
│   │   │       └── v2
│   │   │           └── storefront
│   │   └── views
│   │       └── spree
│   │           └── api
│   │               ├── errors
│   │               └── v1
│   │                   ├── addresses
│   │                   ├── adjustments
│   │                   ├── countries
│   │                   ├── credit_cards
│   │                   ├── customer_returns
│   │                   ├── images
│   │                   ├── inventory_units
│   │                   ├── line_items
│   │                   ├── option_types
│   │                   ├── option_values
│   │                   ├── orders
│   │                   ├── payments
│   │                   ├── product_properties
│   │                   ├── products
│   │                   ├── promotions
│   │                   ├── properties
│   │                   ├── reimbursements
│   │                   ├── return_authorizations
│   │                   ├── shared
│   │                   ├── shipments
│   │                   ├── shipping_rates
│   │                   ├── states
│   │                   ├── stock_items
│   │                   ├── stock_locations
│   │                   ├── stock_movements
│   │                   ├── stores
│   │                   ├── tags
│   │                   ├── taxonomies
│   │                   ├── taxons
│   │                   ├── users
│   │                   ├── variants
│   │                   └── zones
│   ├── config
│   │   ├── initializers
│   │   └── locales
│   ├── db
│   │   └── migrate
│   ├── docs
│   │   ├── oauth
│   │   └── v2
│   │       └── storefront
│   ├── lib
│   │   └── spree
│   │       └── api
│   │           ├── responders
│   │           └── testing_support
│   │               └── v2
│   ├── script
│   └── spec
│       ├── controllers
│       │   └── spree
│       │       └── api
│       │           ├── v1
│       │           └── v2
│       ├── fixtures
│       ├── models
│       │   └── spree
│       ├── requests
│       │   └── spree
│       │       ├── api
│       │       │   └── v2
│       │       │       └── storefront
│       │       │           └── account
│       │       └── oauth
│       ├── shared_examples
│       └── support
├── backend
│   ├── app
│   │   ├── assets
│   │   │   ├── images
│   │   │   │   ├── admin
│   │   │   │   └── credit_cards
│   │   │   ├── javascripts
│   │   │   │   └── spree
│   │   │   │       ├── backend
│   │   │   │       │   ├── checkouts
│   │   │   │       │   ├── orders
│   │   │   │       │   ├── payments
│   │   │   │       │   ├── returns
│   │   │   │       │   └── users
│   │   │   │       └── frontend
│   │   │   └── stylesheets
│   │   │       └── spree
│   │   │           ├── backend
│   │   │           │   ├── components
│   │   │           │   ├── global
│   │   │           │   ├── plugins
│   │   │           │   └── shared
│   │   │           └── frontend
│   │   ├── controllers
│   │   │   └── spree
│   │   │       └── admin
│   │   │           └── orders
│   │   ├── helpers
│   │   │   └── spree
│   │   │       └── admin
│   │   ├── models
│   │   │   └── spree
│   │   │       └── admin
│   │   └── views
│   │       ├── kaminari
│   │       │   └── twitter-bootstrap-4
│   │       └── spree
│   │           ├── admin
│   │           │   ├── adjustments
│   │           │   ├── countries
│   │           │   ├── customer_returns
│   │           │   ├── general_settings
│   │           │   ├── images
│   │           │   ├── log_entries
│   │           │   ├── option_types
│   │           │   ├── orders
│   │           │   │   └── customer_details
│   │           │   ├── payment_methods
│   │           │   ├── payments
│   │           │   │   ├── source_forms
│   │           │   │   └── source_views
│   │           │   ├── product_properties
│   │           │   ├── products
│   │           │   ├── promotion_actions
│   │           │   ├── promotion_categories
│   │           │   ├── promotion_rules
│   │           │   ├── promotions
│   │           │   │   ├── actions
│   │           │   │   ├── calculators
│   │           │   │   │   ├── tiered_flat_rate
│   │           │   │   │   └── tiered_percent
│   │           │   │   └── rules
│   │           │   ├── properties
│   │           │   ├── prototypes
│   │           │   ├── refund_reasons
│   │           │   ├── refunds
│   │           │   ├── reimbursements
│   │           │   ├── reimbursement_types
│   │           │   ├── reports
│   │           │   ├── return_authorization_reasons
│   │           │   ├── return_authorizations
│   │           │   ├── return_index
│   │           │   ├── roles
│   │           │   ├── shared
│   │           │   │   ├── named_types
│   │           │   │   └── sub_menu
│   │           │   ├── shipping_categories
│   │           │   ├── shipping_methods
│   │           │   ├── state_changes
│   │           │   ├── states
│   │           │   ├── stock_items
│   │           │   ├── stock_locations
│   │           │   ├── stock_movements
│   │           │   ├── stock_transfers
│   │           │   ├── store_credit_categories
│   │           │   ├── store_credits
│   │           │   ├── stores
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
│   │   ├── generators
│   │   │   └── spree
│   │   │       └── backend
│   │   │           └── copy_views
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
│   │   │       ├── products
│   │   │       │   └── edit
│   │   │       ├── promotions
│   │   │       ├── refund_reasons
│   │   │       ├── reimbursement_type
│   │   │       ├── return_authorization_reasons
│   │   │       └── returns
│   │   ├── helpers
│   │   │   └── spree
│   │   │       └── admin
│   │   ├── models
│   │   │   └── spree
│   │   ├── routing
│   │   ├── support
│   │   └── test_views
│   │       └── spree
│   │           └── admin
│   │               ├── dummy_models
│   │               └── submodule
│   │                   └── posts
│   └── vendor
│       └── assets
│           ├── javascripts
│           │   └── jquery.jstree
│           └── stylesheets
│               └── jquery.jstree
│                   └── themes
│                       └── spree
├── cmd
│   ├── bin
│   └── lib
│       └── spree_cmd
│           └── templates
│               └── extension
│                   ├── app
│                   │   └── assets
│                   │       ├── javascripts
│                   │       │   └── spree
│                   │       │       ├── backend
│                   │       │       └── frontend
│                   │       └── stylesheets
│                   │           └── spree
│                   │               ├── backend
│                   │               └── frontend
│                   ├── bin
│                   ├── config
│                   │   └── locales
│                   ├── gemfiles
│                   ├── lib
│                   │   ├── %file_name%
│                   │   └── generators
│                   │       └── %file_name%
│                   │           └── install
│                   └── spec
│                       └── support
├── core
│   ├── app
│   │   ├── assets
│   │   │   ├── images
│   │   │   │   ├── logo
│   │   │   │   └── noimage
│   │   │   └── javascripts
│   │   ├── controllers
│   │   │   └── spree
│   │   ├── finders
│   │   │   └── spree
│   │   │       ├── countries
│   │   │       ├── credit_cards
│   │   │       ├── line_items
│   │   │       ├── orders
│   │   │       ├── products
│   │   │       └── taxons
│   │   ├── helpers
│   │   │   └── spree
│   │   ├── mailers
│   │   │   └── spree
│   │   ├── models
│   │   │   ├── concerns
│   │   │   │   └── spree
│   │   │   ├── friendly_id
│   │   │   └── spree
│   │   │       ├── adjustable
│   │   │       │   └── adjuster
│   │   │       ├── asset
│   │   │       │   └── support
│   │   │       ├── calculator
│   │   │       │   ├── returns
│   │   │       │   └── shipping
│   │   │       ├── gateway
│   │   │       ├── image
│   │   │       │   └── configuration
│   │   │       ├── order
│   │   │       ├── payment
│   │   │       ├── payment_method
│   │   │       ├── preferences
│   │   │       ├── promotion
│   │   │       │   ├── actions
│   │   │       │   └── rules
│   │   │       ├── promotion_handler
│   │   │       ├── reimbursement
│   │   │       ├── reimbursement_type
│   │   │       ├── return_item
│   │   │       │   ├── eligibility_validator
│   │   │       │   └── exchange_variant_eligibility
│   │   │       ├── stock
│   │   │       │   └── splitter
│   │   │       ├── taxon_image
│   │   │       │   └── configuration
│   │   │       └── validations
│   │   ├── paginators
│   │   │   └── spree
│   │   │       └── shared
│   │   ├── services
│   │   │   └── spree
│   │   │       ├── cart
│   │   │       └── checkout
│   │   ├── sorters
│   │   │   └── spree
│   │   │       ├── orders
│   │   │       └── products
│   │   ├── validators
│   │   └── views
│   │       ├── layouts
│   │       │   └── spree
│   │       └── spree
│   │           ├── order_mailer
│   │           ├── reimbursement_mailer
│   │           ├── shared
│   │           ├── shipment_mailer
│   │           └── test_mailer
│   ├── config
│   │   ├── initializers
│   │   └── locales
│   ├── db
│   │   ├── default
│   │   │   └── spree
│   │   └── migrate
│   ├── lib
│   │   ├── friendly_id
│   │   ├── generators
│   │   │   └── spree
│   │   │       ├── custom_user
│   │   │       │   └── templates
│   │   │       ├── dummy
│   │   │       │   └── templates
│   │   │       │       ├── initializers
│   │   │       │       └── rails
│   │   │       │           └── script
│   │   │       ├── dummy_model
│   │   │       │   └── templates
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
│   │   ├── spree
│   │   │   ├── core
│   │   │   │   ├── controller_helpers
│   │   │   │   ├── importer
│   │   │   │   ├── query_filters
│   │   │   │   └── search
│   │   │   ├── i18n
│   │   │   └── testing_support
│   │   │       └── factories
│   │   └── tasks
│   ├── script
│   ├── spec
│   │   ├── filters
│   │   │   └── spree
│   │   │       └── products
│   │   ├── fixtures
│   │   ├── helpers
│   │   ├── lib
│   │   │   ├── search
│   │   │   ├── spree
│   │   │   │   └── core
│   │   │   │       ├── controller_helpers
│   │   │   │       ├── importer
│   │   │   │       └── query_filters
│   │   │   └── tasks
│   │   ├── mailers
│   │   ├── models
│   │   │   └── spree
│   │   │       ├── adjustable
│   │   │       │   └── adjuster
│   │   │       ├── calculator
│   │   │       │   ├── refunds
│   │   │       │   └── shipping
│   │   │       ├── concerns
│   │   │       ├── gateway
│   │   │       ├── order
│   │   │       ├── payment
│   │   │       ├── payment_method
│   │   │       ├── preferences
│   │   │       ├── product
│   │   │       ├── promotion
│   │   │       │   ├── actions
│   │   │       │   └── rules
│   │   │       ├── promotion_handler
│   │   │       ├── reimbursement
│   │   │       ├── reimbursement_type
│   │   │       ├── return_item
│   │   │       │   ├── eligibility_validator
│   │   │       │   └── exchange_variant_eligibility
│   │   │       └── stock
│   │   │           └── splitter
│   │   ├── services
│   │   │   └── spree
│   │   │       ├── cart
│   │   │       └── checkout
│   │   ├── support
│   │   │   └── concerns
│   │   └── validators
│   └── vendor
│       └── assets
│           └── javascripts
├── frontend
│   ├── app
│   │   ├── assets
│   │   │   ├── images
│   │   │   │   ├── credit_cards
│   │   │   │   │   └── icons
│   │   │   │   └── logo
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
│   │       ├── kaminari
│   │       │   └── twitter-bootstrap-4
│   │       └── spree
│   │           ├── address
│   │           ├── checkout
│   │           │   └── payment
│   │           ├── content
│   │           ├── home
│   │           ├── layouts
│   │           ├── orders
│   │           ├── products
│   │           ├── shared
│   │           └── taxons
│   ├── config
│   │   └── initializers
│   ├── lib
│   │   ├── generators
│   │   │   └── spree
│   │   │       └── frontend
│   │   │           └── copy_views
│   │   └── spree
│   │       └── frontend
│   │           └── middleware
│   ├── script
│   ├── spec
│   │   ├── controllers
│   │   │   └── spree
│   │   ├── features
│   │   │   └── caching
│   │   ├── fixtures
│   │   ├── helpers
│   │   ├── requests
│   │   ├── support
│   │   │   └── shared_contexts
│   │   └── views
│   │       └── spree
│   │           └── checkout
│   └── vendor
│       └── assets
│           └── javascripts
├── guides
│   ├── src
│   │   ├── components
│   │   │   ├── base
│   │   │   └── helpers
│   │   ├── content
│   │   │   ├── api
│   │   │   ├── developer
│   │   │   │   ├── core
│   │   │   │   ├── customization
│   │   │   │   ├── source
│   │   │   │   ├── tutorials
│   │   │   │   └── upgrades
│   │   │   ├── release_notes
│   │   │   └── user
│   │   │       ├── configuration
│   │   │       ├── orders
│   │   │       ├── payments
│   │   │       ├── products
│   │   │       ├── promotions
│   │   │       ├── reports
│   │   │       ├── shipments
│   │   │       └── users
│   │   ├── data
│   │   ├── images
│   │   │   ├── developer
│   │   │   │   └── core
│   │   │   └── user
│   │   │       ├── config
│   │   │       ├── orders
│   │   │       ├── payments
│   │   │       ├── products
│   │   │       ├── promotions
│   │   │       ├── shipments
│   │   │       └── users
│   │   ├── pages
│   │   │   └── api
│   │   │       └── v2
│   │   ├── styles
│   │   ├── templates
│   │   └── utils
│   └── static
├── lib
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

554 directories
