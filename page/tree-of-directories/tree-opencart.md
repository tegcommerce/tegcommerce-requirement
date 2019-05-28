# opencart

## structure of directories

```
.
└── upload
    ├── admin
    │   ├── controller
    │   │   ├── catalog
    │   │   ├── common
    │   │   ├── cron
    │   │   ├── customer
    │   │   ├── design
    │   │   ├── error
    │   │   ├── event
    │   │   ├── extension
    │   │   │   ├── analytics
    │   │   │   ├── captcha
    │   │   │   ├── currency
    │   │   │   ├── dashboard
    │   │   │   ├── extension
    │   │   │   ├── feed
    │   │   │   ├── fraud
    │   │   │   ├── module
    │   │   │   ├── payment
    │   │   │   ├── report
    │   │   │   ├── shipping
    │   │   │   ├── theme
    │   │   │   └── total
    │   │   ├── localisation
    │   │   ├── mail
    │   │   ├── marketing
    │   │   ├── marketplace
    │   │   ├── report
    │   │   ├── sale
    │   │   ├── setting
    │   │   ├── startup
    │   │   ├── tool
    │   │   └── user
    │   ├── language
    │   │   └── en-gb
    │   │       ├── catalog
    │   │       ├── common
    │   │       ├── customer
    │   │       ├── design
    │   │       ├── error
    │   │       ├── extension
    │   │       │   ├── analytics
    │   │       │   ├── captcha
    │   │       │   ├── currency
    │   │       │   ├── dashboard
    │   │       │   ├── extension
    │   │       │   ├── feed
    │   │       │   ├── fraud
    │   │       │   ├── module
    │   │       │   ├── payment
    │   │       │   ├── report
    │   │       │   ├── shipping
    │   │       │   ├── theme
    │   │       │   └── total
    │   │       ├── localisation
    │   │       ├── mail
    │   │       ├── marketing
    │   │       ├── marketplace
    │   │       ├── report
    │   │       ├── sale
    │   │       ├── setting
    │   │       ├── tool
    │   │       └── user
    │   ├── model
    │   │   ├── catalog
    │   │   ├── customer
    │   │   ├── design
    │   │   ├── extension
    │   │   │   ├── dashboard
    │   │   │   ├── feed
    │   │   │   ├── fraud
    │   │   │   ├── payment
    │   │   │   └── report
    │   │   ├── localisation
    │   │   ├── marketing
    │   │   ├── report
    │   │   ├── sale
    │   │   ├── setting
    │   │   ├── tool
    │   │   ├── upgrade
    │   │   └── user
    │   └── view
    │       ├── image
    │       │   └── payment
    │       ├── javascript
    │       │   ├── bootstrap
    │       │   │   ├── css
    │       │   │   └── js
    │       │   ├── ckeditor
    │       │   │   ├── adapters
    │       │   │   ├── lang
    │       │   │   ├── plugins
    │       │   │   │   ├── a11yhelp
    │       │   │   │   │   └── dialogs
    │       │   │   │   │       └── lang
    │       │   │   │   ├── about
    │       │   │   │   │   └── dialogs
    │       │   │   │   │       └── hidpi
    │       │   │   │   ├── clipboard
    │       │   │   │   │   └── dialogs
    │       │   │   │   ├── codemirror
    │       │   │   │   │   ├── css
    │       │   │   │   │   ├── icons
    │       │   │   │   │   ├── js
    │       │   │   │   │   ├── lang
    │       │   │   │   │   └── theme
    │       │   │   │   ├── colordialog
    │       │   │   │   │   └── dialogs
    │       │   │   │   ├── copyformatting
    │       │   │   │   │   ├── cursors
    │       │   │   │   │   └── styles
    │       │   │   │   ├── dialog
    │       │   │   │   ├── div
    │       │   │   │   │   └── dialogs
    │       │   │   │   ├── find
    │       │   │   │   │   └── dialogs
    │       │   │   │   ├── flash
    │       │   │   │   │   ├── dialogs
    │       │   │   │   │   └── images
    │       │   │   │   ├── forms
    │       │   │   │   │   ├── dialogs
    │       │   │   │   │   └── images
    │       │   │   │   ├── iframe
    │       │   │   │   │   ├── dialogs
    │       │   │   │   │   └── images
    │       │   │   │   ├── image
    │       │   │   │   │   ├── dialogs
    │       │   │   │   │   └── images
    │       │   │   │   ├── link
    │       │   │   │   │   ├── dialogs
    │       │   │   │   │   └── images
    │       │   │   │   │       └── hidpi
    │       │   │   │   ├── liststyle
    │       │   │   │   │   └── dialogs
    │       │   │   │   ├── magicline
    │       │   │   │   │   └── images
    │       │   │   │   │       └── hidpi
    │       │   │   │   ├── opencart
    │       │   │   │   │   └── images
    │       │   │   │   ├── pagebreak
    │       │   │   │   │   └── images
    │       │   │   │   ├── pastefromword
    │       │   │   │   │   └── filter
    │       │   │   │   ├── preview
    │       │   │   │   ├── scayt
    │       │   │   │   │   ├── dialogs
    │       │   │   │   │   └── skins
    │       │   │   │   │       └── moono-lisa
    │       │   │   │   ├── showblocks
    │       │   │   │   │   └── images
    │       │   │   │   ├── smiley
    │       │   │   │   │   ├── dialogs
    │       │   │   │   │   └── images
    │       │   │   │   ├── specialchar
    │       │   │   │   │   └── dialogs
    │       │   │   │   │       └── lang
    │       │   │   │   ├── table
    │       │   │   │   │   └── dialogs
    │       │   │   │   ├── tableselection
    │       │   │   │   │   └── styles
    │       │   │   │   ├── tabletools
    │       │   │   │   │   └── dialogs
    │       │   │   │   ├── templates
    │       │   │   │   │   ├── dialogs
    │       │   │   │   │   └── templates
    │       │   │   │   │       └── images
    │       │   │   │   ├── widget
    │       │   │   │   │   └── images
    │       │   │   │   └── wsc
    │       │   │   │       ├── dialogs
    │       │   │   │       └── skins
    │       │   │   │           └── moono-lisa
    │       │   │   ├── samples
    │       │   │   │   ├── css
    │       │   │   │   ├── img
    │       │   │   │   ├── js
    │       │   │   │   ├── old
    │       │   │   │   │   ├── assets
    │       │   │   │   │   │   ├── inlineall
    │       │   │   │   │   │   ├── outputxhtml
    │       │   │   │   │   │   └── uilanguages
    │       │   │   │   │   ├── dialog
    │       │   │   │   │   │   └── assets
    │       │   │   │   │   ├── enterkey
    │       │   │   │   │   ├── htmlwriter
    │       │   │   │   │   │   └── assets
    │       │   │   │   │   │       └── outputforflash
    │       │   │   │   │   ├── magicline
    │       │   │   │   │   ├── toolbar
    │       │   │   │   │   └── wysiwygarea
    │       │   │   │   └── toolbarconfigurator
    │       │   │   │       ├── css
    │       │   │   │       ├── font
    │       │   │   │       ├── js
    │       │   │   │       └── lib
    │       │   │   │           └── codemirror
    │       │   │   └── skins
    │       │   │       └── moono-lisa
    │       │   │           └── images
    │       │   │               └── hidpi
    │       │   ├── codemirror
    │       │   │   ├── lib
    │       │   │   └── theme
    │       │   ├── font-awesome
    │       │   │   ├── css
    │       │   │   ├── less
    │       │   │   ├── scss
    │       │   │   └── webfonts
    │       │   └── jquery
    │       │       ├── datetimepicker
    │       │       │   └── moment
    │       │       ├── flot
    │       │       │   └── examples
    │       │       │       ├── ajax
    │       │       │       ├── annotating
    │       │       │       ├── axes-interacting
    │       │       │       ├── axes-multiple
    │       │       │       ├── axes-time
    │       │       │       ├── axes-time-zones
    │       │       │       │   └── tz
    │       │       │       ├── basic-options
    │       │       │       ├── basic-usage
    │       │       │       ├── canvas
    │       │       │       ├── categories
    │       │       │       ├── image
    │       │       │       ├── interacting
    │       │       │       ├── navigate
    │       │       │       ├── percentiles
    │       │       │       ├── realtime
    │       │       │       ├── resize
    │       │       │       ├── selection
    │       │       │       ├── series-errorbars
    │       │       │       ├── series-pie
    │       │       │       ├── series-toggle
    │       │       │       ├── series-types
    │       │       │       ├── shared
    │       │       │       │   └── jquery-ui
    │       │       │       ├── stacking
    │       │       │       ├── symbols
    │       │       │       ├── threshold
    │       │       │       ├── tracking
    │       │       │       ├── visitors
    │       │       │       └── zooming
    │       │       ├── jquery-ui
    │       │       │   ├── external
    │       │       │   │   └── jquery
    │       │       │   └── images
    │       │       ├── jqvmap
    │       │       │   ├── data
    │       │       │   └── maps
    │       │       │       └── continents
    │       │       └── magnific
    │       ├── stylesheet
    │       │   ├── fonts
    │       │   └── scss
    │       │       ├── mixins
    │       │       ├── utilities
    │       │       └── vendor
    │       └── template
    │           ├── catalog
    │           ├── common
    │           ├── customer
    │           ├── design
    │           ├── error
    │           ├── extension
    │           │   ├── analytics
    │           │   ├── captcha
    │           │   ├── currency
    │           │   ├── dashboard
    │           │   ├── extension
    │           │   ├── feed
    │           │   ├── fraud
    │           │   ├── module
    │           │   ├── payment
    │           │   ├── report
    │           │   ├── shipping
    │           │   ├── theme
    │           │   └── total
    │           ├── localisation
    │           ├── mail
    │           ├── marketing
    │           ├── marketplace
    │           ├── report
    │           ├── sale
    │           ├── setting
    │           ├── tool
    │           └── user
    ├── catalog
    │   ├── controller
    │   │   ├── account
    │   │   ├── affiliate
    │   │   ├── api
    │   │   ├── checkout
    │   │   ├── common
    │   │   ├── error
    │   │   ├── event
    │   │   ├── extension
    │   │   │   ├── analytics
    │   │   │   ├── captcha
    │   │   │   ├── credit_card
    │   │   │   ├── feed
    │   │   │   ├── module
    │   │   │   ├── payment
    │   │   │   ├── recurring
    │   │   │   └── total
    │   │   ├── information
    │   │   ├── mail
    │   │   ├── product
    │   │   ├── startup
    │   │   └── tool
    │   ├── language
    │   │   └── en-gb
    │   │       ├── account
    │   │       ├── affiliate
    │   │       ├── api
    │   │       ├── checkout
    │   │       ├── common
    │   │       ├── error
    │   │       ├── extension
    │   │       │   ├── captcha
    │   │       │   ├── credit_card
    │   │       │   ├── module
    │   │       │   ├── payment
    │   │       │   ├── recurring
    │   │       │   ├── shipping
    │   │       │   └── total
    │   │       ├── information
    │   │       ├── mail
    │   │       ├── product
    │   │       └── tool
    │   ├── model
    │   │   ├── account
    │   │   ├── catalog
    │   │   ├── checkout
    │   │   ├── design
    │   │   ├── extension
    │   │   │   ├── credit_card
    │   │   │   ├── feed
    │   │   │   ├── fraud
    │   │   │   ├── module
    │   │   │   ├── payment
    │   │   │   ├── shipping
    │   │   │   └── total
    │   │   ├── localisation
    │   │   ├── marketing
    │   │   ├── report
    │   │   ├── setting
    │   │   └── tool
    │   └── view
    │       ├── javascript
    │       │   ├── bootstrap
    │       │   │   ├── css
    │       │   │   └── js
    │       │   ├── font-awesome
    │       │   │   ├── css
    │       │   │   ├── less
    │       │   │   ├── scss
    │       │   │   └── webfonts
    │       │   └── jquery
    │       │       ├── datetimepicker
    │       │       │   └── moment
    │       │       ├── magnific
    │       │       └── swiper
    │       │           ├── css
    │       │           └── js
    │       │               └── maps
    │       └── theme
    │           └── default
    │               ├── image
    │               ├── stylesheet
    │               │   └── scss
    │               │       ├── mixins
    │               │       ├── utilities
    │               │       └── vendor
    │               └── template
    │                   ├── account
    │                   ├── affiliate
    │                   ├── checkout
    │                   ├── common
    │                   ├── error
    │                   ├── extension
    │                   │   ├── captcha
    │                   │   ├── credit_card
    │                   │   ├── module
    │                   │   ├── payment
    │                   │   ├── recurring
    │                   │   └── total
    │                   ├── information
    │                   ├── mail
    │                   └── product
    ├── image
    │   ├── cache
    │   ├── catalog
    │   │   └── demo
    │   │       ├── banners
    │   │       ├── manufacturer
    │   │       └── product
    │   └── payment
    │       └── panasia
    │           └── bank-images
    ├── install
    │   ├── controller
    │   │   ├── 3rd_party
    │   │   ├── common
    │   │   ├── error
    │   │   ├── event
    │   │   ├── install
    │   │   ├── startup
    │   │   └── upgrade
    │   ├── language
    │   │   └── en-gb
    │   │       ├── 3rd_party
    │   │       ├── common
    │   │       ├── install
    │   │       └── upgrade
    │   ├── model
    │   │   ├── 3rd_party
    │   │   ├── install
    │   │   └── upgrade
    │   └── view
    │       ├── image
    │       ├── javascript
    │       │   ├── bootstrap
    │       │   │   ├── css
    │       │   │   └── js
    │       │   ├── cufon
    │       │   ├── font-awesome
    │       │   │   ├── css
    │       │   │   ├── fonts
    │       │   │   ├── less
    │       │   │   └── scss
    │       │   └── jquery
    │       ├── stylesheet
    │       └── template
    │           ├── 3rd_party
    │           ├── common
    │           ├── error
    │           ├── install
    │           └── upgrade
    └── system
        ├── config
        ├── engine
        ├── helper
        ├── library
        │   ├── cache
        │   ├── cart
        │   ├── db
        │   ├── mail
        │   ├── session
        │   ├── squareup
        │   └── template
        └── storage
            ├── backup
            ├── cache
            ├── download
            ├── logs
            ├── marketplace
            ├── modification
            ├── session
            ├── upload
            └── vendor
                ├── bin
                ├── braintree
                │   └── braintree_php
                │       ├── lib
                │       │   ├── Braintree
                │       │   │   ├── Dispute
                │       │   │   ├── Error
                │       │   │   ├── Exception
                │       │   │   ├── MerchantAccount
                │       │   │   ├── Result
                │       │   │   ├── Subscription
                │       │   │   ├── Test
                │       │   │   ├── Transaction
                │       │   │   └── Xml
                │       │   └── ssl
                │       └── tests
                │           ├── Braintree
                │           │   ├── CreditCardNumbers
                │           │   └── fixtures
                │           ├── integration
                │           │   ├── Error
                │           │   └── Result
                │           └── unit
                │               ├── ClientApi
                │               └── Result
                ├── cardinity
                │   └── cardinity-sdk-php
                │       ├── docs
                │       ├── spec
                │       │   ├── Exception
                │       │   ├── Http
                │       │   │   └── Guzzle
                │       │   └── Method
                │       │       ├── Payment
                │       │       ├── Refund
                │       │       ├── Settlement
                │       │       └── Void
                │       ├── src
                │       │   ├── Exception
                │       │   ├── Http
                │       │   │   └── Guzzle
                │       │   └── Method
                │       │       ├── Payment
                │       │       ├── Refund
                │       │       ├── Settlement
                │       │       └── Void
                │       └── tests
                ├── composer
                ├── divido
                │   └── divido-php
                │       └── lib
                │           ├── data
                │           └── Divido
                │               └── Util
                ├── guzzlehttp
                │   ├── guzzle
                │   │   └── src
                │   │       ├── Cookie
                │   │       ├── Event
                │   │       ├── Exception
                │   │       ├── Message
                │   │       ├── Post
                │   │       └── Subscriber
                │   ├── log-subscriber
                │   │   ├── src
                │   │   └── tests
                │   ├── oauth-subscriber
                │   │   ├── src
                │   │   └── tests
                │   ├── ringphp
                │   │   ├── docs
                │   │   ├── src
                │   │   │   ├── Client
                │   │   │   ├── Exception
                │   │   │   └── Future
                │   │   └── tests
                │   │       ├── Client
                │   │       └── Future
                │   └── streams
                │       ├── src
                │       │   └── Exception
                │       └── tests
                │           └── Exception
                ├── klarna
                │   └── kco_rest
                │       ├── docs
                │       │   └── examples
                │       │       ├── capture
                │       │       ├── checkout
                │       │       └── order
                │       ├── git_hooks
                │       │   ├── commit-msg
                │       │   └── pre-commit
                │       ├── src
                │       │   └── Klarna
                │       │       └── Rest
                │       │           ├── Checkout
                │       │           ├── OrderManagement
                │       │           └── Transport
                │       │               └── Exception
                │       └── tests
                │           ├── Component
                │           │   ├── Checkout
                │           │   ├── OrderManagement
                │           │   └── Transport
                │           └── Unit
                │               ├── Checkout
                │               ├── OrderManagement
                │               └── Transport
                │                   └── Exception
                ├── leafo
                │   └── scssphp
                │       ├── bin
                │       ├── example
                │       └── src
                │           ├── Base
                │           ├── Compiler
                │           ├── Exception
                │           ├── Formatter
                │           ├── Node
                │           └── SourceMap
                ├── psr
                │   └── log
                │       └── Psr
                │           └── Log
                │               └── Test
                ├── react
                │   └── promise
                │       ├── src
                │       │   └── Exception
                │       └── tests
                │           ├── fixtures
                │           ├── PromiseAdapter
                │           ├── PromiseTest
                │           └── Stub
                ├── symfony
                │   ├── polyfill-ctype
                │   ├── polyfill-mbstring
                │   │   └── Resources
                │   │       └── unidata
                │   ├── translation
                │   │   ├── Catalogue
                │   │   ├── DataCollector
                │   │   ├── Dumper
                │   │   ├── Exception
                │   │   ├── Extractor
                │   │   ├── Loader
                │   │   │   └── schema
                │   │   │       └── dic
                │   │   │           └── xliff-core
                │   │   ├── Tests
                │   │   │   ├── Catalogue
                │   │   │   ├── DataCollector
                │   │   │   ├── Dumper
                │   │   │   ├── fixtures
                │   │   │   │   └── resourcebundle
                │   │   │   │       ├── corrupted
                │   │   │   │       ├── dat
                │   │   │   │       └── res
                │   │   │   ├── Loader
                │   │   │   ├── Util
                │   │   │   └── Writer
                │   │   ├── Util
                │   │   └── Writer
                │   └── validator
                │       ├── Constraints
                │       │   └── Collection
                │       ├── Context
                │       ├── Exception
                │       ├── Mapping
                │       │   ├── Cache
                │       │   ├── Factory
                │       │   └── Loader
                │       │       └── schema
                │       │           └── dic
                │       │               └── constraint-mapping
                │       ├── Resources
                │       │   └── translations
                │       ├── Tests
                │       │   ├── Constraints
                │       │   │   └── Fixtures
                │       │   ├── Fixtures
                │       │   ├── Mapping
                │       │   │   ├── Cache
                │       │   │   ├── Factory
                │       │   │   └── Loader
                │       │   ├── Resources
                │       │   ├── Util
                │       │   └── Validator
                │       ├── Util
                │       ├── Validator
                │       └── Violation
                ├── twig
                │   └── twig
                │       ├── doc
                │       │   ├── filters
                │       │   ├── functions
                │       │   ├── tags
                │       │   └── tests
                │       ├── lib
                │       │   └── Twig
                │       │       ├── Cache
                │       │       ├── Error
                │       │       ├── Extension
                │       │       ├── Loader
                │       │       ├── Node
                │       │       │   └── Expression
                │       │       │       ├── Binary
                │       │       │       ├── Filter
                │       │       │       ├── Test
                │       │       │       └── Unary
                │       │       ├── NodeVisitor
                │       │       ├── Profiler
                │       │       │   ├── Dumper
                │       │       │   ├── Node
                │       │       │   └── NodeVisitor
                │       │       ├── Sandbox
                │       │       ├── Test
                │       │       ├── TokenParser
                │       │       └── Util
                │       ├── src
                │       │   ├── Cache
                │       │   ├── Error
                │       │   ├── Extension
                │       │   ├── Loader
                │       │   ├── Node
                │       │   │   └── Expression
                │       │   │       ├── Binary
                │       │   │       ├── Filter
                │       │   │       ├── Test
                │       │   │       └── Unary
                │       │   ├── NodeVisitor
                │       │   ├── Profiler
                │       │   │   ├── Dumper
                │       │   │   ├── Node
                │       │   │   └── NodeVisitor
                │       │   ├── RuntimeLoader
                │       │   ├── Sandbox
                │       │   ├── Test
                │       │   ├── TokenParser
                │       │   └── Util
                │       └── test
                │           └── Twig
                │               └── Tests
                │                   ├── Cache
                │                   ├── Extension
                │                   ├── Fixtures
                │                   │   ├── autoescape
                │                   │   ├── errors
                │                   │   ├── exceptions
                │                   │   ├── expressions
                │                   │   ├── extensions
                │                   │   ├── filters
                │                   │   ├── functions
                │                   │   │   └── include
                │                   │   ├── macros
                │                   │   ├── regression
                │                   │   ├── tags
                │                   │   │   ├── autoescape
                │                   │   │   ├── block
                │                   │   │   ├── deprecated
                │                   │   │   ├── embed
                │                   │   │   ├── filter
                │                   │   │   ├── for
                │                   │   │   ├── if
                │                   │   │   ├── include
                │                   │   │   ├── inheritance
                │                   │   │   ├── macro
                │                   │   │   ├── sandbox
                │                   │   │   ├── set
                │                   │   │   ├── spaceless
                │                   │   │   ├── use
                │                   │   │   ├── verbatim
                │                   │   │   └── with
                │                   │   └── tests
                │                   ├── Loader
                │                   │   └── Fixtures
                │                   │       ├── inheritance
                │                   │       ├── named
                │                   │       ├── named_bis
                │                   │       ├── named_final
                │                   │       ├── named_quater
                │                   │       ├── named_ter
                │                   │       ├── normal
                │                   │       ├── normal_bis
                │                   │       ├── normal_final
                │                   │       ├── normal_ter
                │                   │       ├── phar
                │                   │       └── themes
                │                   │           ├── theme1
                │                   │           └── theme2
                │                   ├── Node
                │                   │   └── Expression
                │                   │       ├── Binary
                │                   │       └── Unary
                │                   ├── NodeVisitor
                │                   ├── Profiler
                │                   │   └── Dumper
                │                   └── Util
                └── zoujingli
                    └── wechat-php-sdk
                        └── Wechat
                            └── Lib
```

765 directories
