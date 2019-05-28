# prestashop

## structure of directories

```
.
├── admin-dev
│   ├── autoupgrade
│   │   └── backup
│   ├── backups
│   ├── export
│   ├── filemanager
│   │   ├── config
│   │   ├── css
│   │   ├── img
│   │   │   ├── ico
│   │   │   └── ico_dark
│   │   ├── include
│   │   ├── jPlayer
│   │   │   ├── add-on
│   │   │   ├── popcorn
│   │   │   └── skin
│   │   │       └── blue.monday
│   │   ├── js
│   │   ├── lang
│   │   └── uploader
│   ├── import
│   ├── public
│   └── themes
│       ├── default
│       │   ├── css
│       │   │   ├── bundle
│       │   │   └── vendor
│       │   │       └── font-awesome
│       │   ├── fonts
│       │   ├── img
│       │   │   ├── bundle
│       │   │   └── patterns
│       │   ├── js
│       │   │   ├── bundle
│       │   │   │   ├── admin_parameters
│       │   │   │   ├── module
│       │   │   │   ├── plugins
│       │   │   │   └── product
│       │   │   └── vendor
│       │   │       └── bootstrap
│       │   ├── public
│       │   ├── sass
│       │   │   ├── controllers
│       │   │   ├── modules
│       │   │   │   └── colors
│       │   │   ├── partials
│       │   │   └── vendor
│       │   │       ├── bi-app
│       │   │       ├── bootstrap-rtl-sass
│       │   │       ├── bootstrap-sass
│       │   │       │   └── mixins
│       │   │       └── font-awesome
│       │   └── template
│       │       ├── controllers
│       │       │   ├── access
│       │       │   │   └── helpers
│       │       │   │       └── form
│       │       │   ├── addresses
│       │       │   │   └── helpers
│       │       │   │       ├── form
│       │       │   │       └── list
│       │       │   ├── attachments
│       │       │   │   └── helpers
│       │       │   │       └── list
│       │       │   ├── attribute_generator
│       │       │   ├── attributes
│       │       │   │   └── helpers
│       │       │   │       └── form
│       │       │   ├── attributes_groups
│       │       │   │   └── helpers
│       │       │   │       ├── form
│       │       │   │       ├── list
│       │       │   │       └── view
│       │       │   ├── carriers
│       │       │   │   └── helpers
│       │       │   │       ├── form
│       │       │   │       └── list
│       │       │   ├── carrier_wizard
│       │       │   │   └── helpers
│       │       │   │       ├── form
│       │       │   │       └── view
│       │       │   ├── cart_rules
│       │       │   │   └── helpers
│       │       │   │       └── list
│       │       │   ├── carts
│       │       │   │   └── helpers
│       │       │   │       └── view
│       │       │   ├── countries
│       │       │   │   └── helpers
│       │       │   │       ├── form
│       │       │   │       └── list
│       │       │   ├── customer_threads
│       │       │   │   └── helpers
│       │       │   │       ├── list
│       │       │   │       ├── options
│       │       │   │       └── view
│       │       │   ├── dashboard
│       │       │   │   └── helpers
│       │       │   │       └── view
│       │       │   ├── features
│       │       │   │   └── helpers
│       │       │   │       └── form
│       │       │   ├── feature_value
│       │       │   │   └── helpers
│       │       │   │       └── form
│       │       │   ├── groups
│       │       │   │   └── helpers
│       │       │   │       ├── form
│       │       │   │       ├── tree
│       │       │   │       └── view
│       │       │   ├── images
│       │       │   ├── import
│       │       │   │   └── helpers
│       │       │   │       └── view
│       │       │   ├── login
│       │       │   ├── marketing
│       │       │   │   └── helpers
│       │       │   │       └── view
│       │       │   ├── meta
│       │       │   │   └── helpers
│       │       │   ├── modules
│       │       │   ├── not_found
│       │       │   ├── orders
│       │       │   │   └── helpers
│       │       │   │       ├── list
│       │       │   │       └── view
│       │       │   ├── outstanding
│       │       │   ├── payment
│       │       │   │   └── helpers
│       │       │   │       └── view
│       │       │   ├── referrers
│       │       │   │   └── helpers
│       │       │   │       ├── form
│       │       │   │       ├── list
│       │       │   │       └── view
│       │       │   ├── return
│       │       │   │   └── helpers
│       │       │   │       └── form
│       │       │   ├── scenes
│       │       │   │   └── helpers
│       │       │   │       ├── form
│       │       │   │       └── tree
│       │       │   ├── search
│       │       │   │   └── helpers
│       │       │   │       └── view
│       │       │   ├── shop
│       │       │   │   └── helpers
│       │       │   │       ├── form
│       │       │   │       ├── list
│       │       │   │       └── tree
│       │       │   ├── shop_group
│       │       │   │   └── helpers
│       │       │   │       └── form
│       │       │   ├── shop_url
│       │       │   │   └── helpers
│       │       │   │       ├── form
│       │       │   │       └── list
│       │       │   ├── slip
│       │       │   │   └── helpers
│       │       │   │       └── form
│       │       │   ├── specific_price_rule
│       │       │   │   └── helpers
│       │       │   │       └── form
│       │       │   ├── states
│       │       │   │   └── helpers
│       │       │   │       └── list
│       │       │   ├── stats
│       │       │   │   └── helpers
│       │       │   │       └── view
│       │       │   ├── statuses
│       │       │   │   └── helpers
│       │       │   │       └── form
│       │       │   ├── stores
│       │       │   │   └── helpers
│       │       │   │       ├── form
│       │       │   │       └── options
│       │       │   ├── suppliers
│       │       │   │   └── helpers
│       │       │   │       └── view
│       │       │   ├── tabs
│       │       │   │   └── helpers
│       │       │   │       └── list
│       │       │   ├── tags
│       │       │   │   └── helpers
│       │       │   │       └── form
│       │       │   ├── tax_rules
│       │       │   │   └── helpers
│       │       │   │       ├── form
│       │       │   │       └── list
│       │       │   ├── tax_rules_group
│       │       │   │   └── helpers
│       │       │   ├── tracking
│       │       │   │   └── helpers
│       │       │   │       └── list
│       │       │   ├── translations
│       │       │   │   └── helpers
│       │       │   │       └── view
│       │       │   └── zones
│       │       └── helpers
│       │           ├── calendar
│       │           ├── dataviz
│       │           ├── form
│       │           ├── kpi
│       │           ├── list
│       │           ├── modules_list
│       │           ├── options
│       │           ├── shops_list
│       │           ├── tree
│       │           ├── uploader
│       │           └── view
│       └── new-theme
│           ├── css
│           │   └── module
│           ├── img
│           │   └── empty_state
│           ├── js
│           │   ├── app
│           │   │   ├── cldr
│           │   │   │   ├── exception
│           │   │   │   └── specifications
│           │   │   ├── pages
│           │   │   │   ├── catalog
│           │   │   │   ├── module-card
│           │   │   │   ├── stock
│           │   │   │   │   ├── components
│           │   │   │   │   │   ├── header
│           │   │   │   │   │   │   └── filters
│           │   │   │   │   │   ├── movements
│           │   │   │   │   │   └── overview
│           │   │   │   │   ├── mixins
│           │   │   │   │   ├── router
│           │   │   │   │   └── store
│           │   │   │   └── translations
│           │   │   │       ├── components
│           │   │   │       │   ├── header
│           │   │   │       │   ├── principal
│           │   │   │       │   └── sidebar
│           │   │   │       ├── mixins
│           │   │   │       ├── router
│           │   │   │       └── store
│           │   │   ├── store
│           │   │   ├── utils
│           │   │   │   └── serp
│           │   │   └── widgets
│           │   │       ├── ps-table
│           │   │       └── ps-tree
│           │   ├── components
│           │   │   ├── form
│           │   │   ├── grid
│           │   │   │   └── extension
│           │   │   │       ├── action
│           │   │   │       │   ├── bulk
│           │   │   │       │   │   ├── category
│           │   │   │       │   │   └── customer
│           │   │   │       │   └── row
│           │   │   │       │       ├── category
│           │   │   │       │       └── customer
│           │   │   │       └── column
│           │   │   │           ├── catalog
│           │   │   │           └── common
│           │   │   ├── multi-store-restriction-field
│           │   │   └── showcase-card
│           │   │       └── extension
│           │   ├── maintenance-page
│           │   ├── pages
│           │   │   ├── backup
│           │   │   ├── catalog
│           │   │   │   └── product
│           │   │   ├── category
│           │   │   ├── cms-page
│           │   │   │   └── form
│           │   │   ├── contacts
│           │   │   ├── currency
│           │   │   ├── customer
│           │   │   ├── email
│           │   │   ├── employee
│           │   │   ├── geolocation
│           │   │   ├── import
│           │   │   ├── import-data
│           │   │   ├── improve
│           │   │   │   └── design_positions
│           │   │   ├── invoices
│           │   │   ├── language
│           │   │   ├── localization
│           │   │   ├── logs
│           │   │   ├── maintenance
│           │   │   ├── manufacturer
│           │   │   ├── meta
│           │   │   ├── module
│           │   │   ├── order
│           │   │   │   └── delivery
│           │   │   ├── order-preferences
│           │   │   ├── payment-preferences
│           │   │   ├── product-preferences
│           │   │   ├── profiles
│           │   │   ├── sql-manager
│           │   │   ├── supplier
│           │   │   ├── tax
│           │   │   ├── themes
│           │   │   ├── translation-settings
│           │   │   └── webservice
│           │   ├── product-page
│           │   └── translation-page
│           ├── public
│           ├── scss
│           │   ├── components
│           │   │   └── layout
│           │   ├── config
│           │   ├── img
│           │   │   ├── helper-card
│           │   │   └── pages
│           │   │       └── themes
│           │   ├── mixins
│           │   └── pages
│           │       └── partials
│           ├── template
│           │   ├── components
│           │   │   └── layout
│           │   ├── controllers
│           │   │   └── modules
│           │   └── helpers
│           │       ├── kpi
│           │       └── shops_list
│           └── tests
│               └── cldr
│                   └── specifications
├── app
│   ├── config
│   │   └── addons
│   ├── Resources
│   │   ├── geoip
│   │   ├── translations
│   │   │   └── default
│   │   └── views
│   └── test
│       └── cache
├── bin
├── cache
│   ├── cachefs
│   ├── purifier
│   ├── push
│   ├── sandbox
│   ├── smarty
│   │   ├── cache
│   │   └── compile
│   └── tcpdf
├── classes
│   ├── assets
│   ├── cache
│   ├── checkout
│   ├── container
│   ├── controller
│   ├── db
│   ├── exception
│   ├── form
│   ├── helper
│   ├── lang
│   │   └── KeysReference
│   ├── log
│   ├── module
│   ├── order
│   ├── pdf
│   ├── proxy
│   ├── range
│   ├── shop
│   ├── Smarty
│   ├── stock
│   ├── tax
│   ├── tree
│   └── webservice
├── config
│   ├── services
│   │   ├── admin
│   │   └── front
│   ├── themes
│   └── xml
│       └── themes
├── controllers
│   ├── admin
│   └── front
│       └── listing
├── docs
│   ├── csv_import
│   ├── docker
│   │   ├── nginx_fpm
│   │   │   ├── prestashop-fpm
│   │   │   └── prestashop-nginx
│   │   └── nginx_fpm_supervisord
│   │       └── prestashop-nginx-fpm
│   ├── licences
│   └── server_config
├── download
├── img
│   ├── admin
│   ├── c
│   ├── cms
│   ├── co
│   ├── genders
│   ├── jquery-ui
│   ├── l
│   ├── m
│   ├── os
│   ├── p
│   ├── s
│   ├── scenes
│   │   └── thumbs
│   ├── st
│   ├── su
│   ├── t
│   └── tmp
├── install-dev
│   ├── classes
│   ├── controllers
│   │   ├── console
│   │   └── http
│   ├── data
│   │   ├── img
│   │   │   ├── genders
│   │   │   └── os
│   │   └── xml
│   ├── fixtures
│   │   └── fashion
│   │       ├── data
│   │       ├── img
│   │       │   ├── c
│   │       │   ├── m
│   │       │   ├── p
│   │       │   ├── scenes
│   │       │   │   └── thumbs
│   │       │   ├── st
│   │       │   └── su
│   │       └── langs
│   │           ├── bn
│   │           │   └── data
│   │           ├── br
│   │           │   └── data
│   │           ├── de
│   │           │   └── data
│   │           ├── en
│   │           │   └── data
│   │           ├── es
│   │           │   └── data
│   │           ├── fa
│   │           │   └── data
│   │           ├── fr
│   │           │   └── data
│   │           ├── id
│   │           │   └── data
│   │           ├── it
│   │           │   └── data
│   │           ├── nl
│   │           │   └── data
│   │           ├── pl
│   │           │   └── data
│   │           ├── qc
│   │           │   └── data
│   │           ├── ro
│   │           │   └── data
│   │           ├── ru
│   │           │   └── data
│   │           ├── tw
│   │           │   └── data
│   │           ├── vn
│   │           │   └── data
│   │           └── zh
│   │               └── data
│   ├── langs
│   │   ├── ar
│   │   │   ├── data
│   │   │   └── img
│   │   ├── bg
│   │   │   ├── data
│   │   │   └── img
│   │   ├── bn
│   │   │   ├── data
│   │   │   └── img
│   │   ├── br
│   │   │   ├── data
│   │   │   └── img
│   │   ├── bs
│   │   │   ├── data
│   │   │   └── img
│   │   ├── ca
│   │   ├── cs
│   │   │   ├── data
│   │   │   └── img
│   │   ├── da
│   │   │   ├── data
│   │   │   └── img
│   │   ├── de
│   │   │   ├── data
│   │   │   └── img
│   │   ├── el
│   │   │   ├── data
│   │   │   └── img
│   │   ├── en
│   │   │   ├── data
│   │   │   └── img
│   │   ├── es
│   │   │   ├── data
│   │   │   └── img
│   │   ├── et
│   │   │   ├── data
│   │   │   └── img
│   │   ├── fa
│   │   │   ├── data
│   │   │   └── img
│   │   ├── fi
│   │   │   ├── data
│   │   │   └── img
│   │   ├── fr
│   │   │   ├── data
│   │   │   └── img
│   │   ├── gl
│   │   │   ├── data
│   │   │   └── img
│   │   ├── he
│   │   │   ├── data
│   │   │   └── img
│   │   ├── hi
│   │   │   ├── data
│   │   │   └── img
│   │   ├── hr
│   │   │   ├── data
│   │   │   └── img
│   │   ├── hu
│   │   │   ├── data
│   │   │   └── img
│   │   ├── id
│   │   │   ├── data
│   │   │   └── img
│   │   ├── it
│   │   │   ├── data
│   │   │   └── img
│   │   ├── ja
│   │   │   ├── data
│   │   │   └── img
│   │   ├── lt
│   │   │   ├── data
│   │   │   └── img
│   │   ├── lv
│   │   │   ├── data
│   │   │   └── img
│   │   ├── mk
│   │   │   ├── data
│   │   │   └── img
│   │   ├── mx
│   │   │   ├── data
│   │   │   └── img
│   │   ├── nl
│   │   │   ├── data
│   │   │   └── img
│   │   ├── no
│   │   │   ├── data
│   │   │   └── img
│   │   ├── pl
│   │   │   ├── data
│   │   │   └── img
│   │   ├── pt
│   │   │   ├── data
│   │   │   └── img
│   │   ├── qc
│   │   │   ├── data
│   │   │   └── img
│   │   ├── ro
│   │   │   ├── data
│   │   │   └── img
│   │   ├── ru
│   │   │   ├── data
│   │   │   └── img
│   │   ├── si
│   │   │   ├── data
│   │   │   └── img
│   │   ├── sk
│   │   │   ├── data
│   │   │   └── img
│   │   ├── sr
│   │   │   ├── data
│   │   │   └── img
│   │   ├── sv
│   │   │   ├── data
│   │   │   └── img
│   │   ├── tr
│   │   │   └── img
│   │   ├── tw
│   │   │   ├── data
│   │   │   └── img
│   │   ├── uk
│   │   │   ├── data
│   │   │   └── img
│   │   ├── vn
│   │   │   ├── data
│   │   │   └── img
│   │   └── zh
│   │       ├── data
│   │       └── img
│   ├── sandbox
│   ├── theme
│   │   ├── img
│   │   ├── js
│   │   └── views
│   └── upgrade
│       ├── classes
│       ├── php
│       └── sql
├── js
│   ├── admin
│   ├── cropper
│   ├── jquery
│   │   ├── plugins
│   │   │   ├── ajaxfileupload
│   │   │   ├── alerts
│   │   │   │   └── images
│   │   │   ├── autocomplete
│   │   │   ├── bxslider
│   │   │   │   └── images
│   │   │   ├── chosen
│   │   │   ├── cluetip
│   │   │   ├── fancybox
│   │   │   ├── footable
│   │   │   ├── footable-sort
│   │   │   ├── growl
│   │   │   ├── imgareaselect
│   │   │   ├── jgrowl
│   │   │   ├── jqzoom
│   │   │   ├── jstree
│   │   │   │   └── themes
│   │   │   │       ├── apple
│   │   │   │       ├── classic
│   │   │   │       ├── default
│   │   │   │       └── default-rtl
│   │   │   ├── select2
│   │   │   ├── smartWizard
│   │   │   ├── tabpane
│   │   │   ├── thickbox
│   │   │   ├── timepicker
│   │   │   ├── treeview-categories
│   │   │   │   └── images
│   │   │   └── validate
│   │   │       └── localization
│   │   └── ui
│   │       ├── i18n
│   │       └── themes
│   │           ├── base
│   │           │   ├── images
│   │           │   └── minified
│   │           │       └── images
│   │           └── ui-lightness
│   │               ├── images
│   │               └── minified
│   │                   └── images
│   ├── tiny_mce
│   │   ├── langs
│   │   ├── plugins
│   │   │   ├── advlist
│   │   │   ├── align
│   │   │   ├── anchor
│   │   │   ├── autolink
│   │   │   ├── autoresize
│   │   │   ├── autosave
│   │   │   ├── bbcode
│   │   │   ├── charmap
│   │   │   ├── code
│   │   │   ├── colorpicker
│   │   │   ├── contextmenu
│   │   │   ├── directionality
│   │   │   ├── emoticons
│   │   │   │   └── img
│   │   │   ├── example
│   │   │   ├── example_dependency
│   │   │   ├── fullpage
│   │   │   ├── fullscreen
│   │   │   ├── hr
│   │   │   ├── image
│   │   │   ├── importcss
│   │   │   ├── insertdatetime
│   │   │   ├── layer
│   │   │   ├── legacyoutput
│   │   │   ├── link
│   │   │   ├── lists
│   │   │   ├── media
│   │   │   ├── nonbreaking
│   │   │   ├── noneditable
│   │   │   ├── pagebreak
│   │   │   ├── paste
│   │   │   ├── placeholder
│   │   │   ├── preview
│   │   │   ├── print
│   │   │   ├── save
│   │   │   ├── searchreplace
│   │   │   ├── tabfocus
│   │   │   ├── table
│   │   │   ├── template
│   │   │   ├── textcolor
│   │   │   ├── visualblocks
│   │   │   │   └── css
│   │   │   ├── visualchars
│   │   │   └── wordcount
│   │   ├── skins
│   │   │   └── prestashop
│   │   └── themes
│   │       └── modern
│   └── vendor
├── localization
│   └── CLDR
│       └── core
│           └── common
│               ├── main
│               └── supplemental
├── mails
│   ├── en
│   └── themes
│       ├── classic
│       │   ├── assets
│       │   ├── components
│       │   ├── core
│       │   └── modules
│       │       ├── followup
│       │       ├── ps_emailalerts
│       │       ├── ps_emailsubscription
│       │       └── referralprogram
│       └── modern
│           ├── assets
│           ├── components
│           ├── core
│           └── modules
│               ├── followup
│               ├── ps_emailalerts
│               ├── ps_emailsubscription
│               └── referralprogram
├── modules
├── override
│   ├── classes
│   │   ├── assets
│   │   ├── cache
│   │   ├── checkout
│   │   ├── container
│   │   ├── controller
│   │   ├── db
│   │   ├── exception
│   │   ├── form
│   │   ├── helper
│   │   ├── lang
│   │   ├── log
│   │   ├── module
│   │   ├── order
│   │   ├── pdf
│   │   ├── range
│   │   ├── shop
│   │   ├── Smarty
│   │   ├── stock
│   │   ├── tax
│   │   ├── tree
│   │   └── webservice
│   ├── controllers
│   │   ├── admin
│   │   │   └── templates
│   │   └── front
│   └── modules
├── pdf
├── src
│   ├── Adapter
│   │   ├── Addons
│   │   ├── Address
│   │   │   ├── CommandHandler
│   │   │   └── QueryHandler
│   │   ├── Admin
│   │   ├── Assets
│   │   ├── Attribute
│   │   ├── Backup
│   │   ├── BestSales
│   │   ├── Cache
│   │   │   └── Clearer
│   │   ├── Carrier
│   │   ├── Cart
│   │   │   ├── CommandHandler
│   │   │   └── QueryHandler
│   │   ├── Category
│   │   │   ├── CommandHandler
│   │   │   └── QueryHandler
│   │   ├── CMS
│   │   │   ├── Page
│   │   │   │   ├── CommandHandler
│   │   │   │   └── QueryHandler
│   │   │   └── PageCategory
│   │   │       ├── CommandHandler
│   │   │       └── QueryHandler
│   │   ├── Configuration
│   │   ├── Contact
│   │   │   ├── CommandHandler
│   │   │   └── QueryHandler
│   │   ├── Container
│   │   ├── Converter
│   │   ├── Country
│   │   ├── Currency
│   │   │   ├── CommandHandler
│   │   │   └── QueryHandler
│   │   ├── Customer
│   │   │   ├── CommandHandler
│   │   │   └── QueryHandler
│   │   ├── Debug
│   │   ├── Domain
│   │   ├── Email
│   │   ├── Employee
│   │   ├── Feature
│   │   ├── File
│   │   ├── Form
│   │   │   └── ChoiceProvider
│   │   ├── Geolocation
│   │   ├── Grid
│   │   │   ├── Action
│   │   │   │   └── Row
│   │   │   │       └── AccessibilityChecker
│   │   │   └── Search
│   │   │       └── Factory
│   │   ├── Group
│   │   │   └── Provider
│   │   ├── Hook
│   │   ├── Hosting
│   │   ├── Image
│   │   │   └── Uploader
│   │   ├── Import
│   │   │   └── Handler
│   │   ├── Invoice
│   │   ├── Kpi
│   │   ├── Language
│   │   │   ├── CommandHandler
│   │   │   ├── Pack
│   │   │   ├── QueryHandler
│   │   │   └── RTL
│   │   ├── Localization
│   │   ├── Mail
│   │   ├── MailTemplate
│   │   ├── Manufacturer
│   │   │   ├── CommandHandler
│   │   │   └── QueryHandler
│   │   ├── Media
│   │   ├── Meta
│   │   │   ├── CommandHandler
│   │   │   └── QueryHandler
│   │   ├── Module
│   │   │   ├── Configuration
│   │   │   ├── Presenter
│   │   │   ├── PrestaTrust
│   │   │   └── Tab
│   │   ├── NewProducts
│   │   ├── OptionalFeatures
│   │   ├── Order
│   │   │   ├── CommandHandler
│   │   │   └── Delivery
│   │   ├── OrderState
│   │   ├── Pack
│   │   ├── PDF
│   │   ├── Preferences
│   │   ├── Presenter
│   │   │   ├── Cart
│   │   │   ├── Module
│   │   │   ├── Object
│   │   │   ├── Order
│   │   │   └── Product
│   │   ├── PricesDrop
│   │   ├── Product
│   │   ├── Profile
│   │   │   ├── CommandHandler
│   │   │   ├── Employee
│   │   │   │   ├── CommandHandler
│   │   │   │   └── QueryHandler
│   │   │   └── QueryHandler
│   │   ├── Requirement
│   │   ├── Routes
│   │   ├── Search
│   │   ├── Security
│   │   ├── Shop
│   │   │   ├── CommandHandler
│   │   │   ├── QueryHandler
│   │   │   └── Url
│   │   ├── Smarty
│   │   ├── SqlManager
│   │   │   ├── CommandHandler
│   │   │   └── QueryHandler
│   │   ├── Supplier
│   │   │   └── CommandHandler
│   │   ├── Support
│   │   ├── System
│   │   ├── Tab
│   │   ├── Tax
│   │   │   ├── CommandHandler
│   │   │   ├── Ecotax
│   │   │   └── QueryHandler
│   │   ├── Theme
│   │   ├── Translations
│   │   ├── Upload
│   │   ├── Warehouse
│   │   └── Webservice
│   │       ├── CommandHandler
│   │       └── QueryHandler
│   ├── Core
│   │   ├── Addon
│   │   │   ├── Module
│   │   │   │   └── Exception
│   │   │   └── Theme
│   │   │       └── Exception
│   │   ├── B2b
│   │   ├── Backup
│   │   │   ├── Comparator
│   │   │   ├── Configuration
│   │   │   ├── Exception
│   │   │   ├── Listing
│   │   │   ├── Manager
│   │   │   └── Repository
│   │   ├── Cache
│   │   │   └── Clearer
│   │   ├── Cart
│   │   ├── Checkout
│   │   ├── CMS
│   │   ├── CommandBus
│   │   │   └── Parser
│   │   ├── Configuration
│   │   ├── ConstraintValidator
│   │   │   └── Constraints
│   │   ├── Crypto
│   │   ├── Currency
│   │   ├── Data
│   │   │   └── Layer
│   │   ├── Domain
│   │   │   ├── Address
│   │   │   │   ├── Command
│   │   │   │   ├── CommandHandler
│   │   │   │   ├── Exception
│   │   │   │   ├── Query
│   │   │   │   ├── QueryHandler
│   │   │   │   ├── QueryResult
│   │   │   │   └── ValueObject
│   │   │   ├── Cart
│   │   │   │   ├── Command
│   │   │   │   ├── CommandHandler
│   │   │   │   ├── Exception
│   │   │   │   ├── Query
│   │   │   │   ├── QueryHandler
│   │   │   │   ├── QueryResult
│   │   │   │   └── ValueObject
│   │   │   ├── CartRule
│   │   │   │   └── ValueObject
│   │   │   ├── Category
│   │   │   │   ├── Command
│   │   │   │   ├── CommandHandler
│   │   │   │   ├── Exception
│   │   │   │   ├── Query
│   │   │   │   ├── QueryHandler
│   │   │   │   ├── QueryResult
│   │   │   │   └── ValueObject
│   │   │   ├── CmsPage
│   │   │   │   ├── Command
│   │   │   │   ├── CommandHandler
│   │   │   │   ├── Exception
│   │   │   │   ├── Query
│   │   │   │   ├── QueryHandler
│   │   │   │   ├── QueryResult
│   │   │   │   └── ValueObject
│   │   │   ├── CmsPageCategory
│   │   │   │   ├── Command
│   │   │   │   ├── CommandHandler
│   │   │   │   ├── Exception
│   │   │   │   ├── Query
│   │   │   │   ├── QueryHandler
│   │   │   │   ├── QueryResult
│   │   │   │   └── ValueObject
│   │   │   ├── Contact
│   │   │   │   ├── Command
│   │   │   │   ├── CommandHandler
│   │   │   │   ├── Exception
│   │   │   │   ├── Query
│   │   │   │   ├── QueryHandler
│   │   │   │   ├── QueryResult
│   │   │   │   └── ValueObject
│   │   │   ├── Currency
│   │   │   │   ├── Command
│   │   │   │   ├── CommandHandler
│   │   │   │   ├── Exception
│   │   │   │   ├── Query
│   │   │   │   ├── QueryHandler
│   │   │   │   ├── QueryResult
│   │   │   │   └── ValueObject
│   │   │   ├── Customer
│   │   │   │   ├── Command
│   │   │   │   ├── CommandHandler
│   │   │   │   ├── Exception
│   │   │   │   ├── Query
│   │   │   │   ├── QueryHandler
│   │   │   │   ├── QueryResult
│   │   │   │   │   └── Viewable
│   │   │   │   └── ValueObject
│   │   │   ├── Employee
│   │   │   │   ├── Command
│   │   │   │   ├── CommandHandler
│   │   │   │   ├── Exception
│   │   │   │   ├── Query
│   │   │   │   ├── QueryHandler
│   │   │   │   ├── QueryResult
│   │   │   │   └── ValueObject
│   │   │   ├── Exception
│   │   │   ├── Language
│   │   │   │   ├── Command
│   │   │   │   ├── CommandHandler
│   │   │   │   ├── Exception
│   │   │   │   ├── Query
│   │   │   │   ├── QueryHandler
│   │   │   │   ├── QueryResult
│   │   │   │   └── ValueObject
│   │   │   ├── MailTemplate
│   │   │   │   ├── Command
│   │   │   │   └── CommandHandler
│   │   │   ├── Manufacturer
│   │   │   │   ├── Command
│   │   │   │   ├── CommandHandler
│   │   │   │   ├── Exception
│   │   │   │   ├── Query
│   │   │   │   ├── QueryHandler
│   │   │   │   ├── QueryResult
│   │   │   │   └── ValueObject
│   │   │   ├── Meta
│   │   │   │   ├── Command
│   │   │   │   ├── CommandHandler
│   │   │   │   ├── Exception
│   │   │   │   ├── Query
│   │   │   │   ├── QueryHandler
│   │   │   │   ├── QueryResult
│   │   │   │   └── ValueObject
│   │   │   ├── Order
│   │   │   │   ├── Command
│   │   │   │   ├── CommandHandler
│   │   │   │   ├── Exception
│   │   │   │   └── ValueObject
│   │   │   ├── Product
│   │   │   │   ├── Exception
│   │   │   │   └── ValueObject
│   │   │   ├── Profile
│   │   │   │   ├── Command
│   │   │   │   ├── CommandHandler
│   │   │   │   ├── Exception
│   │   │   │   ├── Query
│   │   │   │   ├── QueryHandler
│   │   │   │   ├── QueryResult
│   │   │   │   └── ValueObject
│   │   │   ├── Shop
│   │   │   │   ├── Command
│   │   │   │   ├── CommandHandler
│   │   │   │   ├── Exception
│   │   │   │   ├── Query
│   │   │   │   ├── QueryHandler
│   │   │   │   ├── QueryResult
│   │   │   │   └── ValueObject
│   │   │   ├── ShowcaseCard
│   │   │   │   ├── Command
│   │   │   │   ├── CommandHandler
│   │   │   │   ├── Exception
│   │   │   │   ├── Query
│   │   │   │   ├── QueryHandler
│   │   │   │   └── ValueObject
│   │   │   ├── SqlManagement
│   │   │   │   ├── Command
│   │   │   │   ├── CommandHandler
│   │   │   │   ├── Exception
│   │   │   │   ├── Query
│   │   │   │   ├── QueryHandler
│   │   │   │   └── ValueObject
│   │   │   ├── Supplier
│   │   │   │   ├── Command
│   │   │   │   ├── CommandHandler
│   │   │   │   ├── Exception
│   │   │   │   └── ValueObject
│   │   │   ├── Tax
│   │   │   │   ├── Command
│   │   │   │   ├── CommandHandler
│   │   │   │   ├── Exception
│   │   │   │   ├── Query
│   │   │   │   ├── QueryHandler
│   │   │   │   ├── QueryResult
│   │   │   │   └── ValueObject
│   │   │   ├── Theme
│   │   │   │   ├── Command
│   │   │   │   ├── CommandHandler
│   │   │   │   ├── Exception
│   │   │   │   └── ValueObject
│   │   │   ├── ValueObject
│   │   │   └── Webservice
│   │   │       ├── Command
│   │   │       ├── CommandHandler
│   │   │       ├── Exception
│   │   │       ├── Query
│   │   │       ├── QueryHandler
│   │   │       ├── QueryResult
│   │   │       └── ValueObject
│   │   ├── Email
│   │   ├── Employee
│   │   │   └── Access
│   │   ├── Encoding
│   │   ├── Exception
│   │   ├── Export
│   │   │   ├── Data
│   │   │   ├── Exception
│   │   │   └── FileWriter
│   │   ├── Feature
│   │   ├── File
│   │   │   └── Converter
│   │   ├── Filter
│   │   │   └── FrontEndObject
│   │   ├── Form
│   │   │   ├── ChoiceProvider
│   │   │   ├── DTO
│   │   │   └── IdentifiableObject
│   │   │       ├── Builder
│   │   │       ├── DataHandler
│   │   │       ├── DataProvider
│   │   │       └── Handler
│   │   ├── Foundation
│   │   │   ├── Database
│   │   │   │   └── EntityManager
│   │   │   ├── Exception
│   │   │   ├── Filesystem
│   │   │   ├── IoC
│   │   │   └── Templating
│   │   ├── Geolocation
│   │   │   └── GeoLite
│   │   ├── Grid
│   │   │   ├── Action
│   │   │   │   ├── Bulk
│   │   │   │   │   └── Type
│   │   │   │   │       ├── Catalog
│   │   │   │   │       │   └── Category
│   │   │   │   │       └── Customer
│   │   │   │   ├── Row
│   │   │   │   │   ├── AccessibilityChecker
│   │   │   │   │   └── Type
│   │   │   │   │       ├── Category
│   │   │   │   │       └── Customer
│   │   │   │   └── Type
│   │   │   ├── Collection
│   │   │   ├── Column
│   │   │   │   └── Type
│   │   │   │       ├── Category
│   │   │   │       ├── Common
│   │   │   │       ├── Employee
│   │   │   │       └── Status
│   │   │   ├── Data
│   │   │   │   └── Factory
│   │   │   ├── Definition
│   │   │   │   └── Factory
│   │   │   ├── Exception
│   │   │   ├── Factory
│   │   │   ├── Filter
│   │   │   ├── Position
│   │   │   │   ├── Exception
│   │   │   │   └── UpdateHandler
│   │   │   ├── Presenter
│   │   │   ├── Query
│   │   │   ├── Record
│   │   │   └── Search
│   │   │       └── Factory
│   │   ├── Group
│   │   │   └── Provider
│   │   ├── Hook
│   │   │   ├── Generator
│   │   │   └── Provider
│   │   ├── Image
│   │   │   ├── Deleter
│   │   │   ├── Parser
│   │   │   └── Uploader
│   │   │       └── Exception
│   │   ├── Import
│   │   │   ├── Access
│   │   │   ├── Configuration
│   │   │   ├── Entity
│   │   │   ├── EntityField
│   │   │   │   └── Provider
│   │   │   ├── Exception
│   │   │   ├── File
│   │   │   │   ├── DataCell
│   │   │   │   └── DataRow
│   │   │   │       └── Factory
│   │   │   ├── Handler
│   │   │   ├── Sample
│   │   │   └── Validator
│   │   ├── Kpi
│   │   │   ├── Exception
│   │   │   └── Row
│   │   ├── Language
│   │   │   ├── Copier
│   │   │   ├── Pack
│   │   │   │   ├── Import
│   │   │   │   └── Loader
│   │   │   └── RTL
│   │   ├── Localization
│   │   │   ├── CLDR
│   │   │   │   └── DataLayer
│   │   │   ├── Currency
│   │   │   │   └── DataLayer
│   │   │   ├── Exception
│   │   │   ├── Locale
│   │   │   ├── Number
│   │   │   ├── Pack
│   │   │   │   ├── Factory
│   │   │   │   ├── Import
│   │   │   │   └── Loader
│   │   │   ├── RTL
│   │   │   │   └── Exception
│   │   │   └── Specification
│   │   ├── MailTemplate
│   │   │   ├── Layout
│   │   │   └── Transformation
│   │   ├── Meta
│   │   ├── Module
│   │   │   ├── Configuration
│   │   │   └── DataProvider
│   │   ├── Multistore
│   │   ├── Order
│   │   ├── Payment
│   │   ├── PDF
│   │   ├── Product
│   │   │   └── Search
│   │   │       └── Exception
│   │   ├── Proxy
│   │   ├── Repository
│   │   ├── Search
│   │   │   ├── Builder
│   │   │   └── Filters
│   │   ├── Shop
│   │   │   └── Url
│   │   ├── SqlManager
│   │   │   ├── Configuration
│   │   │   └── Exporter
│   │   ├── Stock
│   │   ├── Support
│   │   ├── Tax
│   │   │   └── Ecotax
│   │   ├── Team
│   │   │   └── Employee
│   │   │       └── Configuration
│   │   ├── Translation
│   │   │   └── Locale
│   │   ├── Util
│   │   │   ├── DateTime
│   │   │   ├── File
│   │   │   ├── HelperCard
│   │   │   ├── String
│   │   │   └── Url
│   │   ├── Validation
│   │   └── Webservice
│   └── PrestaShopBundle
│       ├── Api
│       │   └── Stock
│       ├── Cache
│       ├── Command
│       ├── Component
│       ├── Controller
│       │   ├── Admin
│       │   │   ├── Configure
│       │   │   │   ├── AdvancedParameters
│       │   │   │   └── ShopParameters
│       │   │   ├── Improve
│       │   │   │   ├── Design
│       │   │   │   ├── International
│       │   │   │   ├── Modules
│       │   │   │   ├── Payment
│       │   │   │   └── Shipping
│       │   │   └── Sell
│       │   │       ├── Catalog
│       │   │       ├── Customer
│       │   │       └── Order
│       │   ├── Api
│       │   │   └── Improve
│       │   │       └── Design
│       │   └── ArgumentResolver
│       ├── DataCollector
│       ├── DependencyInjection
│       │   └── Compiler
│       ├── Entity
│       │   └── Repository
│       ├── Event
│       │   └── Dispatcher
│       ├── EventListener
│       ├── Exception
│       ├── Form
│       │   ├── Admin
│       │   │   ├── AdvancedParameters
│       │   │   │   └── Performance
│       │   │   ├── Catalog
│       │   │   │   └── Category
│       │   │   ├── Category
│       │   │   ├── Configure
│       │   │   │   ├── AdvancedParameters
│       │   │   │   │   ├── Administration
│       │   │   │   │   ├── Backup
│       │   │   │   │   ├── Email
│       │   │   │   │   ├── Employee
│       │   │   │   │   ├── Import
│       │   │   │   │   ├── Logs
│       │   │   │   │   ├── Profile
│       │   │   │   │   ├── RequestSql
│       │   │   │   │   └── Webservice
│       │   │   │   └── ShopParameters
│       │   │   │       ├── Contact
│       │   │   │       ├── CustomerPreferences
│       │   │   │       ├── General
│       │   │   │       ├── OrderPreferences
│       │   │   │       ├── ProductPreferences
│       │   │   │       └── TrafficSeo
│       │   │   │           └── Meta
│       │   │   ├── Feature
│       │   │   ├── Improve
│       │   │   │   ├── Design
│       │   │   │   │   ├── MailTheme
│       │   │   │   │   ├── Pages
│       │   │   │   │   └── Theme
│       │   │   │   ├── International
│       │   │   │   │   ├── Currencies
│       │   │   │   │   ├── Geolocation
│       │   │   │   │   ├── Language
│       │   │   │   │   ├── Localization
│       │   │   │   │   ├── Tax
│       │   │   │   │   └── Translations
│       │   │   │   ├── Payment
│       │   │   │   │   └── Preferences
│       │   │   │   └── Shipping
│       │   │   │       └── Preferences
│       │   │   ├── Product
│       │   │   ├── Sell
│       │   │   │   ├── Address
│       │   │   │   ├── Category
│       │   │   │   ├── Customer
│       │   │   │   ├── Manufacturer
│       │   │   │   └── Order
│       │   │   │       ├── Delivery
│       │   │   │       └── Invoices
│       │   │   └── Type
│       │   │       ├── Common
│       │   │       │   └── Team
│       │   │       └── Material
│       │   ├── DataTransformer
│       │   └── Validator
│       │       └── Constraints
│       ├── Install
│       ├── Kernel
│       ├── Model
│       │   └── Product
│       ├── Resources
│       │   ├── config
│       │   │   ├── doctrine
│       │   │   ├── routing
│       │   │   │   ├── admin
│       │   │   │   │   ├── configure
│       │   │   │   │   │   ├── advanced_parameters
│       │   │   │   │   │   └── shop_parameters
│       │   │   │   │   ├── improve
│       │   │   │   │   │   ├── design
│       │   │   │   │   │   ├── international
│       │   │   │   │   │   ├── modules
│       │   │   │   │   │   ├── payment
│       │   │   │   │   │   └── shipping
│       │   │   │   │   └── sell
│       │   │   │   │       ├── catalog
│       │   │   │   │       │   └── products
│       │   │   │   │       ├── customer
│       │   │   │   │       └── orders
│       │   │   │   └── api
│       │   │   │       └── improve
│       │   │   │           └── design
│       │   │   └── services
│       │   │       ├── adapter
│       │   │       │   └── pdf
│       │   │       ├── bundle
│       │   │       │   └── form
│       │   │       │       └── form_type
│       │   │       └── core
│       │   │           ├── domain
│       │   │           ├── form
│       │   │           ├── grid
│       │   │           └── util
│       │   └── views
│       │       └── Admin
│       │           ├── Category
│       │           ├── Common
│       │           │   ├── Grid
│       │           │   │   ├── Actions
│       │           │   │   │   ├── Bulk
│       │           │   │   │   ├── Grid
│       │           │   │   │   └── Row
│       │           │   │   ├── Blocks
│       │           │   │   │   ├── EmptyState
│       │           │   │   │   └── Table
│       │           │   │   └── Columns
│       │           │   │       ├── Content
│       │           │   │       └── Header
│       │           │   │           └── Content
│       │           │   ├── Kpi
│       │           │   └── _partials
│       │           ├── Configure
│       │           │   ├── AdvancedParameters
│       │           │   │   ├── Backup
│       │           │   │   │   └── Blocks
│       │           │   │   ├── Blocks
│       │           │   │   ├── Email
│       │           │   │   │   └── Blocks
│       │           │   │   ├── Employee
│       │           │   │   │   └── Blocks
│       │           │   │   ├── ImportDataConfiguration
│       │           │   │   │   └── Blocks
│       │           │   │   ├── ImportPage
│       │           │   │   ├── LogsPage
│       │           │   │   │   └── Blocks
│       │           │   │   ├── Profiles
│       │           │   │   │   └── Blocks
│       │           │   │   ├── RequestSql
│       │           │   │   │   └── Blocks
│       │           │   │   └── Webservice
│       │           │   │       └── Blocks
│       │           │   └── ShopParameters
│       │           │       ├── Blocks
│       │           │       ├── Contact
│       │           │       │   └── Contacts
│       │           │       │       └── Blocks
│       │           │       ├── OrderPreferences
│       │           │       │   └── Blocks
│       │           │       └── TrafficSeo
│       │           │           └── Meta
│       │           │               └── Blocks
│       │           ├── Helpers
│       │           ├── Improve
│       │           │   ├── Design
│       │           │   │   ├── Cms
│       │           │   │   │   └── Blocks
│       │           │   │   ├── MailTheme
│       │           │   │   │   └── Blocks
│       │           │   │   ├── Theme
│       │           │   │   │   └── Blocks
│       │           │   │   │       └── Partials
│       │           │   │   └── ThemesCatalogPage
│       │           │   ├── International
│       │           │   │   ├── Currency
│       │           │   │   │   └── Blocks
│       │           │   │   ├── Geolocation
│       │           │   │   │   └── Blocks
│       │           │   │   ├── Language
│       │           │   │   │   └── Blocks
│       │           │   │   ├── Localization
│       │           │   │   │   └── Blocks
│       │           │   │   ├── Tax
│       │           │   │   │   └── Blocks
│       │           │   │   └── Translations
│       │           │   │       └── Blocks
│       │           │   ├── Module
│       │           │   ├── Payment
│       │           │   │   ├── PaymentMethods
│       │           │   │   │   └── Blocks
│       │           │   │   └── Preferences
│       │           │   │       └── Blocks
│       │           │   └── Shipping
│       │           │       └── Preferences
│       │           │           └── Blocks
│       │           ├── Module
│       │           │   └── Includes
│       │           ├── Product
│       │           │   ├── CatalogPage
│       │           │   │   ├── Blocks
│       │           │   │   ├── Forms
│       │           │   │   └── Lists
│       │           │   ├── ProductPage
│       │           │   │   ├── Blocks
│       │           │   │   ├── Forms
│       │           │   │   └── Panels
│       │           │   └── Themes
│       │           ├── ProductImage
│       │           ├── Security
│       │           ├── Sell
│       │           │   ├── Catalog
│       │           │   │   ├── Categories
│       │           │   │   │   └── Blocks
│       │           │   │   ├── Manufacturer
│       │           │   │   │   ├── Address
│       │           │   │   │   │   └── Blocks
│       │           │   │   │   └── Blocks
│       │           │   │   │       └── View
│       │           │   │   └── Suppliers
│       │           │   ├── Customer
│       │           │   │   └── Blocks
│       │           │   │       ├── Index
│       │           │   │       └── View
│       │           │   └── Order
│       │           │       ├── Delivery
│       │           │       └── Invoices
│       │           │           └── Blocks
│       │           ├── Stock
│       │           ├── Translations
│       │           ├── TwigTemplateForm
│       │           └── WebProfiler
│       ├── Routing
│       │   ├── Converter
│       │   │   └── Exception
│       │   └── Linter
│       │       └── Exception
│       ├── Security
│       │   ├── Admin
│       │   ├── Annotation
│       │   ├── Role
│       │   └── Voter
│       ├── Service
│       │   ├── Cache
│       │   ├── Command
│       │   ├── Database
│       │   ├── DataProvider
│       │   │   ├── Admin
│       │   │   └── Marketplace
│       │   ├── DataUpdater
│       │   │   └── Admin
│       │   ├── Grid
│       │   ├── Hook
│       │   ├── Log
│       │   ├── Routing
│       │   └── TransitionalBehavior
│       ├── Translation
│       │   ├── Api
│       │   ├── Constraints
│       │   ├── Exception
│       │   ├── Exporter
│       │   ├── Extractor
│       │   ├── Factory
│       │   ├── Loader
│       │   ├── Provider
│       │   └── View
│       ├── Twig
│       │   ├── Extension
│       │   └── Locator
│       └── Utils
├── tests
│   ├── E2E
│   │   ├── bin
│   │   ├── email_sender
│   │   ├── scripts
│   │   └── test
│   │       ├── campaigns
│   │       │   ├── boom
│   │       │   ├── broken_tests
│   │       │   │   ├── 01_orders
│   │       │   │   ├── 02_product
│   │       │   │   ├── 03_category
│   │       │   │   ├── 05_feature
│   │       │   │   ├── 10_module
│   │       │   │   ├── 11_international
│   │       │   │   │   └── 1_localization
│   │       │   │   │       └── 1_localization
│   │       │   │   ├── 12_shop_parameters
│   │       │   │   │   └── 5_contact
│   │       │   │   ├── 15_design
│   │       │   │   │   ├── 2_pages
│   │       │   │   │   └── 3_link_widget
│   │       │   │   ├── 16_file
│   │       │   │   ├── installation
│   │       │   │   └── install_upgrade
│   │       │   ├── common_scenarios
│   │       │   ├── full
│   │       │   │   ├── 01_orders
│   │       │   │   ├── 02_product
│   │       │   │   ├── 03_category
│   │       │   │   ├── 04_attribute
│   │       │   │   ├── 05_feature
│   │       │   │   ├── 06_catalogbulkaction
│   │       │   │   ├── 07_manufacturer
│   │       │   │   ├── 08_stocks
│   │       │   │   ├── 09_customer
│   │       │   │   │   ├── addresses
│   │       │   │   │   └── customer_settings
│   │       │   │   ├── 10_module
│   │       │   │   ├── 11_international
│   │       │   │   │   ├── 1_localization
│   │       │   │   │   ├── 2_locations
│   │       │   │   │   └── 3_taxes
│   │       │   │   ├── 12_shop_parameters
│   │       │   │   ├── 13_employee
│   │       │   │   ├── 14_discount
│   │       │   │   ├── 15_design
│   │       │   │   │   ├── 1_theme_catalog
│   │       │   │   │   └── 4_positions
│   │       │   │   └── 16_file
│   │       │   ├── high
│   │       │   │   ├── 01_orders
│   │       │   │   ├── 02_product
│   │       │   │   ├── 08_stocks
│   │       │   │   └── 09_customer
│   │       │   ├── install_upgrade
│   │       │   ├── regular
│   │       │   └── selenium
│   │       ├── clients
│   │       │   └── product
│   │       ├── datas
│   │       ├── screenshots
│   │       └── selectors
│   │           ├── BO
│   │           │   ├── advancedParameters
│   │           │   ├── catalogpage
│   │           │   │   ├── Manufacturers
│   │           │   │   └── stocksubmenu
│   │           │   ├── customers
│   │           │   ├── customerService
│   │           │   ├── design
│   │           │   ├── international
│   │           │   └── shopParameters
│   │           └── FO
│   ├── Integration
│   │   ├── Adapter
│   │   ├── Behaviour
│   │   │   └── Features
│   │   │       ├── Context
│   │   │       │   ├── Configuration
│   │   │       │   ├── Domain
│   │   │       │   └── Util
│   │   │       └── Scenario
│   │   │           ├── Cart
│   │   │           │   ├── Adding
│   │   │           │   │   ├── CartRule
│   │   │           │   │   └── Product
│   │   │           │   ├── Calculation
│   │   │           │   │   ├── Carrier
│   │   │           │   │   ├── CartRule
│   │   │           │   │   ├── Currency
│   │   │           │   │   ├── Product
│   │   │           │   │   ├── RoundingMode
│   │   │           │   │   ├── RoundingType
│   │   │           │   │   ├── SpecificPriceRule
│   │   │           │   │   └── Taxes
│   │   │           │   └── CartToOrder
│   │   │           ├── Customer
│   │   │           ├── Database
│   │   │           └── Order
│   │   ├── Core
│   │   │   └── MailTemplate
│   │   └── PrestaShopBundle
│   │       ├── Command
│   │       ├── Entity
│   │       │   └── Repository
│   │       ├── Routing
│   │       │   ├── Converter
│   │       │   └── Linter
│   │       └── Translation
│   │           ├── Extractor
│   │           ├── Loader
│   │           └── Provider
│   ├── Resources
│   │   ├── Controller
│   │   ├── modules
│   │   │   ├── dummy_payment
│   │   │   ├── ps_banner
│   │   │   │   ├── config
│   │   │   │   │   ├── admin
│   │   │   │   │   └── front
│   │   │   │   ├── src
│   │   │   │   │   ├── Entity
│   │   │   │   │   └── Repository
│   │   │   │   └── vendor
│   │   │   │       └── composer
│   │   │   └── translation_test
│   │   │       ├── config
│   │   │       ├── controllers
│   │   │       │   └── admin
│   │   │       ├── src
│   │   │       │   └── Controller
│   │   │       │       └── Admin
│   │   │       ├── translations
│   │   │       ├── vendor
│   │   │       │   └── composer
│   │   │       └── views
│   │   │           └── templates
│   │   │               └── admin
│   │   ├── themes
│   │   │   └── fakeThemeForTranslations
│   │   │       ├── assets
│   │   │       │   ├── css
│   │   │       │   └── js
│   │   │       ├── config
│   │   │       ├── templates
│   │   │       │   ├── catalog
│   │   │       │   │   └── _partials
│   │   │       │   │       └── miniatures
│   │   │       │   ├── checkout
│   │   │       │   └── _partials
│   │   │       └── translations
│   │   │           └── en-US
│   │   └── translations
│   │       ├── default
│   │       └── fr-FR
│   ├── Selenium
│   │   ├── commands
│   │   ├── errorDumps
│   │   ├── errorShots
│   │   ├── helpers
│   │   └── specs
│   │       └── customer
│   ├── TestCase
│   └── Unit
│       ├── Adapter
│       │   └── MailTemplate
│       ├── Core
│       │   ├── Checkout
│       │   ├── CommandBus
│       │   │   └── Parser
│       │   ├── ConstraintValidator
│       │   ├── Crypto
│       │   ├── Data
│       │   ├── Domain
│       │   │   ├── CmsPageCategory
│       │   │   │   └── Command
│       │   │   ├── Contact
│       │   │   │   └── Command
│       │   │   ├── Currency
│       │   │   │   └── ValueObject
│       │   │   ├── Customer
│       │   │   │   └── ValueObject
│       │   │   ├── Language
│       │   │   │   └── ValueObject
│       │   │   ├── Meta
│       │   │   └── ValueObject
│       │   ├── Form
│       │   │   └── IdentifiableObject
│       │   │       ├── Builder
│       │   │       ├── DataProvider
│       │   │       └── Handler
│       │   ├── Foundation
│       │   ├── Hook
│       │   │   └── Generator
│       │   ├── Image
│       │   │   ├── Deleter
│       │   │   └── Parser
│       │   ├── Kpi
│       │   ├── Language
│       │   ├── MailTemplate
│       │   ├── Product
│       │   │   └── Search
│       │   ├── Search
│       │   │   └── Builder
│       │   ├── Util
│       │   │   ├── HelperCard
│       │   │   ├── String
│       │   │   └── Url
│       │   └── Webservice
│       ├── PrestaShopBundle
│       │   ├── Cache
│       │   ├── Controller
│       │   │   └── ArgumentResolver
│       │   ├── Entity
│       │   │   └── Repository
│       │   ├── EventListener
│       │   ├── Form
│       │   │   └── DataTransformer
│       │   ├── Routing
│       │   │   ├── Converter
│       │   │   └── Linter
│       │   ├── Service
│       │   │   └── Hook
│       │   ├── Translation
│       │   │   └── Loader
│       │   └── Twig
│       │       ├── Extension
│       │       ├── Fixtures
│       │       │   └── modules
│       │       └── Locator
│       └── Resources
│           ├── assets
│           │   └── css
│           └── mails
│               ├── html
│               ├── templates
│               └── txt
├── tests-legacy
│   ├── Endpoints
│   ├── Integration
│   │   ├── Adapter
│   │   ├── classes
│   │   │   ├── db
│   │   │   └── module
│   │   ├── Core
│   │   │   ├── Foundation
│   │   │   │   └── Entity
│   │   │   ├── Localization
│   │   │   └── Module
│   │   └── PrestaShopBundle
│   │       ├── Controller
│   │       │   ├── Admin
│   │       │   │   ├── Improve
│   │       │   │   │   ├── Design
│   │       │   │   │   └── International
│   │       │   │   └── Sell
│   │       │   │       └── Order
│   │       │   └── Api
│   │       │       └── Improve
│   │       │           └── Design
│   │       ├── Service
│   │       │   └── DataProvider
│   │       │       └── MarketPlace
│   │       └── Test
│   ├── PrestaShopBundle
│   │   ├── Command
│   │   ├── Controller
│   │   ├── Mock
│   │   ├── Model
│   │   │   └── Product
│   │   ├── resources
│   │   │   └── themes
│   │   │       └── fake-theme
│   │   │           ├── assets
│   │   │           │   ├── css
│   │   │           │   └── js
│   │   │           ├── config
│   │   │           └── templates
│   │   │               ├── catalog
│   │   │               │   └── _partials
│   │   │               │       └── miniatures
│   │   │               ├── checkout
│   │   │               └── _partials
│   │   ├── Routing
│   │   ├── Service
│   │   │   └── Hook
│   │   ├── Translation
│   │   │   ├── Exporter
│   │   │   ├── Extractor
│   │   │   └── Factory
│   │   ├── Twig
│   │   │   ├── Fixtures
│   │   │   │   ├── module1
│   │   │   │   │   └── views
│   │   │   │   │       └── PrestaShop
│   │   │   │   │           └── Admin
│   │   │   │   │               └── Product
│   │   │   │   ├── module2
│   │   │   │   │   └── views
│   │   │   │   │       └── PrestaShop
│   │   │   │   └── module3
│   │   │   │       └── views
│   │   │   │           └── PrestaShop
│   │   │   │               └── Admin
│   │   │   │                   └── Product
│   │   │   │                       └── ProductPage
│   │   │   │                           └── Lists
│   │   │   └── Locator
│   │   └── Utils
│   ├── resources
│   │   ├── assets
│   │   │   ├── css
│   │   │   └── js
│   │   ├── minimal-missconfig-theme
│   │   │   ├── assets
│   │   │   │   ├── css
│   │   │   │   └── js
│   │   │   ├── config
│   │   │   └── templates
│   │   │       ├── catalog
│   │   │       ├── checkout
│   │   │       └── _partials
│   │   ├── minimal-missfiles-theme
│   │   │   ├── assets
│   │   │   │   ├── css
│   │   │   │   └── js
│   │   │   ├── config
│   │   │   └── templates
│   │   │       ├── catalog
│   │   │       └── _partials
│   │   ├── minimal-valid-theme
│   │   │   ├── assets
│   │   │   │   ├── css
│   │   │   │   └── js
│   │   │   ├── config
│   │   │   └── templates
│   │   │       ├── catalog
│   │   │       │   └── listing
│   │   │       ├── checkout
│   │   │       ├── cms
│   │   │       ├── customer
│   │   │       ├── errors
│   │   │       └── _partials
│   │   ├── module
│   │   │   ├── demo
│   │   │   │   ├── config
│   │   │   │   ├── src
│   │   │   │   │   └── Controller
│   │   │   │   │       └── Admin
│   │   │   │   ├── templates
│   │   │   │   │   └── admin
│   │   │   │   └── vendor
│   │   │   │       └── composer
│   │   │   ├── pscsx3241
│   │   │   │   └── override
│   │   │   │       ├── classes
│   │   │   │       └── controllers
│   │   │   │           └── admin
│   │   │   └── pscsx32412
│   │   │       └── override
│   │   │           ├── classes
│   │   │           └── controllers
│   │   │               └── admin
│   │   ├── modules
│   │   │   ├── bankwire
│   │   │   ├── cronjobs
│   │   │   │   ├── classes
│   │   │   │   ├── controllers
│   │   │   │   │   ├── admin
│   │   │   │   │   └── front
│   │   │   │   ├── translations
│   │   │   │   ├── upgrade
│   │   │   │   ├── vendor
│   │   │   │   │   └── composer
│   │   │   │   └── views
│   │   │   │       ├── css
│   │   │   │       └── templates
│   │   │   │           └── admin
│   │   │   │               └── _configure
│   │   │   │                   └── helpers
│   │   │   │                       └── form
│   │   │   ├── gamification
│   │   │   │   ├── classes
│   │   │   │   ├── controllers
│   │   │   │   │   └── admin
│   │   │   │   ├── translations
│   │   │   │   ├── upgrade
│   │   │   │   ├── vendor
│   │   │   │   │   └── composer
│   │   │   │   └── views
│   │   │   │       ├── css
│   │   │   │       ├── img
│   │   │   │       ├── jquerybubblepopup-themes
│   │   │   │       │   └── black
│   │   │   │       │       └── ie
│   │   │   │       ├── js
│   │   │   │       └── templates
│   │   │   │           ├── admin
│   │   │   │           │   └── gamification
│   │   │   │           │       └── helpers
│   │   │   │           │           └── view
│   │   │   │           └── hook
│   │   │   ├── ganalytics
│   │   │   ├── ps_banner
│   │   │   ├── ps_emailsubscription
│   │   │   └── ps_featuredproducts
│   │   ├── module-self-config-files
│   │   │   ├── php
│   │   │   └── sql
│   │   │       └── another-subfolder
│   │   ├── ModulesOverrideInstallUninstallTest
│   │   └── template-hierarchy
│   │       └── templates
│   │           └── catalog
│   │               └── listing
│   ├── TestCase
│   └── Unit
│       ├── Adapter
│       │   ├── Admin
│       │   ├── Cart
│       │   └── Module
│       │       ├── Configuration
│       │       ├── PrestaTrust
│       │       └── Tab
│       ├── classes
│       ├── Classes
│       │   ├── Checkout
│       │   ├── Module
│       │   ├── Smarty
│       │   └── Tax
│       ├── Controller
│       │   ├── Admin
│       │   └── FrontController
│       ├── Core
│       │   ├── Addon
│       │   │   ├── Module
│       │   │   └── Theme
│       │   ├── Business
│       │   │   ├── Payment
│       │   │   └── Product
│       │   │       └── Search
│       │   ├── Cart
│       │   │   ├── Adding
│       │   │   │   ├── CartRule
│       │   │   │   └── Product
│       │   │   ├── Calculation
│       │   │   │   ├── Carrier
│       │   │   │   ├── CartRules
│       │   │   │   ├── Currencies
│       │   │   │   ├── Modes
│       │   │   │   ├── Products
│       │   │   │   ├── SpecificPriceRules
│       │   │   │   └── Taxes
│       │   │   └── CartToOrder
│       │   ├── Domain
│       │   │   └── SqlManagement
│       │   │       ├── CommandHandler
│       │   │       └── QueryHandler
│       │   ├── Filter
│       │   │   └── _Artifacts
│       │   ├── Foundation
│       │   │   ├── Database
│       │   │   │   └── EntityManager
│       │   │   ├── FileSystem
│       │   │   │   └── fixtures
│       │   │   │       └── a
│       │   │   │           └── b
│       │   │   └── IoC
│       │   │       └── Fixtures
│       │   ├── Grid
│       │   │   ├── Column
│       │   │   ├── Data
│       │   │   │   └── Factory
│       │   │   ├── Definition
│       │   │   │   └── Factory
│       │   │   ├── Filter
│       │   │   ├── Position
│       │   │   ├── Presenter
│       │   │   └── Query
│       │   ├── Hook
│       │   ├── Localization
│       │   │   ├── CLDR
│       │   │   │   └── DataLayer
│       │   │   ├── Currency
│       │   │   ├── DataLayer
│       │   │   ├── Locale
│       │   │   ├── Number
│       │   │   └── Specification
│       │   ├── Module
│       │   ├── Payment
│       │   ├── Search
│       │   └── Stock
│       └── PrestaShopBundle
│           ├── Api
│           └── Utils
├── themes
│   ├── classic
│   │   ├── assets
│   │   │   ├── css
│   │   │   └── js
│   │   ├── config
│   │   ├── _dev
│   │   │   ├── css
│   │   │   │   ├── components
│   │   │   │   └── partials
│   │   │   ├── img
│   │   │   └── js
│   │   │       ├── components
│   │   │       └── lib
│   │   ├── modules
│   │   │   ├── blockreassurance
│   │   │   │   └── views
│   │   │   │       └── templates
│   │   │   │           └── hook
│   │   │   ├── contactform
│   │   │   │   └── views
│   │   │   │       └── templates
│   │   │   │           └── widget
│   │   │   ├── ps_advertising
│   │   │   ├── ps_banner
│   │   │   ├── ps_bestsellers
│   │   │   │   └── views
│   │   │   │       └── templates
│   │   │   │           └── hook
│   │   │   ├── ps_brandlist
│   │   │   │   └── views
│   │   │   │       └── templates
│   │   │   │           ├── hook
│   │   │   │           └── _partials
│   │   │   ├── ps_categoryproducts
│   │   │   │   └── views
│   │   │   │       └── templates
│   │   │   │           └── hook
│   │   │   ├── ps_categorytree
│   │   │   │   └── views
│   │   │   │       └── templates
│   │   │   │           └── hook
│   │   │   ├── ps_contactinfo
│   │   │   ├── ps_crossselling
│   │   │   │   └── views
│   │   │   │       └── templates
│   │   │   │           └── hook
│   │   │   ├── ps_currencyselector
│   │   │   ├── ps_customeraccountlinks
│   │   │   ├── ps_customersignin
│   │   │   ├── ps_emailalerts
│   │   │   │   └── views
│   │   │   │       └── templates
│   │   │   │           └── hook
│   │   │   ├── ps_emailsubscription
│   │   │   │   └── views
│   │   │   │       └── templates
│   │   │   │           └── hook
│   │   │   ├── ps_facetedsearch
│   │   │   ├── ps_featuredproducts
│   │   │   │   └── views
│   │   │   │       └── templates
│   │   │   │           └── hook
│   │   │   ├── ps_imageslider
│   │   │   │   └── views
│   │   │   │       └── templates
│   │   │   │           └── hook
│   │   │   ├── ps_languageselector
│   │   │   ├── ps_legalcompliance
│   │   │   │   └── views
│   │   │   │       └── templates
│   │   │   │           └── hook
│   │   │   ├── ps_linklist
│   │   │   │   └── views
│   │   │   │       └── templates
│   │   │   │           └── hook
│   │   │   ├── ps_mainmenu
│   │   │   ├── ps_newproducts
│   │   │   │   └── views
│   │   │   │       └── templates
│   │   │   │           └── hook
│   │   │   ├── ps_productinfo
│   │   │   │   └── views
│   │   │   │       └── templates
│   │   │   │           └── hook
│   │   │   ├── ps_rssfeed
│   │   │   │   └── views
│   │   │   │       └── templates
│   │   │   │           └── hook
│   │   │   ├── ps_searchbar
│   │   │   ├── ps_sharebuttons
│   │   │   │   └── views
│   │   │   │       └── templates
│   │   │   │           └── hook
│   │   │   ├── ps_shoppingcart
│   │   │   ├── ps_socialfollow
│   │   │   ├── ps_specials
│   │   │   │   └── views
│   │   │   │       └── templates
│   │   │   │           └── hook
│   │   │   ├── ps_supplierlist
│   │   │   │   └── views
│   │   │   │       └── templates
│   │   │   │           ├── hook
│   │   │   │           └── _partials
│   │   │   └── ps_viewedproduct
│   │   │       └── views
│   │   │           └── templates
│   │   │               └── hook
│   │   ├── plugins
│   │   └── templates
│   │       ├── catalog
│   │       │   ├── listing
│   │       │   └── _partials
│   │       │       └── miniatures
│   │       ├── checkout
│   │       │   └── _partials
│   │       │       └── steps
│   │       ├── cms
│   │       │   └── _partials
│   │       ├── customer
│   │       │   └── _partials
│   │       ├── errors
│   │       │   └── static
│   │       ├── layouts
│   │       └── _partials
│   ├── _core
│   │   └── js
│   └── _libraries
│       └── font-awesome
│           ├── css
│           └── fonts
├── tools
│   ├── assets
│   ├── build
│   │   ├── doc
│   │   ├── Exception
│   │   ├── Library
│   │   │   └── InstallUnpacker
│   │   │       ├── classes
│   │   │       └── content
│   │   ├── releases
│   │   └── tests
│   │       └── Unit
│   │           └── Library
│   │               └── InstallUnpacker
│   │                   └── classes
│   ├── foreignkeyGenerator
│   ├── parser_sql
│   │   ├── builders
│   │   ├── exceptions
│   │   ├── lexer
│   │   ├── positions
│   │   ├── processors
│   │   └── utils
│   └── profiling
├── translations
│   ├── cldr
│   └── export
├── travis-scripts
├── upload
├── var
│   ├── cache
│   ├── logs
│   └── sessions
├── vendor
└── webservice
```

2196 directories
