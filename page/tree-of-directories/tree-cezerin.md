# cezerin

## structure of directories

```
.
├── config
├── docs
│   ├── api
│   └── images
├── locales
├── logs
├── public
│   ├── admin-assets
│   │   ├── css
│   │   ├── data
│   │   ├── images
│   │   │   └── apps
│   │   └── tinymce
│   │       ├── langs
│   │       ├── plugins
│   │       │   ├── codesample
│   │       │   │   └── css
│   │       │   ├── emoticons
│   │       │   │   └── img
│   │       │   └── visualblocks
│   │       │       └── css
│   │       └── skins
│   │           └── lightgray
│   │               ├── fonts
│   │               └── img
│   └── content
├── scripts
├── src
│   ├── admin
│   │   └── client
│   │       ├── apps
│   │       ├── lib
│   │       ├── modules
│   │       │   ├── apps
│   │       │   │   ├── account
│   │       │   │   │   └── components
│   │       │   │   ├── appDetails
│   │       │   │   ├── head
│   │       │   │   │   └── components
│   │       │   │   ├── serviceDetails
│   │       │   │   │   └── components
│   │       │   │   └── services
│   │       │   │       └── components
│   │       │   ├── customerGroups
│   │       │   │   ├── components
│   │       │   │   ├── edit
│   │       │   │   │   └── components
│   │       │   │   ├── head
│   │       │   │   │   └── components
│   │       │   │   ├── list
│   │       │   │   └── select
│   │       │   ├── customers
│   │       │   │   ├── edit
│   │       │   │   │   └── components
│   │       │   │   ├── editHead
│   │       │   │   │   └── components
│   │       │   │   ├── filter
│   │       │   │   │   └── components
│   │       │   │   ├── list
│   │       │   │   │   └── components
│   │       │   │   └── listHead
│   │       │   │       └── components
│   │       │   ├── files
│   │       │   │   └── list
│   │       │   │       └── components
│   │       │   │           └── fileUploader
│   │       │   ├── head
│   │       │   │   └── components
│   │       │   ├── orders
│   │       │   │   ├── edit
│   │       │   │   │   └── components
│   │       │   │   ├── editHead
│   │       │   │   │   └── components
│   │       │   │   ├── list
│   │       │   │   │   └── components
│   │       │   │   ├── listFilter
│   │       │   │   │   └── components
│   │       │   │   └── listHead
│   │       │   │       └── components
│   │       │   ├── orderStatuses
│   │       │   │   ├── components
│   │       │   │   ├── edit
│   │       │   │   │   └── components
│   │       │   │   ├── head
│   │       │   │   │   └── components
│   │       │   │   ├── list
│   │       │   │   └── select
│   │       │   ├── pages
│   │       │   │   ├── edit
│   │       │   │   │   └── components
│   │       │   │   └── list
│   │       │   │       └── components
│   │       │   ├── productCategories
│   │       │   │   ├── components
│   │       │   │   ├── edit
│   │       │   │   │   └── components
│   │       │   │   ├── head
│   │       │   │   │   └── components
│   │       │   │   ├── list
│   │       │   │   └── select
│   │       │   ├── products
│   │       │   │   ├── edit
│   │       │   │   │   ├── additional
│   │       │   │   │   │   └── components
│   │       │   │   │   ├── attributes
│   │       │   │   │   │   └── components
│   │       │   │   │   ├── general
│   │       │   │   │   │   └── components
│   │       │   │   │   ├── images
│   │       │   │   │   │   └── components
│   │       │   │   │   ├── inventory
│   │       │   │   │   │   └── components
│   │       │   │   │   ├── option
│   │       │   │   │   │   └── components
│   │       │   │   │   └── variants
│   │       │   │   │       └── components
│   │       │   │   ├── editHead
│   │       │   │   │   └── components
│   │       │   │   ├── list
│   │       │   │   │   └── components
│   │       │   │   ├── listFilter
│   │       │   │   │   └── components
│   │       │   │   └── listHead
│   │       │   │       └── components
│   │       │   ├── reports
│   │       │   │   └── ordersBar
│   │       │   ├── settings
│   │       │   │   ├── checkout
│   │       │   │   │   └── components
│   │       │   │   ├── checkoutFields
│   │       │   │   │   └── components
│   │       │   │   ├── email
│   │       │   │   │   └── components
│   │       │   │   ├── emailTemplates
│   │       │   │   │   └── components
│   │       │   │   ├── general
│   │       │   │   │   └── components
│   │       │   │   ├── generalLogo
│   │       │   │   │   └── components
│   │       │   │   ├── paymentGateway
│   │       │   │   │   └── components
│   │       │   │   ├── payments
│   │       │   │   │   └── components
│   │       │   │   ├── paymentsEdit
│   │       │   │   │   └── components
│   │       │   │   ├── shipping
│   │       │   │   │   └── components
│   │       │   │   ├── shippingEdit
│   │       │   │   │   └── components
│   │       │   │   ├── smtp
│   │       │   │   │   └── components
│   │       │   │   ├── theme
│   │       │   │   │   └── components
│   │       │   │   ├── themeSettings
│   │       │   │   │   └── components
│   │       │   │   ├── tokens
│   │       │   │   │   ├── edit
│   │       │   │   │   │   └── components
│   │       │   │   │   └── list
│   │       │   │   │       └── components
│   │       │   │   └── webhooks
│   │       │   │       ├── edit
│   │       │   │       │   └── components
│   │       │   │       └── list
│   │       │   │           └── components
│   │       │   └── shared
│   │       │       ├── confirmation
│   │       │       ├── deleteConfirmation
│   │       │       ├── editor
│   │       │       ├── form
│   │       │       ├── imageUpload
│   │       │       ├── imageUploadMultiple
│   │       │       ├── productSearch
│   │       │       └── tinymce
│   │       │           ├── components
│   │       │           └── helpers
│   │       └── routes
│   │           ├── apps
│   │           ├── customers
│   │           │   └── groups
│   │           ├── orders
│   │           │   └── statuses
│   │           ├── pages
│   │           └── products
│   │               └── categories
│   ├── api
│   │   └── server
│   │       ├── lib
│   │       ├── paymentGateways
│   │       ├── routes
│   │       └── services
│   │           ├── apps
│   │           ├── customers
│   │           ├── orders
│   │           ├── pages
│   │           ├── products
│   │           ├── security
│   │           ├── settings
│   │           └── theme
│   └── store
│       ├── client
│       ├── server
│       └── shared
│           ├── analytics
│           ├── containers
│           └── lib
└── theme
    ├── assets
    │   ├── images
    │   │   ├── icons
    │   │   └── payment
    │   └── scss
    ├── locales
    ├── settings
    └── src
        ├── components
        │   ├── checkoutForm
        │   │   └── paymentForm
        │   │       └── StripeElements
        │   ├── comments
        │   ├── header
        │   ├── pageList
        │   ├── productDetails
        │   ├── productFilter
        │   ├── productList
        │   └── products
        ├── containers
        └── lib
```

228 directories
