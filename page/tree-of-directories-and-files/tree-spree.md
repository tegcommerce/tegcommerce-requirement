spree
├── api
│   ├── app
│   │   ├── assets
│   │   │   └── javascripts
│   │   │       └── spree
│   │   │           └── api
│   │   │               ├── main.js
│   │   │               └── storefront
│   │   │                   └── cart.js
│   │   ├── controllers
│   │   │   ├── concerns
│   │   │   │   └── spree
│   │   │   │       └── api
│   │   │   │           └── v2
│   │   │   │               └── storefront
│   │   │   │                   └── order_concern.rb
│   │   │   └── spree
│   │   │       └── api
│   │   │           ├── base_controller.rb
│   │   │           ├── errors_controller.rb
│   │   │           ├── v1
│   │   │           │   ├── addresses_controller.rb
│   │   │           │   ├── checkouts_controller.rb
│   │   │           │   ├── classifications_controller.rb
│   │   │           │   ├── countries_controller.rb
│   │   │           │   ├── credit_cards_controller.rb
│   │   │           │   ├── customer_returns_controller.rb
│   │   │           │   ├── images_controller.rb
│   │   │           │   ├── inventory_units_controller.rb
│   │   │           │   ├── line_items_controller.rb
│   │   │           │   ├── option_types_controller.rb
│   │   │           │   ├── option_values_controller.rb
│   │   │           │   ├── orders_controller.rb
│   │   │           │   ├── payments_controller.rb
│   │   │           │   ├── product_properties_controller.rb
│   │   │           │   ├── products_controller.rb
│   │   │           │   ├── promotions_controller.rb
│   │   │           │   ├── properties_controller.rb
│   │   │           │   ├── reimbursements_controller.rb
│   │   │           │   ├── return_authorizations_controller.rb
│   │   │           │   ├── shipments_controller.rb
│   │   │           │   ├── states_controller.rb
│   │   │           │   ├── stock_items_controller.rb
│   │   │           │   ├── stock_locations_controller.rb
│   │   │           │   ├── stock_movements_controller.rb
│   │   │           │   ├── stores_controller.rb
│   │   │           │   ├── tags_controller.rb
│   │   │           │   ├── taxonomies_controller.rb
│   │   │           │   ├── taxons_controller.rb
│   │   │           │   ├── users_controller.rb
│   │   │           │   ├── variants_controller.rb
│   │   │           │   └── zones_controller.rb
│   │   │           └── v2
│   │   │               ├── base_controller.rb
│   │   │               └── storefront
│   │   │                   ├── account
│   │   │                   │   ├── credit_cards_controller.rb
│   │   │                   │   └── orders_controller.rb
│   │   │                   ├── account_controller.rb
│   │   │                   ├── cart_controller.rb
│   │   │                   ├── checkout_controller.rb
│   │   │                   ├── countries_controller.rb
│   │   │                   ├── order_status_controller.rb
│   │   │                   ├── products_controller.rb
│   │   │                   └── taxons_controller.rb
│   │   ├── helpers
│   │   │   └── spree
│   │   │       └── api
│   │   │           ├── api_helpers.rb
│   │   │           └── v2
│   │   │               └── collection_options_helpers.rb
│   │   ├── models
│   │   │   ├── concerns
│   │   │   │   └── spree
│   │   │   │       ├── user_api_authentication.rb
│   │   │   │       └── user_api_methods.rb
│   │   │   └── spree
│   │   │       ├── api_configuration.rb
│   │   │       └── api_dependencies.rb
│   │   ├── serializers
│   │   │   └── spree
│   │   │       └── v2
│   │   │           └── storefront
│   │   │               ├── address_serializer.rb
│   │   │               ├── base_serializer.rb
│   │   │               ├── cart_serializer.rb
│   │   │               ├── country_serializer.rb
│   │   │               ├── credit_card_serializer.rb
│   │   │               ├── estimated_shipping_rate_serializer.rb
│   │   │               ├── image_serializer.rb
│   │   │               ├── line_item_serializer.rb
│   │   │               ├── option_type_serializer.rb
│   │   │               ├── option_value_serializer.rb
│   │   │               ├── payment_method_serializer.rb
│   │   │               ├── payment_serializer.rb
│   │   │               ├── product_property_serializer.rb
│   │   │               ├── product_serializer.rb
│   │   │               ├── promotion_serializer.rb
│   │   │               ├── shipment_serializer.rb
│   │   │               ├── shipping_rate_serializer.rb
│   │   │               ├── state_serializer.rb
│   │   │               ├── store_credit_event_serializer.rb
│   │   │               ├── store_credit_serializer.rb
│   │   │               ├── store_credit_type_serializer.rb
│   │   │               ├── taxon_image_serializer.rb
│   │   │               ├── taxonomy_serializer.rb
│   │   │               ├── taxon_serializer.rb
│   │   │               ├── user_serializer.rb
│   │   │               └── variant_serializer.rb
│   │   └── views
│   │       └── spree
│   │           └── api
│   │               ├── errors
│   │               │   ├── gateway_error.rabl
│   │               │   ├── invalid_api_key.rabl
│   │               │   ├── invalid_resource.rabl
│   │               │   ├── must_specify_api_key.rabl
│   │               │   ├── not_found.rabl
│   │               │   └── unauthorized.rabl
│   │               └── v1
│   │                   ├── addresses
│   │                   │   └── show.rabl
│   │                   ├── adjustments
│   │                   │   └── show.rabl
│   │                   ├── countries
│   │                   │   ├── index.rabl
│   │                   │   └── show.rabl
│   │                   ├── credit_cards
│   │                   │   ├── index.rabl
│   │                   │   └── show.rabl
│   │                   ├── customer_returns
│   │                   │   └── index.rabl
│   │                   ├── images
│   │                   │   ├── index.rabl
│   │                   │   ├── new.rabl
│   │                   │   └── show.rabl
│   │                   ├── inventory_units
│   │                   │   └── show.rabl
│   │                   ├── line_items
│   │                   │   ├── new.rabl
│   │                   │   └── show.rabl
│   │                   ├── option_types
│   │                   │   ├── index.rabl
│   │                   │   ├── new.rabl
│   │                   │   └── show.rabl
│   │                   ├── option_values
│   │                   │   ├── index.rabl
│   │                   │   ├── new.rabl
│   │                   │   └── show.rabl
│   │                   ├── orders
│   │                   │   ├── address.rabl
│   │                   │   ├── canceled.rabl
│   │                   │   ├── cart.rabl
│   │                   │   ├── complete.rabl
│   │                   │   ├── could_not_apply_coupon.rabl
│   │                   │   ├── could_not_transition.rabl
│   │                   │   ├── index.rabl
│   │                   │   ├── insufficient_quantity.rabl
│   │                   │   ├── invalid_shipping_method.rabl
│   │                   │   ├── mine.rabl
│   │                   │   ├── order.rabl
│   │                   │   ├── payment.rabl
│   │                   │   └── show.rabl
│   │                   ├── payments
│   │                   │   ├── credit_over_limit.rabl
│   │                   │   ├── index.rabl
│   │                   │   ├── new.rabl
│   │                   │   ├── show.rabl
│   │                   │   └── update_forbidden.rabl
│   │                   ├── product_properties
│   │                   │   ├── index.rabl
│   │                   │   ├── new.rabl
│   │                   │   └── show.rabl
│   │                   ├── products
│   │                   │   ├── index.rabl
│   │                   │   ├── new.rabl
│   │                   │   ├── product.rabl
│   │                   │   └── show.rabl
│   │                   ├── promotions
│   │                   │   ├── handler.rabl
│   │                   │   └── show.rabl
│   │                   ├── properties
│   │                   │   ├── index.rabl
│   │                   │   ├── new.rabl
│   │                   │   └── show.rabl
│   │                   ├── reimbursements
│   │                   │   └── index.rabl
│   │                   ├── return_authorizations
│   │                   │   ├── index.rabl
│   │                   │   ├── new.rabl
│   │                   │   └── show.rabl
│   │                   ├── shared
│   │                   │   └── stock_location_required.rabl
│   │                   ├── shipments
│   │                   │   ├── big.rabl
│   │                   │   ├── cannot_ready_shipment.rabl
│   │                   │   ├── mine.rabl
│   │                   │   ├── show.rabl
│   │                   │   └── small.rabl
│   │                   ├── shipping_rates
│   │                   │   └── show.rabl
│   │                   ├── states
│   │                   │   ├── index.rabl
│   │                   │   └── show.rabl
│   │                   ├── stock_items
│   │                   │   ├── index.rabl
│   │                   │   └── show.rabl
│   │                   ├── stock_locations
│   │                   │   ├── index.rabl
│   │                   │   └── show.rabl
│   │                   ├── stock_movements
│   │                   │   ├── index.rabl
│   │                   │   └── show.rabl
│   │                   ├── stores
│   │                   │   ├── index.rabl
│   │                   │   └── show.rabl
│   │                   ├── tags
│   │                   │   └── index.rabl
│   │                   ├── taxonomies
│   │                   │   ├── index.rabl
│   │                   │   ├── jstree.rabl
│   │                   │   ├── nested.rabl
│   │                   │   ├── new.rabl
│   │                   │   └── show.rabl
│   │                   ├── taxons
│   │                   │   ├── index.rabl
│   │                   │   ├── jstree.rabl
│   │                   │   ├── new.rabl
│   │                   │   ├── show.rabl
│   │                   │   └── taxons.rabl
│   │                   ├── users
│   │                   │   ├── index.rabl
│   │                   │   ├── new.rabl
│   │                   │   └── show.rabl
│   │                   ├── variants
│   │                   │   ├── big.rabl
│   │                   │   ├── index.rabl
│   │                   │   ├── new.rabl
│   │                   │   ├── show.rabl
│   │                   │   └── small.rabl
│   │                   └── zones
│   │                       ├── index.rabl
│   │                       └── show.rabl
│   ├── config
│   │   ├── initializers
│   │   │   ├── doorkeeper.rb
│   │   │   ├── json_api_mime_types.rb
│   │   │   └── user_class_extensions.rb
│   │   ├── locales
│   │   │   └── en.yml
│   │   └── routes.rb
│   ├── db
│   │   └── migrate
│   │       ├── 20100107141738_add_api_key_to_spree_users.rb
│   │       ├── 20120411123334_resize_api_key_field.rb
│   │       ├── 20120530054546_rename_api_key_to_spree_api_key.rb
│   │       ├── 20131017162334_add_index_to_user_spree_api_key.rb
│   │       └── 20180320110726_create_doorkeeper_tables.rb
│   ├── docs
│   │   ├── oauth
│   │   │   └── index.yml
│   │   └── v2
│   │       └── storefront
│   │           └── index.yaml
│   ├── Gemfile
│   ├── lib
│   │   ├── spree
│   │   │   ├── api
│   │   │   │   ├── controller_setup.rb
│   │   │   │   ├── engine.rb
│   │   │   │   ├── responders
│   │   │   │   │   └── rabl_template.rb
│   │   │   │   ├── responders.rb
│   │   │   │   └── testing_support
│   │   │   │       ├── caching.rb
│   │   │   │       ├── helpers.rb
│   │   │   │       ├── setup.rb
│   │   │   │       └── v2
│   │   │   │           ├── base.rb
│   │   │   │           └── current_order.rb
│   │   │   └── api.rb
│   │   └── spree_api.rb
│   ├── LICENSE
│   ├── Rakefile
│   ├── script
│   │   └── rails
│   ├── spec
│   │   ├── controllers
│   │   │   └── spree
│   │   │       └── api
│   │   │           ├── base_controller_spec.rb
│   │   │           ├── v1
│   │   │           │   ├── addresses_controller_spec.rb
│   │   │           │   ├── checkouts_controller_spec.rb
│   │   │           │   ├── classifications_controller_spec.rb
│   │   │           │   ├── countries_controller_spec.rb
│   │   │           │   ├── credit_cards_controller_spec.rb
│   │   │           │   ├── customer_returns_controller_spec.rb
│   │   │           │   ├── images_controller_spec.rb
│   │   │           │   ├── inventory_units_controller_spec.rb
│   │   │           │   ├── line_items_controller_spec.rb
│   │   │           │   ├── option_types_controller_spec.rb
│   │   │           │   ├── option_values_controller_spec.rb
│   │   │           │   ├── orders_controller_spec.rb
│   │   │           │   ├── payments_controller_spec.rb
│   │   │           │   ├── product_properties_controller_spec.rb
│   │   │           │   ├── products_controller_spec.rb
│   │   │           │   ├── promotion_application_spec.rb
│   │   │           │   ├── promotions_controller_spec.rb
│   │   │           │   ├── properties_controller_spec.rb
│   │   │           │   ├── reimbursements_controller_spec.rb
│   │   │           │   ├── return_authorizations_controller_spec.rb
│   │   │           │   ├── shipments_controller_spec.rb
│   │   │           │   ├── states_controller_spec.rb
│   │   │           │   ├── stock_items_controller_spec.rb
│   │   │           │   ├── stock_locations_controller_spec.rb
│   │   │           │   ├── stock_movements_controller_spec.rb
│   │   │           │   ├── stores_controller_spec.rb
│   │   │           │   ├── tags_controller_spec.rb
│   │   │           │   ├── taxonomies_controller_spec.rb
│   │   │           │   ├── taxons_controller_spec.rb
│   │   │           │   ├── unauthenticated_products_controller_spec.rb
│   │   │           │   ├── users_controller_spec.rb
│   │   │           │   ├── variants_controller_spec.rb
│   │   │           │   └── zones_controller_spec.rb
│   │   │           └── v2
│   │   │               └── base_controller_spec.rb
│   │   ├── fixtures
│   │   │   └── thinking-cat.jpg
│   │   ├── models
│   │   │   └── spree
│   │   │       ├── api_dependencies_spec.rb
│   │   │       └── legacy_user_spec.rb
│   │   ├── requests
│   │   │   ├── rabl_cache_spec.rb
│   │   │   ├── ransackable_attributes_spec.rb
│   │   │   ├── spree
│   │   │   │   ├── api
│   │   │   │   │   ├── errors_spec.rb
│   │   │   │   │   └── v2
│   │   │   │   │       ├── errors_spec.rb
│   │   │   │   │       ├── resource_includes_spec.rb
│   │   │   │   │       └── storefront
│   │   │   │   │           ├── account
│   │   │   │   │           │   ├── credit_cards_spec.rb
│   │   │   │   │           │   └── orders_spec.rb
│   │   │   │   │           ├── account_spec.rb
│   │   │   │   │           ├── cart_spec.rb
│   │   │   │   │           ├── checkout_spec.rb
│   │   │   │   │           ├── countries_spec.rb
│   │   │   │   │           ├── order_status_spec.rb
│   │   │   │   │           ├── products_spec.rb
│   │   │   │   │           ├── sparse_fields_spec.rb
│   │   │   │   │           └── taxons_spec.rb
│   │   │   │   └── oauth
│   │   │   │       └── token_spec.rb
│   │   │   └── version_spec.rb
│   │   ├── shared_examples
│   │   │   └── protect_product_actions.rb
│   │   ├── spec_helper.rb
│   │   └── support
│   │       ├── controller_hacks.rb
│   │       ├── database_cleaner.rb
│   │       └── have_attributes_matcher.rb
│   └── spree_api.gemspec
├── app.json
├── backend
│   ├── app
│   │   ├── assets
│   │   │   ├── images
│   │   │   │   ├── admin
│   │   │   │   │   └── logo.png
│   │   │   │   └── credit_cards
│   │   │   │       └── credit_card.gif
│   │   │   ├── javascripts
│   │   │   │   └── spree
│   │   │   │       ├── backend
│   │   │   │       │   ├── address_states.js
│   │   │   │       │   ├── adjustments.js
│   │   │   │       │   ├── admin.js
│   │   │   │       │   ├── calculator.js
│   │   │   │       │   ├── checkouts
│   │   │   │       │   │   └── edit.js
│   │   │   │       │   ├── gateway.js
│   │   │   │       │   ├── general_settings.js
│   │   │   │       │   ├── handlebar_extensions.js
│   │   │   │       │   ├── line_items.js
│   │   │   │       │   ├── line_items_on_order_edit.js
│   │   │   │       │   ├── option_type_autocomplete.js
│   │   │   │       │   ├── option_value_picker.js
│   │   │   │       │   ├── orders
│   │   │   │       │   │   └── edit.js
│   │   │   │       │   ├── payments
│   │   │   │       │   │   ├── edit.js
│   │   │   │       │   │   └── new.js
│   │   │   │       │   ├── product_picker.js
│   │   │   │       │   ├── progress.js
│   │   │   │       │   ├── promotions.js
│   │   │   │       │   ├── returns
│   │   │   │       │   │   ├── expedited_exchanges_warning.js
│   │   │   │       │   │   └── return_item_selection.js
│   │   │   │       │   ├── shipments.js
│   │   │   │       │   ├── spree-select2.js
│   │   │   │       │   ├── states.js
│   │   │   │       │   ├── stock_location.js
│   │   │   │       │   ├── stock_management.js
│   │   │   │       │   ├── stock_movement.js
│   │   │   │       │   ├── stock_transfer.js
│   │   │   │       │   ├── tag_picker.js
│   │   │   │       │   ├── taxon_autocomplete.js
│   │   │   │       │   ├── taxonomy.js
│   │   │   │       │   ├── taxon_permalink_preview.js
│   │   │   │       │   ├── taxons.js
│   │   │   │       │   ├── taxon_tree_menu.js
│   │   │   │       │   ├── user_picker.js
│   │   │   │       │   ├── users
│   │   │   │       │   │   └── edit.js
│   │   │   │       │   ├── variant_autocomplete.js
│   │   │   │       │   ├── variant_management.js
│   │   │   │       │   └── zone.js
│   │   │   │       ├── backend.js
│   │   │   │       └── frontend
│   │   │   │           └── backend.js
│   │   │   └── stylesheets
│   │   │       └── spree
│   │   │           ├── backend
│   │   │           │   ├── components
│   │   │           │   │   ├── _badges.scss
│   │   │           │   │   ├── _buttons.scss
│   │   │           │   │   ├── _filters.scss
│   │   │           │   │   ├── _icons.scss
│   │   │           │   │   ├── _main.scss
│   │   │           │   │   ├── _navbar.scss
│   │   │           │   │   ├── _navigation.scss
│   │   │           │   │   ├── _page_header.scss
│   │   │           │   │   ├── _progress.scss
│   │   │           │   │   ├── _sidebar.scss
│   │   │           │   │   ├── _spinner.scss
│   │   │           │   │   ├── _tables.scss
│   │   │           │   │   └── _taxon_products_view.scss
│   │   │           │   ├── global
│   │   │           │   │   └── _variables.scss
│   │   │           │   ├── plugins
│   │   │           │   │   ├── _jquery_ui.scss
│   │   │           │   │   └── _select2.scss
│   │   │           │   ├── shared
│   │   │           │   │   ├── _base.scss
│   │   │           │   │   └── _forms.scss
│   │   │           │   └── spree_admin.css.scss
│   │   │           ├── backend.css
│   │   │           └── frontend
│   │   │               └── backend.css
│   │   ├── controllers
│   │   │   └── spree
│   │   │       └── admin
│   │   │           ├── adjustments_controller.rb
│   │   │           ├── base_controller.rb
│   │   │           ├── countries_controller.rb
│   │   │           ├── customer_returns_controller.rb
│   │   │           ├── general_settings_controller.rb
│   │   │           ├── images_controller.rb
│   │   │           ├── log_entries_controller.rb
│   │   │           ├── option_types_controller.rb
│   │   │           ├── option_values_controller.rb
│   │   │           ├── orders
│   │   │           │   └── customer_details_controller.rb
│   │   │           ├── orders_controller.rb
│   │   │           ├── payment_methods_controller.rb
│   │   │           ├── payments_controller.rb
│   │   │           ├── product_properties_controller.rb
│   │   │           ├── products_controller.rb
│   │   │           ├── promotion_actions_controller.rb
│   │   │           ├── promotion_categories_controller.rb
│   │   │           ├── promotion_rules_controller.rb
│   │   │           ├── promotions_controller.rb
│   │   │           ├── properties_controller.rb
│   │   │           ├── prototypes_controller.rb
│   │   │           ├── refund_reasons_controller.rb
│   │   │           ├── refunds_controller.rb
│   │   │           ├── reimbursements_controller.rb
│   │   │           ├── reimbursement_types_controller.rb
│   │   │           ├── reports_controller.rb
│   │   │           ├── resource_controller.rb
│   │   │           ├── return_authorization_reasons_controller.rb
│   │   │           ├── return_authorizations_controller.rb
│   │   │           ├── return_index_controller.rb
│   │   │           ├── return_items_controller.rb
│   │   │           ├── roles_controller.rb
│   │   │           ├── shipping_categories_controller.rb
│   │   │           ├── shipping_methods_controller.rb
│   │   │           ├── state_changes_controller.rb
│   │   │           ├── states_controller.rb
│   │   │           ├── stock_items_controller.rb
│   │   │           ├── stock_locations_controller.rb
│   │   │           ├── stock_movements_controller.rb
│   │   │           ├── stock_transfers_controller.rb
│   │   │           ├── store_credit_categories_controller.rb
│   │   │           ├── store_credits_controller.rb
│   │   │           ├── stores_controller.rb
│   │   │           ├── tax_categories_controller.rb
│   │   │           ├── taxonomies_controller.rb
│   │   │           ├── taxons_controller.rb
│   │   │           ├── tax_rates_controller.rb
│   │   │           ├── users_controller.rb
│   │   │           ├── variants_controller.rb
│   │   │           ├── variants_including_master_controller.rb
│   │   │           └── zones_controller.rb
│   │   ├── helpers
│   │   │   └── spree
│   │   │       └── admin
│   │   │           ├── adjustments_helper.rb
│   │   │           ├── base_helper.rb
│   │   │           ├── currency_helper.rb
│   │   │           ├── customer_returns_helper.rb
│   │   │           ├── images_helper.rb
│   │   │           ├── navigation_helper.rb
│   │   │           ├── orders_helper.rb
│   │   │           ├── payments_helper.rb
│   │   │           ├── promotion_rules_helper.rb
│   │   │           ├── reimbursements_helper.rb
│   │   │           ├── reimbursement_type_helper.rb
│   │   │           ├── stock_locations_helper.rb
│   │   │           ├── stock_movements_helper.rb
│   │   │           └── taxons_helper.rb
│   │   ├── models
│   │   │   └── spree
│   │   │       ├── admin
│   │   │       │   └── resource.rb
│   │   │       └── backend_configuration.rb
│   │   └── views
│   │       ├── kaminari
│   │       │   └── twitter-bootstrap-4
│   │       │       ├── _first_page.html.erb
│   │       │       ├── _gap.html.erb
│   │       │       ├── _last_page.html.erb
│   │       │       ├── _next_page.html.erb
│   │       │       ├── _page.html.erb
│   │       │       ├── _paginator.html.erb
│   │       │       └── _prev_page.html.erb
│   │       └── spree
│   │           ├── admin
│   │           │   ├── adjustments
│   │           │   │   ├── _adjustment.html.erb
│   │           │   │   ├── _adjustments_table.html.erb
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── countries
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── customer_returns
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   ├── new.html.erb
│   │           │   │   ├── _reimbursements_table.html.erb
│   │           │   │   ├── _return_item_decision.html.erb
│   │           │   │   └── _return_item_selection.html.erb
│   │           │   ├── general_settings
│   │           │   │   └── edit.html.erb
│   │           │   ├── images
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── log_entries
│   │           │   │   └── index.html.erb
│   │           │   ├── option_types
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   ├── new.html.erb
│   │           │   │   └── _option_value_fields.html.erb
│   │           │   ├── orders
│   │           │   │   ├── _add_line_item.html.erb
│   │           │   │   ├── _add_product.html.erb
│   │           │   │   ├── _adjustments.html.erb
│   │           │   │   ├── cart.html.erb
│   │           │   │   ├── customer_details
│   │           │   │   │   ├── _autocomplete.js.erb
│   │           │   │   │   ├── edit.html.erb
│   │           │   │   │   └── _form.html.erb
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   ├── _line_items_edit_form.html.erb
│   │           │   │   ├── _line_items.html.erb
│   │           │   │   ├── _order_actions.html.erb
│   │           │   │   ├── _risk_analysis.html.erb
│   │           │   │   ├── _shipment.html.erb
│   │           │   │   ├── _shipment_manifest.html.erb
│   │           │   │   ├── _store_form.html.erb
│   │           │   │   └── store.html.erb
│   │           │   ├── payment_methods
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── payments
│   │           │   │   ├── _capture_events.html.erb
│   │           │   │   ├── credit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   ├── _list.html.erb
│   │           │   │   ├── new.html.erb
│   │           │   │   ├── show.html.erb
│   │           │   │   ├── source_forms
│   │           │   │   │   ├── _gateway.html.erb
│   │           │   │   │   └── _storecredit.html.erb
│   │           │   │   └── source_views
│   │           │   │       ├── _check.html.erb
│   │           │   │       ├── _gateway.html.erb
│   │           │   │       └── _storecredit.html.erb
│   │           │   ├── product_properties
│   │           │   │   ├── index.html.erb
│   │           │   │   └── _product_property_fields.html.erb
│   │           │   ├── products
│   │           │   │   ├── _add_stock_form.html.erb
│   │           │   │   ├── _autocomplete.js.erb
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   ├── new.html.erb
│   │           │   │   └── stock.html.erb
│   │           │   ├── promotion_actions
│   │           │   │   ├── create.js.erb
│   │           │   │   └── destroy.js.erb
│   │           │   ├── promotion_categories
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── promotion_rules
│   │           │   │   ├── create.js.erb
│   │           │   │   └── destroy.js.erb
│   │           │   ├── promotions
│   │           │   │   ├── actions
│   │           │   │   │   ├── _create_adjustment.html.erb
│   │           │   │   │   ├── _create_item_adjustments.html.erb
│   │           │   │   │   ├── _create_line_items.html.erb
│   │           │   │   │   └── _free_shipping.html.erb
│   │           │   │   ├── _actions.html.erb
│   │           │   │   ├── calculators
│   │           │   │   │   ├── _default_fields.html.erb
│   │           │   │   │   ├── tiered_flat_rate
│   │           │   │   │   │   └── _fields.html.erb
│   │           │   │   │   └── tiered_percent
│   │           │   │   │       └── _fields.html.erb
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   ├── new.html.erb
│   │           │   │   ├── _promotion_action.html.erb
│   │           │   │   ├── _promotion_rule.html.erb
│   │           │   │   ├── rules
│   │           │   │   │   ├── _country.html.erb
│   │           │   │   │   ├── _first_order.html.erb
│   │           │   │   │   ├── _item_total.html.erb
│   │           │   │   │   ├── _one_use_per_user.html.erb
│   │           │   │   │   ├── _option_value.html.erb
│   │           │   │   │   ├── _product.html.erb
│   │           │   │   │   ├── _taxon.html.erb
│   │           │   │   │   ├── _user.html.erb
│   │           │   │   │   └── _user_logged_in.html.erb
│   │           │   │   └── _rules.html.erb
│   │           │   ├── properties
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── prototypes
│   │           │   │   ├── available.js.erb
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   ├── new.html.erb
│   │           │   │   ├── _prototypes.html.erb
│   │           │   │   ├── select.js.erb
│   │           │   │   └── show.html.erb
│   │           │   ├── refund_reasons
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── refunds
│   │           │   │   ├── edit.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── reimbursements
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── show.html.erb
│   │           │   ├── reimbursement_types
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── reports
│   │           │   │   ├── index.html.erb
│   │           │   │   └── sales_total.html.erb
│   │           │   ├── return_authorization_reasons
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── return_authorizations
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── return_index
│   │           │   │   ├── customer_returns.html.erb
│   │           │   │   └── return_authorizations.html.erb
│   │           │   ├── roles
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── shared
│   │           │   │   ├── _account_nav.html.erb
│   │           │   │   ├── _address_form.html.erb
│   │           │   │   ├── _address.html.erb
│   │           │   │   ├── _calculator_fields.html.erb
│   │           │   │   ├── _content_header.html.erb
│   │           │   │   ├── _destroy.js.erb
│   │           │   │   ├── _edit_resource_links.html.erb
│   │           │   │   ├── _error_messages.html.erb
│   │           │   │   ├── _header.html.erb
│   │           │   │   ├── _head.html.erb
│   │           │   │   ├── _index_table_options.html.erb
│   │           │   │   ├── _main_menu.html.erb
│   │           │   │   ├── named_types
│   │           │   │   │   ├── _edit.html.erb
│   │           │   │   │   ├── _form.html.erb
│   │           │   │   │   ├── _index.html.erb
│   │           │   │   │   └── _new.html.erb
│   │           │   │   ├── _new_resource_links.html.erb
│   │           │   │   ├── _order_summary.html.erb
│   │           │   │   ├── _order_tabs.html.erb
│   │           │   │   ├── _product_tabs.html.erb
│   │           │   │   ├── _refunds.html.erb
│   │           │   │   ├── _report_order_criteria.html.erb
│   │           │   │   ├── _sidebar.html.erb
│   │           │   │   ├── sub_menu
│   │           │   │   │   ├── _configuration.html.erb
│   │           │   │   │   ├── _product.html.erb
│   │           │   │   │   ├── _promotion.html.erb
│   │           │   │   │   └── _returns.html.erb
│   │           │   │   ├── _table_filter.html.erb
│   │           │   │   ├── _translations.html.erb
│   │           │   │   ├── _update_order_state.js.erb
│   │           │   │   ├── _update_store_credit.js.erb
│   │           │   │   └── _version.html.erb
│   │           │   ├── shipping_categories
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── shipping_methods
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── state_changes
│   │           │   │   └── index.html.erb
│   │           │   ├── states
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   ├── new.html.erb
│   │           │   │   ├── new.js.erb
│   │           │   │   └── _state_list.html.erb
│   │           │   ├── stock_items
│   │           │   │   └── destroy.js.erb
│   │           │   ├── stock_locations
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   ├── new.html.erb
│   │           │   │   └── _transfer_stock_form.html.erb
│   │           │   ├── stock_movements
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── stock_transfers
│   │           │   │   ├── index.html.erb
│   │           │   │   ├── new.html.erb
│   │           │   │   ├── show.html.erb
│   │           │   │   └── _stock_movements.html.erb
│   │           │   ├── store_credit_categories
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── store_credits
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── stores
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── tax_categories
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   ├── new.html.erb
│   │           │   │   └── show.html.erb
│   │           │   ├── taxonomies
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   ├── _js_head.html.erb
│   │           │   │   ├── _list.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── taxons
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── _taxon_table.html.erb
│   │           │   ├── tax_rates
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── users
│   │           │   │   ├── _addresses_form.html.erb
│   │           │   │   ├── addresses.html.erb
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   ├── items.html.erb
│   │           │   │   ├── _lifetime_stats.html.erb
│   │           │   │   ├── new.html.erb
│   │           │   │   ├── orders.html.erb
│   │           │   │   ├── _sidebar.html.erb
│   │           │   │   └── _user_page_actions.html.erb
│   │           │   ├── variants
│   │           │   │   ├── _autocomplete.js.erb
│   │           │   │   ├── _autocomplete_line_items_stock.js.erb
│   │           │   │   ├── _autocomplete_stock.js.erb
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   ├── new.html.erb
│   │           │   │   ├── new.js.erb
│   │           │   │   ├── _split.js.erb
│   │           │   │   └── update.js.erb
│   │           │   └── zones
│   │           │       ├── _country_members.html.erb
│   │           │       ├── edit.html.erb
│   │           │       ├── _form.html.erb
│   │           │       ├── index.html.erb
│   │           │       ├── new.html.erb
│   │           │       └── _state_members.html.erb
│   │           └── layouts
│   │               └── admin.html.erb
│   ├── config
│   │   ├── initializers
│   │   │   ├── assets.rb
│   │   │   └── form_builder.rb
│   │   └── routes.rb
│   ├── Gemfile
│   ├── lib
│   │   ├── generators
│   │   │   └── spree
│   │   │       └── backend
│   │   │           └── copy_views
│   │   │               └── copy_views_generator.rb
│   │   ├── spree
│   │   │   ├── backend
│   │   │   │   ├── action_callbacks.rb
│   │   │   │   ├── callbacks.rb
│   │   │   │   └── engine.rb
│   │   │   └── backend.rb
│   │   └── spree_backend.rb
│   ├── Rakefile
│   ├── script
│   │   └── rails
│   ├── spec
│   │   ├── controllers
│   │   │   └── spree
│   │   │       └── admin
│   │   │           ├── adjustments_controller_controller_spec.rb
│   │   │           ├── base_controller_spec.rb
│   │   │           ├── customer_returns_controller_spec.rb
│   │   │           ├── general_settings_controller_spec.rb
│   │   │           ├── missing_products_controller_spec.rb
│   │   │           ├── orders
│   │   │           │   └── customer_details_controller_spec.rb
│   │   │           ├── orders_controller_spec.rb
│   │   │           ├── payment_methods_controller_spec.rb
│   │   │           ├── payments_controller_spec.rb
│   │   │           ├── products_controller_spec.rb
│   │   │           ├── promotion_actions_controller_spec.rb
│   │   │           ├── promotion_rules_controller_spec.rb
│   │   │           ├── promotions_controller_spec.rb
│   │   │           ├── refunds_controller_spec.rb
│   │   │           ├── reimbursements_controller_spec.rb
│   │   │           ├── reports_controller_spec.rb
│   │   │           ├── resource_controller_spec.rb
│   │   │           ├── return_authorizations_controller_spec.rb
│   │   │           ├── return_index_controller_spec.rb
│   │   │           ├── return_items_controller_spec.rb
│   │   │           ├── shipping_methods_controller_spec.rb
│   │   │           ├── stock_items_controller_spec.rb
│   │   │           ├── stock_locations_controller_spec.rb
│   │   │           ├── stock_transfers_controller_spec.rb
│   │   │           ├── tax_categories_controller_spec.rb
│   │   │           ├── users_controller_spec.rb
│   │   │           └── variants_controller_spec.rb
│   │   ├── features
│   │   │   └── admin
│   │   │       ├── configuration
│   │   │       │   ├── countries_spec.rb
│   │   │       │   ├── general_settings_spec.rb
│   │   │       │   ├── payment_methods_spec.rb
│   │   │       │   ├── roles_spec.rb
│   │   │       │   ├── shipping_methods_spec.rb
│   │   │       │   ├── states_spec.rb
│   │   │       │   ├── stock_locations_spec.rb
│   │   │       │   ├── store_credit_categories_spec.rb
│   │   │       │   ├── stores_spec.rb
│   │   │       │   ├── tax_categories_spec.rb
│   │   │       │   ├── tax_rates_spec.rb
│   │   │       │   └── zones_spec.rb
│   │   │       ├── homepage_spec.rb
│   │   │       ├── locale_spec.rb
│   │   │       ├── orders
│   │   │       │   ├── adjustments_promotions_spec.rb
│   │   │       │   ├── adjustments_spec.rb
│   │   │       │   ├── cancelling_and_resuming_spec.rb
│   │   │       │   ├── customer_details_spec.rb
│   │   │       │   ├── line_items_spec.rb
│   │   │       │   ├── listing_spec.rb
│   │   │       │   ├── log_entries_spec.rb
│   │   │       │   ├── new_order_spec.rb
│   │   │       │   ├── order_details_spec.rb
│   │   │       │   ├── payments_spec.rb
│   │   │       │   ├── risk_analysis_spec.rb
│   │   │       │   ├── shipments_spec.rb
│   │   │       │   └── state_changes_spec.rb
│   │   │       ├── products
│   │   │       │   ├── edit
│   │   │       │   │   ├── images_spec.rb
│   │   │       │   │   ├── products_spec.rb
│   │   │       │   │   ├── taxons_spec.rb
│   │   │       │   │   └── variants_spec.rb
│   │   │       │   ├── option_types_spec.rb
│   │   │       │   ├── products_spec.rb
│   │   │       │   ├── properties_spec.rb
│   │   │       │   ├── prototypes_spec.rb
│   │   │       │   ├── stock_management_spec.rb
│   │   │       │   ├── taxonomies_spec.rb
│   │   │       │   └── variant_spec.rb
│   │   │       ├── promotions
│   │   │       │   ├── adjustments_spec.rb
│   │   │       │   ├── option_value_rule_spec.rb
│   │   │       │   └── tiered_calculator_spec.rb
│   │   │       ├── refund_reasons
│   │   │       │   └── refund_reasons_spec.rb
│   │   │       ├── reimbursement_type
│   │   │       │   ├── edit_reimbursement_type_spec.rb
│   │   │       │   └── new_reimbursement_type_spec.rb
│   │   │       ├── reports_spec.rb
│   │   │       ├── return_authorization_reasons
│   │   │       │   └── return_authorization_reasons_spec.rb
│   │   │       ├── returns
│   │   │       │   ├── customer_returns_spec.rb
│   │   │       │   └── return_authorizations_spec.rb
│   │   │       ├── stock_transfer_spec.rb
│   │   │       ├── store_credits_spec.rb
│   │   │       ├── taxons_spec.rb
│   │   │       └── users_spec.rb
│   │   ├── helpers
│   │   │   └── spree
│   │   │       └── admin
│   │   │           ├── base_helper_spec.rb
│   │   │           ├── navigation_helper_spec.rb
│   │   │           ├── promotion_rules_helper_spec.rb
│   │   │           └── stock_movements_helper_spec.rb
│   │   ├── models
│   │   │   └── spree
│   │   │       └── resource_spec.rb
│   │   ├── routing
│   │   │   └── admin_path_spec.rb
│   │   ├── spec_helper.rb
│   │   ├── support
│   │   │   ├── appear_before_matcher.rb
│   │   │   └── ror_ringer.jpeg
│   │   └── test_views
│   │       └── spree
│   │           └── admin
│   │               ├── dummy_models
│   │               │   ├── edit.html.erb
│   │               │   └── new.html.erb
│   │               └── submodule
│   │                   └── posts
│   │                       ├── edit.html.erb
│   │                       └── new.html.erb
│   ├── spree_backend.gemspec
│   └── vendor
│       └── assets
│           ├── javascripts
│           │   ├── handlebars.js
│           │   ├── jquery.jstree
│           │   │   └── jquery.jstree.js
│           │   ├── js.cookie.js
│           │   ├── modernizr.js
│           │   └── underscore-min.js
│           └── stylesheets
│               ├── animate.css
│               └── jquery.jstree
│                   └── themes
│                       └── spree
│                           ├── style.scss
│                           └── throbber.gif
├── build-ci.rb
├── build.sh
├── CHANGELOG.md
├── cmd
│   ├── bin
│   │   ├── spree
│   │   └── spree_cmd
│   ├── lib
│   │   ├── spree_cmd
│   │   │   ├── extension.rb
│   │   │   └── templates
│   │   │       └── extension
│   │   │           ├── app
│   │   │           │   └── assets
│   │   │           │       ├── javascripts
│   │   │           │       │   └── spree
│   │   │           │       │       ├── backend
│   │   │           │       │       │   └── %file_name%.js
│   │   │           │       │       └── frontend
│   │   │           │       │           └── %file_name%.js
│   │   │           │       └── stylesheets
│   │   │           │           └── spree
│   │   │           │               ├── backend
│   │   │           │               │   └── %file_name%.css
│   │   │           │               └── frontend
│   │   │           │                   └── %file_name%.css
│   │   │           ├── Appraisals
│   │   │           ├── bin
│   │   │           │   └── rails.tt
│   │   │           ├── config
│   │   │           │   ├── locales
│   │   │           │   │   └── en.yml
│   │   │           │   └── routes.rb
│   │   │           ├── CONTRIBUTING.md
│   │   │           ├── extension.gemspec
│   │   │           ├── Gemfile
│   │   │           ├── gemfiles
│   │   │           │   ├── spree_3_2.gemfile
│   │   │           │   ├── spree_3_5.gemfile
│   │   │           │   ├── spree_3_7.gemfile
│   │   │           │   └── spree_master.gemfile
│   │   │           ├── gitignore
│   │   │           ├── lib
│   │   │           │   ├── %file_name%
│   │   │           │   │   ├── engine.rb.tt
│   │   │           │   │   ├── factories.rb.tt
│   │   │           │   │   └── version.rb.tt
│   │   │           │   ├── %file_name%.rb.tt
│   │   │           │   └── generators
│   │   │           │       └── %file_name%
│   │   │           │           └── install
│   │   │           │               └── install_generator.rb.tt
│   │   │           ├── LICENSE
│   │   │           ├── Rakefile
│   │   │           ├── README.md
│   │   │           ├── rspec
│   │   │           ├── spec
│   │   │           │   ├── spec_helper.rb
│   │   │           │   └── support
│   │   │           │       ├── capybara.rb
│   │   │           │       ├── database_cleaner.rb
│   │   │           │       └── factory_bot.rb
│   │   │           └── travis.yml
│   │   └── spree_cmd.rb
│   ├── LICENSE
│   ├── Rakefile
│   ├── README.md
│   └── spree_cmd.gemspec
├── CODE_OF_CONDUCT.md
├── common_spree_dependencies.rb
├── core
│   ├── app
│   │   ├── assets
│   │   │   ├── images
│   │   │   │   ├── logo
│   │   │   │   │   └── spree_50.png
│   │   │   │   └── noimage
│   │   │   │       ├── large.png
│   │   │   │       ├── mini.png
│   │   │   │       ├── product.png
│   │   │   │       └── small.png
│   │   │   └── javascripts
│   │   │       └── spree.js
│   │   ├── controllers
│   │   │   └── spree
│   │   │       └── base_controller.rb
│   │   ├── finders
│   │   │   └── spree
│   │   │       ├── countries
│   │   │       │   └── find.rb
│   │   │       ├── credit_cards
│   │   │       │   └── find.rb
│   │   │       ├── line_items
│   │   │       │   └── find_by_variant.rb
│   │   │       ├── orders
│   │   │       │   ├── find_complete.rb
│   │   │       │   └── find_current.rb
│   │   │       ├── products
│   │   │       │   └── find.rb
│   │   │       └── taxons
│   │   │           └── find.rb
│   │   ├── helpers
│   │   │   └── spree
│   │   │       ├── base_helper.rb
│   │   │       └── products_helper.rb
│   │   ├── mailers
│   │   │   └── spree
│   │   │       ├── base_mailer.rb
│   │   │       ├── order_mailer.rb
│   │   │       ├── reimbursement_mailer.rb
│   │   │       ├── shipment_mailer.rb
│   │   │       └── test_mailer.rb
│   │   ├── models
│   │   │   ├── concerns
│   │   │   │   └── spree
│   │   │   │       ├── acts_as_taggable.rb
│   │   │   │       ├── adjustment_source.rb
│   │   │   │       ├── calculated_adjustments.rb
│   │   │   │       ├── default_price.rb
│   │   │   │       ├── display_money.rb
│   │   │   │       ├── named_type.rb
│   │   │   │       ├── number_as_param.rb
│   │   │   │       ├── product_scopes.rb
│   │   │   │       ├── ransackable_attributes.rb
│   │   │   │       ├── user_address.rb
│   │   │   │       ├── user_methods.rb
│   │   │   │       ├── user_payment_source.rb
│   │   │   │       ├── user_reporting.rb
│   │   │   │       └── vat_price_calculation.rb
│   │   │   ├── friendly_id
│   │   │   │   └── slug_decorator.rb
│   │   │   └── spree
│   │   │       ├── ability.rb
│   │   │       ├── address.rb
│   │   │       ├── adjustable
│   │   │       │   ├── adjuster
│   │   │       │   │   ├── base.rb
│   │   │       │   │   ├── promotion.rb
│   │   │       │   │   └── tax.rb
│   │   │       │   ├── adjustments_updater.rb
│   │   │       │   └── promotion_accumulator.rb
│   │   │       ├── adjustment.rb
│   │   │       ├── app_configuration.rb
│   │   │       ├── app_dependencies.rb
│   │   │       ├── asset
│   │   │       │   └── support
│   │   │       │       └── active_storage.rb
│   │   │       ├── asset.rb
│   │   │       ├── base.rb
│   │   │       ├── calculator
│   │   │       │   ├── default_tax.rb
│   │   │       │   ├── flat_percent_item_total.rb
│   │   │       │   ├── flat_rate.rb
│   │   │       │   ├── flexi_rate.rb
│   │   │       │   ├── percent_on_line_item.rb
│   │   │       │   ├── price_sack.rb
│   │   │       │   ├── returns
│   │   │       │   │   └── default_refund_amount.rb
│   │   │       │   ├── shipping
│   │   │       │   │   ├── flat_percent_item_total.rb
│   │   │       │   │   ├── flat_rate.rb
│   │   │       │   │   ├── flexi_rate.rb
│   │   │       │   │   ├── per_item.rb
│   │   │       │   │   └── price_sack.rb
│   │   │       │   ├── tiered_flat_rate.rb
│   │   │       │   └── tiered_percent.rb
│   │   │       ├── calculator.rb
│   │   │       ├── classification.rb
│   │   │       ├── country.rb
│   │   │       ├── credit_card.rb
│   │   │       ├── customer_return.rb
│   │   │       ├── exchange.rb
│   │   │       ├── fulfilment_changer.rb
│   │   │       ├── gateway
│   │   │       │   ├── bogus.rb
│   │   │       │   └── bogus_simple.rb
│   │   │       ├── gateway.rb
│   │   │       ├── image
│   │   │       │   └── configuration
│   │   │       │       └── active_storage.rb
│   │   │       ├── image.rb
│   │   │       ├── inventory_unit.rb
│   │   │       ├── legacy_user.rb
│   │   │       ├── line_item.rb
│   │   │       ├── log_entry.rb
│   │   │       ├── option_type_prototype.rb
│   │   │       ├── option_type.rb
│   │   │       ├── option_value.rb
│   │   │       ├── option_value_variant.rb
│   │   │       ├── order
│   │   │       │   ├── checkout.rb
│   │   │       │   ├── currency_updater.rb
│   │   │       │   ├── payments.rb
│   │   │       │   └── store_credit.rb
│   │   │       ├── order_inventory.rb
│   │   │       ├── order_merger.rb
│   │   │       ├── order_promotion.rb
│   │   │       ├── order.rb
│   │   │       ├── order_updater.rb
│   │   │       ├── payment
│   │   │       │   ├── gateway_options.rb
│   │   │       │   └── processing.rb
│   │   │       ├── payment_capture_event.rb
│   │   │       ├── payment_method
│   │   │       │   ├── check.rb
│   │   │       │   └── store_credit.rb
│   │   │       ├── payment_method.rb
│   │   │       ├── payment.rb
│   │   │       ├── preference.rb
│   │   │       ├── preferences
│   │   │       │   ├── configuration.rb
│   │   │       │   ├── preferable_class_methods.rb
│   │   │       │   ├── preferable.rb
│   │   │       │   ├── scoped_store.rb
│   │   │       │   └── store.rb
│   │   │       ├── price.rb
│   │   │       ├── product_option_type.rb
│   │   │       ├── product_promotion_rule.rb
│   │   │       ├── product_property.rb
│   │   │       ├── product.rb
│   │   │       ├── promotion
│   │   │       │   ├── actions
│   │   │       │   │   ├── create_adjustment.rb
│   │   │       │   │   ├── create_item_adjustments.rb
│   │   │       │   │   ├── create_line_items.rb
│   │   │       │   │   └── free_shipping.rb
│   │   │       │   └── rules
│   │   │       │       ├── country.rb
│   │   │       │       ├── first_order.rb
│   │   │       │       ├── item_total.rb
│   │   │       │       ├── one_use_per_user.rb
│   │   │       │       ├── option_value.rb
│   │   │       │       ├── product.rb
│   │   │       │       ├── taxon.rb
│   │   │       │       ├── user_logged_in.rb
│   │   │       │       └── user.rb
│   │   │       ├── promotion_action_line_item.rb
│   │   │       ├── promotion_action.rb
│   │   │       ├── promotion_category.rb
│   │   │       ├── promotion_handler
│   │   │       │   ├── cart.rb
│   │   │       │   ├── coupon.rb
│   │   │       │   ├── free_shipping.rb
│   │   │       │   ├── page.rb
│   │   │       │   └── promotion_duplicator.rb
│   │   │       ├── promotion.rb
│   │   │       ├── promotion_rule.rb
│   │   │       ├── promotion_rule_taxon.rb
│   │   │       ├── promotion_rule_user.rb
│   │   │       ├── property_prototype.rb
│   │   │       ├── property.rb
│   │   │       ├── prototype.rb
│   │   │       ├── prototype_taxon.rb
│   │   │       ├── refund.rb
│   │   │       ├── refund_reason.rb
│   │   │       ├── reimbursement
│   │   │       │   ├── credit.rb
│   │   │       │   ├── reimbursement_type_engine.rb
│   │   │       │   └── reimbursement_type_validator.rb
│   │   │       ├── reimbursement_performer.rb
│   │   │       ├── reimbursement.rb
│   │   │       ├── reimbursement_tax_calculator.rb
│   │   │       ├── reimbursement_type
│   │   │       │   ├── credit.rb
│   │   │       │   ├── exchange.rb
│   │   │       │   ├── original_payment.rb
│   │   │       │   ├── reimbursement_helpers.rb
│   │   │       │   └── store_credit.rb
│   │   │       ├── reimbursement_type.rb
│   │   │       ├── return_authorization.rb
│   │   │       ├── return_authorization_reason.rb
│   │   │       ├── return_item
│   │   │       │   ├── eligibility_validator
│   │   │       │   │   ├── base_validator.rb
│   │   │       │   │   ├── default.rb
│   │   │       │   │   ├── inventory_shipped.rb
│   │   │       │   │   ├── no_reimbursements.rb
│   │   │       │   │   ├── order_completed.rb
│   │   │       │   │   ├── rma_required.rb
│   │   │       │   │   └── time_since_purchase.rb
│   │   │       │   └── exchange_variant_eligibility
│   │   │       │       ├── same_option_value.rb
│   │   │       │       └── same_product.rb
│   │   │       ├── return_item.rb
│   │   │       ├── returns_calculator.rb
│   │   │       ├── role.rb
│   │   │       ├── role_user.rb
│   │   │       ├── shipment_handler.rb
│   │   │       ├── shipment.rb
│   │   │       ├── shipping_calculator.rb
│   │   │       ├── shipping_category.rb
│   │   │       ├── shipping_method_category.rb
│   │   │       ├── shipping_method.rb
│   │   │       ├── shipping_method_zone.rb
│   │   │       ├── shipping_rate.rb
│   │   │       ├── state_change.rb
│   │   │       ├── state.rb
│   │   │       ├── stock
│   │   │       │   ├── adjuster.rb
│   │   │       │   ├── availability_validator.rb
│   │   │       │   ├── content_item.rb
│   │   │       │   ├── coordinator.rb
│   │   │       │   ├── differentiator.rb
│   │   │       │   ├── estimator.rb
│   │   │       │   ├── inventory_unit_builder.rb
│   │   │       │   ├── package.rb
│   │   │       │   ├── packer.rb
│   │   │       │   ├── prioritizer.rb
│   │   │       │   ├── quantifier.rb
│   │   │       │   └── splitter
│   │   │       │       ├── backordered.rb
│   │   │       │       ├── base.rb
│   │   │       │       ├── shipping_category.rb
│   │   │       │       └── weight.rb
│   │   │       ├── stock_item.rb
│   │   │       ├── stock_location.rb
│   │   │       ├── stock_movement.rb
│   │   │       ├── stock_transfer.rb
│   │   │       ├── store_credit_category.rb
│   │   │       ├── store_credit_event.rb
│   │   │       ├── store_credit.rb
│   │   │       ├── store_credit_type.rb
│   │   │       ├── store.rb
│   │   │       ├── tag.rb
│   │   │       ├── tax_category.rb
│   │   │       ├── taxon_image
│   │   │       │   └── configuration
│   │   │       │       └── active_storage.rb
│   │   │       ├── taxon_image.rb
│   │   │       ├── taxonomy.rb
│   │   │       ├── taxon.rb
│   │   │       ├── tax_rate.rb
│   │   │       ├── validations
│   │   │       │   └── db_maximum_length_validator.rb
│   │   │       ├── variant.rb
│   │   │       ├── zone_member.rb
│   │   │       └── zone.rb
│   │   ├── paginators
│   │   │   └── spree
│   │   │       └── shared
│   │   │           └── paginate.rb
│   │   ├── services
│   │   │   └── spree
│   │   │       ├── cart
│   │   │       │   ├── add_item.rb
│   │   │       │   ├── create.rb
│   │   │       │   ├── estimate_shipping_rates.rb
│   │   │       │   ├── recalculate.rb
│   │   │       │   ├── remove_item.rb
│   │   │       │   ├── remove_line_item.rb
│   │   │       │   ├── set_quantity.rb
│   │   │       │   └── update.rb
│   │   │       ├── checkout
│   │   │       │   ├── add_store_credit.rb
│   │   │       │   ├── advance.rb
│   │   │       │   ├── complete.rb
│   │   │       │   ├── get_shipping_rates.rb
│   │   │       │   ├── next.rb
│   │   │       │   ├── remove_store_credit.rb
│   │   │       │   └── update.rb
│   │   │       ├── compare_line_items.rb
│   │   │       └── generate_token.rb
│   │   ├── sorters
│   │   │   └── spree
│   │   │       ├── orders
│   │   │       │   └── sort.rb
│   │   │       └── products
│   │   │           └── sort.rb
│   │   ├── validators
│   │   │   ├── db_maximum_length_validator.rb
│   │   │   └── email_validator.rb
│   │   └── views
│   │       ├── layouts
│   │       │   └── spree
│   │       │       └── base_mailer.html.erb
│   │       └── spree
│   │           ├── order_mailer
│   │           │   ├── _adjustment.html.erb
│   │           │   ├── cancel_email.html.erb
│   │           │   ├── cancel_email.text.erb
│   │           │   ├── confirm_email.html.erb
│   │           │   ├── confirm_email.text.erb
│   │           │   ├── _subtotal.html.erb
│   │           │   └── _total.html.erb
│   │           ├── reimbursement_mailer
│   │           │   ├── reimbursement_email.html.erb
│   │           │   └── reimbursement_email.text.erb
│   │           ├── shared
│   │           │   ├── _base_mailer_footer.html.erb
│   │           │   ├── _base_mailer_header.html.erb
│   │           │   ├── _base_mailer_stylesheets.html.erb
│   │           │   ├── _error_messages.html.erb
│   │           │   ├── _mailer_line_item.html.erb
│   │           │   └── _paths.html.erb
│   │           ├── shipment_mailer
│   │           │   ├── shipped_email.html.erb
│   │           │   └── shipped_email.text.erb
│   │           └── test_mailer
│   │               ├── test_email.html.erb
│   │               └── test_email.text.erb
│   ├── config
│   │   ├── initializers
│   │   │   ├── active_storage.rb
│   │   │   ├── acts_as_taggable_on.rb
│   │   │   ├── assets.rb
│   │   │   ├── friendly_id.rb
│   │   │   ├── premailer_assets.rb
│   │   │   ├── premailer_rails.rb
│   │   │   └── state_machine.rb
│   │   ├── locales
│   │   │   └── en.yml
│   │   └── routes.rb
│   ├── db
│   │   ├── default
│   │   │   └── spree
│   │   │       ├── countries.rb
│   │   │       ├── default_reimbursement_type.rb
│   │   │       ├── roles.rb
│   │   │       ├── states.rb
│   │   │       ├── stores.rb
│   │   │       └── zones.rb
│   │   ├── migrate
│   │   │   ├── 20120831092320_spree_one_two.rb
│   │   │   ├── 20120831092359_spree_promo_one_two.rb
│   │   │   ├── 20120905145253_add_tax_rate_label.rb
│   │   │   ├── 20120905151823_add_toggle_tax_rate_display.rb
│   │   │   ├── 20120929093553_remove_unused_preference_columns.rb
│   │   │   ├── 20121009142519_add_lock_version_to_variant.rb
│   │   │   ├── 20121010142909_add_states_required_to_countries.rb
│   │   │   ├── 20121012071449_add_on_demand_to_product_and_variant.rb
│   │   │   ├── 20121017010007_remove_not_null_constraint_from_products_on_hand.rb
│   │   │   ├── 20121031162139_split_prices_from_variants.rb
│   │   │   ├── 20121107003422_remove_not_null_from_spree_prices_amount.rb
│   │   │   ├── 20121107184631_add_currency_to_line_items.rb
│   │   │   ├── 20121107194006_add_currency_to_orders.rb
│   │   │   ├── 20121109173623_add_cost_currency_to_variants.rb
│   │   │   ├── 20121111231553_remove_display_on_from_payment_methods.rb
│   │   │   ├── 20121124203911_add_position_to_taxonomies.rb
│   │   │   ├── 20121126040517_add_last_ip_to_spree_orders.rb
│   │   │   ├── 20121213162028_add_state_to_spree_adjustments.rb
│   │   │   ├── 20130114053446_add_display_on_to_spree_payment_methods.rb
│   │   │   ├── 20130120201805_add_position_to_product_properties.spree.rb
│   │   │   ├── 20130203232234_add_identifier_to_spree_payments.rb
│   │   │   ├── 20130207155350_add_order_id_index_to_payments.rb
│   │   │   ├── 20130208032954_add_primary_to_spree_products_taxons.rb
│   │   │   ├── 20130211190146_create_spree_stock_items.rb
│   │   │   ├── 20130211191120_create_spree_stock_locations.rb
│   │   │   ├── 20130213191427_create_default_stock.rb
│   │   │   ├── 20130222032153_add_order_id_index_to_shipments.rb
│   │   │   ├── 20130226032817_change_meta_description_on_spree_products_to_text.rb
│   │   │   ├── 20130226191231_add_stock_location_id_to_spree_shipments.rb
│   │   │   ├── 20130227143905_add_pending_to_inventory_unit.rb
│   │   │   ├── 20130228164411_remove_on_demand_from_product_and_variant.rb
│   │   │   ├── 20130228210442_create_shipping_method_zone.rb
│   │   │   ├── 20130301162745_remove_shipping_category_id_from_shipping_method.rb
│   │   │   ├── 20130301162924_create_shipping_method_categories.rb
│   │   │   ├── 20130301205200_add_tracking_url_to_spree_shipping_methods.rb
│   │   │   ├── 20130304162240_create_spree_shipping_rates.rb
│   │   │   ├── 20130304192936_remove_category_match_attributes_from_shipping_method.rb
│   │   │   ├── 20130305143310_create_stock_movements.rb
│   │   │   ├── 20130306181701_add_address_fields_to_stock_location.rb
│   │   │   ├── 20130306191917_add_active_field_to_stock_locations.rb
│   │   │   ├── 20130306195650_add_backorderable_to_stock_item.rb
│   │   │   ├── 20130307161754_add_default_quantity_to_stock_movement.rb
│   │   │   ├── 20130318151756_add_source_and_destination_to_stock_movements.rb
│   │   │   ├── 20130319062004_change_orders_total_precision.rb
│   │   │   ├── 20130319063911_change_spree_payments_amount_precision.rb
│   │   │   ├── 20130319064308_change_spree_return_authorization_amount_precision.rb
│   │   │   ├── 20130319082943_change_adjustments_amount_precision.rb
│   │   │   ├── 20130319183250_add_originator_to_stock_movement.rb
│   │   │   ├── 20130319190507_drop_source_and_destination_from_stock_movement.rb
│   │   │   ├── 20130325163316_migrate_inventory_unit_sold_to_on_hand.rb
│   │   │   ├── 20130326175857_add_stock_location_to_rma.rb
│   │   │   ├── 20130328130308_update_shipment_state_for_canceled_orders.rb
│   │   │   ├── 20130328195253_add_seo_metas_to_taxons.rb
│   │   │   ├── 20130329134939_remove_stock_item_and_variant_lock.rb
│   │   │   ├── 20130413230529_add_name_to_spree_credit_cards.rb
│   │   │   ├── 20130414000512_update_name_fields_on_spree_credit_cards.rb
│   │   │   ├── 20130417120034_add_index_to_source_columns_on_adjustments.rb
│   │   │   ├── 20130417120035_update_adjustment_states.rb
│   │   │   ├── 20130417123427_add_shipping_rates_to_shipments.rb
│   │   │   ├── 20130418125341_create_spree_stock_transfers.rb
│   │   │   ├── 20130423110707_drop_products_count_on_hand.rb
│   │   │   ├── 20130423223847_set_default_shipping_rate_cost.rb
│   │   │   ├── 20130509115210_add_number_to_stock_transfer.rb
│   │   │   ├── 20130514151929_add_sku_index_to_spree_variants.rb
│   │   │   ├── 20130515180736_add_backorderable_default_to_spree_stock_location.rb
│   │   │   ├── 20130516151222_add_propage_all_variants_to_spree_stock_location.rb
│   │   │   ├── 20130611054351_rename_shipping_methods_zones_to_spree_shipping_methods_zones.rb
│   │   │   ├── 20130611185927_add_user_id_index_to_spree_orders.rb
│   │   │   ├── 20130618041418_add_updated_at_to_spree_countries.rb
│   │   │   ├── 20130619012236_add_updated_at_to_spree_states.rb
│   │   │   ├── 20130626232741_add_cvv_result_code_and_cvv_result_message_to_spree_payments.rb
│   │   │   ├── 20130628021056_add_unique_index_to_permalink_on_spree_products.rb
│   │   │   ├── 20130628022817_add_unique_index_to_orders_shipments_and_stock_transfers.rb
│   │   │   ├── 20130708052307_add_deleted_at_to_spree_tax_rates.rb
│   │   │   ├── 20130711200933_remove_lock_version_from_inventory_units.rb
│   │   │   ├── 20130718042445_add_cost_price_to_line_item.rb
│   │   │   ├── 20130718233855_set_backorderable_to_default_to_false.rb
│   │   │   ├── 20130725031716_add_created_by_id_to_spree_orders.rb
│   │   │   ├── 20130729214043_index_completed_at_on_spree_orders.rb
│   │   │   ├── 20130802014537_add_tax_category_id_to_spree_line_items.rb
│   │   │   ├── 20130802022321_migrate_tax_categories_to_line_items.rb
│   │   │   ├── 20130806022521_drop_spree_mail_methods.rb
│   │   │   ├── 20130806145853_set_default_stock_location_on_shipments.rb
│   │   │   ├── 20130807024301_upgrade_adjustments.rb
│   │   │   ├── 20130807024302_rename_adjustment_fields.rb
│   │   │   ├── 20130809164245_add_admin_name_column_to_spree_shipping_methods.rb
│   │   │   ├── 20130809164330_add_admin_name_column_to_spree_stock_locations.rb
│   │   │   ├── 20130813004002_add_shipment_total_to_spree_orders.rb
│   │   │   ├── 20130813140619_expand_order_number_size.rb
│   │   │   ├── 20130813232134_rename_activators_to_promotions.rb
│   │   │   ├── 20130815000406_add_adjustment_total_to_line_items.rb
│   │   │   ├── 20130815024413_add_adjustment_total_to_shipments.rb
│   │   │   ├── 20130826062534_add_depth_to_spree_taxons.rb
│   │   │   ├── 20130828234942_add_tax_total_to_line_items_shipments_and_orders.rb
│   │   │   ├── 20130830001033_add_shipping_category_to_shipping_methods_and_products.rb
│   │   │   ├── 20130830001159_migrate_old_shipping_calculators.rb
│   │   │   ├── 20130903183026_add_code_to_spree_promotion_rules.rb
│   │   │   ├── 20130909115621_change_states_required_for_countries.rb
│   │   │   ├── 20130915032339_add_deleted_at_to_spree_stock_items.rb
│   │   │   ├── 20130917024658_remove_promotions_event_name_field.rb
│   │   │   ├── 20130924040529_add_promo_total_to_line_items_and_shipments_and_orders.rb
│   │   │   ├── 20131001013410_remove_unused_credit_card_fields.rb
│   │   │   ├── 20131026154747_add_track_inventory_to_variant.rb
│   │   │   ├── 20131107132123_add_tax_category_to_variants.rb
│   │   │   ├── 20131113035136_add_channel_to_spree_orders.rb
│   │   │   ├── 20131118043959_add_included_to_adjustments.rb
│   │   │   ├── 20131118050234_rename_tax_total_fields.rb
│   │   │   ├── 20131118183431_add_line_item_id_to_spree_inventory_units.rb
│   │   │   ├── 20131120234456_add_updated_at_to_variants.rb
│   │   │   ├── 20131127001002_add_position_to_classifications.rb
│   │   │   ├── 20131211112807_create_spree_orders_promotions.rb
│   │   │   ├── 20131211192741_unique_shipping_method_categories.rb
│   │   │   ├── 20131218054603_add_item_count_to_spree_orders.rb
│   │   │   ├── 20140106065820_remove_value_type_from_spree_preferences.rb
│   │   │   ├── 20140106224208_rename_permalink_to_slug_for_products.rb
│   │   │   ├── 20140120160805_add_index_to_variant_id_and_currency_on_prices.rb
│   │   │   ├── 20140124023232_rename_activator_id_in_rules_and_actions_to_promotion_id.rb
│   │   │   ├── 20140129024326_add_deleted_at_to_spree_prices.rb
│   │   │   ├── 20140203161722_add_approver_id_and_approved_at_to_orders.rb
│   │   │   ├── 20140204115338_add_confirmation_delivered_to_spree_orders.rb
│   │   │   ├── 20140204192230_add_auto_capture_to_payment_methods.rb
│   │   │   ├── 20140205120320_create_spree_payment_capture_events.rb
│   │   │   ├── 20140205144710_add_uncaptured_amount_to_payments.rb
│   │   │   ├── 20140205181631_default_variant_weight_to_zero.rb
│   │   │   ├── 20140207085910_add_tax_category_id_to_shipping_methods.rb
│   │   │   ├── 20140207093021_add_tax_rate_id_to_shipping_rates.rb
│   │   │   ├── 20140211040159_add_pre_tax_amount_to_line_items_and_shipments.rb
│   │   │   ├── 20140213184916_add_more_indexes.rb
│   │   │   ├── 20140219060952_add_considered_risky_to_orders.rb
│   │   │   ├── 20140227112348_add_preference_store_to_everything.rb
│   │   │   ├── 20140307235515_add_user_id_to_spree_credit_cards.rb
│   │   │   ├── 20140309023735_migrate_old_preferences.rb
│   │   │   ├── 20140309024355_create_spree_stores.rb
│   │   │   ├── 20140309033438_create_store_from_preferences.rb
│   │   │   ├── 20140315053743_add_timestamps_to_spree_assets.rb
│   │   │   ├── 20140318191500_create_spree_taxons_promotion_rules.rb
│   │   │   ├── 20140331100557_add_additional_store_fields.rb
│   │   │   ├── 20140410141842_add_many_missing_indexes.rb
│   │   │   ├── 20140410150358_correct_some_polymorphic_index_and_add_more_missing.rb
│   │   │   ├── 20140415041315_add_user_id_created_by_id_index_to_order.rb
│   │   │   ├── 20140508151342_change_spree_price_amount_precision.rb
│   │   │   ├── 20140518174634_add_token_to_spree_orders.rb
│   │   │   ├── 20140530024945_move_order_token_from_tokenized_permission.rb
│   │   │   ├── 20140601011216_set_shipment_total_for_users_upgrading.rb
│   │   │   ├── 20140604135309_drop_credit_card_first_name_and_last_name.rb
│   │   │   ├── 20140609201656_add_deleted_at_to_spree_promotion_actions.rb
│   │   │   ├── 20140616202624_remove_uncaptured_amount_from_spree_payments.rb
│   │   │   ├── 20140625214618_create_spree_refunds.rb
│   │   │   ├── 20140702140656_create_spree_return_authorization_inventory_unit.rb
│   │   │   ├── 20140707125621_rename_return_authorization_inventory_unit_to_return_items.rb
│   │   │   ├── 20140709160534_backfill_line_item_pre_tax_amount.rb
│   │   │   ├── 20140710041921_recreate_spree_return_authorizations.rb
│   │   │   ├── 20140710181204_add_amount_fields_to_return_items.rb
│   │   │   ├── 20140710190048_drop_return_authorization_amount.rb
│   │   │   ├── 20140713140455_create_spree_return_authorization_reasons.rb
│   │   │   ├── 20140713140527_create_spree_refund_reasons.rb
│   │   │   ├── 20140713142214_rename_return_authorization_reason.rb
│   │   │   ├── 20140715182625_create_spree_promotion_categories.rb
│   │   │   ├── 20140716204111_drop_received_at_on_return_items.rb
│   │   │   ├── 20140716212330_add_reception_and_acceptance_status_to_return_items.rb
│   │   │   ├── 20140717155155_create_default_refund_reason.rb
│   │   │   ├── 20140717185932_add_default_to_spree_stock_locations.rb
│   │   │   ├── 20140718133010_create_spree_customer_returns.rb
│   │   │   ├── 20140718133349_add_customer_return_id_to_return_item.rb
│   │   │   ├── 20140718195325_create_friendly_id_slugs.rb
│   │   │   ├── 20140723004419_rename_spree_refund_return_authorization_id.rb
│   │   │   ├── 20140723152808_increase_return_item_pre_tax_amount_precision.rb
│   │   │   ├── 20140723214541_copy_product_slugs_to_slug_history.rb
│   │   │   ├── 20140725131539_create_spree_reimbursements.rb
│   │   │   ├── 20140728225422_add_promotionable_to_spree_products.rb
│   │   │   ├── 20140729133613_add_exchange_inventory_unit_foreign_keys.rb
│   │   │   ├── 20140730155938_add_acceptance_status_errors_to_return_item.rb
│   │   │   ├── 20140731150017_create_spree_reimbursement_types.rb
│   │   │   ├── 20140804185157_add_default_to_shipment_cost.rb
│   │   │   ├── 20140805171035_add_default_to_spree_credit_cards.rb
│   │   │   ├── 20140805171219_make_existing_credit_cards_default.rb
│   │   │   ├── 20140806144901_add_type_to_reimbursement_type.rb
│   │   │   ├── 20140808184039_create_spree_reimbursement_credits.rb
│   │   │   ├── 20140827170513_add_meta_title_to_spree_products.rb
│   │   │   ├── 20140911173301_add_kind_to_zone.rb
│   │   │   ├── 20140924164824_add_code_to_spree_tax_categories.rb
│   │   │   ├── 20140927193717_default_pre_tax_amount_should_be_zero.rb
│   │   │   ├── 20141002191113_add_code_to_spree_shipping_methods.rb
│   │   │   ├── 20141007230328_add_cancel_audit_fields_to_spree_orders.rb
│   │   │   ├── 20141009204607_add_store_id_to_orders.rb
│   │   │   ├── 20141012083513_create_spree_taxons_prototypes.rb
│   │   │   ├── 20141021194502_add_state_lock_version_to_order.rb
│   │   │   ├── 20141023005240_add_counter_cache_from_spree_variants_to_spree_stock_items.rb
│   │   │   ├── 20141101231208_fix_adjustment_order_presence.rb
│   │   │   ├── 20141105213646_update_classifications_positions.rb
│   │   │   ├── 20141120135441_add_guest_token_index_to_spree_orders.rb
│   │   │   ├── 20141215232040_remove_token_permissions_table.rb
│   │   │   ├── 20141215235502_remove_extra_products_slug_index.rb
│   │   │   ├── 20141217215630_update_product_slug_index.rb
│   │   │   ├── 20141218025915_rename_identifier_to_number_for_payment.rb
│   │   │   ├── 20150118210639_create_spree_store_credits.rb
│   │   │   ├── 20150118211500_create_spree_store_credit_categories.rb
│   │   │   ├── 20150118212051_create_spree_store_credit_events.rb
│   │   │   ├── 20150118212101_create_spree_store_credit_types.rb
│   │   │   ├── 20150121022521_remove_environment_from_payment_method.rb
│   │   │   ├── 20150122145607_add_resellable_to_return_items.rb
│   │   │   ├── 20150122202432_add_code_to_spree_promotion_categories.rb
│   │   │   ├── 20150128032538_remove_environment_from_tracker.rb
│   │   │   ├── 20150128060325_remove_spree_configurations.rb
│   │   │   ├── 20150216173445_add_index_to_spree_stock_items_variant_id.rb
│   │   │   ├── 20150309161154_ensure_payments_have_numbers.rb
│   │   │   ├── 20150314013438_add_missing_indexes_on_spree_tables.rb
│   │   │   ├── 20150317174308_remove_duplicated_indexes_from_multi_columns.rb
│   │   │   ├── 20150324104002_remove_user_index_from_spree_state_changes.rb
│   │   │   ├── 20150515211137_fix_adjustment_order_id.rb
│   │   │   ├── 20150522071831_add_position_to_spree_payment_methods.rb
│   │   │   ├── 20150522181728_add_deleted_at_to_friendly_id_slugs.rb
│   │   │   ├── 20150609093816_increase_scale_on_pre_tax_amounts.rb
│   │   │   ├── 20150626181949_add_taxable_adjustment_total_to_line_item.rb
│   │   │   ├── 20150627090949_migrate_payment_methods_display.rb
│   │   │   ├── 20150707204155_enable_acts_as_paranoid_on_calculators.rb
│   │   │   ├── 20150714154102_spree_payment_method_store_credits.rb
│   │   │   ├── 20150726141425_rename_has_and_belongs_to_associations_to_model_names.rb
│   │   │   ├── 20150727191614_spree_store_credit_types.rb
│   │   │   ├── 20150819154308_add_discontinued_to_products_and_variants.rb
│   │   │   ├── 20151220072838_remove_shipping_method_id_from_spree_orders.rb
│   │   │   ├── 20160207191757_add_id_column_to_earlier_habtm_tables.rb
│   │   │   ├── 20160219165458_add_indexes.rb
│   │   │   ├── 20160509064646_remove_counter_cache_from_spree_variants_to_spree_stock_items.rb
│   │   │   ├── 20160511071954_acts_as_taggable_on_spree_migration.rb
│   │   │   ├── 20160511072249_change_collation_for_spree_tag_names.rb
│   │   │   ├── 20160511072335_add_missing_indexes_to_spree_taggings.rb
│   │   │   ├── 20160608090604_add_zipcode_required_to_spree_countries.rb
│   │   │   ├── 20161014145148_add_created_at_to_variant.rb
│   │   │   ├── 20161014152814_add_null_false_to_spree_variants_timestamps.rb
│   │   │   ├── 20161125065505_add_quantity_to_inventory_units.rb
│   │   │   ├── 20170119122701_add_original_return_item_id_to_spree_inventory_units.rb
│   │   │   ├── 20170315152755_add_unique_index_on_number_to_spree_orders.rb
│   │   │   ├── 20170316154338_add_unique_index_on_number_to_spree_stock_transfer.rb
│   │   │   ├── 20170316205511_add_unique_index_on_number_to_spree_shipment.rb
│   │   │   ├── 20170320134043_add_unique_index_on_number_to_spree_payments.rb
│   │   │   ├── 20170320142750_add_unique_index_on_number_to_spree_return_authorizations.rb
│   │   │   ├── 20170320145040_add_unique_index_on_number_to_spree_customer_returns.rb
│   │   │   ├── 20170320145518_add_unique_index_on_number_to_spree_reimbursements.rb
│   │   │   ├── 20170323151450_add_missing_unique_indexes_for_unique_attributes.rb
│   │   │   ├── 20170329110859_add_index_on_stock_location_to_spree_customer_returns.rb
│   │   │   ├── 20170329113917_add_index_on_prototype_to_spree_option_type_prototype.rb
│   │   │   ├── 20170330082155_add_indexes_to_spree_option_value_variant.rb
│   │   │   ├── 20170330132215_add_index_on_promotion_id_to_order_promotions.rb
│   │   │   ├── 20170331101758_add_indexes_for_property_prototype.rb
│   │   │   ├── 20170331103334_add_index_for_prototype_id_to_prototype_taxons.rb
│   │   │   ├── 20170331110454_add_indexes_to_refunds.rb
│   │   │   ├── 20170331111757_add_indexes_to_reimbursement_credits.rb
│   │   │   ├── 20170331115246_add_indexes_to_return_authorizations.rb
│   │   │   ├── 20170331120125_add_indexes_to_return_items.rb
│   │   │   ├── 20170331121725_add_index_to_role_users.rb
│   │   │   ├── 20170331123625_add_index_to_shipping_method_categories.rb
│   │   │   ├── 20170331123832_add_index_to_shipping_method_zones.rb
│   │   │   ├── 20170331124251_add_index_to_spree_shipping_rates.rb
│   │   │   ├── 20170331124513_add_index_to_spree_stock_items.rb
│   │   │   ├── 20170331124924_add_index_to_spree_stock_movement.rb
│   │   │   ├── 20170413211707_change_indexes_on_friendly_id_slugs.rb
│   │   │   ├── 20170722102643_add_analytics_kind_to_spree_trackers.rb
│   │   │   ├── 20170727103056_rename_tracker_kind_field.rb
│   │   │   ├── 20171004223836_remove_icon_from_taxons.rb
│   │   │   ├── 20180222133746_add_unique_index_on_spree_promotions_code.rb
│   │   │   ├── 20180613080857_rename_guest_token_to_token_in_orders.rb
│   │   │   ├── 20180915160001_add_timestamps_to_spree_prices.rb
│   │   │   ├── 20181024100754_add_deleted_at_to_spree_credit_cards.rb
│   │   │   └── 20190305121659_add_iso_and_iso3_validation_on_presence_and_uniqueness.rb
│   │   └── seeds.rb
│   ├── Gemfile
│   ├── lib
│   │   ├── friendly_id
│   │   │   └── slug_rails5_patch.rb
│   │   ├── generators
│   │   │   └── spree
│   │   │       ├── custom_user
│   │   │       │   ├── custom_user_generator.rb
│   │   │       │   └── templates
│   │   │       │       ├── authentication_helpers.rb.tt
│   │   │       │       ├── initializer.rb.tt
│   │   │       │       └── migration.rb.tt
│   │   │       ├── dummy
│   │   │       │   ├── dummy_generator.rb
│   │   │       │   └── templates
│   │   │       │       ├── initializers
│   │   │       │       │   └── devise.rb
│   │   │       │       └── rails
│   │   │       │           ├── application.rb
│   │   │       │           ├── boot.rb
│   │   │       │           ├── database.yml
│   │   │       │           ├── routes.rb
│   │   │       │           ├── script
│   │   │       │           │   └── rails
│   │   │       │           └── test.rb
│   │   │       ├── dummy_model
│   │   │       │   ├── dummy_model_generator.rb
│   │   │       │   └── templates
│   │   │       │       ├── migration.rb.tt
│   │   │       │       └── model.rb.tt
│   │   │       └── install
│   │   │           ├── install_generator.rb
│   │   │           └── templates
│   │   │               ├── config
│   │   │               │   └── initializers
│   │   │               │       └── spree.rb
│   │   │               └── vendor
│   │   │                   └── assets
│   │   │                       ├── javascripts
│   │   │                       │   └── spree
│   │   │                       │       ├── backend
│   │   │                       │       │   └── all.js
│   │   │                       │       └── frontend
│   │   │                       │           └── all.js
│   │   │                       └── stylesheets
│   │   │                           └── spree
│   │   │                               ├── backend
│   │   │                               │   └── all.css
│   │   │                               └── frontend
│   │   │                                   └── all.css
│   │   ├── spree
│   │   │   ├── core
│   │   │   │   ├── components.rb
│   │   │   │   ├── controller_helpers
│   │   │   │   │   ├── auth.rb
│   │   │   │   │   ├── common.rb
│   │   │   │   │   ├── order.rb
│   │   │   │   │   ├── search.rb
│   │   │   │   │   ├── store.rb
│   │   │   │   │   └── strong_parameters.rb
│   │   │   │   ├── engine.rb
│   │   │   │   ├── importer
│   │   │   │   │   ├── order.rb
│   │   │   │   │   └── product.rb
│   │   │   │   ├── importer.rb
│   │   │   │   ├── number_generator.rb
│   │   │   │   ├── product_duplicator.rb
│   │   │   │   ├── product_filters.rb
│   │   │   │   ├── query_filters
│   │   │   │   │   ├── comparable.rb
│   │   │   │   │   ├── date.rb
│   │   │   │   │   ├── number.rb
│   │   │   │   │   └── text.rb
│   │   │   │   ├── query_filters.rb
│   │   │   │   ├── routes.rb
│   │   │   │   ├── search
│   │   │   │   │   └── base.rb
│   │   │   │   ├── token_generator.rb
│   │   │   │   └── version.rb
│   │   │   ├── core.rb
│   │   │   ├── dependencies_helper.rb
│   │   │   ├── i18n
│   │   │   │   ├── base.rb
│   │   │   │   └── initializer.rb
│   │   │   ├── i18n.rb
│   │   │   ├── localized_number.rb
│   │   │   ├── migrations.rb
│   │   │   ├── money.rb
│   │   │   ├── permitted_attributes.rb
│   │   │   ├── service_module.rb
│   │   │   └── testing_support
│   │   │       ├── ability_helpers.rb
│   │   │       ├── authorization_helpers.rb
│   │   │       ├── bar_ability.rb
│   │   │       ├── caching.rb
│   │   │       ├── capybara_config.rb
│   │   │       ├── capybara_ext.rb
│   │   │       ├── common_rake.rb
│   │   │       ├── controller_requests.rb
│   │   │       ├── extension_rake.rb
│   │   │       ├── factories
│   │   │       │   ├── address_factory.rb
│   │   │       │   ├── adjustment_factory.rb
│   │   │       │   ├── calculator_factory.rb
│   │   │       │   ├── country_factory.rb
│   │   │       │   ├── credit_card_factory.rb
│   │   │       │   ├── customer_return_factory.rb
│   │   │       │   ├── image_factory.rb
│   │   │       │   ├── inventory_unit_factory.rb
│   │   │       │   ├── line_item_factory.rb
│   │   │       │   ├── options_factory.rb
│   │   │       │   ├── order_factory.rb
│   │   │       │   ├── order_promotion_factory.rb
│   │   │       │   ├── payment_factory.rb
│   │   │       │   ├── payment_method_factory.rb
│   │   │       │   ├── price_factory.rb
│   │   │       │   ├── product_factory.rb
│   │   │       │   ├── product_option_type_factory.rb
│   │   │       │   ├── product_property_factory.rb
│   │   │       │   ├── promotion_category_factory.rb
│   │   │       │   ├── promotion_factory.rb
│   │   │       │   ├── promotion_rule_factory.rb
│   │   │       │   ├── property_factory.rb
│   │   │       │   ├── prototype_factory.rb
│   │   │       │   ├── refund_factory.rb
│   │   │       │   ├── reimbursement_factory.rb
│   │   │       │   ├── reimbursement_type_factory.rb
│   │   │       │   ├── return_authorization_factory.rb
│   │   │       │   ├── return_item_factory.rb
│   │   │       │   ├── role_factory.rb
│   │   │       │   ├── shipment_factory.rb
│   │   │       │   ├── shipping_category_factory.rb
│   │   │       │   ├── shipping_method_factory.rb
│   │   │       │   ├── state_factory.rb
│   │   │       │   ├── stock_factory.rb
│   │   │       │   ├── stock_item_factory.rb
│   │   │       │   ├── stock_location_factory.rb
│   │   │       │   ├── stock_movement_factory.rb
│   │   │       │   ├── store_credit_category_factory.rb
│   │   │       │   ├── store_credit_event_factory.rb
│   │   │       │   ├── store_credit_factory.rb
│   │   │       │   ├── store_credit_type_factory.rb
│   │   │       │   ├── store_factory.rb
│   │   │       │   ├── tag_factory.rb
│   │   │       │   ├── tax_category_factory.rb
│   │   │       │   ├── taxon_factory.rb
│   │   │       │   ├── taxonomy_factory.rb
│   │   │       │   ├── tax_rate_factory.rb
│   │   │       │   ├── user_factory.rb
│   │   │       │   ├── variant_factory.rb
│   │   │       │   ├── zone_factory.rb
│   │   │       │   └── zone_member_factory.rb
│   │   │       ├── factories.rb
│   │   │       ├── flash.rb
│   │   │       ├── i18n.rb
│   │   │       ├── image_helpers.rb
│   │   │       ├── kernel.rb
│   │   │       ├── order_walkthrough.rb
│   │   │       ├── preferences.rb
│   │   │       └── url_helpers.rb
│   │   ├── spree_core.rb
│   │   └── tasks
│   │       ├── core.rake
│   │       ├── email.rake
│   │       └── exchanges.rake
│   ├── LICENSE
│   ├── Rakefile
│   ├── script
│   │   └── rails
│   ├── spec
│   │   ├── filters
│   │   │   └── spree
│   │   │       └── products
│   │   │           └── find_spec.rb
│   │   ├── fixtures
│   │   │   ├── text-file.txt
│   │   │   └── thinking-cat.jpg
│   │   ├── helpers
│   │   │   ├── base_helper_spec.rb
│   │   │   └── products_helper_spec.rb
│   │   ├── lib
│   │   │   ├── calculated_adjustments_spec.rb
│   │   │   ├── i18n_spec.rb
│   │   │   ├── search
│   │   │   │   └── base_spec.rb
│   │   │   ├── spree
│   │   │   │   ├── core
│   │   │   │   │   ├── controller_helpers
│   │   │   │   │   │   ├── auth_spec.rb
│   │   │   │   │   │   ├── order_spec.rb
│   │   │   │   │   │   ├── search_spec.rb
│   │   │   │   │   │   ├── store_spec.rb
│   │   │   │   │   │   └── strong_parameters_spec.rb
│   │   │   │   │   ├── importer
│   │   │   │   │   │   └── order_spec.rb
│   │   │   │   │   ├── number_generator_spec.rb
│   │   │   │   │   ├── query_filters
│   │   │   │   │   │   ├── comparable_spec.rb
│   │   │   │   │   │   └── text_spec.rb
│   │   │   │   │   └── token_generator_spec.rb
│   │   │   │   ├── core_spec.rb
│   │   │   │   ├── localized_number_spec.rb
│   │   │   │   ├── migrations_spec.rb
│   │   │   │   ├── money_spec.rb
│   │   │   │   └── service_module_spec.rb
│   │   │   └── tasks
│   │   │       └── exchanges_spec.rb
│   │   ├── mailers
│   │   │   ├── order_mailer_spec.rb
│   │   │   ├── reimbursement_mailer_spec.rb
│   │   │   ├── shipment_mailer_spec.rb
│   │   │   └── test_mailer_spec.rb
│   │   ├── models
│   │   │   └── spree
│   │   │       ├── ability_spec.rb
│   │   │       ├── address_spec.rb
│   │   │       ├── adjustable
│   │   │       │   ├── adjuster
│   │   │       │   │   ├── base_spec.rb
│   │   │       │   │   ├── promotion_spec.rb
│   │   │       │   │   └── tax_spec.rb
│   │   │       │   └── adjustments_updater_spec.rb
│   │   │       ├── adjustment_spec.rb
│   │   │       ├── app_configuration_spec.rb
│   │   │       ├── app_dependencies_spec.rb
│   │   │       ├── base_spec.rb
│   │   │       ├── calculator
│   │   │       │   ├── default_tax_spec.rb
│   │   │       │   ├── flat_percent_item_total_spec.rb
│   │   │       │   ├── flat_rate_spec.rb
│   │   │       │   ├── flexi_rate_spec.rb
│   │   │       │   ├── percent_on_line_item_spec.rb
│   │   │       │   ├── price_sack_spec.rb
│   │   │       │   ├── refunds
│   │   │       │   │   └── default_refund_amount_spec.rb
│   │   │       │   ├── shipping
│   │   │       │   │   ├── flat_percent_item_total_spec.rb
│   │   │       │   │   ├── flat_rate_spec.rb
│   │   │       │   │   ├── flexi_rate_spec.rb
│   │   │       │   │   ├── per_item_spec.rb
│   │   │       │   │   └── price_sack_spec.rb
│   │   │       │   ├── shipping.rb
│   │   │       │   ├── tiered_flat_rate_spec.rb
│   │   │       │   └── tiered_percent_spec.rb
│   │   │       ├── calculator_spec.rb
│   │   │       ├── classification_spec.rb
│   │   │       ├── concerns
│   │   │       │   ├── display_money_spec.rb
│   │   │       │   ├── user_methods_spec.rb
│   │   │       │   └── vat_price_calculation_spec.rb
│   │   │       ├── country_spec.rb
│   │   │       ├── credit_card_spec.rb
│   │   │       ├── customer_return_spec.rb
│   │   │       ├── exchange_spec.rb
│   │   │       ├── fulfilment_changer_spec.rb
│   │   │       ├── gateway
│   │   │       │   ├── bogus_simple.rb
│   │   │       │   └── bogus_spec.rb
│   │   │       ├── gateway_spec.rb
│   │   │       ├── image_spec.rb
│   │   │       ├── inventory_unit_spec.rb
│   │   │       ├── line_item_spec.rb
│   │   │       ├── option_type_spec.rb
│   │   │       ├── option_value_spec.rb
│   │   │       ├── order
│   │   │       │   ├── address_spec.rb
│   │   │       │   ├── adjustments_spec.rb
│   │   │       │   ├── callbacks_spec.rb
│   │   │       │   ├── checkout_spec.rb
│   │   │       │   ├── currency_updater_spec.rb
│   │   │       │   ├── finalizing_spec.rb
│   │   │       │   ├── payment_spec.rb
│   │   │       │   ├── risk_assessment_spec.rb
│   │   │       │   ├── shipments_spec.rb
│   │   │       │   ├── state_machine_spec.rb
│   │   │       │   ├── store_credit_spec.rb
│   │   │       │   ├── tax_spec.rb
│   │   │       │   ├── totals_spec.rb
│   │   │       │   ├── updating_spec.rb
│   │   │       │   └── validations_spec.rb
│   │   │       ├── order_inventory_spec.rb
│   │   │       ├── order_merger_spec.rb
│   │   │       ├── order_promotion_spec.rb
│   │   │       ├── order_spec.rb
│   │   │       ├── order_updater_spec.rb
│   │   │       ├── payment
│   │   │       │   ├── gateway_options_spec.rb
│   │   │       │   └── store_credit_spec.rb
│   │   │       ├── payment_method
│   │   │       │   └── store_credit_spec.rb
│   │   │       ├── payment_method_spec.rb
│   │   │       ├── payment_spec.rb
│   │   │       ├── preferences
│   │   │       │   ├── configuration_spec.rb
│   │   │       │   ├── preferable_spec.rb
│   │   │       │   ├── scoped_store_spec.rb
│   │   │       │   └── store_spec.rb
│   │   │       ├── preference_spec.rb
│   │   │       ├── price_spec.rb
│   │   │       ├── product
│   │   │       │   └── scopes_spec.rb
│   │   │       ├── product_duplicator_spec.rb
│   │   │       ├── product_filter_spec.rb
│   │   │       ├── product_property_spec.rb
│   │   │       ├── product_spec.rb
│   │   │       ├── promotion
│   │   │       │   ├── actions
│   │   │       │   │   ├── create_adjustment_spec.rb
│   │   │       │   │   ├── create_item_adjustments_spec.rb
│   │   │       │   │   ├── create_line_items_spec.rb
│   │   │       │   │   └── free_shipping_spec.rb
│   │   │       │   └── rules
│   │   │       │       ├── country_spec.rb
│   │   │       │       ├── first_order_spec.rb
│   │   │       │       ├── item_total_spec.rb
│   │   │       │       ├── one_use_per_user_spec.rb
│   │   │       │       ├── option_value_spec.rb
│   │   │       │       ├── product_spec.rb
│   │   │       │       ├── taxon_spec.rb
│   │   │       │       ├── user_logged_in_spec.rb
│   │   │       │       └── user_spec.rb
│   │   │       ├── promotion_action_spec.rb
│   │   │       ├── promotion_category_spec.rb
│   │   │       ├── promotion_handler
│   │   │       │   ├── cart_spec.rb
│   │   │       │   ├── coupon_spec.rb
│   │   │       │   ├── free_shipping_spec.rb
│   │   │       │   ├── page_spec.rb
│   │   │       │   └── promotion_duplicator_spec.rb
│   │   │       ├── promotion_rule_spec.rb
│   │   │       ├── promotion_spec.rb
│   │   │       ├── refund_reason_spec.rb
│   │   │       ├── refund_spec.rb
│   │   │       ├── reimbursement
│   │   │       │   ├── credit_spec.rb
│   │   │       │   ├── reimbursement_type_engine_spec.rb
│   │   │       │   └── reimbursement_type_validator_spec.rb
│   │   │       ├── reimbursement_performer_spec.rb
│   │   │       ├── reimbursement_spec.rb
│   │   │       ├── reimbursement_tax_calculator_spec.rb
│   │   │       ├── reimbursement_type
│   │   │       │   ├── credit_spec.rb
│   │   │       │   ├── exchange_spec.rb
│   │   │       │   ├── original_payment_spec.rb
│   │   │       │   └── store_credit_spec.rb
│   │   │       ├── return_authorization_spec.rb
│   │   │       ├── return_item
│   │   │       │   ├── eligibility_validator
│   │   │       │   │   ├── default_spec.rb
│   │   │       │   │   ├── inventory_shipped_spec.rb
│   │   │       │   │   ├── no_reimbursements_spec.rb
│   │   │       │   │   ├── order_completed_spec.rb
│   │   │       │   │   ├── rma_required_spec.rb
│   │   │       │   │   └── time_since_purchase_spec.rb
│   │   │       │   └── exchange_variant_eligibility
│   │   │       │       ├── same_option_value_spec.rb
│   │   │       │       └── same_product_spec.rb
│   │   │       ├── return_item_spec.rb
│   │   │       ├── returns_calculator_spec.rb
│   │   │       ├── shipment_spec.rb
│   │   │       ├── shipping_calculator_spec.rb
│   │   │       ├── shipping_category_spec.rb
│   │   │       ├── shipping_method_spec.rb
│   │   │       ├── shipping_rate_spec.rb
│   │   │       ├── state_spec.rb
│   │   │       ├── stock
│   │   │       │   ├── availability_validator_spec.rb
│   │   │       │   ├── content_item_spec.rb
│   │   │       │   ├── coordinator_spec.rb
│   │   │       │   ├── differentiator_spec.rb
│   │   │       │   ├── estimator_spec.rb
│   │   │       │   ├── inventory_unit_builder_spec.rb
│   │   │       │   ├── package_spec.rb
│   │   │       │   ├── packer_spec.rb
│   │   │       │   ├── prioritizer_spec.rb
│   │   │       │   ├── quantifier_spec.rb
│   │   │       │   └── splitter
│   │   │       │       ├── backordered_spec.rb
│   │   │       │       ├── base_spec.rb
│   │   │       │       ├── shipping_category_spec.rb
│   │   │       │       └── weight_spec.rb
│   │   │       ├── stock_item_spec.rb
│   │   │       ├── stock_location_spec.rb
│   │   │       ├── stock_movement_spec.rb
│   │   │       ├── stock_transfer_spec.rb
│   │   │       ├── store_credit_category_spec.rb
│   │   │       ├── store_credit_event_spec.rb
│   │   │       ├── store_credit_spec.rb
│   │   │       ├── store_spec.rb
│   │   │       ├── tax_category_spec.rb
│   │   │       ├── taxon_image_spec.rb
│   │   │       ├── taxonomy_spec.rb
│   │   │       ├── taxon_spec.rb
│   │   │       ├── tax_rate_spec.rb
│   │   │       ├── user_spec.rb
│   │   │       ├── variant_spec.rb
│   │   │       ├── zone_member_spec.rb
│   │   │       └── zone_spec.rb
│   │   ├── services
│   │   │   └── spree
│   │   │       ├── cart
│   │   │       │   ├── add_item_spec.rb
│   │   │       │   ├── create_spec.rb
│   │   │       │   ├── remove_item_spec.rb
│   │   │       │   ├── remove_line_item_spec.rb
│   │   │       │   └── set_quantity_spec.rb
│   │   │       └── checkout
│   │   │           ├── add_store_credit_spec.rb
│   │   │           ├── get_shipping_rates_spec.rb
│   │   │           ├── remove_store_credit_spec.rb
│   │   │           └── update_spec.rb
│   │   ├── spec_helper.rb
│   │   ├── support
│   │   │   ├── big_decimal.rb
│   │   │   ├── concerns
│   │   │   │   ├── adjustment_source.rb
│   │   │   │   └── default_price.rb
│   │   │   ├── rake.rb
│   │   │   └── test_gateway.rb
│   │   └── validators
│   │       └── email_validator_spec.rb
│   ├── spree_core.gemspec
│   └── vendor
│       └── assets
│           └── javascripts
│               ├── fetch.umd.js
│               ├── jquery.payment.js
│               ├── jsuri.js
│               └── polyfill.min.js
├── docker-entrypoint.sh
├── Dockerfile
├── frontend
│   ├── app
│   │   ├── assets
│   │   │   ├── images
│   │   │   │   ├── credit_cards
│   │   │   │   │   ├── amex_cid.gif
│   │   │   │   │   ├── credit_card.gif
│   │   │   │   │   ├── discover_cid.gif
│   │   │   │   │   ├── icons
│   │   │   │   │   │   ├── american_express.png
│   │   │   │   │   │   ├── cirrus.png
│   │   │   │   │   │   ├── delta.png
│   │   │   │   │   │   ├── diners_club.png
│   │   │   │   │   │   ├── directdebit.png
│   │   │   │   │   │   ├── discover.png
│   │   │   │   │   │   ├── egold.png
│   │   │   │   │   │   ├── jcb.png
│   │   │   │   │   │   ├── maestro.png
│   │   │   │   │   │   ├── master.png
│   │   │   │   │   │   ├── paypal.png
│   │   │   │   │   │   ├── solo.png
│   │   │   │   │   │   ├── switch.png
│   │   │   │   │   │   ├── visaelectron.png
│   │   │   │   │   │   ├── visa.png
│   │   │   │   │   │   ├── westernunion.png
│   │   │   │   │   │   ├── wirecard.png
│   │   │   │   │   │   └── worldpay.png
│   │   │   │   │   ├── master_cid.jpg
│   │   │   │   │   └── visa_cid.gif
│   │   │   │   ├── favicon.ico
│   │   │   │   └── logo
│   │   │   │       └── spree_50.png
│   │   │   ├── javascripts
│   │   │   │   └── spree
│   │   │   │       ├── frontend
│   │   │   │       │   ├── api_tokens.js
│   │   │   │       │   ├── cart.js
│   │   │   │       │   ├── checkout
│   │   │   │       │   │   ├── address.js
│   │   │   │       │   │   ├── payment.js
│   │   │   │       │   │   └── shipment.js
│   │   │   │       │   ├── checkout.js
│   │   │   │       │   ├── coupon_manager.js
│   │   │   │       │   └── product.js
│   │   │   │       └── frontend.js
│   │   │   └── stylesheets
│   │   │       └── spree
│   │   │           ├── frontend
│   │   │           │   ├── frontend_bootstrap.css.scss
│   │   │           │   └── _variables.scss
│   │   │           └── frontend.css
│   │   ├── controllers
│   │   │   └── spree
│   │   │       ├── checkout_controller.rb
│   │   │       ├── content_controller.rb
│   │   │       ├── home_controller.rb
│   │   │       ├── locale_controller.rb
│   │   │       ├── orders_controller.rb
│   │   │       ├── products_controller.rb
│   │   │       ├── store_controller.rb
│   │   │       └── taxons_controller.rb
│   │   ├── helpers
│   │   │   └── spree
│   │   │       ├── frontend_helper.rb
│   │   │       ├── orders_helper.rb
│   │   │       └── taxons_helper.rb
│   │   ├── models
│   │   │   └── spree
│   │   │       └── frontend_configuration.rb
│   │   └── views
│   │       ├── kaminari
│   │       │   └── twitter-bootstrap-4
│   │       │       ├── _first_page.html.erb
│   │       │       ├── _gap.html.erb
│   │       │       ├── _last_page.html.erb
│   │       │       ├── _next_page.html.erb
│   │       │       ├── _page.html.erb
│   │       │       ├── _paginator.html.erb
│   │       │       └── _prev_page.html.erb
│   │       └── spree
│   │           ├── address
│   │           │   └── _form.html.erb
│   │           ├── checkout
│   │           │   ├── _address.html.erb
│   │           │   ├── _confirm.html.erb
│   │           │   ├── _delivery.html.erb
│   │           │   ├── edit.html.erb
│   │           │   ├── payment
│   │           │   │   ├── _check.html.erb
│   │           │   │   ├── _gateway.html.erb
│   │           │   │   └── _storecredit.html.erb
│   │           │   ├── _payment.html.erb
│   │           │   └── _summary.html.erb
│   │           ├── content
│   │           │   ├── cvv.html.erb
│   │           │   └── test.html.erb
│   │           ├── home
│   │           │   └── index.html.erb
│   │           ├── layouts
│   │           │   └── spree_application.html.erb
│   │           ├── orders
│   │           │   ├── _adjustment_row.html.erb
│   │           │   ├── _adjustments.html.erb
│   │           │   ├── edit.html.erb
│   │           │   ├── _form.html.erb
│   │           │   ├── _line_item.html.erb
│   │           │   └── show.html.erb
│   │           ├── products
│   │           │   ├── _cart_form.html.erb
│   │           │   ├── index.html.erb
│   │           │   ├── _product.html.erb
│   │           │   ├── _promotions.html.erb
│   │           │   ├── _properties.html.erb
│   │           │   ├── show.html.erb
│   │           │   ├── _taxons.html.erb
│   │           │   └── _thumbnails.html.erb
│   │           ├── shared
│   │           │   ├── _address.html.erb
│   │           │   ├── _error_messages.html.erb
│   │           │   ├── _filters.html.erb
│   │           │   ├── forbidden.html.erb
│   │           │   ├── _header.html.erb
│   │           │   ├── _head.html.erb
│   │           │   ├── _link_to_cart.html.erb
│   │           │   ├── _login_bar.html.erb
│   │           │   ├── _login.html.erb
│   │           │   ├── _main_nav_bar.html.erb
│   │           │   ├── _nav_bar.html.erb
│   │           │   ├── _order_details.html.erb
│   │           │   ├── _payment.html.erb
│   │           │   ├── _products.html.erb
│   │           │   ├── _search.html.erb
│   │           │   ├── _shipment_tracking.html.erb
│   │           │   ├── _sidebar.html.erb
│   │           │   ├── _taxonomies.html.erb
│   │           │   ├── _translations.html.erb
│   │           │   └── unauthorized.html.erb
│   │           └── taxons
│   │               ├── show.html.erb
│   │               └── _taxon.html.erb
│   ├── config
│   │   ├── initializers
│   │   │   ├── assets.rb
│   │   │   └── canonical_rails.rb
│   │   └── routes.rb
│   ├── Gemfile
│   ├── lib
│   │   ├── generators
│   │   │   └── spree
│   │   │       └── frontend
│   │   │           └── copy_views
│   │   │               └── copy_views_generator.rb
│   │   ├── spree
│   │   │   ├── frontend
│   │   │   │   ├── engine.rb
│   │   │   │   └── middleware
│   │   │   │       └── seo_assist.rb
│   │   │   └── frontend.rb
│   │   └── spree_frontend.rb
│   ├── LICENSE
│   ├── Rakefile
│   ├── README.md
│   ├── script
│   │   └── rails
│   ├── spec
│   │   ├── controllers
│   │   │   ├── controller_helpers_spec.rb
│   │   │   └── spree
│   │   │       ├── checkout_controller_spec.rb
│   │   │       ├── checkout_controller_with_views_spec.rb
│   │   │       ├── content_controller_spec.rb
│   │   │       ├── current_order_tracking_spec.rb
│   │   │       ├── home_controller_spec.rb
│   │   │       ├── orders_controller_ability_spec.rb
│   │   │       ├── orders_controller_spec.rb
│   │   │       ├── orders_controller_transitions_spec.rb
│   │   │       ├── products_controller_spec.rb
│   │   │       └── taxons_controller_spec.rb
│   │   ├── features
│   │   │   ├── address_spec.rb
│   │   │   ├── automatic_promotion_adjustments_spec.rb
│   │   │   ├── caching
│   │   │   │   ├── products_spec.rb
│   │   │   │   └── taxons_spec.rb
│   │   │   ├── cart_spec.rb
│   │   │   ├── checkout_spec.rb
│   │   │   ├── checkout_unshippable_spec.rb
│   │   │   ├── coupon_code_spec.rb
│   │   │   ├── currency_spec.rb
│   │   │   ├── delivery_spec.rb
│   │   │   ├── free_shipping_promotions_spec.rb
│   │   │   ├── locale_spec.rb
│   │   │   ├── microdata_spec.rb
│   │   │   ├── order_spec.rb
│   │   │   ├── page_promotions_spec.rb
│   │   │   ├── products_spec.rb
│   │   │   ├── taxons_spec.rb
│   │   │   └── template_rendering_spec.rb
│   │   ├── fixtures
│   │   │   └── thinking-cat.jpg
│   │   ├── helpers
│   │   │   ├── frontend_helper_spec.rb
│   │   │   └── taxons_helper_spec.rb
│   │   ├── requests
│   │   │   ├── api_tokens_spec.rb
│   │   │   └── ensure_cart_spec.rb
│   │   ├── spec_helper.rb
│   │   ├── support
│   │   │   ├── add_to_cart.rb
│   │   │   └── shared_contexts
│   │   │       ├── checkout_setup.rb
│   │   │       ├── custom_products.rb
│   │   │       └── product_prototypes.rb
│   │   └── views
│   │       └── spree
│   │           └── checkout
│   │               └── _summary_spec.rb
│   ├── spree_frontend.gemspec
│   └── vendor
│       └── assets
│           └── javascripts
│               └── accounting.min.js
├── Gemfile
├── guides
│   ├── gatsby-browser.js
│   ├── gatsby-config.js
│   ├── gatsby-node.js
│   ├── gatsby-ssr.js
│   ├── package.json
│   ├── README.md
│   ├── serve.json
│   ├── src
│   │   ├── components
│   │   │   ├── base
│   │   │   │   ├── Button.js
│   │   │   │   ├── H1.js
│   │   │   │   ├── H2.js
│   │   │   │   ├── H3.js
│   │   │   │   ├── H4.js
│   │   │   │   ├── HeaderLink.js
│   │   │   │   ├── Hr.js
│   │   │   │   ├── P.js
│   │   │   │   ├── Table.js
│   │   │   │   ├── Td.js
│   │   │   │   └── Th.js
│   │   │   ├── Breadcrumbs.js
│   │   │   ├── Crumb.js
│   │   │   ├── DocSearch.js
│   │   │   ├── ExternalLink.js
│   │   │   ├── Header.js
│   │   │   ├── helpers
│   │   │   │   ├── Alert.js
│   │   │   │   ├── Json.js
│   │   │   │   ├── Params.js
│   │   │   │   └── Status.js
│   │   │   ├── Layout.js
│   │   │   ├── Logo.js
│   │   │   ├── LogoSpark.js
│   │   │   ├── NavItem.js
│   │   │   ├── Section.js
│   │   │   ├── Sidebar.js
│   │   │   ├── SidebarRootLink.js
│   │   │   └── SiteMetadata.js
│   │   ├── content
│   │   │   ├── api
│   │   │   │   ├── addresses.md
│   │   │   │   ├── checkouts.md
│   │   │   │   ├── countries.md
│   │   │   │   ├── index.md
│   │   │   │   ├── line_items.md
│   │   │   │   ├── option_types.md
│   │   │   │   ├── option_values.md
│   │   │   │   ├── orders.md
│   │   │   │   ├── payments.md
│   │   │   │   ├── product_images.md
│   │   │   │   ├── product_properties.md
│   │   │   │   ├── products.md
│   │   │   │   ├── return_authorizations.md
│   │   │   │   ├── shipments.md
│   │   │   │   ├── states.md
│   │   │   │   ├── stock_items.md
│   │   │   │   ├── stock_locations.md
│   │   │   │   ├── stock_movements.md
│   │   │   │   ├── summary.md
│   │   │   │   ├── taxonomies.md
│   │   │   │   ├── users.md
│   │   │   │   ├── variants.md
│   │   │   │   └── zones.md
│   │   │   ├── developer
│   │   │   │   ├── core
│   │   │   │   │   ├── addresses.md
│   │   │   │   │   ├── adjustments.md
│   │   │   │   │   ├── calculators.md
│   │   │   │   │   ├── inventory.md
│   │   │   │   │   ├── orders.md
│   │   │   │   │   ├── payments.md
│   │   │   │   │   ├── preferences.md
│   │   │   │   │   ├── products.md
│   │   │   │   │   ├── promotions.md
│   │   │   │   │   ├── shipments.md
│   │   │   │   │   └── taxation.md
│   │   │   │   ├── customization
│   │   │   │   │   ├── api_v1.md
│   │   │   │   │   ├── api_v2.md
│   │   │   │   │   ├── asset.md
│   │   │   │   │   ├── authentication.md
│   │   │   │   │   ├── checkout.md
│   │   │   │   │   ├── dependencies.md
│   │   │   │   │   ├── extensions.md
│   │   │   │   │   ├── i18n.md
│   │   │   │   │   ├── images.md
│   │   │   │   │   ├── logic.md
│   │   │   │   │   └── view.md
│   │   │   │   ├── index.md
│   │   │   │   ├── source
│   │   │   │   │   ├── about.md
│   │   │   │   │   ├── getting_help.md
│   │   │   │   │   ├── index.md
│   │   │   │   │   └── navigating.md
│   │   │   │   ├── tutorials
│   │   │   │   │   ├── deface_overrides_tutorial.md
│   │   │   │   │   ├── extensions_tutorial.md
│   │   │   │   │   ├── getting_started_tutorial.md
│   │   │   │   │   ├── migration.md
│   │   │   │   │   ├── security.md
│   │   │   │   │   ├── seo.md
│   │   │   │   │   └── testing.md
│   │   │   │   └── upgrades
│   │   │   │       ├── one-dot-oh-to-one-dot-one.md
│   │   │   │       ├── one-dot-one-to-one-dot-two.md
│   │   │   │       ├── one-dot-three-to-two-dot-oh.md
│   │   │   │       ├── one-dot-two-to-one-dot-three.md
│   │   │   │       ├── point-seventy-to-one-dot-oh.md
│   │   │   │       ├── point-sixty-to-point-seventy.md
│   │   │   │       ├── three-dot-five-to-three-dot-six.md
│   │   │   │       ├── three-dot-four-to-three-dot-five.md
│   │   │   │       ├── three-dot-oh-to-three-dot-one.md
│   │   │   │       ├── three-dot-one-to-three-dot-two.md
│   │   │   │       ├── three-dot-six-to-three-dot-seven.md
│   │   │   │       ├── three-dot-three-to-three-dot-four.md
│   │   │   │       ├── three-dot-two-to-three-dot-three.md
│   │   │   │       ├── two-dot-oh-to-two-dot-one.md
│   │   │   │       ├── two-dot-one-to-two-dot-two.md
│   │   │   │       ├── two-dot-three-to-two-dot-four.md
│   │   │   │       ├── two-dot-two-to-two-dot-three.md
│   │   │   │       └── upgrade_guides.md
│   │   │   ├── release_notes
│   │   │   │   ├── 0_10_0.md
│   │   │   │   ├── 0_30_0.md
│   │   │   │   ├── 0_40_0.md
│   │   │   │   ├── 0_50_0.md
│   │   │   │   ├── 0_60_0.md
│   │   │   │   ├── 0_70_0.md
│   │   │   │   ├── 0_9_0.md
│   │   │   │   ├── 1_0_0.md
│   │   │   │   ├── 1_1_0.md
│   │   │   │   ├── 1_1_4.md
│   │   │   │   ├── 1_2_0.md
│   │   │   │   ├── 1_2_2.md
│   │   │   │   ├── 1_3_0.md
│   │   │   │   ├── 2_0_0.md
│   │   │   │   ├── 2_1_0.md
│   │   │   │   ├── 2_2_0.md
│   │   │   │   ├── 2_3_0.md
│   │   │   │   ├── 2_4_0.md
│   │   │   │   ├── 3_0_0.md
│   │   │   │   ├── 3_1_0.md
│   │   │   │   ├── 3_2_0.md
│   │   │   │   ├── 3_3_0.md
│   │   │   │   ├── 3_4_0.md
│   │   │   │   ├── 3_5_0.md
│   │   │   │   ├── 3_6_0.md
│   │   │   │   ├── 3_7_0.md
│   │   │   │   ├── 4_0_0.md
│   │   │   │   └── index.md
│   │   │   └── user
│   │   │       ├── configuration
│   │   │       │   ├── configuring_analytics.md
│   │   │       │   ├── configuring_geography.md
│   │   │       │   ├── configuring_inventory.md
│   │   │       │   ├── configuring_mail_methods.md
│   │   │       │   ├── configuring_multi_stores.md
│   │   │       │   ├── configuring_reimbursement_types.md
│   │   │       │   ├── configuring_return_authorization_reasons.md
│   │   │       │   ├── configuring_roles.md
│   │   │       │   ├── configuring_store_credit_categories.md
│   │   │       │   ├── configuring_taxes.md
│   │   │       │   └── index.md
│   │   │       ├── index.md
│   │   │       ├── orders
│   │   │       │   ├── editing_orders.md
│   │   │       │   ├── entering_orders.md
│   │   │       │   ├── index.md
│   │   │       │   ├── order_states.md
│   │   │       │   ├── processing_orders.md
│   │   │       │   ├── returning_orders.md
│   │   │       │   └── searching_orders.md
│   │   │       ├── payments
│   │   │       │   ├── index.md
│   │   │       │   ├── payment_methods.md
│   │   │       │   └── payment_states.md
│   │   │       ├── products
│   │   │       │   ├── cloning_products.md
│   │   │       │   ├── creating_products.md
│   │   │       │   ├── deleting_products.md
│   │   │       │   ├── editing_products.md
│   │   │       │   ├── index.md
│   │   │       │   ├── product_options.md
│   │   │       │   ├── product_properties.md
│   │   │       │   ├── product_prototypes.md
│   │   │       │   ├── searching_products.md
│   │   │       │   └── taxonomies_and_taxons.md
│   │   │       ├── promotions
│   │   │       │   ├── creating_promotions.md
│   │   │       │   ├── editing_promotions.md
│   │   │       │   ├── index.md
│   │   │       │   └── removing_promotions.md
│   │   │       ├── reports
│   │   │       │   └── index.md
│   │   │       ├── shipments
│   │   │       │   ├── calculators.md
│   │   │       │   ├── index.md
│   │   │       │   ├── shipping_categories.md
│   │   │       │   ├── shipping_methods.md
│   │   │       │   └── zones.md
│   │   │       └── users
│   │   │           ├── creating_users.md
│   │   │           ├── deleting_users.md
│   │   │           ├── editing_users.md
│   │   │           ├── index.md
│   │   │           └── searching_users.md
│   │   ├── data
│   │   │   ├── 401.js
│   │   │   ├── 404.js
│   │   │   ├── address_country.js
│   │   │   ├── address.js
│   │   │   ├── address_state.js
│   │   │   ├── checkout_steps.js
│   │   │   ├── classification.js
│   │   │   ├── countries.js
│   │   │   ├── country.js
│   │   │   ├── country_with_state.js
│   │   │   ├── image.js
│   │   │   ├── images.js
│   │   │   ├── index.js
│   │   │   ├── inventory_unit.js
│   │   │   ├── line_item.js
│   │   │   ├── manifest.js
│   │   │   ├── new_order.js
│   │   │   ├── new_order_show.js
│   │   │   ├── new_taxonomy.js
│   │   │   ├── _no_api_key.js
│   │   │   ├── option_type.js
│   │   │   ├── option_types.js
│   │   │   ├── option_value.js
│   │   │   ├── option_values.js
│   │   │   ├── order_failed_transition.js
│   │   │   ├── order.js
│   │   │   ├── order_show_2.js
│   │   │   ├── order_show.js
│   │   │   ├── orders.js
│   │   │   ├── payment.js
│   │   │   ├── payments.js
│   │   │   ├── product.js
│   │   │   ├── product_properties.js
│   │   │   ├── product_property.js
│   │   │   ├── products.js
│   │   │   ├── return_authorization.js
│   │   │   ├── return_authorizations.js
│   │   │   ├── secondary_taxon.js
│   │   │   ├── shipment.js
│   │   │   ├── shipments.js
│   │   │   ├── shipment_small.js
│   │   │   ├── shipping_category.js
│   │   │   ├── shipping_method.js
│   │   │   ├── shipping_rate.js
│   │   │   ├── state.js
│   │   │   ├── states.js
│   │   │   ├── status.js
│   │   │   ├── stock_item.js
│   │   │   ├── stock_items.js
│   │   │   ├── stock_location.js
│   │   │   ├── stock_locations.js
│   │   │   ├── stock_movement.js
│   │   │   ├── stock_movements.js
│   │   │   ├── taxon.js
│   │   │   ├── taxonomies.js
│   │   │   ├── taxonomy.js
│   │   │   ├── taxons_with_children.js
│   │   │   ├── taxon_with_children.js
│   │   │   ├── update_request.js
│   │   │   ├── user.js
│   │   │   ├── users.js
│   │   │   ├── variant_big.js
│   │   │   ├── variant.js
│   │   │   ├── variants_big.js
│   │   │   ├── zone.js
│   │   │   ├── zone_member.js
│   │   │   └── zones.js
│   │   ├── html.js
│   │   ├── images
│   │   │   ├── developer
│   │   │   │   ├── change_ssl_setting.png
│   │   │   │   ├── core
│   │   │   │   │   ├── new_stock_transfer.png
│   │   │   │   │   ├── payment_flow.jpg
│   │   │   │   │   ├── shipment_flow.jpg
│   │   │   │   │   ├── split_shipments_checkout.png
│   │   │   │   │   ├── stock_movements.png
│   │   │   │   │   └── stock_transfers.png
│   │   │   │   ├── mail_server_settings.png
│   │   │   │   ├── new-admin-interface.png
│   │   │   │   ├── overview.png
│   │   │   │   └── spree_welcome.png
│   │   │   ├── logo.png
│   │   │   ├── logo-spark.png
│   │   │   └── user
│   │   │       ├── config
│   │   │       │   ├── add_new_style.jpg
│   │   │       │   ├── add_reimbursement_types_inside.jpg
│   │   │       │   ├── add_reimbursement_types.jpg
│   │   │       │   ├── add_taxons_to_product.jpg
│   │   │       │   ├── add_taxon_to_taxon.jpg
│   │   │       │   ├── add_taxon_to_taxonomy.jpg
│   │   │       │   ├── amazon_access_keys.jpg
│   │   │       │   ├── amazons3.jpg
│   │   │       │   ├── auto_capture_payment_method.jpg
│   │   │       │   ├── category_delete_icon.jpg
│   │   │       │   ├── category_edit_icon.jpg
│   │   │       │   ├── choose_currency.jpg
│   │   │       │   ├── complex_taxonomy_tree.jpg
│   │   │       │   ├── countries_drop_down.jpg
│   │   │       │   ├── countries.jpg
│   │   │       │   ├── currency_settings.jpg
│   │   │       │   ├── delete_role_icon.jpg
│   │   │       │   ├── delete_stock_location_icon.jpg
│   │   │       │   ├── delete_style.jpg
│   │   │       │   ├── delete_tax_category_link.jpg
│   │   │       │   ├── delete_taxonomy_icon.jpg
│   │   │       │   ├── deleting_state_icon.jpg
│   │   │       │   ├── edit_country_icon.jpg
│   │   │       │   ├── editing_country.jpg
│   │   │       │   ├── editing_state.jpg
│   │   │       │   ├── edit_role_icon.jpg
│   │   │       │   ├── edit_state_icon.jpg
│   │   │       │   ├── edit_stock_location_icon.jpg
│   │   │       │   ├── edit_store_btn.jpg
│   │   │       │   ├── edit_store.jpg
│   │   │       │   ├── edit_tax_category_link.jpg
│   │   │       │   ├── edit_taxon.jpg
│   │   │       │   ├── edit_taxonomy_icon.jpg
│   │   │       │   ├── edit_taxonomy.jpg
│   │   │       │   ├── general_settings.jpg
│   │   │       │   ├── image_settings.jpg
│   │   │       │   ├── mail_method_settings.jpg
│   │   │       │   ├── new_node.jpg
│   │   │       │   ├── new_rma_reason_created.jpg
│   │   │       │   ├── new_rma_reason.jpg
│   │   │       │   ├── new_role_button.jpg
│   │   │       │   ├── new_role_inside.jpg
│   │   │       │   ├── new_sc_category.jpg
│   │   │       │   ├── new_sc_category_name.jpg
│   │   │       │   ├── new_state_form.jpg
│   │   │       │   ├── new_stock_location.jpg
│   │   │       │   ├── new_stock_transfer.jpg
│   │   │       │   ├── new_store.jpg
│   │   │       │   ├── new_tax_category_form.jpg
│   │   │       │   ├── new_taxon.jpg
│   │   │       │   ├── new_taxonomy.jpg
│   │   │       │   ├── new_tax_rate.jpg
│   │   │       │   ├── order_stores.jpg
│   │   │       │   ├── parent_into_parent_taxon_merge.jpg
│   │   │       │   ├── reimbursement_delete_icon.jpg
│   │   │       │   ├── reimbursement_edit_icon.jpg
│   │   │       │   ├── reimbursement_types_dropdown.jpg
│   │   │       │   ├── reimbursement_types.jpg
│   │   │       │   ├── remove_taxon.jpg
│   │   │       │   ├── reorder_taxons.jpg
│   │   │       │   ├── resulting_stock_movements.jpg
│   │   │       │   ├── return_autho_reasons.jpg
│   │   │       │   ├── rma_reason_delete_icon.jpg
│   │   │       │   ├── rma_reason_edit_icon.jpg
│   │   │       │   ├── rma_reason_edit_inside.jpg
│   │   │       │   ├── seo_title_override.jpg
│   │   │       │   ├── show_currency.jpg
│   │   │       │   ├── site_name_in_title.jpg
│   │   │       │   ├── spree_multi_store_admin_page.jpg
│   │   │       │   ├── state_added.jpg
│   │   │       │   ├── stock_movements_link.jpg
│   │   │       │   ├── stock_transfer_complete.jpg
│   │   │       │   ├── stock_transfer.jpg
│   │   │       │   ├── store_credit_categories.jpg
│   │   │       │   ├── tax_categories.jpg
│   │   │       │   ├── taxonomy_tree.jpg
│   │   │       │   ├── tax_rates.jpg
│   │   │       │   ├── tax_settings.jpg
│   │   │       │   └── us_states_list.jpg
│   │   │       ├── orders
│   │   │       │   ├── close_adjustment_icon.jpg
│   │   │       │   ├── closed_adjustment.jpg
│   │   │       │   ├── completed_payment.jpg
│   │   │       │   ├── create_new_order.jpg
│   │   │       │   ├── create_reimbursement_button.jpg
│   │   │       │   ├── customer_return_form.jpg
│   │   │       │   ├── customer_return_link.jpg
│   │   │       │   ├── delete_adjustment_icon.jpg
│   │   │       │   ├── edit_adjustment_icon.jpg
│   │   │       │   ├── edit_order_link.jpg
│   │   │       │   ├── edit_shipping_on_order_link.jpg
│   │   │       │   ├── edit_shipping_options.jpg
│   │   │       │   ├── filter_options.jpg
│   │   │       │   ├── list_of_orders.jpg
│   │   │       │   ├── manual_order_with_product.jpg
│   │   │       │   ├── mass_open_close_adjustments.jpg
│   │   │       │   ├── new_adjustment_button.jpg
│   │   │       │   ├── new_adjustment_form.jpg
│   │   │       │   ├── new_payment_method_link.jpg
│   │   │       │   ├── open_adjustment_icon.jpg
│   │   │       │   ├── order_adjustments.jpg
│   │   │       │   ├── order_customer_details.jpg
│   │   │       │   ├── order_details_link.jpg
│   │   │       │   ├── order_edit.jpg
│   │   │       │   ├── order_product_added.jpg
│   │   │       │   ├── order_product_search.jpg
│   │   │       │   ├── order_shipped.jpg
│   │   │       │   ├── order_to_process.jpg
│   │   │       │   ├── payments_link.jpg
│   │   │       │   ├── payment_to_process.jpg
│   │   │       │   ├── reimbursement_complete.jpg
│   │   │       │   ├── reimbursement_form.jpg
│   │   │       │   ├── return_autho_delete.jpg
│   │   │       │   ├── return_autho_edit.jpg
│   │   │       │   ├── return_autho_inside.jpg
│   │   │       │   ├── return_authorizations_link.jpg
│   │   │       │   ├── rma_form.jpg
│   │   │       │   ├── select_shipping.jpg
│   │   │       │   ├── ship_it.jpg
│   │   │       │   └── tracking_input.jpg
│   │   │       ├── payments
│   │   │       │   ├── add_payment_provider.jpg
│   │   │       │   ├── auto_capture_payment_method.jpg
│   │   │       │   ├── edit_payment_method.jpg
│   │   │       │   ├── new_payment_method.jpg
│   │   │       │   ├── payment_capture.jpg
│   │   │       │   ├── payment_details.jpg
│   │   │       │   ├── payment_edit_button.jpg
│   │   │       │   ├── payment_look_up.jpg
│   │   │       │   ├── payment_method_name.jpg
│   │   │       │   ├── payments_look_up.jpg
│   │   │       │   └── payment_void.jpg
│   │   │       ├── products
│   │   │       │   ├── clone_deleted_product.jpg
│   │   │       │   ├── clone_product.jpg
│   │   │       │   ├── delete_products_icon.jpg
│   │   │       │   ├── edit_cloned_product.jpg
│   │   │       │   ├── edit_product_link.jpg
│   │   │       │   ├── example_cloned_product.jpg
│   │   │       │   ├── filtering_products.jpg
│   │   │       │   ├── large_small_option_values.jpg
│   │   │       │   ├── new_image_form.jpg
│   │   │       │   ├── new_option_form.jpg
│   │   │       │   ├── new_option_type.jpg
│   │   │       │   ├── new_option_value.jpg
│   │   │       │   ├── new_product_entry_form.jpg
│   │   │       │   ├── new_prototype.jpg
│   │   │       │   ├── new_variant.jpg
│   │   │       │   ├── option_types_dropdown.jpg
│   │   │       │   ├── picture_frame_prototype.jpg
│   │   │       │   ├── product_edit_form.jpg
│   │   │       │   ├── product_from_prototype.jpg
│   │   │       │   ├── products_admin.jpg
│   │   │       │   ├── products_landing.jpg
│   │   │       │   ├── properties_example.jpg
│   │   │       │   ├── properties_list.jpg
│   │   │       │   ├── prototype_product_with_options.jpg
│   │   │       │   ├── prototypes.jpg
│   │   │       │   ├── show_deleted_products.jpg
│   │   │       │   ├── stock_location_info.jpg
│   │   │       │   ├── stock_management.jpg
│   │   │       │   └── variants_list.jpg
│   │   │       ├── promotions
│   │   │       │   ├── create_adjustment.jpg
│   │   │       │   ├── create_line_item.jpg
│   │   │       │   ├── delete_promotion_icon.jpg
│   │   │       │   ├── delete_rule_icon.jpg
│   │   │       │   ├── edit_promotion_icon.jpg
│   │   │       │   ├── first_order_rule.jpg
│   │   │       │   ├── item_total_rule.jpg
│   │   │       │   ├── logged_in_rule.jpg
│   │   │       │   ├── new_promotion.jpg
│   │   │       │   ├── products_rule.jpg
│   │   │       │   ├── rules_and_actions.jpg
│   │   │       │   ├── rules_options.jpg
│   │   │       │   └── user_rule.jpg
│   │   │       ├── sales_total_dates.jpg
│   │   │       ├── sales_total_report.jpg
│   │   │       ├── shipments
│   │   │       │   ├── add_multi_to_zone.jpg
│   │   │       │   ├── delete_shipping_method.jpg
│   │   │       │   ├── edit_shipping_method.jpg
│   │   │       │   ├── edit_zone.jpg
│   │   │       │   ├── new_shipping_category.jpg
│   │   │       │   ├── new_shipping_method.jpg
│   │   │       │   ├── new_zone.jpg
│   │   │       │   ├── remove_zone_member.jpg
│   │   │       │   ├── select_shipping_category.jpg
│   │   │       │   ├── shipping_method_calculator.jpg
│   │   │       │   ├── shipping_method_categories.jpg
│   │   │       │   ├── shipping_method_flat_percent.jpg
│   │   │       │   └── shipping_method_zones.jpg
│   │   │       └── users
│   │   │           ├── add_new_user.jpg
│   │   │           ├── store_credit_categories_delete.jpg
│   │   │           ├── store_credit_categories_edit_inside.jpg
│   │   │           ├── store_credit_categories_edit.jpg
│   │   │           ├── store_credit_categories.jpg
│   │   │           ├── store_credit_categories_new.jpg
│   │   │           ├── store_credit_front_applied.jpg
│   │   │           ├── store_credit_front_apply.jpg
│   │   │           ├── store_credit_front_confirm.jpg
│   │   │           ├── store_credit_front_placed_order.jpg
│   │   │           ├── store_credit_order_paid.jpg
│   │   │           ├── store_credit_user_added_delete.jpg
│   │   │           ├── store_credit_user_added_edit_inside.jpg
│   │   │           ├── store_credit_user_added_edit.jpg
│   │   │           ├── store_credit_user_added.jpg
│   │   │           ├── store_credit_user_add.jpg
│   │   │           ├── store_credit_user_categories_dropdown.jpg
│   │   │           ├── store_credit_user.jpg
│   │   │           ├── store_credit_user_new.jpg
│   │   │           ├── store_credit_user_paid.jpg
│   │   │           ├── user_delete_option.jpg
│   │   │           ├── user_edit_inside_address.jpg
│   │   │           ├── user_edit_inside_api.jpg
│   │   │           ├── user_edit_inside_items.jpg
│   │   │           ├── user_edit_inside.jpg
│   │   │           ├── user_edit_inside_lifetimestats.jpg
│   │   │           ├── user_edit_option.jpg
│   │   │           ├── user_edit_orders.jpg
│   │   │           ├── users_search_option.jpg
│   │   │           └── users_tab.jpg
│   │   ├── pages
│   │   │   ├── 404.js
│   │   │   ├── api
│   │   │   │   ├── overview.js
│   │   │   │   └── v2
│   │   │   │       ├── authentication.js
│   │   │   │       ├── index.js
│   │   │   │       └── storefront.js
│   │   │   └── index.js
│   │   ├── styles
│   │   │   ├── app.css
│   │   │   └── spree.css
│   │   ├── templates
│   │   │   └── guide.js
│   │   └── utils
│   │       ├── capitalize.js
│   │       ├── openApiNav.js
│   │       ├── renderHtml.js
│   │       └── styles.js
│   ├── static
│   │   └── favicon.ico
│   └── yarn.lock
├── lib
│   ├── sandbox.sh
│   └── spree.rb
├── license.md
├── netlify.toml
├── Rakefile
├── README.md
├── sample
│   ├── db
│   │   ├── samples
│   │   │   ├── addresses.rb
│   │   │   ├── adjustments.rb
│   │   │   ├── assets.rb
│   │   │   ├── images
│   │   │   │   ├── apache_baseball.png
│   │   │   │   ├── ror_bag.jpeg
│   │   │   │   ├── ror_baseball_back.jpeg
│   │   │   │   ├── ror_baseball_jersey_back_blue.png
│   │   │   │   ├── ror_baseball_jersey_back_green.png
│   │   │   │   ├── ror_baseball_jersey_back_red.png
│   │   │   │   ├── ror_baseball_jersey_blue.png
│   │   │   │   ├── ror_baseball_jersey_green.png
│   │   │   │   ├── ror_baseball_jersey_red.png
│   │   │   │   ├── ror_baseball.jpeg
│   │   │   │   ├── ror_jr_spaghetti.jpeg
│   │   │   │   ├── ror_mug_back.jpeg
│   │   │   │   ├── ror_mug.jpeg
│   │   │   │   ├── ror_ringer_back.jpeg
│   │   │   │   ├── ror_ringer.jpeg
│   │   │   │   ├── ror_stein_back.jpeg
│   │   │   │   ├── ror_stein.jpeg
│   │   │   │   ├── ror_tote_back.jpeg
│   │   │   │   ├── ror_tote.jpeg
│   │   │   │   ├── ruby_baseball.png
│   │   │   │   ├── spree_bag.jpeg
│   │   │   │   ├── spree_jersey_back.jpeg
│   │   │   │   ├── spree_jersey.jpeg
│   │   │   │   ├── spree_mug_back.jpeg
│   │   │   │   ├── spree_mug.jpeg
│   │   │   │   ├── spree_ringer_t_back.jpeg
│   │   │   │   ├── spree_ringer_t.jpeg
│   │   │   │   ├── spree_spaghetti.jpeg
│   │   │   │   ├── spree_stein_back.jpeg
│   │   │   │   ├── spree_stein.jpeg
│   │   │   │   ├── spree_tote_back.jpeg
│   │   │   │   └── spree_tote_front.jpeg
│   │   │   ├── option_types.rb
│   │   │   ├── option_values.rb
│   │   │   ├── orders.rb
│   │   │   ├── payment_methods.rb
│   │   │   ├── payments.rb
│   │   │   ├── product_option_types.rb
│   │   │   ├── product_properties.rb
│   │   │   ├── products.rb
│   │   │   ├── promotions.rb
│   │   │   ├── prototypes.rb
│   │   │   ├── shipping_categories.rb
│   │   │   ├── shipping_methods.rb
│   │   │   ├── stock.rb
│   │   │   ├── store_credit_categories.rb
│   │   │   ├── tax_categories.rb
│   │   │   ├── taxonomies.rb
│   │   │   ├── taxons.rb
│   │   │   ├── tax_rates.rb
│   │   │   └── variants.rb
│   │   └── samples.rb
│   ├── Gemfile
│   ├── lib
│   │   ├── spree
│   │   │   └── sample.rb
│   │   ├── spree_sample.rb
│   │   └── tasks
│   │       └── sample.rake
│   ├── LICENSE
│   ├── Rakefile
│   ├── spec
│   │   ├── lib
│   │   │   └── load_sample_spec.rb
│   │   └── spec_helper.rb
│   └── spree_sample.gemspec
├── spree.gemspec
└── spree_logo.png

554 directories, 2428 files
