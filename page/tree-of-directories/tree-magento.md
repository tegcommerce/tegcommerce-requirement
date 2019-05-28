magento
├── app
│   ├── code
│   │   └── Magento
│   │       ├── AdminNotification
│   │       │   ├── Block
│   │       │   │   ├── Grid
│   │       │   │   │   └── Renderer
│   │       │   │   └── System
│   │       │   │       └── Messages
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       ├── Notification
│   │       │   │       └── System
│   │       │   │           └── Message
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Config
│   │       │   │   │   └── Source
│   │       │   │   ├── ResourceModel
│   │       │   │   │   ├── Grid
│   │       │   │   │   ├── Inbox
│   │       │   │   │   │   └── Collection
│   │       │   │   │   └── System
│   │       │   │   │       └── Message
│   │       │   │   │           └── Collection
│   │       │   │   └── System
│   │       │   │       └── Message
│   │       │   │           └── Media
│   │       │   │               └── Synchronization
│   │       │   ├── Observer
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── Data
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       └── Model
│   │       │   │           └── System
│   │       │   │               └── Message
│   │       │   │                   └── Media
│   │       │   │                       └── Synchronization
│   │       │   ├── Ui
│   │       │   │   └── Component
│   │       │   │       └── DataProvider
│   │       │   └── view
│   │       │       └── adminhtml
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   ├── notification
│   │       │           │   └── system
│   │       │           │       └── messages
│   │       │           ├── ui_component
│   │       │           └── web
│   │       │               ├── js
│   │       │               │   ├── grid
│   │       │               │   │   └── columns
│   │       │               │   └── system
│   │       │               │       └── messages
│   │       │               ├── system
│   │       │               └── template
│   │       │                   └── grid
│   │       │                       └── cells
│   │       ├── AdvancedPricingImportExport
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       └── Export
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Export
│   │       │   │   ├── Import
│   │       │   │   │   └── AdvancedPricing
│   │       │   │   │       └── Validator
│   │       │   │   └── Indexer
│   │       │   │       └── Product
│   │       │   │           └── Price
│   │       │   │               └── Plugin
│   │       │   └── Test
│   │       │       ├── Mftf
│   │       │       └── Unit
│   │       │           └── Model
│   │       │               ├── Export
│   │       │               ├── Import
│   │       │               │   └── AdvancedPricing
│   │       │               │       └── Validator
│   │       │               └── Indexer
│   │       │                   └── Product
│   │       │                       └── Price
│   │       │                           └── Plugin
│   │       ├── AdvancedSearch
│   │       │   ├── Block
│   │       │   │   └── Adminhtml
│   │       │   │       ├── Search
│   │       │   │       └── System
│   │       │   │           └── Config
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       └── Search
│   │       │   │           └── System
│   │       │   │               └── Config
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Adapter
│   │       │   │   │   └── DataMapper
│   │       │   │   ├── Adminhtml
│   │       │   │   │   └── Search
│   │       │   │   │       └── Grid
│   │       │   │   ├── Client
│   │       │   │   ├── DataProvider
│   │       │   │   ├── Indexer
│   │       │   │   │   └── Fulltext
│   │       │   │   │       └── Plugin
│   │       │   │   ├── Recommendations
│   │       │   │   └── ResourceModel
│   │       │   │       └── Search
│   │       │   │           └── Grid
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       ├── Controller
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       └── Search
│   │       │   │       │           └── System
│   │       │   │       │               └── Config
│   │       │   │       └── Model
│   │       │   │           ├── Client
│   │       │   │           ├── Indexer
│   │       │   │           │   └── Fulltext
│   │       │   │           │       └── Plugin
│   │       │   │           └── ResourceModel
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   │   └── system
│   │       │       │   │       └── config
│   │       │       │   └── web
│   │       │       │       └── js
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           └── templates
│   │       ├── Amqp
│   │       │   ├── etc
│   │       │   ├── Model
│   │       │   ├── Setup
│   │       │   └── Test
│   │       │       ├── Mftf
│   │       │       └── Unit
│   │       │           └── Setup
│   │       ├── Analytics
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   ├── Block
│   │       │   │   └── Adminhtml
│   │       │   │       └── System
│   │       │   │           └── Config
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       ├── BIEssentials
│   │       │   │       ├── Reports
│   │       │   │       └── Subscription
│   │       │   ├── Cron
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Config
│   │       │   │   │   ├── Backend
│   │       │   │   │   │   ├── Baseurl
│   │       │   │   │   │   └── Enabled
│   │       │   │   │   └── Source
│   │       │   │   ├── Connector
│   │       │   │   │   ├── Http
│   │       │   │   │   │   └── Client
│   │       │   │   │   └── ResponseHandler
│   │       │   │   ├── Exception
│   │       │   │   │   └── State
│   │       │   │   ├── Plugin
│   │       │   │   ├── ReportXml
│   │       │   │   └── System
│   │       │   │       └── Message
│   │       │   ├── ReportXml
│   │       │   │   ├── Config
│   │       │   │   │   └── Converter
│   │       │   │   └── DB
│   │       │   │       └── Assembler
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       └── System
│   │       │   │       │           └── Config
│   │       │   │       ├── Controller
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       ├── BIEssentials
│   │       │   │       │       ├── Reports
│   │       │   │       │       └── Subscription
│   │       │   │       ├── Cron
│   │       │   │       ├── Model
│   │       │   │       │   ├── Config
│   │       │   │       │   │   ├── Backend
│   │       │   │       │   │   │   ├── Baseurl
│   │       │   │       │   │   │   └── Enabled
│   │       │   │       │   │   └── Source
│   │       │   │       │   ├── Connector
│   │       │   │       │   │   ├── Http
│   │       │   │       │   │   │   └── Client
│   │       │   │       │   │   └── ResponseHandler
│   │       │   │       │   ├── Plugin
│   │       │   │       │   ├── ReportXml
│   │       │   │       │   └── System
│   │       │   │       │       └── Message
│   │       │   │       └── ReportXml
│   │       │   │           ├── Config
│   │       │   │           │   ├── Converter
│   │       │   │           │   └── _files
│   │       │   │           └── DB
│   │       │   │               └── Assembler
│   │       │   └── view
│   │       │       └── adminhtml
│   │       │           ├── layout
│   │       │           └── templates
│   │       │               └── dashboard
│   │       ├── AsynchronousOperations
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   ├── Block
│   │       │   │   └── Adminhtml
│   │       │   │       └── Bulk
│   │       │   │           └── Details
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       ├── Bulk
│   │       │   │       ├── Index
│   │       │   │       └── Notification
│   │       │   ├── Cron
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── BulkDescription
│   │       │   │   ├── BulkStatus
│   │       │   │   ├── Entity
│   │       │   │   ├── Operation
│   │       │   │   └── ResourceModel
│   │       │   │       ├── Bulk
│   │       │   │       ├── Operation
│   │       │   │       └── System
│   │       │   │           └── Message
│   │       │   │               └── Collection
│   │       │   │                   └── Synchronized
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       └── Bulk
│   │       │   │       │           └── Details
│   │       │   │       ├── Controller
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   ├── Bulk
│   │       │   │       │   │   ├── Index
│   │       │   │       │   │   └── Notification
│   │       │   │       │   └── Cron
│   │       │   │       ├── Model
│   │       │   │       │   ├── BulkDescription
│   │       │   │       │   ├── Entity
│   │       │   │       │   ├── Operation
│   │       │   │       │   └── ResourceModel
│   │       │   │       │       ├── Operation
│   │       │   │       │       └── System
│   │       │   │       │           └── Message
│   │       │   │       │               └── Collection
│   │       │   │       │                   └── Synchronized
│   │       │   │       └── Ui
│   │       │   │           └── Component
│   │       │   │               ├── AdminNotification
│   │       │   │               ├── Listing
│   │       │   │               │   └── Column
│   │       │   │               └── Operation
│   │       │   ├── Ui
│   │       │   │   └── Component
│   │       │   │       ├── AdminNotification
│   │       │   │       ├── DataProvider
│   │       │   │       │   ├── Bulk
│   │       │   │       │   └── Operation
│   │       │   │       │       ├── Failed
│   │       │   │       │       └── Retriable
│   │       │   │       ├── Listing
│   │       │   │       │   └── Column
│   │       │   │       └── Operation
│   │       │   └── view
│   │       │       └── adminhtml
│   │       │           ├── layout
│   │       │           ├── ui_component
│   │       │           └── web
│   │       │               ├── js
│   │       │               │   ├── form
│   │       │               │   └── grid
│   │       │               └── template
│   │       │                   ├── form
│   │       │                   └── grid
│   │       │                       └── cells
│   │       ├── Authorization
│   │       │   ├── etc
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Acl
│   │       │   │   │   ├── Loader
│   │       │   │   │   └── Role
│   │       │   │   └── ResourceModel
│   │       │   │       ├── Permissions
│   │       │   │       ├── Role
│   │       │   │       │   └── Grid
│   │       │   │       └── Rules
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   └── Test
│   │       │       ├── Mftf
│   │       │       └── Unit
│   │       │           └── Model
│   │       │               ├── Acl
│   │       │               │   └── Loader
│   │       │               └── ResourceModel
│   │       ├── Authorizenet
│   │       │   ├── Block
│   │       │   │   ├── Adminhtml
│   │       │   │   │   └── Order
│   │       │   │   │       └── View
│   │       │   │   │           └── Info
│   │       │   │   └── Transparent
│   │       │   ├── Controller
│   │       │   │   ├── Adminhtml
│   │       │   │   │   └── Authorizenet
│   │       │   │   │       └── Directpost
│   │       │   │   │           └── Payment
│   │       │   │   └── Directpost
│   │       │   │       └── Payment
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Helper
│   │       │   │   └── Backend
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Directpost
│   │       │   │   │   ├── Request
│   │       │   │   │   └── Response
│   │       │   │   ├── Request
│   │       │   │   ├── ResourceModel
│   │       │   │   │   └── Debug
│   │       │   │   ├── Response
│   │       │   │   └── Source
│   │       │   ├── Observer
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       ├── Controller
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   └── Authorizenet
│   │       │   │       │   │       └── Directpost
│   │       │   │       │   │           └── Payment
│   │       │   │       │   └── Directpost
│   │       │   │       │       └── Payment
│   │       │   │       ├── Helper
│   │       │   │       │   └── Backend
│   │       │   │       ├── Model
│   │       │   │       │   ├── Directpost
│   │       │   │       │   │   ├── Request
│   │       │   │       │   │   └── Response
│   │       │   │       │   ├── Request
│   │       │   │       │   └── Response
│   │       │   │       └── Observer
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   │   ├── directpost
│   │       │       │   │   └── order
│   │       │       │   │       └── view
│   │       │       │   │           └── info
│   │       │       │   └── web
│   │       │       │       └── js
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           └── web
│   │       │               ├── js
│   │       │               │   └── view
│   │       │               │       └── payment
│   │       │               │           └── method-renderer
│   │       │               └── template
│   │       │                   └── payment
│   │       ├── AuthorizenetAcceptjs
│   │       │   ├── Block
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Gateway
│   │       │   │   ├── Command
│   │       │   │   ├── Http
│   │       │   │   │   └── Payload
│   │       │   │   │       └── Filter
│   │       │   │   ├── Request
│   │       │   │   ├── Response
│   │       │   │   └── Validator
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Adminhtml
│   │       │   │   │   └── Source
│   │       │   │   └── Ui
│   │       │   ├── Observer
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       ├── Gateway
│   │       │   │       │   ├── Command
│   │       │   │       │   ├── Http
│   │       │   │       │   │   └── Payload
│   │       │   │       │   │       └── Filter
│   │       │   │       │   ├── Request
│   │       │   │       │   ├── Response
│   │       │   │       │   └── Validator
│   │       │   │       ├── Model
│   │       │   │       │   └── Ui
│   │       │   │       ├── Observer
│   │       │   │       └── Setup
│   │       │   │           └── Patch
│   │       │   │               └── Data
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   │   ├── form
│   │       │       │   │   └── payment
│   │       │       │   └── web
│   │       │       │       └── js
│   │       │       ├── base
│   │       │       │   └── web
│   │       │       │       └── js
│   │       │       │           └── view
│   │       │       │               └── payment
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           └── web
│   │       │               ├── js
│   │       │               │   └── view
│   │       │               │       └── payment
│   │       │               │           └── method-renderer
│   │       │               └── template
│   │       │                   └── payment
│   │       ├── Backend
│   │       │   ├── App
│   │       │   │   ├── Action
│   │       │   │   │   └── Plugin
│   │       │   │   ├── Area
│   │       │   │   ├── Request
│   │       │   │   ├── Response
│   │       │   │   │   └── Http
│   │       │   │   └── Router
│   │       │   ├── Block
│   │       │   │   ├── Admin
│   │       │   │   ├── Cache
│   │       │   │   │   └── Grid
│   │       │   │   │       ├── Column
│   │       │   │   │       └── Massaction
│   │       │   │   ├── Catalog
│   │       │   │   │   └── Product
│   │       │   │   │       └── Tab
│   │       │   │   ├── Dashboard
│   │       │   │   │   ├── Orders
│   │       │   │   │   ├── Searches
│   │       │   │   │   │   └── Renderer
│   │       │   │   │   └── Tab
│   │       │   │   │       ├── Customers
│   │       │   │   │       └── Products
│   │       │   │   ├── DataProviders
│   │       │   │   ├── Media
│   │       │   │   ├── Page
│   │       │   │   │   └── System
│   │       │   │   │       └── Config
│   │       │   │   │           └── Robots
│   │       │   │   ├── Store
│   │       │   │   │   └── Switcher
│   │       │   │   │       └── Form
│   │       │   │   │           └── Renderer
│   │       │   │   │               └── Fieldset
│   │       │   │   ├── System
│   │       │   │   │   ├── Account
│   │       │   │   │   │   └── Edit
│   │       │   │   │   ├── Cache
│   │       │   │   │   ├── Design
│   │       │   │   │   │   └── Edit
│   │       │   │   │   │       └── Tab
│   │       │   │   │   └── Store
│   │       │   │   │       ├── Delete
│   │       │   │   │       ├── Edit
│   │       │   │   │       │   └── Form
│   │       │   │   │       └── Grid
│   │       │   │   │           └── Render
│   │       │   │   ├── Template
│   │       │   │   ├── Text
│   │       │   │   └── Widget
│   │       │   │       ├── Accordion
│   │       │   │       ├── Button
│   │       │   │       │   └── Toolbar
│   │       │   │       ├── Form
│   │       │   │       │   ├── Element
│   │       │   │       │   └── Renderer
│   │       │   │       │       └── Fieldset
│   │       │   │       ├── Grid
│   │       │   │       │   ├── Column
│   │       │   │       │   │   ├── Filter
│   │       │   │       │   │   │   └── Select
│   │       │   │       │   │   └── Renderer
│   │       │   │       │   │       ├── Checkboxes
│   │       │   │       │   │       ├── Options
│   │       │   │       │   │       ├── Radio
│   │       │   │       │   │       └── Select
│   │       │   │       │   └── Massaction
│   │       │   │       │       └── Item
│   │       │   │       │           └── Additional
│   │       │   │       └── Tab
│   │       │   ├── Console
│   │       │   │   └── Command
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       ├── Ajax
│   │       │   │       ├── Auth
│   │       │   │       ├── BackendApp
│   │       │   │       ├── Cache
│   │       │   │       ├── Dashboard
│   │       │   │       ├── Index
│   │       │   │       ├── Noroute
│   │       │   │       └── System
│   │       │   │           ├── Account
│   │       │   │           ├── Design
│   │       │   │           └── Store
│   │       │   ├── Cron
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── Helper
│   │       │   │   └── Dashboard
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Auth
│   │       │   │   │   └── Credential
│   │       │   │   ├── Authorization
│   │       │   │   ├── Cache
│   │       │   │   │   └── ResourceModel
│   │       │   │   │       └── Grid
│   │       │   │   ├── Config
│   │       │   │   │   └── SessionLifetime
│   │       │   │   ├── Image
│   │       │   │   ├── Locale
│   │       │   │   ├── Menu
│   │       │   │   │   ├── Builder
│   │       │   │   │   │   └── Command
│   │       │   │   │   ├── Config
│   │       │   │   │   │   └── Menu
│   │       │   │   │   ├── Director
│   │       │   │   │   ├── Filter
│   │       │   │   │   └── Item
│   │       │   │   ├── ResourceModel
│   │       │   │   ├── Search
│   │       │   │   │   └── Config
│   │       │   │   │       ├── Result
│   │       │   │   │       └── Structure
│   │       │   │   │           └── Element
│   │       │   │   │               └── Builder
│   │       │   │   ├── Session
│   │       │   │   ├── Setup
│   │       │   │   ├── Translate
│   │       │   │   │   └── Inline
│   │       │   │   ├── Url
│   │       │   │   ├── View
│   │       │   │   │   ├── Layout
│   │       │   │   │   │   └── Reader
│   │       │   │   │   ├── Page
│   │       │   │   │   └── Result
│   │       │   │   └── Widget
│   │       │   │       └── Grid
│   │       │   │           └── Row
│   │       │   ├── Service
│   │       │   │   └── V1
│   │       │   ├── Setup
│   │       │   ├── Spi
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── App
│   │       │   │       │   ├── Action
│   │       │   │       │   │   ├── Plugin
│   │       │   │       │   │   └── Stub
│   │       │   │       │   ├── Area
│   │       │   │       │   │   └── Request
│   │       │   │       │   ├── Response
│   │       │   │       │   │   └── Http
│   │       │   │       │   └── Router
│   │       │   │       ├── Block
│   │       │   │       │   ├── Cache
│   │       │   │       │   ├── Page
│   │       │   │       │   │   └── System
│   │       │   │       │   │       └── Config
│   │       │   │       │   │           └── Robots
│   │       │   │       │   ├── Store
│   │       │   │       │   └── Widget
│   │       │   │       │       ├── Button
│   │       │   │       │       ├── Form
│   │       │   │       │       └── Grid
│   │       │   │       │           ├── Column
│   │       │   │       │           │   ├── Filter
│   │       │   │       │           │   └── Renderer
│   │       │   │       │           │       └── Radio
│   │       │   │       │           └── Massaction
│   │       │   │       ├── Console
│   │       │   │       │   └── Command
│   │       │   │       ├── Controller
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       ├── Cache
│   │       │   │       │       ├── Dashboard
│   │       │   │       │       └── System
│   │       │   │       │           ├── Account
│   │       │   │       │           └── Store
│   │       │   │       ├── Cron
│   │       │   │       ├── Helper
│   │       │   │       ├── Model
│   │       │   │       │   ├── Config
│   │       │   │       │   │   └── SessionLifetime
│   │       │   │       │   ├── _files
│   │       │   │       │   ├── Menu
│   │       │   │       │   │   ├── Builder
│   │       │   │       │   │   │   └── Command
│   │       │   │       │   │   ├── Config
│   │       │   │       │   │   │   └── _files
│   │       │   │       │   │   ├── Director
│   │       │   │       │   │   ├── Filter
│   │       │   │       │   │   └── Item
│   │       │   │       │   ├── Search
│   │       │   │       │   │   └── Config
│   │       │   │       │   │       ├── Result
│   │       │   │       │   │       └── Structure
│   │       │   │       │   │           └── Element
│   │       │   │       │   │               └── Builder
│   │       │   │       │   ├── Session
│   │       │   │       │   ├── Translate
│   │       │   │       │   │   └── Inline
│   │       │   │       │   ├── View
│   │       │   │       │   │   ├── Layout
│   │       │   │       │   │   └── Result
│   │       │   │       │   └── Widget
│   │       │   │       │       └── Grid
│   │       │   │       │           └── Row
│   │       │   │       ├── Service
│   │       │   │       │   └── V1
│   │       │   │       └── Setup
│   │       │   ├── Ui
│   │       │   │   └── Component
│   │       │   │       ├── Control
│   │       │   │       └── Listing
│   │       │   │           └── Column
│   │       │   └── view
│   │       │       └── adminhtml
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   ├── admin
│   │       │           │   ├── dashboard
│   │       │           │   │   ├── graph
│   │       │           │   │   ├── store
│   │       │           │   │   └── totalbar
│   │       │           │   ├── media
│   │       │           │   ├── page
│   │       │           │   │   └── js
│   │       │           │   ├── store
│   │       │           │   │   └── switcher
│   │       │           │   │       └── form
│   │       │           │   │           └── renderer
│   │       │           │   │               └── fieldset
│   │       │           │   ├── system
│   │       │           │   │   ├── cache
│   │       │           │   │   ├── design
│   │       │           │   │   └── shipping
│   │       │           │   └── widget
│   │       │           │       ├── button
│   │       │           │       ├── form
│   │       │           │       │   ├── element
│   │       │           │       │   └── renderer
│   │       │           │       │       └── fieldset
│   │       │           │       ├── grid
│   │       │           │       │   └── container
│   │       │           │       └── view
│   │       │           ├── ui_component
│   │       │           └── web
│   │       │               ├── images
│   │       │               ├── js
│   │       │               │   └── bootstrap
│   │       │               └── template
│   │       │                   ├── dynamic-rows
│   │       │                   │   └── cells
│   │       │                   └── form
│   │       │                       └── element
│   │       │                           └── helper
│   │       ├── Backup
│   │       │   ├── Block
│   │       │   │   └── Adminhtml
│   │       │   │       └── Grid
│   │       │   │           └── Column
│   │       │   │               └── Renderer
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       └── Index
│   │       │   ├── Cron
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Config
│   │       │   │   │   ├── Backend
│   │       │   │   │   └── Source
│   │       │   │   ├── Fs
│   │       │   │   ├── Grid
│   │       │   │   └── ResourceModel
│   │       │   │       ├── Table
│   │       │   │       └── View
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Controller
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       └── Index
│   │       │   │       ├── Cron
│   │       │   │       ├── Helper
│   │       │   │       └── Model
│   │       │   │           └── Fs
│   │       │   └── view
│   │       │       └── adminhtml
│   │       │           ├── layout
│   │       │           └── templates
│   │       │               └── backup
│   │       ├── Braintree
│   │       │   ├── Block
│   │       │   │   ├── Adminhtml
│   │       │   │   │   └── Form
│   │       │   │   │       └── Field
│   │       │   │   ├── Customer
│   │       │   │   │   └── PayPal
│   │       │   │   └── Paypal
│   │       │   │       └── Checkout
│   │       │   ├── Controller
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Payment
│   │       │   │   │   └── Report
│   │       │   │   ├── Payment
│   │       │   │   └── Paypal
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Gateway
│   │       │   │   ├── Command
│   │       │   │   ├── Config
│   │       │   │   │   └── PayPal
│   │       │   │   ├── Http
│   │       │   │   │   └── Client
│   │       │   │   ├── Request
│   │       │   │   │   └── PayPal
│   │       │   │   ├── Response
│   │       │   │   │   └── PayPal
│   │       │   │   └── Validator
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Adapter
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Source
│   │       │   │   │   └── System
│   │       │   │   │       └── Config
│   │       │   │   ├── InstantPurchase
│   │       │   │   │   ├── CreditCard
│   │       │   │   │   └── PayPal
│   │       │   │   ├── Multishipping
│   │       │   │   ├── Paypal
│   │       │   │   │   └── Helper
│   │       │   │   ├── Report
│   │       │   │   │   ├── ConditionAppliers
│   │       │   │   │   └── Row
│   │       │   │   └── Ui
│   │       │   │       ├── Adminhtml
│   │       │   │       │   └── PayPal
│   │       │   │       └── PayPal
│   │       │   ├── Observer
│   │       │   ├── Plugin
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Metadata
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       ├── Controller
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   └── Payment
│   │       │   │       │   ├── Payment
│   │       │   │       │   └── Paypal
│   │       │   │       ├── Gateway
│   │       │   │       │   ├── Command
│   │       │   │       │   ├── Config
│   │       │   │       │   ├── Http
│   │       │   │       │   │   └── Client
│   │       │   │       │   ├── Request
│   │       │   │       │   │   └── PayPal
│   │       │   │       │   ├── Response
│   │       │   │       │   │   └── PayPal
│   │       │   │       │   └── Validator
│   │       │   │       ├── Helper
│   │       │   │       ├── Model
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   └── System
│   │       │   │       │   │       └── Config
│   │       │   │       │   ├── InstantPurchase
│   │       │   │       │   │   ├── CreditCard
│   │       │   │       │   │   └── PayPal
│   │       │   │       │   ├── Paypal
│   │       │   │       │   │   └── Helper
│   │       │   │       │   ├── Report
│   │       │   │       │   └── Ui
│   │       │   │       │       ├── Adminhtml
│   │       │   │       │       │   └── PayPal
│   │       │   │       │       └── PayPal
│   │       │   │       ├── Observer
│   │       │   │       └── Ui
│   │       │   │           └── Component
│   │       │   │               └── Report
│   │       │   │                   ├── Filters
│   │       │   │                   │   └── Type
│   │       │   │                   └── Listing
│   │       │   │                       └── Column
│   │       │   ├── Ui
│   │       │   │   └── Component
│   │       │   │       └── Report
│   │       │   │           ├── Filters
│   │       │   │           │   └── Type
│   │       │   │           └── Listing
│   │       │   │               └── Column
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   │   ├── form
│   │       │       │   │   │   └── paypal
│   │       │       │   │   ├── grid
│   │       │       │   │   └── payment
│   │       │       │   ├── ui_component
│   │       │       │   └── web
│   │       │       │       ├── images
│   │       │       │       └── js
│   │       │       │           └── grid
│   │       │       │               └── filters
│   │       │       ├── base
│   │       │       │   └── web
│   │       │       │       ├── images
│   │       │       │       └── js
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   ├── multishipping
│   │       │           │   └── paypal
│   │       │           └── web
│   │       │               ├── js
│   │       │               │   ├── paypal
│   │       │               │   └── view
│   │       │               │       └── payment
│   │       │               │           └── method-renderer
│   │       │               │               └── multishipping
│   │       │               └── template
│   │       │                   └── payment
│   │       │                       ├── multishipping
│   │       │                       └── paypal
│   │       ├── Bundle
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   ├── Block
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Catalog
│   │       │   │   │   │   └── Product
│   │       │   │   │   │       ├── Composite
│   │       │   │   │   │       │   └── Fieldset
│   │       │   │   │   │       │       └── Options
│   │       │   │   │   │       │           └── Type
│   │       │   │   │   │       └── Edit
│   │       │   │   │   │           └── Tab
│   │       │   │   │   │               ├── Attributes
│   │       │   │   │   │               └── Bundle
│   │       │   │   │   │                   └── Option
│   │       │   │   │   │                       └── Search
│   │       │   │   │   ├── Order
│   │       │   │   │   │   └── Create
│   │       │   │   │   └── Sales
│   │       │   │   │       └── Order
│   │       │   │   │           ├── Items
│   │       │   │   │           └── View
│   │       │   │   │               └── Items
│   │       │   │   ├── Catalog
│   │       │   │   │   └── Product
│   │       │   │   │       └── View
│   │       │   │   │           └── Type
│   │       │   │   │               └── Bundle
│   │       │   │   │                   └── Option
│   │       │   │   ├── Checkout
│   │       │   │   │   └── Cart
│   │       │   │   │       └── Item
│   │       │   │   ├── DataProviders
│   │       │   │   └── Sales
│   │       │   │       └── Order
│   │       │   │           └── Items
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       ├── Bundle
│   │       │   │       │   ├── Product
│   │       │   │       │   │   └── Edit
│   │       │   │       │   └── Selection
│   │       │   │       └── Product
│   │       │   │           └── Initialization
│   │       │   │               └── Helper
│   │       │   │                   └── Plugin
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   ├── frontend
│   │       │   │   ├── webapi_rest
│   │       │   │   └── webapi_soap
│   │       │   ├── Helper
│   │       │   │   └── Catalog
│   │       │   │       └── Product
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Option
│   │       │   │   ├── Plugin
│   │       │   │   │   └── Frontend
│   │       │   │   ├── Product
│   │       │   │   │   ├── Attribute
│   │       │   │   │   │   └── Source
│   │       │   │   │   │       ├── Price
│   │       │   │   │   │       └── Shipment
│   │       │   │   │   └── CopyConstructor
│   │       │   │   ├── ResourceModel
│   │       │   │   │   ├── Indexer
│   │       │   │   │   ├── Option
│   │       │   │   │   └── Selection
│   │       │   │   │       ├── Collection
│   │       │   │   │       └── Plugin
│   │       │   │   ├── Sales
│   │       │   │   │   └── Order
│   │       │   │   │       ├── Pdf
│   │       │   │   │       │   └── Items
│   │       │   │   │       └── Plugin
│   │       │   │   └── Source
│   │       │   │       └── Option
│   │       │   │           └── Selection
│   │       │   │               └── Price
│   │       │   ├── Observer
│   │       │   ├── Plugin
│   │       │   ├── Pricing
│   │       │   │   ├── Adjustment
│   │       │   │   ├── Price
│   │       │   │   └── Render
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       ├── Data
│   │       │   │       └── Schema
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Metadata
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   ├── Catalog
│   │       │   │       │   │   │   └── Product
│   │       │   │       │   │   │       ├── Composite
│   │       │   │       │   │   │       │   └── Fieldset
│   │       │   │       │   │   │       │       └── Options
│   │       │   │       │   │   │       │           └── Type
│   │       │   │       │   │   │       └── Edit
│   │       │   │       │   │   │           └── Tab
│   │       │   │       │   │   │               ├── Attributes
│   │       │   │       │   │   │               └── Bundle
│   │       │   │       │   │   └── Sales
│   │       │   │       │   │       └── Order
│   │       │   │       │   │           ├── Items
│   │       │   │       │   │           └── View
│   │       │   │       │   │               └── Items
│   │       │   │       │   ├── Catalog
│   │       │   │       │   │   └── Product
│   │       │   │       │   │       └── View
│   │       │   │       │   │           └── Type
│   │       │   │       │   │               └── Bundle
│   │       │   │       │   ├── DataProviders
│   │       │   │       │   └── Sales
│   │       │   │       │       └── Order
│   │       │   │       │           └── Items
│   │       │   │       ├── Controller
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       ├── Bundle
│   │       │   │       │       │   ├── Product
│   │       │   │       │       │   │   └── Edit
│   │       │   │       │       │   └── Selection
│   │       │   │       │       └── Product
│   │       │   │       │           └── Initialization
│   │       │   │       │               └── Helper
│   │       │   │       │                   └── Plugin
│   │       │   │       ├── Helper
│   │       │   │       │   └── Catalog
│   │       │   │       │       └── Product
│   │       │   │       ├── Model
│   │       │   │       │   ├── Option
│   │       │   │       │   ├── Plugin
│   │       │   │       │   │   └── Frontend
│   │       │   │       │   ├── Product
│   │       │   │       │   │   ├── Attribute
│   │       │   │       │   │   │   └── Source
│   │       │   │       │   │   │       └── Price
│   │       │   │       │   │   └── CopyConstructor
│   │       │   │       │   └── Sales
│   │       │   │       │       └── Order
│   │       │   │       │           ├── Pdf
│   │       │   │       │           │   └── Items
│   │       │   │       │           └── Plugin
│   │       │   │       ├── Pricing
│   │       │   │       │   ├── Adjustment
│   │       │   │       │   ├── Price
│   │       │   │       │   └── Render
│   │       │   │       └── Ui
│   │       │   │           └── DataProvider
│   │       │   │               └── Product
│   │       │   │                   ├── Form
│   │       │   │                   │   └── Modifier
│   │       │   │                   └── Listing
│   │       │   │                       └── Collector
│   │       │   ├── Ui
│   │       │   │   └── DataProvider
│   │       │   │       └── Product
│   │       │   │           ├── Form
│   │       │   │           │   └── Modifier
│   │       │   │           └── Listing
│   │       │   │               └── Collector
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   │   ├── catalog
│   │       │       │   │   │   └── product
│   │       │       │   │   │       └── edit
│   │       │       │   │   │           └── tab
│   │       │       │   │   │               └── attributes
│   │       │       │   │   ├── product
│   │       │       │   │   │   ├── composite
│   │       │       │   │   │   │   └── fieldset
│   │       │       │   │   │   │       └── options
│   │       │       │   │   │   │           └── type
│   │       │       │   │   │   ├── edit
│   │       │       │   │   │   │   └── bundle
│   │       │       │   │   │   │       └── option
│   │       │       │   │   │   └── stock
│   │       │       │   │   └── sales
│   │       │       │   │       ├── creditmemo
│   │       │       │   │       │   ├── create
│   │       │       │   │       │   │   └── items
│   │       │       │   │       │   └── view
│   │       │       │   │       │       └── items
│   │       │       │   │       ├── invoice
│   │       │       │   │       │   ├── create
│   │       │       │   │       │   │   └── items
│   │       │       │   │       │   └── view
│   │       │       │   │       │       └── items
│   │       │       │   │       ├── order
│   │       │       │   │       │   └── view
│   │       │       │   │       │       └── items
│   │       │       │   │       └── shipment
│   │       │       │   │           ├── create
│   │       │       │   │           │   └── items
│   │       │       │   │           └── view
│   │       │       │   │               └── items
│   │       │       │   ├── ui_component
│   │       │       │   └── web
│   │       │       │       ├── css
│   │       │       │       └── js
│   │       │       │           └── components
│   │       │       ├── base
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   │   └── product
│   │       │       │   │       └── price
│   │       │       │   │           └── selection
│   │       │       │   └── web
│   │       │       │       ├── js
│   │       │       │       └── template
│   │       │       │           └── product
│   │       │       │               └── price
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   ├── catalog
│   │       │           │   │   └── product
│   │       │           │   │       └── view
│   │       │           │   │           ├── options
│   │       │           │   │           └── type
│   │       │           │   │               └── bundle
│   │       │           │   │                   └── option
│   │       │           │   ├── email
│   │       │           │   │   └── order
│   │       │           │   │       └── items
│   │       │           │   │           ├── creditmemo
│   │       │           │   │           ├── invoice
│   │       │           │   │           ├── order
│   │       │           │   │           └── shipment
│   │       │           │   ├── js
│   │       │           │   └── sales
│   │       │           │       └── order
│   │       │           │           ├── creditmemo
│   │       │           │           │   └── items
│   │       │           │           ├── invoice
│   │       │           │           │   └── items
│   │       │           │           ├── items
│   │       │           │           └── shipment
│   │       │           │               └── items
│   │       │           ├── ui_component
│   │       │           └── web
│   │       │               └── js
│   │       ├── BundleGraphQl
│   │       │   ├── etc
│   │       │   │   └── graphql
│   │       │   ├── Model
│   │       │   │   └── Resolver
│   │       │   │       ├── Links
│   │       │   │       ├── Options
│   │       │   │       └── Product
│   │       │   │           └── Fields
│   │       │   └── Test
│   │       │       └── Mftf
│   │       ├── BundleImportExport
│   │       │   ├── etc
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Export
│   │       │   │   │   └── Product
│   │       │   │   │       └── Type
│   │       │   │   └── Import
│   │       │   │       └── Product
│   │       │   │           └── Type
│   │       │   │               └── Bundle
│   │       │   └── Test
│   │       │       ├── Mftf
│   │       │       └── Unit
│   │       │           └── Model
│   │       │               ├── Export
│   │       │               │   └── Product
│   │       │               └── Import
│   │       │                   └── Product
│   │       │                       └── Type
│   │       │                           └── Bundle
│   │       ├── CacheInvalidate
│   │       │   ├── etc
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   ├── Observer
│   │       │   └── Test
│   │       │       ├── Mftf
│   │       │       └── Unit
│   │       │           ├── Model
│   │       │           └── Observer
│   │       ├── Captcha
│   │       │   ├── Block
│   │       │   │   ├── Adminhtml
│   │       │   │   │   └── Captcha
│   │       │   │   └── Captcha
│   │       │   ├── Controller
│   │       │   │   ├── Adminhtml
│   │       │   │   │   └── Refresh
│   │       │   │   └── Refresh
│   │       │   ├── Cron
│   │       │   ├── CustomerData
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   ├── crontab
│   │       │   │   └── frontend
│   │       │   ├── Helper
│   │       │   │   └── Adminhtml
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Cart
│   │       │   │   ├── Checkout
│   │       │   │   ├── Config
│   │       │   │   │   └── Form
│   │       │   │   ├── Customer
│   │       │   │   │   └── Plugin
│   │       │   │   └── ResourceModel
│   │       │   ├── Observer
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Controller
│   │       │   │       │   └── Refresh
│   │       │   │       ├── Cron
│   │       │   │       ├── Helper
│   │       │   │       │   └── Adminhtml
│   │       │   │       ├── Model
│   │       │   │       │   ├── Cart
│   │       │   │       │   ├── Checkout
│   │       │   │       │   └── Customer
│   │       │   │       │       └── Plugin
│   │       │   │       └── Observer
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   └── web
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   └── js
│   │       │           └── web
│   │       │               ├── js
│   │       │               │   ├── action
│   │       │               │   ├── model
│   │       │               │   └── view
│   │       │               │       └── checkout
│   │       │               └── template
│   │       │                   └── checkout
│   │       ├── Catalog
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   │       └── ProductRender
│   │       │   ├── Block
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Category
│   │       │   │   │   │   ├── Checkboxes
│   │       │   │   │   │   ├── Edit
│   │       │   │   │   │   ├── Helper
│   │       │   │   │   │   │   └── Sortby
│   │       │   │   │   │   ├── Tab
│   │       │   │   │   │   └── Widget
│   │       │   │   │   ├── Form
│   │       │   │   │   │   └── Renderer
│   │       │   │   │   │       ├── Config
│   │       │   │   │   │       └── Fieldset
│   │       │   │   │   ├── Helper
│   │       │   │   │   │   └── Form
│   │       │   │   │   │       └── Wysiwyg
│   │       │   │   │   ├── Product
│   │       │   │   │   │   ├── Attribute
│   │       │   │   │   │   │   ├── Button
│   │       │   │   │   │   │   ├── Edit
│   │       │   │   │   │   │   │   └── Tab
│   │       │   │   │   │   │   ├── NewAttribute
│   │       │   │   │   │   │   │   └── Product
│   │       │   │   │   │   │   └── Set
│   │       │   │   │   │   │       ├── Main
│   │       │   │   │   │   │       │   └── Tree
│   │       │   │   │   │   │       └── Toolbar
│   │       │   │   │   │   │           └── Main
│   │       │   │   │   │   ├── Composite
│   │       │   │   │   │   │   ├── Fieldset
│   │       │   │   │   │   │   └── Update
│   │       │   │   │   │   ├── Edit
│   │       │   │   │   │   │   ├── Action
│   │       │   │   │   │   │   │   └── Attribute
│   │       │   │   │   │   │   │       └── Tab
│   │       │   │   │   │   │   ├── Button
│   │       │   │   │   │   │   └── Tab
│   │       │   │   │   │   │       ├── Ajax
│   │       │   │   │   │   │       ├── Alerts
│   │       │   │   │   │   │       ├── Attributes
│   │       │   │   │   │   │       ├── Options
│   │       │   │   │   │   │       │   ├── Popup
│   │       │   │   │   │   │       │   └── Type
│   │       │   │   │   │   │       └── Price
│   │       │   │   │   │   │           └── Group
│   │       │   │   │   │   ├── Frontend
│   │       │   │   │   │   │   └── Product
│   │       │   │   │   │   ├── Helper
│   │       │   │   │   │   │   └── Form
│   │       │   │   │   │   │       └── Gallery
│   │       │   │   │   │   ├── Options
│   │       │   │   │   │   └── Widget
│   │       │   │   │   │       └── Chooser
│   │       │   │   │   └── Rss
│   │       │   │   │       └── Grid
│   │       │   │   ├── Category
│   │       │   │   │   ├── Plugin
│   │       │   │   │   └── Rss
│   │       │   │   ├── Product
│   │       │   │   │   ├── Compare
│   │       │   │   │   ├── ProductList
│   │       │   │   │   │   └── Item
│   │       │   │   │   │       └── AddTo
│   │       │   │   │   ├── ReviewRenderer
│   │       │   │   │   ├── View
│   │       │   │   │   │   ├── AddTo
│   │       │   │   │   │   ├── Options
│   │       │   │   │   │   │   └── Type
│   │       │   │   │   │   │       └── Select
│   │       │   │   │   │   └── Type
│   │       │   │   │   └── Widget
│   │       │   │   │       └── Html
│   │       │   │   ├── Rss
│   │       │   │   │   └── Product
│   │       │   │   ├── Ui
│   │       │   │   └── Widget
│   │       │   ├── Console
│   │       │   │   └── Command
│   │       │   ├── Controller
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Category
│   │       │   │   │   │   ├── Image
│   │       │   │   │   │   └── Widget
│   │       │   │   │   └── Product
│   │       │   │   │       ├── Action
│   │       │   │   │       │   └── Attribute
│   │       │   │   │       ├── Attribute
│   │       │   │   │       ├── Datafeeds
│   │       │   │   │       ├── Gallery
│   │       │   │   │       ├── Group
│   │       │   │   │       ├── Initialization
│   │       │   │   │       │   └── Helper
│   │       │   │   │       │       └── Plugin
│   │       │   │   │       │           └── Handler
│   │       │   │   │       ├── Set
│   │       │   │   │       └── Widget
│   │       │   │   ├── Category
│   │       │   │   ├── Index
│   │       │   │   └── Product
│   │       │   │       ├── Compare
│   │       │   │       ├── Frontend
│   │       │   │       │   └── Action
│   │       │   │       └── View
│   │       │   ├── Cron
│   │       │   ├── CustomerData
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   ├── frontend
│   │       │   │   ├── webapi_rest
│   │       │   │   └── webapi_soap
│   │       │   ├── Helper
│   │       │   │   └── Product
│   │       │   │       ├── Configuration
│   │       │   │       ├── Edit
│   │       │   │       │   └── Action
│   │       │   │       └── Flat
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Api
│   │       │   │   │   └── SearchCriteria
│   │       │   │   │       └── CollectionProcessor
│   │       │   │   │           ├── ConditionProcessor
│   │       │   │   │           │   └── ConditionBuilder
│   │       │   │   │           └── FilterProcessor
│   │       │   │   ├── Attribute
│   │       │   │   │   ├── Backend
│   │       │   │   │   ├── Config
│   │       │   │   │   └── Source
│   │       │   │   ├── Category
│   │       │   │   │   ├── Attribute
│   │       │   │   │   │   ├── Backend
│   │       │   │   │   │   └── Source
│   │       │   │   │   ├── Link
│   │       │   │   │   └── Product
│   │       │   │   ├── Config
│   │       │   │   │   ├── Backend
│   │       │   │   │   ├── CatalogClone
│   │       │   │   │   │   └── Media
│   │       │   │   │   └── Source
│   │       │   │   │       ├── Price
│   │       │   │   │       ├── Product
│   │       │   │   │       │   └── Options
│   │       │   │   │       └── Watermark
│   │       │   │   ├── CustomOptions
│   │       │   │   ├── Entity
│   │       │   │   │   └── Product
│   │       │   │   │       └── Attribute
│   │       │   │   │           ├── Design
│   │       │   │   │           │   └── Options
│   │       │   │   │           └── Group
│   │       │   │   ├── Indexer
│   │       │   │   │   ├── Category
│   │       │   │   │   │   ├── Flat
│   │       │   │   │   │   │   ├── Action
│   │       │   │   │   │   │   ├── Plugin
│   │       │   │   │   │   │   └── System
│   │       │   │   │   │   │       └── Config
│   │       │   │   │   │   └── Product
│   │       │   │   │   │       ├── Action
│   │       │   │   │   │       └── Plugin
│   │       │   │   │   └── Product
│   │       │   │   │       ├── Category
│   │       │   │   │       │   └── Action
│   │       │   │   │       ├── Eav
│   │       │   │   │       │   ├── Action
│   │       │   │   │       │   └── Plugin
│   │       │   │   │       │       └── AttributeSet
│   │       │   │   │       ├── Flat
│   │       │   │   │       │   ├── Action
│   │       │   │   │       │   │   └── Rows
│   │       │   │   │       │   ├── Plugin
│   │       │   │   │       │   ├── System
│   │       │   │   │       │   │   └── Config
│   │       │   │   │       │   └── Table
│   │       │   │   │       └── Price
│   │       │   │   │           ├── Action
│   │       │   │   │           ├── Plugin
│   │       │   │   │           └── System
│   │       │   │   │               └── Config
│   │       │   │   ├── Layer
│   │       │   │   │   ├── Category
│   │       │   │   │   ├── Filter
│   │       │   │   │   │   ├── DataProvider
│   │       │   │   │   │   ├── Dynamic
│   │       │   │   │   │   ├── Item
│   │       │   │   │   │   └── Price
│   │       │   │   │   └── Search
│   │       │   │   │       └── Filter
│   │       │   │   ├── Layout
│   │       │   │   ├── Locator
│   │       │   │   ├── Plugin
│   │       │   │   │   └── ProductRepository
│   │       │   │   ├── Product
│   │       │   │   │   ├── Attribute
│   │       │   │   │   │   ├── Backend
│   │       │   │   │   │   │   ├── GroupPrice
│   │       │   │   │   │   │   ├── Media
│   │       │   │   │   │   │   └── TierPrice
│   │       │   │   │   │   ├── Frontend
│   │       │   │   │   │   │   └── Inputtype
│   │       │   │   │   │   └── Source
│   │       │   │   │   ├── AttributeSet
│   │       │   │   │   ├── Compare
│   │       │   │   │   ├── Condition
│   │       │   │   │   ├── Configuration
│   │       │   │   │   │   └── Item
│   │       │   │   │   │       └── Option
│   │       │   │   │   ├── CopyConstructor
│   │       │   │   │   ├── Edit
│   │       │   │   │   ├── Gallery
│   │       │   │   │   ├── Image
│   │       │   │   │   ├── Initialization
│   │       │   │   │   │   └── Helper
│   │       │   │   │   ├── Link
│   │       │   │   │   ├── Media
│   │       │   │   │   ├── Option
│   │       │   │   │   │   ├── Type
│   │       │   │   │   │   │   └── File
│   │       │   │   │   │   └── Validator
│   │       │   │   │   ├── Price
│   │       │   │   │   │   └── Validation
│   │       │   │   │   ├── PriceModifier
│   │       │   │   │   ├── Pricing
│   │       │   │   │   │   └── Renderer
│   │       │   │   │   ├── ProductFrontendAction
│   │       │   │   │   ├── ProductList
│   │       │   │   │   ├── Type
│   │       │   │   │   │   └── Price
│   │       │   │   │   └── Website
│   │       │   │   ├── ProductLink
│   │       │   │   │   ├── CollectionProvider
│   │       │   │   │   └── Converter
│   │       │   │   ├── ProductOptions
│   │       │   │   │   └── Config
│   │       │   │   ├── ProductRender
│   │       │   │   ├── ProductRepository
│   │       │   │   ├── ProductTypes
│   │       │   │   │   └── Config
│   │       │   │   ├── ResourceModel
│   │       │   │   │   ├── Attribute
│   │       │   │   │   ├── Category
│   │       │   │   │   │   ├── Attribute
│   │       │   │   │   │   │   ├── Frontend
│   │       │   │   │   │   │   └── Source
│   │       │   │   │   │   ├── Collection
│   │       │   │   │   │   └── Flat
│   │       │   │   │   ├── Collection
│   │       │   │   │   ├── Eav
│   │       │   │   │   ├── Indexer
│   │       │   │   │   ├── Layer
│   │       │   │   │   │   └── Filter
│   │       │   │   │   ├── Product
│   │       │   │   │   │   ├── Attribute
│   │       │   │   │   │   │   └── Backend
│   │       │   │   │   │   │       └── GroupPrice
│   │       │   │   │   │   ├── Collection
│   │       │   │   │   │   ├── Compare
│   │       │   │   │   │   │   └── Item
│   │       │   │   │   │   ├── Indexer
│   │       │   │   │   │   │   ├── Eav
│   │       │   │   │   │   │   └── Price
│   │       │   │   │   │   │       └── Query
│   │       │   │   │   │   ├── Link
│   │       │   │   │   │   │   └── Product
│   │       │   │   │   │   ├── Option
│   │       │   │   │   │   │   └── Value
│   │       │   │   │   │   ├── Price
│   │       │   │   │   │   └── Website
│   │       │   │   │   ├── ProductFrontendAction
│   │       │   │   │   └── Setup
│   │       │   │   ├── Rss
│   │       │   │   │   └── Product
│   │       │   │   ├── System
│   │       │   │   │   └── Config
│   │       │   │   │       ├── Backend
│   │       │   │   │       │   └── Catalog
│   │       │   │   │       │       └── Url
│   │       │   │   │       │           └── Rewrite
│   │       │   │   │       └── Source
│   │       │   │   ├── Template
│   │       │   │   │   └── Filter
│   │       │   │   ├── View
│   │       │   │   │   └── Asset
│   │       │   │   │       └── Image
│   │       │   │   ├── Webapi
│   │       │   │   │   └── Product
│   │       │   │   │       └── Option
│   │       │   │   │           └── Type
│   │       │   │   │               └── File
│   │       │   │   └── Widget
│   │       │   ├── Observer
│   │       │   │   └── Compare
│   │       │   ├── Plugin
│   │       │   │   ├── Block
│   │       │   │   ├── Framework
│   │       │   │   │   └── App
│   │       │   │   │       └── Action
│   │       │   │   └── Model
│   │       │   │       ├── Attribute
│   │       │   │       │   └── Backend
│   │       │   │       ├── AttributeSetRepository
│   │       │   │       ├── Indexer
│   │       │   │       │   └── Category
│   │       │   │       │       └── Product
│   │       │   │       ├── Product
│   │       │   │       │   ├── Action
│   │       │   │       │   └── Option
│   │       │   │       └── ResourceModel
│   │       │   │           └── Attribute
│   │       │   ├── Pricing
│   │       │   │   ├── Price
│   │       │   │   └── Render
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       ├── Data
│   │       │   │       └── Schema
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Metadata
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   ├── Category
│   │       │   │       │   │   ├── Product
│   │       │   │       │   │   │   ├── Attribute
│   │       │   │       │   │   │   │   ├── Button
│   │       │   │       │   │   │   │   └── Edit
│   │       │   │       │   │   │   │       └── Tab
│   │       │   │       │   │   │   ├── Composite
│   │       │   │       │   │   │   │   └── Fieldset
│   │       │   │       │   │   │   ├── Edit
│   │       │   │       │   │   │   │   ├── Action
│   │       │   │       │   │   │   │   │   └── Attribute
│   │       │   │       │   │   │   │   │       └── Tab
│   │       │   │       │   │   │   │   ├── Button
│   │       │   │       │   │   │   │   └── Tab
│   │       │   │       │   │   │   ├── Helper
│   │       │   │       │   │   │   │   └── Form
│   │       │   │       │   │   │   │       └── Gallery
│   │       │   │       │   │   │   └── Options
│   │       │   │       │   │   └── Rss
│   │       │   │       │   │       └── Grid
│   │       │   │       │   ├── Category
│   │       │   │       │   │   ├── Plugin
│   │       │   │       │   │   └── Rss
│   │       │   │       │   ├── Product
│   │       │   │       │   │   ├── Compare
│   │       │   │       │   │   ├── ProductList
│   │       │   │       │   │   ├── View
│   │       │   │       │   │   └── Widget
│   │       │   │       │   ├── Rss
│   │       │   │       │   │   └── Product
│   │       │   │       │   ├── Ui
│   │       │   │       │   └── Widget
│   │       │   │       ├── Controller
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   ├── Category
│   │       │   │       │   │   │   ├── Image
│   │       │   │       │   │   │   └── Widget
│   │       │   │       │   │   └── Product
│   │       │   │       │   │       ├── Action
│   │       │   │       │   │       │   └── Attribute
│   │       │   │       │   │       ├── Attribute
│   │       │   │       │   │       └── Initialization
│   │       │   │       │   │           └── Helper
│   │       │   │       │   │               └── Plugin
│   │       │   │       │   │                   └── Handler
│   │       │   │       │   ├── Category
│   │       │   │       │   └── Product
│   │       │   │       │       ├── Compare
│   │       │   │       │       └── Frontend
│   │       │   │       │           └── Action
│   │       │   │       ├── Cron
│   │       │   │       ├── CustomerData
│   │       │   │       ├── _files
│   │       │   │       │   └── catalog
│   │       │   │       │       └── product
│   │       │   │       │           └── watermark
│   │       │   │       ├── Helper
│   │       │   │       │   └── Product
│   │       │   │       │       ├── Edit
│   │       │   │       │       │   └── Action
│   │       │   │       │       └── Flat
│   │       │   │       ├── Model
│   │       │   │       │   ├── Api
│   │       │   │       │   │   └── SearchCriteria
│   │       │   │       │   │       └── CollectionProcessor
│   │       │   │       │   │           ├── ConditionProcessor
│   │       │   │       │   │           │   └── ConditionBuilder
│   │       │   │       │   │           └── FilterProcessor
│   │       │   │       │   ├── Attribute
│   │       │   │       │   │   ├── Backend
│   │       │   │       │   │   │   └── TierPrice
│   │       │   │       │   │   └── Config
│   │       │   │       │   │       └── _files
│   │       │   │       │   ├── Category
│   │       │   │       │   │   ├── Attribute
│   │       │   │       │   │   │   ├── Backend
│   │       │   │       │   │   │   └── Source
│   │       │   │       │   │   ├── Link
│   │       │   │       │   │   └── Product
│   │       │   │       │   ├── Config
│   │       │   │       │   │   ├── CatalogClone
│   │       │   │       │   │   │   └── Media
│   │       │   │       │   │   └── Source
│   │       │   │       │   │       └── Product
│   │       │   │       │   │           └── Options
│   │       │   │       │   ├── CustomOptions
│   │       │   │       │   ├── Entity
│   │       │   │       │   ├── _files
│   │       │   │       │   ├── Indexer
│   │       │   │       │   │   ├── Category
│   │       │   │       │   │   │   ├── Flat
│   │       │   │       │   │   │   │   ├── Plugin
│   │       │   │       │   │   │   │   └── System
│   │       │   │       │   │   │   │       └── Config
│   │       │   │       │   │   │   └── Product
│   │       │   │       │   │   │       └── Plugin
│   │       │   │       │   │   └── Product
│   │       │   │       │   │       ├── Category
│   │       │   │       │   │       │   └── Plugin
│   │       │   │       │   │       ├── Eav
│   │       │   │       │   │       │   ├── Action
│   │       │   │       │   │       │   └── Plugin
│   │       │   │       │   │       │       └── AttributeSet
│   │       │   │       │   │       ├── Flat
│   │       │   │       │   │       │   ├── Action
│   │       │   │       │   │       │   │   └── Rows
│   │       │   │       │   │       │   ├── Plugin
│   │       │   │       │   │       │   ├── System
│   │       │   │       │   │       │   │   └── Config
│   │       │   │       │   │       │   └── Table
│   │       │   │       │   │       └── Price
│   │       │   │       │   │           ├── Action
│   │       │   │       │   │           ├── Plugin
│   │       │   │       │   │           └── System
│   │       │   │       │   │               └── Config
│   │       │   │       │   ├── Layer
│   │       │   │       │   │   ├── Category
│   │       │   │       │   │   ├── Filter
│   │       │   │       │   │   │   ├── DataProvider
│   │       │   │       │   │   │   └── Item
│   │       │   │       │   │   └── Search
│   │       │   │       │   ├── Layout
│   │       │   │       │   ├── Locator
│   │       │   │       │   ├── Plugin
│   │       │   │       │   │   └── ProductRepository
│   │       │   │       │   ├── Product
│   │       │   │       │   │   ├── Attribute
│   │       │   │       │   │   │   ├── Backend
│   │       │   │       │   │   │   │   ├── GroupPrice
│   │       │   │       │   │   │   │   └── Media
│   │       │   │       │   │   │   ├── Frontend
│   │       │   │       │   │   │   │   └── InputType
│   │       │   │       │   │   │   └── Source
│   │       │   │       │   │   ├── Compare
│   │       │   │       │   │   ├── CopyConstructor
│   │       │   │       │   │   ├── Gallery
│   │       │   │       │   │   ├── Image
│   │       │   │       │   │   ├── Initialization
│   │       │   │       │   │   │   └── Helper
│   │       │   │       │   │   ├── Link
│   │       │   │       │   │   ├── Media
│   │       │   │       │   │   ├── Option
│   │       │   │       │   │   │   ├── Type
│   │       │   │       │   │   │   └── Validator
│   │       │   │       │   │   ├── Price
│   │       │   │       │   │   │   └── Validation
│   │       │   │       │   │   ├── PriceModifier
│   │       │   │       │   │   ├── Pricing
│   │       │   │       │   │   │   └── Renderer
│   │       │   │       │   │   ├── ProductFrontendAction
│   │       │   │       │   │   ├── ProductList
│   │       │   │       │   │   ├── Type
│   │       │   │       │   │   └── Website
│   │       │   │       │   ├── ProductLink
│   │       │   │       │   ├── ProductOptions
│   │       │   │       │   │   └── Config
│   │       │   │       │   │       └── _files
│   │       │   │       │   ├── ProductRender
│   │       │   │       │   ├── ProductTypes
│   │       │   │       │   │   └── Config
│   │       │   │       │   │       └── _files
│   │       │   │       │   ├── ResourceModel
│   │       │   │       │   │   ├── Attribute
│   │       │   │       │   │   ├── Category
│   │       │   │       │   │   │   └── Collection
│   │       │   │       │   │   ├── Eav
│   │       │   │       │   │   ├── Indexer
│   │       │   │       │   │   └── Product
│   │       │   │       │   │       ├── Collection
│   │       │   │       │   │       ├── Indexer
│   │       │   │       │   │       │   ├── Eav
│   │       │   │       │   │       │   └── Price
│   │       │   │       │   │       ├── Link
│   │       │   │       │   │       │   └── Product
│   │       │   │       │   │       ├── Option
│   │       │   │       │   │       └── Website
│   │       │   │       │   ├── Rss
│   │       │   │       │   │   └── Product
│   │       │   │       │   ├── System
│   │       │   │       │   │   └── Config
│   │       │   │       │   │       ├── Backend
│   │       │   │       │   │       │   └── Catalog
│   │       │   │       │   │       │       └── Url
│   │       │   │       │   │       │           └── Rewrite
│   │       │   │       │   │       └── Source
│   │       │   │       │   ├── Template
│   │       │   │       │   │   └── Filter
│   │       │   │       │   └── View
│   │       │   │       │       └── Asset
│   │       │   │       │           └── Image
│   │       │   │       ├── Observer
│   │       │   │       ├── Plugin
│   │       │   │       │   ├── Block
│   │       │   │       │   └── Model
│   │       │   │       │       ├── Attribute
│   │       │   │       │       │   └── Backend
│   │       │   │       │       ├── AttributeSetRepository
│   │       │   │       │       ├── Indexer
│   │       │   │       │       │   └── Category
│   │       │   │       │       │       └── Product
│   │       │   │       │       ├── Product
│   │       │   │       │       │   └── Action
│   │       │   │       │       └── ResourceModel
│   │       │   │       │           └── Attribute
│   │       │   │       ├── Pricing
│   │       │   │       │   ├── Price
│   │       │   │       │   └── Render
│   │       │   │       ├── Setup
│   │       │   │       ├── Ui
│   │       │   │       │   ├── Component
│   │       │   │       │   │   ├── Listing
│   │       │   │       │   │   │   └── Columns
│   │       │   │       │   │   └── Product
│   │       │   │       │   │       └── Form
│   │       │   │       │   │           └── Categories
│   │       │   │       │   └── DataProvider
│   │       │   │       │       └── Product
│   │       │   │       │           ├── Form
│   │       │   │       │           │   └── Modifier
│   │       │   │       │           ├── Listing
│   │       │   │       │           │   └── Collector
│   │       │   │       │           └── Related
│   │       │   │       └── ViewModel
│   │       │   │           └── Product
│   │       │   ├── Ui
│   │       │   │   ├── Component
│   │       │   │   │   ├── Category
│   │       │   │   │   │   └── Form
│   │       │   │   │   │       └── Element
│   │       │   │   │   ├── Listing
│   │       │   │   │   │   ├── Attribute
│   │       │   │   │   │   └── Columns
│   │       │   │   │   ├── Product
│   │       │   │   │   │   └── Form
│   │       │   │   │   │       └── Categories
│   │       │   │   │   └── UrlInput
│   │       │   │   └── DataProvider
│   │       │   │       └── Product
│   │       │   │           ├── Attributes
│   │       │   │           ├── Form
│   │       │   │           │   └── Modifier
│   │       │   │           │       └── Eav
│   │       │   │           ├── Listing
│   │       │   │           │   └── Collector
│   │       │   │           └── Related
│   │       │   ├── view
│   │       │   │   ├── adminhtml
│   │       │   │   │   ├── layout
│   │       │   │   │   ├── templates
│   │       │   │   │   │   ├── catalog
│   │       │   │   │   │   │   ├── category
│   │       │   │   │   │   │   │   ├── checkboxes
│   │       │   │   │   │   │   │   ├── edit
│   │       │   │   │   │   │   │   └── widget
│   │       │   │   │   │   │   ├── form
│   │       │   │   │   │   │   │   └── renderer
│   │       │   │   │   │   │   │       └── fieldset
│   │       │   │   │   │   │   └── product
│   │       │   │   │   │   │       ├── attribute
│   │       │   │   │   │   │       │   └── set
│   │       │   │   │   │   │       │       ├── main
│   │       │   │   │   │   │       │       │   └── tree
│   │       │   │   │   │   │       │       └── toolbar
│   │       │   │   │   │   │       ├── composite
│   │       │   │   │   │   │       │   └── fieldset
│   │       │   │   │   │   │       │       └── options
│   │       │   │   │   │   │       │           └── type
│   │       │   │   │   │   │       ├── edit
│   │       │   │   │   │   │       │   ├── action
│   │       │   │   │   │   │       │   ├── category
│   │       │   │   │   │   │       │   │   └── new
│   │       │   │   │   │   │       │   ├── options
│   │       │   │   │   │   │       │   │   └── type
│   │       │   │   │   │   │       │   └── price
│   │       │   │   │   │   │       ├── helper
│   │       │   │   │   │   │       ├── tab
│   │       │   │   │   │   │       └── widget
│   │       │   │   │   │   │           └── chooser
│   │       │   │   │   │   ├── product
│   │       │   │   │   │   │   ├── edit
│   │       │   │   │   │   │   │   ├── attribute
│   │       │   │   │   │   │   │   └── tabs
│   │       │   │   │   │   │   └── grid
│   │       │   │   │   │   └── rss
│   │       │   │   │   │       └── grid
│   │       │   │   │   ├── ui_component
│   │       │   │   │   └── web
│   │       │   │   │       ├── catalog
│   │       │   │   │       │   ├── category
│   │       │   │   │       │   ├── images
│   │       │   │   │       │   └── product
│   │       │   │   │       │       ├── attribute
│   │       │   │   │       │       ├── composite
│   │       │   │   │       │       └── edit
│   │       │   │   │       ├── component
│   │       │   │   │       ├── images
│   │       │   │   │       ├── js
│   │       │   │   │       │   ├── components
│   │       │   │   │       │   │   ├── disable-on-option
│   │       │   │   │       │   │   ├── use-parent-settings
│   │       │   │   │       │   │   └── visible-on-option
│   │       │   │   │       │   ├── form
│   │       │   │   │       │   │   └── element
│   │       │   │   │       │   ├── product
│   │       │   │   │       │   ├── tier-price
│   │       │   │   │       │   └── utils
│   │       │   │   │       ├── product
│   │       │   │   │       │   └── images
│   │       │   │   │       └── template
│   │       │   │   │           ├── attributes
│   │       │   │   │           │   └── grid
│   │       │   │   │           └── form
│   │       │   │   │               └── element
│   │       │   │   │                   └── helper
│   │       │   │   ├── base
│   │       │   │   │   ├── layout
│   │       │   │   │   ├── templates
│   │       │   │   │   │   ├── js
│   │       │   │   │   │   └── product
│   │       │   │   │   │       ├── composite
│   │       │   │   │   │       │   └── fieldset
│   │       │   │   │   │       │       └── options
│   │       │   │   │   │       │           └── view
│   │       │   │   │   │       └── price
│   │       │   │   │   │           └── amount
│   │       │   │   │   └── web
│   │       │   │   │       ├── images
│   │       │   │   │       │   └── product
│   │       │   │   │       │       └── placeholder
│   │       │   │   │       ├── js
│   │       │   │   │       │   └── product
│   │       │   │   │       │       └── list
│   │       │   │   │       │           └── columns
│   │       │   │   │       └── template
│   │       │   │   │           └── product
│   │       │   │   │               ├── list
│   │       │   │   │               │   └── columns
│   │       │   │   │               └── price
│   │       │   │   └── frontend
│   │       │   │       ├── layout
│   │       │   │       ├── templates
│   │       │   │       │   ├── category
│   │       │   │       │   │   └── widget
│   │       │   │       │   │       └── link
│   │       │   │       │   ├── messages
│   │       │   │       │   ├── navigation
│   │       │   │       │   └── product
│   │       │   │       │       ├── compare
│   │       │   │       │       ├── list
│   │       │   │       │       │   ├── addto
│   │       │   │       │       │   └── toolbar
│   │       │   │       │       ├── view
│   │       │   │       │       │   ├── addto
│   │       │   │       │       │   ├── opengraph
│   │       │   │       │       │   ├── options
│   │       │   │       │       │   │   ├── type
│   │       │   │       │       │   │   └── wrapper
│   │       │   │       │       │   └── type
│   │       │   │       │       └── widget
│   │       │   │       │           ├── compared
│   │       │   │       │           ├── link
│   │       │   │       │           ├── new
│   │       │   │       │           │   ├── column
│   │       │   │       │           │   └── content
│   │       │   │       │           └── viewed
│   │       │   │       ├── ui_component
│   │       │   │       └── web
│   │       │   │           ├── images
│   │       │   │           ├── js
│   │       │   │           │   ├── product
│   │       │   │           │   │   ├── list
│   │       │   │           │   │   ├── storage
│   │       │   │           │   │   └── view
│   │       │   │           │   └── view
│   │       │   │           ├── product
│   │       │   │           │   └── view
│   │       │   │           └── template
│   │       │   │               └── product
│   │       │   └── ViewModel
│   │       │       └── Product
│   │       │           └── Checker
│   │       ├── CatalogAnalytics
│   │       │   ├── etc
│   │       │   └── Test
│   │       │       └── Mftf
│   │       ├── CatalogGraphQl
│   │       │   ├── etc
│   │       │   │   └── graphql
│   │       │   ├── Model
│   │       │   │   ├── Category
│   │       │   │   ├── Config
│   │       │   │   ├── Layer
│   │       │   │   ├── Product
│   │       │   │   │   └── Option
│   │       │   │   ├── Resolver
│   │       │   │   │   ├── Category
│   │       │   │   │   │   └── DataProvider
│   │       │   │   │   ├── Layer
│   │       │   │   │   │   └── DataProvider
│   │       │   │   │   ├── Product
│   │       │   │   │   │   ├── ProductImage
│   │       │   │   │   │   └── Websites
│   │       │   │   │   └── Products
│   │       │   │   │       ├── Attributes
│   │       │   │   │       ├── DataProvider
│   │       │   │   │       │   ├── Deferred
│   │       │   │   │       │   ├── Image
│   │       │   │   │       │   │   └── Placeholder
│   │       │   │   │       │   └── Product
│   │       │   │   │       │       └── CollectionProcessor
│   │       │   │   │       ├── FilterArgument
│   │       │   │   │       ├── Query
│   │       │   │   │       └── SearchCriteria
│   │       │   │   │           ├── CollectionProcessor
│   │       │   │   │           │   └── FilterProcessor
│   │       │   │   │           └── Helper
│   │       │   │   └── Search
│   │       │   │       └── Adapter
│   │       │   │           └── Mysql
│   │       │   │               └── Query
│   │       │   │                   └── Builder
│   │       │   └── Test
│   │       │       └── Mftf
│   │       ├── CatalogImportExport
│   │       │   ├── etc
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Export
│   │       │   │   │   ├── Product
│   │       │   │   │   │   └── Type
│   │       │   │   │   └── RowCustomizer
│   │       │   │   ├── Import
│   │       │   │   │   ├── Product
│   │       │   │   │   │   ├── Type
│   │       │   │   │   │   └── Validator
│   │       │   │   │   └── Proxy
│   │       │   │   │       └── Product
│   │       │   │   └── Indexer
│   │       │   │       ├── Category
│   │       │   │       │   └── Product
│   │       │   │       │       └── Plugin
│   │       │   │       ├── Product
│   │       │   │       │   ├── Category
│   │       │   │       │   │   └── Plugin
│   │       │   │       │   ├── Eav
│   │       │   │       │   │   └── Plugin
│   │       │   │       │   ├── Flat
│   │       │   │       │   │   └── Plugin
│   │       │   │       │   └── Price
│   │       │   │       │       └── Plugin
│   │       │   │       └── Stock
│   │       │   │           └── Plugin
│   │       │   └── Test
│   │       │       ├── Mftf
│   │       │       │   ├── ActionGroup
│   │       │       │   └── Test
│   │       │       └── Unit
│   │       │           └── Model
│   │       │               ├── Export
│   │       │               ├── Import
│   │       │               │   └── Product
│   │       │               │       ├── Type
│   │       │               │       │   └── _files
│   │       │               │       └── Validator
│   │       │               └── Indexer
│   │       │                   ├── Product
│   │       │                   │   ├── Flat
│   │       │                   │   │   └── Plugin
│   │       │                   │   └── Price
│   │       │                   │       └── Plugin
│   │       │                   └── Stock
│   │       │                       └── Plugin
│   │       ├── CatalogInventory
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   ├── Block
│   │       │   │   ├── Adminhtml
│   │       │   │   │   └── Form
│   │       │   │   │       └── Field
│   │       │   │   ├── Plugin
│   │       │   │   └── Stockqty
│   │       │   │       └── Type
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Adminhtml
│   │       │   │   │   └── Stock
│   │       │   │   ├── Config
│   │       │   │   │   └── Backend
│   │       │   │   ├── Indexer
│   │       │   │   │   └── Stock
│   │       │   │   │       ├── Action
│   │       │   │   │       └── Plugin
│   │       │   │   ├── Plugin
│   │       │   │   ├── Product
│   │       │   │   │   └── CopyConstructor
│   │       │   │   ├── Quote
│   │       │   │   │   └── Item
│   │       │   │   │       └── QuantityValidator
│   │       │   │   │           └── Initializer
│   │       │   │   ├── ResourceModel
│   │       │   │   │   ├── Indexer
│   │       │   │   │   │   └── Stock
│   │       │   │   │   ├── Product
│   │       │   │   │   └── Stock
│   │       │   │   │       ├── Item
│   │       │   │   │       └── Status
│   │       │   │   ├── Source
│   │       │   │   ├── Spi
│   │       │   │   ├── Stock
│   │       │   │   └── System
│   │       │   │       └── Config
│   │       │   │           └── Backend
│   │       │   ├── Observer
│   │       │   ├── Plugin
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Api
│   │       │   │       ├── Block
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   └── Form
│   │       │   │       │   │       └── Field
│   │       │   │       │   ├── Plugin
│   │       │   │       │   └── Stockqty
│   │       │   │       ├── Helper
│   │       │   │       ├── Model
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   └── Stock
│   │       │   │       │   ├── Config
│   │       │   │       │   │   └── Backend
│   │       │   │       │   ├── Indexer
│   │       │   │       │   │   └── Stock
│   │       │   │       │   │       ├── Action
│   │       │   │       │   │       └── Plugin
│   │       │   │       │   ├── Plugin
│   │       │   │       │   ├── Product
│   │       │   │       │   │   └── CopyConstructor
│   │       │   │       │   ├── Quote
│   │       │   │       │   │   └── Item
│   │       │   │       │   │       └── QuantityValidator
│   │       │   │       │   │           └── Initializer
│   │       │   │       │   ├── ResourceModel
│   │       │   │       │   │   └── Product
│   │       │   │       │   ├── Source
│   │       │   │       │   ├── Spi
│   │       │   │       │   └── Stock
│   │       │   │       ├── Observer
│   │       │   │       └── Ui
│   │       │   │           ├── Component
│   │       │   │           │   └── Product
│   │       │   │           │       └── Form
│   │       │   │           │           └── Element
│   │       │   │           └── DataProvider
│   │       │   │               └── Product
│   │       │   │                   └── Form
│   │       │   │                       └── Modifier
│   │       │   ├── Ui
│   │       │   │   ├── Component
│   │       │   │   │   └── Product
│   │       │   │   │       └── Form
│   │       │   │   │           └── Element
│   │       │   │   └── DataProvider
│   │       │   │       └── Product
│   │       │   │           └── Form
│   │       │   │               └── Modifier
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── ui_component
│   │       │       │   └── web
│   │       │       │       └── js
│   │       │       │           └── components
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           └── templates
│   │       │               └── stockqty
│   │       ├── CatalogInventoryGraphQl
│   │       │   ├── etc
│   │       │   └── Model
│   │       │       └── Resolver
│   │       ├── CatalogRule
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   ├── Block
│   │       │   │   └── Adminhtml
│   │       │   │       ├── Edit
│   │       │   │       └── Promo
│   │       │   │           ├── Catalog
│   │       │   │           │   └── Edit
│   │       │   │           │       └── Tab
│   │       │   │           └── Widget
│   │       │   │               └── Chooser
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       └── Promo
│   │       │   │           ├── Catalog
│   │       │   │           └── Widget
│   │       │   ├── Cron
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   ├── crontab
│   │       │   │   ├── frontend
│   │       │   │   ├── webapi_rest
│   │       │   │   └── webapi_soap
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Data
│   │       │   │   │   └── Condition
│   │       │   │   ├── Indexer
│   │       │   │   │   ├── IndexBuilder
│   │       │   │   │   ├── Product
│   │       │   │   │   └── Rule
│   │       │   │   ├── Product
│   │       │   │   ├── ResourceModel
│   │       │   │   │   ├── Grid
│   │       │   │   │   ├── Product
│   │       │   │   │   └── Rule
│   │       │   │   │       └── Product
│   │       │   │   │           └── Price
│   │       │   │   └── Rule
│   │       │   │       ├── Action
│   │       │   │       ├── Condition
│   │       │   │       └── Product
│   │       │   ├── Observer
│   │       │   ├── Plugin
│   │       │   │   ├── Indexer
│   │       │   │   │   └── Product
│   │       │   │   │       └── Save
│   │       │   │   └── Model
│   │       │   │       └── Product
│   │       │   ├── Pricing
│   │       │   │   └── Price
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Metadata
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       └── Edit
│   │       │   │       ├── Cron
│   │       │   │       ├── Helper
│   │       │   │       ├── Model
│   │       │   │       │   ├── Data
│   │       │   │       │   │   └── Condition
│   │       │   │       │   ├── Indexer
│   │       │   │       │   │   ├── IndexBuilder
│   │       │   │       │   │   ├── Product
│   │       │   │       │   │   └── Rule
│   │       │   │       │   ├── Product
│   │       │   │       │   ├── ResourceModel
│   │       │   │       │   └── Rule
│   │       │   │       │       └── Condition
│   │       │   │       ├── Observer
│   │       │   │       ├── Plugin
│   │       │   │       │   ├── Indexer
│   │       │   │       │   │   └── Product
│   │       │   │       │   │       └── Save
│   │       │   │       │   └── Model
│   │       │   │       │       └── Product
│   │       │   │       └── Pricing
│   │       │   │           └── Price
│   │       │   └── view
│   │       │       └── adminhtml
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   └── promo
│   │       │           └── ui_component
│   │       ├── CatalogRuleConfigurable
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── crontab
│   │       │   ├── Plugin
│   │       │   │   ├── CatalogRule
│   │       │   │   │   └── Model
│   │       │   │   │       ├── Indexer
│   │       │   │   │       └── Rule
│   │       │   │   └── ConfigurableProduct
│   │       │   │       └── Model
│   │       │   │           └── ResourceModel
│   │       │   └── Test
│   │       │       ├── Mftf
│   │       │       │   ├── ActionGroup
│   │       │       │   └── Test
│   │       │       └── Unit
│   │       │           └── Plugin
│   │       │               └── CatalogRule
│   │       │                   └── Model
│   │       │                       └── Rule
│   │       ├── CatalogSearch
│   │       │   ├── Block
│   │       │   │   ├── Advanced
│   │       │   │   └── Plugin
│   │       │   ├── Controller
│   │       │   │   ├── Advanced
│   │       │   │   ├── Result
│   │       │   │   └── SearchTermsLog
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   ├── frontend
│   │       │   │   ├── webapi_rest
│   │       │   │   └── webapi_soap
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Adapter
│   │       │   │   │   ├── Aggregation
│   │       │   │   │   │   └── Checker
│   │       │   │   │   │       └── Query
│   │       │   │   │   └── Mysql
│   │       │   │   │       ├── Aggregation
│   │       │   │   │       │   └── DataProvider
│   │       │   │   │       │       └── SelectBuilderForAttribute
│   │       │   │   │       ├── BaseSelectStrategy
│   │       │   │   │       ├── Dynamic
│   │       │   │   │       ├── Field
│   │       │   │   │       ├── Filter
│   │       │   │   │       └── Plugin
│   │       │   │   │           └── Aggregation
│   │       │   │   │               └── Category
│   │       │   │   ├── Adminhtml
│   │       │   │   │   └── System
│   │       │   │   │       └── Config
│   │       │   │   │           └── Backend
│   │       │   │   ├── Advanced
│   │       │   │   │   └── Request
│   │       │   │   ├── Attribute
│   │       │   │   ├── Autocomplete
│   │       │   │   ├── Indexer
│   │       │   │   │   ├── Fulltext
│   │       │   │   │   │   ├── Action
│   │       │   │   │   │   ├── Model
│   │       │   │   │   │   │   └── Plugin
│   │       │   │   │   │   └── Plugin
│   │       │   │   │   │       ├── Product
│   │       │   │   │   │       └── Store
│   │       │   │   │   ├── Mview
│   │       │   │   │   └── Scope
│   │       │   │   ├── Layer
│   │       │   │   │   ├── Category
│   │       │   │   │   ├── Filter
│   │       │   │   │   └── Search
│   │       │   │   │       └── Plugin
│   │       │   │   ├── Price
│   │       │   │   ├── ResourceModel
│   │       │   │   │   ├── Advanced
│   │       │   │   │   ├── Fulltext
│   │       │   │   │   │   └── Collection
│   │       │   │   │   ├── Search
│   │       │   │   │   └── Setup
│   │       │   │   ├── Search
│   │       │   │   │   ├── BaseSelectStrategy
│   │       │   │   │   ├── FilterMapper
│   │       │   │   │   │   └── TermDropdownStrategy
│   │       │   │   │   ├── QueryChecker
│   │       │   │   │   ├── RequestGenerator
│   │       │   │   │   └── SelectContainer
│   │       │   │   └── Source
│   │       │   ├── Plugin
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Metadata
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   └── Plugin
│   │       │   │       ├── Controller
│   │       │   │       │   └── Advanced
│   │       │   │       ├── Model
│   │       │   │       │   ├── Adapter
│   │       │   │       │   │   ├── Aggregation
│   │       │   │       │   │   │   └── Checker
│   │       │   │       │   │   │       └── Query
│   │       │   │       │   │   └── Mysql
│   │       │   │       │   │       ├── Aggregation
│   │       │   │       │   │       │   └── DataProvider
│   │       │   │       │   │       ├── Dynamic
│   │       │   │       │   │       ├── Field
│   │       │   │       │   │       └── Filter
│   │       │   │       │   ├── Advanced
│   │       │   │       │   │   └── Request
│   │       │   │       │   ├── Attribute
│   │       │   │       │   ├── Autocomplete
│   │       │   │       │   ├── Indexer
│   │       │   │       │   │   ├── Fulltext
│   │       │   │       │   │   │   ├── Action
│   │       │   │       │   │   │   └── Plugin
│   │       │   │       │   │   │       ├── Product
│   │       │   │       │   │   │       └── Store
│   │       │   │       │   │   └── Scope
│   │       │   │       │   ├── Layer
│   │       │   │       │   │   ├── Catalog
│   │       │   │       │   │   ├── Filter
│   │       │   │       │   │   └── Search
│   │       │   │       │   │       └── Plugin
│   │       │   │       │   ├── ResourceModel
│   │       │   │       │   │   ├── Advanced
│   │       │   │       │   │   ├── Fulltext
│   │       │   │       │   │   └── Setup
│   │       │   │       │   └── Search
│   │       │   │       │       ├── BaseSelectStrategy
│   │       │   │       │       ├── FilterMapper
│   │       │   │       │       ├── Indexer
│   │       │   │       │       ├── QueryChecker
│   │       │   │       │       ├── RequestGenerator
│   │       │   │       │       └── SelectContainer
│   │       │   │       └── Plugin
│   │       │   ├── Ui
│   │       │   │   └── DataProvider
│   │       │   │       └── Product
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   └── ui_component
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   └── advanced
│   │       │           └── web
│   │       │               └── js
│   │       ├── CatalogUrlRewrite
│   │       │   ├── Block
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   ├── frontend
│   │       │   │   └── webapi_rest
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Category
│   │       │   │   │   └── Plugin
│   │       │   │   │       ├── Category
│   │       │   │   │       └── Store
│   │       │   │   ├── Map
│   │       │   │   ├── Product
│   │       │   │   ├── Products
│   │       │   │   ├── ResourceModel
│   │       │   │   │   └── Category
│   │       │   │   └── Storage
│   │       │   ├── Observer
│   │       │   ├── Plugin
│   │       │   │   ├── Catalog
│   │       │   │   │   ├── Block
│   │       │   │   │   │   └── Adminhtml
│   │       │   │   │   │       ├── Category
│   │       │   │   │   │       │   └── Tab
│   │       │   │   │   │       └── Product
│   │       │   │   │   │           └── Edit
│   │       │   │   │   │               └── Tab
│   │       │   │   │   └── Controller
│   │       │   │   │       └── Adminhtml
│   │       │   │   │           └── Product
│   │       │   │   │               └── Initialization
│   │       │   │   └── Webapi
│   │       │   │       └── Controller
│   │       │   │           └── Rest
│   │       │   ├── Service
│   │       │   │   └── V1
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Model
│   │       │   │       │   ├── Category
│   │       │   │       │   │   └── Plugin
│   │       │   │       │   │       ├── Category
│   │       │   │       │   │       └── Store
│   │       │   │       │   ├── Map
│   │       │   │       │   └── Product
│   │       │   │       ├── Observer
│   │       │   │       ├── Plugin
│   │       │   │       │   └── Webapi
│   │       │   │       │       └── Controller
│   │       │   │       │           └── Rest
│   │       │   │       ├── Service
│   │       │   │       │   └── V1
│   │       │   │       └── Ui
│   │       │   │           └── DataProvider
│   │       │   │               └── Product
│   │       │   │                   └── Form
│   │       │   │                       └── Modifier
│   │       │   ├── Ui
│   │       │   │   └── DataProvider
│   │       │   │       └── Product
│   │       │   │           └── Form
│   │       │   │               └── Modifier
│   │       │   └── view
│   │       │       └── adminhtml
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           └── ui_component
│   │       ├── CatalogUrlRewriteGraphQl
│   │       │   ├── etc
│   │       │   └── Test
│   │       │       └── Mftf
│   │       ├── CatalogWidget
│   │       │   ├── Block
│   │       │   │   └── Product
│   │       │   │       └── Widget
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       └── Product
│   │       │   │           └── Widget
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   └── Rule
│   │       │   │       └── Condition
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   └── Product
│   │       │   │       │       └── Widget
│   │       │   │       ├── Controller
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       └── Product
│   │       │   │       │           └── Widget
│   │       │   │       └── Model
│   │       │   │           └── Rule
│   │       │   │               └── Condition
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── templates
│   │       │       │   │   └── product
│   │       │       │   │       └── widget
│   │       │       │   └── web
│   │       │       │       └── images
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           └── templates
│   │       │               └── product
│   │       │                   └── widget
│   │       │                       └── content
│   │       ├── Checkout
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   ├── Block
│   │       │   │   ├── Adminhtml
│   │       │   │   ├── Cart
│   │       │   │   │   ├── Additional
│   │       │   │   │   └── Item
│   │       │   │   │       └── Renderer
│   │       │   │   │           └── Actions
│   │       │   │   ├── Checkout
│   │       │   │   ├── Item
│   │       │   │   │   └── Price
│   │       │   │   ├── Onepage
│   │       │   │   ├── Shipping
│   │       │   │   └── Total
│   │       │   ├── Controller
│   │       │   │   ├── Account
│   │       │   │   ├── Cart
│   │       │   │   ├── Express
│   │       │   │   ├── Index
│   │       │   │   ├── Noroute
│   │       │   │   ├── Onepage
│   │       │   │   ├── ShippingRates
│   │       │   │   └── Sidebar
│   │       │   ├── CustomerData
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Adminhtml
│   │       │   │   ├── Cart
│   │       │   │   ├── Config
│   │       │   │   │   └── Source
│   │       │   │   │       └── Cart
│   │       │   │   ├── Layout
│   │       │   │   ├── ResourceModel
│   │       │   │   ├── Session
│   │       │   │   └── Type
│   │       │   ├── Observer
│   │       │   ├── Plugin
│   │       │   │   └── Model
│   │       │   │       └── Quote
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   ├── Cart
│   │       │   │       │   │   └── Item
│   │       │   │       │   │       └── Renderer
│   │       │   │       │   │           └── Actions
│   │       │   │       │   ├── Checkout
│   │       │   │       │   ├── Item
│   │       │   │       │   │   └── Price
│   │       │   │       │   ├── Onepage
│   │       │   │       │   └── Shipping
│   │       │   │       ├── Controller
│   │       │   │       │   ├── Account
│   │       │   │       │   ├── Cart
│   │       │   │       │   ├── Index
│   │       │   │       │   ├── Sidebar
│   │       │   │       │   └── Stub
│   │       │   │       ├── CustomerData
│   │       │   │       ├── Helper
│   │       │   │       ├── Model
│   │       │   │       │   ├── Cart
│   │       │   │       │   ├── Config
│   │       │   │       │   │   └── Source
│   │       │   │       │   │       └── Cart
│   │       │   │       │   ├── Layout
│   │       │   │       │   ├── Session
│   │       │   │       │   └── Type
│   │       │   │       └── Observer
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   └── email
│   │       │       ├── base
│   │       │       │   └── web
│   │       │       │       └── js
│   │       │       │           └── model
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── page_layout
│   │       │           ├── templates
│   │       │           │   ├── cart
│   │       │           │   │   ├── additional
│   │       │           │   │   └── item
│   │       │           │   │       ├── configure
│   │       │           │   │       ├── price
│   │       │           │   │       └── renderer
│   │       │           │   │           └── actions
│   │       │           │   ├── item
│   │       │           │   │   └── price
│   │       │           │   ├── js
│   │       │           │   ├── messages
│   │       │           │   ├── onepage
│   │       │           │   │   └── review
│   │       │           │   │       └── item
│   │       │           │   │           └── price
│   │       │           │   ├── shipping
│   │       │           │   └── total
│   │       │           └── web
│   │       │               ├── js
│   │       │               │   ├── action
│   │       │               │   ├── model
│   │       │               │   │   ├── cart
│   │       │               │   │   │   └── totals-processor
│   │       │               │   │   ├── payment
│   │       │               │   │   ├── shipping-address
│   │       │               │   │   ├── shipping-rate-processor
│   │       │               │   │   └── shipping-save-processor
│   │       │               │   └── view
│   │       │               │       ├── billing-address
│   │       │               │       ├── cart
│   │       │               │       │   └── totals
│   │       │               │       ├── checkout
│   │       │               │       │   └── minicart
│   │       │               │       │       └── subtotal
│   │       │               │       ├── configure
│   │       │               │       ├── form
│   │       │               │       │   └── element
│   │       │               │       ├── payment
│   │       │               │       ├── review
│   │       │               │       │   └── actions
│   │       │               │       ├── shipping-address
│   │       │               │       │   └── address-renderer
│   │       │               │       ├── shipping-information
│   │       │               │       │   └── address-renderer
│   │       │               │       └── summary
│   │       │               │           └── item
│   │       │               │               └── details
│   │       │               └── template
│   │       │                   ├── billing-address
│   │       │                   ├── cart
│   │       │                   │   └── totals
│   │       │                   ├── form
│   │       │                   │   └── element
│   │       │                   ├── minicart
│   │       │                   │   ├── item
│   │       │                   │   └── subtotal
│   │       │                   ├── payment
│   │       │                   ├── payment-methods
│   │       │                   ├── review
│   │       │                   │   └── actions
│   │       │                   ├── shipping-address
│   │       │                   │   └── address-renderer
│   │       │                   ├── shipping-information
│   │       │                   │   └── address-renderer
│   │       │                   └── summary
│   │       │                       └── item
│   │       │                           └── details
│   │       ├── CheckoutAgreements
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   ├── Block
│   │       │   │   └── Adminhtml
│   │       │   │       └── Agreement
│   │       │   │           └── Edit
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       └── Agreement
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Api
│   │       │   │   │   └── SearchCriteria
│   │       │   │   │       └── CollectionProcessor
│   │       │   │   │           └── FilterProcessor
│   │       │   │   ├── Checkout
│   │       │   │   │   └── Plugin
│   │       │   │   └── ResourceModel
│   │       │   │       └── Agreement
│   │       │   │           └── Grid
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── Data
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       └── Model
│   │       │   │           ├── Api
│   │       │   │           │   └── SearchCriteria
│   │       │   │           │       └── CollectionProcessor
│   │       │   │           │           └── FilterProcessor
│   │       │   │           └── Checkout
│   │       │   │               └── Plugin
│   │       │   └── view
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           └── web
│   │       │               ├── js
│   │       │               │   ├── model
│   │       │               │   └── view
│   │       │               └── template
│   │       │                   └── checkout
│   │       ├── CheckoutAgreementsGraphQl
│   │       │   ├── etc
│   │       │   └── Model
│   │       │       └── Resolver
│   │       ├── Cms
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   ├── Block
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Block
│   │       │   │   │   │   ├── Edit
│   │       │   │   │   │   └── Widget
│   │       │   │   │   ├── Page
│   │       │   │   │   │   ├── Edit
│   │       │   │   │   │   ├── Grid
│   │       │   │   │   │   │   └── Renderer
│   │       │   │   │   │   │       └── Action
│   │       │   │   │   │   └── Widget
│   │       │   │   │   └── Wysiwyg
│   │       │   │   │       └── Images
│   │       │   │   │           └── Content
│   │       │   │   └── Widget
│   │       │   │       └── Page
│   │       │   ├── Controller
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Block
│   │       │   │   │   │   └── Widget
│   │       │   │   │   ├── Page
│   │       │   │   │   │   └── Widget
│   │       │   │   │   └── Wysiwyg
│   │       │   │   │       └── Images
│   │       │   │   ├── Index
│   │       │   │   ├── Noroute
│   │       │   │   └── Page
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Helper
│   │       │   │   └── Wysiwyg
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Api
│   │       │   │   │   └── SearchCriteria
│   │       │   │   │       └── CollectionProcessor
│   │       │   │   │           └── FilterProcessor
│   │       │   │   ├── Block
│   │       │   │   │   └── Source
│   │       │   │   ├── Config
│   │       │   │   │   └── Source
│   │       │   │   │       └── Wysiwyg
│   │       │   │   ├── Page
│   │       │   │   │   └── Source
│   │       │   │   ├── ResourceModel
│   │       │   │   │   ├── Block
│   │       │   │   │   │   ├── Grid
│   │       │   │   │   │   └── Relation
│   │       │   │   │   │       └── Store
│   │       │   │   │   └── Page
│   │       │   │   │       ├── Grid
│   │       │   │   │       └── Relation
│   │       │   │   │           └── Store
│   │       │   │   ├── Template
│   │       │   │   └── Wysiwyg
│   │       │   │       ├── Gallery
│   │       │   │       └── Images
│   │       │   │           └── Storage
│   │       │   ├── Observer
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Metadata
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   ├── Block
│   │       │   │       │   │   │   └── Widget
│   │       │   │       │   │   └── Page
│   │       │   │       │   │       └── Widget
│   │       │   │       │   └── Widget
│   │       │   │       │       └── Page
│   │       │   │       ├── Controller
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   ├── Block
│   │       │   │       │   │   ├── Page
│   │       │   │       │   │   └── Wysiwyg
│   │       │   │       │   ├── Block
│   │       │   │       │   ├── Index
│   │       │   │       │   ├── Noroute
│   │       │   │       │   └── Page
│   │       │   │       ├── Helper
│   │       │   │       │   └── Wysiwyg
│   │       │   │       ├── Model
│   │       │   │       │   ├── Api
│   │       │   │       │   │   └── SearchCriteria
│   │       │   │       │   │       └── CollectionProcessor
│   │       │   │       │   │           └── FilterProcessor
│   │       │   │       │   ├── Block
│   │       │   │       │   │   └── Source
│   │       │   │       │   ├── Config
│   │       │   │       │   │   └── Source
│   │       │   │       │   ├── Page
│   │       │   │       │   │   └── Source
│   │       │   │       │   ├── ResourceModel
│   │       │   │       │   │   ├── Block
│   │       │   │       │   │   │   └── Relation
│   │       │   │       │   │   │       └── Store
│   │       │   │       │   │   └── Page
│   │       │   │       │   │       ├── Grid
│   │       │   │       │   │       └── Relation
│   │       │   │       │   │           └── Store
│   │       │   │       │   ├── Template
│   │       │   │       │   └── Wysiwyg
│   │       │   │       │       └── Images
│   │       │   │       ├── Observer
│   │       │   │       └── Ui
│   │       │   │           └── Component
│   │       │   │               └── Listing
│   │       │   │                   └── Column
│   │       │   │                       └── Cms
│   │       │   ├── Ui
│   │       │   │   └── Component
│   │       │   │       ├── Listing
│   │       │   │       │   └── Column
│   │       │   │       │       └── Cms
│   │       │   │       └── Page
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   │   ├── browser
│   │       │       │   │   │   └── content
│   │       │       │   │   └── page
│   │       │       │   │       └── edit
│   │       │       │   │           └── form
│   │       │       │   │               └── renderer
│   │       │       │   ├── ui_component
│   │       │       │   └── web
│   │       │       │       ├── css
│   │       │       │       │   └── source
│   │       │       │       ├── images
│   │       │       │       └── js
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           └── templates
│   │       │               ├── default
│   │       │               └── widget
│   │       │                   ├── link
│   │       │                   └── static_block
│   │       ├── CmsGraphQl
│   │       │   ├── etc
│   │       │   │   └── graphql
│   │       │   └── Model
│   │       │       └── Resolver
│   │       │           ├── Block
│   │       │           ├── DataProvider
│   │       │           └── Page
│   │       ├── CmsUrlRewrite
│   │       │   ├── etc
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   ├── Observer
│   │       │   ├── Plugin
│   │       │   │   └── Cms
│   │       │   │       └── Model
│   │       │   │           └── ResourceModel
│   │       │   └── Test
│   │       │       ├── Mftf
│   │       │       └── Unit
│   │       │           ├── Model
│   │       │           ├── Observer
│   │       │           └── Plugin
│   │       │               └── Cms
│   │       │                   └── Model
│   │       │                       └── ResourceModel
│   │       ├── CmsUrlRewriteGraphQl
│   │       │   ├── etc
│   │       │   ├── Model
│   │       │   │   └── Resolver
│   │       │   │       └── UrlRewrite
│   │       │   └── Test
│   │       │       └── Mftf
│   │       ├── Config
│   │       │   ├── App
│   │       │   │   └── Config
│   │       │   │       ├── Source
│   │       │   │       └── Type
│   │       │   │           └── System
│   │       │   ├── Block
│   │       │   │   └── System
│   │       │   │       └── Config
│   │       │   │           └── Form
│   │       │   │               ├── Field
│   │       │   │               │   ├── FieldArray
│   │       │   │               │   └── Select
│   │       │   │               └── Fieldset
│   │       │   │                   └── Modules
│   │       │   ├── Console
│   │       │   │   └── Command
│   │       │   │       ├── ConfigSet
│   │       │   │       └── ConfigShow
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       └── System
│   │       │   │           └── Config
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Config
│   │       │   │   │   ├── Backend
│   │       │   │   │   │   ├── Admin
│   │       │   │   │   │   │   └── Password
│   │       │   │   │   │   │       └── Link
│   │       │   │   │   │   ├── Currency
│   │       │   │   │   │   ├── Design
│   │       │   │   │   │   ├── Email
│   │       │   │   │   │   ├── File
│   │       │   │   │   │   │   └── RequestData
│   │       │   │   │   │   ├── Image
│   │       │   │   │   │   ├── Locale
│   │       │   │   │   │   ├── Log
│   │       │   │   │   │   └── Serialized
│   │       │   │   │   ├── BackendClone
│   │       │   │   │   ├── Compiler
│   │       │   │   │   ├── Export
│   │       │   │   │   ├── Importer
│   │       │   │   │   ├── Parser
│   │       │   │   │   ├── Processor
│   │       │   │   │   ├── Reader
│   │       │   │   │   │   └── Source
│   │       │   │   │   │       └── Deployed
│   │       │   │   │   ├── Source
│   │       │   │   │   │   ├── Admin
│   │       │   │   │   │   ├── Date
│   │       │   │   │   │   ├── Design
│   │       │   │   │   │   ├── Dev
│   │       │   │   │   │   ├── Email
│   │       │   │   │   │   ├── Image
│   │       │   │   │   │   ├── Locale
│   │       │   │   │   │   │   └── Currency
│   │       │   │   │   │   ├── Reports
│   │       │   │   │   │   ├── Web
│   │       │   │   │   │   └── Website
│   │       │   │   │   └── Structure
│   │       │   │   │       ├── Element
│   │       │   │   │       │   ├── Dependency
│   │       │   │   │       │   ├── Group
│   │       │   │   │       │   └── Iterator
│   │       │   │   │       ├── ElementVisibility
│   │       │   │   │       ├── Mapper
│   │       │   │   │       │   ├── Attribute
│   │       │   │   │       │   └── Helper
│   │       │   │   │       └── Search
│   │       │   │   ├── Placeholder
│   │       │   │   └── ResourceModel
│   │       │   │       └── Config
│   │       │   │           └── Data
│   │       │   ├── Observer
│   │       │   │   └── Config
│   │       │   │       └── Backend
│   │       │   │           └── Admin
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Metadata
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── App
│   │       │   │       │   └── Config
│   │       │   │       │       ├── Source
│   │       │   │       │       └── Type
│   │       │   │       │           └── System
│   │       │   │       ├── Block
│   │       │   │       │   └── System
│   │       │   │       │       └── Config
│   │       │   │       │           └── Form
│   │       │   │       │               ├── Field
│   │       │   │       │               │   ├── FieldArray
│   │       │   │       │               │   └── Select
│   │       │   │       │               └── Fieldset
│   │       │   │       │                   └── Modules
│   │       │   │       ├── Console
│   │       │   │       │   └── Command
│   │       │   │       │       ├── ConfigSet
│   │       │   │       │       └── ConfigShow
│   │       │   │       ├── Controller
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       └── System
│   │       │   │       │           └── Config
│   │       │   │       │               └── _files
│   │       │   │       └── Model
│   │       │   │           ├── Compiler
│   │       │   │           ├── Config
│   │       │   │           │   ├── Backend
│   │       │   │           │   │   ├── Email
│   │       │   │           │   │   ├── File
│   │       │   │           │   │   └── Image
│   │       │   │           │   ├── Export
│   │       │   │           │   ├── _files
│   │       │   │           │   ├── Importer
│   │       │   │           │   ├── Parser
│   │       │   │           │   ├── Processor
│   │       │   │           │   ├── Reader
│   │       │   │           │   │   └── Source
│   │       │   │           │   │       └── Deployed
│   │       │   │           │   ├── Source
│   │       │   │           │   │   ├── Admin
│   │       │   │           │   │   ├── Email
│   │       │   │           │   │   └── Locale
│   │       │   │           │   └── Structure
│   │       │   │           │       ├── Element
│   │       │   │           │       │   ├── Dependency
│   │       │   │           │       │   ├── Group
│   │       │   │           │       │   └── Iterator
│   │       │   │           │       ├── ElementVisibility
│   │       │   │           │       └── Mapper
│   │       │   │           │           └── Helper
│   │       │   │           ├── _files
│   │       │   │           └── Placeholder
│   │       │   └── view
│   │       │       └── adminhtml
│   │       │           ├── layout
│   │       │           └── templates
│   │       │               ├── page
│   │       │               │   └── system
│   │       │               │       └── config
│   │       │               │           └── robots
│   │       │               └── system
│   │       │                   └── config
│   │       │                       └── form
│   │       │                           └── field
│   │       ├── ConfigurableImportExport
│   │       │   ├── etc
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Export
│   │       │   │   │   └── Product
│   │       │   │   │       └── Type
│   │       │   │   └── Import
│   │       │   │       └── Product
│   │       │   │           └── Type
│   │       │   └── Test
│   │       │       ├── Mftf
│   │       │       └── Unit
│   │       │           └── Model
│   │       │               ├── Export
│   │       │               └── Import
│   │       │                   └── Product
│   │       │                       └── Type
│   │       ├── ConfigurableProduct
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   ├── Block
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Order
│   │       │   │   │   │   └── Create
│   │       │   │   │   └── Product
│   │       │   │   │       ├── Attribute
│   │       │   │   │       │   ├── Edit
│   │       │   │   │       │   │   └── Tab
│   │       │   │   │       │   │       └── Variations
│   │       │   │   │       │   └── NewAttribute
│   │       │   │   │       │       └── Product
│   │       │   │   │       ├── Composite
│   │       │   │   │       │   └── Fieldset
│   │       │   │   │       ├── Edit
│   │       │   │   │       │   ├── AttributeSet
│   │       │   │   │       │   ├── Button
│   │       │   │   │       │   └── Tab
│   │       │   │   │       │       └── Variations
│   │       │   │   │       │           └── Config
│   │       │   │   │       └── Steps
│   │       │   │   ├── Cart
│   │       │   │   │   └── Item
│   │       │   │   │       └── Renderer
│   │       │   │   ├── Plugin
│   │       │   │   │   └── Product
│   │       │   │   │       └── Media
│   │       │   │   ├── Product
│   │       │   │   │   ├── Configurable
│   │       │   │   │   │   └── AssociatedSelector
│   │       │   │   │   │       └── Renderer
│   │       │   │   │   └── View
│   │       │   │   │       └── Type
│   │       │   │   └── Stockqty
│   │       │   │       └── Type
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       └── Product
│   │       │   │           ├── Associated
│   │       │   │           ├── Attribute
│   │       │   │           ├── Builder
│   │       │   │           └── Initialization
│   │       │   │               └── Helper
│   │       │   │                   └── Plugin
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Helper
│   │       │   │   └── Product
│   │       │   │       ├── Configuration
│   │       │   │       └── Options
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Attribute
│   │       │   │   ├── Entity
│   │       │   │   │   └── Product
│   │       │   │   │       └── Attribute
│   │       │   │   │           └── Group
│   │       │   │   │               └── AttributeMapper
│   │       │   │   ├── Order
│   │       │   │   │   └── Admin
│   │       │   │   │       └── Item
│   │       │   │   │           └── Plugin
│   │       │   │   ├── Plugin
│   │       │   │   │   └── Frontend
│   │       │   │   ├── Product
│   │       │   │   │   ├── CartConfiguration
│   │       │   │   │   │   └── Plugin
│   │       │   │   │   ├── Configuration
│   │       │   │   │   │   └── Item
│   │       │   │   │   ├── Type
│   │       │   │   │   │   ├── Collection
│   │       │   │   │   │   └── Configurable
│   │       │   │   │   │       └── Variations
│   │       │   │   │   ├── TypeTransitionManager
│   │       │   │   │   │   └── Plugin
│   │       │   │   │   └── Validator
│   │       │   │   ├── Quote
│   │       │   │   │   └── Item
│   │       │   │   │       └── QuantityValidator
│   │       │   │   │           └── Initializer
│   │       │   │   │               └── Option
│   │       │   │   │                   └── Plugin
│   │       │   │   └── ResourceModel
│   │       │   │       ├── Attribute
│   │       │   │       ├── Indexer
│   │       │   │       │   └── Stock
│   │       │   │       ├── Product
│   │       │   │       │   ├── Indexer
│   │       │   │       │   │   └── Price
│   │       │   │       │   └── Type
│   │       │   │       │       └── Configurable
│   │       │   │       │           ├── Attribute
│   │       │   │       │           └── Product
│   │       │   │       └── Setup
│   │       │   ├── Observer
│   │       │   ├── Plugin
│   │       │   │   ├── Catalog
│   │       │   │   │   └── Model
│   │       │   │   │       └── Product
│   │       │   │   │           └── Pricing
│   │       │   │   │               └── Renderer
│   │       │   │   ├── Model
│   │       │   │   │   ├── Attribute
│   │       │   │   │   │   └── Backend
│   │       │   │   │   └── ResourceModel
│   │       │   │   │       └── Attribute
│   │       │   │   ├── SalesRule
│   │       │   │   │   └── Model
│   │       │   │   │       └── Rule
│   │       │   │   │           └── Condition
│   │       │   │   └── Tax
│   │       │   │       └── Model
│   │       │   │           └── Sales
│   │       │   │               └── Total
│   │       │   │                   └── Quote
│   │       │   ├── Pricing
│   │       │   │   ├── Price
│   │       │   │   └── Render
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Metadata
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   └── Product
│   │       │   │       │   │       ├── Edit
│   │       │   │       │   │       │   ├── Button
│   │       │   │       │   │       │   └── Tab
│   │       │   │       │   │       │       └── Variations
│   │       │   │       │   │       │           └── Config
│   │       │   │       │   │       └── Steps
│   │       │   │       │   ├── Cart
│   │       │   │       │   │   └── Item
│   │       │   │       │   │       └── Renderer
│   │       │   │       │   ├── Plugin
│   │       │   │       │   │   └── Product
│   │       │   │       │   │       └── Media
│   │       │   │       │   └── Product
│   │       │   │       │       ├── Configurable
│   │       │   │       │       └── View
│   │       │   │       │           └── Type
│   │       │   │       ├── Controller
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       └── Product
│   │       │   │       │           ├── Attribute
│   │       │   │       │           ├── Builder
│   │       │   │       │           └── Initialization
│   │       │   │       │               └── Helper
│   │       │   │       │                   └── Plugin
│   │       │   │       ├── Helper
│   │       │   │       │   └── Product
│   │       │   │       │       ├── Configuration
│   │       │   │       │       └── Options
│   │       │   │       ├── Model
│   │       │   │       │   ├── Attribute
│   │       │   │       │   ├── Entity
│   │       │   │       │   │   └── Product
│   │       │   │       │   │       └── Attribute
│   │       │   │       │   │           └── Group
│   │       │   │       │   │               └── AttributeMapper
│   │       │   │       │   ├── Order
│   │       │   │       │   │   └── Admin
│   │       │   │       │   │       └── Item
│   │       │   │       │   │           └── Plugin
│   │       │   │       │   ├── Plugin
│   │       │   │       │   │   └── Frontend
│   │       │   │       │   ├── Product
│   │       │   │       │   │   ├── CartConfiguration
│   │       │   │       │   │   │   └── Plugin
│   │       │   │       │   │   ├── Configuration
│   │       │   │       │   │   │   └── Item
│   │       │   │       │   │   ├── Type
│   │       │   │       │   │   │   ├── Collection
│   │       │   │       │   │   │   └── Configurable
│   │       │   │       │   │   │       └── Variations
│   │       │   │       │   │   ├── TypeTransitionManager
│   │       │   │       │   │   │   └── Plugin
│   │       │   │       │   │   └── Validator
│   │       │   │       │   ├── Quote
│   │       │   │       │   │   └── Item
│   │       │   │       │   │       └── QuantityValidator
│   │       │   │       │   │           └── Initializer
│   │       │   │       │   │               └── Option
│   │       │   │       │   │                   └── Plugin
│   │       │   │       │   └── ResourceModel
│   │       │   │       │       ├── Attribute
│   │       │   │       │       └── Product
│   │       │   │       │           └── Type
│   │       │   │       │               └── Configurable
│   │       │   │       ├── Observer
│   │       │   │       ├── Plugin
│   │       │   │       │   ├── Catalog
│   │       │   │       │   │   └── Model
│   │       │   │       │   │       └── Product
│   │       │   │       │   │           └── Pricing
│   │       │   │       │   │               └── Renderer
│   │       │   │       │   ├── Model
│   │       │   │       │   │   └── ResourceModel
│   │       │   │       │   │       └── Attribute
│   │       │   │       │   ├── SalesRule
│   │       │   │       │   │   └── Model
│   │       │   │       │   │       └── Rule
│   │       │   │       │   │           └── Condition
│   │       │   │       │   └── Tax
│   │       │   │       │       └── Model
│   │       │   │       │           └── Sales
│   │       │   │       │               └── Total
│   │       │   │       │                   └── Quote
│   │       │   │       ├── Pricing
│   │       │   │       │   ├── Price
│   │       │   │       │   └── Render
│   │       │   │       └── Ui
│   │       │   │           ├── Component
│   │       │   │           │   └── Listing
│   │       │   │           │       └── AssociatedProduct
│   │       │   │           │           └── Columns
│   │       │   │           └── DataProvider
│   │       │   │               └── Product
│   │       │   │                   └── Form
│   │       │   │                       └── Modifier
│   │       │   ├── Ui
│   │       │   │   ├── Component
│   │       │   │   │   └── Listing
│   │       │   │   │       └── AssociatedProduct
│   │       │   │   │           ├── Attribute
│   │       │   │   │           └── Columns
│   │       │   │   └── DataProvider
│   │       │   │       └── Product
│   │       │   │           └── Form
│   │       │   │               └── Modifier
│   │       │   │                   └── Data
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   │   ├── catalog
│   │       │       │   │   │   └── product
│   │       │       │   │   │       ├── attribute
│   │       │       │   │   │       │   ├── new
│   │       │       │   │   │       │   └── set
│   │       │       │   │   │       ├── composite
│   │       │       │   │   │       │   └── fieldset
│   │       │       │   │   │       └── edit
│   │       │       │   │   │           ├── attribute
│   │       │       │   │   │           │   └── steps
│   │       │       │   │   │           └── super
│   │       │       │   │   └── product
│   │       │       │   │       └── configurable
│   │       │       │   │           ├── affected-attribute-set-selector
│   │       │       │   │           ├── attribute-selector
│   │       │       │   │           └── stock
│   │       │       │   ├── ui_component
│   │       │       │   └── web
│   │       │       │       ├── css
│   │       │       │       ├── js
│   │       │       │       │   ├── components
│   │       │       │       │   ├── options
│   │       │       │       │   └── variations
│   │       │       │       │       ├── paging
│   │       │       │       │       └── steps
│   │       │       │       ├── product
│   │       │       │       └── template
│   │       │       │           ├── components
│   │       │       │           └── variations
│   │       │       │               └── steps
│   │       │       ├── base
│   │       │       │   ├── layout
│   │       │       │   └── templates
│   │       │       │       └── product
│   │       │       │           └── price
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   ├── js
│   │       │           │   └── product
│   │       │           │       └── view
│   │       │           │           └── type
│   │       │           │               └── options
│   │       │           ├── ui_component
│   │       │           └── web
│   │       │               ├── js
│   │       │               └── template
│   │       │                   └── product
│   │       ├── ConfigurableProductGraphQl
│   │       │   ├── etc
│   │       │   │   └── graphql
│   │       │   ├── Model
│   │       │   │   ├── Options
│   │       │   │   ├── Resolver
│   │       │   │   │   └── Variant
│   │       │   │   └── Variant
│   │       │   └── Test
│   │       │       └── Mftf
│   │       ├── ConfigurableProductSales
│   │       │   ├── etc
│   │       │   ├── Model
│   │       │   │   └── Order
│   │       │   │       └── Reorder
│   │       │   └── Test
│   │       │       └── Mftf
│   │       ├── Contact
│   │       │   ├── Block
│   │       │   ├── Controller
│   │       │   │   └── Index
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   └── System
│   │       │   │       └── Config
│   │       │   │           └── Backend
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Page
│   │       │   │   │   └── Section
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       ├── Controller
│   │       │   │       │   ├── Index
│   │       │   │       │   └── Stub
│   │       │   │       ├── Helper
│   │       │   │       └── Model
│   │       │   │           └── System
│   │       │   │               └── Config
│   │       │   │                   └── Backend
│   │       │   └── view
│   │       │       └── frontend
│   │       │           ├── email
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           └── web
│   │       │               └── css
│   │       │                   └── source
│   │       ├── Cookie
│   │       │   ├── Block
│   │       │   │   └── Html
│   │       │   ├── Controller
│   │       │   │   └── Index
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   └── Config
│   │       │   │       └── Backend
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       ├── Controller
│   │       │   │       │   └── Index
│   │       │   │       ├── Helper
│   │       │   │       └── Model
│   │       │   │           └── Config
│   │       │   │               └── Backend
│   │       │   └── view
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   └── html
│   │       │           └── web
│   │       │               └── js
│   │       ├── Cron
│   │       │   ├── Console
│   │       │   │   └── Command
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── crontab
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Backend
│   │       │   │   │   └── Config
│   │       │   │   │       └── Structure
│   │       │   │   ├── Config
│   │       │   │   │   ├── Backend
│   │       │   │   │   │   └── Product
│   │       │   │   │   ├── Converter
│   │       │   │   │   ├── Reader
│   │       │   │   │   └── Source
│   │       │   │   ├── Groups
│   │       │   │   │   └── Config
│   │       │   │   │       ├── Converter
│   │       │   │   │       └── Reader
│   │       │   │   ├── ResourceModel
│   │       │   │   │   └── Schedule
│   │       │   │   └── System
│   │       │   │       └── Config
│   │       │   │           └── Initial
│   │       │   ├── Observer
│   │       │   ├── Setup
│   │       │   └── Test
│   │       │       ├── Mftf
│   │       │       └── Unit
│   │       │           ├── Console
│   │       │           │   └── Command
│   │       │           ├── Model
│   │       │           │   ├── Config
│   │       │           │   │   ├── Converter
│   │       │           │   │   ├── _files
│   │       │           │   │   └── Reader
│   │       │           │   ├── Groups
│   │       │           │   │   └── Config
│   │       │           │   │       └── Converter
│   │       │           │   └── System
│   │       │           │       └── Config
│   │       │           │           └── Initial
│   │       │           └── Observer
│   │       ├── CurrencySymbol
│   │       │   ├── Block
│   │       │   │   └── Adminhtml
│   │       │   │       └── System
│   │       │   │           └── Currency
│   │       │   │               └── Rate
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       └── System
│   │       │   │           ├── Currency
│   │       │   │           └── Currencysymbol
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   └── System
│   │       │   ├── Observer
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       └── System
│   │       │   │       │           └── Currency
│   │       │   │       │               └── Rate
│   │       │   │       ├── Controller
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       └── System
│   │       │   │       │           └── Currencysymbol
│   │       │   │       ├── Model
│   │       │   │       │   └── System
│   │       │   │       └── Observer
│   │       │   └── view
│   │       │       └── adminhtml
│   │       │           ├── layout
│   │       │           └── templates
│   │       │               └── system
│   │       │                   └── currency
│   │       │                       └── rate
│   │       ├── Customer
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   ├── Block
│   │       │   │   ├── Account
│   │       │   │   │   └── Dashboard
│   │       │   │   ├── Address
│   │       │   │   │   └── Renderer
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Edit
│   │       │   │   │   │   ├── Address
│   │       │   │   │   │   ├── Renderer
│   │       │   │   │   │   └── Tab
│   │       │   │   │   │       ├── Newsletter
│   │       │   │   │   │       │   └── Grid
│   │       │   │   │   │       │       ├── Filter
│   │       │   │   │   │       │       └── Renderer
│   │       │   │   │   │       ├── View
│   │       │   │   │   │       │   └── Grid
│   │       │   │   │   │       │       └── Renderer
│   │       │   │   │   │       └── Wishlist
│   │       │   │   │   │           └── Grid
│   │       │   │   │   │               └── Renderer
│   │       │   │   │   ├── Form
│   │       │   │   │   │   └── Element
│   │       │   │   │   ├── Grid
│   │       │   │   │   │   ├── Filter
│   │       │   │   │   │   └── Renderer
│   │       │   │   │   ├── Group
│   │       │   │   │   │   └── Edit
│   │       │   │   │   ├── Sales
│   │       │   │   │   │   └── Order
│   │       │   │   │   │       └── Address
│   │       │   │   │   │           └── Form
│   │       │   │   │   │               └── Renderer
│   │       │   │   │   └── System
│   │       │   │   │       └── Config
│   │       │   │   ├── DataProviders
│   │       │   │   ├── Form
│   │       │   │   │   └── Login
│   │       │   │   └── Widget
│   │       │   ├── Console
│   │       │   │   └── Command
│   │       │   ├── Controller
│   │       │   │   ├── Account
│   │       │   │   ├── Address
│   │       │   │   │   └── File
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Address
│   │       │   │   │   ├── Cart
│   │       │   │   │   │   └── Product
│   │       │   │   │   │       └── Composite
│   │       │   │   │   │           └── Cart
│   │       │   │   │   ├── Customer
│   │       │   │   │   ├── File
│   │       │   │   │   │   ├── Address
│   │       │   │   │   │   └── Customer
│   │       │   │   │   ├── Group
│   │       │   │   │   ├── Index
│   │       │   │   │   ├── Locks
│   │       │   │   │   ├── Online
│   │       │   │   │   ├── System
│   │       │   │   │   │   └── Config
│   │       │   │   │   │       └── Validatevat
│   │       │   │   │   └── Wishlist
│   │       │   │   │       └── Product
│   │       │   │   │           └── Composite
│   │       │   │   │               └── Wishlist
│   │       │   │   ├── Ajax
│   │       │   │   ├── Plugin
│   │       │   │   ├── Review
│   │       │   │   └── Section
│   │       │   ├── CustomerData
│   │       │   │   ├── Plugin
│   │       │   │   └── Section
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   ├── frontend
│   │       │   │   ├── graphql
│   │       │   │   ├── webapi_rest
│   │       │   │   └── webapi_soap
│   │       │   ├── Helper
│   │       │   │   └── Session
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Account
│   │       │   │   ├── Address
│   │       │   │   │   ├── Config
│   │       │   │   │   └── Validator
│   │       │   │   ├── App
│   │       │   │   │   └── Action
│   │       │   │   ├── Attribute
│   │       │   │   │   ├── Backend
│   │       │   │   │   │   └── Data
│   │       │   │   │   └── Data
│   │       │   │   ├── Authorization
│   │       │   │   ├── Backend
│   │       │   │   ├── Cache
│   │       │   │   │   └── Type
│   │       │   │   ├── Cart
│   │       │   │   ├── Checkout
│   │       │   │   ├── Config
│   │       │   │   │   ├── Backend
│   │       │   │   │   │   ├── Address
│   │       │   │   │   │   ├── CreateAccount
│   │       │   │   │   │   ├── Password
│   │       │   │   │   │   │   └── Link
│   │       │   │   │   │   └── Show
│   │       │   │   │   └── Source
│   │       │   │   │       ├── Address
│   │       │   │   │       └── Group
│   │       │   │   ├── Customer
│   │       │   │   │   ├── Attribute
│   │       │   │   │   │   ├── Backend
│   │       │   │   │   │   └── Source
│   │       │   │   │   └── Source
│   │       │   │   ├── Data
│   │       │   │   ├── Delegation
│   │       │   │   │   └── Data
│   │       │   │   ├── Group
│   │       │   │   ├── Indexer
│   │       │   │   │   ├── Address
│   │       │   │   │   └── Attribute
│   │       │   │   ├── Layout
│   │       │   │   ├── Metadata
│   │       │   │   │   └── Form
│   │       │   │   ├── Observer
│   │       │   │   ├── Plugin
│   │       │   │   │   └── CustomerRepository
│   │       │   │   ├── Renderer
│   │       │   │   ├── ResourceModel
│   │       │   │   │   ├── Address
│   │       │   │   │   │   ├── Attribute
│   │       │   │   │   │   │   ├── Backend
│   │       │   │   │   │   │   └── Source
│   │       │   │   │   │   └── Grid
│   │       │   │   │   ├── Attribute
│   │       │   │   │   ├── Customer
│   │       │   │   │   │   └── Indexer
│   │       │   │   │   ├── Db
│   │       │   │   │   │   └── VersionControl
│   │       │   │   │   ├── Form
│   │       │   │   │   │   └── Attribute
│   │       │   │   │   ├── Grid
│   │       │   │   │   ├── Group
│   │       │   │   │   │   └── Grid
│   │       │   │   │   ├── Online
│   │       │   │   │   │   └── Grid
│   │       │   │   │   ├── Setup
│   │       │   │   │   └── Visitor
│   │       │   │   └── Session
│   │       │   ├── Observer
│   │       │   │   └── Visitor
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Metadata
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   ├── Account
│   │       │   │       │   │   └── Dashboard
│   │       │   │       │   ├── Address
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   ├── Edit
│   │       │   │       │   │   │   ├── Address
│   │       │   │       │   │   │   └── Tab
│   │       │   │       │   │   │       └── View
│   │       │   │       │   │   │           └── Grid
│   │       │   │       │   │   │               └── Renderer
│   │       │   │       │   │   └── From
│   │       │   │       │   │       └── Element
│   │       │   │       │   ├── Form
│   │       │   │       │   │   └── Login
│   │       │   │       │   └── Widget
│   │       │   │       ├── Console
│   │       │   │       │   └── Command
│   │       │   │       ├── Controller
│   │       │   │       │   ├── Account
│   │       │   │       │   ├── Address
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   ├── File
│   │       │   │       │   │   │   ├── Address
│   │       │   │       │   │   │   └── Customer
│   │       │   │       │   │   ├── Group
│   │       │   │       │   │   ├── Index
│   │       │   │       │   │   ├── Locks
│   │       │   │       │   │   └── System
│   │       │   │       │   │       └── Config
│   │       │   │       │   │           └── Validatevat
│   │       │   │       │   ├── Ajax
│   │       │   │       │   ├── Plugin
│   │       │   │       │   └── Section
│   │       │   │       ├── CustomerData
│   │       │   │       │   ├── _files
│   │       │   │       │   ├── Plugin
│   │       │   │       │   └── Section
│   │       │   │       ├── Helper
│   │       │   │       │   └── Session
│   │       │   │       ├── Model
│   │       │   │       │   ├── Account
│   │       │   │       │   ├── Address
│   │       │   │       │   │   ├── Config
│   │       │   │       │   │   │   └── _files
│   │       │   │       │   │   └── Validator
│   │       │   │       │   ├── App
│   │       │   │       │   │   └── Action
│   │       │   │       │   ├── Attribute
│   │       │   │       │   │   ├── Backend
│   │       │   │       │   │   └── Data
│   │       │   │       │   ├── Authorization
│   │       │   │       │   ├── Backend
│   │       │   │       │   ├── Checkout
│   │       │   │       │   ├── Config
│   │       │   │       │   │   ├── Backend
│   │       │   │       │   │   │   └── CreateAccount
│   │       │   │       │   │   └── Source
│   │       │   │       │   │       ├── Address
│   │       │   │       │   │       └── Group
│   │       │   │       │   ├── Customer
│   │       │   │       │   │   ├── Attribute
│   │       │   │       │   │   │   ├── Backend
│   │       │   │       │   │   │   └── Source
│   │       │   │       │   │   └── Source
│   │       │   │       │   ├── Indexer
│   │       │   │       │   │   └── Attribute
│   │       │   │       │   ├── Layout
│   │       │   │       │   ├── Metadata
│   │       │   │       │   │   └── Form
│   │       │   │       │   │       └── _files
│   │       │   │       │   ├── Plugin
│   │       │   │       │   │   └── CustomerRepository
│   │       │   │       │   ├── Renderer
│   │       │   │       │   └── ResourceModel
│   │       │   │       │       ├── Address
│   │       │   │       │       │   └── Attribute
│   │       │   │       │       │       ├── Backend
│   │       │   │       │       │       └── Source
│   │       │   │       │       ├── Customer
│   │       │   │       │       ├── Db
│   │       │   │       │       │   └── VersionControl
│   │       │   │       │       └── Group
│   │       │   │       │           └── Grid
│   │       │   │       ├── Observer
│   │       │   │       └── Ui
│   │       │   │           └── Component
│   │       │   │               ├── DataProvider
│   │       │   │               ├── Form
│   │       │   │               └── Listing
│   │       │   │                   └── Column
│   │       │   ├── Ui
│   │       │   │   └── Component
│   │       │   │       ├── DataProvider
│   │       │   │       ├── Form
│   │       │   │       ├── Listing
│   │       │   │       │   ├── Address
│   │       │   │       │   │   └── Column
│   │       │   │       │   └── Column
│   │       │   │       │       ├── Group
│   │       │   │       │       └── Online
│   │       │   │       │           └── Type
│   │       │   │       └── MassAction
│   │       │   │           └── Group
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   │   ├── edit
│   │       │       │   │   ├── sales
│   │       │       │   │   │   └── order
│   │       │       │   │   │       └── create
│   │       │       │   │   │           └── address
│   │       │       │   │   │               └── form
│   │       │       │   │   │                   └── renderer
│   │       │       │   │   ├── system
│   │       │       │   │   │   └── config
│   │       │       │   │   └── tab
│   │       │       │   │       └── view
│   │       │       │   ├── ui_component
│   │       │       │   └── web
│   │       │       │       ├── edit
│   │       │       │       │   └── tab
│   │       │       │       │       └── js
│   │       │       │       ├── js
│   │       │       │       │   ├── address
│   │       │       │       │   ├── bootstrap
│   │       │       │       │   ├── form
│   │       │       │       │   │   ├── components
│   │       │       │       │   │   └── element
│   │       │       │       │   └── grid
│   │       │       │       │       ├── columns
│   │       │       │       │       └── filters
│   │       │       │       └── template
│   │       │       ├── base
│   │       │       │   └── ui_component
│   │       │       └── frontend
│   │       │           ├── email
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   ├── account
│   │       │           │   │   ├── dashboard
│   │       │           │   │   └── link
│   │       │           │   ├── address
│   │       │           │   ├── form
│   │       │           │   ├── js
│   │       │           │   │   └── customer-data
│   │       │           │   └── widget
│   │       │           └── web
│   │       │               ├── js
│   │       │               │   ├── action
│   │       │               │   ├── invalidation-rules
│   │       │               │   ├── model
│   │       │               │   │   └── customer
│   │       │               │   └── view
│   │       │               └── template
│   │       ├── CustomerAnalytics
│   │       │   ├── etc
│   │       │   └── Test
│   │       │       └── Mftf
│   │       ├── CustomerGraphQl
│   │       │   ├── etc
│   │       │   │   └── graphql
│   │       │   └── Model
│   │       │       ├── Customer
│   │       │       │   └── Address
│   │       │       └── Resolver
│   │       ├── CustomerImportExport
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       └── Index
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Export
│   │       │   │   ├── Import
│   │       │   │   └── ResourceModel
│   │       │   │       └── Import
│   │       │   │           ├── Address
│   │       │   │           ├── Customer
│   │       │   │           └── CustomerComposite
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       └── Model
│   │       │   │           ├── Export
│   │       │   │           ├── Import
│   │       │   │           │   └── _files
│   │       │   │           └── ResourceModel
│   │       │   │               └── Import
│   │       │   │                   ├── Customer
│   │       │   │                   └── CustomerComposite
│   │       │   └── view
│   │       │       └── adminhtml
│   │       │           └── layout
│   │       ├── Deploy
│   │       │   ├── App
│   │       │   │   └── Mode
│   │       │   ├── Collector
│   │       │   ├── Config
│   │       │   ├── Console
│   │       │   │   └── Command
│   │       │   │       └── App
│   │       │   │           ├── ConfigImport
│   │       │   │           └── SensitiveConfigSet
│   │       │   ├── etc
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── DeploymentConfig
│   │       │   │   │   └── Hash
│   │       │   │   └── Plugin
│   │       │   ├── Package
│   │       │   │   ├── Bundle
│   │       │   │   └── Processor
│   │       │   │       ├── PostProcessor
│   │       │   │       └── PreProcessor
│   │       │   ├── Process
│   │       │   ├── Service
│   │       │   ├── Source
│   │       │   ├── Strategy
│   │       │   └── Test
│   │       │       ├── Mftf
│   │       │       └── Unit
│   │       │           ├── App
│   │       │           │   └── Mode
│   │       │           ├── Console
│   │       │           │   └── Command
│   │       │           │       └── App
│   │       │           │           ├── ConfigImport
│   │       │           │           └── SensitiveConfigSet
│   │       │           ├── Model
│   │       │           │   ├── DeploymentConfig
│   │       │           │   │   └── Hash
│   │       │           │   └── Plugin
│   │       │           ├── Process
│   │       │           ├── Service
│   │       │           └── Strategy
│   │       ├── Developer
│   │       │   ├── Block
│   │       │   │   └── Adminhtml
│   │       │   │       └── System
│   │       │   │           └── Config
│   │       │   ├── Console
│   │       │   │   └── Command
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Config
│   │       │   │   │   ├── Backend
│   │       │   │   │   └── Source
│   │       │   │   ├── Css
│   │       │   │   │   └── PreProcessor
│   │       │   │   │       └── FileGenerator
│   │       │   │   ├── Di
│   │       │   │   ├── Logger
│   │       │   │   │   └── Handler
│   │       │   │   ├── Setup
│   │       │   │   │   └── Declaration
│   │       │   │   │       └── Schema
│   │       │   │   ├── TemplateEngine
│   │       │   │   │   ├── Decorator
│   │       │   │   │   └── Plugin
│   │       │   │   ├── Tools
│   │       │   │   ├── View
│   │       │   │   │   ├── Asset
│   │       │   │   │   │   └── PreProcessor
│   │       │   │   │   └── Page
│   │       │   │   │       └── Config
│   │       │   │   │           └── ClientSideLessCompilation
│   │       │   │   └── XmlCatalog
│   │       │   │       └── Format
│   │       │   │           └── PhpStorm
│   │       │   └── Test
│   │       │       ├── Mftf
│   │       │       └── Unit
│   │       │           ├── Block
│   │       │           │   └── Adminhtml
│   │       │           │       └── System
│   │       │           │           └── Config
│   │       │           ├── Console
│   │       │           │   └── Command
│   │       │           │       └── _files
│   │       │           ├── Helper
│   │       │           └── Model
│   │       │               ├── Config
│   │       │               │   ├── Backend
│   │       │               │   └── Source
│   │       │               ├── Css
│   │       │               │   └── PreProcessor
│   │       │               │       └── FileGenerator
│   │       │               ├── Di
│   │       │               ├── Logger
│   │       │               │   └── Handler
│   │       │               ├── TemplateEngine
│   │       │               │   ├── Decorator
│   │       │               │   └── Plugin
│   │       │               └── View
│   │       │                   ├── Asset
│   │       │                   │   └── PreProcessor
│   │       │                   └── Page
│   │       │                       └── Config
│   │       │                           └── ClientSideLessCompilation
│   │       ├── Dhl
│   │       │   ├── Block
│   │       │   │   └── Adminhtml
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Plugin
│   │       │   │   │   └── Checkout
│   │       │   │   │       └── Block
│   │       │   │   │           └── Cart
│   │       │   │   ├── Source
│   │       │   │   │   └── Method
│   │       │   │   └── Validator
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       └── Model
│   │       │   │           ├── _files
│   │       │   │           └── Validator
│   │       │   │               └── _files
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── templates
│   │       │       │   └── web
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           └── web
│   │       │               └── js
│   │       │                   ├── model
│   │       │                   └── view
│   │       ├── Directory
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   ├── Block
│   │       │   │   └── Adminhtml
│   │       │   │       └── Frontend
│   │       │   │           ├── Currency
│   │       │   │           └── Region
│   │       │   ├── Controller
│   │       │   │   ├── Adminhtml
│   │       │   │   │   └── Json
│   │       │   │   └── Currency
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Config
│   │       │   │   │   └── Source
│   │       │   │   │       └── Country
│   │       │   │   ├── Country
│   │       │   │   │   └── Postcode
│   │       │   │   │       └── Config
│   │       │   │   ├── Currency
│   │       │   │   │   └── Import
│   │       │   │   │       └── Source
│   │       │   │   ├── Data
│   │       │   │   └── ResourceModel
│   │       │   │       ├── Country
│   │       │   │       │   └── Format
│   │       │   │       └── Region
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       ├── _files
│   │       │   │       ├── Helper
│   │       │   │       └── Model
│   │       │   │           ├── Config
│   │       │   │           │   └── Source
│   │       │   │           ├── Country
│   │       │   │           │   └── Postcode
│   │       │   │           │       └── Config
│   │       │   │           ├── Currency
│   │       │   │           │   └── Import
│   │       │   │           │       └── Source
│   │       │   │           └── ResourceModel
│   │       │   │               ├── Country
│   │       │   │               └── Region
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── email
│   │       │       │   └── templates
│   │       │       │       └── js
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           └── templates
│   │       │               └── currency
│   │       ├── DirectoryGraphQl
│   │       │   ├── Controller
│   │       │   │   ├── HttpHeaderProcessor
│   │       │   │   └── HttpRequestValidator
│   │       │   ├── etc
│   │       │   │   └── graphql
│   │       │   ├── Model
│   │       │   │   └── Resolver
│   │       │   └── Test
│   │       │       └── Mftf
│   │       ├── Downloadable
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   │       └── File
│   │       │   ├── Block
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Catalog
│   │       │   │   │   │   └── Product
│   │       │   │   │   │       ├── Composite
│   │       │   │   │   │       │   └── Fieldset
│   │       │   │   │   │       └── Edit
│   │       │   │   │   │           └── Tab
│   │       │   │   │   │               └── Downloadable
│   │       │   │   │   └── Sales
│   │       │   │   │       └── Items
│   │       │   │   │           └── Column
│   │       │   │   │               └── Downloadable
│   │       │   │   ├── Catalog
│   │       │   │   │   └── Product
│   │       │   │   │       └── View
│   │       │   │   ├── Checkout
│   │       │   │   │   └── Cart
│   │       │   │   │       └── Item
│   │       │   │   ├── Customer
│   │       │   │   │   └── Products
│   │       │   │   └── Sales
│   │       │   │       └── Order
│   │       │   │           ├── Email
│   │       │   │           │   └── Items
│   │       │   │           │       └── Order
│   │       │   │           └── Item
│   │       │   │               └── Renderer
│   │       │   ├── Controller
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Downloadable
│   │       │   │   │   │   ├── File
│   │       │   │   │   │   └── Product
│   │       │   │   │   │       └── Edit
│   │       │   │   │   └── Product
│   │       │   │   │       └── Initialization
│   │       │   │   │           └── Helper
│   │       │   │   │               └── Plugin
│   │       │   │   ├── Customer
│   │       │   │   └── Download
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   ├── frontend
│   │       │   │   ├── webapi_rest
│   │       │   │   └── webapi_soap
│   │       │   ├── Helper
│   │       │   │   └── Catalog
│   │       │   │       └── Product
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── File
│   │       │   │   ├── Link
│   │       │   │   │   └── Purchased
│   │       │   │   ├── Product
│   │       │   │   │   ├── CartConfiguration
│   │       │   │   │   │   └── Plugin
│   │       │   │   │   ├── CopyConstructor
│   │       │   │   │   ├── TypeHandler
│   │       │   │   │   └── TypeTransitionManager
│   │       │   │   │       └── Plugin
│   │       │   │   ├── Quote
│   │       │   │   │   └── Item
│   │       │   │   ├── ResourceModel
│   │       │   │   │   ├── Indexer
│   │       │   │   │   ├── Link
│   │       │   │   │   │   └── Purchased
│   │       │   │   │   │       └── Item
│   │       │   │   │   └── Sample
│   │       │   │   ├── Sales
│   │       │   │   │   └── Order
│   │       │   │   │       └── Pdf
│   │       │   │   │           └── Items
│   │       │   │   ├── Sample
│   │       │   │   ├── Source
│   │       │   │   └── System
│   │       │   │       └── Config
│   │       │   │           └── Source
│   │       │   ├── Observer
│   │       │   ├── Pricing
│   │       │   │   └── Price
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Metadata
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   ├── Catalog
│   │       │   │       │   │   │   └── Product
│   │       │   │       │   │   │       └── Edit
│   │       │   │       │   │   │           └── Tab
│   │       │   │       │   │   │               └── Downloadable
│   │       │   │       │   │   └── Sales
│   │       │   │       │   │       └── Items
│   │       │   │       │   │           └── Column
│   │       │   │       │   │               └── Downloadable
│   │       │   │       │   ├── Catalog
│   │       │   │       │   │   └── Product
│   │       │   │       │   └── Sales
│   │       │   │       │       └── Order
│   │       │   │       │           ├── Email
│   │       │   │       │           │   └── Items
│   │       │   │       │           │       └── Order
│   │       │   │       │           └── Item
│   │       │   │       │               └── Renderer
│   │       │   │       ├── Controller
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   ├── Downloadable
│   │       │   │       │   │   │   ├── File
│   │       │   │       │   │   │   └── Product
│   │       │   │       │   │   │       └── Edit
│   │       │   │       │   │   └── Product
│   │       │   │       │   │       └── Initialization
│   │       │   │       │   │           └── Helper
│   │       │   │       │   │               └── Plugin
│   │       │   │       │   └── Download
│   │       │   │       ├── _files
│   │       │   │       ├── Helper
│   │       │   │       │   └── Catalog
│   │       │   │       │       └── Product
│   │       │   │       ├── Model
│   │       │   │       │   ├── File
│   │       │   │       │   ├── Link
│   │       │   │       │   ├── Product
│   │       │   │       │   │   ├── CopyConstructor
│   │       │   │       │   │   │   └── _files
│   │       │   │       │   │   ├── TypeHandler
│   │       │   │       │   │   └── TypeTransitionManager
│   │       │   │       │   │       └── Plugin
│   │       │   │       │   ├── Quote
│   │       │   │       │   │   └── Item
│   │       │   │       │   ├── Sales
│   │       │   │       │   │   └── Order
│   │       │   │       │   │       └── Pdf
│   │       │   │       │   │           └── Items
│   │       │   │       │   └── Sample
│   │       │   │       ├── Observer
│   │       │   │       ├── Pricing
│   │       │   │       │   └── Price
│   │       │   │       └── Ui
│   │       │   │           └── DataProvider
│   │       │   │               └── Product
│   │       │   │                   └── Form
│   │       │   │                       └── Modifier
│   │       │   │                           └── Data
│   │       │   ├── Ui
│   │       │   │   └── DataProvider
│   │       │   │       └── Product
│   │       │   │           └── Form
│   │       │   │               └── Modifier
│   │       │   │                   └── Data
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   │   ├── product
│   │       │       │   │   │   ├── composite
│   │       │       │   │   │   │   └── fieldset
│   │       │       │   │   │   └── edit
│   │       │       │   │   │       └── downloadable
│   │       │       │   │   └── sales
│   │       │       │   │       └── items
│   │       │       │   │           └── column
│   │       │       │   │               └── downloadable
│   │       │       │   │                   ├── creditmemo
│   │       │       │   │                   └── invoice
│   │       │       │   └── web
│   │       │       │       ├── js
│   │       │       │       │   └── components
│   │       │       │       └── template
│   │       │       │           └── components
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   ├── catalog
│   │       │           │   │   └── product
│   │       │           │   ├── checkout
│   │       │           │   ├── customer
│   │       │           │   │   └── products
│   │       │           │   ├── email
│   │       │           │   │   └── order
│   │       │           │   │       └── items
│   │       │           │   │           ├── creditmemo
│   │       │           │   │           ├── invoice
│   │       │           │   │           └── order
│   │       │           │   ├── js
│   │       │           │   └── sales
│   │       │           │       └── order
│   │       │           │           ├── creditmemo
│   │       │           │           │   └── items
│   │       │           │           │       └── renderer
│   │       │           │           ├── invoice
│   │       │           │           │   └── items
│   │       │           │           │       └── renderer
│   │       │           │           └── items
│   │       │           │               └── renderer
│   │       │           └── web
│   │       │               └── js
│   │       ├── DownloadableGraphQl
│   │       │   ├── etc
│   │       │   │   └── graphql
│   │       │   ├── Model
│   │       │   │   ├── Resolver
│   │       │   │   │   └── Product
│   │       │   │   └── ResourceModel
│   │       │   └── Test
│   │       │       └── Mftf
│   │       ├── DownloadableImportExport
│   │       │   ├── etc
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   └── Import
│   │       │   │       └── Product
│   │       │   │           └── Type
│   │       │   └── Test
│   │       │       ├── Mftf
│   │       │       └── Unit
│   │       │           └── Model
│   │       │               └── Import
│   │       │                   └── Product
│   │       │                       └── Type
│   │       ├── Eav
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   ├── Block
│   │       │   │   └── Adminhtml
│   │       │   │       └── Attribute
│   │       │   │           ├── Edit
│   │       │   │           │   ├── Main
│   │       │   │           │   └── Options
│   │       │   │           └── Grid
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Attribute
│   │       │   │   │   │   └── Validation
│   │       │   │   │   │       └── Rules
│   │       │   │   │   └── System
│   │       │   │   │       └── Config
│   │       │   │   │           └── Source
│   │       │   │   │               └── Inputtype
│   │       │   │   ├── Api
│   │       │   │   │   └── SearchCriteria
│   │       │   │   │       └── CollectionProcessor
│   │       │   │   │           └── FilterProcessor
│   │       │   │   ├── Attribute
│   │       │   │   │   └── Data
│   │       │   │   ├── Cache
│   │       │   │   ├── Entity
│   │       │   │   │   ├── Attribute
│   │       │   │   │   │   ├── Backend
│   │       │   │   │   │   │   └── Time
│   │       │   │   │   │   ├── Config
│   │       │   │   │   │   ├── Frontend
│   │       │   │   │   │   └── Source
│   │       │   │   │   ├── Collection
│   │       │   │   │   │   └── VersionControl
│   │       │   │   │   ├── Increment
│   │       │   │   │   ├── Setup
│   │       │   │   │   │   └── PropertyMapper
│   │       │   │   │   └── VersionControl
│   │       │   │   ├── Form
│   │       │   │   ├── ResourceModel
│   │       │   │   │   ├── Attribute
│   │       │   │   │   │   └── DefaultEntityAttributes
│   │       │   │   │   ├── Entity
│   │       │   │   │   │   ├── Attribute
│   │       │   │   │   │   │   ├── Grid
│   │       │   │   │   │   │   ├── Group
│   │       │   │   │   │   │   ├── Option
│   │       │   │   │   │   │   └── Set
│   │       │   │   │   │   └── Type
│   │       │   │   │   └── Form
│   │       │   │   │       ├── Attribute
│   │       │   │   │       ├── Element
│   │       │   │   │       ├── Fieldset
│   │       │   │   │       └── Type
│   │       │   │   ├── TypeLocator
│   │       │   │   └── Validator
│   │       │   │       └── Attribute
│   │       │   ├── Plugin
│   │       │   │   └── Model
│   │       │   │       └── ResourceModel
│   │       │   │           └── Entity
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       └── Attribute
│   │       │   │       ├── _files
│   │       │   │       ├── Helper
│   │       │   │       ├── Model
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   ├── Attribute
│   │       │   │       │   │   │   └── Validation
│   │       │   │       │   │   │       └── Rules
│   │       │   │       │   │   └── System
│   │       │   │       │   │       └── Config
│   │       │   │       │   │           └── Source
│   │       │   │       │   │               └── Inputtype
│   │       │   │       │   ├── Api
│   │       │   │       │   │   └── SearchCriteria
│   │       │   │       │   │       └── CollectionProcessor
│   │       │   │       │   │           └── FilterProcessor
│   │       │   │       │   ├── Attribute
│   │       │   │       │   │   └── Data
│   │       │   │       │   │       └── _files
│   │       │   │       │   ├── Entity
│   │       │   │       │   │   ├── Attribute
│   │       │   │       │   │   │   ├── Backend
│   │       │   │       │   │   │   ├── Config
│   │       │   │       │   │   │   │   └── _files
│   │       │   │       │   │   │   ├── Frontend
│   │       │   │       │   │   │   └── Source
│   │       │   │       │   │   ├── Collection
│   │       │   │       │   │   │   └── VersionControl
│   │       │   │       │   │   ├── Increment
│   │       │   │       │   │   └── VersionControl
│   │       │   │       │   ├── ResourceModel
│   │       │   │       │   │   ├── Attribute
│   │       │   │       │   │   └── Entity
│   │       │   │       │   │       └── Attribute
│   │       │   │       │   │           └── Option
│   │       │   │       │   └── Validator
│   │       │   │       │       └── Attribute
│   │       │   │       └── Plugin
│   │       │   │           └── Model
│   │       │   │               └── ResourceModel
│   │       │   │                   └── Entity
│   │       │   └── view
│   │       │       └── adminhtml
│   │       │           ├── templates
│   │       │           │   └── attribute
│   │       │           │       └── edit
│   │       │           └── web
│   │       │               └── js
│   │       ├── EavGraphQl
│   │       │   ├── etc
│   │       │   ├── Model
│   │       │   │   └── Resolver
│   │       │   │       ├── DataProvider
│   │       │   │       └── Query
│   │       │   └── Test
│   │       │       └── Mftf
│   │       ├── Elasticsearch
│   │       │   ├── Block
│   │       │   │   └── Adminhtml
│   │       │   │       └── System
│   │       │   │           └── Config
│   │       │   │               └── Elasticsearch5
│   │       │   ├── Elasticsearch5
│   │       │   │   ├── Model
│   │       │   │   │   ├── Adapter
│   │       │   │   │   │   ├── BatchDataMapper
│   │       │   │   │   │   ├── DataMapper
│   │       │   │   │   │   └── FieldMapper
│   │       │   │   │   │       └── Product
│   │       │   │   │   │           └── FieldProvider
│   │       │   │   │   │               ├── FieldIndex
│   │       │   │   │   │               └── FieldType
│   │       │   │   │   │                   └── Resolver
│   │       │   │   │   └── Client
│   │       │   │   └── SearchAdapter
│   │       │   │       ├── Aggregation
│   │       │   │       └── Query
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── stopwords
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Adapter
│   │       │   │   │   ├── BatchDataMapper
│   │       │   │   │   ├── Container
│   │       │   │   │   ├── DataMapper
│   │       │   │   │   ├── Document
│   │       │   │   │   ├── FieldMapper
│   │       │   │   │   │   └── Product
│   │       │   │   │   │       ├── AttributeAdapter
│   │       │   │   │   │       └── FieldProvider
│   │       │   │   │   │           ├── FieldIndex
│   │       │   │   │   │           ├── FieldName
│   │       │   │   │   │           │   └── Resolver
│   │       │   │   │   │           └── FieldType
│   │       │   │   │   │               └── Resolver
│   │       │   │   │   ├── FieldType
│   │       │   │   │   └── Index
│   │       │   │   │       └── Config
│   │       │   │   ├── Advanced
│   │       │   │   ├── Client
│   │       │   │   ├── DataProvider
│   │       │   │   ├── Indexer
│   │       │   │   │   └── Plugin
│   │       │   │   ├── Layer
│   │       │   │   │   ├── Category
│   │       │   │   │   └── Search
│   │       │   │   └── ResourceModel
│   │       │   │       └── Fulltext
│   │       │   │           └── Collection
│   │       │   ├── Observer
│   │       │   ├── SearchAdapter
│   │       │   │   ├── Aggregation
│   │       │   │   │   └── Builder
│   │       │   │   ├── Dynamic
│   │       │   │   ├── Filter
│   │       │   │   │   └── Builder
│   │       │   │   └── Query
│   │       │   │       ├── Builder
│   │       │   │       ├── Preprocessor
│   │       │   │       └── ValueTransformer
│   │       │   └── Test
│   │       │       ├── Mftf
│   │       │       │   └── Test
│   │       │       └── Unit
│   │       │           ├── Elasticsearch5
│   │       │           │   ├── Model
│   │       │           │   │   ├── Adapter
│   │       │           │   │   │   └── FieldMapper
│   │       │           │   │   │       └── Product
│   │       │           │   │   │           └── FieldProvider
│   │       │           │   │   │               ├── FieldIndex
│   │       │           │   │   │               └── FieldType
│   │       │           │   │   │                   └── Resolver
│   │       │           │   │   └── Client
│   │       │           │   └── SearchAdapter
│   │       │           │       └── Aggregation
│   │       │           ├── Model
│   │       │           │   ├── Adapter
│   │       │           │   │   ├── BatchDataMapper
│   │       │           │   │   ├── Container
│   │       │           │   │   ├── DataMapper
│   │       │           │   │   ├── Document
│   │       │           │   │   ├── FieldMapper
│   │       │           │   │   │   └── Product
│   │       │           │   │   │       └── FieldProvider
│   │       │           │   │   │           ├── FieldIndex
│   │       │           │   │   │           ├── FieldName
│   │       │           │   │   │           │   └── Resolver
│   │       │           │   │   │           └── FieldType
│   │       │           │   │   │               └── Resolver
│   │       │           │   │   ├── FieldType
│   │       │           │   │   └── Index
│   │       │           │   │       └── Config
│   │       │           │   │           └── _files
│   │       │           │   ├── DataProvider
│   │       │           │   ├── Indexer
│   │       │           │   │   └── Plugin
│   │       │           │   └── ResourceModel
│   │       │           ├── Observer
│   │       │           └── SearchAdapter
│   │       │               ├── Aggregation
│   │       │               │   └── Builder
│   │       │               ├── Dynamic
│   │       │               ├── Filter
│   │       │               │   └── Builder
│   │       │               └── Query
│   │       │                   ├── Builder
│   │       │                   └── Preprocessor
│   │       ├── Elasticsearch6
│   │       │   ├── Block
│   │       │   │   └── Adminhtml
│   │       │   │       └── System
│   │       │   │           └── Config
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── Model
│   │       │   │   ├── Adapter
│   │       │   │   │   └── FieldMapper
│   │       │   │   │       └── Product
│   │       │   │   │           └── FieldProvider
│   │       │   │   │               └── FieldName
│   │       │   │   │                   └── Resolver
│   │       │   │   ├── Client
│   │       │   │   └── DataProvider
│   │       │   └── Test
│   │       │       └── Unit
│   │       │           └── Model
│   │       │               ├── Adapter
│   │       │               │   └── FieldMapper
│   │       │               │       └── Product
│   │       │               │           └── FieldProvider
│   │       │               │               └── FieldName
│   │       │               │                   └── Resolver
│   │       │               ├── Client
│   │       │               └── DataProvider
│   │       ├── Email
│   │       │   ├── Block
│   │       │   │   └── Adminhtml
│   │       │   │       └── Template
│   │       │   │           ├── Edit
│   │       │   │           └── Grid
│   │       │   │               ├── Filter
│   │       │   │               └── Renderer
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       └── Email
│   │       │   │           └── Template
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Design
│   │       │   │   │   └── Backend
│   │       │   │   ├── Mail
│   │       │   │   ├── Plugin
│   │       │   │   ├── ResourceModel
│   │       │   │   │   └── Template
│   │       │   │   └── Template
│   │       │   │       ├── Config
│   │       │   │       └── Css
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       └── Template
│   │       │   │       │           ├── Edit
│   │       │   │       │           └── Grid
│   │       │   │       │               └── Renderer
│   │       │   │       ├── Controller
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       └── Email
│   │       │   │       │           └── Template
│   │       │   │       └── Model
│   │       │   │           ├── Mail
│   │       │   │           ├── Plugin
│   │       │   │           └── Template
│   │       │   │               ├── Config
│   │       │   │               │   └── _files
│   │       │   │               │       └── Fixture
│   │       │   │               │           ├── ModuleOne
│   │       │   │               │           │   └── etc
│   │       │   │               │           └── ModuleTwo
│   │       │   │               │               └── etc
│   │       │   │               └── Css
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   │   └── template
│   │       │       │   ├── ui_component
│   │       │       │   └── web
│   │       │       │       └── js
│   │       │       └── frontend
│   │       │           ├── email
│   │       │           └── web
│   │       ├── EncryptionKey
│   │       │   ├── Block
│   │       │   │   └── Adminhtml
│   │       │   │       └── Crypt
│   │       │   │           └── Key
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       └── Crypt
│   │       │   │           └── Key
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   └── ResourceModel
│   │       │   │       └── Key
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       ├── Controller
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       └── Crypt
│   │       │   │       │           └── Key
│   │       │   │       └── Model
│   │       │   │           └── ResourceModel
│   │       │   │               └── Key
│   │       │   └── view
│   │       │       └── adminhtml
│   │       │           └── layout
│   │       ├── Fedex
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── wsdl
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   └── Source
│   │       │   ├── Plugin
│   │       │   │   └── Block
│   │       │   │       ├── DataProviders
│   │       │   │       │   └── Tracking
│   │       │   │       └── Tracking
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       └── Model
│   │       │   └── view
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           └── web
│   │       │               └── js
│   │       │                   ├── model
│   │       │                   └── view
│   │       ├── GiftMessage
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   ├── Block
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Product
│   │       │   │   │   │   └── Helper
│   │       │   │   │   │       └── Form
│   │       │   │   │   └── Sales
│   │       │   │   │       └── Order
│   │       │   │   │           ├── Create
│   │       │   │   │           └── View
│   │       │   │   ├── Cart
│   │       │   │   │   └── Item
│   │       │   │   │       └── Renderer
│   │       │   │   │           └── Actions
│   │       │   │   └── Message
│   │       │   │       └── Multishipping
│   │       │   │           └── Plugin
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   ├── frontend
│   │       │   │   └── webapi_rest
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Plugin
│   │       │   │   ├── ResourceModel
│   │       │   │   │   └── Message
│   │       │   │   └── Type
│   │       │   │       └── Plugin
│   │       │   ├── Observer
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Metadata
│   │       │   │   │   └── Section
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   └── Cart
│   │       │   │       │       └── Item
│   │       │   │       │           └── Renderer
│   │       │   │       │               └── Actions
│   │       │   │       ├── Helper
│   │       │   │       ├── Model
│   │       │   │       │   ├── Plugin
│   │       │   │       │   └── Type
│   │       │   │       │       └── Plugin
│   │       │   │       ├── Observer
│   │       │   │       └── Ui
│   │       │   │           └── DataProvider
│   │       │   │               └── Product
│   │       │   │                   └── Modifier
│   │       │   ├── Ui
│   │       │   │   └── DataProvider
│   │       │   │       └── Product
│   │       │   │           └── Modifier
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   └── templates
│   │       │       │       └── sales
│   │       │       │           └── order
│   │       │       │               ├── create
│   │       │       │               └── view
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   └── cart
│   │       │           │       └── item
│   │       │           │           └── renderer
│   │       │           │               └── actions
│   │       │           └── web
│   │       │               ├── js
│   │       │               │   ├── action
│   │       │               │   ├── model
│   │       │               │   └── view
│   │       │               └── template
│   │       ├── GoogleAdwords
│   │       │   ├── Block
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Config
│   │       │   │   │   ├── Backend
│   │       │   │   │   └── Source
│   │       │   │   ├── Filter
│   │       │   │   └── Validator
│   │       │   ├── Observer
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       ├── Helper
│   │       │   │       ├── Model
│   │       │   │       │   ├── Config
│   │       │   │       │   │   └── Source
│   │       │   │       │   ├── Filter
│   │       │   │       │   └── Validator
│   │       │   │       └── Observer
│   │       │   └── view
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           └── templates
│   │       ├── GoogleAnalytics
│   │       │   ├── Block
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Observer
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       └── Observer
│   │       │   └── view
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           └── web
│   │       │               └── js
│   │       ├── GoogleOptimizer
│   │       │   ├── Block
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Catalog
│   │       │   │   │   │   ├── Category
│   │       │   │   │   │   │   └── Edit
│   │       │   │   │   │   └── Product
│   │       │   │   │   │       └── Edit
│   │       │   │   │   │           └── Tab
│   │       │   │   │   └── Cms
│   │       │   │   │       └── Page
│   │       │   │   │           └── Edit
│   │       │   │   │               └── Tab
│   │       │   │   └── Code
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Plugin
│   │       │   │   │   ├── Catalog
│   │       │   │   │   │   ├── Category
│   │       │   │   │   │   └── Product
│   │       │   │   │   │       └── Category
│   │       │   │   │   └── Cms
│   │       │   │   │       └── Page
│   │       │   │   └── ResourceModel
│   │       │   ├── Observer
│   │       │   │   ├── Category
│   │       │   │   ├── CmsPage
│   │       │   │   └── Product
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   └── Code
│   │       │   │       ├── Helper
│   │       │   │       ├── Model
│   │       │   │       │   └── Plugin
│   │       │   │       │       └── Catalog
│   │       │   │       │           └── Product
│   │       │   │       │               └── Category
│   │       │   │       ├── Observer
│   │       │   │       │   ├── Category
│   │       │   │       │   ├── CmsPage
│   │       │   │       │   └── Product
│   │       │   │       └── Ui
│   │       │   │           └── DataProvider
│   │       │   │               └── Product
│   │       │   │                   └── Form
│   │       │   │                       └── Modifier
│   │       │   ├── Ui
│   │       │   │   └── DataProvider
│   │       │   │       └── Product
│   │       │   │           └── Form
│   │       │   │               └── Modifier
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   └── ui_component
│   │       │       └── frontend
│   │       │           └── layout
│   │       ├── GraphQl
│   │       │   ├── Controller
│   │       │   │   └── HttpRequestValidator
│   │       │   ├── etc
│   │       │   │   └── graphql
│   │       │   ├── Model
│   │       │   │   └── Query
│   │       │   │       └── Resolver
│   │       │   └── Test
│   │       │       └── Mftf
│   │       ├── GraphQlCache
│   │       │   ├── Controller
│   │       │   │   └── Plugin
│   │       │   ├── etc
│   │       │   │   └── graphql
│   │       │   ├── Model
│   │       │   │   ├── Plugin
│   │       │   │   │   ├── App
│   │       │   │   │   │   └── PageCache
│   │       │   │   │   └── Query
│   │       │   │   └── Resolver
│   │       │   └── Test
│   │       │       └── Unit
│   │       │           └── Model
│   │       ├── GroupedCatalogInventory
│   │       │   ├── etc
│   │       │   ├── Plugin
│   │       │   └── Test
│   │       │       └── Unit
│   │       │           └── Plugin
│   │       ├── GroupedImportExport
│   │       │   ├── etc
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Export
│   │       │   │   │   └── Product
│   │       │   │   │       └── Type
│   │       │   │   └── Import
│   │       │   │       └── Product
│   │       │   │           └── Type
│   │       │   │               └── Grouped
│   │       │   └── Test
│   │       │       ├── Mftf
│   │       │       └── Unit
│   │       │           └── Model
│   │       │               ├── Export
│   │       │               │   └── Product
│   │       │               └── Import
│   │       │                   └── Product
│   │       │                       └── Type
│   │       │                           └── Grouped
│   │       ├── GroupedProduct
│   │       │   ├── Block
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Items
│   │       │   │   │   │   └── Column
│   │       │   │   │   │       └── Name
│   │       │   │   │   ├── Order
│   │       │   │   │   │   └── Create
│   │       │   │   │   └── Product
│   │       │   │   │       └── Composite
│   │       │   │   │           └── Fieldset
│   │       │   │   ├── Cart
│   │       │   │   │   └── Item
│   │       │   │   │       └── Renderer
│   │       │   │   ├── Order
│   │       │   │   │   ├── Email
│   │       │   │   │   │   └── Items
│   │       │   │   │   │       └── Order
│   │       │   │   │   └── Item
│   │       │   │   │       └── Renderer
│   │       │   │   ├── Product
│   │       │   │   │   ├── Grouped
│   │       │   │   │   │   └── AssociatedProducts
│   │       │   │   │   └── View
│   │       │   │   │       └── Type
│   │       │   │   └── Stockqty
│   │       │   │       └── Type
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       └── Edit
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── Helper
│   │       │   │   └── Product
│   │       │   │       └── Configuration
│   │       │   │           └── Plugin
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Order
│   │       │   │   │   └── Pdf
│   │       │   │   │       └── Items
│   │       │   │   │           ├── Creditmemo
│   │       │   │   │           └── Invoice
│   │       │   │   ├── Product
│   │       │   │   │   ├── Cart
│   │       │   │   │   │   └── Configuration
│   │       │   │   │   │       └── Plugin
│   │       │   │   │   ├── Configuration
│   │       │   │   │   │   └── Item
│   │       │   │   │   ├── CopyConstructor
│   │       │   │   │   ├── Initialization
│   │       │   │   │   │   └── Helper
│   │       │   │   │   │       └── ProductLinks
│   │       │   │   │   │           └── Plugin
│   │       │   │   │   ├── Link
│   │       │   │   │   │   ├── CollectionProvider
│   │       │   │   │   │   └── ProductEntity
│   │       │   │   │   └── Type
│   │       │   │   │       └── Grouped
│   │       │   │   ├── ResourceModel
│   │       │   │   │   ├── Indexer
│   │       │   │   │   │   └── Stock
│   │       │   │   │   └── Product
│   │       │   │   │       ├── Indexer
│   │       │   │   │       │   └── Price
│   │       │   │   │       ├── Link
│   │       │   │   │       └── Type
│   │       │   │   │           └── Grouped
│   │       │   │   └── Sales
│   │       │   │       └── AdminOrder
│   │       │   │           └── Product
│   │       │   │               └── Quote
│   │       │   │                   └── Plugin
│   │       │   ├── Pricing
│   │       │   │   └── Price
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   ├── Order
│   │       │   │       │   │   │   └── Create
│   │       │   │       │   │   └── Product
│   │       │   │       │   │       └── Composite
│   │       │   │       │   │           └── Fieldset
│   │       │   │       │   ├── Cart
│   │       │   │       │   │   └── Item
│   │       │   │       │   │       └── Renderer
│   │       │   │       │   ├── Product
│   │       │   │       │   │   ├── Grouped
│   │       │   │       │   │   │   └── AssociatedProducts
│   │       │   │       │   │   └── View
│   │       │   │       │   │       └── Type
│   │       │   │       │   └── Stockqty
│   │       │   │       │       └── Type
│   │       │   │       ├── Controller
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       └── Edit
│   │       │   │       ├── Helper
│   │       │   │       │   └── Product
│   │       │   │       │       └── Configuration
│   │       │   │       │           └── Plugin
│   │       │   │       ├── Model
│   │       │   │       │   ├── Product
│   │       │   │       │   │   ├── Cart
│   │       │   │       │   │   │   └── Configuration
│   │       │   │       │   │   │       └── Plugin
│   │       │   │       │   │   ├── CopyConstructor
│   │       │   │       │   │   ├── Initialization
│   │       │   │       │   │   │   └── Helper
│   │       │   │       │   │   │       └── ProductLinks
│   │       │   │       │   │   │           └── Plugin
│   │       │   │       │   │   └── Type
│   │       │   │       │   │       └── Grouped
│   │       │   │       │   ├── ResourceModel
│   │       │   │       │   │   └── Product
│   │       │   │       │   │       └── Link
│   │       │   │       │   └── Sales
│   │       │   │       │       └── AdminOrder
│   │       │   │       │           └── Product
│   │       │   │       │               └── Quote
│   │       │   │       │                   └── Plugin
│   │       │   │       ├── Pricing
│   │       │   │       │   └── Price
│   │       │   │       └── Ui
│   │       │   │           └── DataProvider
│   │       │   │               └── Product
│   │       │   │                   └── Form
│   │       │   │                       └── Modifier
│   │       │   ├── Ui
│   │       │   │   └── DataProvider
│   │       │   │       └── Product
│   │       │   │           └── Form
│   │       │   │               └── Modifier
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   │   ├── catalog
│   │       │       │   │   │   └── product
│   │       │       │   │   │       └── composite
│   │       │       │   │   │           └── fieldset
│   │       │       │   │   └── product
│   │       │       │   │       ├── grouped
│   │       │       │   │       └── stock
│   │       │       │   ├── ui_component
│   │       │       │   └── web
│   │       │       │       ├── css
│   │       │       │       ├── js
│   │       │       │       └── template
│   │       │       │           └── components
│   │       │       ├── base
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   │   └── product
│   │       │       │   │       └── price
│   │       │       │   └── web
│   │       │       │       └── template
│   │       │       │           └── product
│   │       │       │               └── price
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   └── product
│   │       │           │       └── view
│   │       │           │           └── type
│   │       │           ├── ui_component
│   │       │           └── web
│   │       │               └── js
│   │       ├── GroupedProductGraphQl
│   │       │   ├── etc
│   │       │   │   └── graphql
│   │       │   ├── Model
│   │       │   │   └── Resolver
│   │       │   └── Test
│   │       │       └── Mftf
│   │       ├── ImportExport
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   ├── Block
│   │       │   │   └── Adminhtml
│   │       │   │       ├── Export
│   │       │   │       │   └── Edit
│   │       │   │       ├── Form
│   │       │   │       ├── Grid
│   │       │   │       │   └── Column
│   │       │   │       │       └── Renderer
│   │       │   │       └── Import
│   │       │   │           ├── Edit
│   │       │   │           └── Frame
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       ├── Export
│   │       │   │       │   └── File
│   │       │   │       ├── History
│   │       │   │       └── Import
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── Files
│   │       │   │   └── Sample
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Export
│   │       │   │   │   ├── Adapter
│   │       │   │   │   ├── Config
│   │       │   │   │   └── Entity
│   │       │   │   ├── Import
│   │       │   │   │   ├── Config
│   │       │   │   │   ├── Entity
│   │       │   │   │   ├── ErrorProcessing
│   │       │   │   │   └── Source
│   │       │   │   ├── Report
│   │       │   │   ├── ResourceModel
│   │       │   │   │   ├── History
│   │       │   │   │   └── Import
│   │       │   │   └── Source
│   │       │   │       ├── Export
│   │       │   │       └── Import
│   │       │   │           └── Behavior
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       ├── Export
│   │       │   │       │       ├── Grid
│   │       │   │       │       │   └── Column
│   │       │   │       │       │       └── Renderer
│   │       │   │       │       └── Import
│   │       │   │       │           └── Edit
│   │       │   │       ├── Controller
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       ├── History
│   │       │   │       │       └── Import
│   │       │   │       ├── Helper
│   │       │   │       └── Model
│   │       │   │           ├── Export
│   │       │   │           │   ├── Config
│   │       │   │           │   │   └── _files
│   │       │   │           │   └── Entity
│   │       │   │           ├── Import
│   │       │   │           │   ├── Config
│   │       │   │           │   │   └── _files
│   │       │   │           │   ├── Entity
│   │       │   │           │   ├── ErrorProcessing
│   │       │   │           │   └── Source
│   │       │   │           │       └── _files
│   │       │   │           ├── Report
│   │       │   │           ├── ResourceModel
│   │       │   │           └── Source
│   │       │   │               └── Import
│   │       │   │                   └── Behavior
│   │       │   ├── Ui
│   │       │   │   ├── Component
│   │       │   │   │   └── Columns
│   │       │   │   └── DataProvider
│   │       │   └── view
│   │       │       └── adminhtml
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   ├── export
│   │       │           │   │   └── form
│   │       │           │   │       └── filter
│   │       │           │   └── import
│   │       │           │       ├── form
│   │       │           │       └── frame
│   │       │           ├── ui_component
│   │       │           └── web
│   │       │               └── css
│   │       ├── Indexer
│   │       │   ├── App
│   │       │   ├── Block
│   │       │   │   └── Backend
│   │       │   │       └── Grid
│   │       │   │           └── Column
│   │       │   │               └── Renderer
│   │       │   ├── Console
│   │       │   │   └── Command
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       └── Indexer
│   │       │   ├── Cron
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Config
│   │       │   │   ├── Indexer
│   │       │   │   ├── Message
│   │       │   │   ├── Mview
│   │       │   │   │   └── View
│   │       │   │   ├── Processor
│   │       │   │   ├── ResourceModel
│   │       │   │   │   ├── Indexer
│   │       │   │   │   │   └── State
│   │       │   │   │   └── Mview
│   │       │   │   │       └── View
│   │       │   │   │           └── State
│   │       │   │   └── Source
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── App
│   │       │   │       ├── Block
│   │       │   │       │   └── Backend
│   │       │   │       │       └── Grid
│   │       │   │       │           └── Column
│   │       │   │       │               └── Renderer
│   │       │   │       ├── Console
│   │       │   │       │   └── Command
│   │       │   │       ├── Controller
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       └── Indexer
│   │       │   │       ├── Model
│   │       │   │       │   ├── Config
│   │       │   │       │   ├── Indexer
│   │       │   │       │   ├── Message
│   │       │   │       │   ├── Mview
│   │       │   │       │   │   └── View
│   │       │   │       │   ├── Processor
│   │       │   │       │   └── ResourceModel
│   │       │   │       │       ├── Indexer
│   │       │   │       │       │   └── State
│   │       │   │       │       └── Mview
│   │       │   │       │           └── View
│   │       │   │       │               └── State
│   │       │   │       └── Ui
│   │       │   │           └── DataProvider
│   │       │   │               └── Indexer
│   │       │   ├── Ui
│   │       │   │   └── DataProvider
│   │       │   │       └── Indexer
│   │       │   └── view
│   │       │       └── adminhtml
│   │       │           └── layout
│   │       ├── InstantPurchase
│   │       │   ├── Block
│   │       │   ├── Controller
│   │       │   │   └── Button
│   │       │   ├── CustomerData
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Model
│   │       │   │   ├── BillingAddressChoose
│   │       │   │   ├── PaymentMethodChoose
│   │       │   │   ├── QuoteManagement
│   │       │   │   ├── ShippingAddressChoose
│   │       │   │   ├── ShippingMethodChoose
│   │       │   │   └── Ui
│   │       │   ├── PaymentMethodIntegration
│   │       │   ├── Test
│   │       │   │   └── Mftf
│   │       │   └── view
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           └── web
│   │       │               ├── js
│   │       │               │   └── view
│   │       │               └── template
│   │       ├── Integration
│   │       │   ├── Api
│   │       │   ├── Block
│   │       │   │   └── Adminhtml
│   │       │   │       ├── Integration
│   │       │   │       │   ├── Activate
│   │       │   │       │   │   └── Permissions
│   │       │   │       │   │       └── Tab
│   │       │   │       │   └── Edit
│   │       │   │       │       └── Tab
│   │       │   │       └── Widget
│   │       │   │           └── Grid
│   │       │   │               └── Column
│   │       │   │                   └── Renderer
│   │       │   │                       ├── Button
│   │       │   │                       └── Link
│   │       │   ├── Controller
│   │       │   │   ├── Adminhtml
│   │       │   │   │   └── Integration
│   │       │   │   └── Token
│   │       │   ├── Cron
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   ├── frontend
│   │       │   │   ├── integration
│   │       │   │   ├── webapi_rest
│   │       │   │   └── webapi_soap
│   │       │   ├── Helper
│   │       │   │   └── Oauth
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Cache
│   │       │   │   ├── Config
│   │       │   │   │   ├── Consolidated
│   │       │   │   │   └── Integration
│   │       │   │   ├── Integration
│   │       │   │   │   └── Source
│   │       │   │   ├── Message
│   │       │   │   ├── Oauth
│   │       │   │   │   ├── Consumer
│   │       │   │   │   │   └── Validator
│   │       │   │   │   ├── Nonce
│   │       │   │   │   └── Token
│   │       │   │   │       └── RequestLog
│   │       │   │   ├── Plugin
│   │       │   │   └── ResourceModel
│   │       │   │       ├── Integration
│   │       │   │       └── Oauth
│   │       │   │           ├── Consumer
│   │       │   │           ├── Nonce
│   │       │   │           └── Token
│   │       │   ├── Plugin
│   │       │   │   └── Model
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── Data
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       ├── Integration
│   │       │   │       │       │   └── Edit
│   │       │   │       │       │       └── Tab
│   │       │   │       │       └── Widget
│   │       │   │       │           └── Grid
│   │       │   │       │               └── Column
│   │       │   │       │                   └── Renderer
│   │       │   │       ├── Controller
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   └── Integration
│   │       │   │       │   └── Token
│   │       │   │       ├── Helper
│   │       │   │       │   ├── _files
│   │       │   │       │   └── Oauth
│   │       │   │       ├── Model
│   │       │   │       │   ├── Config
│   │       │   │       │   │   ├── Consolidated
│   │       │   │       │   │   │   └── _files
│   │       │   │       │   │   ├── _files
│   │       │   │       │   │   └── Integration
│   │       │   │       │   │       └── _files
│   │       │   │       │   ├── Integration
│   │       │   │       │   │   └── Source
│   │       │   │       │   ├── Oauth
│   │       │   │       │   │   ├── Consumer
│   │       │   │       │   │   │   └── Validator
│   │       │   │       │   │   └── Token
│   │       │   │       │   ├── Plugin
│   │       │   │       │   └── ResourceModel
│   │       │   │       │       ├── Integration
│   │       │   │       │       └── Oauth
│   │       │   │       │           └── Token
│   │       │   │       └── Oauth
│   │       │   ├── view
│   │       │   │   └── adminhtml
│   │       │   │       ├── layout
│   │       │   │       ├── templates
│   │       │   │       │   └── integration
│   │       │   │       │       └── activate
│   │       │   │       │           └── permissions
│   │       │   │       │               └── tab
│   │       │   │       └── web
│   │       │   │           └── js
│   │       │   └── ViewModel
│   │       ├── LayeredNavigation
│   │       │   ├── Block
│   │       │   │   └── Navigation
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Aggregation
│   │       │   │   └── Attribute
│   │       │   │       └── Source
│   │       │   ├── Observer
│   │       │   │   ├── Edit
│   │       │   │   │   └── Tab
│   │       │   │   │       └── Front
│   │       │   │   └── Grid
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       └── Model
│   │       │   │           └── Aggregation
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   └── ui_component
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── page_layout
│   │       │           └── templates
│   │       │               └── layer
│   │       ├── Marketplace
│   │       │   ├── Block
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       ├── Index
│   │       │   │       └── Partners
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       ├── Controller
│   │       │   │       │   ├── Index
│   │       │   │       │   └── Partners
│   │       │   │       ├── Helper
│   │       │   │       └── Model
│   │       │   └── view
│   │       │       └── adminhtml
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           └── web
│   │       │               └── partners
│   │       │                   └── images
│   │       ├── MediaStorage
│   │       │   ├── App
│   │       │   ├── Block
│   │       │   │   └── System
│   │       │   │       └── Config
│   │       │   │           └── System
│   │       │   │               └── Storage
│   │       │   │                   └── Media
│   │       │   ├── Console
│   │       │   │   └── Command
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       └── System
│   │       │   │           └── Config
│   │       │   │               └── System
│   │       │   │                   └── Storage
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── Helper
│   │       │   │   └── File
│   │       │   │       └── Storage
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Asset
│   │       │   │   │   └── Plugin
│   │       │   │   ├── Config
│   │       │   │   │   ├── Backend
│   │       │   │   │   │   └── Storage
│   │       │   │   │   │       └── Media
│   │       │   │   │   └── Source
│   │       │   │   │       └── Storage
│   │       │   │   │           └── Media
│   │       │   │   ├── File
│   │       │   │   │   ├── Storage
│   │       │   │   │   │   ├── Database
│   │       │   │   │   │   └── Directory
│   │       │   │   │   └── Validator
│   │       │   │   └── ResourceModel
│   │       │   │       └── File
│   │       │   │           └── Storage
│   │       │   │               └── Directory
│   │       │   ├── Service
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       ├── App
│   │       │   │       ├── Helper
│   │       │   │       │   └── File
│   │       │   │       │       └── Storage
│   │       │   │       └── Model
│   │       │   │           ├── Asset
│   │       │   │           │   └── Plugin
│   │       │   │           ├── Config
│   │       │   │           │   └── Source
│   │       │   │           │       └── Storage
│   │       │   │           │           └── Media
│   │       │   │           ├── File
│   │       │   │           │   └── Storage
│   │       │   │           │       ├── Directory
│   │       │   │           │       └── _files
│   │       │   │           └── ResourceModel
│   │       │   │               └── File
│   │       │   │                   └── Storage
│   │       │   └── view
│   │       │       └── adminhtml
│   │       │           └── templates
│   │       │               └── system
│   │       │                   └── config
│   │       │                       └── system
│   │       │                           └── storage
│   │       │                               └── media
│   │       ├── MessageQueue
│   │       │   ├── Console
│   │       │   ├── etc
│   │       │   ├── Model
│   │       │   │   ├── Cron
│   │       │   │   │   └── ConsumersRunner
│   │       │   │   ├── Plugin
│   │       │   │   │   └── ResourceModel
│   │       │   │   └── ResourceModel
│   │       │   └── Test
│   │       │       ├── Mftf
│   │       │       └── Unit
│   │       │           ├── Console
│   │       │           ├── _files
│   │       │           └── Model
│   │       │               ├── Cron
│   │       │               │   └── ConsumersRunner
│   │       │               └── ResourceModel
│   │       ├── Msrp
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   │       └── ProductRender
│   │       │   ├── Block
│   │       │   │   └── Adminhtml
│   │       │   │       └── Product
│   │       │   │           └── Helper
│   │       │   │               └── Form
│   │       │   │                   └── Type
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   ├── frontend
│   │       │   │   ├── webapi_rest
│   │       │   │   └── webapi_soap
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Product
│   │       │   │   │   └── Attribute
│   │       │   │   │       └── Source
│   │       │   │   │           └── Type
│   │       │   │   ├── ProductRender
│   │       │   │   └── Quote
│   │       │   │       └── Address
│   │       │   ├── Observer
│   │       │   │   └── Frontend
│   │       │   │       └── Quote
│   │       │   ├── Plugin
│   │       │   │   └── Bundle
│   │       │   │       └── Block
│   │       │   │           └── Adminhtml
│   │       │   │               └── Catalog
│   │       │   │                   └── Product
│   │       │   │                       └── Edit
│   │       │   │                           └── Tab
│   │       │   ├── Pricing
│   │       │   │   ├── Price
│   │       │   │   └── Render
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Metadata
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Helper
│   │       │   │       ├── Model
│   │       │   │       │   └── Product
│   │       │   │       │       └── Attribute
│   │       │   │       │           └── Source
│   │       │   │       │               └── Type
│   │       │   │       ├── Observer
│   │       │   │       │   └── Frontend
│   │       │   │       │       └── Quote
│   │       │   │       ├── Pricing
│   │       │   │       │   └── Price
│   │       │   │       └── Ui
│   │       │   │           └── DataProvider
│   │       │   │               └── Product
│   │       │   │                   ├── Form
│   │       │   │                   │   └── Modifier
│   │       │   │                   └── Listing
│   │       │   │                       └── Collector
│   │       │   ├── Ui
│   │       │   │   └── DataProvider
│   │       │   │       └── Product
│   │       │   │           ├── Form
│   │       │   │           │   └── Modifier
│   │       │   │           └── Listing
│   │       │   │               └── Collector
│   │       │   └── view
│   │       │       ├── base
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   │   └── product
│   │       │       │   │       └── price
│   │       │       │   └── web
│   │       │       │       └── js
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   ├── cart
│   │       │           │   └── render
│   │       │           │       └── item
│   │       │           ├── ui_component
│   │       │           └── web
│   │       │               ├── js
│   │       │               │   ├── product
│   │       │               │   │   └── list
│   │       │               │   │       └── columns
│   │       │               │   └── view
│   │       │               │       └── checkout
│   │       │               │           └── minicart
│   │       │               │               └── subtotal
│   │       │               └── template
│   │       │                   ├── checkout
│   │       │                   │   └── minicart
│   │       │                   │       └── subtotal
│   │       │                   └── product
│   │       │                       ├── item
│   │       │                       └── price
│   │       ├── MsrpConfigurableProduct
│   │       │   ├── etc
│   │       │   └── Pricing
│   │       ├── MsrpGroupedProduct
│   │       │   ├── etc
│   │       │   └── Pricing
│   │       ├── Multishipping
│   │       │   ├── Block
│   │       │   │   ├── Checkout
│   │       │   │   │   ├── Address
│   │       │   │   │   ├── Billing
│   │       │   │   │   └── Payment
│   │       │   │   └── DataProviders
│   │       │   ├── Controller
│   │       │   │   └── Checkout
│   │       │   │       └── Address
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Cart
│   │       │   │   │   └── Controller
│   │       │   │   ├── Checkout
│   │       │   │   │   └── Type
│   │       │   │   │       └── Multishipping
│   │       │   │   └── Payment
│   │       │   │       └── Method
│   │       │   │           └── Specification
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── Page
│   │       │   │   │   └── Section
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   └── Checkout
│   │       │   │       │       ├── Address
│   │       │   │       │       ├── Billing
│   │       │   │       │       └── Payment
│   │       │   │       ├── Controller
│   │       │   │       │   └── Checkout
│   │       │   │       │       └── Address
│   │       │   │       ├── Helper
│   │       │   │       └── Model
│   │       │   │           ├── Cart
│   │       │   │           │   └── Controller
│   │       │   │           ├── Checkout
│   │       │   │           │   └── Type
│   │       │   │           │       └── Multishipping
│   │       │   │           └── Payment
│   │       │   │               └── Method
│   │       │   │                   └── Specification
│   │       │   └── view
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   ├── checkout
│   │       │           │   │   ├── address
│   │       │           │   │   ├── billing
│   │       │           │   │   ├── item
│   │       │           │   │   └── overview
│   │       │           │   ├── js
│   │       │           │   └── multishipping
│   │       │           │       └── item
│   │       │           └── web
│   │       │               └── js
│   │       ├── MysqlMq
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Driver
│   │       │   │   │   └── Bulk
│   │       │   │   └── ResourceModel
│   │       │   ├── Setup
│   │       │   └── Test
│   │       │       ├── Mftf
│   │       │       └── Unit
│   │       │           ├── Model
│   │       │           │   ├── Driver
│   │       │           │   │   └── Bulk
│   │       │           │   └── ResourceModel
│   │       │           └── Setup
│   │       ├── NewRelicReporting
│   │       │   ├── Console
│   │       │   │   └── Command
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Apm
│   │       │   │   ├── Cron
│   │       │   │   ├── Module
│   │       │   │   ├── Observer
│   │       │   │   └── ResourceModel
│   │       │   │       ├── Counts
│   │       │   │       ├── Module
│   │       │   │       ├── Orders
│   │       │   │       ├── System
│   │       │   │       └── Users
│   │       │   ├── Plugin
│   │       │   └── Test
│   │       │       ├── Mftf
│   │       │       └── Unit
│   │       │           └── Model
│   │       │               ├── Apm
│   │       │               ├── Cron
│   │       │               ├── Module
│   │       │               └── Observer
│   │       ├── Newsletter
│   │       │   ├── Block
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Problem
│   │       │   │   │   │   └── Grid
│   │       │   │   │   │       ├── Filter
│   │       │   │   │   │       └── Renderer
│   │       │   │   │   ├── Queue
│   │       │   │   │   │   ├── Edit
│   │       │   │   │   │   ├── Grid
│   │       │   │   │   │   │   └── Renderer
│   │       │   │   │   │   └── Preview
│   │       │   │   │   ├── Subscriber
│   │       │   │   │   │   └── Grid
│   │       │   │   │   │       ├── Filter
│   │       │   │   │   │       └── Renderer
│   │       │   │   │   └── Template
│   │       │   │   │       ├── Edit
│   │       │   │   │       ├── Grid
│   │       │   │   │       │   └── Renderer
│   │       │   │   │       └── Preview
│   │       │   │   └── Subscribe
│   │       │   │       └── Grid
│   │       │   │           └── Options
│   │       │   ├── Controller
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Problem
│   │       │   │   │   ├── Queue
│   │       │   │   │   ├── Subscriber
│   │       │   │   │   └── Template
│   │       │   │   ├── Manage
│   │       │   │   └── Subscriber
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Plugin
│   │       │   │   ├── Queue
│   │       │   │   │   └── Options
│   │       │   │   ├── ResourceModel
│   │       │   │   │   ├── Grid
│   │       │   │   │   ├── Problem
│   │       │   │   │   ├── Queue
│   │       │   │   │   │   └── Grid
│   │       │   │   │   ├── Subscriber
│   │       │   │   │   │   └── Grid
│   │       │   │   │   └── Template
│   │       │   │   └── Template
│   │       │   ├── Observer
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       ├── Queue
│   │       │   │       │       └── Template
│   │       │   │       │           └── Grid
│   │       │   │       │               └── Renderer
│   │       │   │       ├── Controller
│   │       │   │       │   └── Manage
│   │       │   │       ├── Model
│   │       │   │       │   ├── Plugin
│   │       │   │       │   ├── Queue
│   │       │   │       │   └── Template
│   │       │   │       └── Observer
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   └── templates
│   │       │       │       ├── preview
│   │       │       │       ├── problem
│   │       │       │       ├── queue
│   │       │       │       ├── subscriber
│   │       │       │       └── template
│   │       │       ├── base
│   │       │       │   └── ui_component
│   │       │       └── frontend
│   │       │           ├── email
│   │       │           ├── layout
│   │       │           └── templates
│   │       │               └── js
│   │       ├── OfflinePayments
│   │       │   ├── Block
│   │       │   │   ├── Form
│   │       │   │   └── Info
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   ├── Observer
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   └── Data
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   ├── Form
│   │       │   │       │   └── Info
│   │       │   │       ├── Model
│   │       │   │       └── Observer
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   └── templates
│   │       │       │       ├── form
│   │       │       │       └── info
│   │       │       │           └── pdf
│   │       │       ├── base
│   │       │       │   └── templates
│   │       │       │       └── info
│   │       │       │           └── pdf
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   ├── form
│   │       │           │   ├── info
│   │       │           │   └── multishipping
│   │       │           └── web
│   │       │               ├── js
│   │       │               │   └── view
│   │       │               │       └── payment
│   │       │               │           └── method-renderer
│   │       │               └── template
│   │       │                   └── payment
│   │       ├── OfflineShipping
│   │       │   ├── Block
│   │       │   │   └── Adminhtml
│   │       │   │       ├── Carrier
│   │       │   │       │   └── Tablerate
│   │       │   │       └── Form
│   │       │   │           └── Field
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       └── System
│   │       │   │           └── Config
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Carrier
│   │       │   │   │   └── Flatrate
│   │       │   │   ├── Config
│   │       │   │   │   ├── Backend
│   │       │   │   │   └── Source
│   │       │   │   ├── Plugin
│   │       │   │   │   └── Checkout
│   │       │   │   │       └── Block
│   │       │   │   │           └── Cart
│   │       │   │   ├── Quote
│   │       │   │   │   └── Address
│   │       │   │   ├── ResourceModel
│   │       │   │   │   └── Carrier
│   │       │   │   │       └── Tablerate
│   │       │   │   │           └── CSV
│   │       │   │   ├── SalesRule
│   │       │   │   └── Source
│   │       │   │       └── SalesRule
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       ├── Carrier
│   │       │   │       │       │   └── Tablerate
│   │       │   │       │       └── Form
│   │       │   │       │           └── Field
│   │       │   │       └── Model
│   │       │   │           ├── Carrier
│   │       │   │           ├── Config
│   │       │   │           │   ├── Backend
│   │       │   │           │   └── Source
│   │       │   │           ├── Plugin
│   │       │   │           │   └── Checkout
│   │       │   │           │       └── Block
│   │       │   │           │           └── Cart
│   │       │   │           ├── Quote
│   │       │   │           │   └── Address
│   │       │   │           ├── ResourceModel
│   │       │   │           │   └── Carrier
│   │       │   │           │       └── Tablerate
│   │       │   │           │           └── CSV
│   │       │   │           └── SalesRule
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   └── ui_component
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           └── web
│   │       │               └── js
│   │       │                   ├── model
│   │       │                   │   ├── shipping-rates-validation-rules
│   │       │                   │   └── shipping-rates-validator
│   │       │                   └── view
│   │       │                       └── shipping-rates-validation
│   │       ├── PageCache
│   │       │   ├── Block
│   │       │   │   └── System
│   │       │   │       └── Config
│   │       │   │           └── Form
│   │       │   │               └── Field
│   │       │   │                   └── Export
│   │       │   ├── Console
│   │       │   │   └── Command
│   │       │   ├── Controller
│   │       │   │   ├── Adminhtml
│   │       │   │   │   └── PageCache
│   │       │   │   └── Block
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Exception
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── App
│   │       │   │   │   ├── FrontController
│   │       │   │   │   └── Response
│   │       │   │   ├── Cache
│   │       │   │   ├── Controller
│   │       │   │   │   └── Result
│   │       │   │   ├── Layout
│   │       │   │   ├── System
│   │       │   │   │   └── Config
│   │       │   │   │       ├── Backend
│   │       │   │   │       └── Source
│   │       │   │   └── Varnish
│   │       │   ├── Observer
│   │       │   │   └── SwitchPageCacheOnMaintenance
│   │       │   ├── Plugin
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── App
│   │       │   │       ├── Block
│   │       │   │       │   └── Controller
│   │       │   │       ├── Controller
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   └── PageCache
│   │       │   │       │   └── Block
│   │       │   │       ├── Helper
│   │       │   │       ├── Model
│   │       │   │       │   ├── App
│   │       │   │       │   │   ├── FrontController
│   │       │   │       │   │   └── Response
│   │       │   │       │   ├── Cache
│   │       │   │       │   ├── Controller
│   │       │   │       │   │   └── Result
│   │       │   │       │   ├── _files
│   │       │   │       │   ├── Layout
│   │       │   │       │   └── System
│   │       │   │       │       └── Config
│   │       │   │       │           └── Backend
│   │       │   │       └── Observer
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   └── templates
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   └── js
│   │       │           └── web
│   │       │               └── js
│   │       ├── Payment
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   ├── Block
│   │       │   │   ├── Adminhtml
│   │       │   │   │   └── Transparent
│   │       │   │   ├── Form
│   │       │   │   ├── Info
│   │       │   │   └── Transparent
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Gateway
│   │       │   │   ├── Command
│   │       │   │   │   └── Result
│   │       │   │   ├── Config
│   │       │   │   ├── Data
│   │       │   │   │   ├── Order
│   │       │   │   │   └── Quote
│   │       │   │   ├── ErrorMapper
│   │       │   │   ├── Helper
│   │       │   │   ├── Http
│   │       │   │   │   ├── Client
│   │       │   │   │   └── Converter
│   │       │   │   │       └── Soap
│   │       │   │   ├── Request
│   │       │   │   ├── Response
│   │       │   │   └── Validator
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Cart
│   │       │   │   │   └── SalesModel
│   │       │   │   ├── Checks
│   │       │   │   │   └── CanUseForCountry
│   │       │   │   ├── Config
│   │       │   │   │   └── Source
│   │       │   │   ├── Method
│   │       │   │   │   ├── Online
│   │       │   │   │   └── Specification
│   │       │   │   ├── Paygate
│   │       │   │   ├── ResourceModel
│   │       │   │   │   └── Grid
│   │       │   │   └── Source
│   │       │   ├── Observer
│   │       │   ├── Plugin
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   └── Metadata
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   └── Transparent
│   │       │   │       │   ├── Form
│   │       │   │       │   ├── Info
│   │       │   │       │   └── Transparent
│   │       │   │       ├── Gateway
│   │       │   │       │   ├── Command
│   │       │   │       │   ├── Config
│   │       │   │       │   ├── Data
│   │       │   │       │   │   ├── Order
│   │       │   │       │   │   └── Quote
│   │       │   │       │   ├── Http
│   │       │   │       │   │   ├── Client
│   │       │   │       │   │   └── Converter
│   │       │   │       │   │       └── Soap
│   │       │   │       │   ├── Request
│   │       │   │       │   ├── Response
│   │       │   │       │   └── Validator
│   │       │   │       ├── Helper
│   │       │   │       ├── Model
│   │       │   │       │   ├── Cart
│   │       │   │       │   │   └── SalesModel
│   │       │   │       │   ├── Checks
│   │       │   │       │   │   └── CanUseForCountry
│   │       │   │       │   ├── Config
│   │       │   │       │   │   ├── _files
│   │       │   │       │   │   └── Source
│   │       │   │       │   ├── Method
│   │       │   │       │   │   ├── AbstractMethod
│   │       │   │       │   │   └── Specification
│   │       │   │       │   ├── ResourceModel
│   │       │   │       │   │   └── Grid
│   │       │   │       │   └── Source
│   │       │   │       ├── Observer
│   │       │   │       └── Plugin
│   │       │   ├── Ui
│   │       │   │   └── Component
│   │       │   │       └── Listing
│   │       │   │           └── Column
│   │       │   │               └── Method
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── templates
│   │       │       │   │   ├── form
│   │       │       │   │   ├── info
│   │       │       │   │   │   └── pdf
│   │       │       │   │   └── transparent
│   │       │       │   └── web
│   │       │       │       └── js
│   │       │       ├── base
│   │       │       │   ├── templates
│   │       │       │   │   └── info
│   │       │       │   │       └── pdf
│   │       │       │   └── web
│   │       │       │       ├── images
│   │       │       │       │   └── cc
│   │       │       │       └── js
│   │       │       │           └── model
│   │       │       │               └── credit-card-validation
│   │       │       │                   ├── credit-card-number-validator
│   │       │       │                   └── expiration-date-validator
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   ├── form
│   │       │           │   ├── info
│   │       │           │   │   └── pdf
│   │       │           │   └── transparent
│   │       │           └── web
│   │       │               ├── js
│   │       │               │   └── view
│   │       │               │       └── payment
│   │       │               │           └── method-renderer
│   │       │               └── template
│   │       │                   └── payment
│   │       ├── Paypal
│   │       │   ├── Block
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Billing
│   │       │   │   │   │   └── Agreement
│   │       │   │   │   │       └── View
│   │       │   │   │   │           └── Tab
│   │       │   │   │   ├── Customer
│   │       │   │   │   │   └── Edit
│   │       │   │   │   │       └── Tab
│   │       │   │   │   ├── Order
│   │       │   │   │   ├── Payflowpro
│   │       │   │   │   ├── Settlement
│   │       │   │   │   │   └── Details
│   │       │   │   │   ├── Store
│   │       │   │   │   └── System
│   │       │   │   │       └── Config
│   │       │   │   │           ├── Field
│   │       │   │   │           │   ├── Depends
│   │       │   │   │           │   └── Enable
│   │       │   │   │           ├── Fieldset
│   │       │   │   │           ├── MultiSelect
│   │       │   │   │           └── Payflowlink
│   │       │   │   ├── Billing
│   │       │   │   │   └── Agreement
│   │       │   │   ├── Bml
│   │       │   │   ├── Cart
│   │       │   │   ├── Checkout
│   │       │   │   │   └── Onepage
│   │       │   │   │       └── Success
│   │       │   │   ├── Express
│   │       │   │   │   ├── InContext
│   │       │   │   │   │   └── Minicart
│   │       │   │   │   └── Review
│   │       │   │   ├── Hosted
│   │       │   │   │   └── Pro
│   │       │   │   ├── Payflow
│   │       │   │   │   ├── Advanced
│   │       │   │   │   ├── Bml
│   │       │   │   │   ├── Customer
│   │       │   │   │   └── Link
│   │       │   │   ├── PayflowExpress
│   │       │   │   └── Payment
│   │       │   │       ├── Form
│   │       │   │       │   └── Billing
│   │       │   │       └── Info
│   │       │   │           └── Billing
│   │       │   ├── Controller
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Billing
│   │       │   │   │   │   └── Agreement
│   │       │   │   │   ├── Express
│   │       │   │   │   ├── Paypal
│   │       │   │   │   │   └── Reports
│   │       │   │   │   └── Transparent
│   │       │   │   ├── Billing
│   │       │   │   │   └── Agreement
│   │       │   │   ├── Bml
│   │       │   │   ├── Express
│   │       │   │   │   └── AbstractExpress
│   │       │   │   ├── Hostedpro
│   │       │   │   ├── Ipn
│   │       │   │   ├── Payflow
│   │       │   │   ├── Payflowadvanced
│   │       │   │   ├── Payflowbml
│   │       │   │   ├── Payflowexpress
│   │       │   │   └── Transparent
│   │       │   ├── Cron
│   │       │   ├── CustomerData
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   │   ├── rules
│   │       │   │   │   └── system
│   │       │   │   └── frontend
│   │       │   ├── Gateway
│   │       │   │   └── Payflowpro
│   │       │   │       └── Command
│   │       │   ├── Helper
│   │       │   │   └── Shortcut
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Adminhtml
│   │       │   │   ├── Api
│   │       │   │   │   └── Type
│   │       │   │   ├── Billing
│   │       │   │   │   └── Agreement
│   │       │   │   ├── Config
│   │       │   │   │   ├── Rules
│   │       │   │   │   └── Structure
│   │       │   │   │       └── Element
│   │       │   │   ├── Express
│   │       │   │   │   └── Checkout
│   │       │   │   ├── Hostedpro
│   │       │   │   ├── InstantPurchase
│   │       │   │   │   └── Payflow
│   │       │   │   │       └── Pro
│   │       │   │   ├── Method
│   │       │   │   │   └── Checks
│   │       │   │   ├── Payflow
│   │       │   │   │   ├── Service
│   │       │   │   │   │   ├── Request
│   │       │   │   │   │   └── Response
│   │       │   │   │   │       ├── Handler
│   │       │   │   │   │       └── Validator
│   │       │   │   │   └── Ui
│   │       │   │   │       └── Adminhtml
│   │       │   │   ├── PayflowExpress
│   │       │   │   ├── Payment
│   │       │   │   │   └── Method
│   │       │   │   │       └── Billing
│   │       │   │   ├── Report
│   │       │   │   │   └── Settlement
│   │       │   │   ├── ResourceModel
│   │       │   │   │   ├── Billing
│   │       │   │   │   │   └── Agreement
│   │       │   │   │   └── Report
│   │       │   │   │       └── Settlement
│   │       │   │   │           ├── Options
│   │       │   │   │           └── Row
│   │       │   │   └── System
│   │       │   │       └── Config
│   │       │   │           ├── Backend
│   │       │   │           └── Source
│   │       │   │               └── PaymentActions
│   │       │   ├── Observer
│   │       │   ├── Plugin
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Metadata
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   ├── Suite
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   ├── Order
│   │       │   │       │   │   ├── Store
│   │       │   │       │   │   └── System
│   │       │   │       │   │       └── Config
│   │       │   │       │   │           ├── Field
│   │       │   │       │   │           │   └── Enable
│   │       │   │       │   │           │       └── AbstractEnable
│   │       │   │       │   │           ├── Fieldset
│   │       │   │       │   │           └── Multiselect
│   │       │   │       │   ├── Billing
│   │       │   │       │   │   └── Agreement
│   │       │   │       │   ├── Bml
│   │       │   │       │   ├── Express
│   │       │   │       │   ├── Payflow
│   │       │   │       │   │   └── Link
│   │       │   │       │   └── PayflowExpress
│   │       │   │       ├── Controller
│   │       │   │       │   ├── Billing
│   │       │   │       │   │   └── Agreement
│   │       │   │       │   ├── Express
│   │       │   │       │   ├── Ipn
│   │       │   │       │   ├── Payflow
│   │       │   │       │   └── Transparent
│   │       │   │       ├── Cron
│   │       │   │       ├── CustomerData
│   │       │   │       ├── Helper
│   │       │   │       │   └── Shortcut
│   │       │   │       ├── Model
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   ├── Api
│   │       │   │       │   ├── Billing
│   │       │   │       │   │   └── Agreement
│   │       │   │       │   ├── Config
│   │       │   │       │   │   ├── Rules
│   │       │   │       │   │   │   └── ConvertibleContent
│   │       │   │       │   │   └── Structure
│   │       │   │       │   │       ├── Element
│   │       │   │       │   │       └── _files
│   │       │   │       │   ├── Express
│   │       │   │       │   ├── _files
│   │       │   │       │   ├── Hostedpro
│   │       │   │       │   ├── Method
│   │       │   │       │   │   └── Checks
│   │       │   │       │   ├── Payflow
│   │       │   │       │   │   └── Service
│   │       │   │       │   │       ├── Request
│   │       │   │       │   │       └── Response
│   │       │   │       │   │           ├── Handler
│   │       │   │       │   │           │   └── _files
│   │       │   │       │   │           └── Validator
│   │       │   │       │   ├── Payment
│   │       │   │       │   │   └── Method
│   │       │   │       │   │       └── Billing
│   │       │   │       │   ├── Report
│   │       │   │       │   │   └── Settlement
│   │       │   │       │   ├── ResourceModel
│   │       │   │       │   │   └── Billing
│   │       │   │       │   └── System
│   │       │   │       │       └── Config
│   │       │   │       │           └── Source
│   │       │   │       └── Observer
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   │   ├── billing
│   │       │       │   │   │   └── agreement
│   │       │       │   │   │       └── view
│   │       │       │   │   │           └── tab
│   │       │       │   │   ├── payflowpro
│   │       │       │   │   ├── payment
│   │       │       │   │   │   └── form
│   │       │       │   │   │       └── billing
│   │       │       │   │   ├── system
│   │       │       │   │   │   └── config
│   │       │       │   │   │       ├── fieldset
│   │       │       │   │   │       └── payflowlink
│   │       │       │   │   └── transparent
│   │       │       │   └── web
│   │       │       │       ├── images
│   │       │       │       └── js
│   │       │       │           ├── payflowpro
│   │       │       │           └── predicate
│   │       │       ├── base
│   │       │       │   └── ui_component
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   ├── billing
│   │       │           │   │   └── agreement
│   │       │           │   ├── checkout
│   │       │           │   │   └── onepage
│   │       │           │   │       ├── review
│   │       │           │   │       └── success
│   │       │           │   ├── express
│   │       │           │   │   ├── in-context
│   │       │           │   │   │   └── shortcut
│   │       │           │   │   ├── review
│   │       │           │   │   │   └── shipping
│   │       │           │   │   └── shortcut
│   │       │           │   ├── hss
│   │       │           │   │   └── review
│   │       │           │   ├── js
│   │       │           │   ├── partner
│   │       │           │   ├── payflowadvanced
│   │       │           │   ├── payflowlink
│   │       │           │   └── payment
│   │       │           │       └── form
│   │       │           │           └── billing
│   │       │           └── web
│   │       │               ├── js
│   │       │               │   ├── action
│   │       │               │   ├── in-context
│   │       │               │   ├── model
│   │       │               │   └── view
│   │       │               │       ├── payment
│   │       │               │       │   └── method-renderer
│   │       │               │       │       ├── in-context
│   │       │               │       │       └── payflowpro
│   │       │               │       └── review
│   │       │               │           └── actions
│   │       │               └── template
│   │       │                   └── payment
│   │       │                       └── express
│   │       ├── PaypalCaptcha
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Model
│   │       │   │   └── Checkout
│   │       │   ├── Observer
│   │       │   └── view
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           └── web
│   │       │               ├── js
│   │       │               │   └── view
│   │       │               │       ├── checkout
│   │       │               │       └── payment
│   │       │               └── template
│   │       │                   └── payment
│   │       ├── Persistent
│   │       │   ├── Block
│   │       │   │   ├── Form
│   │       │   │   └── Header
│   │       │   ├── Controller
│   │       │   │   └── Index
│   │       │   ├── CustomerData
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   ├── frontend
│   │       │   │   ├── webapi_rest
│   │       │   │   └── webapi_soap
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Checkout
│   │       │   │   ├── Layout
│   │       │   │   ├── Persistent
│   │       │   │   ├── Plugin
│   │       │   │   └── ResourceModel
│   │       │   ├── Observer
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Metadata
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   └── Header
│   │       │   │       ├── Helper
│   │       │   │       ├── Model
│   │       │   │       │   ├── Checkout
│   │       │   │       │   ├── Layout
│   │       │   │       │   └── Plugin
│   │       │   │       └── Observer
│   │       │   └── view
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           └── web
│   │       │               ├── js
│   │       │               │   └── view
│   │       │               └── template
│   │       ├── ProductAlert
│   │       │   ├── Block
│   │       │   │   ├── Email
│   │       │   │   └── Product
│   │       │   │       └── View
│   │       │   ├── Controller
│   │       │   │   ├── Add
│   │       │   │   └── Unsubscribe
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   └── ResourceModel
│   │       │   │       ├── Price
│   │       │   │       │   └── Customer
│   │       │   │       └── Stock
│   │       │   │           └── Customer
│   │       │   ├── Setup
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   ├── Email
│   │       │   │       │   └── Product
│   │       │   │       │       └── View
│   │       │   │       └── Model
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   └── email
│   │       │       └── frontend
│   │       │           ├── email
│   │       │           ├── layout
│   │       │           └── templates
│   │       │               ├── email
│   │       │               └── product
│   │       ├── ProductVideo
│   │       │   ├── Block
│   │       │   │   ├── Adminhtml
│   │       │   │   │   └── Product
│   │       │   │   │       └── Edit
│   │       │   │   └── Product
│   │       │   │       └── View
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       └── Product
│   │       │   │           └── Gallery
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Plugin
│   │       │   │   │   └── Catalog
│   │       │   │   │       └── Product
│   │       │   │   │           └── Gallery
│   │       │   │   ├── Product
│   │       │   │   │   └── Attribute
│   │       │   │   │       └── Media
│   │       │   │   └── ResourceModel
│   │       │   ├── Observer
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Metadata
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   └── Product
│   │       │   │       │   │       └── Edit
│   │       │   │       │   └── Product
│   │       │   │       │       └── View
│   │       │   │       ├── Controller
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       └── Product
│   │       │   │       │           └── Gallery
│   │       │   │       ├── Helper
│   │       │   │       ├── Model
│   │       │   │       │   ├── Plugin
│   │       │   │       │   │   └── Catalog
│   │       │   │       │   │       └── Product
│   │       │   │       │   │           └── Gallery
│   │       │   │       │   └── Product
│   │       │   │       │       └── Attribute
│   │       │   │       │           └── Media
│   │       │   │       └── Observer
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   │   ├── helper
│   │       │       │   │   └── product
│   │       │       │   │       └── edit
│   │       │       │   │           └── slideout
│   │       │       │   ├── ui_component
│   │       │       │   └── web
│   │       │       │       ├── css
│   │       │       │       ├── images
│   │       │       │       └── js
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   └── product
│   │       │           │       └── view
│   │       │           └── web
│   │       │               ├── img
│   │       │               └── js
│   │       ├── Quote
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   ├── frontend
│   │       │   │   ├── webapi_rest
│   │       │   │   └── webapi_soap
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Cart
│   │       │   │   │   └── Totals
│   │       │   │   ├── GuestCart
│   │       │   │   ├── GuestCartManagement
│   │       │   │   │   └── Plugin
│   │       │   │   ├── Product
│   │       │   │   │   └── Plugin
│   │       │   │   ├── Quote
│   │       │   │   │   ├── Address
│   │       │   │   │   │   ├── RateResult
│   │       │   │   │   │   └── Total
│   │       │   │   │   ├── Item
│   │       │   │   │   ├── Payment
│   │       │   │   │   ├── ShippingAssignment
│   │       │   │   │   └── Validator
│   │       │   │   │       └── MinimumOrderAmount
│   │       │   │   ├── QuoteRepository
│   │       │   │   │   └── Plugin
│   │       │   │   ├── ResourceModel
│   │       │   │   │   └── Quote
│   │       │   │   │       ├── Address
│   │       │   │   │       │   ├── Attribute
│   │       │   │   │       │   │   ├── Backend
│   │       │   │   │       │   │   └── Frontend
│   │       │   │   │       │   ├── Item
│   │       │   │   │       │   └── Rate
│   │       │   │   │       ├── Item
│   │       │   │   │       │   └── Option
│   │       │   │   │       └── Payment
│   │       │   │   ├── ValidationRules
│   │       │   │   └── Webapi
│   │       │   ├── Observer
│   │       │   │   ├── Backend
│   │       │   │   └── Frontend
│   │       │   │       └── Quote
│   │       │   │           └── Address
│   │       │   ├── Plugin
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   └── Test
│   │       │       ├── Mftf
│   │       │       │   ├── Data
│   │       │       │   ├── Metadata
│   │       │       │   └── Test
│   │       │       └── Unit
│   │       │           ├── Model
│   │       │           │   ├── Cart
│   │       │           │   │   └── Totals
│   │       │           │   ├── GuestCart
│   │       │           │   ├── GuestCartManagement
│   │       │           │   │   └── Plugin
│   │       │           │   ├── Product
│   │       │           │   │   └── Plugin
│   │       │           │   ├── Quote
│   │       │           │   │   ├── Address
│   │       │           │   │   │   └── Total
│   │       │           │   │   ├── Item
│   │       │           │   │   ├── Payment
│   │       │           │   │   ├── ShippingAssignment
│   │       │           │   │   └── Validator
│   │       │           │   │       └── MinimumOrderAmount
│   │       │           │   ├── QuoteRepository
│   │       │           │   │   └── Plugin
│   │       │           │   ├── ResourceModel
│   │       │           │   │   └── Quote
│   │       │           │   │       └── Item
│   │       │           │   └── Webapi
│   │       │           ├── Observer
│   │       │           │   ├── Backend
│   │       │           │   └── Frontend
│   │       │           │       └── Quote
│   │       │           │           └── Address
│   │       │           └── Setup
│   │       ├── QuoteAnalytics
│   │       │   ├── etc
│   │       │   └── Test
│   │       │       └── Mftf
│   │       ├── QuoteGraphQl
│   │       │   ├── etc
│   │       │   │   └── graphql
│   │       │   └── Model
│   │       │       ├── Cart
│   │       │       ├── CartItem
│   │       │       │   └── DataProvider
│   │       │       │       └── CustomizableOptionValue
│   │       │       └── Resolver
│   │       │           └── ShippingAddress
│   │       ├── RelatedProductGraphQl
│   │       │   ├── etc
│   │       │   └── Model
│   │       │       ├── DataProvider
│   │       │       └── Resolver
│   │       ├── ReleaseNotification
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       └── Notification
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Condition
│   │       │   │   ├── ContentProvider
│   │       │   │   │   └── Http
│   │       │   │   ├── ResourceModel
│   │       │   │   │   └── Viewer
│   │       │   │   └── Viewer
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       ├── Controller
│   │       │   │       │   └── Notification
│   │       │   │       └── Model
│   │       │   │           ├── Condition
│   │       │   │           └── ContentProvider
│   │       │   │               └── Http
│   │       │   ├── Ui
│   │       │   │   ├── DataProvider
│   │       │   │   │   └── Modifier
│   │       │   │   └── Renderer
│   │       │   └── view
│   │       │       └── adminhtml
│   │       │           ├── layout
│   │       │           ├── ui_component
│   │       │           └── web
│   │       │               └── js
│   │       │                   └── modal
│   │       ├── Reports
│   │       │   ├── Block
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Config
│   │       │   │   │   │   └── Form
│   │       │   │   │   │       └── Field
│   │       │   │   │   ├── Customer
│   │       │   │   │   ├── Filter
│   │       │   │   │   ├── Grid
│   │       │   │   │   │   └── Column
│   │       │   │   │   │       └── Renderer
│   │       │   │   │   ├── Product
│   │       │   │   │   │   ├── Downloads
│   │       │   │   │   │   │   └── Renderer
│   │       │   │   │   │   ├── Lowstock
│   │       │   │   │   │   └── Viewed
│   │       │   │   │   ├── Refresh
│   │       │   │   │   ├── Review
│   │       │   │   │   │   └── Detail
│   │       │   │   │   ├── Sales
│   │       │   │   │   │   ├── Bestsellers
│   │       │   │   │   │   ├── Coupons
│   │       │   │   │   │   ├── Grid
│   │       │   │   │   │   │   └── Column
│   │       │   │   │   │   │       └── Renderer
│   │       │   │   │   │   ├── Invoiced
│   │       │   │   │   │   ├── Refunded
│   │       │   │   │   │   ├── Sales
│   │       │   │   │   │   ├── Shipping
│   │       │   │   │   │   └── Tax
│   │       │   │   │   ├── Shopcart
│   │       │   │   │   │   ├── Abandoned
│   │       │   │   │   │   ├── Customer
│   │       │   │   │   │   └── Product
│   │       │   │   │   └── Wishlist
│   │       │   │   └── Product
│   │       │   │       └── Widget
│   │       │   │           └── Viewed
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       └── Report
│   │       │   │           ├── Customer
│   │       │   │           ├── Product
│   │       │   │           ├── Review
│   │       │   │           ├── Sales
│   │       │   │           ├── Shopcart
│   │       │   │           └── Statistics
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   ├── frontend
│   │       │   │   ├── webapi_rest
│   │       │   │   └── webapi_soap
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Event
│   │       │   │   ├── Grouped
│   │       │   │   ├── Plugin
│   │       │   │   ├── Product
│   │       │   │   │   └── Index
│   │       │   │   └── ResourceModel
│   │       │   │       ├── Accounts
│   │       │   │       │   └── Collection
│   │       │   │       ├── Customer
│   │       │   │       │   ├── Orders
│   │       │   │       │   │   └── Collection
│   │       │   │       │   └── Totals
│   │       │   │       │       └── Collection
│   │       │   │       ├── Event
│   │       │   │       │   └── Type
│   │       │   │       ├── Order
│   │       │   │       ├── Product
│   │       │   │       │   ├── Downloads
│   │       │   │       │   ├── Index
│   │       │   │       │   │   ├── Collection
│   │       │   │       │   │   ├── Compared
│   │       │   │       │   │   └── Viewed
│   │       │   │       │   ├── Lowstock
│   │       │   │       │   └── Sold
│   │       │   │       │       └── Collection
│   │       │   │       ├── Quote
│   │       │   │       │   └── Item
│   │       │   │       ├── Refresh
│   │       │   │       ├── Report
│   │       │   │       │   ├── Collection
│   │       │   │       │   └── Product
│   │       │   │       │       └── Viewed
│   │       │   │       ├── Review
│   │       │   │       │   ├── Customer
│   │       │   │       │   └── Product
│   │       │   │       └── Wishlist
│   │       │   │           └── Product
│   │       │   ├── Observer
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   ├── Grid
│   │       │   │       │   │   └── Sales
│   │       │   │       │   │       ├── Coupons
│   │       │   │       │   │       └── Grid
│   │       │   │       │   │           └── Column
│   │       │   │       │   │               └── Renderer
│   │       │   │       │   └── Product
│   │       │   │       ├── Controller
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       └── Report
│   │       │   │       │           ├── Customer
│   │       │   │       │           └── Product
│   │       │   │       ├── Helper
│   │       │   │       ├── Model
│   │       │   │       │   ├── Plugin
│   │       │   │       │   ├── Product
│   │       │   │       │   │   └── Index
│   │       │   │       │   └── ResourceModel
│   │       │   │       │       ├── Event
│   │       │   │       │       ├── Order
│   │       │   │       │       ├── Product
│   │       │   │       │       │   └── Sold
│   │       │   │       │       │       └── Collection
│   │       │   │       │       ├── Quote
│   │       │   │       │       └── Report
│   │       │   │       │           ├── Collection
│   │       │   │       │           ├── Product
│   │       │   │       │           └── Quote
│   │       │   │       └── Observer
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   │   ├── report
│   │       │       │   │   │   ├── grid
│   │       │       │   │   │   └── refresh
│   │       │       │   │   └── store
│   │       │       │   │       └── switcher
│   │       │       │   └── web
│   │       │       │       └── images
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   ├── js
│   │       │           │   ├── product
│   │       │           │   │   └── widget
│   │       │           │   │       └── viewed
│   │       │           │   └── widget
│   │       │           │       ├── compared
│   │       │           │       │   ├── column
│   │       │           │       │   └── content
│   │       │           │       └── viewed
│   │       │           │           ├── column
│   │       │           │           └── content
│   │       │           └── web
│   │       │               └── js
│   │       ├── RequireJs
│   │       │   ├── Block
│   │       │   │   └── Html
│   │       │   │       └── Head
│   │       │   ├── etc
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   └── Test
│   │       │       ├── Mftf
│   │       │       └── Unit
│   │       │           ├── Block
│   │       │           │   └── Html
│   │       │           │       └── Head
│   │       │           └── Model
│   │       ├── Review
│   │       │   ├── Block
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Add
│   │       │   │   │   ├── Edit
│   │       │   │   │   ├── Grid
│   │       │   │   │   │   ├── Filter
│   │       │   │   │   │   └── Renderer
│   │       │   │   │   ├── Product
│   │       │   │   │   │   └── Edit
│   │       │   │   │   │       └── Tab
│   │       │   │   │   ├── Rating
│   │       │   │   │   │   └── Edit
│   │       │   │   │   │       └── Tab
│   │       │   │   │   └── Rss
│   │       │   │   │       └── Grid
│   │       │   │   ├── Customer
│   │       │   │   ├── Form
│   │       │   │   ├── Product
│   │       │   │   │   ├── Compare
│   │       │   │   │   │   └── ListCompare
│   │       │   │   │   │       └── Plugin
│   │       │   │   │   └── View
│   │       │   │   └── Rating
│   │       │   │       └── Entity
│   │       │   ├── Controller
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Product
│   │       │   │   │   │   └── Reviews
│   │       │   │   │   └── Rating
│   │       │   │   ├── Customer
│   │       │   │   └── Product
│   │       │   ├── CustomerData
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Helper
│   │       │   │   └── Action
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Rating
│   │       │   │   │   └── Option
│   │       │   │   ├── ResourceModel
│   │       │   │   │   ├── Rating
│   │       │   │   │   │   ├── Grid
│   │       │   │   │   │   └── Option
│   │       │   │   │   │       └── Vote
│   │       │   │   │   └── Review
│   │       │   │   │       ├── Product
│   │       │   │   │       ├── Status
│   │       │   │   │       └── Summary
│   │       │   │   └── Review
│   │       │   ├── Observer
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── Data
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   ├── Rating
│   │       │   │       │   │   │   └── Edit
│   │       │   │       │   │   │       └── Tab
│   │       │   │       │   │   └── Rss
│   │       │   │       │   │       └── Grid
│   │       │   │       │   ├── Customer
│   │       │   │       │   └── Product
│   │       │   │       ├── Controller
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   └── Product
│   │       │   │       │   └── Product
│   │       │   │       ├── Helper
│   │       │   │       │   └── Action
│   │       │   │       ├── Model
│   │       │   │       │   └── ResourceModel
│   │       │   │       │       └── Review
│   │       │   │       │           ├── Product
│   │       │   │       │           └── Summary
│   │       │   │       ├── Observer
│   │       │   │       └── Ui
│   │       │   │           ├── Component
│   │       │   │           │   └── Listing
│   │       │   │           │       └── Columns
│   │       │   │           └── DataProvider
│   │       │   │               └── Product
│   │       │   │                   └── Form
│   │       │   │                       └── Modifier
│   │       │   ├── Ui
│   │       │   │   ├── Component
│   │       │   │   │   └── Listing
│   │       │   │   │       └── Columns
│   │       │   │   └── DataProvider
│   │       │   │       └── Product
│   │       │   │           ├── Form
│   │       │   │           │   └── Modifier
│   │       │   │           └── Listing
│   │       │   │               └── Collector
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   │   ├── rating
│   │       │       │   │   │   └── stars
│   │       │       │   │   └── rss
│   │       │       │   │       └── grid
│   │       │       │   ├── ui_component
│   │       │       │   └── web
│   │       │       │       └── js
│   │       │       ├── base
│   │       │       │   └── ui_component
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   ├── customer
│   │       │           │   ├── helper
│   │       │           │   └── product
│   │       │           │       └── view
│   │       │           ├── ui_component
│   │       │           └── web
│   │       │               └── js
│   │       │                   └── view
│   │       ├── ReviewAnalytics
│   │       │   ├── etc
│   │       │   └── Test
│   │       │       └── Mftf
│   │       ├── Robots
│   │       │   ├── Block
│   │       │   ├── Controller
│   │       │   │   └── Index
│   │       │   ├── etc
│   │       │   │   └── frontend
│   │       │   ├── Model
│   │       │   │   └── Config
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       ├── Controller
│   │       │   │       │   └── Index
│   │       │   │       └── Model
│   │       │   │           └── Config
│   │       │   └── view
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── page_layout
│   │       │           └── templates
│   │       ├── Rss
│   │       │   ├── App
│   │       │   │   └── Action
│   │       │   │       └── Plugin
│   │       │   ├── Block
│   │       │   ├── Controller
│   │       │   │   ├── Adminhtml
│   │       │   │   │   └── Feed
│   │       │   │   ├── Feed
│   │       │   │   └── Index
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   └── System
│   │       │   │       └── Config
│   │       │   │           └── Backend
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       ├── App
│   │       │   │       │   └── Action
│   │       │   │       │       └── Plugin
│   │       │   │       ├── Block
│   │       │   │       ├── Controller
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   └── Feed
│   │       │   │       │   └── Feed
│   │       │   │       └── Model
│   │       │   └── view
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           └── templates
│   │       ├── Rule
│   │       │   ├── Block
│   │       │   ├── etc
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Action
│   │       │   │   ├── Condition
│   │       │   │   │   ├── Product
│   │       │   │   │   └── Sql
│   │       │   │   ├── Renderer
│   │       │   │   └── ResourceModel
│   │       │   │       └── Rule
│   │       │   │           └── Collection
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       └── Model
│   │       │   │           ├── Condition
│   │       │   │           │   ├── Product
│   │       │   │           │   └── Sql
│   │       │   │           ├── Renderer
│   │       │   │           └── ResourceModel
│   │       │   │               └── Rule
│   │       │   │                   └── Collection
│   │       │   └── view
│   │       │       └── adminhtml
│   │       │           └── web
│   │       ├── Sales
│   │       │   ├── Api
│   │       │   │   ├── Data
│   │       │   │   └── Exception
│   │       │   ├── Block
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Items
│   │       │   │   │   │   ├── Column
│   │       │   │   │   │   └── Renderer
│   │       │   │   │   ├── Order
│   │       │   │   │   │   ├── Address
│   │       │   │   │   │   ├── Comments
│   │       │   │   │   │   ├── Create
│   │       │   │   │   │   │   ├── Billing
│   │       │   │   │   │   │   │   └── Method
│   │       │   │   │   │   │   ├── Coupons
│   │       │   │   │   │   │   ├── Form
│   │       │   │   │   │   │   ├── Giftmessage
│   │       │   │   │   │   │   ├── Items
│   │       │   │   │   │   │   ├── Newsletter
│   │       │   │   │   │   │   ├── Search
│   │       │   │   │   │   │   │   └── Grid
│   │       │   │   │   │   │   │       ├── DataProvider
│   │       │   │   │   │   │   │       └── Renderer
│   │       │   │   │   │   │   ├── Shipping
│   │       │   │   │   │   │   │   └── Method
│   │       │   │   │   │   │   ├── Sidebar
│   │       │   │   │   │   │   ├── Store
│   │       │   │   │   │   │   └── Totals
│   │       │   │   │   │   ├── Creditmemo
│   │       │   │   │   │   │   ├── Create
│   │       │   │   │   │   │   └── View
│   │       │   │   │   │   ├── Invoice
│   │       │   │   │   │   │   ├── Create
│   │       │   │   │   │   │   └── View
│   │       │   │   │   │   ├── Status
│   │       │   │   │   │   │   ├── Assign
│   │       │   │   │   │   │   ├── Edit
│   │       │   │   │   │   │   └── NewStatus
│   │       │   │   │   │   ├── Totals
│   │       │   │   │   │   └── View
│   │       │   │   │   │       ├── Items
│   │       │   │   │   │       │   └── Renderer
│   │       │   │   │   │       └── Tab
│   │       │   │   │   ├── Reorder
│   │       │   │   │   │   └── Renderer
│   │       │   │   │   ├── Report
│   │       │   │   │   │   └── Filter
│   │       │   │   │   │       └── Form
│   │       │   │   │   ├── Rss
│   │       │   │   │   │   └── Order
│   │       │   │   │   │       └── Grid
│   │       │   │   │   ├── System
│   │       │   │   │   │   └── Config
│   │       │   │   │   │       └── Form
│   │       │   │   │   │           └── Fieldset
│   │       │   │   │   │               └── Order
│   │       │   │   │   └── Transactions
│   │       │   │   │       └── Detail
│   │       │   │   ├── Guest
│   │       │   │   ├── Items
│   │       │   │   ├── Order
│   │       │   │   │   ├── Creditmemo
│   │       │   │   │   ├── Email
│   │       │   │   │   │   ├── Creditmemo
│   │       │   │   │   │   ├── Invoice
│   │       │   │   │   │   ├── Items
│   │       │   │   │   │   │   └── Order
│   │       │   │   │   │   └── Shipment
│   │       │   │   │   ├── History
│   │       │   │   │   ├── Info
│   │       │   │   │   │   └── Buttons
│   │       │   │   │   ├── Invoice
│   │       │   │   │   ├── Item
│   │       │   │   │   │   └── Renderer
│   │       │   │   │   └── PrintOrder
│   │       │   │   ├── Reorder
│   │       │   │   ├── Status
│   │       │   │   │   └── Grid
│   │       │   │   │       └── Column
│   │       │   │   └── Widget
│   │       │   │       └── Guest
│   │       │   ├── Console
│   │       │   │   └── Command
│   │       │   ├── Controller
│   │       │   │   ├── AbstractController
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Creditmemo
│   │       │   │   │   │   └── AbstractCreditmemo
│   │       │   │   │   ├── Invoice
│   │       │   │   │   │   └── AbstractInvoice
│   │       │   │   │   ├── Order
│   │       │   │   │   │   ├── Create
│   │       │   │   │   │   ├── Creditmemo
│   │       │   │   │   │   ├── Edit
│   │       │   │   │   │   ├── Invoice
│   │       │   │   │   │   ├── Status
│   │       │   │   │   │   └── View
│   │       │   │   │   │       └── Giftmessage
│   │       │   │   │   ├── Shipment
│   │       │   │   │   │   └── AbstractShipment
│   │       │   │   │   └── Transactions
│   │       │   │   ├── Download
│   │       │   │   ├── Guest
│   │       │   │   └── Order
│   │       │   │       └── Plugin
│   │       │   ├── Cron
│   │       │   ├── CustomerData
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   ├── frontend
│   │       │   │   ├── webapi_rest
│   │       │   │   └── webapi_soap
│   │       │   ├── Exception
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── AdminOrder
│   │       │   │   │   └── Product
│   │       │   │   │       └── Quote
│   │       │   │   ├── Config
│   │       │   │   │   ├── Backend
│   │       │   │   │   │   ├── Email
│   │       │   │   │   │   └── Grid
│   │       │   │   │   └── Source
│   │       │   │   │       └── Order
│   │       │   │   │           └── Status
│   │       │   │   ├── Convert
│   │       │   │   ├── CronJob
│   │       │   │   ├── Grid
│   │       │   │   │   └── Child
│   │       │   │   ├── Order
│   │       │   │   │   ├── Address
│   │       │   │   │   ├── Admin
│   │       │   │   │   ├── Creditmemo
│   │       │   │   │   │   ├── Comment
│   │       │   │   │   │   ├── Item
│   │       │   │   │   │   │   └── Validation
│   │       │   │   │   │   ├── Sender
│   │       │   │   │   │   ├── Total
│   │       │   │   │   │   └── Validation
│   │       │   │   │   ├── Email
│   │       │   │   │   │   ├── Container
│   │       │   │   │   │   └── Sender
│   │       │   │   │   ├── Grid
│   │       │   │   │   │   ├── Massaction
│   │       │   │   │   │   └── Row
│   │       │   │   │   ├── Invoice
│   │       │   │   │   │   ├── Comment
│   │       │   │   │   │   ├── Grid
│   │       │   │   │   │   │   └── Row
│   │       │   │   │   │   ├── Plugin
│   │       │   │   │   │   ├── Sender
│   │       │   │   │   │   ├── Total
│   │       │   │   │   │   └── Validation
│   │       │   │   │   ├── Payment
│   │       │   │   │   │   ├── Operations
│   │       │   │   │   │   ├── State
│   │       │   │   │   │   └── Transaction
│   │       │   │   │   ├── Pdf
│   │       │   │   │   │   ├── Config
│   │       │   │   │   │   ├── Items
│   │       │   │   │   │   │   ├── Creditmemo
│   │       │   │   │   │   │   ├── Invoice
│   │       │   │   │   │   │   └── Shipment
│   │       │   │   │   │   └── Total
│   │       │   │   │   ├── Reorder
│   │       │   │   │   ├── Shipment
│   │       │   │   │   │   ├── Comment
│   │       │   │   │   │   ├── Sender
│   │       │   │   │   │   ├── Track
│   │       │   │   │   │   └── Validation
│   │       │   │   │   ├── ShipmentDocumentFactory
│   │       │   │   │   ├── Status
│   │       │   │   │   │   └── History
│   │       │   │   │   ├── Tax
│   │       │   │   │   ├── Total
│   │       │   │   │   │   └── Config
│   │       │   │   │   ├── Validation
│   │       │   │   │   └── Webapi
│   │       │   │   ├── ResourceModel
│   │       │   │   │   ├── Collection
│   │       │   │   │   ├── Grid
│   │       │   │   │   ├── Order
│   │       │   │   │   │   ├── Address
│   │       │   │   │   │   ├── Attribute
│   │       │   │   │   │   │   └── Backend
│   │       │   │   │   │   ├── Collection
│   │       │   │   │   │   ├── Comment
│   │       │   │   │   │   │   └── Collection
│   │       │   │   │   │   ├── Creditmemo
│   │       │   │   │   │   │   ├── Attribute
│   │       │   │   │   │   │   │   └── Backend
│   │       │   │   │   │   │   ├── Comment
│   │       │   │   │   │   │   ├── Grid
│   │       │   │   │   │   │   ├── Item
│   │       │   │   │   │   │   ├── Order
│   │       │   │   │   │   │   │   └── Grid
│   │       │   │   │   │   │   └── Relation
│   │       │   │   │   │   ├── Customer
│   │       │   │   │   │   ├── Grid
│   │       │   │   │   │   ├── Handler
│   │       │   │   │   │   ├── Invoice
│   │       │   │   │   │   │   ├── Attribute
│   │       │   │   │   │   │   │   └── Backend
│   │       │   │   │   │   │   ├── Comment
│   │       │   │   │   │   │   ├── Grid
│   │       │   │   │   │   │   ├── Item
│   │       │   │   │   │   │   └── Orders
│   │       │   │   │   │   │       └── Grid
│   │       │   │   │   │   ├── Item
│   │       │   │   │   │   ├── Payment
│   │       │   │   │   │   │   └── Transaction
│   │       │   │   │   │   ├── Plugin
│   │       │   │   │   │   ├── Rss
│   │       │   │   │   │   ├── Shipment
│   │       │   │   │   │   │   ├── Attribute
│   │       │   │   │   │   │   │   └── Backend
│   │       │   │   │   │   │   ├── Comment
│   │       │   │   │   │   │   ├── Grid
│   │       │   │   │   │   │   ├── Item
│   │       │   │   │   │   │   ├── Order
│   │       │   │   │   │   │   │   └── Grid
│   │       │   │   │   │   │   └── Track
│   │       │   │   │   │   ├── Status
│   │       │   │   │   │   │   └── History
│   │       │   │   │   │   └── Tax
│   │       │   │   │   ├── Provider
│   │       │   │   │   ├── Report
│   │       │   │   │   │   ├── Bestsellers
│   │       │   │   │   │   ├── Collection
│   │       │   │   │   │   ├── Invoiced
│   │       │   │   │   │   │   └── Collection
│   │       │   │   │   │   ├── Order
│   │       │   │   │   │   │   └── Updatedat
│   │       │   │   │   │   ├── Refunded
│   │       │   │   │   │   │   └── Collection
│   │       │   │   │   │   └── Shipping
│   │       │   │   │   │       └── Collection
│   │       │   │   │   ├── Sale
│   │       │   │   │   ├── Status
│   │       │   │   │   └── Transaction
│   │       │   │   │       └── Grid
│   │       │   │   ├── Rss
│   │       │   │   ├── Service
│   │       │   │   ├── Spi
│   │       │   │   └── Status
│   │       │   ├── Observer
│   │       │   │   ├── Backend
│   │       │   │   ├── Frontend
│   │       │   │   └── Virtual
│   │       │   ├── Plugin
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Metadata
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   ├── Items
│   │       │   │       │   │   │   └── Column
│   │       │   │       │   │   ├── Order
│   │       │   │       │   │   │   ├── Address
│   │       │   │       │   │   │   ├── Comments
│   │       │   │       │   │   │   ├── Create
│   │       │   │       │   │   │   │   ├── Items
│   │       │   │       │   │   │   │   ├── Search
│   │       │   │       │   │   │   │   │   └── Grid
│   │       │   │       │   │   │   │   │       └── Renderer
│   │       │   │       │   │   │   │   └── Sidebar
│   │       │   │       │   │   │   ├── Creditmemo
│   │       │   │       │   │   │   │   └── Create
│   │       │   │       │   │   │   ├── Invoice
│   │       │   │       │   │   │   ├── Status
│   │       │   │       │   │   │   │   └── Assign
│   │       │   │       │   │   │   ├── Totals
│   │       │   │       │   │   │   └── View
│   │       │   │       │   │   │       └── Tab
│   │       │   │       │   │   │           └── Stub
│   │       │   │       │   │   └── Rss
│   │       │   │       │   │       └── Order
│   │       │   │       │   │           └── Grid
│   │       │   │       │   ├── Guest
│   │       │   │       │   ├── Items
│   │       │   │       │   ├── Order
│   │       │   │       │   │   ├── Create
│   │       │   │       │   │   ├── Email
│   │       │   │       │   │   │   └── Items
│   │       │   │       │   │   │       └── Order
│   │       │   │       │   │   ├── Info
│   │       │   │       │   │   │   └── Buttons
│   │       │   │       │   │   └── Item
│   │       │   │       │   │       └── Renderer
│   │       │   │       │   ├── Reorder
│   │       │   │       │   └── Status
│   │       │   │       │       └── Grid
│   │       │   │       │           └── Column
│   │       │   │       ├── Controller
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   ├── Creditmemo
│   │       │   │       │   │   │   └── AbstractCreditmemo
│   │       │   │       │   │   ├── Invoice
│   │       │   │       │   │   │   └── AbstractInvoice
│   │       │   │       │   │   └── Order
│   │       │   │       │   │       ├── Create
│   │       │   │       │   │       ├── Creditmemo
│   │       │   │       │   │       └── Invoice
│   │       │   │       │   ├── Download
│   │       │   │       │   └── Guest
│   │       │   │       ├── Cron
│   │       │   │       ├── CustomerData
│   │       │   │       ├── Helper
│   │       │   │       ├── Model
│   │       │   │       │   ├── AdminOrder
│   │       │   │       │   │   └── Product
│   │       │   │       │   │       └── Quote
│   │       │   │       │   ├── Config
│   │       │   │       │   │   ├── Backend
│   │       │   │       │   │   │   ├── Email
│   │       │   │       │   │   │   └── Grid
│   │       │   │       │   │   ├── _files
│   │       │   │       │   │   └── Source
│   │       │   │       │   │       └── Order
│   │       │   │       │   ├── CronJob
│   │       │   │       │   ├── Grid
│   │       │   │       │   │   └── Child
│   │       │   │       │   ├── Order
│   │       │   │       │   │   ├── Address
│   │       │   │       │   │   ├── Admin
│   │       │   │       │   │   ├── Creditmemo
│   │       │   │       │   │   │   ├── Comment
│   │       │   │       │   │   │   ├── Item
│   │       │   │       │   │   │   │   └── Validation
│   │       │   │       │   │   │   ├── Sender
│   │       │   │       │   │   │   ├── Total
│   │       │   │       │   │   │   └── Validation
│   │       │   │       │   │   ├── Email
│   │       │   │       │   │   │   ├── Container
│   │       │   │       │   │   │   ├── Sender
│   │       │   │       │   │   │   └── Stub
│   │       │   │       │   │   ├── Grid
│   │       │   │       │   │   │   ├── Massaction
│   │       │   │       │   │   │   └── Row
│   │       │   │       │   │   ├── Invoice
│   │       │   │       │   │   │   ├── Comment
│   │       │   │       │   │   │   ├── Grid
│   │       │   │       │   │   │   │   └── Row
│   │       │   │       │   │   │   ├── Plugin
│   │       │   │       │   │   │   ├── Sender
│   │       │   │       │   │   │   ├── Total
│   │       │   │       │   │   │   └── Validation
│   │       │   │       │   │   ├── Payment
│   │       │   │       │   │   │   ├── Operations
│   │       │   │       │   │   │   ├── State
│   │       │   │       │   │   │   └── Transaction
│   │       │   │       │   │   ├── Pdf
│   │       │   │       │   │   │   ├── Config
│   │       │   │       │   │   │   │   └── _files
│   │       │   │       │   │   │   └── Total
│   │       │   │       │   │   ├── Reorder
│   │       │   │       │   │   ├── Shipment
│   │       │   │       │   │   │   ├── Comment
│   │       │   │       │   │   │   ├── Plugin
│   │       │   │       │   │   │   ├── Sender
│   │       │   │       │   │   │   ├── Track
│   │       │   │       │   │   │   └── Validation
│   │       │   │       │   │   ├── Status
│   │       │   │       │   │   │   └── History
│   │       │   │       │   │   ├── Total
│   │       │   │       │   │   │   └── Config
│   │       │   │       │   │   └── Validation
│   │       │   │       │   ├── ResourceModel
│   │       │   │       │   │   ├── Order
│   │       │   │       │   │   │   ├── Creditmemo
│   │       │   │       │   │   │   │   └── Relation
│   │       │   │       │   │   │   ├── Handler
│   │       │   │       │   │   │   ├── Invoice
│   │       │   │       │   │   │   ├── Plugin
│   │       │   │       │   │   │   ├── Shipment
│   │       │   │       │   │   │   ├── Status
│   │       │   │       │   │   │   │   └── History
│   │       │   │       │   │   │   └── Tax
│   │       │   │       │   │   └── Provider
│   │       │   │       │   ├── Rss
│   │       │   │       │   ├── Service
│   │       │   │       │   └── Status
│   │       │   │       ├── Observer
│   │       │   │       │   ├── Backend
│   │       │   │       │   └── Frontend
│   │       │   │       ├── Setup
│   │       │   │       └── Ui
│   │       │   │           └── Component
│   │       │   │               ├── DataProvider
│   │       │   │               └── Listing
│   │       │   │                   └── Column
│   │       │   │                       └── Status
│   │       │   ├── Ui
│   │       │   │   └── Component
│   │       │   │       ├── Control
│   │       │   │       ├── DataProvider
│   │       │   │       └── Listing
│   │       │   │           └── Column
│   │       │   │               ├── Creditmemo
│   │       │   │               │   └── State
│   │       │   │               ├── Invoice
│   │       │   │               │   └── State
│   │       │   │               └── Status
│   │       │   ├── view
│   │       │   │   ├── adminhtml
│   │       │   │   │   ├── layout
│   │       │   │   │   ├── templates
│   │       │   │   │   │   ├── items
│   │       │   │   │   │   │   ├── column
│   │       │   │   │   │   │   ├── price
│   │       │   │   │   │   │   └── renderer
│   │       │   │   │   │   ├── order
│   │       │   │   │   │   │   ├── address
│   │       │   │   │   │   │   ├── comments
│   │       │   │   │   │   │   ├── create
│   │       │   │   │   │   │   │   ├── billing
│   │       │   │   │   │   │   │   │   └── method
│   │       │   │   │   │   │   │   ├── coupons
│   │       │   │   │   │   │   │   ├── form
│   │       │   │   │   │   │   │   ├── items
│   │       │   │   │   │   │   │   │   └── price
│   │       │   │   │   │   │   │   ├── newsletter
│   │       │   │   │   │   │   │   ├── shipping
│   │       │   │   │   │   │   │   │   └── method
│   │       │   │   │   │   │   │   ├── sidebar
│   │       │   │   │   │   │   │   ├── store
│   │       │   │   │   │   │   │   └── totals
│   │       │   │   │   │   │   ├── creditmemo
│   │       │   │   │   │   │   │   ├── create
│   │       │   │   │   │   │   │   │   ├── items
│   │       │   │   │   │   │   │   │   │   └── renderer
│   │       │   │   │   │   │   │   │   └── totals
│   │       │   │   │   │   │   │   └── view
│   │       │   │   │   │   │   │       └── items
│   │       │   │   │   │   │   │           └── renderer
│   │       │   │   │   │   │   ├── invoice
│   │       │   │   │   │   │   │   ├── create
│   │       │   │   │   │   │   │   │   └── items
│   │       │   │   │   │   │   │   │       └── renderer
│   │       │   │   │   │   │   │   └── view
│   │       │   │   │   │   │   │       └── items
│   │       │   │   │   │   │   │           └── renderer
│   │       │   │   │   │   │   ├── totals
│   │       │   │   │   │   │   └── view
│   │       │   │   │   │   │       ├── items
│   │       │   │   │   │   │       │   └── renderer
│   │       │   │   │   │   │       └── tab
│   │       │   │   │   │   ├── page
│   │       │   │   │   │   │   └── js
│   │       │   │   │   │   ├── rss
│   │       │   │   │   │   │   └── order
│   │       │   │   │   │   │       └── grid
│   │       │   │   │   │   └── transactions
│   │       │   │   │   ├── ui_component
│   │       │   │   │   └── web
│   │       │   │   │       ├── js
│   │       │   │   │       │   └── bootstrap
│   │       │   │   │       ├── order
│   │       │   │   │       │   ├── create
│   │       │   │   │       │   ├── edit
│   │       │   │   │       │   │   └── address
│   │       │   │   │       │   └── view
│   │       │   │   │       └── templates
│   │       │   │   │           └── order
│   │       │   │   │               └── create
│   │       │   │   │                   ├── payment
│   │       │   │   │                   └── shipping
│   │       │   │   ├── base
│   │       │   │   │   └── ui_component
│   │       │   │   └── frontend
│   │       │   │       ├── email
│   │       │   │       ├── layout
│   │       │   │       ├── templates
│   │       │   │       │   ├── email
│   │       │   │       │   │   ├── creditmemo
│   │       │   │       │   │   ├── invoice
│   │       │   │       │   │   ├── items
│   │       │   │       │   │   │   ├── creditmemo
│   │       │   │       │   │   │   ├── invoice
│   │       │   │       │   │   │   ├── order
│   │       │   │       │   │   │   ├── price
│   │       │   │       │   │   │   └── shipment
│   │       │   │       │   │   └── shipment
│   │       │   │       │   ├── guest
│   │       │   │       │   ├── items
│   │       │   │       │   │   └── price
│   │       │   │       │   ├── js
│   │       │   │       │   ├── order
│   │       │   │       │   │   ├── creditmemo
│   │       │   │       │   │   │   └── items
│   │       │   │       │   │   │       └── renderer
│   │       │   │       │   │   ├── info
│   │       │   │       │   │   │   └── buttons
│   │       │   │       │   │   ├── invoice
│   │       │   │       │   │   │   └── items
│   │       │   │       │   │   │       └── renderer
│   │       │   │       │   │   ├── items
│   │       │   │       │   │   │   └── renderer
│   │       │   │       │   │   ├── print
│   │       │   │       │   │   └── shipment
│   │       │   │       │   │       └── items
│   │       │   │       │   │           └── renderer
│   │       │   │       │   ├── reorder
│   │       │   │       │   └── widget
│   │       │   │       │       └── guest
│   │       │   │       └── web
│   │       │   │           └── js
│   │       │   │               └── view
│   │       │   └── ViewModel
│   │       │       └── Customer
│   │       ├── SalesAnalytics
│   │       │   ├── etc
│   │       │   └── Test
│   │       │       └── Mftf
│   │       ├── SalesGraphQl
│   │       │   ├── etc
│   │       │   └── Model
│   │       │       └── Resolver
│   │       ├── SalesInventory
│   │       │   ├── etc
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Order
│   │       │   │   └── Plugin
│   │       │   │       └── Order
│   │       │   │           └── Validation
│   │       │   ├── Observer
│   │       │   └── Test
│   │       │       ├── Mftf
│   │       │       └── Unit
│   │       │           ├── Model
│   │       │           │   ├── Order
│   │       │           │   └── Plugin
│   │       │           │       └── Order
│   │       │           │           └── Validation
│   │       │           └── Observer
│   │       ├── SalesRule
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   ├── Block
│   │       │   │   ├── Adminhtml
│   │       │   │   │   └── Promo
│   │       │   │   │       ├── Quote
│   │       │   │   │       │   └── Edit
│   │       │   │   │       │       └── Tab
│   │       │   │   │       │           └── Coupons
│   │       │   │   │       │               └── Grid
│   │       │   │   │       │                   └── Column
│   │       │   │   │       │                       └── Renderer
│   │       │   │   │       └── Widget
│   │       │   │   ├── Rss
│   │       │   │   └── Widget
│   │       │   │       └── Form
│   │       │   │           └── Element
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       └── Promo
│   │       │   │           ├── Quote
│   │       │   │           └── Widget
│   │       │   ├── Cron
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Converter
│   │       │   │   ├── Coupon
│   │       │   │   ├── Data
│   │       │   │   ├── Plugin
│   │       │   │   │   └── ResourceModel
│   │       │   │   ├── Quote
│   │       │   │   │   └── Address
│   │       │   │   │       └── Total
│   │       │   │   ├── ResourceModel
│   │       │   │   │   ├── Coupon
│   │       │   │   │   ├── Report
│   │       │   │   │   │   ├── Rule
│   │       │   │   │   │   └── Updatedat
│   │       │   │   │   └── Rule
│   │       │   │   │       ├── Customer
│   │       │   │   │       └── Quote
│   │       │   │   ├── Rss
│   │       │   │   ├── Rule
│   │       │   │   │   ├── Action
│   │       │   │   │   │   └── Discount
│   │       │   │   │   ├── Condition
│   │       │   │   │   │   └── Product
│   │       │   │   │   └── Metadata
│   │       │   │   ├── Service
│   │       │   │   ├── Spi
│   │       │   │   ├── System
│   │       │   │   │   └── Config
│   │       │   │   │       └── Source
│   │       │   │   │           └── Coupon
│   │       │   │   └── Validator
│   │       │   ├── Observer
│   │       │   ├── Plugin
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Metadata
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   └── Promo
│   │       │   │       │   │       └── Quote
│   │       │   │       │   │           └── Edit
│   │       │   │       │   └── Rss
│   │       │   │       ├── Controller
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       └── Promo
│   │       │   │       │           └── Quote
│   │       │   │       ├── Cron
│   │       │   │       ├── Helper
│   │       │   │       ├── Model
│   │       │   │       │   ├── Converter
│   │       │   │       │   ├── Coupon
│   │       │   │       │   ├── _files
│   │       │   │       │   ├── Plugin
│   │       │   │       │   │   └── ResourceModel
│   │       │   │       │   ├── Quote
│   │       │   │       │   ├── ResourceModel
│   │       │   │       │   │   ├── Report
│   │       │   │       │   │   └── Rule
│   │       │   │       │   ├── Rss
│   │       │   │       │   ├── Rule
│   │       │   │       │   │   ├── Action
│   │       │   │       │   │   │   └── Discount
│   │       │   │       │   │   ├── Condition
│   │       │   │       │   │   └── Metadata
│   │       │   │       │   │       └── _files
│   │       │   │       │   ├── Service
│   │       │   │       │   ├── System
│   │       │   │       │   │   └── Config
│   │       │   │       │   │       └── Source
│   │       │   │       │   │           └── Coupon
│   │       │   │       │   └── Validator
│   │       │   │       └── Observer
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   │   ├── promo
│   │       │       │   │   └── tab
│   │       │       │   ├── ui_component
│   │       │       │   └── web
│   │       │       │       └── js
│   │       │       │           └── form
│   │       │       │               └── element
│   │       │       ├── base
│   │       │       │   └── web
│   │       │       │       └── js
│   │       │       │           └── form
│   │       │       │               └── element
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           └── web
│   │       │               ├── js
│   │       │               │   ├── action
│   │       │               │   ├── model
│   │       │               │   │   └── payment
│   │       │               │   └── view
│   │       │               │       ├── cart
│   │       │               │       │   └── totals
│   │       │               │       ├── payment
│   │       │               │       └── summary
│   │       │               └── template
│   │       │                   ├── cart
│   │       │                   │   └── totals
│   │       │                   ├── payment
│   │       │                   └── summary
│   │       ├── SalesSequence
│   │       │   ├── etc
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   └── ResourceModel
│   │       │   ├── Observer
│   │       │   ├── Setup
│   │       │   └── Test
│   │       │       ├── Mftf
│   │       │       └── Unit
│   │       │           └── Model
│   │       │               └── ResourceModel
│   │       ├── SampleData
│   │       │   ├── Console
│   │       │   │   └── Command
│   │       │   ├── etc
│   │       │   ├── Model
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   └── Test
│   │       │       ├── Mftf
│   │       │       └── Unit
│   │       │           ├── Console
│   │       │           │   └── Command
│   │       │           └── Model
│   │       ├── Search
│   │       │   ├── Adapter
│   │       │   │   └── Query
│   │       │   │       └── Preprocessor
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   ├── Block
│   │       │   │   └── Adminhtml
│   │       │   │       ├── Dashboard
│   │       │   │       ├── Reports
│   │       │   │       ├── Synonyms
│   │       │   │       │   └── Edit
│   │       │   │       └── Term
│   │       │   │           └── Edit
│   │       │   ├── Controller
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Synonyms
│   │       │   │   │   └── Term
│   │       │   │   ├── Ajax
│   │       │   │   └── Term
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Adminhtml
│   │       │   │   │   └── System
│   │       │   │   │       └── Config
│   │       │   │   │           └── Source
│   │       │   │   ├── Autocomplete
│   │       │   │   ├── ResourceModel
│   │       │   │   │   ├── Query
│   │       │   │   │   └── SynonymGroup
│   │       │   │   ├── Search
│   │       │   │   ├── SearchEngine
│   │       │   │   │   └── Config
│   │       │   │   └── Synonym
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Metadata
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Adapter
│   │       │   │       │   └── Query
│   │       │   │       │       └── Preprocessor
│   │       │   │       ├── Controller
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       ├── Ajax
│   │       │   │       │       ├── Synonyms
│   │       │   │       │       └── Term
│   │       │   │       ├── Helper
│   │       │   │       └── Model
│   │       │   │           ├── ResourceModel
│   │       │   │           ├── Search
│   │       │   │           └── SearchEngine
│   │       │   ├── Ui
│   │       │   │   └── Component
│   │       │   │       └── Listing
│   │       │   │           └── Column
│   │       │   │               ├── Scope
│   │       │   │               ├── Store
│   │       │   │               └── Website
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   └── ui_component
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           └── web
│   │       │               └── js
│   │       ├── Security
│   │       │   ├── Block
│   │       │   │   └── Adminhtml
│   │       │   │       └── Session
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       └── Session
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Config
│   │       │   │   │   └── Source
│   │       │   │   ├── Plugin
│   │       │   │   ├── ResourceModel
│   │       │   │   │   ├── AdminSessionInfo
│   │       │   │   │   └── PasswordResetRequestEvent
│   │       │   │   └── SecurityChecker
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       └── Session
│   │       │   │       ├── Controller
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       └── Session
│   │       │   │       └── Model
│   │       │   │           ├── Config
│   │       │   │           │   └── Source
│   │       │   │           ├── Plugin
│   │       │   │           ├── ResourceModel
│   │       │   │           │   ├── AdminSessionInfo
│   │       │   │           │   └── PasswordResetRequestEvent
│   │       │   │           └── SecurityChecker
│   │       │   └── view
│   │       │       └── adminhtml
│   │       │           ├── layout
│   │       │           ├── page_layout
│   │       │           ├── templates
│   │       │           │   ├── page
│   │       │           │   └── session
│   │       │           └── web
│   │       │               ├── css
│   │       │               └── js
│   │       ├── SendFriend
│   │       │   ├── Block
│   │       │   │   └── Plugin
│   │       │   │       └── Catalog
│   │       │   │           └── Product
│   │       │   ├── Controller
│   │       │   │   └── Product
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── ResourceModel
│   │       │   │   │   └── SendFriend
│   │       │   │   └── Source
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   └── Plugin
│   │       │   │       │       └── Catalog
│   │       │   │       │           └── Product
│   │       │   │       └── Model
│   │       │   └── view
│   │       │       └── frontend
│   │       │           ├── email
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           └── web
│   │       │               └── js
│   │       ├── SendFriendGraphQl
│   │       │   ├── etc
│   │       │   └── Model
│   │       │       └── Resolver
│   │       ├── Shipping
│   │       │   ├── Block
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Create
│   │       │   │   │   ├── Order
│   │       │   │   │   │   ├── Packaging
│   │       │   │   │   │   └── Tracking
│   │       │   │   │   └── View
│   │       │   │   ├── DataProviders
│   │       │   │   │   └── Tracking
│   │       │   │   ├── Order
│   │       │   │   └── Tracking
│   │       │   ├── Controller
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Order
│   │       │   │   │   │   └── Shipment
│   │       │   │   │   └── Shipment
│   │       │   │   └── Tracking
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Carrier
│   │       │   │   │   └── Source
│   │       │   │   ├── Config
│   │       │   │   │   └── Source
│   │       │   │   │       └── Online
│   │       │   │   ├── Order
│   │       │   │   │   └── Pdf
│   │       │   │   ├── Rate
│   │       │   │   ├── ResourceModel
│   │       │   │   │   └── Order
│   │       │   │   │       └── Track
│   │       │   │   ├── Shipment
│   │       │   │   ├── Shipping
│   │       │   │   ├── Simplexml
│   │       │   │   ├── Source
│   │       │   │   └── Tracking
│   │       │   │       └── Result
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Metadata
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       └── Order
│   │       │   │       ├── Controller
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       └── Order
│   │       │   │       │           └── Shipment
│   │       │   │       ├── Helper
│   │       │   │       └── Model
│   │       │   │           ├── Carrier
│   │       │   │           │   └── AbstractCarrierOnline
│   │       │   │           ├── Order
│   │       │   │           ├── Shipping
│   │       │   │           └── Simplexml
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   │   ├── create
│   │       │       │   │   │   └── items
│   │       │       │   │   │       └── renderer
│   │       │       │   │   ├── order
│   │       │       │   │   │   ├── packaging
│   │       │       │   │   │   ├── tracking
│   │       │       │   │   │   └── view
│   │       │       │   │   └── view
│   │       │       │   │       └── items
│   │       │       │   │           └── renderer
│   │       │       │   └── web
│   │       │       │       ├── js
│   │       │       │       └── order
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   ├── order
│   │       │           │   └── tracking
│   │       │           └── web
│   │       │               ├── js
│   │       │               │   ├── model
│   │       │               │   └── view
│   │       │               │       └── checkout
│   │       │               │           └── shipping
│   │       │               └── template
│   │       │                   └── checkout
│   │       │                       └── shipping
│   │       ├── Signifyd
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   ├── Block
│   │       │   │   └── Adminhtml
│   │       │   │       └── System
│   │       │   │           └── Config
│   │       │   │               ├── Field
│   │       │   │               └── Fieldset
│   │       │   ├── Controller
│   │       │   │   └── Webhooks
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── CaseServices
│   │       │   │   ├── Guarantee
│   │       │   │   ├── MessageGenerators
│   │       │   │   ├── PaymentMethodMapper
│   │       │   │   ├── QuoteSession
│   │       │   │   │   └── Adminhtml
│   │       │   │   ├── ResourceModel
│   │       │   │   │   └── CaseEntity
│   │       │   │   ├── SalesOrderGrid
│   │       │   │   └── SignifydGateway
│   │       │   │       ├── Client
│   │       │   │       ├── Debugger
│   │       │   │       ├── Request
│   │       │   │       └── Response
│   │       │   ├── Observer
│   │       │   ├── Plugin
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   └── Adminhtml
│   │       │   │       ├── Controller
│   │       │   │       │   └── Webhooks
│   │       │   │       ├── Model
│   │       │   │       │   ├── CaseServices
│   │       │   │       │   ├── Guarantee
│   │       │   │       │   ├── MessageGenerators
│   │       │   │       │   ├── PaymentMethodMapper
│   │       │   │       │   │   └── _files
│   │       │   │       │   ├── SalesOrderGrid
│   │       │   │       │   └── SignifydGateway
│   │       │   │       │       ├── Client
│   │       │   │       │       └── Response
│   │       │   │       └── Observer
│   │       │   ├── Ui
│   │       │   │   └── Component
│   │       │   │       └── Listing
│   │       │   │           └── Column
│   │       │   │               └── Guarantee
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   ├── ui_component
│   │       │       │   └── web
│   │       │       │       ├── images
│   │       │       │       └── js
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           └── templates
│   │       ├── Sitemap
│   │       │   ├── Block
│   │       │   │   └── Adminhtml
│   │       │   │       ├── Edit
│   │       │   │       └── Grid
│   │       │   │           └── Renderer
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       └── Sitemap
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Config
│   │       │   │   │   ├── Backend
│   │       │   │   │   └── Source
│   │       │   │   ├── ItemProvider
│   │       │   │   ├── ResourceModel
│   │       │   │   │   ├── Catalog
│   │       │   │   │   ├── Cms
│   │       │   │   │   └── Sitemap
│   │       │   │   └── Source
│   │       │   │       └── Product
│   │       │   │           └── Image
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── Data
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       ├── Controller
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       └── Sitemap
│   │       │   │       └── Model
│   │       │   │           ├── Config
│   │       │   │           │   └── Backend
│   │       │   │           ├── _files
│   │       │   │           ├── ItemProvider
│   │       │   │           └── ResourceModel
│   │       │   │               └── Cms
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── email
│   │       │       │   └── layout
│   │       │       └── frontend
│   │       │           └── layout
│   │       ├── Store
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   ├── App
│   │       │   │   ├── Action
│   │       │   │   │   └── Plugin
│   │       │   │   ├── Config
│   │       │   │   │   ├── Source
│   │       │   │   │   └── Type
│   │       │   │   ├── FrontController
│   │       │   │   │   └── Plugin
│   │       │   │   ├── Request
│   │       │   │   └── Response
│   │       │   ├── Block
│   │       │   │   └── Store
│   │       │   ├── Console
│   │       │   │   └── Command
│   │       │   ├── Controller
│   │       │   │   └── Store
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   ├── data_source
│   │       │   │   └── frontend
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Address
│   │       │   │   ├── App
│   │       │   │   ├── Argument
│   │       │   │   │   └── Interpreter
│   │       │   │   ├── Config
│   │       │   │   │   ├── Importer
│   │       │   │   │   │   └── Processor
│   │       │   │   │   ├── Processor
│   │       │   │   │   └── Reader
│   │       │   │   │       └── Source
│   │       │   │   │           ├── Dynamic
│   │       │   │   │           └── Initial
│   │       │   │   ├── Data
│   │       │   │   ├── HeaderProvider
│   │       │   │   ├── Indexer
│   │       │   │   ├── Message
│   │       │   │   ├── Plugin
│   │       │   │   ├── Resolver
│   │       │   │   ├── ResourceModel
│   │       │   │   │   ├── Config
│   │       │   │   │   │   └── Collection
│   │       │   │   │   ├── Group
│   │       │   │   │   ├── Store
│   │       │   │   │   └── Website
│   │       │   │   │       └── Grid
│   │       │   │   ├── Service
│   │       │   │   ├── StoreResolver
│   │       │   │   ├── StoreSwitcher
│   │       │   │   └── System
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       ├── Data
│   │       │   │       └── Schema
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Metadata
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── App
│   │       │   │       │   ├── Action
│   │       │   │       │   │   └── Plugin
│   │       │   │       │   ├── Config
│   │       │   │       │   │   ├── Source
│   │       │   │       │   │   └── Type
│   │       │   │       │   ├── FrontController
│   │       │   │       │   │   └── Plugin
│   │       │   │       │   ├── Request
│   │       │   │       │   └── Response
│   │       │   │       ├── Block
│   │       │   │       │   └── Store
│   │       │   │       ├── Console
│   │       │   │       │   └── Command
│   │       │   │       ├── Controller
│   │       │   │       │   └── Store
│   │       │   │       ├── Model
│   │       │   │       │   ├── Address
│   │       │   │       │   ├── App
│   │       │   │       │   ├── Config
│   │       │   │       │   │   ├── Importer
│   │       │   │       │   │   │   └── Processor
│   │       │   │       │   │   ├── Processor
│   │       │   │       │   │   └── Reader
│   │       │   │       │   │       └── Source
│   │       │   │       │   │           ├── Dynamic
│   │       │   │       │   │           └── Initial
│   │       │   │       │   ├── HeaderProvider
│   │       │   │       │   ├── Message
│   │       │   │       │   ├── Plugin
│   │       │   │       │   ├── Resolver
│   │       │   │       │   ├── ResourceModel
│   │       │   │       │   ├── Service
│   │       │   │       │   └── System
│   │       │   │       ├── Ui
│   │       │   │       │   └── Component
│   │       │   │       │       └── Listing
│   │       │   │       │           └── Column
│   │       │   │       └── Url
│   │       │   │           └── Plugin
│   │       │   ├── Ui
│   │       │   │   └── Component
│   │       │   │       ├── Form
│   │       │   │       │   └── Fieldset
│   │       │   │       └── Listing
│   │       │   │           └── Column
│   │       │   │               └── Store
│   │       │   ├── Url
│   │       │   │   └── Plugin
│   │       │   ├── view
│   │       │   │   └── frontend
│   │       │   │       └── templates
│   │       │   │           └── switch
│   │       │   └── ViewModel
│   │       ├── StoreGraphQl
│   │       │   ├── Controller
│   │       │   │   ├── HttpHeaderProcessor
│   │       │   │   └── HttpRequestValidator
│   │       │   ├── etc
│   │       │   │   └── graphql
│   │       │   ├── Model
│   │       │   │   └── Resolver
│   │       │   │       └── Store
│   │       │   └── Test
│   │       │       └── Mftf
│   │       ├── Swagger
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   ├── Block
│   │       │   ├── Controller
│   │       │   │   └── Index
│   │       │   ├── etc
│   │       │   │   └── frontend
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       └── Controller
│   │       │   │           └── Index
│   │       │   └── view
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   └── swagger-ui
│   │       │           └── web
│   │       │               └── swagger-ui
│   │       │                   ├── css
│   │       │                   ├── images
│   │       │                   └── js
│   │       │                       └── lang
│   │       ├── SwaggerWebapi
│   │       │   ├── etc
│   │       │   │   └── frontend
│   │       │   ├── Model
│   │       │   │   └── SchemaType
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       └── Model
│   │       │   │           └── SchemaType
│   │       │   └── view
│   │       │       └── frontend
│   │       │           └── layout
│   │       ├── SwaggerWebapiAsync
│   │       │   ├── etc
│   │       │   │   └── frontend
│   │       │   ├── Model
│   │       │   │   └── SchemaType
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       └── Model
│   │       │   │           └── SchemaType
│   │       │   └── view
│   │       │       └── frontend
│   │       │           └── layout
│   │       ├── Swatches
│   │       │   ├── Block
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Attribute
│   │       │   │   │   │   └── Edit
│   │       │   │   │   │       └── Options
│   │       │   │   │   └── Product
│   │       │   │   │       └── Attribute
│   │       │   │   │           └── Edit
│   │       │   │   ├── LayeredNavigation
│   │       │   │   └── Product
│   │       │   │       └── Renderer
│   │       │   │           └── Listing
│   │       │   ├── Controller
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Iframe
│   │       │   │   │   └── Product
│   │       │   │   │       └── Attribute
│   │       │   │   │           └── Plugin
│   │       │   │   └── Ajax
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Form
│   │       │   │   │   └── Element
│   │       │   │   ├── Plugin
│   │       │   │   └── ResourceModel
│   │       │   │       └── Swatch
│   │       │   ├── Observer
│   │       │   ├── Plugin
│   │       │   │   ├── Catalog
│   │       │   │   └── Eav
│   │       │   │       └── System
│   │       │   │           └── Config
│   │       │   │               └── Source
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   ├── Attribute
│   │       │   │       │   │   │   └── Edit
│   │       │   │       │   │   │       └── Options
│   │       │   │       │   │   └── Product
│   │       │   │       │   │       └── Attribute
│   │       │   │       │   │           └── Edit
│   │       │   │       │   ├── LayeredNavigation
│   │       │   │       │   └── Product
│   │       │   │       │       └── Renderer
│   │       │   │       │           └── Listing
│   │       │   │       ├── Controller
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   ├── Iframe
│   │       │   │       │   │   └── Product
│   │       │   │       │   │       └── Attribute
│   │       │   │       │   │           └── Plugin
│   │       │   │       │   └── Ajax
│   │       │   │       ├── Helper
│   │       │   │       ├── Model
│   │       │   │       │   ├── Form
│   │       │   │       │   │   └── Element
│   │       │   │       │   └── Plugin
│   │       │   │       ├── Observer
│   │       │   │       └── Plugin
│   │       │   │           └── Catalog
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   │   └── catalog
│   │       │       │   │       └── product
│   │       │       │   │           ├── attribute
│   │       │       │   │           └── edit
│   │       │       │   │               └── attribute
│   │       │       │   │                   └── steps
│   │       │       │   ├── ui_component
│   │       │       │   └── web
│   │       │       │       ├── css
│   │       │       │       ├── js
│   │       │       │       │   └── form
│   │       │       │       │       └── element
│   │       │       │       └── template
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   └── product
│   │       │           │       ├── layered
│   │       │           │       ├── listing
│   │       │           │       └── view
│   │       │           └── web
│   │       │               └── js
│   │       ├── SwatchesGraphQl
│   │       │   ├── etc
│   │       │   │   └── graphql
│   │       │   ├── Model
│   │       │   │   └── Resolver
│   │       │   ├── Plugin
│   │       │   │   └── Filters
│   │       │   └── Test
│   │       │       └── Mftf
│   │       ├── SwatchesLayeredNavigation
│   │       │   ├── etc
│   │       │   ├── Test
│   │       │   │   └── Mftf
│   │       │   └── view
│   │       │       └── adminhtml
│   │       │           └── ui_component
│   │       ├── Tax
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   ├── Block
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Frontend
│   │       │   │   │   │   └── Region
│   │       │   │   │   ├── Items
│   │       │   │   │   │   └── Price
│   │       │   │   │   ├── Rate
│   │       │   │   │   │   ├── Grid
│   │       │   │   │   │   │   └── Renderer
│   │       │   │   │   │   ├── Title
│   │       │   │   │   │   └── Toolbar
│   │       │   │   │   └── Rule
│   │       │   │   │       └── Edit
│   │       │   │   ├── Checkout
│   │       │   │   │   └── Shipping
│   │       │   │   ├── Grid
│   │       │   │   │   └── Renderer
│   │       │   │   ├── Item
│   │       │   │   │   └── Price
│   │       │   │   └── Sales
│   │       │   │       └── Order
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       ├── Rate
│   │       │   │       ├── Rule
│   │       │   │       └── Tax
│   │       │   ├── CustomerData
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Api
│   │       │   │   │   └── SearchCriteria
│   │       │   │   │       └── JoinProcessor
│   │       │   │   ├── App
│   │       │   │   │   └── Action
│   │       │   │   ├── Calculation
│   │       │   │   │   ├── Rate
│   │       │   │   │   └── Rule
│   │       │   │   ├── Config
│   │       │   │   │   ├── Price
│   │       │   │   │   └── Source
│   │       │   │   │       └── Apply
│   │       │   │   ├── Layout
│   │       │   │   ├── Plugin
│   │       │   │   ├── Quote
│   │       │   │   ├── Rate
│   │       │   │   ├── ResourceModel
│   │       │   │   │   ├── Calculation
│   │       │   │   │   │   ├── Rate
│   │       │   │   │   │   │   └── Title
│   │       │   │   │   │   └── Rule
│   │       │   │   │   ├── Report
│   │       │   │   │   │   ├── Tax
│   │       │   │   │   │   └── Updatedat
│   │       │   │   │   ├── Sales
│   │       │   │   │   │   └── Order
│   │       │   │   │   │       └── Tax
│   │       │   │   │   └── TaxClass
│   │       │   │   ├── Sales
│   │       │   │   │   ├── Order
│   │       │   │   │   ├── Pdf
│   │       │   │   │   ├── Quote
│   │       │   │   │   └── Total
│   │       │   │   │       └── Quote
│   │       │   │   ├── System
│   │       │   │   │   ├── Config
│   │       │   │   │   │   └── Source
│   │       │   │   │   │       └── Tax
│   │       │   │   │   │           └── Display
│   │       │   │   │   └── Message
│   │       │   │   │       └── Notification
│   │       │   │   ├── TaxClass
│   │       │   │   │   ├── Source
│   │       │   │   │   └── Type
│   │       │   │   └── TaxDetails
│   │       │   ├── Observer
│   │       │   ├── Plugin
│   │       │   │   ├── Checkout
│   │       │   │   │   └── CustomerData
│   │       │   │   └── Ui
│   │       │   │       └── DataProvider
│   │       │   ├── Pricing
│   │       │   │   └── Render
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Metadata
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── App
│   │       │   │       │   └── Action
│   │       │   │       ├── Block
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   ├── Items
│   │       │   │       │   │   │   └── Price
│   │       │   │       │   │   └── Rule
│   │       │   │       │   │       └── Edit
│   │       │   │       │   ├── Checkout
│   │       │   │       │   │   └── Shipping
│   │       │   │       │   ├── Grid
│   │       │   │       │   │   └── Renderer
│   │       │   │       │   └── Item
│   │       │   │       │       └── Price
│   │       │   │       ├── Controller
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       ├── Rate
│   │       │   │       │       ├── Rule
│   │       │   │       │       └── Tax
│   │       │   │       ├── Helper
│   │       │   │       ├── Model
│   │       │   │       │   ├── Calculation
│   │       │   │       │   │   └── Rate
│   │       │   │       │   ├── Config
│   │       │   │       │   ├── Plugin
│   │       │   │       │   ├── Quote
│   │       │   │       │   ├── ResourceModel
│   │       │   │       │   ├── Sales
│   │       │   │       │   │   ├── Order
│   │       │   │       │   │   └── Total
│   │       │   │       │   │       └── Quote
│   │       │   │       │   ├── System
│   │       │   │       │   │   └── Message
│   │       │   │       │   │       └── Notification
│   │       │   │       │   └── TaxClass
│   │       │   │       │       ├── Source
│   │       │   │       │       └── Type
│   │       │   │       ├── Observer
│   │       │   │       ├── Plugin
│   │       │   │       │   └── Checkout
│   │       │   │       │       └── CustomerData
│   │       │   │       ├── Pricing
│   │       │   │       │   └── Render
│   │       │   │       ├── Setup
│   │       │   │       └── Ui
│   │       │   │           └── DataProvider
│   │       │   │               └── Product
│   │       │   │                   └── Listing
│   │       │   │                       └── Collector
│   │       │   ├── Ui
│   │       │   │   └── DataProvider
│   │       │   │       └── Product
│   │       │   │           └── Listing
│   │       │   │               └── Collector
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   │   ├── items
│   │       │       │   │   │   └── price
│   │       │       │   │   ├── order
│   │       │       │   │   │   └── create
│   │       │       │   │   │       └── items
│   │       │       │   │   │           └── price
│   │       │       │   │   ├── rate
│   │       │       │   │   ├── rule
│   │       │       │   │   │   └── rate
│   │       │       │   │   └── toolbar
│   │       │       │   │       ├── class
│   │       │       │   │       ├── rate
│   │       │       │   │       └── rule
│   │       │       │   └── web
│   │       │       │       └── js
│   │       │       ├── base
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   │   └── pricing
│   │       │       │   │       └── adjustment
│   │       │       │   └── web
│   │       │       │       ├── js
│   │       │       │       │   └── price
│   │       │       │       └── template
│   │       │       │           └── price
│   │       │       │               └── bundle
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   ├── checkout
│   │       │           │   │   ├── cart
│   │       │           │   │   │   └── item
│   │       │           │   │   │       └── price
│   │       │           │   │   └── shipping
│   │       │           │   ├── email
│   │       │           │   │   └── items
│   │       │           │   │       └── price
│   │       │           │   ├── item
│   │       │           │   │   └── price
│   │       │           │   └── order
│   │       │           ├── ui_component
│   │       │           └── web
│   │       │               ├── js
│   │       │               │   └── view
│   │       │               │       └── checkout
│   │       │               │           ├── cart
│   │       │               │           │   └── totals
│   │       │               │           ├── minicart
│   │       │               │           │   └── subtotal
│   │       │               │           ├── shipping_method
│   │       │               │           └── summary
│   │       │               │               └── item
│   │       │               │                   └── details
│   │       │               └── template
│   │       │                   └── checkout
│   │       │                       ├── cart
│   │       │                       │   └── totals
│   │       │                       ├── minicart
│   │       │                       │   └── subtotal
│   │       │                       ├── shipping_method
│   │       │                       └── summary
│   │       │                           └── item
│   │       │                               └── details
│   │       ├── TaxGraphQl
│   │       │   ├── etc
│   │       │   └── Test
│   │       │       └── Mftf
│   │       ├── TaxImportExport
│   │       │   ├── Block
│   │       │   │   └── Adminhtml
│   │       │   │       └── Rate
│   │       │   │           └── Grid
│   │       │   │               └── Renderer
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       └── Rate
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   └── Rate
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       └── Controller
│   │       │   │           └── Adminhtml
│   │       │   │               └── Rate
│   │       │   └── view
│   │       │       └── adminhtml
│   │       │           ├── layout
│   │       │           └── templates
│   │       ├── Theme
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   ├── Block
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Design
│   │       │   │   │   │   └── Config
│   │       │   │   │   │       └── Edit
│   │       │   │   │   ├── System
│   │       │   │   │   │   └── Design
│   │       │   │   │   │       └── Theme
│   │       │   │   │   │           └── Edit
│   │       │   │   │   │               ├── Form
│   │       │   │   │   │               │   └── Element
│   │       │   │   │   │               └── Tab
│   │       │   │   │   └── Wysiwyg
│   │       │   │   │       └── Files
│   │       │   │   │           └── Content
│   │       │   │   └── Html
│   │       │   │       └── Header
│   │       │   ├── Console
│   │       │   │   └── Command
│   │       │   ├── Controller
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Design
│   │       │   │   │   │   └── Config
│   │       │   │   │   │       └── FileUploader
│   │       │   │   │   └── System
│   │       │   │   │       └── Design
│   │       │   │   │           ├── Theme
│   │       │   │   │           └── Wysiwyg
│   │       │   │   │               └── Files
│   │       │   │   └── Result
│   │       │   ├── CustomerData
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Config
│   │       │   │   │   └── Processor
│   │       │   │   ├── Data
│   │       │   │   │   └── Design
│   │       │   │   │       └── Config
│   │       │   │   ├── Design
│   │       │   │   │   ├── Backend
│   │       │   │   │   ├── Config
│   │       │   │   │   │   ├── DataProvider
│   │       │   │   │   │   ├── FileUploader
│   │       │   │   │   │   └── Plugin
│   │       │   │   │   └── Theme
│   │       │   │   ├── Favicon
│   │       │   │   ├── Indexer
│   │       │   │   │   └── Design
│   │       │   │   │       └── Config
│   │       │   │   │           └── Plugin
│   │       │   │   ├── Layout
│   │       │   │   │   ├── Config
│   │       │   │   │   └── Source
│   │       │   │   ├── PageLayout
│   │       │   │   │   └── Config
│   │       │   │   ├── ResourceModel
│   │       │   │   │   ├── Design
│   │       │   │   │   │   └── Config
│   │       │   │   │   │       └── Scope
│   │       │   │   │   └── Theme
│   │       │   │   │       ├── Customization
│   │       │   │   │       ├── Data
│   │       │   │   │       ├── File
│   │       │   │   │       └── Grid
│   │       │   │   ├── Source
│   │       │   │   ├── Theme
│   │       │   │   │   ├── Customization
│   │       │   │   │   │   └── File
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Domain
│   │       │   │   │   ├── Image
│   │       │   │   │   ├── Plugin
│   │       │   │   │   └── Source
│   │       │   │   ├── Uploader
│   │       │   │   ├── Url
│   │       │   │   │   └── Plugin
│   │       │   │   ├── View
│   │       │   │   └── Wysiwyg
│   │       │   ├── Observer
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   ├── Design
│   │       │   │       │   │   │   └── Config
│   │       │   │       │   │   │       └── Edit
│   │       │   │       │   │   ├── System
│   │       │   │       │   │   │   └── Design
│   │       │   │       │   │   │       └── Theme
│   │       │   │       │   │   │           ├── Edit
│   │       │   │       │   │   │           │   └── Form
│   │       │   │       │   │   │           │       └── Element
│   │       │   │       │   │   │           └── Tab
│   │       │   │       │   │   └── Wysiwyg
│   │       │   │       │   │       └── Files
│   │       │   │       │   └── Html
│   │       │   │       │       ├── _files
│   │       │   │       │       │   └── logo
│   │       │   │       │       │       └── default
│   │       │   │       │       └── Header
│   │       │   │       ├── Console
│   │       │   │       │   └── Command
│   │       │   │       ├── Controller
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   ├── Design
│   │       │   │       │   │   │   └── Config
│   │       │   │       │   │   │       └── FileUploader
│   │       │   │       │   │   └── System
│   │       │   │       │   │       └── Design
│   │       │   │       │   │           ├── Theme
│   │       │   │       │   │           └── Wysiwyg
│   │       │   │       │   │               └── Files
│   │       │   │       │   └── Result
│   │       │   │       ├── CustomerData
│   │       │   │       ├── Helper
│   │       │   │       ├── Model
│   │       │   │       │   ├── Config
│   │       │   │       │   │   ├── _files
│   │       │   │       │   │   └── Processor
│   │       │   │       │   ├── Data
│   │       │   │       │   │   └── Design
│   │       │   │       │   ├── Design
│   │       │   │       │   │   ├── Backend
│   │       │   │       │   │   └── Config
│   │       │   │       │   │       ├── DataProvider
│   │       │   │       │   │       ├── FileUploader
│   │       │   │       │   │       └── Plugin
│   │       │   │       │   ├── Favicon
│   │       │   │       │   ├── _files
│   │       │   │       │   │   └── frontend
│   │       │   │       │   │       └── magento_iphone
│   │       │   │       │   ├── Indexer
│   │       │   │       │   │   └── Design
│   │       │   │       │   │       └── Config
│   │       │   │       │   │           └── Plugin
│   │       │   │       │   ├── Layout
│   │       │   │       │   │   ├── Config
│   │       │   │       │   │   │   └── _files
│   │       │   │       │   │   └── Source
│   │       │   │       │   ├── PageLayout
│   │       │   │       │   │   └── Config
│   │       │   │       │   ├── ResourceModel
│   │       │   │       │   │   └── Design
│   │       │   │       │   │       └── Config
│   │       │   │       │   │           └── Scope
│   │       │   │       │   ├── Source
│   │       │   │       │   ├── Theme
│   │       │   │       │   │   ├── Customization
│   │       │   │       │   │   │   └── File
│   │       │   │       │   │   ├── Domain
│   │       │   │       │   │   ├── Image
│   │       │   │       │   │   ├── Plugin
│   │       │   │       │   │   └── Source
│   │       │   │       │   ├── Uploader
│   │       │   │       │   ├── Url
│   │       │   │       │   │   └── Plugin
│   │       │   │       │   ├── View
│   │       │   │       │   └── Wysiwyg
│   │       │   │       ├── Observer
│   │       │   │       └── Ui
│   │       │   │           └── Component
│   │       │   │               ├── Design
│   │       │   │               │   └── Config
│   │       │   │               │       └── SearchRobots
│   │       │   │               └── Listing
│   │       │   │                   └── Column
│   │       │   ├── Ui
│   │       │   │   └── Component
│   │       │   │       ├── Design
│   │       │   │       │   └── Config
│   │       │   │       │       └── SearchRobots
│   │       │   │       ├── Listing
│   │       │   │       │   └── Column
│   │       │   │       └── Theme
│   │       │   │           └── DataProvider
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   ├── page_layout
│   │       │       │   ├── templates
│   │       │       │   │   ├── browser
│   │       │       │   │   │   └── content
│   │       │       │   │   ├── design
│   │       │       │   │   │   └── config
│   │       │       │   │   │       └── edit
│   │       │       │   │   └── tabs
│   │       │       │   │       └── fieldset
│   │       │       │   ├── ui_component
│   │       │       │   └── web
│   │       │       │       ├── css
│   │       │       │       ├── images
│   │       │       │       ├── js
│   │       │       │       │   └── form
│   │       │       │       │       └── component
│   │       │       │       ├── prototype
│   │       │       │       ├── template
│   │       │       │       │   └── form
│   │       │       │       │       └── element
│   │       │       │       └── theme
│   │       │       ├── base
│   │       │       │   ├── layout
│   │       │       │   ├── page_layout
│   │       │       │   └── templates
│   │       │       ├── frontend
│   │       │       │   ├── layout
│   │       │       │   ├── page_layout
│   │       │       │   ├── templates
│   │       │       │   │   ├── callouts
│   │       │       │   │   ├── html
│   │       │       │   │   │   └── header
│   │       │       │   │   ├── js
│   │       │       │   │   └── page
│   │       │       │   │       └── js
│   │       │       │   └── web
│   │       │       │       ├── css
│   │       │       │       ├── images
│   │       │       │       ├── js
│   │       │       │       │   ├── model
│   │       │       │       │   └── view
│   │       │       │       ├── prototype
│   │       │       │       └── templates
│   │       │       └── install
│   │       │           └── web
│   │       ├── ThemeGraphQl
│   │       │   └── etc
│   │       │       └── graphql
│   │       ├── Tinymce3
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── Model
│   │       │   │   ├── Config
│   │       │   │   │   ├── Gallery
│   │       │   │   │   ├── Source
│   │       │   │   │   │   └── Wysiwyg
│   │       │   │   │   ├── Variable
│   │       │   │   │   ├── Widget
│   │       │   │   │   └── Wysiwyg
│   │       │   │   └── Plugin
│   │       │   ├── Test
│   │       │   │   └── Mftf
│   │       │   │       ├── Section
│   │       │   │       └── Test
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   └── web
│   │       │       │       ├── images
│   │       │       │       │   ├── catalog
│   │       │       │       │   ├── cms
│   │       │       │       │   └── widget
│   │       │       │       └── wysiwyg
│   │       │       │           └── tiny_mce
│   │       │       │               └── plugins
│   │       │       │                   └── magentovariable
│   │       │       │                       └── img
│   │       │       └── base
│   │       │           └── web
│   │       │               └── tiny_mce
│   │       │                   ├── classes
│   │       │                   │   ├── adapter
│   │       │                   │   │   ├── jquery
│   │       │                   │   │   └── prototype
│   │       │                   │   ├── dom
│   │       │                   │   ├── firebug
│   │       │                   │   ├── html
│   │       │                   │   ├── ui
│   │       │                   │   ├── util
│   │       │                   │   └── xml
│   │       │                   ├── langs
│   │       │                   ├── plugins
│   │       │                   │   ├── advhr
│   │       │                   │   │   ├── css
│   │       │                   │   │   ├── js
│   │       │                   │   │   └── langs
│   │       │                   │   ├── advimage
│   │       │                   │   │   ├── css
│   │       │                   │   │   ├── img
│   │       │                   │   │   ├── js
│   │       │                   │   │   └── langs
│   │       │                   │   ├── advlink
│   │       │                   │   │   ├── css
│   │       │                   │   │   ├── js
│   │       │                   │   │   └── langs
│   │       │                   │   ├── advlist
│   │       │                   │   ├── autolink
│   │       │                   │   ├── autoresize
│   │       │                   │   ├── autosave
│   │       │                   │   │   └── langs
│   │       │                   │   ├── bbcode
│   │       │                   │   ├── contextmenu
│   │       │                   │   ├── directionality
│   │       │                   │   ├── emotions
│   │       │                   │   │   ├── img
│   │       │                   │   │   ├── js
│   │       │                   │   │   └── langs
│   │       │                   │   ├── example
│   │       │                   │   │   ├── img
│   │       │                   │   │   ├── js
│   │       │                   │   │   └── langs
│   │       │                   │   ├── example_dependency
│   │       │                   │   ├── fullpage
│   │       │                   │   │   ├── css
│   │       │                   │   │   ├── js
│   │       │                   │   │   └── langs
│   │       │                   │   ├── fullscreen
│   │       │                   │   ├── iespell
│   │       │                   │   ├── inlinepopups
│   │       │                   │   │   └── skins
│   │       │                   │   │       └── clearlooks2
│   │       │                   │   │           └── img
│   │       │                   │   ├── insertdatetime
│   │       │                   │   ├── layer
│   │       │                   │   ├── legacyoutput
│   │       │                   │   ├── lists
│   │       │                   │   ├── magentowidget
│   │       │                   │   │   └── img
│   │       │                   │   ├── media
│   │       │                   │   │   ├── css
│   │       │                   │   │   ├── img
│   │       │                   │   │   ├── js
│   │       │                   │   │   └── langs
│   │       │                   │   ├── nonbreaking
│   │       │                   │   ├── noneditable
│   │       │                   │   ├── pagebreak
│   │       │                   │   │   ├── css
│   │       │                   │   │   └── img
│   │       │                   │   ├── paste
│   │       │                   │   │   ├── js
│   │       │                   │   │   └── langs
│   │       │                   │   ├── preview
│   │       │                   │   │   └── jscripts
│   │       │                   │   ├── print
│   │       │                   │   ├── save
│   │       │                   │   ├── searchreplace
│   │       │                   │   │   ├── css
│   │       │                   │   │   ├── js
│   │       │                   │   │   └── langs
│   │       │                   │   ├── spellchecker
│   │       │                   │   │   ├── css
│   │       │                   │   │   └── img
│   │       │                   │   ├── style
│   │       │                   │   │   ├── css
│   │       │                   │   │   ├── js
│   │       │                   │   │   └── langs
│   │       │                   │   ├── tabfocus
│   │       │                   │   ├── table
│   │       │                   │   │   ├── css
│   │       │                   │   │   ├── js
│   │       │                   │   │   └── langs
│   │       │                   │   ├── template
│   │       │                   │   │   ├── css
│   │       │                   │   │   ├── js
│   │       │                   │   │   └── langs
│   │       │                   │   ├── visualchars
│   │       │                   │   ├── wordcount
│   │       │                   │   └── xhtmlxtras
│   │       │                   │       ├── css
│   │       │                   │       ├── js
│   │       │                   │       └── langs
│   │       │                   ├── themes
│   │       │                   │   ├── advanced
│   │       │                   │   │   ├── img
│   │       │                   │   │   ├── js
│   │       │                   │   │   ├── langs
│   │       │                   │   │   └── skins
│   │       │                   │   │       ├── default
│   │       │                   │   │       │   └── img
│   │       │                   │   │       ├── highcontrast
│   │       │                   │   │       └── o2k7
│   │       │                   │   │           └── img
│   │       │                   │   └── simple
│   │       │                   │       ├── img
│   │       │                   │       ├── langs
│   │       │                   │       └── skins
│   │       │                   │           ├── default
│   │       │                   │           └── o2k7
│   │       │                   │               └── img
│   │       │                   └── utils
│   │       ├── Translation
│   │       │   ├── App
│   │       │   │   └── Config
│   │       │   │       └── Type
│   │       │   ├── Block
│   │       │   │   └── Html
│   │       │   │       └── Head
│   │       │   ├── Console
│   │       │   │   └── Command
│   │       │   ├── Controller
│   │       │   │   └── Ajax
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Inline
│   │       │   │   ├── Js
│   │       │   │   │   └── Config
│   │       │   │   │       └── Source
│   │       │   │   ├── Json
│   │       │   │   ├── ResourceModel
│   │       │   │   └── Source
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       ├── App
│   │       │   │       │   └── Config
│   │       │   │       │       └── Type
│   │       │   │       ├── Block
│   │       │   │       ├── Console
│   │       │   │       │   └── Command
│   │       │   │       └── Model
│   │       │   │           ├── Inline
│   │       │   │           │   └── _files
│   │       │   │           ├── Js
│   │       │   │           │   └── Config
│   │       │   │           │       └── Source
│   │       │   │           ├── Json
│   │       │   │           └── Source
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   └── templates
│   │       │       ├── base
│   │       │       │   ├── templates
│   │       │       │   └── web
│   │       │       │       └── js
│   │       │       └── frontend
│   │       │           ├── templates
│   │       │           └── web
│   │       │               └── js
│   │       ├── Ui
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   ├── Block
│   │       │   │   ├── Component
│   │       │   │   │   └── StepsWizard
│   │       │   │   └── Wysiwyg
│   │       │   ├── Component
│   │       │   │   ├── Control
│   │       │   │   ├── Filters
│   │       │   │   │   └── Type
│   │       │   │   ├── Form
│   │       │   │   │   ├── Element
│   │       │   │   │   │   └── DataType
│   │       │   │   │   │       └── Media
│   │       │   │   │   ├── Field
│   │       │   │   │   └── Fieldset
│   │       │   │   ├── Layout
│   │       │   │   │   └── Tabs
│   │       │   │   ├── Listing
│   │       │   │   │   └── Columns
│   │       │   │   ├── MassAction
│   │       │   │   │   └── Columns
│   │       │   │   ├── Wrapper
│   │       │   │   └── Wysiwyg
│   │       │   ├── Config
│   │       │   │   ├── Argument
│   │       │   │   │   └── Parser
│   │       │   │   ├── Converter
│   │       │   │   └── Reader
│   │       │   │       ├── Definition
│   │       │   │       ├── DefinitionMap
│   │       │   │       └── Template
│   │       │   ├── Controller
│   │       │   │   ├── Adminhtml
│   │       │   │   │   ├── Bookmark
│   │       │   │   │   ├── Export
│   │       │   │   │   └── Index
│   │       │   │   │       └── Render
│   │       │   │   └── Index
│   │       │   ├── DataProvider
│   │       │   │   ├── Mapper
│   │       │   │   └── Modifier
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── ColorPicker
│   │       │   │   ├── Export
│   │       │   │   ├── ResourceModel
│   │       │   │   │   └── Bookmark
│   │       │   │   └── UrlInput
│   │       │   ├── TemplateEngine
│   │       │   │   └── Xhtml
│   │       │   │       └── Compiler
│   │       │   │           └── Element
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Component
│   │       │   │       │   ├── Control
│   │       │   │       │   ├── Filters
│   │       │   │       │   │   └── Type
│   │       │   │       │   ├── Form
│   │       │   │       │   │   ├── Element
│   │       │   │       │   │   │   └── DataType
│   │       │   │       │   │   │       └── Media
│   │       │   │       │   │   └── Field
│   │       │   │       │   ├── Listing
│   │       │   │       │   │   └── Columns
│   │       │   │       │   └── MassAction
│   │       │   │       │       └── Columns
│   │       │   │       ├── Config
│   │       │   │       │   └── Converter
│   │       │   │       │       └── _files
│   │       │   │       ├── Controller
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       ├── Export
│   │       │   │       │       └── Index
│   │       │   │       │           └── Render
│   │       │   │       ├── DataProvider
│   │       │   │       │   └── Modifier
│   │       │   │       └── Model
│   │       │   │           ├── Export
│   │       │   │           └── ResourceModel
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   └── web
│   │       │       │       └── templates
│   │       │       │           └── modal
│   │       │       ├── base
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   │   ├── container
│   │       │       │   │   │   └── content
│   │       │       │   │   ├── context
│   │       │       │   │   ├── control
│   │       │       │   │   │   └── button
│   │       │       │   │   ├── form
│   │       │       │   │   ├── label
│   │       │       │   │   ├── layout
│   │       │       │   │   │   └── tabs
│   │       │       │   │   │       └── nav
│   │       │       │   │   └── wysiwyg
│   │       │       │   ├── ui_component
│   │       │       │   │   ├── etc
│   │       │       │   │   │   └── definition
│   │       │       │   │   └── templates
│   │       │       │   │       ├── container
│   │       │       │   │       ├── export
│   │       │       │   │       ├── form
│   │       │       │   │       └── listing
│   │       │       │   └── web
│   │       │       │       ├── js
│   │       │       │       │   ├── core
│   │       │       │       │   │   └── renderer
│   │       │       │       │   ├── dynamic-rows
│   │       │       │       │   ├── form
│   │       │       │       │   │   ├── adapter
│   │       │       │       │   │   ├── components
│   │       │       │       │   │   │   └── collection
│   │       │       │       │   │   └── element
│   │       │       │       │   ├── grid
│   │       │       │       │   │   ├── columns
│   │       │       │       │   │   ├── controls
│   │       │       │       │   │   │   ├── bookmarks
│   │       │       │       │   │   │   └── button
│   │       │       │       │   │   ├── editing
│   │       │       │       │   │   ├── filters
│   │       │       │       │   │   ├── paging
│   │       │       │       │   │   ├── search
│   │       │       │       │   │   └── sticky
│   │       │       │       │   ├── lib
│   │       │       │       │   │   ├── core
│   │       │       │       │   │   │   ├── element
│   │       │       │       │   │   │   └── storage
│   │       │       │       │   │   ├── knockout
│   │       │       │       │   │   │   ├── bindings
│   │       │       │       │   │   │   ├── extender
│   │       │       │       │   │   │   └── template
│   │       │       │       │   │   ├── logger
│   │       │       │       │   │   ├── registry
│   │       │       │       │   │   ├── validation
│   │       │       │       │   │   └── view
│   │       │       │       │   │       └── utils
│   │       │       │       │   ├── modal
│   │       │       │       │   └── timeline
│   │       │       │       └── templates
│   │       │       │           ├── content
│   │       │       │           ├── dynamic-rows
│   │       │       │           │   ├── cells
│   │       │       │           │   └── templates
│   │       │       │           ├── form
│   │       │       │           │   ├── components
│   │       │       │           │   │   ├── button
│   │       │       │           │   │   ├── collection
│   │       │       │           │   │   └── single
│   │       │       │           │   └── element
│   │       │       │           │       ├── helper
│   │       │       │           │       ├── uploader
│   │       │       │           │       └── urlInput
│   │       │       │           ├── grid
│   │       │       │           │   ├── cells
│   │       │       │           │   │   ├── expandable
│   │       │       │           │   │   └── thumbnail
│   │       │       │           │   ├── columns
│   │       │       │           │   ├── controls
│   │       │       │           │   │   └── bookmarks
│   │       │       │           │   ├── editing
│   │       │       │           │   ├── filters
│   │       │       │           │   │   └── elements
│   │       │       │           │   ├── paging
│   │       │       │           │   ├── search
│   │       │       │           │   └── sticky
│   │       │       │           ├── group
│   │       │       │           ├── list
│   │       │       │           ├── modal
│   │       │       │           ├── timeline
│   │       │       │           └── tooltip
│   │       │       └── frontend
│   │       │           └── web
│   │       │               ├── js
│   │       │               │   ├── model
│   │       │               │   └── view
│   │       │               ├── template
│   │       │               └── templates
│   │       │                   ├── form
│   │       │                   │   └── element
│   │       │                   │       ├── helper
│   │       │                   │       └── uploader
│   │       │                   └── group
│   │       ├── Ups
│   │       │   ├── Block
│   │       │   │   └── Backend
│   │       │   │       └── System
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   └── Config
│   │       │   │       └── Source
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Metadata
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Fixtures
│   │       │   │       ├── Helper
│   │       │   │       └── Model
│   │       │   │           └── _files
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   └── templates
│   │       │       │       └── system
│   │       │       │           └── shipping
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           └── web
│   │       │               └── js
│   │       │                   ├── model
│   │       │                   └── view
│   │       ├── UrlRewrite
│   │       │   ├── Block
│   │       │   │   ├── Catalog
│   │       │   │   │   ├── Category
│   │       │   │   │   ├── Edit
│   │       │   │   │   └── Product
│   │       │   │   ├── Cms
│   │       │   │   │   └── Page
│   │       │   │   │       └── Edit
│   │       │   │   └── Edit
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       └── Url
│   │       │   │           └── Rewrite
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Exception
│   │       │   │   ├── Message
│   │       │   │   ├── ResourceModel
│   │       │   │   ├── Storage
│   │       │   │   └── StoreSwitcher
│   │       │   ├── Service
│   │       │   │   └── V1
│   │       │   │       └── Data
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Metadata
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   └── Catalog
│   │       │   │       │       └── Edit
│   │       │   │       ├── Controller
│   │       │   │       ├── Helper
│   │       │   │       ├── Model
│   │       │   │       │   ├── Exception
│   │       │   │       │   ├── Message
│   │       │   │       │   ├── ResourceModel
│   │       │   │       │   └── Storage
│   │       │   │       └── Service
│   │       │   │           └── V1
│   │       │   │               └── Data
│   │       │   └── view
│   │       │       └── adminhtml
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   └── messages
│   │       │           └── web
│   │       │               └── js
│   │       ├── UrlRewriteGraphQl
│   │       │   ├── etc
│   │       │   ├── Model
│   │       │   │   └── Resolver
│   │       │   │       └── UrlRewrite
│   │       │   └── Test
│   │       │       └── Mftf
│   │       ├── User
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   ├── Block
│   │       │   │   ├── Adminhtml
│   │       │   │   ├── Role
│   │       │   │   │   ├── Grid
│   │       │   │   │   └── Tab
│   │       │   │   └── User
│   │       │   │       └── Edit
│   │       │   │           └── Tab
│   │       │   ├── Console
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       ├── Auth
│   │       │   │       ├── Locks
│   │       │   │       └── User
│   │       │   │           └── Role
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── webapi_rest
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Authorization
│   │       │   │   ├── Backend
│   │       │   │   │   └── Config
│   │       │   │   ├── Plugin
│   │       │   │   ├── ResourceModel
│   │       │   │   │   ├── Role
│   │       │   │   │   │   └── User
│   │       │   │   │   └── User
│   │       │   │   │       └── Locked
│   │       │   │   ├── Spi
│   │       │   │   └── System
│   │       │   │       └── Config
│   │       │   │           └── Source
│   │       │   ├── Observer
│   │       │   │   └── Backend
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Metadata
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   └── Role
│   │       │   │       │       ├── Grid
│   │       │   │       │       └── Tab
│   │       │   │       ├── Console
│   │       │   │       ├── Controller
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       └── User
│   │       │   │       ├── Helper
│   │       │   │       ├── Model
│   │       │   │       │   ├── Plugin
│   │       │   │       │   └── ResourceModel
│   │       │   │       └── Observer
│   │       │   │           └── Backend
│   │       │   ├── view
│   │       │   │   └── adminhtml
│   │       │   │       ├── email
│   │       │   │       ├── layout
│   │       │   │       ├── templates
│   │       │   │       │   ├── admin
│   │       │   │       │   ├── role
│   │       │   │       │   └── user
│   │       │   │       └── web
│   │       │   │           └── js
│   │       │   └── ViewModel
│   │       ├── Usps
│   │       │   ├── Block
│   │       │   │   └── Adminhtml
│   │       │   │       └── Order
│   │       │   │           └── Packaging
│   │       │   │               └── Plugin
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   └── Source
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       ├── Helper
│   │       │   │       └── Model
│   │       │   │           ├── _files
│   │       │   │           └── Source
│   │       │   └── view
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           └── web
│   │       │               └── js
│   │       │                   ├── model
│   │       │                   └── view
│   │       ├── Variable
│   │       │   ├── Block
│   │       │   │   └── System
│   │       │   │       └── Variable
│   │       │   │           └── Edit
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       └── System
│   │       │   │           └── Variable
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── ResourceModel
│   │       │   │   │   └── Variable
│   │       │   │   ├── Source
│   │       │   │   └── Variable
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Controller
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       └── System
│   │       │   │       │           └── Variable
│   │       │   │       └── Model
│   │       │   │           ├── ResourceModel
│   │       │   │           │   └── Variable
│   │       │   │           ├── Source
│   │       │   │           └── Variable
│   │       │   ├── Ui
│   │       │   │   └── Component
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   │   └── system
│   │       │       │   │       └── variable
│   │       │       │   ├── ui_component
│   │       │       │   └── web
│   │       │       │       └── js
│   │       │       └── base
│   │       │           └── web
│   │       │               ├── js
│   │       │               │   └── grid
│   │       │               │       └── columns
│   │       │               └── template
│   │       │                   └── grid
│   │       │                       └── cells
│   │       ├── Vault
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   ├── Block
│   │       │   │   └── Customer
│   │       │   ├── Controller
│   │       │   │   └── Cards
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Method
│   │       │   │   ├── ResourceModel
│   │       │   │   │   └── PaymentToken
│   │       │   │   └── Ui
│   │       │   │       └── Adminhtml
│   │       │   ├── Observer
│   │       │   ├── Plugin
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   └── Customer
│   │       │   │       ├── Model
│   │       │   │       │   ├── Method
│   │       │   │       │   └── Ui
│   │       │   │       │       └── Adminhtml
│   │       │   │       ├── Observer
│   │       │   │       └── Plugin
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── templates
│   │       │       │   │   └── form
│   │       │       │   └── web
│   │       │       │       └── js
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   └── customer_account
│   │       │           └── web
│   │       │               ├── js
│   │       │               │   ├── customer_account
│   │       │               │   └── view
│   │       │               │       └── payment
│   │       │               │           └── method-renderer
│   │       │               └── template
│   │       │                   └── payment
│   │       ├── VaultGraphQl
│   │       │   ├── etc
│   │       │   └── Model
│   │       │       └── Resolver
│   │       ├── Version
│   │       │   ├── Controller
│   │       │   │   └── Index
│   │       │   ├── etc
│   │       │   │   └── frontend
│   │       │   ├── i18n
│   │       │   └── Test
│   │       │       └── Mftf
│   │       ├── Webapi
│   │       │   ├── Controller
│   │       │   │   ├── Rest
│   │       │   │   │   └── Router
│   │       │   │   └── Soap
│   │       │   │       └── Request
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   ├── frontend
│   │       │   │   ├── webapi_rest
│   │       │   │   └── webapi_soap
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Authorization
│   │       │   │   ├── Cache
│   │       │   │   │   └── Type
│   │       │   │   ├── Config
│   │       │   │   ├── Plugin
│   │       │   │   │   └── Authorization
│   │       │   │   ├── Rest
│   │       │   │   │   └── Swagger
│   │       │   │   └── Soap
│   │       │   │       └── Wsdl
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   └── Unit
│   │       │   │       ├── Controller
│   │       │   │       │   ├── Rest
│   │       │   │       │   │   └── Router
│   │       │   │       │   └── Soap
│   │       │   │       │       └── Request
│   │       │   │       ├── _files
│   │       │   │       │   └── soap_fault
│   │       │   │       └── Model
│   │       │   │           ├── Authorization
│   │       │   │           ├── Config
│   │       │   │           │   └── _files
│   │       │   │           ├── _files
│   │       │   │           ├── Plugin
│   │       │   │           ├── Rest
│   │       │   │           │   └── Swagger
│   │       │   │           └── Soap
│   │       │   │               └── Wsdl
│   │       │   └── view
│   │       │       └── adminhtml
│   │       │           └── layout
│   │       ├── WebapiAsync
│   │       │   ├── Code
│   │       │   │   └── Generator
│   │       │   │       └── Config
│   │       │   │           └── RemoteServiceReader
│   │       │   ├── Controller
│   │       │   │   └── Rest
│   │       │   │       └── Asynchronous
│   │       │   ├── etc
│   │       │   │   └── webapi_rest
│   │       │   ├── Model
│   │       │   │   └── ServiceConfig
│   │       │   ├── Plugin
│   │       │   │   └── Cache
│   │       │   └── Test
│   │       │       ├── Mftf
│   │       │       └── Unit
│   │       │           ├── Controller
│   │       │           └── Model
│   │       │               └── ServiceConfig
│   │       │                   └── _files
│   │       │                       ├── Converter
│   │       │                       └── Reader
│   │       ├── WebapiSecurity
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   └── Plugin
│   │       │   └── Test
│   │       │       └── Mftf
│   │       ├── Weee
│   │       │   ├── Api
│   │       │   │   └── Data
│   │       │   │       └── ProductRender
│   │       │   ├── Block
│   │       │   │   ├── Adminhtml
│   │       │   │   │   └── Items
│   │       │   │   │       └── Price
│   │       │   │   ├── Element
│   │       │   │   │   └── Weee
│   │       │   │   ├── Item
│   │       │   │   │   └── Price
│   │       │   │   ├── Renderer
│   │       │   │   │   └── Weee
│   │       │   │   └── Sales
│   │       │   │       └── Order
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── App
│   │       │   │   │   └── Action
│   │       │   │   ├── Attribute
│   │       │   │   │   └── Backend
│   │       │   │   │       └── Weee
│   │       │   │   ├── Config
│   │       │   │   │   └── Source
│   │       │   │   ├── ProductRender
│   │       │   │   ├── ResourceModel
│   │       │   │   │   └── Attribute
│   │       │   │   │       └── Backend
│   │       │   │   │           └── Weee
│   │       │   │   ├── Sales
│   │       │   │   │   └── Pdf
│   │       │   │   └── Total
│   │       │   │       ├── Creditmemo
│   │       │   │       ├── Invoice
│   │       │   │       └── Quote
│   │       │   ├── Observer
│   │       │   ├── Plugin
│   │       │   │   ├── Catalog
│   │       │   │   │   └── Controller
│   │       │   │   │       └── Adminhtml
│   │       │   │   │           └── Product
│   │       │   │   │               └── Initialization
│   │       │   │   │                   └── Helper
│   │       │   │   ├── Checkout
│   │       │   │   │   └── CustomerData
│   │       │   │   └── Ui
│   │       │   │       └── DataProvider
│   │       │   ├── Pricing
│   │       │   │   └── Render
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Metadata
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── App
│   │       │   │       │   └── Action
│   │       │   │       ├── Block
│   │       │   │       │   ├── Element
│   │       │   │       │   │   └── Weee
│   │       │   │       │   └── Item
│   │       │   │       │       └── Price
│   │       │   │       ├── Helper
│   │       │   │       ├── Model
│   │       │   │       │   ├── Attribute
│   │       │   │       │   │   └── Backend
│   │       │   │       │   │       └── Weee
│   │       │   │       │   ├── ResourceModel
│   │       │   │       │   │   └── Attribute
│   │       │   │       │   │       └── Backend
│   │       │   │       │   │           └── Weee
│   │       │   │       │   └── Total
│   │       │   │       │       ├── Creditmemo
│   │       │   │       │       ├── Invoice
│   │       │   │       │       └── Quote
│   │       │   │       ├── Observer
│   │       │   │       ├── Pricing
│   │       │   │       │   └── Render
│   │       │   │       └── Ui
│   │       │   │           └── DataProvider
│   │       │   │               └── Product
│   │       │   │                   ├── Form
│   │       │   │                   │   └── Modifier
│   │       │   │                   │       └── Manager
│   │       │   │                   └── Listing
│   │       │   │                       └── Collector
│   │       │   ├── Ui
│   │       │   │   └── DataProvider
│   │       │   │       └── Product
│   │       │   │           ├── Form
│   │       │   │           │   └── Modifier
│   │       │   │           │       └── Manager
│   │       │   │           └── Listing
│   │       │   │               └── Collector
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   │   ├── items
│   │       │       │   │   │   └── price
│   │       │       │   │   ├── order
│   │       │       │   │   │   └── create
│   │       │       │   │   │       └── items
│   │       │       │   │   │           └── price
│   │       │       │   │   └── renderer
│   │       │       │   ├── ui_component
│   │       │       │   └── web
│   │       │       │       └── js
│   │       │       ├── base
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   │   └── pricing
│   │       │       │   └── web
│   │       │       │       ├── js
│   │       │       │       │   └── price
│   │       │       │       └── template
│   │       │       │           └── price
│   │       │       └── frontend
│   │       │           ├── layout
│   │       │           ├── templates
│   │       │           │   ├── checkout
│   │       │           │   │   ├── cart
│   │       │           │   │   │   └── item
│   │       │           │   │   │       └── price
│   │       │           │   │   └── onepage
│   │       │           │   │       └── review
│   │       │           │   │           └── item
│   │       │           │   │               └── price
│   │       │           │   ├── email
│   │       │           │   │   └── items
│   │       │           │   │       └── price
│   │       │           │   └── item
│   │       │           │       └── price
│   │       │           ├── ui_component
│   │       │           └── web
│   │       │               ├── js
│   │       │               │   └── view
│   │       │               │       ├── cart
│   │       │               │       │   └── totals
│   │       │               │       └── checkout
│   │       │               │           └── summary
│   │       │               │               └── item
│   │       │               │                   └── price
│   │       │               └── template
│   │       │                   └── checkout
│   │       │                       └── summary
│   │       │                           └── item
│   │       │                               └── price
│   │       ├── WeeeGraphQl
│   │       │   ├── etc
│   │       │   └── Test
│   │       │       └── Mftf
│   │       ├── Widget
│   │       │   ├── Block
│   │       │   │   └── Adminhtml
│   │       │   │       └── Widget
│   │       │   │           ├── Catalog
│   │       │   │           │   └── Category
│   │       │   │           └── Instance
│   │       │   │               └── Edit
│   │       │   │                   ├── Chooser
│   │       │   │                   └── Tab
│   │       │   │                       └── Main
│   │       │   ├── Controller
│   │       │   │   └── Adminhtml
│   │       │   │       └── Widget
│   │       │   │           └── Instance
│   │       │   ├── etc
│   │       │   │   └── adminhtml
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Config
│   │       │   │   ├── Layout
│   │       │   │   ├── ResourceModel
│   │       │   │   │   ├── Layout
│   │       │   │   │   │   ├── Link
│   │       │   │   │   │   └── Update
│   │       │   │   │   └── Widget
│   │       │   │   │       └── Instance
│   │       │   │   │           └── Options
│   │       │   │   ├── Template
│   │       │   │   └── Widget
│   │       │   │       └── Instance
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       └── Data
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       └── Widget
│   │       │   │       │           ├── Catalog
│   │       │   │       │           │   └── Category
│   │       │   │       │           └── Instance
│   │       │   │       │               └── Edit
│   │       │   │       │                   ├── Chooser
│   │       │   │       │                   └── Tab
│   │       │   │       ├── Controller
│   │       │   │       │   └── Adminhtml
│   │       │   │       │       └── Widget
│   │       │   │       │           └── Instance
│   │       │   │       ├── Helper
│   │       │   │       └── Model
│   │       │   │           ├── Config
│   │       │   │           ├── _files
│   │       │   │           ├── ResourceModel
│   │       │   │           │   ├── Layout
│   │       │   │           │   │   ├── Link
│   │       │   │           │   │   └── Update
│   │       │   │           │   └── Widget
│   │       │   │           │       └── Instance
│   │       │   │           │           └── Options
│   │       │   │           ├── Template
│   │       │   │           └── Widget
│   │       │   └── view
│   │       │       ├── adminhtml
│   │       │       │   ├── layout
│   │       │       │   ├── templates
│   │       │       │   │   ├── catalog
│   │       │       │   │   │   └── category
│   │       │       │   │   │       └── widget
│   │       │       │   │   └── instance
│   │       │       │   │       └── edit
│   │       │       │   └── web
│   │       │       └── frontend
│   │       │           └── layout
│   │       ├── Wishlist
│   │       │   ├── Block
│   │       │   │   ├── Adminhtml
│   │       │   │   │   └── Widget
│   │       │   │   │       └── Grid
│   │       │   │   │           └── Column
│   │       │   │   │               └── Filter
│   │       │   │   ├── Cart
│   │       │   │   │   └── Item
│   │       │   │   │       └── Renderer
│   │       │   │   │           └── Actions
│   │       │   │   ├── Catalog
│   │       │   │   │   └── Product
│   │       │   │   │       ├── ProductList
│   │       │   │   │       │   └── Item
│   │       │   │   │       │       └── AddTo
│   │       │   │   │       └── View
│   │       │   │   │           └── AddTo
│   │       │   │   ├── Customer
│   │       │   │   │   └── Wishlist
│   │       │   │   │       └── Item
│   │       │   │   │           └── Column
│   │       │   │   ├── Item
│   │       │   │   ├── Rss
│   │       │   │   └── Share
│   │       │   │       └── Email
│   │       │   ├── Controller
│   │       │   │   ├── Index
│   │       │   │   └── Shared
│   │       │   ├── CustomerData
│   │       │   ├── etc
│   │       │   │   ├── adminhtml
│   │       │   │   └── frontend
│   │       │   ├── Helper
│   │       │   ├── i18n
│   │       │   ├── Model
│   │       │   │   ├── Config
│   │       │   │   │   └── Source
│   │       │   │   ├── Item
│   │       │   │   ├── Product
│   │       │   │   ├── ResourceModel
│   │       │   │   │   ├── Item
│   │       │   │   │   │   ├── Collection
│   │       │   │   │   │   └── Option
│   │       │   │   │   └── Wishlist
│   │       │   │   └── Rss
│   │       │   ├── Observer
│   │       │   ├── Plugin
│   │       │   │   └── Ui
│   │       │   │       └── DataProvider
│   │       │   ├── Pricing
│   │       │   │   ├── ConfiguredPrice
│   │       │   │   └── Render
│   │       │   ├── Setup
│   │       │   │   └── Patch
│   │       │   │       ├── Data
│   │       │   │       └── Schema
│   │       │   ├── Test
│   │       │   │   ├── Mftf
│   │       │   │   │   ├── ActionGroup
│   │       │   │   │   ├── Data
│   │       │   │   │   ├── Metadata
│   │       │   │   │   ├── Page
│   │       │   │   │   ├── Section
│   │       │   │   │   └── Test
│   │       │   │   └── Unit
│   │       │   │       ├── Block
│   │       │   │       │   ├── Adminhtml
│   │       │   │       │   │   └── Widget
│   │       │   │       │   │       └── Grid
│   │       │   │       │   │           └── Column
│   │       │   │       │   │               └── Filter
│   │       │   │       │   ├── Cart
│   │       │   │       │   │   └── Item
│   │       │   │       │   │       └── Renderer
│   │       │   │       │   │           └── Actions
│   │       │   │       │   ├── Customer
│   │       │   │       │   │   └── Wishlist
│   │       │   │       │   │       └── Item
│   │       │   │       │   ├── Item
│   │       │   │       │   └── Rss
│   │       │   │       ├── Controller
│   │       │   │       │   ├── Index
│   │       │   │       │   └── Shared
│   │       │   │       ├── CustomerData
│   │       │   │       ├── DataProvider
│   │       │   │       │   └── Product
│   │       │   │       │       └── Collector
│   │       │   │       ├── Helper
│   │       │   │       ├── Model
│   │       │   │       │   ├── Product
│   │       │   │       │   ├── ResourceModel
│   │       │   │       │   │   └── Item
│   │       │   │       │   └── Rss
│   │       │   │       ├── Observer
│   │       │   │       ├── Plugin
│   │       │   │       │   └── Ui
│   │       │   │       │       └── DataProvider
│   │       │   │       └── Pricing
│   │       │   │           ├── ConfiguredPrice
│   │       │   │           └── Render
│   │       │   ├── Ui
│   │       │   │   └── DataProvider
│   │       │   │       └── Product
│   │       │   │           └── Collector
│   │       │   ├── view
│   │       │   │   ├── adminhtml
│   │       │   │   │   ├── layout
│   │       │   │   │   └── templates
│   │       │   │   │       └── customer
│   │       │   │   │           └── edit
│   │       │   │   │               └── tab
│   │       │   │   ├── base
│   │       │   │   │   ├── layout
│   │       │   │   │   ├── templates
│   │       │   │   │   │   └── product
│   │       │   │   │   │       └── price
│   │       │   │   │   │           ├── bundle
│   │       │   │   │   │           └── configurable
│   │       │   │   │   └── ui_component
│   │       │   │   └── frontend
│   │       │   │       ├── email
│   │       │   │       ├── layout
│   │       │   │       ├── templates
│   │       │   │       │   ├── button
│   │       │   │       │   ├── cart
│   │       │   │       │   │   └── item
│   │       │   │       │   │       └── renderer
│   │       │   │       │   │           └── actions
│   │       │   │       │   ├── catalog
│   │       │   │       │   │   └── product
│   │       │   │       │   │       ├── list
│   │       │   │       │   │       │   └── addto
│   │       │   │       │   │       └── view
│   │       │   │       │   │           └── addto
│   │       │   │       │   ├── email
│   │       │   │       │   ├── item
│   │       │   │       │   │   ├── column
│   │       │   │       │   │   └── configure
│   │       │   │       │   │       └── addto
│   │       │   │       │   ├── js
│   │       │   │       │   ├── messages
│   │       │   │       │   └── rss
│   │       │   │       ├── ui_component
│   │       │   │       └── web
│   │       │   │           ├── js
│   │       │   │           │   ├── product
│   │       │   │           │   └── view
│   │       │   │           └── template
│   │       │   │               └── product
│   │       │   └── ViewModel
│   │       ├── WishlistAnalytics
│   │       │   ├── etc
│   │       │   └── Test
│   │       │       └── Mftf
│   │       └── WishlistGraphQl
│   │           ├── etc
│   │           └── Model
│   │               └── Resolver
│   ├── design
│   │   ├── adminhtml
│   │   │   └── Magento
│   │   │       └── backend
│   │   │           ├── etc
│   │   │           ├── Magento_AdminNotification
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_AdvancedCheckout
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_Analytics
│   │   │           │   └── web
│   │   │           │       ├── css
│   │   │           │       │   └── source
│   │   │           │       └── images
│   │   │           ├── Magento_Backend
│   │   │           │   ├── layout
│   │   │           │   └── web
│   │   │           │       ├── css
│   │   │           │       │   └── source
│   │   │           │       │       └── module
│   │   │           │       │           ├── header
│   │   │           │       │           │   ├── actions-group
│   │   │           │       │           │   └── headings-group
│   │   │           │       │           ├── main
│   │   │           │       │           │   └── actions-bar
│   │   │           │       │           └── pages
│   │   │           │       └── images
│   │   │           ├── Magento_Banner
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_Braintree
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_Catalog
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_CatalogPermissions
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_Config
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_ConfigurableProduct
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           │               └── module
│   │   │           │                   ├── components
│   │   │           │                   │   └── navigation-bar
│   │   │           │                   └── steps
│   │   │           ├── Magento_CurrencySymbol
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_Customer
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_CustomerBalance
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_Developer
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_Downloadable
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_Enterprise
│   │   │           │   ├── layout
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_GiftCard
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_GiftRegistry
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_GiftWrapping
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_Integration
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_Marketplace
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_Msrp
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_ProductVideo
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_ReleaseNotification
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_Review
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_Reward
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_Rma
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_Sales
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           │               └── module
│   │   │           │                   └── order
│   │   │           ├── Magento_Shipping
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_Signifyd
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           │               └── module
│   │   │           ├── Magento_Staging
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           │               └── module
│   │   │           ├── Magento_Tax
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_Theme
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_Translation
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_Ui
│   │   │           │   └── web
│   │   │           │       ├── css
│   │   │           │       │   └── source
│   │   │           │       │       └── module
│   │   │           │       │           └── data-grid
│   │   │           │       │               └── data-grid-header
│   │   │           │       └── images
│   │   │           ├── Magento_Vault
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_VersionsCms
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           ├── Magento_VisualMerchandiser
│   │   │           │   └── web
│   │   │           │       └── css
│   │   │           │           └── source
│   │   │           └── web
│   │   │               ├── app
│   │   │               │   ├── setup
│   │   │               │   │   └── styles
│   │   │               │   │       └── less
│   │   │               │   │           ├── components
│   │   │               │   │           │   └── tooltips
│   │   │               │   │           ├── lib
│   │   │               │   │           │   ├── forms
│   │   │               │   │           │   └── utilities
│   │   │               │   │           └── pages
│   │   │               │   └── updater
│   │   │               │       └── styles
│   │   │               │           └── less
│   │   │               │               ├── components
│   │   │               │               ├── pages
│   │   │               │               └── source
│   │   │               ├── css
│   │   │               │   └── source
│   │   │               │       ├── actions
│   │   │               │       ├── components
│   │   │               │       ├── forms
│   │   │               │       │   ├── controls
│   │   │               │       │   └── fields
│   │   │               │       ├── utilities
│   │   │               │       └── variables
│   │   │               ├── fonts
│   │   │               │   └── admin-icons
│   │   │               ├── images
│   │   │               ├── js
│   │   │               └── mui
│   │   │                   ├── clearless
│   │   │                   ├── images
│   │   │                   └── styles
│   │   └── frontend
│   │       └── Magento
│   │           ├── blank
│   │           │   ├── etc
│   │           │   ├── i18n
│   │           │   ├── Magento_AdvancedCheckout
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_Banner
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_Braintree
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_Bundle
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_Catalog
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   │               └── module
│   │           │   ├── Magento_CatalogEvent
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_CatalogSearch
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_Checkout
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   │               └── module
│   │           │   │                   └── checkout
│   │           │   ├── Magento_Cms
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_Customer
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_Downloadable
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_GiftCard
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_GiftCardAccount
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_GiftMessage
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_GiftRegistry
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_GiftWrapping
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_GroupedProduct
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_Invitation
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_LayeredNavigation
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_Msrp
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_MultipleWishlist
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_Multishipping
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_Newsletter
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_Paypal
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   │               └── module
│   │           │   ├── Magento_ProductVideo
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_Reports
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_Review
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_Reward
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_Rma
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_Sales
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_SalesRule
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_SendFriend
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_Swatches
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_Theme
│   │           │   │   ├── layout
│   │           │   │   └── web
│   │           │   │       ├── css
│   │           │   │       │   └── source
│   │           │   │       └── js
│   │           │   ├── Magento_Vault
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_VersionsCms
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_Weee
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── Magento_Wishlist
│   │           │   │   └── web
│   │           │   │       └── css
│   │           │   │           └── source
│   │           │   ├── media
│   │           │   └── web
│   │           │       ├── css
│   │           │       │   └── source
│   │           │       │       └── components
│   │           │       ├── images
│   │           │       └── js
│   │           └── luma
│   │               ├── etc
│   │               ├── i18n
│   │               ├── Magento_AdvancedCheckout
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               ├── Magento_AdvancedSearch
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               ├── Magento_Bundle
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               ├── Magento_Catalog
│   │               │   ├── layout
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               │               └── module
│   │               ├── Magento_CatalogSearch
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               ├── Magento_Checkout
│   │               │   ├── layout
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               │               └── module
│   │               │                   └── checkout
│   │               │                       └── fields
│   │               ├── Magento_Customer
│   │               │   ├── email
│   │               │   ├── layout
│   │               │   └── web
│   │               │       ├── css
│   │               │       │   └── source
│   │               │       └── images
│   │               ├── Magento_CustomerBalance
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               ├── Magento_Downloadable
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               ├── Magento_Email
│   │               │   ├── email
│   │               │   └── web
│   │               ├── Magento_GiftCard
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               ├── Magento_GiftCardAccount
│   │               │   ├── layout
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               ├── Magento_GiftMessage
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               ├── Magento_GiftRegistry
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               ├── Magento_GiftWrapping
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               ├── Magento_GroupedProduct
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               ├── Magento_InstantPurchase
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               ├── Magento_Invitation
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               ├── Magento_LayeredNavigation
│   │               │   ├── templates
│   │               │   │   └── layer
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               ├── Magento_Msrp
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               ├── Magento_MultipleWishlist
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               ├── Magento_Multishipping
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               ├── Magento_Newsletter
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               ├── Magento_Paypal
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               │               └── module
│   │               ├── Magento_Review
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               ├── Magento_Reward
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               ├── Magento_Rma
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               ├── Magento_Sales
│   │               │   ├── email
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               ├── Magento_SendFriend
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               ├── Magento_Theme
│   │               │   ├── layout
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               │               └── module
│   │               ├── Magento_Vault
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               ├── Magento_Wishlist
│   │               │   └── web
│   │               │       └── css
│   │               │           └── source
│   │               ├── media
│   │               └── web
│   │                   ├── css
│   │                   │   └── source
│   │                   │       └── components
│   │                   ├── fonts
│   │                   └── images
│   ├── etc
│   └── i18n
│       └── Magento
│           ├── de_DE
│           ├── en_US
│           ├── es_ES
│           ├── fr_FR
│           ├── nl_NL
│           ├── pt_BR
│           └── zh_Hans_CN
├── bin
├── dev
│   ├── tests
│   │   ├── acceptance
│   │   │   └── tests
│   │   │       ├── _data
│   │   │       ├── functional
│   │   │       │   └── Magento
│   │   │       │       └── FunctionalTest
│   │   │       │           ├── ConfigurableProductCatalogSearch
│   │   │       │           │   └── Test
│   │   │       │           └── ConfigurableProductWishlist
│   │   │       │               ├── ActionGroup
│   │   │       │               └── Test
│   │   │       └── _suite
│   │   ├── api-functional
│   │   │   ├── config
│   │   │   ├── _files
│   │   │   │   └── Magento
│   │   │   │       ├── TestModule1
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── CookieTester
│   │   │   │       │   ├── etc
│   │   │   │       │   │   └── frontend
│   │   │   │       │   └── Service
│   │   │   │       │       ├── V1
│   │   │   │       │       │   └── Entity
│   │   │   │       │       └── V2
│   │   │   │       │           └── Entity
│   │   │   │       ├── TestModule2
│   │   │   │       │   ├── etc
│   │   │   │       │   │   └── schema
│   │   │   │       │   └── Service
│   │   │   │       │       └── V1
│   │   │   │       │           └── Entity
│   │   │   │       ├── TestModule3
│   │   │   │       │   ├── etc
│   │   │   │       │   └── Service
│   │   │   │       │       └── V1
│   │   │   │       │           └── Entity
│   │   │   │       ├── TestModule4
│   │   │   │       │   ├── etc
│   │   │   │       │   ├── Model
│   │   │   │       │   │   └── ResourceModel
│   │   │   │       │   └── Service
│   │   │   │       │       └── V1
│   │   │   │       │           └── Entity
│   │   │   │       ├── TestModule5
│   │   │   │       │   ├── etc
│   │   │   │       │   └── Service
│   │   │   │       │       ├── V1
│   │   │   │       │       │   └── Entity
│   │   │   │       │       └── V2
│   │   │   │       │           └── Entity
│   │   │   │       ├── TestModuleDefaultHydrator
│   │   │   │       │   ├── Api
│   │   │   │       │   │   └── Data
│   │   │   │       │   ├── etc
│   │   │   │       │   └── Model
│   │   │   │       │       ├── Address
│   │   │   │       │       ├── Data
│   │   │   │       │       └── ResourceModel
│   │   │   │       │           └── Address
│   │   │   │       ├── TestModuleGraphQlQuery
│   │   │   │       │   ├── etc
│   │   │   │       │   └── Model
│   │   │   │       │       └── Resolver
│   │   │   │       ├── TestModuleGraphQlQueryExtension
│   │   │   │       │   ├── etc
│   │   │   │       │   └── Model
│   │   │   │       │       └── Resolver
│   │   │   │       ├── TestModuleIntegrationFromConfig
│   │   │   │       │   └── etc
│   │   │   │       ├── TestModuleJoinDirectives
│   │   │   │       │   ├── Api
│   │   │   │       │   ├── etc
│   │   │   │       │   └── Model
│   │   │   │       └── TestModuleMSC
│   │   │   │           ├── Api
│   │   │   │           │   └── Data
│   │   │   │           ├── etc
│   │   │   │           └── Model
│   │   │   │               ├── Data
│   │   │   │               │   └── Eav
│   │   │   │               └── ResourceModel
│   │   │   ├── framework
│   │   │   │   └── Magento
│   │   │   │       └── TestFramework
│   │   │   │           ├── Annotation
│   │   │   │           ├── Assert
│   │   │   │           ├── Authentication
│   │   │   │           │   └── Rest
│   │   │   │           │       └── OauthClient
│   │   │   │           ├── Bootstrap
│   │   │   │           ├── Helper
│   │   │   │           └── TestCase
│   │   │   │               ├── GraphQl
│   │   │   │               ├── HttpClient
│   │   │   │               └── Webapi
│   │   │   │                   └── Adapter
│   │   │   │                       └── Rest
│   │   │   └── testsuite
│   │   │       └── Magento
│   │   │           ├── Analytics
│   │   │           │   └── Api
│   │   │           ├── AsynchronousOperations
│   │   │           │   └── Api
│   │   │           ├── Bundle
│   │   │           │   └── Api
│   │   │           ├── Catalog
│   │   │           │   └── Api
│   │   │           │       └── _files
│   │   │           ├── CatalogInventory
│   │   │           │   └── Api
│   │   │           ├── CheckoutAgreements
│   │   │           │   └── Api
│   │   │           ├── Cms
│   │   │           │   └── Api
│   │   │           ├── ConfigurableProduct
│   │   │           │   └── Api
│   │   │           ├── Customer
│   │   │           │   └── Api
│   │   │           │       └── _files
│   │   │           ├── Directory
│   │   │           │   └── Api
│   │   │           ├── Downloadable
│   │   │           │   └── Api
│   │   │           │       └── _files
│   │   │           ├── Eav
│   │   │           │   └── Api
│   │   │           ├── Framework
│   │   │           │   ├── Api
│   │   │           │   │   └── Search
│   │   │           │   ├── Model
│   │   │           │   │   └── Entity
│   │   │           │   └── Stdlib
│   │   │           ├── GiftMessage
│   │   │           │   └── Api
│   │   │           ├── GraphQl
│   │   │           │   ├── Bundle
│   │   │           │   ├── Catalog
│   │   │           │   ├── CatalogInventory
│   │   │           │   ├── CheckoutAgreements
│   │   │           │   ├── Cms
│   │   │           │   ├── ConfigurableProduct
│   │   │           │   ├── Customer
│   │   │           │   ├── Directory
│   │   │           │   ├── DownloadableProduct
│   │   │           │   ├── _files
│   │   │           │   ├── Framework
│   │   │           │   ├── GroupedProduct
│   │   │           │   ├── PageCache
│   │   │           │   │   ├── Cms
│   │   │           │   │   └── Quote
│   │   │           │   │       └── Guest
│   │   │           │   ├── Quote
│   │   │           │   │   ├── Customer
│   │   │           │   │   └── Guest
│   │   │           │   ├── RelatedProduct
│   │   │           │   ├── Sales
│   │   │           │   ├── SendFriend
│   │   │           │   ├── Store
│   │   │           │   ├── Swatches
│   │   │           │   ├── Tax
│   │   │           │   ├── TestModule
│   │   │           │   ├── Ups
│   │   │           │   ├── UrlRewrite
│   │   │           │   ├── Vault
│   │   │           │   └── Wishlist
│   │   │           ├── GroupedProduct
│   │   │           │   └── Api
│   │   │           ├── Integration
│   │   │           │   └── Model
│   │   │           ├── Quote
│   │   │           │   └── Api
│   │   │           ├── Sales
│   │   │           │   └── Service
│   │   │           │       └── V1
│   │   │           ├── SalesInventory
│   │   │           │   └── Api
│   │   │           │       └── Service
│   │   │           │           └── V1
│   │   │           ├── SalesRule
│   │   │           │   └── Api
│   │   │           ├── Search
│   │   │           │   └── Api
│   │   │           ├── Store
│   │   │           │   └── Api
│   │   │           ├── Tax
│   │   │           │   └── Api
│   │   │           ├── Webapi
│   │   │           │   ├── Authentication
│   │   │           │   ├── DataObjectSerialization
│   │   │           │   └── Routing
│   │   │           └── WebapiAsync
│   │   │               └── Model
│   │   ├── functional
│   │   │   ├── etc
│   │   │   ├── lib
│   │   │   │   └── Magento
│   │   │   │       └── Mtf
│   │   │   │           ├── App
│   │   │   │           │   └── State
│   │   │   │           ├── Client
│   │   │   │           │   └── Element
│   │   │   │           ├── Config
│   │   │   │           │   └── FileResolver
│   │   │   │           ├── Constraint
│   │   │   │           ├── EntryPoint
│   │   │   │           ├── Handler
│   │   │   │           ├── Page
│   │   │   │           ├── System
│   │   │   │           │   └── Observer
│   │   │   │           ├── Troubleshooting
│   │   │   │           │   └── Helper
│   │   │   │           └── Util
│   │   │   │               ├── Command
│   │   │   │               │   ├── Cli
│   │   │   │               │   └── File
│   │   │   │               │       └── Export
│   │   │   │               ├── Filesystem
│   │   │   │               ├── Generate
│   │   │   │               │   ├── Factory
│   │   │   │               │   ├── File
│   │   │   │               │   ├── Fixture
│   │   │   │               │   └── Repository
│   │   │   │               ├── ModuleResolver
│   │   │   │               └── Protocol
│   │   │   │                   └── CurlTransport
│   │   │   ├── tests
│   │   │   │   └── app
│   │   │   │       └── Magento
│   │   │   │           ├── AdminNotification
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── System
│   │   │   │           │       │       └── Messages
│   │   │   │           │       └── TestCase
│   │   │   │           ├── AdvancedPricingImportExport
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       ├── _files
│   │   │   │           │       │   └── template
│   │   │   │           │       │       └── pricing
│   │   │   │           │       ├── Repository
│   │   │   │           │       └── TestCase
│   │   │   │           ├── Analytics
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   ├── Adminhtml
│   │   │   │           │       │   │   └── Dashboard
│   │   │   │           │       │   │       └── AdvancedReporting
│   │   │   │           │       │   └── System
│   │   │   │           │       │       └── Config
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Repository
│   │   │   │           │       ├── TestCase
│   │   │   │           │       └── TestStep
│   │   │   │           ├── Authorizenet
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   ├── Form
│   │   │   │           │       │   └── Sandbox
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       ├── Fixture
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Sandbox
│   │   │   │           │       ├── Repository
│   │   │   │           │       ├── TestCase
│   │   │   │           │       └── TestStep
│   │   │   │           ├── Backend
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   ├── Admin
│   │   │   │           │       │   ├── Dashboard
│   │   │   │           │       │   │   └── Tab
│   │   │   │           │       │   │       └── Products
│   │   │   │           │       │   ├── Page
│   │   │   │           │       │   ├── System
│   │   │   │           │       │   │   ├── Config
│   │   │   │           │       │   │   │   └── Form
│   │   │   │           │       │   │   └── Store
│   │   │   │           │       │   │       ├── Delete
│   │   │   │           │       │   │       └── Edit
│   │   │   │           │       │   │           └── Form
│   │   │   │           │       │   └── Widget
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   ├── Admin
│   │   │   │           │       │   ├── GlobalSearch
│   │   │   │           │       │   └── Source
│   │   │   │           │       ├── Handler
│   │   │   │           │       │   └── Ui
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Repository
│   │   │   │           │       ├── TestCase
│   │   │   │           │       └── TestStep
│   │   │   │           ├── Backup
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       └── Repository
│   │   │   │           ├── Braintree
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   ├── Adminhtml
│   │   │   │           │       │   │   └── Report
│   │   │   │           │       │   ├── Form
│   │   │   │           │       │   ├── Paypal
│   │   │   │           │       │   └── System
│   │   │   │           │       │       └── Config
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       ├── Fixture
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Repository
│   │   │   │           │       ├── TestCase
│   │   │   │           │       └── TestStep
│   │   │   │           ├── Bundle
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   ├── Adminhtml
│   │   │   │           │       │   │   ├── Catalog
│   │   │   │           │       │   │   │   └── Product
│   │   │   │           │       │   │   │       └── Edit
│   │   │   │           │       │   │   │           └── Section
│   │   │   │           │       │   │   │               └── Bundle
│   │   │   │           │       │   │   │                   └── Option
│   │   │   │           │       │   │   │                       └── Search
│   │   │   │           │       │   │   └── Product
│   │   │   │           │       │   │       └── Composite
│   │   │   │           │       │   └── Catalog
│   │   │   │           │       │       └── Product
│   │   │   │           │       │           └── View
│   │   │   │           │       │               ├── Summary
│   │   │   │           │       │               └── Type
│   │   │   │           │       │                   └── Option
│   │   │   │           │       │                       └── Element
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       │   ├── curl
│   │   │   │           │       │   └── webapi
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   ├── BundleProduct
│   │   │   │           │       │   └── Cart
│   │   │   │           │       ├── Handler
│   │   │   │           │       │   └── BundleProduct
│   │   │   │           │       ├── Page
│   │   │   │           │       │   ├── Adminhtml
│   │   │   │           │       │   └── Product
│   │   │   │           │       ├── Repository
│   │   │   │           │       │   └── BundleProduct
│   │   │   │           │       ├── TestCase
│   │   │   │           │       └── TestStep
│   │   │   │           ├── BundleImportExport
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   └── Import
│   │   │   │           │       └── TestCase
│   │   │   │           ├── Captcha
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   ├── Adminhtml
│   │   │   │           │       │   └── Form
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── Fixture
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Repository
│   │   │   │           │       └── TestCase
│   │   │   │           ├── Catalog
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   ├── Adminhtml
│   │   │   │           │       │   │   ├── Category
│   │   │   │           │       │   │   │   ├── Edit
│   │   │   │           │       │   │   │   │   └── Section
│   │   │   │           │       │   │   │   └── Widget
│   │   │   │           │       │   │   └── Product
│   │   │   │           │       │   │       ├── Attribute
│   │   │   │           │       │   │       │   ├── Edit
│   │   │   │           │       │   │       │   │   └── Tab
│   │   │   │           │       │   │       │   │       └── Options
│   │   │   │           │       │   │       │   └── Set
│   │   │   │           │       │   │       │       └── Main
│   │   │   │           │       │   │       ├── Composite
│   │   │   │           │       │   │       ├── Edit
│   │   │   │           │       │   │       │   ├── Action
│   │   │   │           │       │   │       │   │   └── Tab
│   │   │   │           │       │   │       │   └── Section
│   │   │   │           │       │   │       │       ├── AdvancedPricing
│   │   │   │           │       │   │       │       ├── Attributes
│   │   │   │           │       │   │       │       ├── Options
│   │   │   │           │       │   │       │       │   ├── Search
│   │   │   │           │       │   │       │       │   └── Type
│   │   │   │           │       │   │       │       ├── ProductDetails
│   │   │   │           │       │   │       │       ├── Related
│   │   │   │           │       │   │       │       └── Websites
│   │   │   │           │       │   │       ├── Modal
│   │   │   │           │       │   │       └── Widget
│   │   │   │           │       │   ├── Category
│   │   │   │           │       │   ├── Links
│   │   │   │           │       │   └── Product
│   │   │   │           │       │       ├── Compare
│   │   │   │           │       │       ├── Grouped
│   │   │   │           │       │       │   └── AssociatedProducts
│   │   │   │           │       │       │       ├── ListAssociatedProducts
│   │   │   │           │       │       │       └── Search
│   │   │   │           │       │       ├── ProductList
│   │   │   │           │       │       │   └── Related
│   │   │   │           │       │       └── View
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       │   ├── curl
│   │   │   │           │       │   ├── ui
│   │   │   │           │       │   └── webapi
│   │   │   │           │       ├── _files
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   ├── Cart
│   │   │   │           │       │   ├── CatalogAttributeSet
│   │   │   │           │       │   ├── CatalogProductSimple
│   │   │   │           │       │   ├── Category
│   │   │   │           │       │   └── Product
│   │   │   │           │       ├── Handler
│   │   │   │           │       │   ├── CatalogAttributeSet
│   │   │   │           │       │   ├── CatalogProductAttribute
│   │   │   │           │       │   ├── CatalogProductSimple
│   │   │   │           │       │   ├── CatalogProductVirtual
│   │   │   │           │       │   └── Category
│   │   │   │           │       ├── Page
│   │   │   │           │       │   ├── Adminhtml
│   │   │   │           │       │   ├── Category
│   │   │   │           │       │   └── Product
│   │   │   │           │       ├── Repository
│   │   │   │           │       │   ├── CatalogProductAttribute
│   │   │   │           │       │   ├── CatalogProductSimple
│   │   │   │           │       │   ├── CatalogProductVirtual
│   │   │   │           │       │   └── Product
│   │   │   │           │       ├── TestCase
│   │   │   │           │       │   ├── Category
│   │   │   │           │       │   ├── Product
│   │   │   │           │       │   └── ProductAttribute
│   │   │   │           │       └── TestStep
│   │   │   │           ├── CatalogImportExport
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       ├── _files
│   │   │   │           │       │   └── template
│   │   │   │           │       └── TestCase
│   │   │   │           ├── CatalogInventory
│   │   │   │           │   └── Test
│   │   │   │           │       └── Repository
│   │   │   │           ├── CatalogRule
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       │       └── Promo
│   │   │   │           │       │           └── Catalog
│   │   │   │           │       │               └── Edit
│   │   │   │           │       │                   └── Section
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       │   ├── curl
│   │   │   │           │       │   └── ui
│   │   │   │           │       ├── Fixture
│   │   │   │           │       ├── Handler
│   │   │   │           │       │   └── CatalogRule
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Repository
│   │   │   │           │       ├── TestCase
│   │   │   │           │       └── TestStep
│   │   │   │           ├── CatalogRuleConfigurable
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Constraint
│   │   │   │           │       └── TestCase
│   │   │   │           ├── CatalogSearch
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   ├── Adminhtml
│   │   │   │           │       │   │   └── Edit
│   │   │   │           │       │   └── Advanced
│   │   │   │           │       │       └── CustomAttribute
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       │   └── curl
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   └── CatalogSearchQuery
│   │   │   │           │       ├── Handler
│   │   │   │           │       │   └── CatalogSearchQuery
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Repository
│   │   │   │           │       └── TestCase
│   │   │   │           ├── CatalogUrlRewrite
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       │       └── Category
│   │   │   │           │       │           └── Edit
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       ├── Fixture
│   │   │   │           │       └── TestCase
│   │   │   │           ├── Checkout
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   ├── Cart
│   │   │   │           │       │   │   └── Sidebar
│   │   │   │           │       │   └── Onepage
│   │   │   │           │       │       ├── Payment
│   │   │   │           │       │       │   └── Method
│   │   │   │           │       │       └── Shipping
│   │   │   │           │       ├── Constraint
│   │   │   │           │       │   └── Utils
│   │   │   │           │       ├── etc
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   └── Cart
│   │   │   │           │       ├── Page
│   │   │   │           │       ├── Repository
│   │   │   │           │       ├── TestCase
│   │   │   │           │       └── TestStep
│   │   │   │           ├── CheckoutAgreements
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   ├── Adminhtml
│   │   │   │           │       │   │   └── Block
│   │   │   │           │       │   │       └── Agreement
│   │   │   │           │       │   │           └── Edit
│   │   │   │           │       │   ├── Multishipping
│   │   │   │           │       │   └── Onepage
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       │   └── curl
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   └── CheckoutAgreement
│   │   │   │           │       ├── Handler
│   │   │   │           │       │   └── CheckoutAgreement
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Repository
│   │   │   │           │       ├── TestCase
│   │   │   │           │       └── TestStep
│   │   │   │           ├── Cms
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       │       ├── Block
│   │   │   │           │       │       │   └── Edit
│   │   │   │           │       │       ├── Page
│   │   │   │           │       │       │   ├── Edit
│   │   │   │           │       │       │   │   └── Tab
│   │   │   │           │       │       │   └── Widget
│   │   │   │           │       │       └── Wysiwyg
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       │   └── curl
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   ├── CmsBlock
│   │   │   │           │       │   └── CmsPage
│   │   │   │           │       ├── Handler
│   │   │   │           │       │   ├── CmsBlock
│   │   │   │           │       │   └── CmsPage
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Repository
│   │   │   │           │       │   └── CmsPage
│   │   │   │           │       └── TestCase
│   │   │   │           ├── Config
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── System
│   │   │   │           │       │       └── Config
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       │   └── curl
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   └── ConfigData
│   │   │   │           │       ├── Handler
│   │   │   │           │       │   └── ConfigData
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── TestCase
│   │   │   │           │       └── TestStep
│   │   │   │           ├── ConfigurableImportExport
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   └── Import
│   │   │   │           │       └── TestCase
│   │   │   │           ├── ConfigurableProduct
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   ├── Adminhtml
│   │   │   │           │       │   │   └── Product
│   │   │   │           │       │   │       ├── Composite
│   │   │   │           │       │   │       └── Edit
│   │   │   │           │       │   │           └── Section
│   │   │   │           │       │   │               └── Variations
│   │   │   │           │       │   │                   └── Config
│   │   │   │           │       │   │                       └── Attribute
│   │   │   │           │       │   └── Product
│   │   │   │           │       │       └── View
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       │   ├── curl
│   │   │   │           │       │   └── webapi
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   ├── Cart
│   │   │   │           │       │   └── ConfigurableProduct
│   │   │   │           │       ├── Handler
│   │   │   │           │       │   └── ConfigurableProduct
│   │   │   │           │       ├── Page
│   │   │   │           │       │   ├── Adminhtml
│   │   │   │           │       │   └── Product
│   │   │   │           │       ├── Repository
│   │   │   │           │       │   └── ConfigurableProduct
│   │   │   │           │       ├── TestCase
│   │   │   │           │       └── TestStep
│   │   │   │           ├── Contact
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Form
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   └── Comment
│   │   │   │           │       └── Page
│   │   │   │           ├── CurrencySymbol
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       │       └── System
│   │   │   │           │       │           └── Currency
│   │   │   │           │       │               └── Rate
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       │   └── curl
│   │   │   │           │       ├── Fixture
│   │   │   │           │       ├── Handler
│   │   │   │           │       │   └── CurrencySymbolEntity
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Repository
│   │   │   │           │       └── TestCase
│   │   │   │           ├── Customer
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   ├── Account
│   │   │   │           │       │   │   └── Dashboard
│   │   │   │           │       │   ├── Address
│   │   │   │           │       │   ├── Adminhtml
│   │   │   │           │       │   │   ├── Edit
│   │   │   │           │       │   │   │   └── Tab
│   │   │   │           │       │   │   │       └── Addresses
│   │   │   │           │       │   │   └── Group
│   │   │   │           │       │   │       └── Edit
│   │   │   │           │       │   └── Form
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       │   ├── curl
│   │   │   │           │       │   └── webapi
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   ├── Customer
│   │   │   │           │       │   └── CustomerGroup
│   │   │   │           │       ├── Handler
│   │   │   │           │       │   ├── Customer
│   │   │   │           │       │   └── CustomerGroup
│   │   │   │           │       ├── Page
│   │   │   │           │       │   ├── Address
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Repository
│   │   │   │           │       ├── TestCase
│   │   │   │           │       └── TestStep
│   │   │   │           ├── CustomerImportExport
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       ├── _files
│   │   │   │           │       │   └── template
│   │   │   │           │       │       └── address
│   │   │   │           │       ├── Repository
│   │   │   │           │       ├── TestCase
│   │   │   │           │       └── TestStep
│   │   │   │           ├── Dhl
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Repository
│   │   │   │           │       └── TestCase
│   │   │   │           ├── Directory
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Currency
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       │   └── curl
│   │   │   │           │       ├── Fixture
│   │   │   │           │       ├── Handler
│   │   │   │           │       │   └── CurrencyRate
│   │   │   │           │       ├── Repository
│   │   │   │           │       └── TestCase
│   │   │   │           ├── Downloadable
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   ├── Adminhtml
│   │   │   │           │       │   │   ├── Catalog
│   │   │   │           │       │   │   │   └── Product
│   │   │   │           │       │   │   │       └── Edit
│   │   │   │           │       │   │   │           └── Section
│   │   │   │           │       │   │   │               └── Downloadable
│   │   │   │           │       │   │   └── Product
│   │   │   │           │       │   │       └── Composite
│   │   │   │           │       │   ├── Catalog
│   │   │   │           │       │   │   └── Product
│   │   │   │           │       │   │       └── View
│   │   │   │           │       │   └── Customer
│   │   │   │           │       │       └── Products
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       │   ├── curl
│   │   │   │           │       │   └── webapi
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   └── Cart
│   │   │   │           │       ├── Handler
│   │   │   │           │       │   └── DownloadableProduct
│   │   │   │           │       ├── Page
│   │   │   │           │       │   ├── Adminhtml
│   │   │   │           │       │   └── Product
│   │   │   │           │       ├── Repository
│   │   │   │           │       │   └── DownloadableProduct
│   │   │   │           │       └── TestCase
│   │   │   │           ├── Email
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       │       └── Template
│   │   │   │           │       │           └── Edit
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── Fixture
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       └── TestCase
│   │   │   │           ├── Fedex
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Repository
│   │   │   │           │       └── TestCase
│   │   │   │           ├── GiftMessage
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   ├── Adminhtml
│   │   │   │           │       │   │   └── Order
│   │   │   │           │       │   │       ├── Create
│   │   │   │           │       │   │       │   └── Items
│   │   │   │           │       │   │       └── View
│   │   │   │           │       │   │           └── Items
│   │   │   │           │       │   ├── Cart
│   │   │   │           │       │   │   ├── GiftOptions
│   │   │   │           │       │   │   └── Item
│   │   │   │           │       │   └── Message
│   │   │   │           │       │       └── Order
│   │   │   │           │       │           └── Items
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   └── GiftMessage
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Repository
│   │   │   │           │       ├── TestCase
│   │   │   │           │       └── TestStep
│   │   │   │           ├── GroupedImportExport
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   └── Import
│   │   │   │           │       └── TestCase
│   │   │   │           ├── GroupedProduct
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   ├── Adminhtml
│   │   │   │           │       │   │   └── Product
│   │   │   │           │       │   │       ├── Composite
│   │   │   │           │       │   │       └── Grouped
│   │   │   │           │       │   │           └── AssociatedProducts
│   │   │   │           │       │   │               ├── ListAssociatedProducts
│   │   │   │           │       │   │               └── Search
│   │   │   │           │       │   ├── Cart
│   │   │   │           │       │   │   └── Sidebar
│   │   │   │           │       │   ├── Catalog
│   │   │   │           │       │   │   └── Product
│   │   │   │           │       │   │       └── View
│   │   │   │           │       │   │           └── Type
│   │   │   │           │       │   └── Checkout
│   │   │   │           │       │       └── Cart
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       │   ├── curl
│   │   │   │           │       │   └── webapi
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   ├── Cart
│   │   │   │           │       │   └── GroupedProduct
│   │   │   │           │       ├── Handler
│   │   │   │           │       │   └── GroupedProduct
│   │   │   │           │       ├── Page
│   │   │   │           │       │   ├── Adminhtml
│   │   │   │           │       │   └── Product
│   │   │   │           │       ├── Repository
│   │   │   │           │       │   └── GroupedProduct
│   │   │   │           │       └── TestCase
│   │   │   │           ├── ImportExport
│   │   │   │           │   ├── Mtf
│   │   │   │           │   │   └── Util
│   │   │   │           │   │       └── Import
│   │   │   │           │   │           └── File
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       │       ├── Export
│   │   │   │           │       │       │   └── Edit
│   │   │   │           │       │       └── Import
│   │   │   │           │       │           ├── Edit
│   │   │   │           │       │           └── Frame
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   ├── ExportData
│   │   │   │           │       │   └── Import
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Repository
│   │   │   │           │       ├── TestCase
│   │   │   │           │       └── TestStep
│   │   │   │           ├── Indexer
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       │       └── IndexManagement
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── TestCase
│   │   │   │           │       └── TestStep
│   │   │   │           ├── Install
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── Fixture
│   │   │   │           │       ├── Page
│   │   │   │           │       └── TestCase
│   │   │   │           ├── Integration
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       │       └── Integration
│   │   │   │           │       │           ├── Edit
│   │   │   │           │       │           │   └── Tab
│   │   │   │           │       │           └── IntegrationGrid
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       │   └── curl
│   │   │   │           │       ├── Fixture
│   │   │   │           │       ├── Handler
│   │   │   │           │       │   └── Integration
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Repository
│   │   │   │           │       └── TestCase
│   │   │   │           ├── LayeredNavigation
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Category
│   │   │   │           │       ├── Repository
│   │   │   │           │       └── TestCase
│   │   │   │           ├── Msrp
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Product
│   │   │   │           │       │       └── ProductList
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── Page
│   │   │   │           │       │   ├── Category
│   │   │   │           │       │   └── Product
│   │   │   │           │       ├── Repository
│   │   │   │           │       └── TestCase
│   │   │   │           ├── Multishipping
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Checkout
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       ├── Page
│   │   │   │           │       └── TestStep
│   │   │   │           ├── Newsletter
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       │       ├── Queue
│   │   │   │           │       │       │   └── Edit
│   │   │   │           │       │       ├── Subscriber
│   │   │   │           │       │       └── Template
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       │   └── curl
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   └── Queue
│   │   │   │           │       ├── Handler
│   │   │   │           │       │   └── Template
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Repository
│   │   │   │           │       └── TestCase
│   │   │   │           ├── OfflinePayments
│   │   │   │           │   └── Test
│   │   │   │           │       └── Repository
│   │   │   │           ├── OfflineShipping
│   │   │   │           │   └── Test
│   │   │   │           │       └── Repository
│   │   │   │           ├── PageCache
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Cache
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Repository
│   │   │   │           │       └── TestCase
│   │   │   │           ├── Payment
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Form
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       ├── Fixture
│   │   │   │           │       ├── Page
│   │   │   │           │       ├── Repository
│   │   │   │           │       └── TestCase
│   │   │   │           ├── Paypal
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   ├── Express
│   │   │   │           │       │   │   └── Review
│   │   │   │           │       │   ├── Form
│   │   │   │           │       │   │   ├── HostedPro
│   │   │   │           │       │   │   ├── PayflowLink
│   │   │   │           │       │   │   └── PaymentsAdvanced
│   │   │   │           │       │   ├── Onepage
│   │   │   │           │       │   │   └── Payment
│   │   │   │           │       │   ├── Sandbox
│   │   │   │           │       │   └── System
│   │   │   │           │       │       └── Config
│   │   │   │           │       ├── Constraint
│   │   │   │           │       │   └── Sandbox
│   │   │   │           │       ├── etc
│   │   │   │           │       ├── Fixture
│   │   │   │           │       ├── Page
│   │   │   │           │       │   ├── Adminhtml
│   │   │   │           │       │   └── Sandbox
│   │   │   │           │       ├── Repository
│   │   │   │           │       ├── TestCase
│   │   │   │           │       └── TestStep
│   │   │   │           ├── Persistent
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── Repository
│   │   │   │           │       └── TestCase
│   │   │   │           ├── ProductVideo
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       │       └── Product
│   │   │   │           │       │           └── Edit
│   │   │   │           │       │               └── Tab
│   │   │   │           │       │                   └── Images
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   └── Product
│   │   │   │           │       ├── Repository
│   │   │   │           │       └── TestCase
│   │   │   │           ├── ReleaseNotification
│   │   │   │           │   ├── Mtf
│   │   │   │           │   │   └── App
│   │   │   │           │   │       └── State
│   │   │   │           │   └── Test
│   │   │   │           │       └── etc
│   │   │   │           ├── Reports
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       │       ├── Customer
│   │   │   │           │       │       │   ├── Counts
│   │   │   │           │       │       │   └── Totals
│   │   │   │           │       │       ├── Product
│   │   │   │           │       │       │   ├── Downloads
│   │   │   │           │       │       │   ├── Lowstock
│   │   │   │           │       │       │   ├── Sold
│   │   │   │           │       │       │   └── Viewed
│   │   │   │           │       │       ├── Refresh
│   │   │   │           │       │       │   └── Statistics
│   │   │   │           │       │       ├── Review
│   │   │   │           │       │       │   ├── Customer
│   │   │   │           │       │       │   └── Products
│   │   │   │           │       │       │       └── Viewed
│   │   │   │           │       │       ├── Sales
│   │   │   │           │       │       │   ├── Coupons
│   │   │   │           │       │       │   ├── Invoiced
│   │   │   │           │       │       │   ├── Orders
│   │   │   │           │       │       │   │   └── Viewed
│   │   │   │           │       │       │   ├── Refunded
│   │   │   │           │       │       │   ├── Shipping
│   │   │   │           │       │       │   └── TaxRule
│   │   │   │           │       │       ├── Shopcart
│   │   │   │           │       │       │   ├── Abandoned
│   │   │   │           │       │       │   └── Product
│   │   │   │           │       │       └── Viewed
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Repository
│   │   │   │           │       └── TestCase
│   │   │   │           ├── Review
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   ├── Adminhtml
│   │   │   │           │       │   │   ├── Customer
│   │   │   │           │       │   │   │   └── Edit
│   │   │   │           │       │   │   │       └── Tab
│   │   │   │           │       │   │   ├── Edit
│   │   │   │           │       │   │   │   └── Product
│   │   │   │           │       │   │   ├── Product
│   │   │   │           │       │   │   │   └── Edit
│   │   │   │           │       │   │   │       └── Section
│   │   │   │           │       │   │   └── Rating
│   │   │   │           │       │   │       └── Edit
│   │   │   │           │       │   └── Product
│   │   │   │           │       │       └── View
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       │   └── curl
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   └── Review
│   │   │   │           │       ├── Handler
│   │   │   │           │       │   ├── Rating
│   │   │   │           │       │   └── Review
│   │   │   │           │       ├── Page
│   │   │   │           │       │   ├── Adminhtml
│   │   │   │           │       │   └── Product
│   │   │   │           │       ├── Repository
│   │   │   │           │       └── TestCase
│   │   │   │           ├── Sales
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   ├── Adminhtml
│   │   │   │           │       │   │   ├── CreditMemo
│   │   │   │           │       │   │   ├── Invoice
│   │   │   │           │       │   │   ├── Order
│   │   │   │           │       │   │   │   ├── AbstractForm
│   │   │   │           │       │   │   │   ├── Create
│   │   │   │           │       │   │   │   │   ├── Billing
│   │   │   │           │       │   │   │   │   ├── CustomerActivities
│   │   │   │           │       │   │   │   │   │   └── Sidebar
│   │   │   │           │       │   │   │   │   ├── Form
│   │   │   │           │       │   │   │   │   ├── Items
│   │   │   │           │       │   │   │   │   ├── Search
│   │   │   │           │       │   │   │   │   └── Shipping
│   │   │   │           │       │   │   │   ├── Creditmemo
│   │   │   │           │       │   │   │   │   ├── Form
│   │   │   │           │       │   │   │   │   │   └── Items
│   │   │   │           │       │   │   │   │   └── View
│   │   │   │           │       │   │   │   ├── Invoice
│   │   │   │           │       │   │   │   │   ├── Form
│   │   │   │           │       │   │   │   │   │   └── Items
│   │   │   │           │       │   │   │   │   └── View
│   │   │   │           │       │   │   │   ├── Shipment
│   │   │   │           │       │   │   │   │   └── View
│   │   │   │           │       │   │   │   ├── Status
│   │   │   │           │       │   │   │   │   └── Assign
│   │   │   │           │       │   │   │   ├── Transactions
│   │   │   │           │       │   │   │   └── View
│   │   │   │           │       │   │   │       └── Tab
│   │   │   │           │       │   │   │           ├── CreditMemos
│   │   │   │           │       │   │   │           ├── Info
│   │   │   │           │       │   │   │           ├── Invoices
│   │   │   │           │       │   │   │           ├── Shipments
│   │   │   │           │       │   │   │           └── Transactions
│   │   │   │           │       │   │   └── Report
│   │   │   │           │       │   │       └── Filter
│   │   │   │           │       │   ├── Order
│   │   │   │           │       │   │   └── View
│   │   │   │           │       │   └── Widget
│   │   │   │           │       │       └── Guest
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       │   ├── curl
│   │   │   │           │       │   └── webapi
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   └── OrderInjectable
│   │   │   │           │       ├── Handler
│   │   │   │           │       │   ├── OrderInjectable
│   │   │   │           │       │   └── OrderStatus
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Repository
│   │   │   │           │       │   └── OrderInjectable
│   │   │   │           │       ├── TestCase
│   │   │   │           │       └── TestStep
│   │   │   │           │           └── Utils
│   │   │   │           ├── SalesRule
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   ├── Adminhtml
│   │   │   │           │       │   │   └── Promo
│   │   │   │           │       │   │       └── Quote
│   │   │   │           │       │   │           └── Edit
│   │   │   │           │       │   │               └── Section
│   │   │   │           │       │   └── Order
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       │   ├── curl
│   │   │   │           │       │   └── webapi
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   └── SalesRule
│   │   │   │           │       ├── Handler
│   │   │   │           │       │   └── SalesRule
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Repository
│   │   │   │           │       ├── TestCase
│   │   │   │           │       └── TestStep
│   │   │   │           ├── Search
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       │       └── Block
│   │   │   │           │       │           └── Edit
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       │   └── curl
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   └── SynonymGroup
│   │   │   │           │       ├── Handler
│   │   │   │           │       │   └── SynonymGroup
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Repository
│   │   │   │           │       ├── TestCase
│   │   │   │           │       └── TestStep
│   │   │   │           ├── Security
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Form
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       ├── Page
│   │   │   │           │       ├── Repository
│   │   │   │           │       └── TestCase
│   │   │   │           ├── Setup
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   ├── Extension
│   │   │   │           │       │   ├── Module
│   │   │   │           │       │   └── SelectVersion
│   │   │   │           │       │       └── OtherComponentsGrid
│   │   │   │           │       ├── Constraint
│   │   │   │           │       │   ├── Extension
│   │   │   │           │       │   └── Module
│   │   │   │           │       ├── Fixture
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Repository
│   │   │   │           │       └── TestCase
│   │   │   │           ├── Shipping
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   ├── Adminhtml
│   │   │   │           │       │   │   ├── Form
│   │   │   │           │       │   │   │   └── Items
│   │   │   │           │       │   │   ├── Order
│   │   │   │           │       │   │   │   └── Tracking
│   │   │   │           │       │   │   ├── Shipment
│   │   │   │           │       │   │   └── View
│   │   │   │           │       │   └── Order
│   │   │   │           │       │       └── Shipment
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       ├── Fixture
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Repository
│   │   │   │           │       ├── TestCase
│   │   │   │           │       └── TestStep
│   │   │   │           ├── Signifyd
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   ├── Adminhtml
│   │   │   │           │       │   │   └── Order
│   │   │   │           │       │   │       └── View
│   │   │   │           │       │   └── SignifydConsole
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   └── SignifydAddress
│   │   │   │           │       ├── Page
│   │   │   │           │       │   ├── Adminhtml
│   │   │   │           │       │   └── SignifydConsole
│   │   │   │           │       ├── Repository
│   │   │   │           │       ├── TestCase
│   │   │   │           │       └── TestStep
│   │   │   │           ├── Sitemap
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       │   └── curl
│   │   │   │           │       ├── Fixture
│   │   │   │           │       ├── Handler
│   │   │   │           │       │   └── Sitemap
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Repository
│   │   │   │           │       └── TestCase
│   │   │   │           ├── Store
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       │   └── curl
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   ├── Store
│   │   │   │           │       │   └── StoreGroup
│   │   │   │           │       ├── Handler
│   │   │   │           │       │   ├── Store
│   │   │   │           │       │   ├── StoreGroup
│   │   │   │           │       │   └── Website
│   │   │   │           │       ├── Repository
│   │   │   │           │       ├── TestCase
│   │   │   │           │       └── TestStep
│   │   │   │           ├── Swagger
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── Page
│   │   │   │           │       └── TestCase
│   │   │   │           ├── Swatches
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Product
│   │   │   │           │       │       └── ProductList
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       │   └── curl
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   └── Cart
│   │   │   │           │       ├── Handler
│   │   │   │           │       │   └── SwatchProductAttribute
│   │   │   │           │       ├── Page
│   │   │   │           │       │   ├── Category
│   │   │   │           │       │   └── Product
│   │   │   │           │       ├── Repository
│   │   │   │           │       │   └── ConfigurableProduct
│   │   │   │           │       ├── TestCase
│   │   │   │           │       └── TestStep
│   │   │   │           ├── Tax
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       │       ├── Rate
│   │   │   │           │       │       │   └── Edit
│   │   │   │           │       │       └── Rule
│   │   │   │           │       │           └── Edit
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       │   ├── curl
│   │   │   │           │       │   └── webapi
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   └── TaxRule
│   │   │   │           │       ├── Handler
│   │   │   │           │       │   ├── Curl
│   │   │   │           │       │   ├── TaxClass
│   │   │   │           │       │   ├── TaxRate
│   │   │   │           │       │   └── TaxRule
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Repository
│   │   │   │           │       ├── TestCase
│   │   │   │           │       └── TestStep
│   │   │   │           ├── Theme
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Html
│   │   │   │           │       ├── Page
│   │   │   │           │       └── TestCase
│   │   │   │           ├── Ui
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       └── TestCase
│   │   │   │           ├── Ups
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Repository
│   │   │   │           │       └── TestCase
│   │   │   │           ├── UrlRewrite
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       │       ├── Catalog
│   │   │   │           │       │       │   ├── Category
│   │   │   │           │       │       │   ├── Edit
│   │   │   │           │       │       │   └── Product
│   │   │   │           │       │       └── Cms
│   │   │   │           │       │           └── Page
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       │   └── curl
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   └── UrlRewrite
│   │   │   │           │       ├── Handler
│   │   │   │           │       │   └── UrlRewrite
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Repository
│   │   │   │           │       └── TestCase
│   │   │   │           ├── User
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       │       ├── Role
│   │   │   │           │       │       │   └── Tab
│   │   │   │           │       │       │       └── User
│   │   │   │           │       │       └── User
│   │   │   │           │       │           ├── Edit
│   │   │   │           │       │           │   └── Tab
│   │   │   │           │       │           └── Tab
│   │   │   │           │       │               └── Role
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       │   └── curl
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   ├── Role
│   │   │   │           │       │   └── User
│   │   │   │           │       ├── Handler
│   │   │   │           │       │   ├── Role
│   │   │   │           │       │   └── User
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Repository
│   │   │   │           │       ├── TestCase
│   │   │   │           │       └── TestStep
│   │   │   │           ├── Usps
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Repository
│   │   │   │           │       └── TestCase
│   │   │   │           ├── Variable
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       │       └── System
│   │   │   │           │       │           └── Variable
│   │   │   │           │       │               └── Edit
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       │   └── curl
│   │   │   │           │       ├── Fixture
│   │   │   │           │       ├── Handler
│   │   │   │           │       │   └── SystemVariable
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Repository
│   │   │   │           │       └── TestCase
│   │   │   │           ├── Vault
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Onepage
│   │   │   │           │       │       └── Payment
│   │   │   │           │       │           └── Method
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       ├── Page
│   │   │   │           │       ├── TestCase
│   │   │   │           │       └── TestStep
│   │   │   │           ├── Weee
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   ├── Adminhtml
│   │   │   │           │       │   │   └── Product
│   │   │   │           │       │   │       └── Edit
│   │   │   │           │       │   │           └── Section
│   │   │   │           │       │   │               └── ProductDetails
│   │   │   │           │       │   ├── Cart
│   │   │   │           │       │   │   ├── CartItem
│   │   │   │           │       │   │   └── Totals
│   │   │   │           │       │   └── Product
│   │   │   │           │       │       └── ProductList
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       ├── Page
│   │   │   │           │       │   ├── Category
│   │   │   │           │       │   └── Product
│   │   │   │           │       ├── Repository
│   │   │   │           │       └── TestCase
│   │   │   │           ├── Widget
│   │   │   │           │   └── Test
│   │   │   │           │       ├── Block
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       │       └── Widget
│   │   │   │           │       │           └── Instance
│   │   │   │           │       │               └── Edit
│   │   │   │           │       │                   └── Tab
│   │   │   │           │       │                       ├── ParametersType
│   │   │   │           │       │                       │   ├── CatalogCategoryLink
│   │   │   │           │       │                       │   ├── CatalogProductLink
│   │   │   │           │       │                       │   ├── CmsPageLink
│   │   │   │           │       │                       │   └── CmsStaticBlock
│   │   │   │           │       │                       └── WidgetInstanceType
│   │   │   │           │       │                           └── Product
│   │   │   │           │       ├── Constraint
│   │   │   │           │       ├── etc
│   │   │   │           │       │   └── curl
│   │   │   │           │       ├── Fixture
│   │   │   │           │       │   └── Widget
│   │   │   │           │       ├── Handler
│   │   │   │           │       │   └── Widget
│   │   │   │           │       ├── Page
│   │   │   │           │       │   └── Adminhtml
│   │   │   │           │       ├── Repository
│   │   │   │           │       │   └── Widget
│   │   │   │           │       ├── TestCase
│   │   │   │           │       └── TestStep
│   │   │   │           └── Wishlist
│   │   │   │               └── Test
│   │   │   │                   ├── Block
│   │   │   │                   │   ├── Adminhtml
│   │   │   │                   │   │   ├── Customer
│   │   │   │                   │   │   │   └── Edit
│   │   │   │                   │   │   │       └── Tab
│   │   │   │                   │   │   │           └── Wishlist
│   │   │   │                   │   │   └── Edit
│   │   │   │                   │   └── Customer
│   │   │   │                   │       └── Wishlist
│   │   │   │                   │           └── Items
│   │   │   │                   ├── Constraint
│   │   │   │                   ├── Page
│   │   │   │                   ├── TestCase
│   │   │   │                   └── TestStep
│   │   │   ├── testsuites
│   │   │   │   └── Magento
│   │   │   │       └── Mtf
│   │   │   │           └── TestSuite
│   │   │   │               └── InjectableTests
│   │   │   └── utils
│   │   │       └── generate
│   │   ├── integration
│   │   │   ├── bin
│   │   │   ├── etc
│   │   │   │   └── di
│   │   │   │       └── preferences
│   │   │   ├── _files
│   │   │   │   └── Magento
│   │   │   │       ├── TestModuleAsyncAmqp
│   │   │   │       │   ├── etc
│   │   │   │       │   └── Model
│   │   │   │       ├── TestModuleDirectoryZipCodes
│   │   │   │       │   └── etc
│   │   │   │       ├── TestModuleExtensionAttributes
│   │   │   │       │   ├── Api
│   │   │   │       │   │   └── Data
│   │   │   │       │   ├── etc
│   │   │   │       │   └── Model
│   │   │   │       │       └── Data
│   │   │   │       ├── TestModuleFakePaymentMethod
│   │   │   │       │   ├── etc
│   │   │   │       │   └── Gateway
│   │   │   │       │       └── Command
│   │   │   │       ├── TestModuleMessageQueueConfigOverride
│   │   │   │       │   └── etc
│   │   │   │       ├── TestModuleMessageQueueConfiguration
│   │   │   │       │   └── etc
│   │   │   │       ├── TestModuleMysqlMq
│   │   │   │       │   ├── etc
│   │   │   │       │   └── Model
│   │   │   │       ├── TestModuleSample
│   │   │   │       │   └── etc
│   │   │   │       ├── TestModuleSynchronousAmqp
│   │   │   │       │   ├── Api
│   │   │   │       │   ├── etc
│   │   │   │       │   └── Model
│   │   │   │       └── TestModuleWysiwygConfig
│   │   │   │           ├── etc
│   │   │   │           │   └── adminhtml
│   │   │   │           ├── Model
│   │   │   │           └── view
│   │   │   │               └── adminhtml
│   │   │   │                   └── web
│   │   │   │                       └── wysiwyg
│   │   │   ├── framework
│   │   │   │   ├── Magento
│   │   │   │   │   └── TestFramework
│   │   │   │   │       ├── Annotation
│   │   │   │   │       ├── Api
│   │   │   │   │       │   └── Config
│   │   │   │   │       │       └── Reader
│   │   │   │   │       ├── App
│   │   │   │   │       │   └── ObjectManager
│   │   │   │   │       │       └── Environment
│   │   │   │   │       ├── Backend
│   │   │   │   │       │   └── App
│   │   │   │   │       ├── Bootstrap
│   │   │   │   │       ├── Db
│   │   │   │   │       │   ├── Adapter
│   │   │   │   │       │   └── Sequence
│   │   │   │   │       ├── ErrorLog
│   │   │   │   │       ├── Event
│   │   │   │   │       │   └── Param
│   │   │   │   │       ├── Helper
│   │   │   │   │       ├── Indexer
│   │   │   │   │       ├── Interception
│   │   │   │   │       ├── Isolation
│   │   │   │   │       ├── Listener
│   │   │   │   │       ├── Lock
│   │   │   │   │       │   └── Backend
│   │   │   │   │       ├── Mail
│   │   │   │   │       │   └── Template
│   │   │   │   │       ├── MessageQueue
│   │   │   │   │       ├── ObjectManager
│   │   │   │   │       ├── Profiler
│   │   │   │   │       ├── Session
│   │   │   │   │       ├── Store
│   │   │   │   │       ├── TestCase
│   │   │   │   │       ├── View
│   │   │   │   │       └── Workaround
│   │   │   │   │           └── Cleanup
│   │   │   │   └── tests
│   │   │   │       └── unit
│   │   │   │           ├── framework
│   │   │   │           └── testsuite
│   │   │   │               └── Magento
│   │   │   │                   └── Test
│   │   │   │                       ├── Annotation
│   │   │   │                       │   └── _files
│   │   │   │                       │       └── components
│   │   │   │                       │           ├── a
│   │   │   │                       │           │   └── aa
│   │   │   │                       │           │       └── aaa
│   │   │   │                       │           └── b
│   │   │   │                       ├── App
│   │   │   │                       ├── Bootstrap
│   │   │   │                       │   └── _files
│   │   │   │                       ├── Db
│   │   │   │                       │   └── Adapter
│   │   │   │                       ├── Event
│   │   │   │                       │   └── Param
│   │   │   │                       ├── Helper
│   │   │   │                       ├── Isolation
│   │   │   │                       ├── Profiler
│   │   │   │                       ├── TestCase
│   │   │   │                       └── Workaround
│   │   │   │                           └── Cleanup
│   │   │   │                               └── TestCasePropertiesTest
│   │   │   ├── testsuite
│   │   │   │   └── Magento
│   │   │   │       ├── AdminNotification
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       └── Notification
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Model
│   │   │   │       │       └── ResourceModel
│   │   │   │       │           └── Inbox
│   │   │   │       │               └── Collection
│   │   │   │       ├── AdvancedPricingImportExport
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Model
│   │   │   │       │       ├── Export
│   │   │   │       │       └── Import
│   │   │   │       │           └── _files
│   │   │   │       ├── AdvancedSearch
│   │   │   │       │   └── Block
│   │   │   │       ├── Analytics
│   │   │   │       │   ├── Block
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       └── System
│   │   │   │       │   │           └── Config
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Model
│   │   │   │       │       ├── Connector
│   │   │   │       │       │   └── Http
│   │   │   │       │       └── Plugin
│   │   │   │       ├── AsynchronousOperations
│   │   │   │       │   ├── _files
│   │   │   │       │   ├── Model
│   │   │   │       │   └── Ui
│   │   │   │       │       └── Component
│   │   │   │       │           └── DataProvider
│   │   │   │       │               └── Operation
│   │   │   │       │                   ├── Failed
│   │   │   │       │                   └── Retriable
│   │   │   │       ├── Authorization
│   │   │   │       │   └── Model
│   │   │   │       │       └── ResourceModel
│   │   │   │       │           ├── Role
│   │   │   │       │           │   └── Grid
│   │   │   │       │           └── Rules
│   │   │   │       ├── Authorizenet
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   ├── Adminhtml
│   │   │   │       │   │   │   └── Authorizenet
│   │   │   │       │   │   │       └── Directpost
│   │   │   │       │   │   │           └── Payment
│   │   │   │       │   │   └── Directpost
│   │   │   │       │   │       └── Payment
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Model
│   │   │   │       │       └── Directpost
│   │   │   │       ├── AuthorizenetAcceptjs
│   │   │   │       │   ├── _files
│   │   │   │       │   │   ├── expected_request
│   │   │   │       │   │   └── response
│   │   │   │       │   ├── Fixture
│   │   │   │       │   └── Gateway
│   │   │   │       │       └── Command
│   │   │   │       ├── Backend
│   │   │   │       │   ├── App
│   │   │   │       │   │   └── Request
│   │   │   │       │   ├── Block
│   │   │   │       │   │   ├── Dashboard
│   │   │   │       │   │   │   ├── Orders
│   │   │   │       │   │   │   └── Tab
│   │   │   │       │   │   │       └── Products
│   │   │   │       │   │   ├── _files
│   │   │   │       │   │   │   ├── design
│   │   │   │       │   │   │   │   └── adminhtml
│   │   │   │       │   │   │   │       └── Magento
│   │   │   │       │   │   │   │           └── test_default
│   │   │   │       │   │   │   │               ├── Magento_Backend
│   │   │   │       │   │   │   │               │   └── layout
│   │   │   │       │   │   │   │               └── web
│   │   │   │       │   │   │   │                   └── images
│   │   │   │       │   │   │   └── menu
│   │   │   │       │   │   │       └── Magento
│   │   │   │       │   │   │           └── Backend
│   │   │   │       │   │   │               └── etc
│   │   │   │       │   │   │                   └── adminhtml
│   │   │   │       │   │   ├── Page
│   │   │   │       │   │   ├── System
│   │   │   │       │   │   │   ├── Account
│   │   │   │       │   │   │   │   └── Edit
│   │   │   │       │   │   │   ├── Design
│   │   │   │       │   │   │   │   └── Edit
│   │   │   │       │   │   │   │       └── Tab
│   │   │   │       │   │   │   └── Store
│   │   │   │       │   │   │       └── Edit
│   │   │   │       │   │   │           └── Form
│   │   │   │       │   │   └── Widget
│   │   │   │       │   │       ├── Form
│   │   │   │       │   │       └── Grid
│   │   │   │       │   │           ├── Column
│   │   │   │       │   │           │   └── Renderer
│   │   │   │       │   │           └── Massaction
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       ├── Cache
│   │   │   │       │   │       ├── Dashboard
│   │   │   │       │   │       └── System
│   │   │   │       │   ├── controllers
│   │   │   │       │   │   └── _files
│   │   │   │       │   │       └── cache
│   │   │   │       │   ├── _files
│   │   │   │       │   ├── Helper
│   │   │   │       │   └── Model
│   │   │   │       │       ├── Auth
│   │   │   │       │       ├── Locale
│   │   │   │       │       ├── Search
│   │   │   │       │       │   └── _files
│   │   │   │       │       ├── Session
│   │   │   │       │       └── Translate
│   │   │   │       ├── Braintree
│   │   │   │       │   ├── Block
│   │   │   │       │   │   └── Form
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   ├── Adminhtml
│   │   │   │       │   │   │   ├── Invoice
│   │   │   │       │   │   │   ├── Order
│   │   │   │       │   │   │   └── Payment
│   │   │   │       │   │   ├── Cards
│   │   │   │       │   │   └── Paypal
│   │   │   │       │   ├── _files
│   │   │   │       │   ├── Fixtures
│   │   │   │       │   ├── Gateway
│   │   │   │       │   │   └── Config
│   │   │   │       │   └── Model
│   │   │   │       │       ├── Adminhtml
│   │   │   │       │       │   └── System
│   │   │   │       │       │       └── Config
│   │   │   │       │       └── Ui
│   │   │   │       │           └── Adminhtml
│   │   │   │       │               └── PayPal
│   │   │   │       ├── Bundle
│   │   │   │       │   ├── Block
│   │   │   │       │   │   ├── Adminhtml
│   │   │   │       │   │   │   └── Catalog
│   │   │   │       │   │   │       └── Product
│   │   │   │       │   │   │           └── Edit
│   │   │   │       │   │   │               └── Tab
│   │   │   │       │   │   │                   └── Bundle
│   │   │   │       │   │   │                       └── Option
│   │   │   │       │   │   │                           └── Search
│   │   │   │       │   │   └── Catalog
│   │   │   │       │   │       └── Product
│   │   │   │       │   │           └── View
│   │   │   │       │   │               └── Type
│   │   │   │       │   ├── Controller
│   │   │   │       │   ├── _files
│   │   │   │       │   │   └── PriceCalculator
│   │   │   │       │   └── Model
│   │   │   │       │       ├── Category
│   │   │   │       │       ├── Plugin
│   │   │   │       │       │   └── Frontend
│   │   │   │       │       ├── Product
│   │   │   │       │       └── ResourceModel
│   │   │   │       │           └── Indexer
│   │   │   │       ├── BundleImportExport
│   │   │   │       │   └── Model
│   │   │   │       │       ├── Export
│   │   │   │       │       └── Import
│   │   │   │       │           ├── _files
│   │   │   │       │           └── Product
│   │   │   │       │               └── Type
│   │   │   │       ├── Captcha
│   │   │   │       │   ├── Block
│   │   │   │       │   │   ├── Adminhtml
│   │   │   │       │   │   │   └── Captcha
│   │   │   │       │   │   └── Captcha
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Observer
│   │   │   │       ├── Catalog
│   │   │   │       │   ├── Block
│   │   │   │       │   │   ├── Adminhtml
│   │   │   │       │   │   │   ├── Category
│   │   │   │       │   │   │   │   └── Checkboxes
│   │   │   │       │   │   │   └── Product
│   │   │   │       │   │   │       ├── Attribute
│   │   │   │       │   │   │       │   ├── Edit
│   │   │   │       │   │   │       │   │   └── Tab
│   │   │   │       │   │   │       │   └── Set
│   │   │   │       │   │   │       │       └── Toolbar
│   │   │   │       │   │   │       ├── Edit
│   │   │   │       │   │   │       │   └── Tab
│   │   │   │       │   │   │       │       └── Options
│   │   │   │       │   │   │       │           └── Type
│   │   │   │       │   │   │       ├── Helper
│   │   │   │       │   │   │       │   └── Form
│   │   │   │       │   │   │       │       └── Gallery
│   │   │   │       │   │   │       └── Options
│   │   │   │       │   │   └── Product
│   │   │   │       │   │       ├── ProductList
│   │   │   │       │   │       └── View
│   │   │   │       │   ├── Console
│   │   │   │       │   │   └── Command
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   ├── Adminhtml
│   │   │   │       │   │   │   └── Product
│   │   │   │       │   │   │       ├── Action
│   │   │   │       │   │   │       └── Set
│   │   │   │       │   │   └── Product
│   │   │   │       │   ├── controllers
│   │   │   │       │   │   └── _files
│   │   │   │       │   ├── Cron
│   │   │   │       │   ├── _files
│   │   │   │       │   │   └── etc
│   │   │   │       │   ├── Helper
│   │   │   │       │   │   └── Product
│   │   │   │       │   │       └── Stub
│   │   │   │       │   ├── Model
│   │   │   │       │   │   ├── AbstractModel
│   │   │   │       │   │   ├── Category
│   │   │   │       │   │   │   ├── _files
│   │   │   │       │   │   │   └── Link
│   │   │   │       │   │   ├── Indexer
│   │   │   │       │   │   │   ├── Category
│   │   │   │       │   │   │   └── Product
│   │   │   │       │   │   │       ├── Eav
│   │   │   │       │   │   │       │   └── Action
│   │   │   │       │   │   │       ├── Flat
│   │   │   │       │   │   │       │   └── Action
│   │   │   │       │   │   │       └── Price
│   │   │   │       │   │   │           └── Action
│   │   │   │       │   │   ├── Layer
│   │   │   │       │   │   │   └── Filter
│   │   │   │       │   │   │       ├── DataProvider
│   │   │   │       │   │   │       ├── _files
│   │   │   │       │   │   │       └── Price
│   │   │   │       │   │   │           └── _files
│   │   │   │       │   │   ├── Product
│   │   │   │       │   │   │   ├── Attribute
│   │   │   │       │   │   │   │   ├── Backend
│   │   │   │       │   │   │   │   ├── _files
│   │   │   │       │   │   │   │   └── Source
│   │   │   │       │   │   │   ├── Compare
│   │   │   │       │   │   │   ├── _files
│   │   │   │       │   │   │   ├── Gallery
│   │   │   │       │   │   │   ├── Option
│   │   │   │       │   │   │   │   └── Type
│   │   │   │       │   │   │   │       └── File
│   │   │   │       │   │   │   └── Type
│   │   │   │       │   │   ├── ResourceModel
│   │   │   │       │   │   │   ├── Attribute
│   │   │   │       │   │   │   ├── Category
│   │   │   │       │   │   │   ├── Eav
│   │   │   │       │   │   │   ├── _files
│   │   │   │       │   │   │   └── Product
│   │   │   │       │   │   │       ├── Indexer
│   │   │   │       │   │   │       │   └── Eav
│   │   │   │       │   │   │       └── Link
│   │   │   │       │   │   │           └── Product
│   │   │   │       │   │   └── Webapi
│   │   │   │       │   │       └── Product
│   │   │   │       │   │           └── Option
│   │   │   │       │   │               └── Type
│   │   │   │       │   │                   └── File
│   │   │   │       │   ├── Observer
│   │   │   │       │   ├── Plugin
│   │   │   │       │   │   └── Model
│   │   │   │       │   │       └── AttributeSetRepository
│   │   │   │       │   ├── Pricing
│   │   │   │       │   │   └── Render
│   │   │   │       │   │       └── FinalPriceBox
│   │   │   │       │   └── Ui
│   │   │   │       │       └── DataProvider
│   │   │   │       │           └── Product
│   │   │   │       │               ├── Attributes
│   │   │   │       │               └── Form
│   │   │   │       │                   └── Modifier
│   │   │   │       │                       └── _files
│   │   │   │       ├── CatalogImportExport
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Model
│   │   │   │       │       ├── Export
│   │   │   │       │       └── Import
│   │   │   │       │           ├── _files
│   │   │   │       │           └── Product
│   │   │   │       │               └── Type
│   │   │   │       ├── CatalogInventory
│   │   │   │       │   ├── Api
│   │   │   │       │   ├── Block
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       └── Form
│   │   │   │       │   │           └── Field
│   │   │   │       │   ├── _files
│   │   │   │       │   ├── Model
│   │   │   │       │   │   ├── Indexer
│   │   │   │       │   │   │   └── Stock
│   │   │   │       │   │   │       └── Action
│   │   │   │       │   │   ├── Plugin
│   │   │   │       │   │   ├── Quote
│   │   │   │       │   │   │   └── Item
│   │   │   │       │   │   ├── ResourceModel
│   │   │   │       │   │   │   └── Indexer
│   │   │   │       │   │   │       └── Stock
│   │   │   │       │   │   ├── Stock
│   │   │   │       │   │   ├── StockItemSave
│   │   │   │       │   │   │   ├── OnProductCreate
│   │   │   │       │   │   │   │   ├── ByProductModel
│   │   │   │       │   │   │   │   └── ByProductRepository
│   │   │   │       │   │   │   └── OnProductUpdate
│   │   │   │       │   │   │       ├── ByProductModel
│   │   │   │       │   │   │       └── ByProductRepository
│   │   │   │       │   │   └── System
│   │   │   │       │   │       └── Config
│   │   │   │       │   │           └── Backend
│   │   │   │       │   └── Observer
│   │   │   │       ├── CatalogRule
│   │   │   │       │   ├── _files
│   │   │   │       │   │   └── conditions_to_collection
│   │   │   │       │   └── Model
│   │   │   │       │       ├── Indexer
│   │   │   │       │       │   └── Product
│   │   │   │       │       └── ResourceModel
│   │   │   │       │           ├── Product
│   │   │   │       │           └── Rule
│   │   │   │       ├── CatalogSearch
│   │   │   │       │   ├── Block
│   │   │   │       │   │   └── Advanced
│   │   │   │       │   ├── Controller
│   │   │   │       │   ├── _files
│   │   │   │       │   ├── Helper
│   │   │   │       │   └── Model
│   │   │   │       │       ├── Adapter
│   │   │   │       │       │   └── Mysql
│   │   │   │       │       │       └── BaseSelectStrategy
│   │   │   │       │       ├── Indexer
│   │   │   │       │       │   └── Fulltext
│   │   │   │       │       │       ├── Action
│   │   │   │       │       │       └── Model
│   │   │   │       │       │           └── Plugin
│   │   │   │       │       ├── Layer
│   │   │   │       │       │   └── Filter
│   │   │   │       │       ├── ResourceModel
│   │   │   │       │       │   ├── Advanced
│   │   │   │       │       │   └── Fulltext
│   │   │   │       │       └── Search
│   │   │   │       │           └── FilterMapper
│   │   │   │       ├── CatalogUrlRewrite
│   │   │   │       │   ├── _files
│   │   │   │       │   ├── Fixtures
│   │   │   │       │   ├── Model
│   │   │   │       │   ├── Observer
│   │   │   │       │   └── Plugin
│   │   │   │       │       └── Catalog
│   │   │   │       │           └── Block
│   │   │   │       │               └── Adminhtml
│   │   │   │       │                   └── Category
│   │   │   │       │                       └── Tab
│   │   │   │       ├── CatalogWidget
│   │   │   │       │   ├── Block
│   │   │   │       │   │   └── Product
│   │   │   │       │   │       └── Widget
│   │   │   │       │   └── Model
│   │   │   │       │       └── Rule
│   │   │   │       │           └── Condition
│   │   │   │       ├── Checkout
│   │   │   │       │   ├── Api
│   │   │   │       │   ├── Block
│   │   │   │       │   │   └── Cart
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Cart
│   │   │   │       │   │       └── Index
│   │   │   │       │   ├── _files
│   │   │   │       │   ├── Model
│   │   │   │       │   └── Plugin
│   │   │   │       │       └── Model
│   │   │   │       │           └── Quote
│   │   │   │       ├── CheckoutAgreements
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Model
│   │   │   │       │       ├── Api
│   │   │   │       │       │   └── SearchCriteria
│   │   │   │       │       ├── Checkout
│   │   │   │       │       │   └── Plugin
│   │   │   │       │       └── ResourceModel
│   │   │   │       │           └── Grid
│   │   │   │       ├── Cms
│   │   │   │       │   ├── Block
│   │   │   │       │   │   └── Widget
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   ├── Adminhtml
│   │   │   │       │   │   │   └── Wysiwyg
│   │   │   │       │   │   │       └── Images
│   │   │   │       │   │   └── Noroute
│   │   │   │       │   ├── _files
│   │   │   │       │   ├── Fixtures
│   │   │   │       │   ├── Helper
│   │   │   │       │   │   └── Wysiwyg
│   │   │   │       │   ├── Model
│   │   │   │       │   │   └── Wysiwyg
│   │   │   │       │   │       └── Images
│   │   │   │       │   └── Setup
│   │   │   │       ├── Config
│   │   │   │       │   ├── App
│   │   │   │       │   │   └── Config
│   │   │   │       │   │       └── Type
│   │   │   │       │   ├── Block
│   │   │   │       │   │   └── System
│   │   │   │       │   │       └── Config
│   │   │   │       │   │           └── _files
│   │   │   │       │   ├── Console
│   │   │   │       │   │   └── Command
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       └── System
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Model
│   │   │   │       │       ├── Config
│   │   │   │       │       │   ├── Backend
│   │   │   │       │       │   │   ├── Admin
│   │   │   │       │       │   │   └── Image
│   │   │   │       │       │   ├── Processor
│   │   │   │       │       │   └── Structure
│   │   │   │       │       │       └── Reader
│   │   │   │       │       │           └── _files
│   │   │   │       │       ├── _files
│   │   │   │       │       └── ResourceModel
│   │   │   │       ├── ConfigurableImportExport
│   │   │   │       │   └── Model
│   │   │   │       │       ├── Export
│   │   │   │       │       └── Import
│   │   │   │       │           ├── _files
│   │   │   │       │           └── Product
│   │   │   │       │               └── Type
│   │   │   │       ├── ConfigurableProduct
│   │   │   │       │   ├── Block
│   │   │   │       │   │   ├── Adminhtml
│   │   │   │       │   │   │   └── Product
│   │   │   │       │   │   │       └── Edit
│   │   │   │       │   │   │           └── Tab
│   │   │   │       │   │   │               └── Variations
│   │   │   │       │   │   │                   └── Config
│   │   │   │       │   │   └── Product
│   │   │   │       │   │       └── View
│   │   │   │       │   │           └── Type
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   ├── etc
│   │   │   │       │   ├── _files
│   │   │   │       │   ├── Model
│   │   │   │       │   │   ├── Category
│   │   │   │       │   │   ├── Plugin
│   │   │   │       │   │   │   └── Frontend
│   │   │   │       │   │   ├── Product
│   │   │   │       │   │   │   └── Type
│   │   │   │       │   │   │       └── Configurable
│   │   │   │       │   │   └── ResourceModel
│   │   │   │       │   │       └── Product
│   │   │   │       │   │           └── Indexer
│   │   │   │       │   │               ├── Price
│   │   │   │       │   │               └── Stock
│   │   │   │       │   ├── Pricing
│   │   │   │       │   │   ├── Price
│   │   │   │       │   │   └── Render
│   │   │   │       │   │       └── FinalPriceBox
│   │   │   │       │   └── Ui
│   │   │   │       │       └── DataProvider
│   │   │   │       │           └── Product
│   │   │   │       │               └── Form
│   │   │   │       │                   └── Modifier
│   │   │   │       │                       └── Data
│   │   │   │       ├── Contact
│   │   │   │       │   ├── Controller
│   │   │   │       │   ├── Helper
│   │   │   │       │   └── Model
│   │   │   │       ├── Cookie
│   │   │   │       │   └── Model
│   │   │   │       │       └── Config
│   │   │   │       │           └── Backend
│   │   │   │       ├── Cron
│   │   │   │       │   ├── Model
│   │   │   │       │   └── Observer
│   │   │   │       ├── CurrencySymbol
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       └── System
│   │   │   │       │   │           ├── Currency
│   │   │   │       │   │           └── Currencysymbol
│   │   │   │       │   └── Model
│   │   │   │       │       └── System
│   │   │   │       ├── Customer
│   │   │   │       │   ├── Api
│   │   │   │       │   ├── Block
│   │   │   │       │   │   ├── Account
│   │   │   │       │   │   │   └── Dashboard
│   │   │   │       │   │   ├── Address
│   │   │   │       │   │   │   └── Renderer
│   │   │   │       │   │   ├── Adminhtml
│   │   │   │       │   │   │   ├── Edit
│   │   │   │       │   │   │   │   └── Tab
│   │   │   │       │   │   │   │       └── View
│   │   │   │       │   │   │   └── Group
│   │   │   │       │   │   │       └── Edit
│   │   │   │       │   │   ├── Form
│   │   │   │       │   │   └── Widget
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   ├── Adminhtml
│   │   │   │       │   │   │   ├── Address
│   │   │   │       │   │   │   ├── Cart
│   │   │   │       │   │   │   │   └── Product
│   │   │   │       │   │   │   │       └── Composite
│   │   │   │       │   │   │   └── Index
│   │   │   │       │   │   └── Section
│   │   │   │       │   ├── etc
│   │   │   │       │   ├── _files
│   │   │   │       │   │   ├── etc
│   │   │   │       │   │   └── import_export
│   │   │   │       │   ├── Fixtures
│   │   │   │       │   ├── Helper
│   │   │   │       │   └── Model
│   │   │   │       │       ├── Config
│   │   │   │       │       │   └── Source
│   │   │   │       │       │       └── Group
│   │   │   │       │       ├── Metadata
│   │   │   │       │       └── ResourceModel
│   │   │   │       │           ├── Address
│   │   │   │       │           ├── Customer
│   │   │   │       │           ├── Grid
│   │   │   │       │           └── Group
│   │   │   │       │               └── Grid
│   │   │   │       ├── CustomerImportExport
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Model
│   │   │   │       │       ├── Export
│   │   │   │       │       └── Import
│   │   │   │       │           └── _files
│   │   │   │       ├── Deploy
│   │   │   │       │   ├── Console
│   │   │   │       │   │   └── Command
│   │   │   │       │   │       └── App
│   │   │   │       │   │           └── ConfigImportCommand
│   │   │   │       │   └── _files
│   │   │   │       │       ├── lib
│   │   │   │       │       │   └── web
│   │   │   │       │       ├── scopes
│   │   │   │       │       ├── zoom1
│   │   │   │       │       │   ├── etc
│   │   │   │       │       │   └── web
│   │   │   │       │       │       ├── css
│   │   │   │       │       │       ├── images
│   │   │   │       │       │       └── js
│   │   │   │       │       ├── zoom2
│   │   │   │       │       │   ├── etc
│   │   │   │       │       │   └── web
│   │   │   │       │       │       ├── css
│   │   │   │       │       │       ├── images
│   │   │   │       │       │       └── js
│   │   │   │       │       └── zoom3
│   │   │   │       │           ├── etc
│   │   │   │       │           └── web
│   │   │   │       │               ├── css
│   │   │   │       │               ├── images
│   │   │   │       │               └── js
│   │   │   │       ├── Developer
│   │   │   │       │   ├── Console
│   │   │   │       │   │   └── Command
│   │   │   │       │   ├── Helper
│   │   │   │       │   └── Model
│   │   │   │       │       ├── Config
│   │   │   │       │       │   └── Backend
│   │   │   │       │       └── Logger
│   │   │   │       │           └── Handler
│   │   │   │       ├── Dhl
│   │   │   │       │   ├── Block
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Model
│   │   │   │       ├── Directory
│   │   │   │       │   ├── Block
│   │   │   │       │   ├── Helper
│   │   │   │       │   └── Model
│   │   │   │       │       └── Country
│   │   │   │       │           └── Postcode
│   │   │   │       │               └── Config
│   │   │   │       ├── Downloadable
│   │   │   │       │   ├── Block
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       └── Catalog
│   │   │   │       │   │           └── Product
│   │   │   │       │   │               └── Edit
│   │   │   │       │   │                   └── Tab
│   │   │   │       │   │                       └── Downloadable
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       ├── Downloadable
│   │   │   │       │   │       └── _files
│   │   │   │       │   ├── etc
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Model
│   │   │   │       │       ├── Observer
│   │   │   │       │       ├── Product
│   │   │   │       │       └── ResourceModel
│   │   │   │       │           └── Indexer
│   │   │   │       ├── DownloadableImportExport
│   │   │   │       │   └── Model
│   │   │   │       │       └── Import
│   │   │   │       │           ├── _files
│   │   │   │       │           └── Product
│   │   │   │       │               └── Type
│   │   │   │       ├── Eav
│   │   │   │       │   ├── Block
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       └── Attribute
│   │   │   │       │   │           └── Edit
│   │   │   │       │   │               └── Main
│   │   │   │       │   ├── _files
│   │   │   │       │   ├── Model
│   │   │   │       │   │   ├── Attribute
│   │   │   │       │   │   ├── Entity
│   │   │   │       │   │   │   └── Attribute
│   │   │   │       │   │   │       └── Frontend
│   │   │   │       │   │   ├── ResourceModel
│   │   │   │       │   │   │   └── Entity
│   │   │   │       │   │   │       └── Attribute
│   │   │   │       │   │   └── Validator
│   │   │   │       │   │       └── Attribute
│   │   │   │       │   └── Setup
│   │   │   │       ├── Elasticsearch
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       └── Category
│   │   │   │       │   ├── Elasticsearch5
│   │   │   │       │   │   └── SearchAdapter
│   │   │   │       │   ├── _files
│   │   │   │       │   ├── Model
│   │   │   │       │   │   ├── Client
│   │   │   │       │   │   └── Indexer
│   │   │   │       │   └── SearchAdapter
│   │   │   │       ├── Email
│   │   │   │       │   ├── Block
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       └── Template
│   │   │   │       │   │           └── Edit
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       └── Email
│   │   │   │       │   └── Model
│   │   │   │       │       ├── _files
│   │   │   │       │       │   ├── code
│   │   │   │       │       │   │   └── Magento
│   │   │   │       │       │   │       └── Email
│   │   │   │       │       │   │           └── view
│   │   │   │       │       │   │               └── email
│   │   │   │       │       │   └── design
│   │   │   │       │       │       ├── adminhtml
│   │   │   │       │       │       │   ├── Magento
│   │   │   │       │       │       │   │   └── default
│   │   │   │       │       │       │   │       ├── Magento_Email
│   │   │   │       │       │       │   │       │   ├── layout
│   │   │   │       │       │       │   │       │   └── templates
│   │   │   │       │       │       │   │       └── Magento_ProductAlert
│   │   │   │       │       │       │   │           └── email
│   │   │   │       │       │       │   └── Vendor
│   │   │   │       │       │       │       ├── custom_theme
│   │   │   │       │       │       │       └── default
│   │   │   │       │       │       └── frontend
│   │   │   │       │       │           ├── Magento
│   │   │   │       │       │           │   └── default
│   │   │   │       │       │           │       ├── Magento_Customer
│   │   │   │       │       │           │       │   └── email
│   │   │   │       │       │           │       ├── Magento_Email
│   │   │   │       │       │           │       │   ├── layout
│   │   │   │       │       │           │       │   └── templates
│   │   │   │       │       │           │       └── web
│   │   │   │       │       │           │           └── css
│   │   │   │       │       │           └── Vendor
│   │   │   │       │       │               ├── custom_theme
│   │   │   │       │       │               │   ├── Magento_Customer
│   │   │   │       │       │               │   │   └── email
│   │   │   │       │       │               │   └── web
│   │   │   │       │       │               │       └── css
│   │   │   │       │       │               └── default
│   │   │   │       │       │                   ├── Magento_Customer
│   │   │   │       │       │                   │   └── email
│   │   │   │       │       │                   └── web
│   │   │   │       │       │                       └── css
│   │   │   │       │       └── Template
│   │   │   │       ├── EncryptionKey
│   │   │   │       │   ├── Block
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       └── Crypt
│   │   │   │       │   │           └── Key
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       └── Crypt
│   │   │   │       │   │           └── Key
│   │   │   │       │   ├── _files
│   │   │   │       │   ├── Model
│   │   │   │       │   │   └── ResourceModel
│   │   │   │       │   │       └── Key
│   │   │   │       │   └── Setup
│   │   │   │       │       └── Patch
│   │   │   │       │           └── Data
│   │   │   │       ├── Fedex
│   │   │   │       │   └── Model
│   │   │   │       │       └── Source
│   │   │   │       ├── Framework
│   │   │   │       │   ├── Api
│   │   │   │       │   │   ├── ExtensionAttribute
│   │   │   │       │   │   │   └── Config
│   │   │   │       │   │   │       └── _files
│   │   │   │       │   │   └── _files
│   │   │   │       │   ├── App
│   │   │   │       │   │   ├── Cache
│   │   │   │       │   │   │   └── Frontend
│   │   │   │       │   │   ├── Config
│   │   │   │       │   │   ├── Filesystem
│   │   │   │       │   │   ├── Language
│   │   │   │       │   │   │   └── _files
│   │   │   │       │   │   │       ├── bar
│   │   │   │       │   │   │       │   ├── en_gb
│   │   │   │       │   │   │       │   └── en_us
│   │   │   │       │   │   │       ├── baz
│   │   │   │       │   │   │       │   └── en_gb
│   │   │   │       │   │   │       ├── first
│   │   │   │       │   │   │       │   └── en_us
│   │   │   │       │   │   │       ├── foo
│   │   │   │       │   │   │       │   └── en_au
│   │   │   │       │   │   │       ├── my
│   │   │   │       │   │   │       │   └── ru_ru
│   │   │   │       │   │   │       ├── second
│   │   │   │       │   │   │       │   └── en_gb
│   │   │   │       │   │   │       └── theirs
│   │   │   │       │   │   │           └── ru_ru
│   │   │   │       │   │   ├── ObjectManager
│   │   │   │       │   │   │   └── ConfigWriter
│   │   │   │       │   │   ├── Request
│   │   │   │       │   │   ├── ResourceConnection
│   │   │   │       │   │   ├── Response
│   │   │   │       │   │   │   └── HeaderProvider
│   │   │   │       │   │   ├── Route
│   │   │   │       │   │   ├── Router
│   │   │   │       │   │   ├── Utility
│   │   │   │       │   │   │   └── _files
│   │   │   │       │   │   │       ├── fixtures
│   │   │   │       │   │   │       │   ├── language
│   │   │   │       │   │   │       │   ├── library
│   │   │   │       │   │   │       │   ├── module
│   │   │   │       │   │   │       │   └── theme
│   │   │   │       │   │   │       └── patterns
│   │   │   │       │   │   └── View
│   │   │   │       │   │       └── Deployment
│   │   │   │       │   ├── Backup
│   │   │   │       │   │   └── _files
│   │   │   │       │   │       └── var
│   │   │   │       │   │           └── backups
│   │   │   │       │   ├── Cache
│   │   │   │       │   │   └── Backend
│   │   │   │       │   ├── Code
│   │   │   │       │   │   ├── _expected
│   │   │   │       │   │   ├── File
│   │   │   │       │   │   │   └── Validator
│   │   │   │       │   │   ├── _files
│   │   │   │       │   │   ├── Generator
│   │   │   │       │   │   ├── GeneratorTest
│   │   │   │       │   │   └── Reader
│   │   │   │       │   │       └── _files
│   │   │   │       │   ├── Communication
│   │   │   │       │   │   └── _files
│   │   │   │       │   ├── Composer
│   │   │   │       │   │   └── _files
│   │   │   │       │   │       ├── testFromClone
│   │   │   │       │   │       │   ├── cache
│   │   │   │       │   │       │   └── vendor
│   │   │   │       │   │       ├── testFromCreateProject
│   │   │   │       │   │       │   ├── cache
│   │   │   │       │   │       │   └── vendor
│   │   │   │       │   │       └── testSkeleton
│   │   │   │       │   │           ├── cache
│   │   │   │       │   │           └── vendor
│   │   │   │       │   ├── Config
│   │   │   │       │   ├── Console
│   │   │   │       │   │   └── _files
│   │   │   │       │   ├── Css
│   │   │   │       │   │   ├── _files
│   │   │   │       │   │   │   └── css
│   │   │   │       │   │   └── PreProcessor
│   │   │   │       │   │       ├── Adapter
│   │   │   │       │   │       ├── File
│   │   │   │       │   │       │   └── Collector
│   │   │   │       │   │       └── _files
│   │   │   │       │   │           ├── code
│   │   │   │       │   │           │   └── Magento
│   │   │   │       │   │           │       ├── Other
│   │   │   │       │   │           │       │   └── view
│   │   │   │       │   │           │       │       └── frontend
│   │   │   │       │   │           │       │           └── web
│   │   │   │       │   │           │       └── Third
│   │   │   │       │   │           │           └── view
│   │   │   │       │   │           │               └── frontend
│   │   │   │       │   │           │                   └── web
│   │   │   │       │   │           ├── design
│   │   │   │       │   │           │   └── frontend
│   │   │   │       │   │           │       └── Test
│   │   │   │       │   │           │           ├── default
│   │   │   │       │   │           │           │   ├── MagentoFrameworkCssTest_Module
│   │   │   │       │   │           │           │   │   └── web
│   │   │   │       │   │           │           │   ├── MagentoFrameworkCssTest_Third
│   │   │   │       │   │           │           │   │   └── web
│   │   │   │       │   │           │           │   └── web
│   │   │   │       │   │           │           └── parent
│   │   │   │       │   │           │               ├── MagentoFrameworkCssTest_Module
│   │   │   │       │   │           │               │   └── web
│   │   │   │       │   │           │               └── MagentoFrameworkCssTest_Second
│   │   │   │       │   │           │                   └── web
│   │   │   │       │   │           └── lib
│   │   │   │       │   │               └── web
│   │   │   │       │   │                   └── some_dir
│   │   │   │       │   │                       └── import_dir
│   │   │   │       │   ├── Data
│   │   │   │       │   │   ├── Argument
│   │   │   │       │   │   │   └── Interpreter
│   │   │   │       │   │   ├── Form
│   │   │   │       │   │   │   └── Element
│   │   │   │       │   │   └── Wysiwyg
│   │   │   │       │   ├── DataObject
│   │   │   │       │   │   └── Copy
│   │   │   │       │   │       └── Config
│   │   │   │       │   │           └── _files
│   │   │   │       │   ├── DB
│   │   │   │       │   │   ├── Adapter
│   │   │   │       │   │   │   └── Pdo
│   │   │   │       │   │   └── DataConverter
│   │   │   │       │   ├── Encryption
│   │   │   │       │   ├── Error
│   │   │   │       │   ├── Exception
│   │   │   │       │   ├── File
│   │   │   │       │   ├── Filesystem
│   │   │   │       │   │   ├── Directory
│   │   │   │       │   │   ├── Driver
│   │   │   │       │   │   ├── File
│   │   │   │       │   │   └── _files
│   │   │   │       │   │       └── foo
│   │   │   │       │   │           └── bar
│   │   │   │       │   │               └── baz
│   │   │   │       │   ├── Filter
│   │   │   │       │   │   └── Template
│   │   │   │       │   │       └── Tokenizer
│   │   │   │       │   ├── GraphQl
│   │   │   │       │   │   ├── Config
│   │   │   │       │   │   └── _files
│   │   │   │       │   ├── HTTP
│   │   │   │       │   │   └── PhpEnvironment
│   │   │   │       │   ├── Image
│   │   │   │       │   │   ├── Adapter
│   │   │   │       │   │   └── _files
│   │   │   │       │   ├── Interception
│   │   │   │       │   │   ├── Config
│   │   │   │       │   │   └── Fixture
│   │   │   │       │   │       └── Intercepted
│   │   │   │       │   ├── Json
│   │   │   │       │   │   └── Helper
│   │   │   │       │   ├── Lock
│   │   │   │       │   │   └── Backend
│   │   │   │       │   ├── Message
│   │   │   │       │   ├── MessageQueue
│   │   │   │       │   │   ├── Consumer
│   │   │   │       │   │   ├── _files
│   │   │   │       │   │   ├── Publisher
│   │   │   │       │   │   ├── Topology
│   │   │   │       │   │   └── UseCase
│   │   │   │       │   │       └── DeprecatedFormat
│   │   │   │       │   ├── Model
│   │   │   │       │   │   ├── Entity
│   │   │   │       │   │   └── ResourceModel
│   │   │   │       │   │       ├── Db
│   │   │   │       │   │       │   └── Collection
│   │   │   │       │   │       ├── Entity
│   │   │   │       │   │       └── Type
│   │   │   │       │   │           └── Db
│   │   │   │       │   │               └── Pdo
│   │   │   │       │   ├── Module
│   │   │   │       │   │   └── Plugin
│   │   │   │       │   ├── Mview
│   │   │   │       │   │   └── View
│   │   │   │       │   ├── ObjectManager
│   │   │   │       │   │   ├── Config
│   │   │   │       │   │   │   └── Reader
│   │   │   │       │   │   ├── Factory
│   │   │   │       │   │   │   └── Dynamic
│   │   │   │       │   │   ├── _files
│   │   │   │       │   │   └── TestAsset
│   │   │   │       │   ├── Pricing
│   │   │   │       │   │   └── Helper
│   │   │   │       │   ├── Profiler
│   │   │   │       │   │   └── Driver
│   │   │   │       │   │       └── Standard
│   │   │   │       │   │           └── Output
│   │   │   │       │   │               └── _files
│   │   │   │       │   ├── Reflection
│   │   │   │       │   ├── Search
│   │   │   │       │   │   ├── Adapter
│   │   │   │       │   │   │   └── Mysql
│   │   │   │       │   │   │       └── Builder
│   │   │   │       │   │   │           └── Query
│   │   │   │       │   │   ├── _files
│   │   │   │       │   │   │   └── etc
│   │   │   │       │   │   └── Request
│   │   │   │       │   │       └── Config
│   │   │   │       │   ├── Session
│   │   │   │       │   │   ├── Config
│   │   │   │       │   │   │   └── Validator
│   │   │   │       │   │   └── SaveHandler
│   │   │   │       │   ├── Stdlib
│   │   │   │       │   │   ├── Cookie
│   │   │   │       │   │   └── DateTime
│   │   │   │       │   │       └── Filter
│   │   │   │       │   ├── Translate
│   │   │   │       │   │   └── _files
│   │   │   │       │   ├── Url
│   │   │   │       │   │   └── Helper
│   │   │   │       │   ├── Validator
│   │   │   │       │   └── View
│   │   │   │       │       ├── Asset
│   │   │   │       │       ├── Design
│   │   │   │       │       │   ├── Fallback
│   │   │   │       │       │   ├── FileResolution
│   │   │   │       │       │   └── Theme
│   │   │   │       │       ├── Element
│   │   │   │       │       │   ├── _files
│   │   │   │       │       │   │   └── frontend
│   │   │   │       │       │   │       └── Magento
│   │   │   │       │       │   │           └── plushe
│   │   │   │       │       │   │               └── css
│   │   │   │       │       │   ├── Text
│   │   │   │       │       │   └── UiComponent
│   │   │   │       │       │       └── Config
│   │   │   │       │       │           └── Provider
│   │   │   │       │       ├── _files
│   │   │   │       │       │   ├── fallback
│   │   │   │       │       │   │   ├── app
│   │   │   │       │       │   │   │   └── code
│   │   │   │       │       │   │   │       └── ViewTest_Module
│   │   │   │       │       │   │   ├── design
│   │   │   │       │       │   │   │   └── frontend
│   │   │   │       │       │   │   │       └── Vendor
│   │   │   │       │       │   │   │           ├── custom_theme
│   │   │   │       │       │   │   │           │   ├── i18n
│   │   │   │       │       │   │   │           │   ├── templates
│   │   │   │       │       │   │   │           │   ├── ViewTest_Module
│   │   │   │       │       │   │   │           │   │   ├── templates
│   │   │   │       │       │   │   │           │   │   └── web
│   │   │   │       │       │   │   │           │   └── web
│   │   │   │       │       │   │   │           │       └── mage
│   │   │   │       │       │   │   │           ├── custom_theme2
│   │   │   │       │       │   │   │           ├── default
│   │   │   │       │       │   │   │           │   ├── i18n
│   │   │   │       │       │   │   │           │   ├── templates
│   │   │   │       │       │   │   │           │   ├── ViewTest_Module
│   │   │   │       │       │   │   │           │   │   ├── templates
│   │   │   │       │       │   │   │           │   │   └── web
│   │   │   │       │       │   │   │           │   │       └── i18n
│   │   │   │       │       │   │   │           │   │           └── ru_RU
│   │   │   │       │       │   │   │           │   └── web
│   │   │   │       │       │   │   │           │       └── i18n
│   │   │   │       │       │   │   │           │           └── ru_RU
│   │   │   │       │       │   │   │           └── standalone_theme
│   │   │   │       │       │   │   └── lib
│   │   │   │       │       │   │       └── web
│   │   │   │       │       │   │           └── mage
│   │   │   │       │       │   ├── Fixture_Module
│   │   │   │       │       │   ├── layout
│   │   │   │       │       │   ├── layout_directives_test
│   │   │   │       │       │   ├── layout_with_exceptions
│   │   │   │       │       │   ├── Magento
│   │   │   │       │       │   │   ├── ModuleA
│   │   │   │       │       │   │   │   └── view
│   │   │   │       │       │   │   │       └── adminhtml
│   │   │   │       │       │   │   │           └── product
│   │   │   │       │       │   │   ├── ModuleB
│   │   │   │       │       │   │   │   └── view
│   │   │   │       │       │   │   │       └── adminhtml
│   │   │   │       │       │   │   │           └── images
│   │   │   │       │       │   │   └── ModuleC
│   │   │   │       │       │   │       └── view
│   │   │   │       │       │   │           └── adminhtml
│   │   │   │       │       │   │               └── images
│   │   │   │       │       │   ├── static
│   │   │   │       │       │   │   ├── expected
│   │   │   │       │       │   │   └── theme
│   │   │   │       │       │   │       └── web
│   │   │   │       │       │   │           ├── css
│   │   │   │       │       │   │           └── js
│   │   │   │       │       │   └── UiComponent
│   │   │   │       │       │       ├── expected
│   │   │   │       │       │       └── theme
│   │   │   │       │       │           ├── Magento_Catalog
│   │   │   │       │       │           │   └── ui_component
│   │   │   │       │       │           └── Magento_Customer
│   │   │   │       │       │               └── ui_component
│   │   │   │       │       ├── Fixture
│   │   │   │       │       │   └── Block
│   │   │   │       │       ├── Layout
│   │   │   │       │       │   ├── _files
│   │   │   │       │       │   ├── _mergeFiles
│   │   │   │       │       │   │   └── layout
│   │   │   │       │       │   └── Reader
│   │   │   │       │       │       └── _files
│   │   │   │       │       ├── Model
│   │   │   │       │       │   └── Layout
│   │   │   │       │       │       └── _files
│   │   │   │       │       │           └── layout
│   │   │   │       │       ├── Page
│   │   │   │       │       │   └── Config
│   │   │   │       │       │       └── Reader
│   │   │   │       │       │           └── _files
│   │   │   │       │       └── Utility
│   │   │   │       │           └── _files
│   │   │   │       │               ├── layout
│   │   │   │       │               └── layout_merged
│   │   │   │       ├── GiftMessage
│   │   │   │       │   ├── _files
│   │   │   │       │   ├── Model
│   │   │   │       │   └── Observer
│   │   │   │       ├── GoogleAdwords
│   │   │   │       │   └── Model
│   │   │   │       │       └── Validator
│   │   │   │       ├── GoogleAnalytics
│   │   │   │       │   └── Block
│   │   │   │       ├── GraphQl
│   │   │   │       │   ├── Catalog
│   │   │   │       │   │   └── _files
│   │   │   │       │   ├── Controller
│   │   │   │       │   ├── Quote
│   │   │   │       │   │   └── _files
│   │   │   │       │   │       ├── customer
│   │   │   │       │   │       └── guest
│   │   │   │       │   ├── Tax
│   │   │   │       │   │   └── _files
│   │   │   │       │   └── Ups
│   │   │   │       │       └── _files
│   │   │   │       ├── GraphQlCache
│   │   │   │       │   └── Controller
│   │   │   │       │       ├── Catalog
│   │   │   │       │       └── Cms
│   │   │   │       ├── GroupedImportExport
│   │   │   │       │   └── Model
│   │   │   │       │       └── Import
│   │   │   │       │           ├── _files
│   │   │   │       │           └── Product
│   │   │   │       │               └── Type
│   │   │   │       ├── GroupedProduct
│   │   │   │       │   ├── _files
│   │   │   │       │   ├── Model
│   │   │   │       │   │   ├── Product
│   │   │   │       │   │   │   └── Type
│   │   │   │       │   │   └── ResourceModel
│   │   │   │       │   │       └── Product
│   │   │   │       │   │           ├── Indexer
│   │   │   │       │   │           │   ├── Price
│   │   │   │       │   │           │   └── Stock
│   │   │   │       │   │           └── Type
│   │   │   │       │   │               └── Grouped
│   │   │   │       │   └── Pricing
│   │   │   │       │       └── Price
│   │   │   │       ├── ImportExport
│   │   │   │       │   ├── Block
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       ├── Export
│   │   │   │       │   │       │   └── Edit
│   │   │   │       │   │       └── Import
│   │   │   │       │   │           └── Edit
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       ├── _files
│   │   │   │       │   │       └── Import
│   │   │   │       │   │           └── _files
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Model
│   │   │   │       │       ├── Export
│   │   │   │       │       │   └── Entity
│   │   │   │       │       ├── Import
│   │   │   │       │       │   └── Entity
│   │   │   │       │       │       └── _files
│   │   │   │       │       ├── ResourceModel
│   │   │   │       │       │   └── Import
│   │   │   │       │       └── Source
│   │   │   │       │           └── Import
│   │   │   │       ├── Indexer
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   └── Model
│   │   │   │       │       └── Config
│   │   │   │       │           └── _files
│   │   │   │       ├── InstantPurchase
│   │   │   │       │   ├── CustomerData
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Model
│   │   │   │       ├── Integration
│   │   │   │       │   ├── Block
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       ├── Integration
│   │   │   │       │   │       │   ├── Activate
│   │   │   │       │   │       │   │   └── Permissions
│   │   │   │       │   │       │   │       └── Tab
│   │   │   │       │   │       │   └── Edit
│   │   │   │       │   │       │       └── Tab
│   │   │   │       │   │       ├── System
│   │   │   │       │   │       │   └── Config
│   │   │   │       │   │       └── Widget
│   │   │   │       │   │           └── Grid
│   │   │   │       │   │               └── Column
│   │   │   │       │   │                   └── Renderer
│   │   │   │       │   │                       ├── Button
│   │   │   │       │   │                       └── Link
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Model
│   │   │   │       │       ├── Config
│   │   │   │       │       │   ├── Consolidated
│   │   │   │       │       │   │   └── _files
│   │   │   │       │       │   ├── _files
│   │   │   │       │       │   └── Integration
│   │   │   │       │       │       └── _files
│   │   │   │       │       └── ResourceModel
│   │   │   │       │           └── Oauth
│   │   │   │       ├── MediaStorage
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Model
│   │   │   │       │       └── File
│   │   │   │       │           └── Storage
│   │   │   │       ├── MessageQueue
│   │   │   │       │   └── Model
│   │   │   │       │       ├── Cron
│   │   │   │       │       └── Plugin
│   │   │   │       │           └── ResourceModel
│   │   │   │       ├── Multishipping
│   │   │   │       │   ├── Block
│   │   │   │       │   │   └── Checkout
│   │   │   │       │   │       └── Address
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Checkout
│   │   │   │       │   ├── Fixtures
│   │   │   │       │   └── Model
│   │   │   │       │       └── Checkout
│   │   │   │       │           └── Type
│   │   │   │       ├── MysqlMq
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Model
│   │   │   │       │       └── Driver
│   │   │   │       ├── NewRelicReporting
│   │   │   │       │   ├── Model
│   │   │   │       │   │   └── Module
│   │   │   │       │   └── Plugin
│   │   │   │       ├── Newsletter
│   │   │   │       │   ├── Block
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       ├── Queue
│   │   │   │       │   │       │   └── Edit
│   │   │   │       │   │       └── Subscriber
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   ├── _files
│   │   │   │       │   ├── Helper
│   │   │   │       │   └── Model
│   │   │   │       │       ├── Plugin
│   │   │   │       │       └── ResourceModel
│   │   │   │       │           ├── Problem
│   │   │   │       │           └── Subscriber
│   │   │   │       ├── OfflineShipping
│   │   │   │       │   └── _files
│   │   │   │       ├── PageCache
│   │   │   │       │   ├── Block
│   │   │   │       │   │   └── System
│   │   │   │       │   │       └── Config
│   │   │   │       │   │           └── Form
│   │   │   │       │   │               └── Field
│   │   │   │       │   ├── Model
│   │   │   │       │   │   ├── _files
│   │   │   │       │   │   ├── Layout
│   │   │   │       │   │   └── System
│   │   │   │       │   │       └── Config
│   │   │   │       │   │           └── Backend
│   │   │   │       │   ├── Observer
│   │   │   │       │   │   └── SwitchPageCacheOnMaintenance
│   │   │   │       │   └── Plugin
│   │   │   │       ├── Payment
│   │   │   │       │   ├── Block
│   │   │   │       │   │   └── Transparent
│   │   │   │       │   ├── _files
│   │   │   │       │   ├── Helper
│   │   │   │       │   ├── Model
│   │   │   │       │   │   ├── Config
│   │   │   │       │   │   └── _files
│   │   │   │       │   └── Observer
│   │   │   │       ├── Paypal
│   │   │   │       │   ├── Adminhtml
│   │   │   │       │   │   └── Paypal
│   │   │   │       │   ├── Block
│   │   │   │       │   │   ├── Adminhtml
│   │   │   │       │   │   │   └── Billing
│   │   │   │       │   │   │       └── Agreement
│   │   │   │       │   │   │           └── View
│   │   │   │       │   │   │               └── Tab
│   │   │   │       │   │   ├── Billing
│   │   │   │       │   │   │   └── Agreement
│   │   │   │       │   │   ├── Bml
│   │   │   │       │   │   ├── Express
│   │   │   │       │   │   │   └── Review
│   │   │   │       │   │   └── Payment
│   │   │   │       │   │       └── Form
│   │   │   │       │   │           └── Billing
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   ├── Adminhtml
│   │   │   │       │   │   │   ├── Billing
│   │   │   │       │   │   │   │   └── Agreement
│   │   │   │       │   │   │   ├── Express
│   │   │   │       │   │   │   └── Paypal
│   │   │   │       │   │   │       └── Reports
│   │   │   │       │   │   ├── Billing
│   │   │   │       │   │   ├── Payflow
│   │   │   │       │   │   └── Transparent
│   │   │   │       │   ├── _files
│   │   │   │       │   ├── Fixtures
│   │   │   │       │   ├── Helper
│   │   │   │       │   └── Model
│   │   │   │       │       ├── Api
│   │   │   │       │       ├── Express
│   │   │   │       │       ├── Hostedpro
│   │   │   │       │       ├── Payflow
│   │   │   │       │       │   └── Service
│   │   │   │       │       │       └── Request
│   │   │   │       │       ├── Payment
│   │   │   │       │       │   └── Method
│   │   │   │       │       │       └── Billing
│   │   │   │       │       ├── Report
│   │   │   │       │       └── ResourceModel
│   │   │   │       │           └── Billing
│   │   │   │       │               └── Agreement
│   │   │   │       ├── Persistent
│   │   │   │       │   ├── Block
│   │   │   │       │   │   └── Header
│   │   │   │       │   ├── _files
│   │   │   │       │   ├── Model
│   │   │   │       │   │   ├── Checkout
│   │   │   │       │   │   └── Persistent
│   │   │   │       │   │       └── _files
│   │   │   │       │   └── Observer
│   │   │   │       ├── Phpserver
│   │   │   │       ├── ProductAlert
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Model
│   │   │   │       ├── Quote
│   │   │   │       │   ├── etc
│   │   │   │       │   ├── _files
│   │   │   │       │   ├── Fixtures
│   │   │   │       │   ├── Model
│   │   │   │       │   │   ├── Plugin
│   │   │   │       │   │   └── Quote
│   │   │   │       │   │       └── Item
│   │   │   │       │   └── Observer
│   │   │   │       │       └── Frontend
│   │   │   │       │           └── Quote
│   │   │   │       │               └── Address
│   │   │   │       ├── ReleaseNotification
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       └── Dashboard
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Model
│   │   │   │       │       └── ResourceModel
│   │   │   │       │           └── Viewer
│   │   │   │       ├── Reports
│   │   │   │       │   ├── Block
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       ├── Filter
│   │   │   │       │   │       ├── Sales
│   │   │   │       │   │       │   ├── Bestsellers
│   │   │   │       │   │       │   ├── Coupons
│   │   │   │       │   │       │   ├── Invoiced
│   │   │   │       │   │       │   ├── Refunded
│   │   │   │       │   │       │   ├── Sales
│   │   │   │       │   │       │   ├── Shipping
│   │   │   │       │   │       │   └── Tax
│   │   │   │       │   │       └── Shopcart
│   │   │   │       │   │           ├── Abandoned
│   │   │   │       │   │           └── Product
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       └── Report
│   │   │   │       │   │           └── Product
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Model
│   │   │   │       │       └── ResourceModel
│   │   │   │       │           ├── Product
│   │   │   │       │           │   └── Lowstock
│   │   │   │       │           ├── Report
│   │   │   │       │           │   ├── Product
│   │   │   │       │           │   │   └── Viewed
│   │   │   │       │           │   └── Sold
│   │   │   │       │           └── Review
│   │   │   │       │               ├── Customer
│   │   │   │       │               └── Product
│   │   │   │       ├── Review
│   │   │   │       │   ├── Block
│   │   │   │       │   │   ├── Adminhtml
│   │   │   │       │   │   │   └── Edit
│   │   │   │       │   │   │       └── Tab
│   │   │   │       │   │   └── Product
│   │   │   │       │   ├── Controller
│   │   │   │       │   ├── _files
│   │   │   │       │   ├── Model
│   │   │   │       │   │   └── ResourceModel
│   │   │   │       │   │       ├── Rating
│   │   │   │       │   │       └── Review
│   │   │   │       │   │           └── Product
│   │   │   │       │   └── Observer
│   │   │   │       ├── Rss
│   │   │   │       │   └── Controller
│   │   │   │       │       └── Feed
│   │   │   │       ├── Rule
│   │   │   │       │   └── Model
│   │   │   │       │       └── Condition
│   │   │   │       │           └── Sql
│   │   │   │       ├── Sales
│   │   │   │       │   ├── Api
│   │   │   │       │   ├── Block
│   │   │   │       │   │   ├── Adminhtml
│   │   │   │       │   │   │   ├── Items
│   │   │   │       │   │   │   │   └── Column
│   │   │   │       │   │   │   ├── Order
│   │   │   │       │   │   │   │   ├── Create
│   │   │   │       │   │   │   │   │   ├── Billing
│   │   │   │       │   │   │   │   │   │   └── Method
│   │   │   │       │   │   │   │   │   ├── Form
│   │   │   │       │   │   │   │   │   └── Giftmessage
│   │   │   │       │   │   │   │   └── View
│   │   │   │       │   │   │   └── Report
│   │   │   │       │   │   │       └── Filter
│   │   │   │       │   │   │           └── Form
│   │   │   │       │   │   └── Order
│   │   │   │       │   │       ├── Creditmemo
│   │   │   │       │   │       ├── Invoice
│   │   │   │       │   │       └── PrintOrder
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   ├── Adminhtml
│   │   │   │       │   │   │   └── Order
│   │   │   │       │   │   │       ├── Create
│   │   │   │       │   │   │       ├── Creditmemo
│   │   │   │       │   │   │       ├── Invoice
│   │   │   │       │   │   │       └── Stub
│   │   │   │       │   │   └── Guest
│   │   │   │       │   ├── CustomerData
│   │   │   │       │   ├── etc
│   │   │   │       │   ├── _files
│   │   │   │       │   ├── Model
│   │   │   │       │   │   ├── AdminOrder
│   │   │   │       │   │   ├── Convert
│   │   │   │       │   │   ├── CronJob
│   │   │   │       │   │   ├── Order
│   │   │   │       │   │   │   ├── Address
│   │   │   │       │   │   │   ├── Email
│   │   │   │       │   │   │   │   └── Sender
│   │   │   │       │   │   │   ├── Payment
│   │   │   │       │   │   │   └── Reorder
│   │   │   │       │   │   ├── ResourceModel
│   │   │   │       │   │   │   ├── Order
│   │   │   │       │   │   │   │   ├── Grid
│   │   │   │       │   │   │   │   └── Payment
│   │   │   │       │   │   │   ├── Report
│   │   │   │       │   │   │   │   ├── Bestsellers
│   │   │   │       │   │   │   │   ├── Invoiced
│   │   │   │       │   │   │   │   │   └── Collection
│   │   │   │       │   │   │   │   ├── Refunded
│   │   │   │       │   │   │   │   │   └── Collection
│   │   │   │       │   │   │   │   └── Shipping
│   │   │   │       │   │   │   │       └── Collection
│   │   │   │       │   │   │   └── Sale
│   │   │   │       │   │   └── Service
│   │   │   │       │   └── Observer
│   │   │   │       │       └── Backend
│   │   │   │       ├── SalesRule
│   │   │   │       │   ├── Block
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       └── Promo
│   │   │   │       │   │           └── Quote
│   │   │   │       │   │               └── Edit
│   │   │   │       │   │                   └── Tab
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Model
│   │   │   │       │       ├── Quote
│   │   │   │       │       │   └── Address
│   │   │   │       │       │       └── Total
│   │   │   │       │       ├── ResourceModel
│   │   │   │       │       │   ├── Report
│   │   │   │       │       │   │   └── Rule
│   │   │   │       │       │   └── Rule
│   │   │   │       │       └── Rule
│   │   │   │       │           ├── Action
│   │   │   │       │           │   └── Discount
│   │   │   │       │           └── Condition
│   │   │   │       ├── SampleData
│   │   │   │       │   ├── _files
│   │   │   │       │   │   └── Modules
│   │   │   │       │   │       ├── FirstModule
│   │   │   │       │   │       ├── SecondModule
│   │   │   │       │   │       └── ThirdModule
│   │   │   │       │   └── Model
│   │   │   │       ├── Search
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Model
│   │   │   │       │       ├── Adminhtml
│   │   │   │       │       │   └── System
│   │   │   │       │       │       └── Config
│   │   │   │       │       │           └── Source
│   │   │   │       │       ├── ResourceModel
│   │   │   │       │       └── SearchEngine
│   │   │   │       ├── Security
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       └── Session
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Model
│   │   │   │       │       ├── Plugin
│   │   │   │       │       └── ResourceModel
│   │   │   │       │           ├── AdminSessionInfo
│   │   │   │       │           └── PasswordResetRequestEvent
│   │   │   │       ├── SendFriend
│   │   │   │       │   ├── Block
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Product
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Fixtures
│   │   │   │       ├── Setup
│   │   │   │       │   ├── Console
│   │   │   │       │   │   └── Command
│   │   │   │       │   │       └── _files
│   │   │   │       │   │           ├── config
│   │   │   │       │   │           ├── output
│   │   │   │       │   │           ├── phrases
│   │   │   │       │   │           └── root
│   │   │   │       │   │               ├── app
│   │   │   │       │   │               │   └── code
│   │   │   │       │   │               │       └── Magento
│   │   │   │       │   │               │           ├── A
│   │   │   │       │   │               │           │   ├── etc
│   │   │   │       │   │               │           │   └── Model
│   │   │   │       │   │               │           ├── B
│   │   │   │       │   │               │           │   ├── etc
│   │   │   │       │   │               │           │   └── Model
│   │   │   │       │   │               │           ├── C
│   │   │   │       │   │               │           └── D
│   │   │   │       │   │               └── lib
│   │   │   │       │   │                   └── internal
│   │   │   │       │   │                       └── Magento
│   │   │   │       │   │                           └── Framework
│   │   │   │       │   │                               └── Test
│   │   │   │       │   │                                   └── Unit
│   │   │   │       │   │                                       └── View
│   │   │   │       │   │                                           └── Element
│   │   │   │       │   ├── Controller
│   │   │   │       │   ├── Declaration
│   │   │   │       │   │   └── _files
│   │   │   │       │   │       └── ignore_whitelisting
│   │   │   │       │   ├── Fixtures
│   │   │   │       │   │   ├── _files
│   │   │   │       │   │   └── FixturesAsserts
│   │   │   │       │   ├── Model
│   │   │   │       │   │   ├── Cron
│   │   │   │       │   │   │   └── _files
│   │   │   │       │   │   ├── _files
│   │   │   │       │   │   │   └── testSkeleton
│   │   │   │       │   │   └── FixtureGenerator
│   │   │   │       │   └── Module
│   │   │   │       │       ├── Dependency
│   │   │   │       │       │   ├── _files
│   │   │   │       │       │   │   ├── code
│   │   │   │       │       │   │   │   └── Magento
│   │   │   │       │       │   │   │       └── FirstModule
│   │   │   │       │       │   │   │           ├── etc
│   │   │   │       │       │   │   │           ├── Helper
│   │   │   │       │       │   │   │           ├── Model
│   │   │   │       │       │   │   │           └── view
│   │   │   │       │       │   │   │               └── frontend
│   │   │   │       │       │   │   └── expected
│   │   │   │       │       │   ├── Parser
│   │   │   │       │       │   │   ├── Composer
│   │   │   │       │       │   │   └── Config
│   │   │   │       │       │   └── Report
│   │   │   │       │       └── I18n
│   │   │   │       │           ├── Dictionary
│   │   │   │       │           │   └── _files
│   │   │   │       │           │       ├── expected
│   │   │   │       │           │       └── source
│   │   │   │       │           │           ├── app
│   │   │   │       │           │           │   ├── code
│   │   │   │       │           │           │   │   └── Magento
│   │   │   │       │           │           │   │       ├── FirstModule
│   │   │   │       │           │           │   │       │   ├── Helper
│   │   │   │       │           │           │   │       │   ├── Model
│   │   │   │       │           │           │   │       │   └── view
│   │   │   │       │           │           │   │       │       └── frontend
│   │   │   │       │           │           │   │       └── SecondModule
│   │   │   │       │           │           │   │           └── Model
│   │   │   │       │           │           │   └── design
│   │   │   │       │           │           │       └── adminhtml
│   │   │   │       │           │           │           └── default
│   │   │   │       │           │           │               └── backend
│   │   │   │       │           │           ├── lib
│   │   │   │       │           │           │   └── web
│   │   │   │       │           │           │       ├── mage
│   │   │   │       │           │           │       └── varien
│   │   │   │       │           │           └── not_magento_dir
│   │   │   │       │           ├── Pack
│   │   │   │       │           │   └── _files
│   │   │   │       │           │       └── expected
│   │   │   │       │           │           ├── app
│   │   │   │       │           │           │   ├── code
│   │   │   │       │           │           │   │   └── Magento
│   │   │   │       │           │           │   │       ├── FirstModule
│   │   │   │       │           │           │   │       │   └── i18n
│   │   │   │       │           │           │   │       └── SecondModule
│   │   │   │       │           │           │   │           └── i18n
│   │   │   │       │           │           │   └── design
│   │   │   │       │           │           │       └── adminhtml
│   │   │   │       │           │           │           └── default
│   │   │   │       │           │           │               └── i18n
│   │   │   │       │           │           └── lib
│   │   │   │       │           │               └── web
│   │   │   │       │           │                   └── i18n
│   │   │   │       │           └── Parser
│   │   │   │       │               └── Adapter
│   │   │   │       │                   ├── _files
│   │   │   │       │                   └── Php
│   │   │   │       │                       └── Tokenizer
│   │   │   │       │                           ├── _files
│   │   │   │       │                           └── Translate
│   │   │   │       ├── Shipping
│   │   │   │       │   ├── Block
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       └── Order
│   │   │   │       │   │           └── Shipment
│   │   │   │       │   ├── Helper
│   │   │   │       │   └── Model
│   │   │   │       ├── Signifyd
│   │   │   │       │   ├── Block
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Webhooks
│   │   │   │       │   ├── _files
│   │   │   │       │   ├── Model
│   │   │   │       │   │   ├── CaseServices
│   │   │   │       │   │   ├── Guarantee
│   │   │   │       │   │   └── SignifydGateway
│   │   │   │       │   │       └── Request
│   │   │   │       │   ├── Observer
│   │   │   │       │   └── Plugin
│   │   │   │       ├── Sitemap
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Model
│   │   │   │       │       ├── ItemProvider
│   │   │   │       │       └── ResourceModel
│   │   │   │       │           ├── Catalog
│   │   │   │       │           └── Cms
│   │   │   │       ├── Store
│   │   │   │       │   ├── App
│   │   │   │       │   │   ├── FrontController
│   │   │   │       │   │   │   └── Plugin
│   │   │   │       │   │   └── Request
│   │   │   │       │   ├── Block
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Store
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Model
│   │   │   │       │       ├── App
│   │   │   │       │       └── ResourceModel
│   │   │   │       │           └── Store
│   │   │   │       ├── SwaggerWebapi
│   │   │   │       │   └── Block
│   │   │   │       │       └── Swagger
│   │   │   │       ├── Swatches
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       ├── Iframe
│   │   │   │       │   │       └── Product
│   │   │   │       │   ├── _files
│   │   │   │       │   ├── Model
│   │   │   │       │   └── Observer
│   │   │   │       ├── Tax
│   │   │   │       │   ├── Block
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       └── Rate
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   ├── _files
│   │   │   │       │   │   └── scenarios
│   │   │   │       │   ├── Helper
│   │   │   │       │   ├── Model
│   │   │   │       │   │   ├── Calculation
│   │   │   │       │   │   ├── Rate
│   │   │   │       │   │   ├── ResourceModel
│   │   │   │       │   │   │   ├── Calculation
│   │   │   │       │   │   │   │   └── Rule
│   │   │   │       │   │   │   └── Report
│   │   │   │       │   │   ├── Sales
│   │   │   │       │   │   │   └── Total
│   │   │   │       │   │   │       └── Quote
│   │   │   │       │   │   └── TaxClass
│   │   │   │       │   │       ├── Source
│   │   │   │       │   │       └── Type
│   │   │   │       │   └── Pricing
│   │   │   │       ├── TaxImportExport
│   │   │   │       │   ├── Block
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       └── Rate
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       └── Rate
│   │   │   │       │   └── Model
│   │   │   │       │       └── Rate
│   │   │   │       │           └── _files
│   │   │   │       ├── Test
│   │   │   │       │   └── Integrity
│   │   │   │       │       ├── Magento
│   │   │   │       │       │   ├── Payment
│   │   │   │       │       │   └── Widget
│   │   │   │       │       ├── Modular
│   │   │   │       │       │   ├── _files
│   │   │   │       │       │   └── Magento
│   │   │   │       │       │       ├── Catalog
│   │   │   │       │       │       ├── Customer
│   │   │   │       │       │       ├── Email
│   │   │   │       │       │       └── Sales
│   │   │   │       │       └── Theme
│   │   │   │       ├── TestFixture
│   │   │   │       │   └── Controller
│   │   │   │       │       └── Adminhtml
│   │   │   │       ├── TestModuleSample
│   │   │   │       ├── Theme
│   │   │   │       │   ├── Block
│   │   │   │       │   │   ├── Adminhtml
│   │   │   │       │   │   │   └── System
│   │   │   │       │   │   │       └── Design
│   │   │   │       │   │   │           └── Theme
│   │   │   │       │   │   │               └── Edit
│   │   │   │       │   │   │                   └── Tab
│   │   │   │       │   │   └── Html
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       └── System
│   │   │   │       │   │           └── Design
│   │   │   │       │   │               ├── Config
│   │   │   │       │   │               └── _files
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Model
│   │   │   │       │       ├── Config
│   │   │   │       │       │   └── Processor
│   │   │   │       │       ├── Design
│   │   │   │       │       │   └── Backend
│   │   │   │       │       ├── _files
│   │   │   │       │       │   └── design
│   │   │   │       │       │       ├── adminhtml
│   │   │   │       │       │       │   └── Vendor
│   │   │   │       │       │       │       └── test
│   │   │   │       │       │       ├── area_two
│   │   │   │       │       │       │   └── Vendor
│   │   │   │       │       │       │       └── theme_one
│   │   │   │       │       │       │           └── web
│   │   │   │       │       │       ├── design_area
│   │   │   │       │       │       │   └── Vendor
│   │   │   │       │       │       │       └── theme_one
│   │   │   │       │       │       │           └── web
│   │   │   │       │       │       └── frontend
│   │   │   │       │       │           ├── Magento
│   │   │   │       │       │           │   ├── default
│   │   │   │       │       │           │   └── default_iphone
│   │   │   │       │       │           │       └── images
│   │   │   │       │       │           ├── Test
│   │   │   │       │       │           │   ├── cache_test_theme
│   │   │   │       │       │           │   ├── default
│   │   │   │       │       │           │   │   ├── etc
│   │   │   │       │       │           │   │   ├── i18n
│   │   │   │       │       │           │   │   ├── Magento_Catalog
│   │   │   │       │       │           │   │   │   └── templates
│   │   │   │       │       │           │   │   ├── Magento_Cms
│   │   │   │       │       │           │   │   ├── Magento_Core
│   │   │   │       │       │           │   │   ├── Namespace_Module
│   │   │   │       │       │           │   │   │   └── web
│   │   │   │       │       │           │   │   └── web
│   │   │   │       │       │           │   │       ├── css
│   │   │   │       │       │           │   │       ├── i18n
│   │   │   │       │       │           │   │       │   └── fr_FR
│   │   │   │       │       │           │   │       ├── images
│   │   │   │       │       │           │   │       └── js
│   │   │   │       │       │           │   ├── publication
│   │   │   │       │       │           │   └── test_theme
│   │   │   │       │       │           └── Vendor
│   │   │   │       │       │               ├── custom_theme
│   │   │   │       │       │               │   └── Fixture_Module
│   │   │   │       │       │               │       └── web
│   │   │   │       │       │               └── default
│   │   │   │       │       │                   ├── Namespace_Module
│   │   │   │       │       │                   │   └── web
│   │   │   │       │       │                   └── web
│   │   │   │       │       │                       ├── css
│   │   │   │       │       │                       │   └── deep
│   │   │   │       │       │                       └── images
│   │   │   │       │       ├── Layout
│   │   │   │       │       │   ├── Config
│   │   │   │       │       │   └── _files
│   │   │   │       │       ├── ResourceModel
│   │   │   │       │       │   └── Theme
│   │   │   │       │       ├── Theme
│   │   │   │       │       │   ├── Domain
│   │   │   │       │       │   └── Source
│   │   │   │       │       │       └── _files
│   │   │   │       │       │           └── design
│   │   │   │       │       │               └── frontend
│   │   │   │       │       │                   ├── a_d
│   │   │   │       │       │                   ├── b_e
│   │   │   │       │       │                   ├── magento_default
│   │   │   │       │       │                   └── magento_g
│   │   │   │       │       └── View
│   │   │   │       ├── Translation
│   │   │   │       │   ├── Controller
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Model
│   │   │   │       │       └── _files
│   │   │   │       │           ├── local_config
│   │   │   │       │           │   ├── local_config
│   │   │   │       │           │   │   └── custom
│   │   │   │       │           │   └── no_local_config
│   │   │   │       │           │       └── custom
│   │   │   │       │           ├── locale
│   │   │   │       │           │   └── en_AU
│   │   │   │       │           ├── Magento
│   │   │   │       │           │   ├── Catalog
│   │   │   │       │           │   │   └── i18n
│   │   │   │       │           │   ├── design
│   │   │   │       │           │   │   └── Magento
│   │   │   │       │           │   │       └── theme
│   │   │   │       │           │   │           └── i18n
│   │   │   │       │           │   └── Store
│   │   │   │       │           │       └── i18n
│   │   │   │       │           └── media
│   │   │   │       ├── Ui
│   │   │   │       │   ├── Api
│   │   │   │       │   ├── Component
│   │   │   │       │   ├── Config
│   │   │   │       │   │   └── Reader
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       └── Index
│   │   │   │       │   │           └── Renderer
│   │   │   │       │   ├── DataProvider
│   │   │   │       │   ├── _files
│   │   │   │       │   │   └── view
│   │   │   │       │   │       ├── module_one
│   │   │   │       │   │       │   └── ui_component
│   │   │   │       │   │       │       └── etc
│   │   │   │       │   │       ├── module_two
│   │   │   │       │   │       │   └── ui_component
│   │   │   │       │   │       │       └── etc
│   │   │   │       │   │       └── ui_component
│   │   │   │       │   │           ├── arbitrary
│   │   │   │       │   │           ├── etc
│   │   │   │       │   │           ├── expected
│   │   │   │       │   │           ├── mixed
│   │   │   │       │   │           └── semantic
│   │   │   │       │   └── Model
│   │   │   │       ├── Ups
│   │   │   │       │   └── Model
│   │   │   │       ├── UrlRewrite
│   │   │   │       │   ├── Block
│   │   │   │       │   │   ├── Catalog
│   │   │   │       │   │   │   ├── Category
│   │   │   │       │   │   │   ├── Edit
│   │   │   │       │   │   │   └── Product
│   │   │   │       │   │   ├── Cms
│   │   │   │       │   │   │   └── Page
│   │   │   │       │   │   │       └── Edit
│   │   │   │       │   │   └── Edit
│   │   │   │       │   ├── Controller
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Model
│   │   │   │       │       └── StoreSwitcher
│   │   │   │       ├── User
│   │   │   │       │   ├── Block
│   │   │   │       │   │   ├── Role
│   │   │   │       │   │   │   ├── Grid
│   │   │   │       │   │   │   └── Tab
│   │   │   │       │   │   └── User
│   │   │   │       │   │       └── Edit
│   │   │   │       │   │           └── Tab
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       ├── Locks
│   │   │   │       │   │       └── User
│   │   │   │       │   ├── _files
│   │   │   │       │   ├── Helper
│   │   │   │       │   └── Model
│   │   │   │       │       └── ResourceModel
│   │   │   │       │           └── Role
│   │   │   │       │               └── User
│   │   │   │       ├── Usps
│   │   │   │       │   ├── Api
│   │   │   │       │   └── Fixtures
│   │   │   │       ├── Variable
│   │   │   │       │   ├── Block
│   │   │   │       │   │   └── System
│   │   │   │       │   │       └── Variable
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       └── System
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Model
│   │   │   │       ├── Vault
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Model
│   │   │   │       │       └── ResourceModel
│   │   │   │       ├── Version
│   │   │   │       │   └── Controller
│   │   │   │       │       └── Index
│   │   │   │       ├── Webapi
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Rest
│   │   │   │       │   ├── _files
│   │   │   │       │   ├── Model
│   │   │   │       │   │   ├── Config
│   │   │   │       │   │   │   └── _files
│   │   │   │       │   │   └── Soap
│   │   │   │       │   └── Service
│   │   │   │       │       └── Entity
│   │   │   │       ├── WebapiAsync
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Rest
│   │   │   │       │   ├── Model
│   │   │   │       │   │   └── Rest
│   │   │   │       │   │       └── Swagger
│   │   │   │       │   └── Plugin
│   │   │   │       ├── Weee
│   │   │   │       │   ├── _files
│   │   │   │       │   └── Model
│   │   │   │       │       └── ResourceModel
│   │   │   │       ├── Widget
│   │   │   │       │   ├── Block
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       └── Widget
│   │   │   │       │   │           └── Instance
│   │   │   │       │   │               └── Edit
│   │   │   │       │   │                   ├── Chooser
│   │   │   │       │   │                   │   └── _files
│   │   │   │       │   │                   │       └── layout
│   │   │   │       │   │                   └── Tab
│   │   │   │       │   │                       └── Main
│   │   │   │       │   ├── Controller
│   │   │   │       │   │   └── Adminhtml
│   │   │   │       │   │       └── Widget
│   │   │   │       │   ├── _files
│   │   │   │       │   │   └── design
│   │   │   │       │   │       └── adminhtml
│   │   │   │       │   │           └── magento_basic
│   │   │   │       │   │               └── Magento_Catalog
│   │   │   │       │   │                   └── web
│   │   │   │       │   │                       └── images
│   │   │   │       │   ├── Model
│   │   │   │       │   │   ├── Config
│   │   │   │       │   │   │   └── _files
│   │   │   │       │   │   ├── Layout
│   │   │   │       │   │   ├── ResourceModel
│   │   │   │       │   │   │   └── Layout
│   │   │   │       │   │   ├── Template
│   │   │   │       │   │   └── Widget
│   │   │   │       │   └── Setup
│   │   │   │       └── Wishlist
│   │   │   │           ├── Block
│   │   │   │           │   ├── Customer
│   │   │   │           │   │   └── Wishlist
│   │   │   │           │   │       └── Item
│   │   │   │           │   └── Share
│   │   │   │           ├── Controller
│   │   │   │           ├── _files
│   │   │   │           ├── Helper
│   │   │   │           └── Model
│   │   │   │               └── ResourceModel
│   │   │   │                   └── Item
│   │   │   └── tmp
│   │   ├── js
│   │   │   └── jasmine
│   │   │       ├── assets
│   │   │       │   ├── apply
│   │   │       │   │   ├── components
│   │   │       │   │   └── templates
│   │   │       │   ├── gallery
│   │   │       │   ├── jsbuild
│   │   │       │   ├── lib
│   │   │       │   │   └── web
│   │   │       │   │       └── mage
│   │   │       │   ├── script
│   │   │       │   │   └── templates
│   │   │       │   └── text
│   │   │       ├── spec_runner
│   │   │       │   └── tasks
│   │   │       └── tests
│   │   │           ├── app
│   │   │           │   └── code
│   │   │           │       └── Magento
│   │   │           │           ├── Backend
│   │   │           │           │   └── view
│   │   │           │           │       └── adminhtml
│   │   │           │           │           └── web
│   │   │           │           │               └── js
│   │   │           │           ├── Braintree
│   │   │           │           │   └── frontend
│   │   │           │           │       └── js
│   │   │           │           │           ├── paypal
│   │   │           │           │           └── view
│   │   │           │           │               └── payment
│   │   │           │           │                   └── method-renderer
│   │   │           │           ├── Bundle
│   │   │           │           │   └── adminhtml
│   │   │           │           │       └── js
│   │   │           │           │           └── components
│   │   │           │           ├── Catalog
│   │   │           │           │   ├── adminhtml
│   │   │           │           │   │   └── js
│   │   │           │           │   │       ├── components
│   │   │           │           │   │       ├── disable-on-option
│   │   │           │           │   │       ├── use-parent-settings
│   │   │           │           │   │       └── utils
│   │   │           │           │   ├── base
│   │   │           │           │   │   └── js
│   │   │           │           │   │       └── product
│   │   │           │           │   │           └── list
│   │   │           │           │   │               └── columns
│   │   │           │           │   └── frontend
│   │   │           │           │       └── js
│   │   │           │           │           └── product
│   │   │           │           │               ├── storage
│   │   │           │           │               └── view
│   │   │           │           ├── Checkout
│   │   │           │           │   ├── base
│   │   │           │           │   │   └── web
│   │   │           │           │   │       └── js
│   │   │           │           │   │           └── model
│   │   │           │           │   └── frontend
│   │   │           │           │       └── js
│   │   │           │           │           ├── action
│   │   │           │           │           ├── model
│   │   │           │           │           │   └── cart
│   │   │           │           │           │       └── totals-processor
│   │   │           │           │           └── view
│   │   │           │           │               ├── cart
│   │   │           │           │               └── summary
│   │   │           │           ├── CheckoutAgreements
│   │   │           │           │   └── frontend
│   │   │           │           │       └── js
│   │   │           │           │           └── model
│   │   │           │           ├── ConfigurableProduct
│   │   │           │           │   └── view
│   │   │           │           │       └── adminhtml
│   │   │           │           │           └── web
│   │   │           │           │               └── js
│   │   │           │           │                   └── variations
│   │   │           │           ├── Customer
│   │   │           │           │   ├── adminhtml
│   │   │           │           │   │   └── js
│   │   │           │           │   │       └── view
│   │   │           │           │   │           └── form
│   │   │           │           │   │               └── components
│   │   │           │           │   └── frontend
│   │   │           │           │       └── js
│   │   │           │           │           ├── model
│   │   │           │           │           │   └── customer
│   │   │           │           │           └── view
│   │   │           │           ├── InstantPurchase
│   │   │           │           │   └── frontend
│   │   │           │           │       └── web
│   │   │           │           │           └── js
│   │   │           │           │               └── view
│   │   │           │           ├── Msrp
│   │   │           │           │   └── frontend
│   │   │           │           │       └── js
│   │   │           │           ├── PageCache
│   │   │           │           │   └── frontend
│   │   │           │           │       └── js
│   │   │           │           ├── Payment
│   │   │           │           │   └── base
│   │   │           │           │       └── js
│   │   │           │           │           └── model
│   │   │           │           │               └── credit-card-validation
│   │   │           │           ├── Paypal
│   │   │           │           │   └── frontend
│   │   │           │           │       └── js
│   │   │           │           │           ├── in-context
│   │   │           │           │           └── view
│   │   │           │           │               └── payment
│   │   │           │           │                   └── method-renderer
│   │   │           │           │                       └── in-context
│   │   │           │           ├── Review
│   │   │           │           │   └── view
│   │   │           │           │       ├── base
│   │   │           │           │       │   └── web
│   │   │           │           │       │       ├── js
│   │   │           │           │       │       │   └── product
│   │   │           │           │       │       └── template
│   │   │           │           │       │           └── product
│   │   │           │           │       └── frontend
│   │   │           │           │           └── web
│   │   │           │           │               └── js
│   │   │           │           ├── Rule
│   │   │           │           │   └── view
│   │   │           │           │       └── adminhtml
│   │   │           │           │           └── web
│   │   │           │           ├── Signifyd
│   │   │           │           │   └── frontend
│   │   │           │           │       └── js
│   │   │           │           ├── Tax
│   │   │           │           │   └── view
│   │   │           │           │       └── frontend
│   │   │           │           │           └── web
│   │   │           │           │               └── js
│   │   │           │           │                   └── view
│   │   │           │           │                       └── checkout
│   │   │           │           │                           └── summary
│   │   │           │           ├── Theme
│   │   │           │           │   └── view
│   │   │           │           │       └── frontend
│   │   │           │           │           └── web
│   │   │           │           │               └── js
│   │   │           │           │                   └── view
│   │   │           │           ├── Ui
│   │   │           │           │   ├── adminhtml
│   │   │           │           │   │   └── js
│   │   │           │           │   │       └── form
│   │   │           │           │   └── base
│   │   │           │           │       └── js
│   │   │           │           │           ├── core
│   │   │           │           │           ├── dynamic-rows
│   │   │           │           │           ├── form
│   │   │           │           │           │   ├── components
│   │   │           │           │           │   │   └── collection
│   │   │           │           │           │   └── element
│   │   │           │           │           ├── grid
│   │   │           │           │           │   ├── columns
│   │   │           │           │           │   ├── controls
│   │   │           │           │           │   │   └── bookmarks
│   │   │           │           │           │   ├── editing
│   │   │           │           │           │   ├── filters
│   │   │           │           │           │   ├── paging
│   │   │           │           │           │   ├── search
│   │   │           │           │           │   └── sticky
│   │   │           │           │           ├── lib
│   │   │           │           │           │   ├── component
│   │   │           │           │           │   ├── ko
│   │   │           │           │           │   │   └── bind
│   │   │           │           │           │   ├── logger
│   │   │           │           │           │   ├── registry
│   │   │           │           │           │   └── validation
│   │   │           │           │           ├── modal
│   │   │           │           │           └── timeline
│   │   │           │           └── Wishlist
│   │   │           │               └── view
│   │   │           │                   └── frontend
│   │   │           │                       └── web
│   │   │           │                           └── js
│   │   │           └── lib
│   │   │               └── mage
│   │   │                   ├── backend
│   │   │                   └── requirejs
│   │   ├── setup-integration
│   │   │   ├── etc
│   │   │   ├── _files
│   │   │   │   └── Magento
│   │   │   │       ├── TestSetupDeclarationModule1
│   │   │   │       │   ├── etc
│   │   │   │       │   ├── fixture
│   │   │   │       │   │   └── declarative_installer
│   │   │   │       │   ├── revisions
│   │   │   │       │   │   ├── after_rollback
│   │   │   │       │   │   ├── base_update
│   │   │   │       │   │   ├── before_rollback
│   │   │   │       │   │   ├── column_modifications
│   │   │   │       │   │   ├── column_removals
│   │   │   │       │   │   ├── constraint_modifications
│   │   │   │       │   │   ├── drop_table
│   │   │   │       │   │   ├── fail_on_column_declaration
│   │   │   │       │   │   ├── fail_on_unique_key_declaration
│   │   │   │       │   │   ├── foreign_key_interpreter
│   │   │   │       │   │   ├── index_to_disable
│   │   │   │       │   │   ├── old_diff
│   │   │   │       │   │   ├── old_diff_before
│   │   │   │       │   │   ├── table_rename
│   │   │   │       │   │   ├── table_rename_after
│   │   │   │       │   │   ├── whitelist_upgrade
│   │   │   │       │   │   └── without_setup_version
│   │   │   │       │   └── Setup
│   │   │   │       ├── TestSetupDeclarationModule3
│   │   │   │       │   ├── etc
│   │   │   │       │   ├── revisions
│   │   │   │       │   │   ├── all_patches_revision
│   │   │   │       │   │   ├── cyclomatic_and_bic_revision
│   │   │   │       │   │   ├── drop_table_with_external_dependency
│   │   │   │       │   │   ├── first_patch_revision
│   │   │   │       │   │   ├── old_revision
│   │   │   │       │   │   ├── patches_revision
│   │   │   │       │   │   └── without_setup_version
│   │   │   │       │   └── Setup
│   │   │   │       ├── TestSetupDeclarationModule4
│   │   │   │       │   ├── etc
│   │   │   │       │   ├── fixture
│   │   │   │       │   └── revisions
│   │   │   │       │       ├── remove_title_column
│   │   │   │       │       └── restore_title_column
│   │   │   │       ├── TestSetupDeclarationModule5
│   │   │   │       │   ├── etc
│   │   │   │       │   └── revisions
│   │   │   │       │       ├── module-without-version
│   │   │   │       │       ├── old-scripts
│   │   │   │       │       └── patches
│   │   │   │       ├── TestSetupDeclarationModule6
│   │   │   │       │   └── etc
│   │   │   │       ├── TestSetupDeclarationModule7
│   │   │   │       │   ├── etc
│   │   │   │       │   ├── revisions
│   │   │   │       │   │   ├── swap_with_declaration
│   │   │   │       │   │   ├── us_to_us
│   │   │   │       │   │   └── wl_remove_table
│   │   │   │       │   └── Setup
│   │   │   │       ├── TestSetupDeclarationModule8
│   │   │   │       │   ├── etc
│   │   │   │       │   └── revisions
│   │   │   │       │       ├── disable_index_by_external_module
│   │   │   │       │       ├── disabling_tables
│   │   │   │       │       ├── incosistence_reference_definition
│   │   │   │       │       ├── invalid_auto_increment
│   │   │   │       │       ├── invalid_primary_key
│   │   │   │       │       ├── setup_install_with_converting
│   │   │   │       │       ├── unpatterned_fk_name
│   │   │   │       │       └── whitelist_upgrade
│   │   │   │       └── TestSetupDeclarationModule9
│   │   │   │           ├── etc
│   │   │   │           ├── fixture
│   │   │   │           │   └── declarative_installer
│   │   │   │           └── revisions
│   │   │   │               ├── disabling_tables
│   │   │   │               └── setup_install_with_converting
│   │   │   ├── framework
│   │   │   │   ├── Magento
│   │   │   │   │   └── TestFramework
│   │   │   │   │       ├── Annotation
│   │   │   │   │       ├── Bootstrap
│   │   │   │   │       ├── Deploy
│   │   │   │   │       ├── TestCase
│   │   │   │   │       └── Workaround
│   │   │   │   └── tests
│   │   │   │       └── unit
│   │   │   │           ├── framework
│   │   │   │           └── testsuite
│   │   │   │               └── Magento
│   │   │   │                   └── TestFramework
│   │   │   │                       └── Test
│   │   │   │                           └── Unit
│   │   │   │                               └── Annotation
│   │   │   └── testsuite
│   │   │       └── Magento
│   │   │           ├── Developer
│   │   │           │   ├── Console
│   │   │           │   │   └── Command
│   │   │           │   └── _files
│   │   │           │       ├── SetupInstall
│   │   │           │       │   ├── TestSetupDeclarationModule8
│   │   │           │       │   └── TestSetupDeclarationModule9
│   │   │           │       ├── SetupUpgrade
│   │   │           │       │   ├── TestSetupDeclarationModule8
│   │   │           │       │   └── TestSetupDeclarationModule9
│   │   │           │       └── WhitelistGenerate
│   │   │           │           ├── TestSetupDeclarationModule1
│   │   │           │           └── TestSetupDeclarationModule8
│   │   │           └── Setup
│   │   ├── static
│   │   │   ├── framework
│   │   │   │   ├── Magento
│   │   │   │   │   ├── CodeMessDetector
│   │   │   │   │   │   ├── resources
│   │   │   │   │   │   │   └── rulesets
│   │   │   │   │   │   ├── Rule
│   │   │   │   │   │   │   └── Design
│   │   │   │   │   │   └── Test
│   │   │   │   │   │       └── Unit
│   │   │   │   │   │           └── Rule
│   │   │   │   │   │               └── Design
│   │   │   │   │   ├── Sniffs
│   │   │   │   │   │   ├── Annotation
│   │   │   │   │   │   └── Less
│   │   │   │   │   └── TestFramework
│   │   │   │   │       ├── CodingStandard
│   │   │   │   │       │   └── Tool
│   │   │   │   │       │       └── CodeSniffer
│   │   │   │   │       ├── Dependency
│   │   │   │   │       │   └── VirtualType
│   │   │   │   │       ├── Inspection
│   │   │   │   │       ├── Integrity
│   │   │   │   │       │   └── Library
│   │   │   │   │       │       └── PhpParser
│   │   │   │   │       └── Utility
│   │   │   │   │           └── File
│   │   │   │   └── tests
│   │   │   │       └── unit
│   │   │   │           └── testsuite
│   │   │   │               └── Magento
│   │   │   │                   ├── Sniffs
│   │   │   │                   │   ├── Annotation
│   │   │   │                   │   │   └── _files
│   │   │   │                   │   └── Less
│   │   │   │                   │       └── _files
│   │   │   │                   ├── Test
│   │   │   │                   │   ├── Integrity
│   │   │   │                   │   │   └── Library
│   │   │   │                   │   │       └── PhpParser
│   │   │   │                   │   └── Utility
│   │   │   │                   │       └── File
│   │   │   │                   │           └── _files
│   │   │   │                   └── TestFramework
│   │   │   │                       ├── CodingStandard
│   │   │   │                       │   └── Tool
│   │   │   │                       │       └── CodeSniffer
│   │   │   │                       ├── Dependency
│   │   │   │                       │   ├── _files
│   │   │   │                       │   └── VirtualType
│   │   │   │                       │       └── _files
│   │   │   │                       │           └── etc
│   │   │   │                       │               └── adminhtml
│   │   │   │                       ├── Inspection
│   │   │   │                       │   └── _files
│   │   │   │                       │       └── words_finder
│   │   │   │                       │           └── twilight
│   │   │   │                       └── Utility
│   │   │   │                           ├── _files
│   │   │   │                           └── PartialNamespace
│   │   │   ├── testsuite
│   │   │   │   └── Magento
│   │   │   │       └── Test
│   │   │   │           ├── _files
│   │   │   │           ├── Integrity
│   │   │   │           │   ├── App
│   │   │   │           │   │   └── Language
│   │   │   │           │   │       └── _files
│   │   │   │           │   ├── Dependency
│   │   │   │           │   ├── Di
│   │   │   │           │   ├── _files
│   │   │   │           │   │   ├── blacklist
│   │   │   │           │   │   └── dependency_test
│   │   │   │           │   ├── Layout
│   │   │   │           │   ├── Library
│   │   │   │           │   │   └── _files
│   │   │   │           │   ├── Magento
│   │   │   │           │   │   ├── Backend
│   │   │   │           │   │   │   └── _files
│   │   │   │           │   │   ├── Core
│   │   │   │           │   │   │   └── Model
│   │   │   │           │   │   │       └── Fieldset
│   │   │   │           │   │   │           └── _files
│   │   │   │           │   │   ├── Framework
│   │   │   │           │   │   │   ├── Api
│   │   │   │           │   │   │   │   └── _files
│   │   │   │           │   │   │   │       └── ExtensibleInterfacesTest
│   │   │   │           │   │   │   └── Search
│   │   │   │           │   │   │       └── _files
│   │   │   │           │   │   │           ├── request
│   │   │   │           │   │   │           └── search_engine
│   │   │   │           │   │   ├── Indexer
│   │   │   │           │   │   │   └── _files
│   │   │   │           │   │   ├── Payment
│   │   │   │           │   │   │   ├── Config
│   │   │   │           │   │   │   └── Model
│   │   │   │           │   │   │       └── _files
│   │   │   │           │   │   ├── Persistent
│   │   │   │           │   │   │   └── _files
│   │   │   │           │   │   ├── Webapi
│   │   │   │           │   │   │   └── Model
│   │   │   │           │   │   │       └── _files
│   │   │   │           │   │   └── Widget
│   │   │   │           │   │       └── _files
│   │   │   │           │   ├── Phrase
│   │   │   │           │   │   └── Legacy
│   │   │   │           │   ├── Readme
│   │   │   │           │   │   └── _files
│   │   │   │           │   │       └── blacklist
│   │   │   │           │   └── Xml
│   │   │   │           ├── Js
│   │   │   │           │   └── _files
│   │   │   │           │       ├── blacklist
│   │   │   │           │       ├── eslint
│   │   │   │           │       ├── jscs
│   │   │   │           │       └── whitelist
│   │   │   │           ├── Legacy
│   │   │   │           │   ├── _files
│   │   │   │           │   │   ├── blacklist
│   │   │   │           │   │   ├── connection
│   │   │   │           │   │   │   ├── blacklist
│   │   │   │           │   │   │   └── whitelist
│   │   │   │           │   │   ├── copyright
│   │   │   │           │   │   ├── response
│   │   │   │           │   │   │   ├── blacklist
│   │   │   │           │   │   │   └── whitelist
│   │   │   │           │   │   └── security
│   │   │   │           │   └── Magento
│   │   │   │           │       ├── Core
│   │   │   │           │       │   └── Block
│   │   │   │           │       ├── Framework
│   │   │   │           │       │   ├── Module
│   │   │   │           │       │   └── ObjectManager
│   │   │   │           │       └── Widget
│   │   │   │           ├── Less
│   │   │   │           │   └── _files
│   │   │   │           │       ├── blacklist
│   │   │   │           │       ├── lesscs
│   │   │   │           │       └── whitelist
│   │   │   │           ├── Php
│   │   │   │           │   └── _files
│   │   │   │           │       ├── blacklist
│   │   │   │           │       ├── phpcpd
│   │   │   │           │       │   └── blacklist
│   │   │   │           │       ├── phpmd
│   │   │   │           │       └── whitelist
│   │   │   │           │           └── exempt_modules
│   │   │   │           └── Tools
│   │   │   │               └── Composer
│   │   │   └── tmp
│   │   └── unit
│   │       ├── framework
│   │       └── tmp
│   ├── tools
│   │   ├── grunt
│   │   │   ├── assets
│   │   │   │   └── legacy-build
│   │   │   ├── configs
│   │   │   ├── tasks
│   │   │   └── tools
│   │   └── UpgradeScripts
│   └── travis
│       └── config
├── generated
├── lib
│   ├── internal
│   │   ├── GnuFreeFont
│   │   ├── LinLibertineFont
│   │   └── Magento
│   │       └── Framework
│   │           ├── Acl
│   │           │   ├── AclResource
│   │           │   │   └── Config
│   │           │   │       ├── Converter
│   │           │   │       └── Reader
│   │           │   ├── Data
│   │           │   ├── etc
│   │           │   ├── Loader
│   │           │   ├── Role
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           ├── AclResource
│   │           │           │   └── Config
│   │           │           │       ├── Converter
│   │           │           │       │   └── _files
│   │           │           │       └── _files
│   │           │           ├── _files
│   │           │           ├── Loader
│   │           │           └── Role
│   │           ├── Amqp
│   │           │   ├── Bulk
│   │           │   ├── Connection
│   │           │   ├── Test
│   │           │   │   └── Unit
│   │           │   │       ├── Bulk
│   │           │   │       ├── Connection
│   │           │   │       └── Topology
│   │           │   │           └── BindingInstallerType
│   │           │   └── Topology
│   │           │       └── BindingInstallerType
│   │           ├── Api
│   │           │   ├── Code
│   │           │   │   └── Generator
│   │           │   ├── Data
│   │           │   ├── etc
│   │           │   ├── ExtensionAttribute
│   │           │   │   └── Config
│   │           │   ├── Search
│   │           │   ├── SearchCriteria
│   │           │   │   └── CollectionProcessor
│   │           │   │       ├── ConditionProcessor
│   │           │   │       ├── FilterProcessor
│   │           │   │       └── JoinProcessor
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           ├── Api
│   │           │           │   └── _files
│   │           │           ├── Code
│   │           │           │   └── Generator
│   │           │           │       └── _files
│   │           │           ├── Data
│   │           │           ├── ExtensionAttribute
│   │           │           │   └── Config
│   │           │           │       └── _files
│   │           │           ├── Search
│   │           │           └── SearchCriteria
│   │           │               └── CollectionProcessor
│   │           │                   └── ConditionProcessor
│   │           ├── App
│   │           │   ├── Action
│   │           │   │   └── Plugin
│   │           │   ├── Area
│   │           │   ├── AreaList
│   │           │   ├── Arguments
│   │           │   │   └── FileResolver
│   │           │   ├── Cache
│   │           │   │   ├── Frontend
│   │           │   │   ├── Tag
│   │           │   │   │   └── Strategy
│   │           │   │   └── Type
│   │           │   ├── Config
│   │           │   │   ├── ConfigResource
│   │           │   │   ├── Data
│   │           │   │   ├── Initial
│   │           │   │   ├── Reader
│   │           │   │   │   └── Source
│   │           │   │   ├── Scope
│   │           │   │   ├── Spi
│   │           │   │   └── Storage
│   │           │   ├── Console
│   │           │   ├── DefaultPath
│   │           │   ├── DeploymentConfig
│   │           │   │   └── Writer
│   │           │   ├── etc
│   │           │   ├── Filesystem
│   │           │   ├── Helper
│   │           │   ├── Http
│   │           │   ├── Interception
│   │           │   │   └── Cache
│   │           │   ├── Language
│   │           │   ├── ObjectManager
│   │           │   │   ├── ConfigLoader
│   │           │   │   ├── ConfigWriter
│   │           │   │   └── Environment
│   │           │   ├── PageCache
│   │           │   ├── Request
│   │           │   ├── ResourceConnection
│   │           │   │   └── Config
│   │           │   ├── Response
│   │           │   │   ├── HeaderProvider
│   │           │   │   └── Http
│   │           │   ├── Route
│   │           │   │   ├── Config
│   │           │   │   └── ConfigInterface
│   │           │   ├── Router
│   │           │   ├── Rss
│   │           │   ├── Scope
│   │           │   ├── State
│   │           │   ├── Test
│   │           │   │   └── Unit
│   │           │   │       ├── Action
│   │           │   │       │   ├── Plugin
│   │           │   │       │   └── Stub
│   │           │   │       ├── Arguments
│   │           │   │       │   └── FileResolver
│   │           │   │       │       └── _files
│   │           │   │       │           ├── app
│   │           │   │       │           │   └── etc
│   │           │   │       │           │       └── custom
│   │           │   │       │           └── primary
│   │           │   │       │               └── app
│   │           │   │       │                   └── etc
│   │           │   │       │                       └── some_config
│   │           │   │       ├── Cache
│   │           │   │       │   ├── Frontend
│   │           │   │       │   │   └── FactoryTest
│   │           │   │       │   ├── Tag
│   │           │   │       │   │   └── Strategy
│   │           │   │       │   └── Type
│   │           │   │       ├── Config
│   │           │   │       │   ├── Data
│   │           │   │       │   ├── _files
│   │           │   │       │   ├── Initial
│   │           │   │       │   │   └── _files
│   │           │   │       │   ├── Scope
│   │           │   │       │   └── Storage
│   │           │   │       ├── Console
│   │           │   │       ├── DefaultPath
│   │           │   │       ├── DeploymentConfig
│   │           │   │       │   ├── _files
│   │           │   │       │   └── Writer
│   │           │   │       ├── _files
│   │           │   │       │   ├── app
│   │           │   │       │   │   └── etc
│   │           │   │       │   ├── other
│   │           │   │       │   ├── pub
│   │           │   │       │   └── setup
│   │           │   │       ├── Filesystem
│   │           │   │       ├── Http
│   │           │   │       ├── Language
│   │           │   │       │   └── _files
│   │           │   │       ├── ObjectManager
│   │           │   │       │   └── Environment
│   │           │   │       ├── PageCache
│   │           │   │       ├── Request
│   │           │   │       ├── ResourceConnection
│   │           │   │       │   └── Config
│   │           │   │       │       └── _files
│   │           │   │       ├── Response
│   │           │   │       │   ├── HeaderProvider
│   │           │   │       │   └── Http
│   │           │   │       ├── Route
│   │           │   │       │   ├── Config
│   │           │   │       │   │   └── _files
│   │           │   │       │   └── ConfigInterface
│   │           │   │       ├── Router
│   │           │   │       ├── Scope
│   │           │   │       ├── State
│   │           │   │       ├── Utility
│   │           │   │       │   └── _files
│   │           │   │       │       └── foo
│   │           │   │       │           ├── bar
│   │           │   │       │           │   └── recursive
│   │           │   │       │           └── baz
│   │           │   │       └── View
│   │           │   │           ├── Asset
│   │           │   │           │   └── MaterializationStrategy
│   │           │   │           └── Deployment
│   │           │   │               └── Version
│   │           │   │                   └── Storage
│   │           │   ├── Utility
│   │           │   └── View
│   │           │       ├── Asset
│   │           │       │   └── MaterializationStrategy
│   │           │       └── Deployment
│   │           │           └── Version
│   │           │               └── Storage
│   │           ├── Archive
│   │           │   ├── Helper
│   │           │   │   └── File
│   │           │   └── Test
│   │           │       └── Unit
│   │           ├── Authorization
│   │           │   ├── Policy
│   │           │   ├── RoleLocator
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           └── Policy
│   │           ├── Autoload
│   │           │   └── Test
│   │           │       └── Unit
│   │           ├── Backup
│   │           │   ├── Archive
│   │           │   ├── Db
│   │           │   ├── Exception
│   │           │   ├── Filesystem
│   │           │   │   ├── Iterator
│   │           │   │   └── Rollback
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           ├── _files
│   │           │           └── Filesystem
│   │           │               └── Rollback
│   │           │                   └── _files
│   │           ├── Bulk
│   │           ├── Cache
│   │           │   ├── Backend
│   │           │   │   └── Decorator
│   │           │   ├── Config
│   │           │   ├── etc
│   │           │   ├── Frontend
│   │           │   │   ├── Adapter
│   │           │   │   └── Decorator
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           ├── Backend
│   │           │           │   ├── Decorator
│   │           │           │   └── _files
│   │           │           ├── Config
│   │           │           │   └── _files
│   │           │           └── Frontend
│   │           │               ├── Adapter
│   │           │               └── Decorator
│   │           ├── Code
│   │           │   ├── Generator
│   │           │   ├── Minifier
│   │           │   │   └── Adapter
│   │           │   │       ├── Css
│   │           │   │       └── Js
│   │           │   ├── Reader
│   │           │   ├── Test
│   │           │   │   └── Unit
│   │           │   │       ├── _files
│   │           │   │       │   └── app
│   │           │   │       │       └── code
│   │           │   │       │           └── Magento
│   │           │   │       │               └── SomeModule
│   │           │   │       │                   └── Model
│   │           │   │       │                       ├── Five
│   │           │   │       │                       ├── Four
│   │           │   │       │                       ├── One
│   │           │   │       │                       ├── Six
│   │           │   │       │                       ├── Three
│   │           │   │       │                       └── Two
│   │           │   │       ├── Generator
│   │           │   │       │   └── TestAsset
│   │           │   │       ├── Minifier
│   │           │   │       │   ├── Adapter
│   │           │   │       │   │   ├── Css
│   │           │   │       │   │   └── Js
│   │           │   │       │   └── _files
│   │           │   │       │       └── js
│   │           │   │       ├── Model
│   │           │   │       │   └── File
│   │           │   │       │       └── Validator
│   │           │   │       ├── Reader
│   │           │   │       │   └── _files
│   │           │   │       └── Validator
│   │           │   │           └── _files
│   │           │   └── Validator
│   │           ├── Communication
│   │           │   ├── Config
│   │           │   │   └── Reader
│   │           │   │       ├── EnvReader
│   │           │   │       └── XmlReader
│   │           │   └── etc
│   │           ├── Component
│   │           │   └── Test
│   │           │       └── Unit
│   │           ├── Composer
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           └── _files
│   │           ├── Config
│   │           │   ├── Composer
│   │           │   ├── Converter
│   │           │   │   └── Dom
│   │           │   ├── Data
│   │           │   ├── Dom
│   │           │   ├── etc
│   │           │   ├── File
│   │           │   ├── Reader
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           ├── Composer
│   │           │           ├── Converter
│   │           │           │   └── Dom
│   │           │           ├── Data
│   │           │           ├── Dom
│   │           │           ├── File
│   │           │           ├── _files
│   │           │           │   ├── area
│   │           │           │   │   ├── default_default
│   │           │           │   │   ├── default_test
│   │           │           │   │   ├── default_test2
│   │           │           │   │   ├── test_default
│   │           │           │   │   └── test_external_package_descendant
│   │           │           │   ├── converter
│   │           │           │   │   └── dom
│   │           │           │   │       └── flat
│   │           │           │   ├── dom
│   │           │           │   │   └── converter
│   │           │           │   └── reader
│   │           │           └── Reader
│   │           ├── Console
│   │           │   ├── Exception
│   │           │   ├── QuestionPerformer
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           ├── Exception
│   │           │           └── QuestionPerformer
│   │           ├── Controller
│   │           │   ├── Index
│   │           │   ├── Noroute
│   │           │   ├── Result
│   │           │   ├── Router
│   │           │   │   └── Route
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           ├── Controller
│   │           │           │   └── Index
│   │           │           ├── Result
│   │           │           └── Router
│   │           │               └── Route
│   │           ├── Convert
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           └── _files
│   │           ├── Crontab
│   │           │   └── Test
│   │           │       └── Unit
│   │           ├── Css
│   │           │   ├── PreProcessor
│   │           │   │   ├── Adapter
│   │           │   │   │   └── Less
│   │           │   │   ├── File
│   │           │   │   │   ├── Collector
│   │           │   │   │   └── FileList
│   │           │   │   ├── FileGenerator
│   │           │   │   └── Instruction
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           └── PreProcessor
│   │           │               ├── Adapter
│   │           │               │   └── Less
│   │           │               │       └── _file
│   │           │               ├── File
│   │           │               │   ├── Collector
│   │           │               │   └── FileList
│   │           │               ├── _files
│   │           │               └── Instruction
│   │           ├── Data
│   │           │   ├── Argument
│   │           │   │   └── Interpreter
│   │           │   ├── Collection
│   │           │   │   └── Db
│   │           │   │       └── FetchStrategy
│   │           │   ├── etc
│   │           │   │   └── argument
│   │           │   ├── Form
│   │           │   │   ├── Element
│   │           │   │   │   └── Renderer
│   │           │   │   ├── Filter
│   │           │   │   └── FormKey
│   │           │   ├── Helper
│   │           │   ├── Test
│   │           │   │   └── Unit
│   │           │   │       ├── Argument
│   │           │   │       │   ├── _files
│   │           │   │       │   └── Interpreter
│   │           │   │       ├── Collection
│   │           │   │       │   └── Db
│   │           │   │       │       └── FetchStrategy
│   │           │   │       ├── Criteria
│   │           │   │       ├── Form
│   │           │   │       │   ├── Element
│   │           │   │       │   └── FormKey
│   │           │   │       ├── Helper
│   │           │   │       ├── Stub
│   │           │   │       └── Tree
│   │           │   │           └── Node
│   │           │   ├── Tree
│   │           │   │   └── Node
│   │           │   └── Wysiwyg
│   │           ├── DataObject
│   │           │   ├── Copy
│   │           │   │   └── Config
│   │           │   │       └── Data
│   │           │   ├── etc
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           └── Copy
│   │           │               └── Config
│   │           │                   └── _files
│   │           ├── DB
│   │           │   ├── Adapter
│   │           │   │   └── Pdo
│   │           │   ├── DataConverter
│   │           │   ├── Ddl
│   │           │   ├── Helper
│   │           │   │   └── Mysql
│   │           │   ├── Logger
│   │           │   ├── Platform
│   │           │   ├── Query
│   │           │   ├── Select
│   │           │   ├── Sequence
│   │           │   ├── Sql
│   │           │   ├── Statement
│   │           │   │   └── Pdo
│   │           │   ├── Test
│   │           │   │   └── Unit
│   │           │   │       ├── Adapter
│   │           │   │       │   └── Pdo
│   │           │   │       ├── DataConverter
│   │           │   │       ├── DB
│   │           │   │       │   ├── Logger
│   │           │   │       │   └── Statement
│   │           │   │       ├── Ddl
│   │           │   │       ├── Helper
│   │           │   │       │   └── Mysql
│   │           │   │       ├── Logger
│   │           │   │       ├── Platform
│   │           │   │       ├── Select
│   │           │   │       └── Sql
│   │           │   └── Tree
│   │           ├── DomDocument
│   │           ├── Encryption
│   │           │   ├── Adapter
│   │           │   ├── Helper
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           ├── Adapter
│   │           │           ├── Crypt
│   │           │           │   └── _files
│   │           │           └── Helper
│   │           ├── EntityManager
│   │           │   ├── Db
│   │           │   ├── Observer
│   │           │   ├── Operation
│   │           │   │   ├── Create
│   │           │   │   ├── Delete
│   │           │   │   ├── Read
│   │           │   │   └── Update
│   │           │   ├── Sequence
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           ├── Db
│   │           │           ├── Operation
│   │           │           └── Sequence
│   │           ├── Event
│   │           │   ├── Config
│   │           │   ├── etc
│   │           │   ├── Invoker
│   │           │   ├── Observer
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           ├── Config
│   │           │           │   └── _files
│   │           │           ├── Invoker
│   │           │           └── Observer
│   │           ├── Exception
│   │           │   ├── Plugin
│   │           │   ├── State
│   │           │   ├── TemporaryState
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           └── State
│   │           ├── File
│   │           │   ├── Test
│   │           │   │   └── Unit
│   │           │   │       ├── _files
│   │           │   │       └── Transfer
│   │           │   │           └── Adapter
│   │           │   └── Transfer
│   │           │       └── Adapter
│   │           ├── Filesystem
│   │           │   ├── Directory
│   │           │   ├── Driver
│   │           │   ├── File
│   │           │   ├── Filter
│   │           │   ├── Io
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           ├── Directory
│   │           │           ├── Driver
│   │           │           ├── File
│   │           │           └── _files
│   │           ├── Filter
│   │           │   ├── DataObject
│   │           │   ├── Encrypt
│   │           │   ├── FilterManager
│   │           │   ├── Input
│   │           │   ├── Template
│   │           │   │   └── Tokenizer
│   │           │   ├── Test
│   │           │   │   └── Unit
│   │           │   │       ├── DataObject
│   │           │   │       ├── FilterManager
│   │           │   │       ├── Input
│   │           │   │       └── Template
│   │           │   │           └── Tokenizer
│   │           │   └── TruncateFilter
│   │           ├── Flag
│   │           ├── GraphQl
│   │           │   ├── Config
│   │           │   │   ├── Data
│   │           │   │   └── Element
│   │           │   ├── Exception
│   │           │   ├── Query
│   │           │   │   └── Resolver
│   │           │   │       └── Argument
│   │           │   │           ├── Filter
│   │           │   │           └── SearchCriteria
│   │           │   │               └── ArgumentApplier
│   │           │   └── Schema
│   │           │       └── Type
│   │           │           ├── Entity
│   │           │           ├── Enum
│   │           │           ├── Input
│   │           │           └── Output
│   │           │               └── ElementMapper
│   │           │                   └── Formatter
│   │           ├── GraphQlSchemaStitching
│   │           │   ├── Common
│   │           │   └── GraphQlReader
│   │           │       ├── MetaReader
│   │           │       └── Reader
│   │           ├── HTTP
│   │           │   ├── Adapter
│   │           │   ├── Client
│   │           │   ├── PhpEnvironment
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           ├── Adapter
│   │           │           │   └── _files
│   │           │           └── PhpEnvironment
│   │           ├── Image
│   │           │   ├── Adapter
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           └── Adapter
│   │           │               └── _files
│   │           ├── Indexer
│   │           │   ├── Action
│   │           │   ├── Config
│   │           │   ├── etc
│   │           │   ├── Handler
│   │           │   ├── SaveHandler
│   │           │   ├── ScopeResolver
│   │           │   ├── Table
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           ├── Config
│   │           │           ├── _files
│   │           │           ├── Handler
│   │           │           └── ScopeResolver
│   │           ├── Interception
│   │           │   ├── Code
│   │           │   │   └── Generator
│   │           │   ├── Config
│   │           │   ├── Definition
│   │           │   ├── ObjectManager
│   │           │   │   └── Config
│   │           │   ├── PluginList
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           ├── Code
│   │           │           │   └── Generator
│   │           │           │       └── _files
│   │           │           ├── Config
│   │           │           ├── Custom
│   │           │           │   └── Module
│   │           │           │       └── Model
│   │           │           │           ├── InterfaceValidator
│   │           │           │           │   └── ItemPlugin
│   │           │           │           ├── Item
│   │           │           │           ├── ItemContainer
│   │           │           │           ├── ItemContainerPlugin
│   │           │           │           ├── ItemPlugin
│   │           │           │           └── StartingBackslash
│   │           │           ├── _files
│   │           │           ├── ObjectManager
│   │           │           │   └── Config
│   │           │           └── PluginList
│   │           ├── Intl
│   │           ├── Json
│   │           │   ├── Helper
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           └── Helper
│   │           ├── Locale
│   │           │   ├── Bundle
│   │           │   ├── Deployed
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           └── Deployed
│   │           ├── Lock
│   │           │   ├── Backend
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           └── Backend
│   │           ├── Logger
│   │           │   ├── Handler
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           └── Handler
│   │           ├── Mail
│   │           │   ├── Template
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           └── Template
│   │           ├── Math
│   │           │   └── Test
│   │           │       └── Unit
│   │           ├── Message
│   │           │   └── Test
│   │           │       └── Unit
│   │           ├── MessageQueue
│   │           │   ├── Bulk
│   │           │   │   └── Rpc
│   │           │   ├── Code
│   │           │   │   └── Generator
│   │           │   │       └── Config
│   │           │   │           └── RemoteServiceReader
│   │           │   ├── Config
│   │           │   │   ├── Consumer
│   │           │   │   ├── Publisher
│   │           │   │   ├── Reader
│   │           │   │   │   ├── Env
│   │           │   │   │   │   └── Converter
│   │           │   │   │   └── Xml
│   │           │   │   │       └── Converter
│   │           │   │   └── Topology
│   │           │   ├── Consumer
│   │           │   │   └── Config
│   │           │   │       ├── ConsumerConfigItem
│   │           │   │       │   └── Handler
│   │           │   │       ├── Env
│   │           │   │       ├── Validator
│   │           │   │       └── Xml
│   │           │   ├── etc
│   │           │   ├── Lock
│   │           │   ├── PoisonPill
│   │           │   ├── Publisher
│   │           │   │   └── Config
│   │           │   │       ├── Env
│   │           │   │       ├── PublisherConfigItem
│   │           │   │       ├── RemoteService
│   │           │   │       ├── Validator
│   │           │   │       └── Xml
│   │           │   ├── Rpc
│   │           │   ├── Test
│   │           │   │   └── Unit
│   │           │   │       ├── Bulk
│   │           │   │       │   └── Rpc
│   │           │   │       ├── Code
│   │           │   │       │   └── Generator
│   │           │   │       │       └── _files
│   │           │   │       ├── Config
│   │           │   │       │   ├── Consumer
│   │           │   │       │   ├── Publisher
│   │           │   │       │   ├── Reader
│   │           │   │       │   │   ├── Env
│   │           │   │       │   │   │   └── Converter
│   │           │   │       │   │   ├── Xml
│   │           │   │       │   │   │   └── Converter
│   │           │   │       │   │   └── XmlReader
│   │           │   │       │   └── Topology
│   │           │   │       ├── Consumer
│   │           │   │       │   └── Config
│   │           │   │       │       ├── Env
│   │           │   │       │       ├── Validator
│   │           │   │       │       └── Xml
│   │           │   │       ├── _files
│   │           │   │       │   ├── queue_consumer
│   │           │   │       │   ├── queue_publisher
│   │           │   │       │   └── queue_topology
│   │           │   │       ├── Publisher
│   │           │   │       │   └── Config
│   │           │   │       │       ├── Env
│   │           │   │       │       ├── RemoteService
│   │           │   │       │       ├── Validator
│   │           │   │       │       └── Xml
│   │           │   │       ├── Rpc
│   │           │   │       └── Topology
│   │           │   │           └── Config
│   │           │   │               ├── QueueConfigItem
│   │           │   │               ├── RemoteService
│   │           │   │               ├── Validator
│   │           │   │               └── Xml
│   │           │   └── Topology
│   │           │       └── Config
│   │           │           ├── ExchangeConfigItem
│   │           │           │   └── Binding
│   │           │           ├── QueueConfigItem
│   │           │           ├── RemoteService
│   │           │           ├── Validator
│   │           │           └── Xml
│   │           ├── Model
│   │           │   ├── ActionValidator
│   │           │   │   └── RemoveAction
│   │           │   ├── Entity
│   │           │   ├── EntitySnapshot
│   │           │   ├── Operation
│   │           │   ├── ResourceModel
│   │           │   │   ├── Db
│   │           │   │   │   ├── Collection
│   │           │   │   │   ├── Relation
│   │           │   │   │   └── VersionControl
│   │           │   │   ├── Entity
│   │           │   │   └── Type
│   │           │   │       └── Db
│   │           │   │           └── Pdo
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           ├── ActionValidator
│   │           │           ├── EntitySnapshot
│   │           │           └── ResourceModel
│   │           │               ├── Db
│   │           │               │   ├── Collection
│   │           │               │   ├── Relation
│   │           │               │   └── VersionControl
│   │           │               └── Type
│   │           │                   └── Db
│   │           │                       └── Pdo
│   │           ├── Module
│   │           │   ├── Declaration
│   │           │   │   └── Converter
│   │           │   ├── Dir
│   │           │   ├── etc
│   │           │   ├── ModuleList
│   │           │   ├── Output
│   │           │   ├── Plugin
│   │           │   ├── Setup
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           ├── Declaration
│   │           │           │   └── Converter
│   │           │           │       └── _files
│   │           │           ├── Dir
│   │           │           ├── _files
│   │           │           │   └── Module
│   │           │           │       ├── data
│   │           │           │       │   ├── module_first_setup
│   │           │           │       │   └── module_second_setup
│   │           │           │       └── sql
│   │           │           │           └── module_first_setup
│   │           │           ├── ModuleList
│   │           │           ├── Plugin
│   │           │           └── Setup
│   │           │               └── _files
│   │           ├── Mview
│   │           │   ├── Config
│   │           │   │   └── Data
│   │           │   ├── etc
│   │           │   ├── Test
│   │           │   │   └── Unit
│   │           │   │       ├── Config
│   │           │   │       │   └── Data
│   │           │   │       ├── _files
│   │           │   │       └── View
│   │           │   └── View
│   │           │       └── State
│   │           ├── Notification
│   │           │   └── Test
│   │           │       └── Unit
│   │           ├── Oauth
│   │           │   ├── Helper
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           └── Helper
│   │           ├── ObjectManager
│   │           │   ├── Code
│   │           │   │   └── Generator
│   │           │   ├── Config
│   │           │   │   ├── Mapper
│   │           │   │   └── Reader
│   │           │   ├── Definition
│   │           │   ├── etc
│   │           │   ├── Factory
│   │           │   │   └── Dynamic
│   │           │   ├── Helper
│   │           │   ├── Profiler
│   │           │   │   ├── Code
│   │           │   │   │   └── Generator
│   │           │   │   └── Tree
│   │           │   ├── Relations
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           ├── Code
│   │           │           │   └── Generator
│   │           │           │       └── _files
│   │           │           ├── Config
│   │           │           │   ├── _files
│   │           │           │   ├── Mapper
│   │           │           │   │   └── _files
│   │           │           │   └── Reader
│   │           │           │       └── _files
│   │           │           ├── Factory
│   │           │           │   └── Fixture
│   │           │           │       └── Compiled
│   │           │           ├── _files
│   │           │           │   ├── Aggregate
│   │           │           │   ├── Child
│   │           │           │   │   └── Interceptor
│   │           │           │   └── TMap
│   │           │           ├── Helper
│   │           │           ├── Profiler
│   │           │           └── Relations
│   │           ├── Option
│   │           ├── Parse
│   │           ├── Phrase
│   │           │   ├── Renderer
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           └── Renderer
│   │           ├── Pricing
│   │           │   ├── Adjustment
│   │           │   ├── Amount
│   │           │   ├── Helper
│   │           │   ├── Price
│   │           │   ├── PriceInfo
│   │           │   ├── Render
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           ├── Adjustment
│   │           │           ├── Amount
│   │           │           ├── Helper
│   │           │           ├── Price
│   │           │           ├── PriceInfo
│   │           │           └── Render
│   │           ├── Process
│   │           ├── Profiler
│   │           │   ├── Driver
│   │           │   │   └── Standard
│   │           │   │       └── Output
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           └── Driver
│   │           │               └── Standard
│   │           │                   └── Output
│   │           ├── Reflection
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           └── Fixture
│   │           │               └── UseClasses
│   │           │                   ├── SampleOne
│   │           │                   └── SampleTwo
│   │           ├── RequireJs
│   │           │   ├── Config
│   │           │   │   └── File
│   │           │   │       └── Collector
│   │           │   └── Test
│   │           │       └── Unit
│   │           ├── Search
│   │           │   ├── Adapter
│   │           │   │   ├── Aggregation
│   │           │   │   ├── Mysql
│   │           │   │   │   ├── Aggregation
│   │           │   │   │   │   └── Builder
│   │           │   │   │   ├── Field
│   │           │   │   │   ├── Filter
│   │           │   │   │   │   └── Builder
│   │           │   │   │   └── Query
│   │           │   │   │       └── Builder
│   │           │   │   └── Preprocessor
│   │           │   ├── Dynamic
│   │           │   │   └── Algorithm
│   │           │   ├── etc
│   │           │   ├── Request
│   │           │   │   ├── Aggregation
│   │           │   │   ├── Config
│   │           │   │   ├── Filter
│   │           │   │   └── Query
│   │           │   ├── Response
│   │           │   │   └── Aggregation
│   │           │   ├── SearchEngine
│   │           │   │   └── Config
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           ├── Adapter
│   │           │           │   ├── Aggregation
│   │           │           │   └── Mysql
│   │           │           │       ├── Aggregation
│   │           │           │       │   └── Builder
│   │           │           │       ├── Filter
│   │           │           │       │   └── Builder
│   │           │           │       └── Query
│   │           │           │           └── Builder
│   │           │           ├── Dynamic
│   │           │           ├── _files
│   │           │           ├── Request
│   │           │           │   ├── Aggregation
│   │           │           │   └── Config
│   │           │           ├── Response
│   │           │           └── SearchEngine
│   │           │               └── Config
│   │           ├── Serialize
│   │           │   ├── Serializer
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           └── Serializer
│   │           ├── Session
│   │           │   ├── Config
│   │           │   │   └── Validator
│   │           │   ├── SaveHandler
│   │           │   │   └── Redis
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           ├── _files
│   │           │           └── SaveHandler
│   │           │               └── Redis
│   │           ├── Setup
│   │           │   ├── Declaration
│   │           │   │   └── Schema
│   │           │   │       ├── Config
│   │           │   │       ├── DataSavior
│   │           │   │       ├── Db
│   │           │   │       │   └── MySQL
│   │           │   │       │       ├── DDL
│   │           │   │       │       │   └── Triggers
│   │           │   │       │       └── Definition
│   │           │   │       │           ├── Columns
│   │           │   │       │           └── Constraints
│   │           │   │       ├── Declaration
│   │           │   │       │   ├── TableElement
│   │           │   │       │   └── ValidationRules
│   │           │   │       ├── Diff
│   │           │   │       ├── Dto
│   │           │   │       │   ├── Columns
│   │           │   │       │   ├── Constraints
│   │           │   │       │   └── Factories
│   │           │   │       ├── etc
│   │           │   │       │   ├── constraints
│   │           │   │       │   └── types
│   │           │   │       │       ├── binaries
│   │           │   │       │       ├── datetime
│   │           │   │       │       ├── integers
│   │           │   │       │       ├── real
│   │           │   │       │       └── texts
│   │           │   │       ├── FileSystem
│   │           │   │       └── Operations
│   │           │   ├── Option
│   │           │   ├── Patch
│   │           │   ├── SampleData
│   │           │   ├── SchemaListenerDefinition
│   │           │   ├── SchemaListenerHandlers
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           ├── Declaration
│   │           │           │   └── Schema
│   │           │           │       ├── Config
│   │           │           │       ├── Db
│   │           │           │       │   └── MySQL
│   │           │           │       │       └── Definition
│   │           │           │       │           ├── Columns
│   │           │           │       │           └── Constraints
│   │           │           │       ├── Declaration
│   │           │           │       ├── Diff
│   │           │           │       ├── Dto
│   │           │           │       │   └── Factories
│   │           │           │       ├── Operations
│   │           │           │       └── ValidationRules
│   │           │           ├── _files
│   │           │           ├── Option
│   │           │           ├── Patch
│   │           │           └── SampleData
│   │           ├── Shell
│   │           │   └── Test
│   │           │       └── Unit
│   │           ├── Simplexml
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           └── _files
│   │           ├── Stdlib
│   │           │   ├── Cookie
│   │           │   ├── DateTime
│   │           │   │   ├── Filter
│   │           │   │   └── Timezone
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           ├── Cookie
│   │           │           │   └── _files
│   │           │           ├── DateTime
│   │           │           │   ├── Filter
│   │           │           │   └── Timezone
│   │           │           └── _files
│   │           ├── System
│   │           ├── Test
│   │           │   └── Unit
│   │           │       ├── App
│   │           │       │   └── Scope
│   │           │       ├── Communication
│   │           │       │   └── Config
│   │           │       ├── Config
│   │           │       ├── Data
│   │           │       │   └── Form
│   │           │       │       └── Element
│   │           │       ├── DB
│   │           │       │   └── Query
│   │           │       ├── DomDocument
│   │           │       ├── _files
│   │           │       │   └── archives
│   │           │       ├── Interception
│   │           │       │   └── Sample
│   │           │       ├── Message
│   │           │       ├── Module
│   │           │       │   └── Plugin
│   │           │       ├── Translate
│   │           │       │   └── Js
│   │           │       └── View
│   │           │           └── Design
│   │           │               └── Theme
│   │           │                   └── Label
│   │           ├── TestFramework
│   │           │   ├── Test
│   │           │   │   └── Unit
│   │           │   │       ├── Autoloader
│   │           │   │       └── Unit
│   │           │   │           ├── Helper
│   │           │   │           ├── Matcher
│   │           │   │           └── Utility
│   │           │   │               └── _files
│   │           │   └── Unit
│   │           │       ├── Autoloader
│   │           │       ├── Block
│   │           │       ├── Helper
│   │           │       ├── Listener
│   │           │       ├── Matcher
│   │           │       ├── Module
│   │           │       └── Utility
│   │           ├── Translate
│   │           │   ├── Inline
│   │           │   ├── Js
│   │           │   ├── Locale
│   │           │   │   └── Resolver
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           └── Inline
│   │           ├── Unserialize
│   │           │   └── Test
│   │           │       └── Unit
│   │           ├── Url
│   │           │   ├── Helper
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           └── Helper
│   │           ├── Validation
│   │           ├── Validator
│   │           │   ├── Constraint
│   │           │   │   └── Option
│   │           │   ├── Entity
│   │           │   ├── etc
│   │           │   ├── File
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           ├── Constraint
│   │           │           │   └── Option
│   │           │           ├── Entity
│   │           │           ├── _files
│   │           │           │   └── validation
│   │           │           │       ├── negative
│   │           │           │       └── positive
│   │           │           │           ├── builder
│   │           │           │           ├── module_a
│   │           │           │           └── module_b
│   │           │           └── Test
│   │           ├── View
│   │           │   ├── Asset
│   │           │   │   ├── Bundle
│   │           │   │   ├── File
│   │           │   │   ├── MergeStrategy
│   │           │   │   ├── NotationResolver
│   │           │   │   └── PreProcessor
│   │           │   │       ├── AlternativeSource
│   │           │   │       └── Helper
│   │           │   ├── Design
│   │           │   │   ├── Fallback
│   │           │   │   │   └── Rule
│   │           │   │   ├── FileResolution
│   │           │   │   │   └── Fallback
│   │           │   │   │       └── Resolver
│   │           │   │   └── Theme
│   │           │   │       ├── Customization
│   │           │   │       │   └── File
│   │           │   │       ├── Domain
│   │           │   │       ├── File
│   │           │   │       ├── Image
│   │           │   │       └── Label
│   │           │   ├── Element
│   │           │   │   ├── Block
│   │           │   │   ├── Html
│   │           │   │   │   └── Link
│   │           │   │   ├── Js
│   │           │   │   ├── Message
│   │           │   │   │   └── Renderer
│   │           │   │   │       └── BlockRenderer
│   │           │   │   ├── Template
│   │           │   │   │   └── File
│   │           │   │   ├── Text
│   │           │   │   │   └── TextList
│   │           │   │   └── UiComponent
│   │           │   │       ├── Argument
│   │           │   │       │   └── Interpreter
│   │           │   │       ├── Config
│   │           │   │       │   ├── FileCollector
│   │           │   │       │   └── Provider
│   │           │   │       │       └── Component
│   │           │   │       ├── ContentType
│   │           │   │       ├── Control
│   │           │   │       ├── DataProvider
│   │           │   │       └── Factory
│   │           │   ├── File
│   │           │   │   ├── Collector
│   │           │   │   │   ├── Decorator
│   │           │   │   │   └── Override
│   │           │   │   └── FileList
│   │           │   ├── Helper
│   │           │   ├── Layout
│   │           │   │   ├── Argument
│   │           │   │   │   └── Interpreter
│   │           │   │   │       └── Decorator
│   │           │   │   ├── Condition
│   │           │   │   ├── Data
│   │           │   │   ├── etc
│   │           │   │   ├── File
│   │           │   │   │   └── Collector
│   │           │   │   ├── Generator
│   │           │   │   ├── PageType
│   │           │   │   │   └── Config
│   │           │   │   ├── Reader
│   │           │   │   │   └── Visibility
│   │           │   │   └── ScheduledStructure
│   │           │   ├── Model
│   │           │   │   ├── Layout
│   │           │   │   │   └── Update
│   │           │   │   └── PageLayout
│   │           │   │       └── Config
│   │           │   ├── Page
│   │           │   │   ├── Config
│   │           │   │   │   ├── Generator
│   │           │   │   │   └── Reader
│   │           │   │   └── Layout
│   │           │   ├── PageLayout
│   │           │   │   ├── etc
│   │           │   │   └── File
│   │           │   │       └── Collector
│   │           │   ├── Render
│   │           │   ├── Result
│   │           │   ├── Template
│   │           │   │   └── Html
│   │           │   ├── TemplateEngine
│   │           │   │   └── Xhtml
│   │           │   │       └── Compiler
│   │           │   │           ├── Directive
│   │           │   │           └── Element
│   │           │   ├── Test
│   │           │   │   └── Unit
│   │           │   │       ├── Asset
│   │           │   │       │   ├── Bundle
│   │           │   │       │   ├── File
│   │           │   │       │   ├── MergeStrategy
│   │           │   │       │   ├── NotationResolver
│   │           │   │       │   └── PreProcessor
│   │           │   │       │       └── Helper
│   │           │   │       ├── Design
│   │           │   │       │   ├── Fallback
│   │           │   │       │   │   └── Rule
│   │           │   │       │   ├── FileResolution
│   │           │   │       │   │   └── Fallback
│   │           │   │       │   │       └── Resolver
│   │           │   │       │   └── Theme
│   │           │   │       │       ├── Customization
│   │           │   │       │       ├── Domain
│   │           │   │       │       └── Image
│   │           │   │       ├── Element
│   │           │   │       │   ├── Html
│   │           │   │       │   │   └── Link
│   │           │   │       │   ├── Js
│   │           │   │       │   ├── Message
│   │           │   │       │   │   └── Renderer
│   │           │   │       │   │       └── BlockRenderer
│   │           │   │       │   ├── Template
│   │           │   │       │   │   └── File
│   │           │   │       │   ├── Text
│   │           │   │       │   │   └── TextList
│   │           │   │       │   └── UiComponent
│   │           │   │       │       ├── Control
│   │           │   │       │       └── DataProvider
│   │           │   │       ├── File
│   │           │   │       │   ├── Collector
│   │           │   │       │   │   ├── Decorator
│   │           │   │       │   │   └── Override
│   │           │   │       │   └── FileList
│   │           │   │       ├── Helper
│   │           │   │       ├── Layout
│   │           │   │       │   ├── Argument
│   │           │   │       │   │   ├── _files
│   │           │   │       │   │   └── Interpreter
│   │           │   │       │   │       └── Decorator
│   │           │   │       │   ├── Condition
│   │           │   │       │   ├── Data
│   │           │   │       │   ├── File
│   │           │   │       │   │   └── Collector
│   │           │   │       │   ├── _files
│   │           │   │       │   ├── Generator
│   │           │   │       │   ├── Reader
│   │           │   │       │   └── ScheduledStructure
│   │           │   │       ├── Model
│   │           │   │       │   └── Layout
│   │           │   │       │       └── Update
│   │           │   │       ├── Page
│   │           │   │       │   ├── Config
│   │           │   │       │   │   ├── _files
│   │           │   │       │   │   ├── Generator
│   │           │   │       │   │   └── Reader
│   │           │   │       │   └── Layout
│   │           │   │       ├── PageLayout
│   │           │   │       │   └── _files
│   │           │   │       ├── Render
│   │           │   │       ├── Result
│   │           │   │       ├── Template
│   │           │   │       │   └── Html
│   │           │   │       ├── TemplateEngine
│   │           │   │       │   └── _files
│   │           │   │       ├── UiComponent
│   │           │   │       │   └── Factory
│   │           │   │       └── Url
│   │           │   │           └── _files
│   │           │   ├── Url
│   │           │   └── Xsd
│   │           │       └── Media
│   │           ├── Webapi
│   │           │   ├── CustomAttribute
│   │           │   ├── Rest
│   │           │   │   ├── Request
│   │           │   │   │   └── Deserializer
│   │           │   │   └── Response
│   │           │   │       └── Renderer
│   │           │   ├── Soap
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           ├── Rest
│   │           │           │   ├── Request
│   │           │           │   │   └── Deserializer
│   │           │           │   └── Response
│   │           │           │       └── Renderer
│   │           │           └── ServiceInputProcessor
│   │           ├── Xml
│   │           │   └── Test
│   │           │       └── Unit
│   │           │           └── _files
│   │           └── XsltProcessor
│   └── web
│       ├── css
│       │   ├── docs
│       │   │   └── source
│       │   │       └── js
│       │   └── source
│       │       ├── components
│       │       └── lib
│       │           └── variables
│       ├── extjs
│       │   └── resources
│       │       ├── css
│       │       └── images
│       │           ├── aero
│       │           │   ├── basic-dialog
│       │           │   ├── grid
│       │           │   ├── layout
│       │           │   ├── menu
│       │           │   ├── qtip
│       │           │   ├── sizer
│       │           │   ├── tabs
│       │           │   └── toolbar
│       │           ├── default
│       │           │   ├── basic-dialog
│       │           │   ├── box
│       │           │   ├── dd
│       │           │   ├── editor
│       │           │   ├── form
│       │           │   ├── grid
│       │           │   ├── layout
│       │           │   ├── menu
│       │           │   ├── panel
│       │           │   ├── qtip
│       │           │   ├── shared
│       │           │   ├── sizer
│       │           │   ├── tabs
│       │           │   ├── toolbar
│       │           │   ├── tree
│       │           │   └── window
│       │           ├── galdaka
│       │           │   ├── basic-dialog
│       │           │   ├── form
│       │           │   ├── grid
│       │           │   ├── layout
│       │           │   ├── menu
│       │           │   ├── qtip
│       │           │   ├── shared
│       │           │   ├── sizer
│       │           │   ├── tabs
│       │           │   └── toolbar
│       │           ├── gray
│       │           │   ├── basic-dialog
│       │           │   ├── grid
│       │           │   ├── layout
│       │           │   ├── menu
│       │           │   ├── qtip
│       │           │   ├── sizer
│       │           │   ├── tabs
│       │           │   └── toolbar
│       │           ├── magento
│       │           │   ├── basic-dialog
│       │           │   ├── grid
│       │           │   ├── layout
│       │           │   ├── tabs
│       │           │   ├── toolbar
│       │           │   └── tree
│       │           └── vista
│       │               ├── basic-dialog
│       │               ├── grid
│       │               ├── layout
│       │               ├── qtip
│       │               ├── sizer
│       │               ├── tabs
│       │               └── toolbar
│       ├── fonts
│       │   ├── Blank-Theme-Icons
│       │   ├── MUI-Icons
│       │   ├── opensans
│       │   │   ├── bold
│       │   │   ├── light
│       │   │   ├── regular
│       │   │   └── semibold
│       │   └── UX-Icons
│       ├── fotorama
│       ├── i18n
│       ├── images
│       ├── jquery
│       │   ├── colorpicker
│       │   │   ├── css
│       │   │   ├── images
│       │   │   └── js
│       │   ├── editableMultiselect
│       │   │   ├── css
│       │   │   └── js
│       │   ├── fileUploader
│       │   │   ├── cors
│       │   │   ├── css
│       │   │   ├── img
│       │   │   └── vendor
│       │   ├── jstree
│       │   │   └── themes
│       │   │       ├── apple
│       │   │       ├── classic
│       │   │       ├── default
│       │   │       └── default-rtl
│       │   ├── patches
│       │   └── spectrum
│       ├── knockoutjs
│       ├── less
│       ├── lib
│       ├── mage
│       │   ├── adminhtml
│       │   │   └── wysiwyg
│       │   │       └── tiny_mce
│       │   │           ├── plugins
│       │   │           │   ├── magentovariable
│       │   │           │   │   └── img
│       │   │           │   └── magentowidget
│       │   │           │       └── img
│       │   │           └── themes
│       │   │               └── advanced
│       │   │                   └── skins
│       │   │                       └── default
│       │   ├── app
│       │   ├── apply
│       │   ├── backend
│       │   ├── gallery
│       │   │   └── module
│       │   ├── requirejs
│       │   ├── utils
│       │   ├── validation
│       │   └── view
│       ├── magnifier
│       ├── modernizr
│       ├── prototype
│       │   └── windows
│       │       └── themes
│       │           ├── alert
│       │           ├── alphacube
│       │           ├── darkX
│       │           ├── default
│       │           ├── iefix
│       │           ├── lighting
│       │           ├── nuncio
│       │           └── spread
│       ├── requirejs
│       ├── scriptaculous
│       ├── tiny_mce_4
│       │   ├── langs
│       │   ├── plugins
│       │   │   ├── advlist
│       │   │   ├── anchor
│       │   │   ├── autolink
│       │   │   ├── autoresize
│       │   │   ├── autosave
│       │   │   ├── bbcode
│       │   │   ├── charmap
│       │   │   ├── code
│       │   │   ├── codesample
│       │   │   │   └── css
│       │   │   ├── colorpicker
│       │   │   ├── contextmenu
│       │   │   ├── directionality
│       │   │   ├── emoticons
│       │   │   │   └── img
│       │   │   ├── fullpage
│       │   │   ├── fullscreen
│       │   │   ├── help
│       │   │   │   └── img
│       │   │   ├── hr
│       │   │   ├── image
│       │   │   ├── imagetools
│       │   │   ├── importcss
│       │   │   ├── insertdatetime
│       │   │   ├── legacyoutput
│       │   │   ├── lineheight
│       │   │   ├── link
│       │   │   ├── lists
│       │   │   ├── media
│       │   │   ├── nonbreaking
│       │   │   ├── noneditable
│       │   │   ├── pagebreak
│       │   │   ├── paste
│       │   │   ├── preview
│       │   │   ├── print
│       │   │   ├── save
│       │   │   ├── searchreplace
│       │   │   ├── spellchecker
│       │   │   ├── tabfocus
│       │   │   ├── table
│       │   │   ├── template
│       │   │   ├── textcolor
│       │   │   ├── textpattern
│       │   │   ├── toc
│       │   │   ├── visualblocks
│       │   │   │   └── css
│       │   │   ├── visualchars
│       │   │   └── wordcount
│       │   ├── skins
│       │   │   └── lightgray
│       │   │       ├── fonts
│       │   │       └── img
│       │   └── themes
│       │       ├── inlite
│       │       └── modern
│       └── varien
├── phpserver
├── pub
│   ├── errors
│   │   └── default
│   │       ├── css
│   │       └── images
│   ├── media
│   │   ├── customer
│   │   ├── downloadable
│   │   ├── import
│   │   └── theme_customization
│   ├── opt
│   │   └── magento
│   │       └── var
│   └── static
├── setup
│   ├── config
│   │   └── autoload
│   ├── performance-toolkit
│   │   ├── config
│   │   ├── files
│   │   └── profiles
│   │       └── ce
│   ├── pub
│   │   ├── angular
│   │   ├── angular-clickout
│   │   ├── angular-ng-dialog
│   │   ├── angular-ng-storage
│   │   ├── angular-sanitize
│   │   ├── angular-ui-bootstrap
│   │   ├── angular-ui-router
│   │   ├── bootstrap
│   │   │   └── js
│   │   ├── fonts
│   │   │   ├── icons
│   │   │   └── opensans
│   │   │       ├── bold
│   │   │       ├── light
│   │   │       ├── regular
│   │   │       └── semibold
│   │   ├── images
│   │   │   └── favicon
│   │   ├── magento
│   │   │   └── setup
│   │   │       └── view
│   │   └── styles
│   ├── src
│   │   ├── Magento
│   │   │   └── Setup
│   │   │       ├── Console
│   │   │       │   ├── Command
│   │   │       │   └── Style
│   │   │       ├── Controller
│   │   │       ├── Fixtures
│   │   │       │   ├── AttributeSet
│   │   │       │   ├── _files
│   │   │       │   ├── ImagesGenerator
│   │   │       │   └── Quote
│   │   │       ├── Model
│   │   │       │   ├── Address
│   │   │       │   ├── Complex
│   │   │       │   ├── ConfigOptionsList
│   │   │       │   ├── Cron
│   │   │       │   │   ├── Helper
│   │   │       │   │   └── Queue
│   │   │       │   ├── Customer
│   │   │       │   ├── DateTime
│   │   │       │   ├── Description
│   │   │       │   │   └── Mixin
│   │   │       │   │       └── Helper
│   │   │       │   ├── FixtureGenerator
│   │   │       │   ├── Grid
│   │   │       │   └── Installer
│   │   │       ├── Module
│   │   │       │   ├── Dependency
│   │   │       │   │   ├── Parser
│   │   │       │   │   │   ├── Composer
│   │   │       │   │   │   └── Config
│   │   │       │   │   └── Report
│   │   │       │   │       ├── Builder
│   │   │       │   │       ├── Circular
│   │   │       │   │       │   └── Data
│   │   │       │   │       ├── Data
│   │   │       │   │       │   └── Config
│   │   │       │   │       ├── Dependency
│   │   │       │   │       │   └── Data
│   │   │       │   │       ├── Framework
│   │   │       │   │       │   └── Data
│   │   │       │   │       └── Writer
│   │   │       │   │           └── Csv
│   │   │       │   ├── Di
│   │   │       │   │   ├── App
│   │   │       │   │   │   └── Task
│   │   │       │   │   │       └── Operation
│   │   │       │   │   ├── Code
│   │   │       │   │   │   ├── Generator
│   │   │       │   │   │   ├── Reader
│   │   │       │   │   │   │   └── Decorator
│   │   │       │   │   │   └── Scanner
│   │   │       │   │   ├── Compiler
│   │   │       │   │   │   ├── Config
│   │   │       │   │   │   │   ├── Chain
│   │   │       │   │   │   │   └── Writer
│   │   │       │   │   │   └── Log
│   │   │       │   │   │       └── Writer
│   │   │       │   │   └── Definition
│   │   │       │   ├── I18n
│   │   │       │   │   ├── Dictionary
│   │   │       │   │   │   ├── Loader
│   │   │       │   │   │   │   └── File
│   │   │       │   │   │   ├── Options
│   │   │       │   │   │   └── Writer
│   │   │       │   │   │       └── Csv
│   │   │       │   │   ├── Pack
│   │   │       │   │   │   └── Writer
│   │   │       │   │   │       └── File
│   │   │       │   │   └── Parser
│   │   │       │   │       └── Adapter
│   │   │       │   │           └── Php
│   │   │       │   │               └── Tokenizer
│   │   │       │   │                   └── Translate
│   │   │       │   └── Setup
│   │   │       ├── Mvc
│   │   │       │   ├── Bootstrap
│   │   │       │   └── View
│   │   │       │       └── Http
│   │   │       ├── Test
│   │   │       │   └── Unit
│   │   │       │       ├── Console
│   │   │       │       │   ├── Command
│   │   │       │       │   └── Style
│   │   │       │       ├── Controller
│   │   │       │       ├── Fixtures
│   │   │       │       │   ├── AttributeSet
│   │   │       │       │   └── Quote
│   │   │       │       ├── Model
│   │   │       │       │   ├── Address
│   │   │       │       │   ├── Complex
│   │   │       │       │   ├── ConfigOptionsList
│   │   │       │       │   ├── Cron
│   │   │       │       │   │   ├── Helper
│   │   │       │       │   │   └── Queue
│   │   │       │       │   ├── Customer
│   │   │       │       │   ├── DateTime
│   │   │       │       │   ├── Description
│   │   │       │       │   │   └── Mixin
│   │   │       │       │   │       └── Helper
│   │   │       │       │   ├── _files
│   │   │       │       │   ├── FixtureGenerator
│   │   │       │       │   ├── Grid
│   │   │       │       │   └── Installer
│   │   │       │       ├── Module
│   │   │       │       │   ├── Dependency
│   │   │       │       │   │   ├── Parser
│   │   │       │       │   │   │   ├── Composer
│   │   │       │       │   │   │   └── Config
│   │   │       │       │   │   └── Report
│   │   │       │       │   │       ├── Builder
│   │   │       │       │   │       ├── Circular
│   │   │       │       │   │       │   └── Data
│   │   │       │       │   │       ├── Data
│   │   │       │       │   │       │   └── Config
│   │   │       │       │   │       ├── Dependency
│   │   │       │       │   │       │   └── Data
│   │   │       │       │   │       ├── Framework
│   │   │       │       │   │       │   └── Data
│   │   │       │       │   │       └── Writer
│   │   │       │       │   │           └── Csv
│   │   │       │       │   ├── Di
│   │   │       │       │   │   ├── App
│   │   │       │       │   │   │   └── Task
│   │   │       │       │   │   ├── Code
│   │   │       │       │   │   │   ├── Generator
│   │   │       │       │   │   │   ├── Reader
│   │   │       │       │   │   │   │   ├── _files
│   │   │       │       │   │   │   │   └── InstancesNamesList
│   │   │       │       │   │   │   └── Scanner
│   │   │       │       │   │   ├── Compiler
│   │   │       │       │   │   │   └── Config
│   │   │       │       │   │   │       └── Chain
│   │   │       │       │   │   ├── Definition
│   │   │       │       │   │   └── _files
│   │   │       │       │   │       ├── app
│   │   │       │       │   │       │   ├── code
│   │   │       │       │   │       │   │   └── Magento
│   │   │       │       │   │       │   │       └── SomeModule
│   │   │       │       │   │       │   │           ├── Api
│   │   │       │       │   │       │   │           │   └── Data
│   │   │       │       │   │       │   │           ├── etc
│   │   │       │       │   │       │   │           │   ├── adminhtml
│   │   │       │       │   │       │   │           │   └── source
│   │   │       │       │   │       │   │           │       └── PhpExt.php
│   │   │       │       │   │       │   │           ├── Helper
│   │   │       │       │   │       │   │           ├── Model
│   │   │       │       │   │       │   │           └── view
│   │   │       │       │   │       │   │               └── frontend
│   │   │       │       │   │       │   ├── design
│   │   │       │       │   │       │   │   └── adminhtml
│   │   │       │       │   │       │   │       └── default
│   │   │       │       │   │       │   │           └── backend
│   │   │       │       │   │       │   └── etc
│   │   │       │       │   │       │       └── di
│   │   │       │       │   │       └── var
│   │   │       │       │   │           └── generation
│   │   │       │       │   ├── I18n
│   │   │       │       │   │   ├── Dictionary
│   │   │       │       │   │   │   ├── Loader
│   │   │       │       │   │   │   │   └── File
│   │   │       │       │   │   │   ├── Options
│   │   │       │       │   │   │   │   └── _files
│   │   │       │       │   │   │   │       └── source
│   │   │       │       │   │   │   │           ├── app
│   │   │       │       │   │   │   │           │   ├── code
│   │   │       │       │   │   │   │           │   │   ├── module1
│   │   │       │       │   │   │   │           │   │   └── module2
│   │   │       │       │   │   │   │           │   └── design
│   │   │       │       │   │   │   │           └── lib
│   │   │       │       │   │   │   │               └── web
│   │   │       │       │   │   │   │                   ├── mage
│   │   │       │       │   │   │   │                   └── varien
│   │   │       │       │   │   │   └── Writer
│   │   │       │       │   │   │       ├── Csv
│   │   │       │       │   │   │       └── _files
│   │   │       │       │   │   ├── _files
│   │   │       │       │   │   │   └── files_collector
│   │   │       │       │   │   ├── Pack
│   │   │       │       │   │   │   └── Writer
│   │   │       │       │   │   │       └── File
│   │   │       │       │   │   │           └── _files
│   │   │       │       │   │   └── Parser
│   │   │       │       │   │       └── Adapter
│   │   │       │       │   │           ├── _files
│   │   │       │       │   │           └── Php
│   │   │       │       │   │               ├── _files
│   │   │       │       │   │               └── Tokenizer
│   │   │       │       │   └── Setup
│   │   │       │       ├── Mvc
│   │   │       │       │   └── Bootstrap
│   │   │       │       └── Validator
│   │   │       └── Validator
│   │   └── Zend
│   │       └── Mvc
│   │           └── Controller
│   └── view
│       ├── error
│       ├── layout
│       ├── magento
│       │   └── setup
│       │       ├── complete-backup
│       │       ├── navigation
│       │       └── readiness-check
│       └── styles
│           └── lib
│               └── variables
├── var
└── vendor

16536 directories
