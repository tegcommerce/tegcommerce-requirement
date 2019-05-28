# saleor

## structure of directories

```
.
├── deployment
│   └── elasticbeanstalk
├── docs
│   ├── architecture
│   ├── contributing
│   ├── customization
│   ├── deployment
│   ├── gettingstarted
│   ├── guides
│   ├── img
│   ├── integrations
│   └── payment-gateways
├── locale
│   ├── ar
│   │   └── LC_MESSAGES
│   ├── az
│   │   └── LC_MESSAGES
│   ├── bg
│   │   └── LC_MESSAGES
│   ├── bn
│   │   └── LC_MESSAGES
│   ├── ca
│   │   └── LC_MESSAGES
│   ├── cs
│   │   └── LC_MESSAGES
│   ├── da
│   │   └── LC_MESSAGES
│   ├── de
│   │   └── LC_MESSAGES
│   ├── en
│   │   └── LC_MESSAGES
│   ├── es
│   │   └── LC_MESSAGES
│   ├── es_CO
│   │   └── LC_MESSAGES
│   ├── et
│   │   └── LC_MESSAGES
│   ├── fa
│   │   └── LC_MESSAGES
│   ├── fr
│   │   └── LC_MESSAGES
│   ├── hi
│   │   └── LC_MESSAGES
│   ├── hu
│   │   └── LC_MESSAGES
│   ├── hy
│   │   └── LC_MESSAGES
│   ├── id
│   │   └── LC_MESSAGES
│   ├── it
│   │   └── LC_MESSAGES
│   ├── ja
│   │   └── LC_MESSAGES
│   ├── ko
│   │   └── LC_MESSAGES
│   ├── mn
│   │   └── LC_MESSAGES
│   ├── nb
│   │   └── LC_MESSAGES
│   ├── nl
│   │   └── LC_MESSAGES
│   ├── pl
│   │   └── LC_MESSAGES
│   ├── pt
│   │   └── LC_MESSAGES
│   ├── pt_BR
│   │   └── LC_MESSAGES
│   ├── ro
│   │   └── LC_MESSAGES
│   ├── ru
│   │   └── LC_MESSAGES
│   ├── sk
│   │   └── LC_MESSAGES
│   ├── sl
│   │   └── LC_MESSAGES
│   ├── sq
│   │   └── LC_MESSAGES
│   ├── sr
│   │   └── LC_MESSAGES
│   ├── sv
│   │   └── LC_MESSAGES
│   ├── sw
│   │   └── LC_MESSAGES
│   ├── th
│   │   └── LC_MESSAGES
│   ├── tr
│   │   └── LC_MESSAGES
│   ├── uk
│   │   └── LC_MESSAGES
│   ├── vi
│   │   └── LC_MESSAGES
│   ├── zh_Hans
│   │   └── LC_MESSAGES
│   └── zh_Hant
│       └── LC_MESSAGES
├── saleor
│   ├── account
│   │   ├── backends
│   │   ├── management
│   │   │   └── commands
│   │   ├── migrations
│   │   └── templatetags
│   ├── checkout
│   │   ├── migrations
│   │   └── views
│   ├── core
│   │   ├── management
│   │   │   └── commands
│   │   ├── migrations
│   │   ├── templatetags
│   │   └── utils
│   ├── dashboard
│   │   ├── category
│   │   ├── collection
│   │   ├── customer
│   │   ├── discount
│   │   ├── locale
│   │   │   ├── ar
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── az
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── bg
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── bn
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── ca
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── cs
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── da
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── de
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── en
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── es
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── es_CO
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── et
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── fa
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── fr
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── hi
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── hu
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── hy
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── id
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── it
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── ja
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── ko
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── lt
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── mn
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── nb
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── nl
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── pl
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── pt
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── pt_BR
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── ro
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── ru
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── sk
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── sl
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── sq
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── sr
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── sv
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── sw
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── th
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── tr
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── uk
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── vi
│   │   │   │   └── LC_MESSAGES
│   │   │   ├── zh_Hans
│   │   │   │   └── LC_MESSAGES
│   │   │   └── zh_Hant
│   │   │       └── LC_MESSAGES
│   │   ├── menu
│   │   ├── order
│   │   ├── page
│   │   ├── product
│   │   ├── search
│   │   ├── seo
│   │   ├── shipping
│   │   ├── sites
│   │   ├── staff
│   │   ├── taxes
│   │   └── templatetags
│   ├── data_feeds
│   │   └── management
│   │       └── commands
│   ├── discount
│   │   ├── migrations
│   │   └── templatetags
│   ├── graphql
│   │   ├── account
│   │   ├── checkout
│   │   ├── core
│   │   │   └── types
│   │   ├── discount
│   │   ├── management
│   │   │   └── commands
│   │   ├── menu
│   │   ├── order
│   │   │   ├── bulk_mutations
│   │   │   └── mutations
│   │   ├── page
│   │   ├── payment
│   │   ├── product
│   │   │   ├── bulk_mutations
│   │   │   ├── mutations
│   │   │   └── types
│   │   ├── shipping
│   │   ├── shop
│   │   └── translations
│   ├── menu
│   │   └── migrations
│   ├── order
│   │   └── migrations
│   ├── page
│   │   └── migrations
│   ├── payment
│   │   ├── gateways
│   │   │   ├── braintree
│   │   │   ├── dummy
│   │   │   ├── razorpay
│   │   │   └── stripe
│   │   └── migrations
│   ├── product
│   │   ├── migrations
│   │   ├── templatetags
│   │   └── utils
│   ├── search
│   │   ├── backends
│   │   ├── management
│   │   │   └── commands
│   │   └── migrations
│   ├── seo
│   │   └── schema
│   ├── shipping
│   │   └── migrations
│   ├── site
│   │   └── migrations
│   ├── static
│   │   ├── dashboard
│   │   │   ├── images
│   │   │   │   └── editor
│   │   │   ├── js
│   │   │   │   └── components
│   │   │   └── scss
│   │   │       ├── components
│   │   │       └── layouts
│   │   ├── dashboard-next
│   │   │   ├── auth
│   │   │   │   ├── components
│   │   │   │   │   ├── LoginLoading
│   │   │   │   │   └── LoginPage
│   │   │   │   ├── types
│   │   │   │   └── views
│   │   │   ├── categories
│   │   │   │   ├── components
│   │   │   │   │   ├── CategoryBackground
│   │   │   │   │   ├── CategoryCreatePage
│   │   │   │   │   ├── CategoryDeleteDialog
│   │   │   │   │   ├── CategoryDetailsForm
│   │   │   │   │   ├── CategoryList
│   │   │   │   │   ├── CategoryListPage
│   │   │   │   │   ├── CategoryProducts
│   │   │   │   │   ├── CategoryProductsCard
│   │   │   │   │   └── CategoryUpdatePage
│   │   │   │   ├── types
│   │   │   │   └── views
│   │   │   ├── collections
│   │   │   │   ├── components
│   │   │   │   │   ├── CollectionCreatePage
│   │   │   │   │   ├── CollectionDetails
│   │   │   │   │   ├── CollectionDetailsPage
│   │   │   │   │   ├── CollectionImage
│   │   │   │   │   ├── CollectionList
│   │   │   │   │   ├── CollectionListPage
│   │   │   │   │   ├── CollectionProducts
│   │   │   │   │   └── CollectionStatus
│   │   │   │   ├── containers
│   │   │   │   ├── types
│   │   │   │   └── views
│   │   │   ├── components
│   │   │   │   ├── ActionDialog
│   │   │   │   ├── AddressEdit
│   │   │   │   ├── AddressFormatter
│   │   │   │   ├── AppHeader
│   │   │   │   ├── AppLayout
│   │   │   │   ├── AppProgress
│   │   │   │   ├── AssignCategoryDialog
│   │   │   │   ├── AssignCollectionDialog
│   │   │   │   ├── AssignProductDialog
│   │   │   │   ├── AutocompleteSelectMenu
│   │   │   │   ├── CardMenu
│   │   │   │   ├── CardTitle
│   │   │   │   ├── Checkbox
│   │   │   │   ├── Chip
│   │   │   │   ├── ConfirmButton
│   │   │   │   ├── CountryList
│   │   │   │   ├── Date
│   │   │   │   ├── EditableTableCell
│   │   │   │   ├── ErrorMessageCard
│   │   │   │   ├── ErrorPage
│   │   │   │   ├── ExtendedPageHeader
│   │   │   │   ├── ExternalLink
│   │   │   │   ├── FileUpload
│   │   │   │   ├── FilterCard
│   │   │   │   ├── Form
│   │   │   │   ├── Grid
│   │   │   │   ├── IconButtonTableCell
│   │   │   │   ├── ImageTile
│   │   │   │   ├── ImageUpload
│   │   │   │   ├── LanguageSwitch
│   │   │   │   ├── ListField
│   │   │   │   ├── Locale
│   │   │   │   ├── messages
│   │   │   │   ├── Money
│   │   │   │   ├── MoneyRange
│   │   │   │   ├── MultiAutocompleteSelectField
│   │   │   │   ├── MultiSelectField
│   │   │   │   ├── NotFoundPage
│   │   │   │   ├── PageHeader
│   │   │   │   ├── Percent
│   │   │   │   ├── PhoneField
│   │   │   │   ├── PriceField
│   │   │   │   ├── ProductList
│   │   │   │   ├── RichTextEditor
│   │   │   │   ├── SaveButtonBar
│   │   │   │   ├── SeoForm
│   │   │   │   ├── Shop
│   │   │   │   │   └── types
│   │   │   │   ├── SingleAutocompleteSelectField
│   │   │   │   ├── SingleSelectField
│   │   │   │   ├── StatusLabel
│   │   │   │   ├── Tab
│   │   │   │   ├── TableCellAvatar
│   │   │   │   ├── TableFilter
│   │   │   │   ├── TableHead
│   │   │   │   ├── TablePagination
│   │   │   │   ├── TextFieldWithChoice
│   │   │   │   ├── Theme
│   │   │   │   ├── Timeline
│   │   │   │   ├── Timezone
│   │   │   │   ├── Weight
│   │   │   │   ├── WeightRange
│   │   │   │   └── WindowTitle
│   │   │   ├── configuration
│   │   │   ├── containers
│   │   │   │   ├── SearchCategories
│   │   │   │   │   └── types
│   │   │   │   ├── SearchCollections
│   │   │   │   │   └── types
│   │   │   │   ├── SearchPages
│   │   │   │   │   └── types
│   │   │   │   └── SearchProducts
│   │   │   │       └── types
│   │   │   ├── customers
│   │   │   │   ├── components
│   │   │   │   │   ├── CustomerAddress
│   │   │   │   │   ├── CustomerAddressDialog
│   │   │   │   │   ├── CustomerAddresses
│   │   │   │   │   ├── CustomerAddressListPage
│   │   │   │   │   ├── CustomerCreateAddress
│   │   │   │   │   ├── CustomerCreateDetails
│   │   │   │   │   ├── CustomerCreateNote
│   │   │   │   │   ├── CustomerCreatePage
│   │   │   │   │   ├── CustomerDetails
│   │   │   │   │   ├── CustomerDetailsPage
│   │   │   │   │   ├── CustomerList
│   │   │   │   │   ├── CustomerListPage
│   │   │   │   │   ├── CustomerOrders
│   │   │   │   │   └── CustomerStats
│   │   │   │   ├── types
│   │   │   │   └── views
│   │   │   ├── discounts
│   │   │   │   ├── components
│   │   │   │   │   ├── DiscountCategories
│   │   │   │   │   ├── DiscountCollections
│   │   │   │   │   ├── DiscountCountrySelectDialog
│   │   │   │   │   ├── DiscountProducts
│   │   │   │   │   ├── SaleCreatePage
│   │   │   │   │   ├── SaleDetailsPage
│   │   │   │   │   ├── SaleInfo
│   │   │   │   │   ├── SaleList
│   │   │   │   │   ├── SaleListPage
│   │   │   │   │   ├── SalePricing
│   │   │   │   │   ├── SaleSummary
│   │   │   │   │   ├── VoucherCreatePage
│   │   │   │   │   ├── VoucherDetailsPage
│   │   │   │   │   ├── VoucherInfo
│   │   │   │   │   ├── VoucherList
│   │   │   │   │   ├── VoucherListPage
│   │   │   │   │   ├── VoucherOptions
│   │   │   │   │   └── VoucherSummary
│   │   │   │   ├── types
│   │   │   │   └── views
│   │   │   ├── home
│   │   │   │   ├── components
│   │   │   │   │   ├── HomeActivityCard
│   │   │   │   │   ├── HomeAnalyticsCard
│   │   │   │   │   ├── HomeHeader
│   │   │   │   │   ├── HomeNotificationTable
│   │   │   │   │   ├── HomePage
│   │   │   │   │   └── HomeProductListCard
│   │   │   │   ├── types
│   │   │   │   └── views
│   │   │   ├── hooks
│   │   │   ├── icons
│   │   │   ├── navigation
│   │   │   │   ├── components
│   │   │   │   │   ├── MenuCreateDialog
│   │   │   │   │   ├── MenuDetailsPage
│   │   │   │   │   │   └── __snapshots__
│   │   │   │   │   ├── MenuItemDialog
│   │   │   │   │   ├── MenuItems
│   │   │   │   │   │   └── __snapshots__
│   │   │   │   │   ├── MenuList
│   │   │   │   │   ├── MenuListPage
│   │   │   │   │   └── MenuProperties
│   │   │   │   ├── types
│   │   │   │   └── views
│   │   │   │       └── MenuDetails
│   │   │   ├── orders
│   │   │   │   ├── components
│   │   │   │   │   ├── OrderAddressEditDialog
│   │   │   │   │   ├── OrderBulkCancelDialog
│   │   │   │   │   ├── OrderCancelDialog
│   │   │   │   │   ├── OrderCustomer
│   │   │   │   │   ├── OrderCustomerEditDialog
│   │   │   │   │   ├── OrderCustomerNote
│   │   │   │   │   ├── OrderDetailsPage
│   │   │   │   │   ├── OrderDraftCancelDialog
│   │   │   │   │   ├── OrderDraftDetails
│   │   │   │   │   ├── OrderDraftDetailsProducts
│   │   │   │   │   ├── OrderDraftDetailsSummary
│   │   │   │   │   ├── OrderDraftFinalizeDialog
│   │   │   │   │   ├── OrderDraftList
│   │   │   │   │   ├── OrderDraftListPage
│   │   │   │   │   ├── OrderDraftPage
│   │   │   │   │   ├── OrderFulfillment
│   │   │   │   │   ├── OrderFulfillmentCancelDialog
│   │   │   │   │   ├── OrderFulfillmentDialog
│   │   │   │   │   ├── OrderFulfillmentTrackingDialog
│   │   │   │   │   ├── OrderHistory
│   │   │   │   │   ├── OrderList
│   │   │   │   │   ├── OrderListFilter
│   │   │   │   │   ├── OrderListPage
│   │   │   │   │   ├── OrderMarkAsPaidDialog
│   │   │   │   │   ├── OrderPayment
│   │   │   │   │   ├── OrderPaymentDialog
│   │   │   │   │   ├── OrderPaymentVoidDialog
│   │   │   │   │   ├── OrderProductAddDialog
│   │   │   │   │   ├── OrderShippingMethodEditDialog
│   │   │   │   │   └── OrderUnfulfilledItems
│   │   │   │   ├── containers
│   │   │   │   ├── types
│   │   │   │   └── views
│   │   │   │       └── OrderDetails
│   │   │   ├── pages
│   │   │   │   ├── components
│   │   │   │   │   ├── PageAvailability
│   │   │   │   │   ├── PageDetailsPage
│   │   │   │   │   ├── PageInfo
│   │   │   │   │   ├── PageList
│   │   │   │   │   ├── PageListPage
│   │   │   │   │   └── PageSlug
│   │   │   │   ├── types
│   │   │   │   └── views
│   │   │   ├── products
│   │   │   │   ├── components
│   │   │   │   │   ├── ProductAvailabilityForm
│   │   │   │   │   ├── ProductCategoryAndCollectionsForm
│   │   │   │   │   ├── ProductCreatePage
│   │   │   │   │   ├── ProductDetailsForm
│   │   │   │   │   ├── ProductImageNavigation
│   │   │   │   │   ├── ProductImagePage
│   │   │   │   │   ├── ProductImages
│   │   │   │   │   ├── ProductListCard
│   │   │   │   │   ├── ProductListFilter
│   │   │   │   │   ├── ProductOrganization
│   │   │   │   │   ├── ProductPricing
│   │   │   │   │   ├── ProductStock
│   │   │   │   │   ├── ProductUpdatePage
│   │   │   │   │   ├── ProductVariantAttributes
│   │   │   │   │   ├── ProductVariantCreatePage
│   │   │   │   │   ├── ProductVariantDeleteDialog
│   │   │   │   │   ├── ProductVariantImages
│   │   │   │   │   ├── ProductVariantImageSelectDialog
│   │   │   │   │   ├── ProductVariantNavigation
│   │   │   │   │   ├── ProductVariantPage
│   │   │   │   │   ├── ProductVariantPrice
│   │   │   │   │   ├── ProductVariants
│   │   │   │   │   └── ProductVariantStock
│   │   │   │   ├── containers
│   │   │   │   ├── types
│   │   │   │   └── views
│   │   │   ├── productTypes
│   │   │   │   ├── components
│   │   │   │   │   ├── ProductTypeAttributeEditDialog
│   │   │   │   │   ├── ProductTypeAttributes
│   │   │   │   │   ├── ProductTypeCreatePage
│   │   │   │   │   ├── ProductTypeDetails
│   │   │   │   │   ├── ProductTypeDetailsPage
│   │   │   │   │   ├── ProductTypeList
│   │   │   │   │   ├── ProductTypeListPage
│   │   │   │   │   ├── ProductTypeShipping
│   │   │   │   │   └── ProductTypeTaxes
│   │   │   │   ├── containers
│   │   │   │   ├── types
│   │   │   │   └── views
│   │   │   │       └── ProductTypeUpdate
│   │   │   ├── shipping
│   │   │   │   ├── components
│   │   │   │   │   ├── ShippingWeightUnitForm
│   │   │   │   │   ├── ShippingZoneCountriesAssignDialog
│   │   │   │   │   ├── ShippingZoneCreatePage
│   │   │   │   │   ├── ShippingZoneDetailsPage
│   │   │   │   │   ├── ShippingZoneInfo
│   │   │   │   │   ├── ShippingZoneRateDialog
│   │   │   │   │   ├── ShippingZoneRates
│   │   │   │   │   ├── ShippingZonesList
│   │   │   │   │   └── ShippingZonesListPage
│   │   │   │   ├── types
│   │   │   │   └── views
│   │   │   │       └── ShippingZoneDetails
│   │   │   ├── siteSettings
│   │   │   │   ├── components
│   │   │   │   │   ├── SiteSettingsDetails
│   │   │   │   │   ├── SiteSettingsKeyDialog
│   │   │   │   │   ├── SiteSettingsKeys
│   │   │   │   │   └── SiteSettingsPage
│   │   │   │   ├── types
│   │   │   │   └── views
│   │   │   ├── staff
│   │   │   │   ├── components
│   │   │   │   │   ├── StaffAddMemberDialog
│   │   │   │   │   ├── StaffDetailsPage
│   │   │   │   │   ├── StaffList
│   │   │   │   │   ├── StaffListPage
│   │   │   │   │   ├── StaffPermissions
│   │   │   │   │   ├── StaffProperties
│   │   │   │   │   └── StaffStatus
│   │   │   │   ├── types
│   │   │   │   └── views
│   │   │   ├── storybook
│   │   │   │   ├── __snapshots__
│   │   │   │   └── stories
│   │   │   │       ├── auth
│   │   │   │       ├── categories
│   │   │   │       ├── collections
│   │   │   │       ├── components
│   │   │   │       ├── configuration
│   │   │   │       ├── customers
│   │   │   │       ├── discounts
│   │   │   │       ├── home
│   │   │   │       ├── navigation
│   │   │   │       ├── orders
│   │   │   │       ├── pages
│   │   │   │       ├── products
│   │   │   │       ├── productTypes
│   │   │   │       ├── shipping
│   │   │   │       ├── siteSettings
│   │   │   │       ├── staff
│   │   │   │       ├── taxes
│   │   │   │       └── translations
│   │   │   ├── taxes
│   │   │   │   ├── components
│   │   │   │   │   ├── CountryList
│   │   │   │   │   ├── CountryListPage
│   │   │   │   │   ├── CountryTaxesPage
│   │   │   │   │   └── TaxConfiguration
│   │   │   │   ├── types
│   │   │   │   └── views
│   │   │   ├── translations
│   │   │   │   ├── components
│   │   │   │   │   ├── TranslationFields
│   │   │   │   │   ├── TranslationsCategoriesPage
│   │   │   │   │   ├── TranslationsCollectionsPage
│   │   │   │   │   ├── TranslationsEntitiesList
│   │   │   │   │   ├── TranslationsEntitiesListPage
│   │   │   │   │   ├── TranslationsLanguageList
│   │   │   │   │   ├── TranslationsLanguageListPage
│   │   │   │   │   ├── TranslationsPagesPage
│   │   │   │   │   ├── TranslationsProductsPage
│   │   │   │   │   ├── TranslationsProductTypesPage
│   │   │   │   │   ├── TranslationsSalesPage
│   │   │   │   │   └── TranslationsVouchersPage
│   │   │   │   ├── types
│   │   │   │   └── views
│   │   │   └── types
│   │   ├── favicons
│   │   ├── fonts
│   │   ├── images
│   │   │   └── avatars
│   │   ├── js
│   │   │   ├── components
│   │   │   │   └── variantPicker
│   │   │   └── stores
│   │   ├── placeholders
│   │   │   └── products-list
│   │   └── scss
│   │       ├── components
│   │       └── layouts
│   └── wsgi
├── scripts
├── templates
│   ├── account
│   │   ├── partials
│   │   └── snippets
│   ├── category
│   ├── checkout
│   │   └── snippets
│   ├── collection
│   ├── dashboard
│   │   ├── category
│   │   │   └── modal
│   │   ├── collection
│   │   ├── customer
│   │   │   └── modal
│   │   ├── discount
│   │   │   ├── sale
│   │   │   │   └── modal
│   │   │   └── voucher
│   │   │       └── modal
│   │   ├── includes
│   │   ├── menu
│   │   │   ├── item
│   │   │   │   └── modal
│   │   │   └── modal
│   │   ├── order
│   │   │   ├── modal
│   │   │   ├── pdf
│   │   │   └── widget
│   │   ├── page
│   │   ├── product
│   │   │   ├── attribute
│   │   │   │   ├── modal
│   │   │   │   └── values
│   │   │   │       └── modal
│   │   │   ├── modal
│   │   │   ├── product_image
│   │   │   │   └── modal
│   │   │   ├── product_type
│   │   │   │   └── modal
│   │   │   └── product_variant
│   │   │       └── modal
│   │   ├── search
│   │   ├── shipping
│   │   │   ├── methods
│   │   │   └── modal
│   │   ├── sites
│   │   │   ├── authorization_keys
│   │   │   └── modal
│   │   ├── staff
│   │   │   └── modal
│   │   ├── styleguide
│   │   └── taxes
│   ├── graphql
│   ├── materializecssform
│   ├── order
│   │   └── payment
│   ├── page
│   ├── payments
│   ├── prices
│   ├── product
│   ├── search
│   └── templated_email
│       ├── account
│       ├── compiled
│       ├── dashboard
│       │   ├── customer
│       │   └── staff
│       ├── order
│       │   └── payment
│       ├── shared
│       └── source
│           ├── partials
│           └── shared
└── tests
    ├── api
    ├── cassettes
    ├── dashboard
    └── gateway
```

710 directories
