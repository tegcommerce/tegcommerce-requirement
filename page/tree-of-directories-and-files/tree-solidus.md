solidus
├── api
│   ├── app
│   │   ├── controllers
│   │   │   └── spree
│   │   │       └── api
│   │   │           ├── address_books_controller.rb
│   │   │           ├── addresses_controller.rb
│   │   │           ├── base_controller.rb
│   │   │           ├── checkouts_controller.rb
│   │   │           ├── classifications_controller.rb
│   │   │           ├── config_controller.rb
│   │   │           ├── countries_controller.rb
│   │   │           ├── coupon_codes_controller.rb
│   │   │           ├── credit_cards_controller.rb
│   │   │           ├── images_controller.rb
│   │   │           ├── inventory_units_controller.rb
│   │   │           ├── line_items_controller.rb
│   │   │           ├── option_types_controller.rb
│   │   │           ├── option_values_controller.rb
│   │   │           ├── orders_controller.rb
│   │   │           ├── payments_controller.rb
│   │   │           ├── product_properties_controller.rb
│   │   │           ├── products_controller.rb
│   │   │           ├── promotions_controller.rb
│   │   │           ├── properties_controller.rb
│   │   │           ├── resource_controller.rb
│   │   │           ├── return_authorizations_controller.rb
│   │   │           ├── shipments_controller.rb
│   │   │           ├── states_controller.rb
│   │   │           ├── stock_items_controller.rb
│   │   │           ├── stock_locations_controller.rb
│   │   │           ├── stock_movements_controller.rb
│   │   │           ├── store_credit_events_controller.rb
│   │   │           ├── stores_controller.rb
│   │   │           ├── taxonomies_controller.rb
│   │   │           ├── taxons_controller.rb
│   │   │           ├── users_controller.rb
│   │   │           ├── variants_controller.rb
│   │   │           └── zones_controller.rb
│   │   ├── helpers
│   │   │   └── spree
│   │   │       └── api
│   │   │           └── api_helpers.rb
│   │   ├── models
│   │   │   └── spree
│   │   │       └── api_configuration.rb
│   │   └── views
│   │       └── spree
│   │           └── api
│   │               ├── address_books
│   │               │   └── show.json.jbuilder
│   │               ├── addresses
│   │               │   ├── _address.json.jbuilder
│   │               │   └── show.json.jbuilder
│   │               ├── adjustments
│   │               │   └── _adjustment.json.jbuilder
│   │               ├── config
│   │               │   ├── money.json.jbuilder
│   │               │   └── show.json.jbuilder
│   │               ├── countries
│   │               │   ├── index.json.jbuilder
│   │               │   └── show.json.jbuilder
│   │               ├── credit_cards
│   │               │   ├── _credit_card.json.jbuilder
│   │               │   ├── index.json.jbuilder
│   │               │   └── show.json.jbuilder
│   │               ├── errors
│   │               │   ├── delete_restriction.json.jbuilder
│   │               │   ├── gateway_error.json.jbuilder
│   │               │   ├── invalid_api_key.json.jbuilder
│   │               │   ├── invalid_resource.json.jbuilder
│   │               │   ├── must_specify_api_key.json.jbuilder
│   │               │   ├── not_found.json.jbuilder
│   │               │   └── unauthorized.json.jbuilder
│   │               ├── images
│   │               │   ├── _image.json.jbuilder
│   │               │   ├── index.json.jbuilder
│   │               │   └── show.json.jbuilder
│   │               ├── inventory_units
│   │               │   └── show.json.jbuilder
│   │               ├── line_items
│   │               │   ├── _line_item.json.jbuilder
│   │               │   ├── new.json.jbuilder
│   │               │   └── show.json.jbuilder
│   │               ├── option_types
│   │               │   ├── index.json.jbuilder
│   │               │   ├── _option_type.json.jbuilder
│   │               │   └── show.json.jbuilder
│   │               ├── option_values
│   │               │   ├── index.json.jbuilder
│   │               │   ├── _option_value.json.jbuilder
│   │               │   └── show.json.jbuilder
│   │               ├── orders
│   │               │   ├── _big.json.jbuilder
│   │               │   ├── could_not_apply_coupon.json.jbuilder
│   │               │   ├── could_not_transition.json.jbuilder
│   │               │   ├── expected_total_mismatch.json.jbuilder
│   │               │   ├── index.json.jbuilder
│   │               │   ├── invalid_shipping_method.json.jbuilder
│   │               │   ├── mine.json.jbuilder
│   │               │   ├── _order.json.jbuilder
│   │               │   └── show.json.jbuilder
│   │               ├── payments
│   │               │   ├── credit_over_limit.json.jbuilder
│   │               │   ├── index.json.jbuilder
│   │               │   ├── new.json.jbuilder
│   │               │   ├── show.json.jbuilder
│   │               │   ├── source_views
│   │               │   │   ├── _check.json.jbuilder
│   │               │   │   ├── _gateway.json.jbuilder
│   │               │   │   └── _storecredit.json.jbuilder
│   │               │   └── update_forbidden.json.jbuilder
│   │               ├── product_properties
│   │               │   ├── index.json.jbuilder
│   │               │   ├── new.json.jbuilder
│   │               │   └── show.json.jbuilder
│   │               ├── products
│   │               │   ├── index.json.jbuilder
│   │               │   ├── new.json.jbuilder
│   │               │   ├── _product.json.jbuilder
│   │               │   └── show.json.jbuilder
│   │               ├── promotions
│   │               │   ├── handler.json.jbuilder
│   │               │   └── show.json.jbuilder
│   │               ├── properties
│   │               │   ├── index.json.jbuilder
│   │               │   ├── new.json.jbuilder
│   │               │   └── show.json.jbuilder
│   │               ├── return_authorizations
│   │               │   ├── index.json.jbuilder
│   │               │   ├── new.json.jbuilder
│   │               │   └── show.json.jbuilder
│   │               ├── shared
│   │               │   └── _pagination.json.jbuilder
│   │               ├── shipments
│   │               │   ├── _big.json.jbuilder
│   │               │   ├── cannot_ready_shipment.json.jbuilder
│   │               │   ├── estimated_rates.json.jbuilder
│   │               │   ├── mine.json.jbuilder
│   │               │   ├── show.json.jbuilder
│   │               │   └── _small.json.jbuilder
│   │               ├── shipping_rates
│   │               │   └── _shipping_rate.json.jbuilder
│   │               ├── states
│   │               │   ├── index.json.jbuilder
│   │               │   └── show.json.jbuilder
│   │               ├── stock_items
│   │               │   ├── index.json.jbuilder
│   │               │   ├── show.json.jbuilder
│   │               │   └── _stock_item.json.jbuilder
│   │               ├── stock_locations
│   │               │   ├── index.json.jbuilder
│   │               │   ├── show.json.jbuilder
│   │               │   └── _stock_location.json.jbuilder
│   │               ├── stock_movements
│   │               │   ├── index.json.jbuilder
│   │               │   ├── show.json.jbuilder
│   │               │   └── _stock_movement.json.jbuilder
│   │               ├── store_credit_events
│   │               │   └── mine.json.jbuilder
│   │               ├── stores
│   │               │   ├── index.json.jbuilder
│   │               │   └── show.json.jbuilder
│   │               ├── taxonomies
│   │               │   ├── index.json.jbuilder
│   │               │   ├── jstree.json.jbuilder
│   │               │   ├── _nested.json.jbuilder
│   │               │   ├── new.json.jbuilder
│   │               │   ├── show.json.jbuilder
│   │               │   └── _taxonomy.json.jbuilder
│   │               ├── taxons
│   │               │   ├── index.json.jbuilder
│   │               │   ├── jstree.json.jbuilder
│   │               │   ├── new.json.jbuilder
│   │               │   ├── show.json.jbuilder
│   │               │   ├── _taxon.json.jbuilder
│   │               │   └── _taxons.json.jbuilder
│   │               ├── users
│   │               │   ├── index.json.jbuilder
│   │               │   ├── new.json.jbuilder
│   │               │   ├── show.json.jbuilder
│   │               │   └── _user.json.jbuilder
│   │               ├── variants
│   │               │   ├── _big.json.jbuilder
│   │               │   ├── index.json.jbuilder
│   │               │   ├── new.json.jbuilder
│   │               │   ├── show.json.jbuilder
│   │               │   └── _small.json.jbuilder
│   │               └── zones
│   │                   ├── index.json.jbuilder
│   │                   ├── show.json.jbuilder
│   │                   └── _zone.json.jbuilder
│   ├── config
│   │   ├── locales
│   │   │   └── en.yml
│   │   └── routes.rb
│   ├── db
│   │   └── migrate
│   │       ├── 20100107141738_add_api_key_to_spree_users.rb
│   │       ├── 20120411123334_resize_api_key_field.rb
│   │       ├── 20120530054546_rename_api_key_to_spree_api_key.rb
│   │       └── 20131017162334_add_index_to_user_spree_api_key.rb
│   ├── lib
│   │   ├── solidus_api.rb
│   │   ├── spree
│   │   │   ├── api
│   │   │   │   ├── engine.rb
│   │   │   │   ├── responders
│   │   │   │   │   └── rabl_template.rb
│   │   │   │   ├── responders.rb
│   │   │   │   └── testing_support
│   │   │   │       ├── caching.rb
│   │   │   │       ├── helpers.rb
│   │   │   │       └── setup.rb
│   │   │   └── api.rb
│   │   └── spree_api.rb
│   ├── LICENSE
│   ├── Rakefile
│   ├── README.md
│   ├── script
│   │   └── rails
│   ├── solidus_api.gemspec
│   └── spec
│       ├── controllers
│       │   └── spree
│       │       └── api
│       │           ├── base_controller_spec.rb
│       │           └── resource_controller_spec.rb
│       ├── features
│       │   └── checkout_spec.rb
│       ├── fixtures
│       │   └── thinking-cat.jpg
│       ├── models
│       │   └── spree
│       │       └── legacy_user_spec.rb
│       ├── requests
│       │   ├── api
│       │   │   └── address_books_spec.rb
│       │   ├── rabl_cache_spec.rb
│       │   ├── ransackable_attributes_spec.rb
│       │   └── spree
│       │       └── api
│       │           ├── addresses_controller_spec.rb
│       │           ├── checkouts_controller_spec.rb
│       │           ├── classifications_controller_spec.rb
│       │           ├── config_controller_spec.rb
│       │           ├── countries_controller_spec.rb
│       │           ├── coupon_codes_controller_spec.rb
│       │           ├── credit_cards_controller_spec.rb
│       │           ├── images_controller_spec.rb
│       │           ├── inventory_units_controller_spec.rb
│       │           ├── line_items_controller_spec.rb
│       │           ├── option_types_controller_spec.rb
│       │           ├── option_values_controller_spec.rb
│       │           ├── orders_controller_spec.rb
│       │           ├── payments_controller_spec.rb
│       │           ├── product_properties_controller_spec.rb
│       │           ├── products_controller_spec.rb
│       │           ├── promotion_application_spec.rb
│       │           ├── promotions_controller_spec.rb
│       │           ├── properties_controller_spec.rb
│       │           ├── return_authorizations_controller_spec.rb
│       │           ├── shipments_controller_spec.rb
│       │           ├── states_controller_spec.rb
│       │           ├── stock_items_controller_spec.rb
│       │           ├── stock_locations_controller_spec.rb
│       │           ├── stock_movements_controller_spec.rb
│       │           ├── store_credit_events_controller_spec.rb
│       │           ├── stores_controller_spec.rb
│       │           ├── taxonomies_controller_spec.rb
│       │           ├── taxons_controller_spec.rb
│       │           ├── unauthenticated_products_controller_spec.rb
│       │           ├── users_controller_spec.rb
│       │           ├── variants_controller_spec.rb
│       │           └── zones_controller_spec.rb
│       ├── shared_examples
│       │   └── protect_product_actions.rb
│       ├── spec_helper.rb
│       ├── support
│       │   ├── be_paginated_matcher.rb
│       │   ├── controller_hacks.rb
│       │   ├── database_cleaner.rb
│       │   └── have_attributes_matcher.rb
│       └── test_views
│           └── spree
│               └── api
│                   └── widgets
│                       ├── index.json.jbuilder
│                       ├── new.json.jbuilder
│                       ├── show.json.jbuilder
│                       └── _widget.json.jbuilder
├── app.json
├── backend
│   ├── app
│   │   ├── assets
│   │   │   ├── config
│   │   │   │   └── solidus_backend_manifest.js
│   │   │   ├── images
│   │   │   │   ├── favicon.ico
│   │   │   │   └── solidus-style-guide-logo.png
│   │   │   ├── javascripts
│   │   │   │   └── spree
│   │   │   │       ├── backend
│   │   │   │       │   ├── addresses.js
│   │   │   │       │   ├── adjustments.js
│   │   │   │       │   ├── admin.js
│   │   │   │       │   ├── backbone-overrides.js
│   │   │   │       │   ├── calculator.js
│   │   │   │       │   ├── checkouts
│   │   │   │       │   │   └── edit.js
│   │   │   │       │   ├── collections
│   │   │   │       │   │   ├── index.js
│   │   │   │       │   │   ├── line_items.js
│   │   │   │       │   │   ├── shipments.js
│   │   │   │       │   │   └── states.js
│   │   │   │       │   ├── components
│   │   │   │       │   │   ├── editable_table.js
│   │   │   │       │   │   ├── number_with_currency.js
│   │   │   │       │   │   ├── sortable_table.js
│   │   │   │       │   │   ├── tabs.js
│   │   │   │       │   │   └── tooltips.js
│   │   │   │       │   ├── datepicker.js
│   │   │   │       │   ├── flash.js
│   │   │   │       │   ├── format_money.js
│   │   │   │       │   ├── gateway.js
│   │   │   │       │   ├── handlebars_extensions.js
│   │   │   │       │   ├── highlight_negative_numbers.js
│   │   │   │       │   ├── images
│   │   │   │       │   │   ├── index.js
│   │   │   │       │   │   └── upload.js
│   │   │   │       │   ├── locale_selection.js
│   │   │   │       │   ├── models
│   │   │   │       │   │   ├── address.js
│   │   │   │       │   │   ├── image_upload.js
│   │   │   │       │   │   ├── index.js
│   │   │   │       │   │   ├── line_item.js
│   │   │   │       │   │   ├── order.js
│   │   │   │       │   │   ├── payment.js
│   │   │   │       │   │   ├── shipment.js
│   │   │   │       │   │   ├── stock_item.js
│   │   │   │       │   │   └── taxonomy.js
│   │   │   │       │   ├── namespaces.js
│   │   │   │       │   ├── navigation.js
│   │   │   │       │   ├── option_type_autocomplete.js
│   │   │   │       │   ├── option_value_picker.js
│   │   │   │       │   ├── orders
│   │   │   │       │   │   ├── cart.js
│   │   │   │       │   │   ├── edit.js
│   │   │   │       │   │   └── index.js
│   │   │   │       │   ├── payments
│   │   │   │       │   │   ├── edit.js
│   │   │   │       │   │   └── new.js
│   │   │   │       │   ├── product_picker.js
│   │   │   │       │   ├── progress.js
│   │   │   │       │   ├── promotions
│   │   │   │       │   │   └── activation.js
│   │   │   │       │   ├── promotions.js
│   │   │   │       │   ├── returns
│   │   │   │       │   │   └── return_item_selection.js
│   │   │   │       │   ├── routes.js
│   │   │   │       │   ├── shipments.js
│   │   │   │       │   ├── spree-select2.js
│   │   │   │       │   ├── stock_management.js
│   │   │   │       │   ├── store_credits.js
│   │   │   │       │   ├── style_guide.js
│   │   │   │       │   ├── taxon_autocomplete.js
│   │   │   │       │   ├── taxonomy.js
│   │   │   │       │   ├── taxons.js
│   │   │   │       │   ├── templates
│   │   │   │       │   │   ├── _image.hbs
│   │   │   │       │   │   ├── index.js
│   │   │   │       │   │   ├── orders
│   │   │   │       │   │   │   ├── customer_details
│   │   │   │       │   │   │   │   └── autocomplete.hbs
│   │   │   │       │   │   │   ├── details_adjustment_row.hbs
│   │   │   │       │   │   │   ├── line_item.hbs
│   │   │   │       │   │   │   ├── shipment_tracking.hbs
│   │   │   │       │   │   │   └── shipping_method.hbs
│   │   │   │       │   │   ├── products
│   │   │   │       │   │   │   ├── sortable.hbs
│   │   │   │       │   │   │   └── upload_progress.hbs
│   │   │   │       │   │   ├── promotions
│   │   │   │       │   │   │   ├── calculators
│   │   │   │       │   │   │   │   └── fields
│   │   │   │       │   │   │   │       ├── tiered_flat_rate.hbs
│   │   │   │       │   │   │   │       └── tiered_percent.hbs
│   │   │   │       │   │   │   └── rules
│   │   │   │       │   │   │       └── option_values.hbs
│   │   │   │       │   │   ├── stock_items
│   │   │   │       │   │   │   └── stock_location_stock_item.hbs
│   │   │   │       │   │   ├── taxons
│   │   │   │       │   │   │   ├── _tree.hbs
│   │   │   │       │   │   │   └── tree.hbs
│   │   │   │       │   │   └── variants
│   │   │   │       │   │       ├── autocomplete.hbs
│   │   │   │       │   │       ├── autocomplete_stock.hbs
│   │   │   │       │   │       ├── line_items_autocomplete_stock.hbs
│   │   │   │       │   │       └── split.hbs
│   │   │   │       │   ├── translation.js
│   │   │   │       │   ├── turbolinks-integration.js
│   │   │   │       │   ├── user_picker.js
│   │   │   │       │   ├── variant_autocomplete.js
│   │   │   │       │   ├── views
│   │   │   │       │   │   ├── calculators
│   │   │   │       │   │   │   └── tiered.js
│   │   │   │       │   │   ├── cart
│   │   │   │       │   │   │   ├── add_line_item_button.js
│   │   │   │       │   │   │   ├── line_item_row.js
│   │   │   │       │   │   │   └── line_item_table.js
│   │   │   │       │   │   ├── images
│   │   │   │       │   │   │   ├── upload_progress.js
│   │   │   │       │   │   │   └── upload_zone.js
│   │   │   │       │   │   ├── index.js
│   │   │   │       │   │   ├── number_with_currency.js
│   │   │   │       │   │   ├── order
│   │   │   │       │   │   │   ├── address.js
│   │   │   │       │   │   │   ├── customer_details.js
│   │   │   │       │   │   │   ├── customer_select.js
│   │   │   │       │   │   │   ├── details_adjustments.js
│   │   │   │       │   │   │   ├── details_total.js
│   │   │   │       │   │   │   ├── shipment_tracking.js
│   │   │   │       │   │   │   ├── shipping_method.js
│   │   │   │       │   │   │   └── summary.js
│   │   │   │       │   │   ├── payment
│   │   │   │       │   │   │   ├── edit_credit_card.js
│   │   │   │       │   │   │   ├── new.js
│   │   │   │       │   │   │   └── payment_row.js
│   │   │   │       │   │   ├── promotions
│   │   │   │       │   │   │   └── option_values_rule.js
│   │   │   │       │   │   ├── state_select.js
│   │   │   │       │   │   ├── stock
│   │   │   │       │   │   │   ├── add_stock_item.js
│   │   │   │       │   │   │   └── edit_stock_item_row.js
│   │   │   │       │   │   ├── tables
│   │   │   │       │   │   │   ├── editable_table.js
│   │   │   │       │   │   │   └── editable_table_row.js
│   │   │   │       │   │   └── zones
│   │   │   │       │   │       └── form.js
│   │   │   │       │   └── zone.js
│   │   │   │       └── backend.js
│   │   │   └── stylesheets
│   │   │       └── spree
│   │   │           ├── backend
│   │   │           │   ├── _bootstrap_custom.scss
│   │   │           │   ├── components
│   │   │           │   │   ├── _actions.scss
│   │   │           │   │   ├── _breadcrumb.scss
│   │   │           │   │   ├── _editable_table.scss
│   │   │           │   │   ├── _hint.scss
│   │   │           │   │   ├── _image_placeholder.scss
│   │   │           │   │   ├── _list_group.scss
│   │   │           │   │   ├── _messages.scss
│   │   │           │   │   ├── _navigation.scss
│   │   │           │   │   ├── _number_with_currency.scss
│   │   │           │   │   ├── _pills.scss
│   │   │           │   │   ├── _progress.scss
│   │   │           │   │   ├── _sidebar.scss
│   │   │           │   │   ├── _states.scss
│   │   │           │   │   ├── _stock_table.scss
│   │   │           │   │   ├── _table-filter.scss
│   │   │           │   │   └── _tabs.scss
│   │   │           │   ├── globals
│   │   │           │   │   ├── _deprecation.scss
│   │   │           │   │   ├── _functions.scss
│   │   │           │   │   ├── mixins
│   │   │           │   │   │   ├── _caret.scss
│   │   │           │   │   │   └── _line_through.scss
│   │   │           │   │   ├── _mixins.css
│   │   │           │   │   ├── _variables_override.scss
│   │   │           │   │   └── _variables.scss
│   │   │           │   ├── plugins
│   │   │           │   │   ├── _bootstrap_tooltip.scss
│   │   │           │   │   ├── _select2.scss
│   │   │           │   │   └── _sortable.scss
│   │   │           │   ├── sections
│   │   │           │   │   ├── _adjustments.scss
│   │   │           │   │   ├── _bulk_transfer.scss
│   │   │           │   │   ├── _image_settings.scss
│   │   │           │   │   ├── _log_entries.scss
│   │   │           │   │   ├── _orders.scss
│   │   │           │   │   ├── _products.scss
│   │   │           │   │   ├── _promotions.scss
│   │   │           │   │   ├── _return_authorizations.scss
│   │   │           │   │   ├── _stock_management.scss
│   │   │           │   │   ├── _store_credits.scss
│   │   │           │   │   ├── _style_guide.scss
│   │   │           │   │   ├── _taxonomies.scss
│   │   │           │   │   ├── _taxons.scss
│   │   │           │   │   ├── _users.scss
│   │   │           │   │   └── _variants.scss
│   │   │           │   ├── shared
│   │   │           │   │   ├── _forms.scss
│   │   │           │   │   ├── _header.scss
│   │   │           │   │   ├── _icons.scss
│   │   │           │   │   ├── _images.scss
│   │   │           │   │   ├── _layout.scss
│   │   │           │   │   ├── _tables.scss
│   │   │           │   │   ├── _typography.scss
│   │   │           │   │   └── _utilities.scss
│   │   │           │   ├── spree_admin.scss
│   │   │           │   └── themes
│   │   │           │       └── blue_steel
│   │   │           │           └── globals
│   │   │           │               └── _variables_override.scss
│   │   │           └── backend.css
│   │   ├── controllers
│   │   │   └── spree
│   │   │       └── admin
│   │   │           ├── adjustment_reasons_controller.rb
│   │   │           ├── adjustments_controller.rb
│   │   │           ├── base_controller.rb
│   │   │           ├── cancellations_controller.rb
│   │   │           ├── customer_returns_controller.rb
│   │   │           ├── dashboards_controller.rb
│   │   │           ├── general_settings_controller.rb
│   │   │           ├── images_controller.rb
│   │   │           ├── locale_controller.rb
│   │   │           ├── log_entries_controller.rb
│   │   │           ├── option_types_controller.rb
│   │   │           ├── option_values_controller.rb
│   │   │           ├── orders
│   │   │           │   └── customer_details_controller.rb
│   │   │           ├── orders_controller.rb
│   │   │           ├── payment_methods_controller.rb
│   │   │           ├── payments_controller.rb
│   │   │           ├── prices_controller.rb
│   │   │           ├── product_properties_controller.rb
│   │   │           ├── products_controller.rb
│   │   │           ├── promotion_actions_controller.rb
│   │   │           ├── promotion_categories_controller.rb
│   │   │           ├── promotion_code_batches_controller.rb
│   │   │           ├── promotion_codes_controller.rb
│   │   │           ├── promotion_rules_controller.rb
│   │   │           ├── promotions_controller.rb
│   │   │           ├── properties_controller.rb
│   │   │           ├── refund_reasons_controller.rb
│   │   │           ├── refunds_controller.rb
│   │   │           ├── reimbursements_controller.rb
│   │   │           ├── reimbursement_types_controller.rb
│   │   │           ├── resource_controller.rb
│   │   │           ├── return_authorizations_controller.rb
│   │   │           ├── return_items_controller.rb
│   │   │           ├── return_reasons_controller.rb
│   │   │           ├── root_controller.rb
│   │   │           ├── search_controller.rb
│   │   │           ├── shipping_categories_controller.rb
│   │   │           ├── shipping_methods_controller.rb
│   │   │           ├── stock_items_controller.rb
│   │   │           ├── stock_locations_controller.rb
│   │   │           ├── stock_movements_controller.rb
│   │   │           ├── store_credit_reasons_controller.rb
│   │   │           ├── store_credits_controller.rb
│   │   │           ├── stores_controller.rb
│   │   │           ├── style_guide_controller.rb
│   │   │           ├── tax_categories_controller.rb
│   │   │           ├── taxonomies_controller.rb
│   │   │           ├── taxons_controller.rb
│   │   │           ├── tax_rates_controller.rb
│   │   │           ├── users_controller.rb
│   │   │           ├── variant_property_rule_values_controller.rb
│   │   │           ├── variants_controller.rb
│   │   │           ├── variants_including_master_controller.rb
│   │   │           └── zones_controller.rb
│   │   ├── helpers
│   │   │   └── spree
│   │   │       ├── admin
│   │   │       │   ├── adjustments_helper.rb
│   │   │       │   ├── base_helper.rb
│   │   │       │   ├── customer_returns_helper.rb
│   │   │       │   ├── navigation_helper.rb
│   │   │       │   ├── orders_helper.rb
│   │   │       │   ├── payments_helper.rb
│   │   │       │   ├── products_helper.rb
│   │   │       │   ├── reimbursement_type_helper.rb
│   │   │       │   ├── stock_locations_helper.rb
│   │   │       │   ├── stock_movements_helper.rb
│   │   │       │   └── store_credit_events_helper.rb
│   │   │       └── promotion_rules_helper.rb
│   │   ├── models
│   │   │   └── spree
│   │   │       └── backend_configuration.rb
│   │   └── views
│   │       ├── kaminari
│   │       │   └── solidus_admin
│   │       │       ├── _first_page.html.erb
│   │       │       ├── _gap.html.erb
│   │       │       ├── _last_page.html.erb
│   │       │       ├── _next_page.html.erb
│   │       │       ├── _page.html.erb
│   │       │       ├── _paginator.html.erb
│   │       │       └── _prev_page.html.erb
│   │       └── spree
│   │           ├── admin
│   │           │   ├── adjustment_reasons
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   ├── new.html.erb
│   │           │   │   └── shared
│   │           │   │       └── _form.html.erb
│   │           │   ├── adjustments
│   │           │   │   ├── _adjustment.html.erb
│   │           │   │   ├── _adjustments_table.html.erb
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── cancellations
│   │           │   │   └── index.html.erb
│   │           │   ├── customer_returns
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   ├── new.html.erb
│   │           │   │   ├── _reimbursements_table.html.erb
│   │           │   │   ├── _return_item_decision.html.erb
│   │           │   │   └── _return_item_selection.html.erb
│   │           │   ├── dashboards
│   │           │   │   └── home.html.erb
│   │           │   ├── images
│   │           │   │   ├── create.js.erb
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── _image_row.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   ├── _new.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── log_entries
│   │           │   │   └── index.html.erb
│   │           │   ├── option_types
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   ├── new.html.erb
│   │           │   │   ├── new.js.erb
│   │           │   │   └── _option_value_fields.html.erb
│   │           │   ├── orders
│   │           │   │   ├── _add_product.html.erb
│   │           │   │   ├── _adjustments.html.erb
│   │           │   │   ├── cart.html.erb
│   │           │   │   ├── _carton.html.erb
│   │           │   │   ├── _carton_manifest.html.erb
│   │           │   │   ├── confirm
│   │           │   │   │   ├── _customer_details.html.erb
│   │           │   │   │   ├── _line_items.html.erb
│   │           │   │   │   ├── _payments.html.erb
│   │           │   │   │   ├── _shipment.html.erb
│   │           │   │   │   └── _shipment_manifest.html.erb
│   │           │   │   ├── confirm_advance.html.erb
│   │           │   │   ├── confirm.html.erb
│   │           │   │   ├── customer_details
│   │           │   │   │   ├── edit.html.erb
│   │           │   │   │   ├── _form.html.erb
│   │           │   │   │   └── show.html.erb
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   ├── _line_items_edit_form.html.erb
│   │           │   │   ├── _line_items.html.erb
│   │           │   │   ├── _order_details.html.erb
│   │           │   │   ├── _risk_analysis.html.erb
│   │           │   │   ├── _shipment.html.erb
│   │           │   │   └── _shipment_manifest.html.erb
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
│   │           │   │   ├── _log_entries.html.erb
│   │           │   │   ├── new.html.erb
│   │           │   │   ├── show.html.erb
│   │           │   │   ├── source_forms
│   │           │   │   │   ├── _check.html.erb
│   │           │   │   │   ├── _gateway.html.erb
│   │           │   │   │   └── _storecredit.html.erb
│   │           │   │   └── source_views
│   │           │   │       ├── _check.html.erb
│   │           │   │       ├── _gateway.html.erb
│   │           │   │       └── _storecredit.html.erb
│   │           │   ├── prices
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   ├── _master_variant_table.html.erb
│   │           │   │   ├── new.html.erb
│   │           │   │   └── _table.html.erb
│   │           │   ├── product_properties
│   │           │   │   ├── index.html.erb
│   │           │   │   └── _product_property_fields.html.erb
│   │           │   ├── products
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── promotion_actions
│   │           │   │   ├── create.js.erb
│   │           │   │   └── destroy.js.erb
│   │           │   ├── promotion_categories
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── promotion_code_batches
│   │           │   │   ├── download.csv.ruby
│   │           │   │   ├── index.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── promotion_codes
│   │           │   │   ├── index.csv.ruby
│   │           │   │   ├── index.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── promotion_rules
│   │           │   │   ├── create.js.erb
│   │           │   │   └── destroy.js.erb
│   │           │   ├── promotions
│   │           │   │   ├── actions
│   │           │   │   │   ├── _create_adjustment.html.erb
│   │           │   │   │   ├── _create_item_adjustments.html.erb
│   │           │   │   │   ├── _create_quantity_adjustments.html.erb
│   │           │   │   │   ├── _free_shipping.html.erb
│   │           │   │   │   └── _promotion_calculators_with_custom_fields.html.erb
│   │           │   │   ├── _actions.html.erb
│   │           │   │   ├── _activations_edit.html.erb
│   │           │   │   ├── _activations_new.html.erb
│   │           │   │   ├── calculators
│   │           │   │   │   ├── _default_fields.html.erb
│   │           │   │   │   ├── distributed_amount
│   │           │   │   │   │   └── _fields.html.erb
│   │           │   │   │   ├── flat_rate
│   │           │   │   │   │   └── _fields.html.erb
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
│   │           │   │   │   ├── _first_order.html.erb
│   │           │   │   │   ├── _first_repeat_purchase_since.html.erb
│   │           │   │   │   ├── _item_total.html.erb
│   │           │   │   │   ├── _nth_order.html.erb
│   │           │   │   │   ├── _one_use_per_user.html.erb
│   │           │   │   │   ├── _option_value.html.erb
│   │           │   │   │   ├── _product.html.erb
│   │           │   │   │   ├── _store.html.erb
│   │           │   │   │   ├── _taxon.html.erb
│   │           │   │   │   ├── _user.html.erb
│   │           │   │   │   ├── _user_logged_in.html.erb
│   │           │   │   │   └── _user_role.html.erb
│   │           │   │   └── _rules.html.erb
│   │           │   ├── properties
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── filtered.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   ├── new.html.erb
│   │           │   │   └── new.js.erb
│   │           │   ├── refund_reasons
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   ├── new.html.erb
│   │           │   │   └── shared
│   │           │   │       └── _form.html.erb
│   │           │   ├── refunds
│   │           │   │   ├── edit.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── reimbursements
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── show.html.erb
│   │           │   ├── reimbursement_types
│   │           │   │   └── index.html.erb
│   │           │   ├── return_authorizations
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── return_reasons
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── search
│   │           │   │   ├── products.json.jbuilder
│   │           │   │   └── users.json.jbuilder
│   │           │   ├── shared
│   │           │   │   ├── _address_form.html.erb
│   │           │   │   ├── _address.html.erb
│   │           │   │   ├── _calculator_fields.html.erb
│   │           │   │   ├── _configuration_menu.html.erb
│   │           │   │   ├── _datepicker.html.erb
│   │           │   │   ├── _destroy.js.erb
│   │           │   │   ├── _edit_resource_links.html.erb
│   │           │   │   ├── _flash.html.erb
│   │           │   │   ├── _general_tabs.html.erb
│   │           │   │   ├── _header.html.erb
│   │           │   │   ├── _head.html.erb
│   │           │   │   ├── _image.html.erb
│   │           │   │   ├── _js_locale_data.html.erb
│   │           │   │   ├── _locale_selection.html.erb
│   │           │   │   ├── _menu.html.erb
│   │           │   │   ├── _modal.html.erb
│   │           │   │   ├── named_types
│   │           │   │   │   ├── _edit.html.erb
│   │           │   │   │   ├── _form.html.erb
│   │           │   │   │   ├── _index.html.erb
│   │           │   │   │   └── _new.html.erb
│   │           │   │   ├── _navigation_footer.html.erb
│   │           │   │   ├── _navigation_header.html.erb
│   │           │   │   ├── _navigation.html.erb
│   │           │   │   ├── _new_resource_links.html.erb
│   │           │   │   ├── _no_objects_found.html.erb
│   │           │   │   ├── _number_with_currency.html.erb
│   │           │   │   ├── _order_submenu.html.erb
│   │           │   │   ├── _order_summary.html.erb
│   │           │   │   ├── _order_tabs.html.erb
│   │           │   │   ├── _payments_tabs.html.erb
│   │           │   │   ├── preference_fields
│   │           │   │   │   ├── _boolean.html.erb
│   │           │   │   │   ├── _decimal.html.erb
│   │           │   │   │   ├── _integer.html.erb
│   │           │   │   │   ├── _password.html.erb
│   │           │   │   │   ├── _string.html.erb
│   │           │   │   │   └── _text.html.erb
│   │           │   │   ├── _product_sub_menu.html.erb
│   │           │   │   ├── _product_tabs.html.erb
│   │           │   │   ├── _promotion_sub_menu.html.erb
│   │           │   │   ├── _rebuild_vat_prices_checkbox.html.erb
│   │           │   │   ├── _refunds.html.erb
│   │           │   │   ├── _settings_checkout_tabs.html.erb
│   │           │   │   ├── _settings_sub_menu.html.erb
│   │           │   │   ├── _shipping_tabs.html.erb
│   │           │   │   ├── _sidebar.html.erb
│   │           │   │   ├── _spinner.html.erb
│   │           │   │   ├── _table_filter.html.erb
│   │           │   │   ├── _tabs.html.erb
│   │           │   │   ├── _taxes_tabs.html.erb
│   │           │   │   └── _variant_search.html.erb
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
│   │           │   ├── stock_items
│   │           │   │   ├── destroy.js.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── _stock_management.html.erb
│   │           │   ├── stock_locations
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── stock_movements
│   │           │   │   └── index.html.erb
│   │           │   ├── store_credit_reasons
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   ├── new.html.erb
│   │           │   │   └── shared
│   │           │   │       └── _form.html.erb
│   │           │   ├── store_credits
│   │           │   │   ├── edit_amount.html.erb
│   │           │   │   ├── edit_validity.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   ├── new.html.erb
│   │           │   │   ├── show.html.erb
│   │           │   │   └── _store_credit_reason_field.html.erb
│   │           │   ├── stores
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── new.html.erb
│   │           │   ├── style_guide
│   │           │   │   ├── index.html.erb
│   │           │   │   └── topics
│   │           │   │       ├── components
│   │           │   │       │   ├── _modals.html.erb
│   │           │   │       │   ├── _pills.html.erb
│   │           │   │       │   └── _tabs.html.erb
│   │           │   │       ├── forms
│   │           │   │       │   ├── _building_forms.html.erb
│   │           │   │       │   ├── _buttons.html.erb
│   │           │   │       │   ├── _helper_text.html.erb
│   │           │   │       │   ├── _inputs.html.erb
│   │           │   │       │   ├── _labels.html.erb
│   │           │   │       │   └── _validation.html.erb
│   │           │   │       ├── layout
│   │           │   │       │   ├── _full_width_table_layout.html.erb
│   │           │   │       │   ├── _helpful_layout.html.erb
│   │           │   │       │   └── _sidebar_layout.html.erb
│   │           │   │       ├── messaging
│   │           │   │       │   ├── _flashes.html.erb
│   │           │   │       │   ├── _loading.html.erb
│   │           │   │       │   └── _tooltips.html.erb
│   │           │   │       ├── tables
│   │           │   │       │   ├── _building_tables.html.erb
│   │           │   │       │   ├── _forms_in_tables.html.erb
│   │           │   │       │   └── _pagination.html.erb
│   │           │   │       └── typography
│   │           │   │           ├── _colors.html.erb
│   │           │   │           ├── _fonts.html.erb
│   │           │   │           ├── _icons.html.erb
│   │           │   │           └── _lists.html.erb
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
│   │           │   │   ├── _list.html.erb
│   │           │   │   ├── new.html.erb
│   │           │   │   └── _taxon.html.erb
│   │           │   ├── taxons
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   └── search.json.jbuilder
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
│   │           │   │   ├── new.html.erb
│   │           │   │   ├── orders.html.erb
│   │           │   │   ├── _sidebar.html.erb
│   │           │   │   ├── _tabs.html.erb
│   │           │   │   └── _user_page_actions.html.erb
│   │           │   ├── variants
│   │           │   │   ├── edit.html.erb
│   │           │   │   ├── _form.html.erb
│   │           │   │   ├── index.html.erb
│   │           │   │   ├── new.html.erb
│   │           │   │   ├── _table_filter.html.erb
│   │           │   │   ├── _table.html.erb
│   │           │   │   └── update.js.erb
│   │           │   └── zones
│   │           │       ├── _country_members.html.erb
│   │           │       ├── edit.html.erb
│   │           │       ├── _form.html.erb
│   │           │       ├── index.html.erb
│   │           │       ├── new.html.erb
│   │           │       └── _state_members.html.erb
│   │           └── layouts
│   │               ├── admin.html.erb
│   │               └── admin_style_guide.html.erb
│   ├── config
│   │   ├── initializers
│   │   │   ├── assets.rb
│   │   │   └── form_builder.rb
│   │   └── routes.rb
│   ├── lib
│   │   ├── solidus_backend.rb
│   │   ├── spree
│   │   │   ├── backend
│   │   │   │   ├── action_callbacks.rb
│   │   │   │   ├── callbacks.rb
│   │   │   │   └── engine.rb
│   │   │   └── backend.rb
│   │   └── spree_backend.rb
│   ├── Rakefile
│   ├── README.md
│   ├── script
│   │   └── rails
│   ├── solidus_backend.gemspec
│   ├── spec
│   │   ├── controllers
│   │   │   └── spree
│   │   │       └── admin
│   │   │           ├── base_controller_spec.rb
│   │   │           ├── cancellations_controller_spec.rb
│   │   │           ├── customer_returns_controller_spec.rb
│   │   │           ├── locale_controller_spec.rb
│   │   │           ├── missing_products_controller_spec.rb
│   │   │           ├── orders
│   │   │           │   └── customer_details_controller_spec.rb
│   │   │           ├── orders_controller_spec.rb
│   │   │           ├── payment_methods_controller_spec.rb
│   │   │           ├── payments_controller_spec.rb
│   │   │           ├── prices_controller_spec.rb
│   │   │           ├── product_properties_controller_spec.rb
│   │   │           ├── products_controller_spec.rb
│   │   │           ├── promotion_actions_controller_spec.rb
│   │   │           ├── promotion_codes_controller_spec.rb
│   │   │           ├── promotion_rules_controller_spec.rb
│   │   │           ├── promotions_controller_spec.rb
│   │   │           ├── refunds_controller_spec.rb
│   │   │           ├── reimbursements_controller_spec.rb
│   │   │           ├── resource_controller_spec.rb
│   │   │           ├── return_authorizations_controller_spec.rb
│   │   │           ├── return_items_controller_spec.rb
│   │   │           ├── root_controller_spec.rb
│   │   │           ├── search_controller_spec.rb
│   │   │           ├── shipping_methods_controller_spec.rb
│   │   │           ├── stock_items_controller_spec.rb
│   │   │           ├── stock_locations_controller_spec.rb
│   │   │           ├── store_credits_controller_spec.rb
│   │   │           ├── users_controller_spec.rb
│   │   │           └── variants_controller_spec.rb
│   │   ├── features
│   │   │   └── admin
│   │   │       ├── configuration
│   │   │       │   ├── payment_methods_spec.rb
│   │   │       │   ├── shipping_methods_spec.rb
│   │   │       │   ├── stock_locations_spec.rb
│   │   │       │   ├── store_spec.rb
│   │   │       │   ├── tax_categories_spec.rb
│   │   │       │   ├── taxonomies_spec.rb
│   │   │       │   ├── tax_rates_spec.rb
│   │   │       │   └── zones_spec.rb
│   │   │       ├── homepage_spec.rb
│   │   │       ├── javascript_format_money_spec.rb
│   │   │       ├── locale_spec.rb
│   │   │       ├── orders
│   │   │       │   ├── adjustments_promotions_spec.rb
│   │   │       │   ├── adjustments_spec.rb
│   │   │       │   ├── cancelling_and_resuming_spec.rb
│   │   │       │   ├── cancelling_inventory_spec.rb
│   │   │       │   ├── customer_details_spec.rb
│   │   │       │   ├── line_items_spec.rb
│   │   │       │   ├── listing_spec.rb
│   │   │       │   ├── log_entries_spec.rb
│   │   │       │   ├── new_order_spec.rb
│   │   │       │   ├── new_refund_spec.rb
│   │   │       │   ├── order_details_spec.rb
│   │   │       │   ├── payments_spec.rb
│   │   │       │   ├── return_authorizations_spec.rb
│   │   │       │   ├── return_payment_state_spec.rb
│   │   │       │   ├── risk_analysis_spec.rb
│   │   │       │   └── shipments_spec.rb
│   │   │       ├── payments
│   │   │       │   └── store_credits_spec.rb
│   │   │       ├── products
│   │   │       │   ├── edit
│   │   │       │   │   ├── images_spec.rb
│   │   │       │   │   ├── products_spec.rb
│   │   │       │   │   ├── taxons_spec.rb
│   │   │       │   │   └── variants_spec.rb
│   │   │       │   ├── option_types_spec.rb
│   │   │       │   ├── pricing_spec.rb
│   │   │       │   ├── products_spec.rb
│   │   │       │   ├── properties_spec.rb
│   │   │       │   ├── stock_management_spec.rb
│   │   │       │   └── variant_spec.rb
│   │   │       ├── promotion_adjustments_spec.rb
│   │   │       ├── promotions
│   │   │       │   ├── option_value_rule_spec.rb
│   │   │       │   ├── product_rule_spec.rb
│   │   │       │   ├── promotion_categories_spec.rb
│   │   │       │   ├── tiered_calculator_spec.rb
│   │   │       │   └── user_rule_spec.rb
│   │   │       ├── reimbursements_spec.rb
│   │   │       ├── store_credits_spec.rb
│   │   │       ├── stores_spec.rb
│   │   │       ├── style_guide_spec.rb
│   │   │       ├── taxons_spec.rb
│   │   │       └── users_spec.rb
│   │   ├── helpers
│   │   │   ├── admin
│   │   │   │   ├── base_helper_spec.rb
│   │   │   │   ├── navigation_helper_spec.rb
│   │   │   │   ├── stock_movements_helper_spec.rb
│   │   │   │   └── store_credit_events_helper_spec.rb
│   │   │   └── promotion_rules_helper_spec.rb
│   │   ├── javascripts
│   │   │   ├── fixtures
│   │   │   │   ├── _boot.html.erb
│   │   │   │   └── number_with_currency
│   │   │   │       ├── with_currency_select.html.erb
│   │   │   │       └── without_select.html.erb
│   │   │   ├── format_money_spec.js
│   │   │   ├── spec_helper.js
│   │   │   ├── support
│   │   │   │   ├── show_errors.js
│   │   │   │   └── with_translations.js
│   │   │   ├── translation_spec.js
│   │   │   └── views
│   │   │       └── number_with_currency_spec.js
│   │   ├── models
│   │   │   └── spree
│   │   │       ├── backend_configuration
│   │   │       │   └── menu_item_spec.rb
│   │   │       └── backend_configuration_spec.rb
│   │   ├── spec_helper.rb
│   │   ├── support
│   │   │   ├── appear_before_matcher.rb
│   │   │   ├── feature
│   │   │   │   ├── base_feature_helper.rb
│   │   │   │   └── order_feature_helper.rb
│   │   │   └── ror_ringer.jpeg
│   │   ├── teaspoon_env.rb
│   │   ├── test_views
│   │   │   └── spree
│   │   │       └── admin
│   │   │           └── widgets
│   │   │               ├── edit.html.erb
│   │   │               └── new.html.erb
│   │   └── views
│   │       └── spree
│   │           └── admin
│   │               └── shared
│   │                   └── navigation_footer_spec.rb
│   └── vendor
│       └── assets
│           ├── images
│           │   └── solidus_admin
│           │       ├── select2.png
│           │       ├── select2-spinner.gif
│           │       └── select2x2.png
│           ├── javascripts
│           │   ├── jquery.sticky-kit.min.js
│           │   ├── prism.js
│           │   └── solidus_admin
│           │       ├── accounting.js
│           │       ├── backbone.js
│           │       ├── backbone-nested-models.js
│           │       ├── bind-polyfill.js
│           │       ├── bootstrap.js
│           │       ├── flatpickr
│           │       │   └── flatpickr.js
│           │       ├── popover.js
│           │       ├── select2.js
│           │       ├── select2_locales
│           │       │   ├── index.js
│           │       │   ├── select2_locale_ar.js
│           │       │   ├── select2_locale_az.js
│           │       │   ├── select2_locale_bg.js
│           │       │   ├── select2_locale_ca.js
│           │       │   ├── select2_locale_cs.js
│           │       │   ├── select2_locale_da.js
│           │       │   ├── select2_locale_de.js
│           │       │   ├── select2_locale_el.js
│           │       │   ├── select2_locale_en-US.js
│           │       │   ├── select2_locale_es.js
│           │       │   ├── select2_locale_es-MX.js
│           │       │   ├── select2_locale_et.js
│           │       │   ├── select2_locale_eu.js
│           │       │   ├── select2_locale_fa.js
│           │       │   ├── select2_locale_fi.js
│           │       │   ├── select2_locale_fr.js
│           │       │   ├── select2_locale_gl.js
│           │       │   ├── select2_locale_he.js
│           │       │   ├── select2_locale_hr.js
│           │       │   ├── select2_locale_hu.js
│           │       │   ├── select2_locale_id.js
│           │       │   ├── select2_locale_is.js
│           │       │   ├── select2_locale_it.js
│           │       │   ├── select2_locale_ja.js
│           │       │   ├── select2_locale_ka.js
│           │       │   ├── select2_locale_ko.js
│           │       │   ├── select2_locale_lt.js
│           │       │   ├── select2_locale_lv.js
│           │       │   ├── select2_locale_mk.js
│           │       │   ├── select2_locale_ms.js
│           │       │   ├── select2_locale_nb.js
│           │       │   ├── select2_locale_nl.js
│           │       │   ├── select2_locale_pl.js
│           │       │   ├── select2_locale_pt-BR.js
│           │       │   ├── select2_locale_pt-PT.js
│           │       │   ├── select2_locale_ro.js
│           │       │   ├── select2_locale_rs.js
│           │       │   ├── select2_locale_ru.js
│           │       │   ├── select2_locale_sk.js
│           │       │   ├── select2_locale_sv.js
│           │       │   ├── select2_locale_th.js
│           │       │   ├── select2_locale_tr.js
│           │       │   ├── select2_locale_ug-CN.js
│           │       │   ├── select2_locale_uk.js
│           │       │   ├── select2_locale_vi.js
│           │       │   ├── select2_locale_zh-CN.js
│           │       │   └── select2_locale_zh-TW.js
│           │       ├── Sortable.js
│           │       └── underscore.js
│           └── stylesheets
│               ├── prism.css
│               └── solidus_admin
│                   ├── bootstrap
│                   │   ├── _alert.scss
│                   │   ├── _badge.scss
│                   │   ├── bootstrap-grid.scss
│                   │   ├── bootstrap-reboot.scss
│                   │   ├── bootstrap.scss
│                   │   ├── _breadcrumb.scss
│                   │   ├── _button-group.scss
│                   │   ├── _buttons.scss
│                   │   ├── _card.scss
│                   │   ├── _carousel.scss
│                   │   ├── _close.scss
│                   │   ├── _code.scss
│                   │   ├── _custom-forms.scss
│                   │   ├── _dropdown.scss
│                   │   ├── _forms.scss
│                   │   ├── _functions.scss
│                   │   ├── _grid.scss
│                   │   ├── _images.scss
│                   │   ├── _input-group.scss
│                   │   ├── _jumbotron.scss
│                   │   ├── _list-group.scss
│                   │   ├── _media.scss
│                   │   ├── mixins
│                   │   │   ├── _alert.scss
│                   │   │   ├── _background-variant.scss
│                   │   │   ├── _badge.scss
│                   │   │   ├── _border-radius.scss
│                   │   │   ├── _box-shadow.scss
│                   │   │   ├── _breakpoints.scss
│                   │   │   ├── _buttons.scss
│                   │   │   ├── _caret.scss
│                   │   │   ├── _clearfix.scss
│                   │   │   ├── _float.scss
│                   │   │   ├── _forms.scss
│                   │   │   ├── _gradients.scss
│                   │   │   ├── _grid-framework.scss
│                   │   │   ├── _grid.scss
│                   │   │   ├── _hover.scss
│                   │   │   ├── _image.scss
│                   │   │   ├── _list-group.scss
│                   │   │   ├── _lists.scss
│                   │   │   ├── _navbar-align.scss
│                   │   │   ├── _nav-divider.scss
│                   │   │   ├── _pagination.scss
│                   │   │   ├── _reset-text.scss
│                   │   │   ├── _resize.scss
│                   │   │   ├── _screen-reader.scss
│                   │   │   ├── _size.scss
│                   │   │   ├── _table-row.scss
│                   │   │   ├── _text-emphasis.scss
│                   │   │   ├── _text-hide.scss
│                   │   │   ├── _text-truncate.scss
│                   │   │   ├── _transition.scss
│                   │   │   └── _visibility.scss
│                   │   ├── _mixins.scss
│                   │   ├── _modal.scss
│                   │   ├── _navbar.scss
│                   │   ├── _nav.scss
│                   │   ├── _pagination.scss
│                   │   ├── _popover.scss
│                   │   ├── _print.scss
│                   │   ├── _progress.scss
│                   │   ├── _reboot.scss
│                   │   ├── _root.scss
│                   │   ├── _tables.scss
│                   │   ├── _tooltip.scss
│                   │   ├── _transitions.scss
│                   │   ├── _type.scss
│                   │   ├── utilities
│                   │   │   ├── _align.scss
│                   │   │   ├── _background.scss
│                   │   │   ├── _borders.scss
│                   │   │   ├── _clearfix.scss
│                   │   │   ├── _display.scss
│                   │   │   ├── _embed.scss
│                   │   │   ├── _flex.scss
│                   │   │   ├── _float.scss
│                   │   │   ├── _position.scss
│                   │   │   ├── _screenreaders.scss
│                   │   │   ├── _sizing.scss
│                   │   │   ├── _spacing.scss
│                   │   │   ├── _text.scss
│                   │   │   └── _visibility.scss
│                   │   ├── _utilities.scss
│                   │   └── _variables.scss
│                   ├── flatpickr
│                   │   └── flatpickr.css
│                   └── select2.scss
├── bin
│   ├── build
│   └── build-ci
├── CHANGELOG.md
├── CONTRIBUTING.md
├── core
│   ├── app
│   │   ├── assets
│   │   │   ├── config
│   │   │   │   └── solidus_core_manifest.js
│   │   │   ├── images
│   │   │   │   ├── logo
│   │   │   │   │   ├── solidus_logo.png
│   │   │   │   │   └── solidus.svg
│   │   │   │   └── noimage
│   │   │   │       ├── large.png
│   │   │   │       ├── mini.png
│   │   │   │       ├── product.png
│   │   │   │       └── small.png
│   │   │   └── javascripts
│   │   │       └── spree.js.erb
│   │   ├── controllers
│   │   │   └── spree
│   │   │       └── base_controller.rb
│   │   ├── helpers
│   │   │   └── spree
│   │   │       ├── base_helper.rb
│   │   │       ├── checkout_helper.rb
│   │   │       ├── products_helper.rb
│   │   │       ├── store_helper.rb
│   │   │       └── taxons_helper.rb
│   │   ├── jobs
│   │   │   └── spree
│   │   │       └── promotion_code_batch_job.rb
│   │   ├── mailers
│   │   │   └── spree
│   │   │       ├── base_mailer.rb
│   │   │       ├── carton_mailer.rb
│   │   │       ├── order_mailer.rb
│   │   │       ├── promotion_code_batch_mailer.rb
│   │   │       ├── reimbursement_mailer.rb
│   │   │       └── test_mailer.rb
│   │   ├── models
│   │   │   ├── concerns
│   │   │   │   └── spree
│   │   │   │       ├── adjustment_source.rb
│   │   │   │       ├── calculated_adjustments.rb
│   │   │   │       ├── default_price.rb
│   │   │   │       ├── display_money.rb
│   │   │   │       ├── named_type.rb
│   │   │   │       ├── ordered_property_value_list.rb
│   │   │   │       ├── ransackable_attributes.rb
│   │   │   │       ├── user_address_book.rb
│   │   │   │       ├── user_api_authentication.rb
│   │   │   │       ├── user_methods.rb
│   │   │   │       ├── user_payment_source.rb
│   │   │   │       └── user_reporting.rb
│   │   │   └── spree
│   │   │       ├── ability.rb
│   │   │       ├── address.rb
│   │   │       ├── adjustment.rb
│   │   │       ├── adjustment_reason.rb
│   │   │       ├── asset.rb
│   │   │       ├── base.rb
│   │   │       ├── billing_integration.rb
│   │   │       ├── calculator
│   │   │       │   ├── default_tax.rb
│   │   │       │   ├── distributed_amount.rb
│   │   │       │   ├── flat_percent_item_total.rb
│   │   │       │   ├── flat_rate.rb
│   │   │       │   ├── flexi_rate.rb
│   │   │       │   ├── free_shipping.rb
│   │   │       │   ├── percent_on_line_item.rb
│   │   │       │   ├── percent_per_item.rb
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
│   │   │       ├── carton.rb
│   │   │       ├── classification.rb
│   │   │       ├── country.rb
│   │   │       ├── credit_card.rb
│   │   │       ├── customer_return.rb
│   │   │       ├── distributed_amounts_handler.rb
│   │   │       ├── exchange.rb
│   │   │       ├── fulfilment_changer.rb
│   │   │       ├── gallery
│   │   │       │   ├── product_gallery.rb
│   │   │       │   └── variant_gallery.rb
│   │   │       ├── gateway
│   │   │       │   ├── bogus.rb
│   │   │       │   └── bogus_simple.rb
│   │   │       ├── gateway.rb
│   │   │       ├── image.rb
│   │   │       ├── inventory_unit.rb
│   │   │       ├── legacy_user.rb
│   │   │       ├── line_item_action.rb
│   │   │       ├── line_item.rb
│   │   │       ├── log_entry.rb
│   │   │       ├── option_type.rb
│   │   │       ├── option_value.rb
│   │   │       ├── option_values_variant.rb
│   │   │       ├── order
│   │   │       │   ├── checkout.rb
│   │   │       │   ├── number_generator.rb
│   │   │       │   └── payments.rb
│   │   │       ├── order_cancellations.rb
│   │   │       ├── order_capturing.rb
│   │   │       ├── order_contents.rb
│   │   │       ├── order_inventory.rb
│   │   │       ├── order_merger.rb
│   │   │       ├── order_mutex.rb
│   │   │       ├── order_promotion.rb
│   │   │       ├── order.rb
│   │   │       ├── order_shipping.rb
│   │   │       ├── order_taxation.rb
│   │   │       ├── order_update_attributes.rb
│   │   │       ├── order_updater.rb
│   │   │       ├── payment
│   │   │       │   ├── cancellation.rb
│   │   │       │   └── processing.rb
│   │   │       ├── payment_capture_event.rb
│   │   │       ├── payment_create.rb
│   │   │       ├── payment_method
│   │   │       │   ├── bogus_credit_card.rb
│   │   │       │   ├── check.rb
│   │   │       │   ├── credit_card.rb
│   │   │       │   ├── simple_bogus_credit_card.rb
│   │   │       │   └── store_credit.rb
│   │   │       ├── payment_method.rb
│   │   │       ├── payment.rb
│   │   │       ├── payment_source.rb
│   │   │       ├── preference.rb
│   │   │       ├── price.rb
│   │   │       ├── product
│   │   │       │   └── scopes.rb
│   │   │       ├── product_option_type.rb
│   │   │       ├── product_promotion_rule.rb
│   │   │       ├── product_property.rb
│   │   │       ├── product.rb
│   │   │       ├── promotion
│   │   │       │   ├── actions
│   │   │       │   │   ├── create_adjustment.rb
│   │   │       │   │   ├── create_item_adjustments.rb
│   │   │       │   │   ├── create_quantity_adjustments.rb
│   │   │       │   │   └── free_shipping.rb
│   │   │       │   └── rules
│   │   │       │       ├── first_order.rb
│   │   │       │       ├── first_repeat_purchase_since.rb
│   │   │       │       ├── item_total.rb
│   │   │       │       ├── nth_order.rb
│   │   │       │       ├── one_use_per_user.rb
│   │   │       │       ├── option_value.rb
│   │   │       │       ├── product.rb
│   │   │       │       ├── store.rb
│   │   │       │       ├── taxon.rb
│   │   │       │       ├── user_logged_in.rb
│   │   │       │       ├── user.rb
│   │   │       │       └── user_role.rb
│   │   │       ├── promotion_action.rb
│   │   │       ├── promotion_category.rb
│   │   │       ├── promotion_chooser.rb
│   │   │       ├── promotion_code
│   │   │       │   └── batch_builder.rb
│   │   │       ├── promotion_code_batch.rb
│   │   │       ├── promotion_code.rb
│   │   │       ├── promotion_handler
│   │   │       │   ├── cart.rb
│   │   │       │   ├── coupon.rb
│   │   │       │   ├── free_shipping.rb
│   │   │       │   ├── page.rb
│   │   │       │   └── shipping.rb
│   │   │       ├── promotion.rb
│   │   │       ├── promotion_rule.rb
│   │   │       ├── promotion_rule_role.rb
│   │   │       ├── promotion_rule_store.rb
│   │   │       ├── promotion_rule_taxon.rb
│   │   │       ├── promotion_rule_user.rb
│   │   │       ├── property.rb
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
│   │   │       ├── return_reason.rb
│   │   │       ├── returns_calculator.rb
│   │   │       ├── role.rb
│   │   │       ├── role_user.rb
│   │   │       ├── shipment.rb
│   │   │       ├── shipping_calculator.rb
│   │   │       ├── shipping_category.rb
│   │   │       ├── shipping_manifest.rb
│   │   │       ├── shipping_method_category.rb
│   │   │       ├── shipping_method.rb
│   │   │       ├── shipping_method_stock_location.rb
│   │   │       ├── shipping_method_zone.rb
│   │   │       ├── shipping_rate.rb
│   │   │       ├── shipping_rate_tax.rb
│   │   │       ├── state_change.rb
│   │   │       ├── state.rb
│   │   │       ├── stock
│   │   │       │   ├── allocator
│   │   │       │   │   ├── base.rb
│   │   │       │   │   └── on_hand_first.rb
│   │   │       │   ├── availability.rb
│   │   │       │   ├── availability_validator.rb
│   │   │       │   ├── content_item.rb
│   │   │       │   ├── differentiator.rb
│   │   │       │   ├── estimator.rb
│   │   │       │   ├── inventory_unit_builder.rb
│   │   │       │   ├── inventory_units_finalizer.rb
│   │   │       │   ├── inventory_validator.rb
│   │   │       │   ├── location_filter
│   │   │       │   │   ├── active.rb
│   │   │       │   │   └── base.rb
│   │   │       │   ├── location_sorter
│   │   │       │   │   ├── base.rb
│   │   │       │   │   ├── default_first.rb
│   │   │       │   │   └── unsorted.rb
│   │   │       │   ├── package.rb
│   │   │       │   ├── quantifier.rb
│   │   │       │   ├── shipping_rate_selector.rb
│   │   │       │   ├── shipping_rate_sorter.rb
│   │   │       │   ├── simple_coordinator.rb
│   │   │       │   ├── splitter
│   │   │       │   │   ├── backordered.rb
│   │   │       │   │   ├── base.rb
│   │   │       │   │   ├── shipping_category.rb
│   │   │       │   │   └── weight.rb
│   │   │       │   └── splitter_chain.rb
│   │   │       ├── stock_item.rb
│   │   │       ├── stock_location.rb
│   │   │       ├── stock_movement.rb
│   │   │       ├── stock_quantities.rb
│   │   │       ├── store_credit_category.rb
│   │   │       ├── store_credit_event.rb
│   │   │       ├── store_credit.rb
│   │   │       ├── store_credit_reason.rb
│   │   │       ├── store_credit_type.rb
│   │   │       ├── store_payment_method.rb
│   │   │       ├── store.rb
│   │   │       ├── store_selector
│   │   │       │   ├── by_server_name.rb
│   │   │       │   └── legacy.rb
│   │   │       ├── store_shipping_method.rb
│   │   │       ├── tax
│   │   │       │   ├── item_tax.rb
│   │   │       │   ├── order_adjuster.rb
│   │   │       │   ├── order_tax.rb
│   │   │       │   ├── shipping_rate_taxer.rb
│   │   │       │   ├── tax_helpers.rb
│   │   │       │   └── tax_location.rb
│   │   │       ├── tax_calculator
│   │   │       │   ├── default.rb
│   │   │       │   └── shipping_rate.rb
│   │   │       ├── tax_category.rb
│   │   │       ├── taxonomy.rb
│   │   │       ├── taxon.rb
│   │   │       ├── tax_rate.rb
│   │   │       ├── tax_rate_tax_category.rb
│   │   │       ├── unit_cancel.rb
│   │   │       ├── user_address.rb
│   │   │       ├── user_class_handle.rb
│   │   │       ├── user_stock_location.rb
│   │   │       ├── validations
│   │   │       │   └── db_maximum_length_validator.rb
│   │   │       ├── variant
│   │   │       │   ├── price_selector.rb
│   │   │       │   ├── pricing_options.rb
│   │   │       │   ├── scopes.rb
│   │   │       │   └── vat_price_generator.rb
│   │   │       ├── variant_property_rule_condition.rb
│   │   │       ├── variant_property_rule.rb
│   │   │       ├── variant_property_rule_value.rb
│   │   │       ├── variant.rb
│   │   │       ├── wallet
│   │   │       │   ├── add_payment_sources_to_wallet.rb
│   │   │       │   └── default_payment_builder.rb
│   │   │       ├── wallet_payment_source.rb
│   │   │       ├── wallet.rb
│   │   │       ├── zone_member.rb
│   │   │       └── zone.rb
│   │   └── views
│   │       ├── layouts
│   │       │   └── spree
│   │       │       └── base_mailer.html.erb
│   │       └── spree
│   │           ├── carton_mailer
│   │           │   ├── shipped_email.html.erb
│   │           │   └── shipped_email.text.erb
│   │           ├── order_mailer
│   │           │   ├── cancel_email.html.erb
│   │           │   ├── cancel_email.text.erb
│   │           │   ├── confirm_email.html.erb
│   │           │   ├── confirm_email.text.erb
│   │           │   ├── inventory_cancellation_email.html.erb
│   │           │   └── inventory_cancellation_email.text.erb
│   │           ├── promotion_code_batch_mailer
│   │           │   ├── promotion_code_batch_errored.text.erb
│   │           │   └── promotion_code_batch_finished.text.erb
│   │           ├── reimbursement_mailer
│   │           │   ├── reimbursement_email.html.erb
│   │           │   └── reimbursement_email.text.erb
│   │           ├── shared
│   │           │   ├── _base_mailer_footer.html.erb
│   │           │   ├── _base_mailer_header.html.erb
│   │           │   └── _error_messages.html.erb
│   │           └── test_mailer
│   │               ├── test_email.html.erb
│   │               └── test_email.text.erb
│   ├── config
│   │   ├── initializers
│   │   │   ├── assets.rb
│   │   │   ├── friendly_id.rb
│   │   │   └── money.rb
│   │   └── locales
│   │       └── en.yml
│   ├── db
│   │   ├── default
│   │   │   └── spree
│   │   │       ├── countries.rb
│   │   │       ├── refund_reasons.rb
│   │   │       ├── return_reasons.rb
│   │   │       ├── roles.rb
│   │   │       ├── shipping_categories.rb
│   │   │       ├── states.rb
│   │   │       ├── stock_locations.rb
│   │   │       ├── store_credit.rb
│   │   │       ├── stores.rb
│   │   │       └── zones.rb
│   │   ├── migrate
│   │   │   ├── 20160101010000_solidus_one_four.rb
│   │   │   ├── 20160420044191_create_spree_wallet_payment_sources.rb
│   │   │   ├── 20160420181916_migrate_credit_cards_to_wallet_payment_sources.rb
│   │   │   ├── 20160924135758_remove_is_default_from_prices.rb
│   │   │   ├── 20161009141333_remove_currency_from_line_items.rb
│   │   │   ├── 20161014221052_add_available_to_columns_and_remove_display_on_from_payment_methods.rb
│   │   │   ├── 20161017102621_create_spree_promotion_code_batch.rb
│   │   │   ├── 20161123154034_add_available_to_users_and_remove_display_on_from_shipping_methods.rb
│   │   │   ├── 20161129035810_add_index_to_spree_payments_number.rb
│   │   │   ├── 20170223235001_remove_spree_store_credits_column.rb
│   │   │   ├── 20170317035819_add_lft_and_rgt_indexes_to_taxons.rb
│   │   │   ├── 20170319191942_remove_order_id_from_inventory_units.rb
│   │   │   ├── 20170412103617_transform_tax_rate_category_relation.rb
│   │   │   ├── 20170422134804_add_roles_unique_constraints.rb
│   │   │   ├── 20170522143442_add_time_range_to_tax_rate.rb
│   │   │   ├── 20170608074534_rename_bogus_gateways.rb
│   │   │   ├── 20170831201542_remove_default_tax_from_spree_zones.rb
│   │   │   ├── 20180202190713_create_promotion_rule_stores.rb
│   │   │   ├── 20180202222641_create_store_shipping_methods.rb
│   │   │   ├── 20180313220213_add_available_locales_to_stores.rb
│   │   │   ├── 20180322142651_add_amount_remaining_to_store_credit_events.rb
│   │   │   ├── 20180328172631_add_join_characters_to_promotion_code_batch.rb
│   │   │   ├── 20180710170104_create_spree_store_credit_reasons_table.rb
│   │   │   ├── 20190106184413_remove_code_from_spree_promotions.rb
│   │   │   └── 20190220093635_drop_spree_store_credit_update_reasons.rb
│   │   └── seeds.rb
│   ├── lib
│   │   ├── generators
│   │   │   └── spree
│   │   │       ├── custom_user
│   │   │       │   ├── custom_user_generator.rb
│   │   │       │   └── templates
│   │   │       │       ├── authentication_helpers.rb.tt
│   │   │       │       └── migration.rb.tt
│   │   │       ├── dummy
│   │   │       │   ├── dummy_generator.rb
│   │   │       │   └── templates
│   │   │       │       └── rails
│   │   │       │           ├── application.rb.tt
│   │   │       │           ├── boot.rb
│   │   │       │           ├── database.yml
│   │   │       │           ├── routes.rb
│   │   │       │           ├── script
│   │   │       │           │   └── rails
│   │   │       │           └── test.rb
│   │   │       └── install
│   │   │           ├── install_generator.rb
│   │   │           └── templates
│   │   │               ├── config
│   │   │               │   └── initializers
│   │   │               │       └── spree.rb.tt
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
│   │   ├── solidus
│   │   │   └── migrations
│   │   │       ├── promotions_with_code_handlers.rb
│   │   │       └── rename_gateways.rb
│   │   ├── solidus_core.rb
│   │   ├── spree
│   │   │   ├── app_configuration.rb
│   │   │   ├── config.rb
│   │   │   ├── core
│   │   │   │   ├── active_merchant_dependencies.rb
│   │   │   │   ├── class_constantizer.rb
│   │   │   │   ├── controller_helpers
│   │   │   │   │   ├── auth.rb
│   │   │   │   │   ├── common.rb
│   │   │   │   │   ├── order.rb
│   │   │   │   │   ├── payment_parameters.rb
│   │   │   │   │   ├── pricing.rb
│   │   │   │   │   ├── search.rb
│   │   │   │   │   ├── store.rb
│   │   │   │   │   └── strong_parameters.rb
│   │   │   │   ├── current_store.rb
│   │   │   │   ├── engine.rb
│   │   │   │   ├── environment
│   │   │   │   │   └── calculators.rb
│   │   │   │   ├── environment_extension.rb
│   │   │   │   ├── environment.rb
│   │   │   │   ├── importer
│   │   │   │   │   ├── order.rb
│   │   │   │   │   └── product.rb
│   │   │   │   ├── importer.rb
│   │   │   │   ├── permalinks.rb
│   │   │   │   ├── product_duplicator.rb
│   │   │   │   ├── product_filters.rb
│   │   │   │   ├── role_configuration.rb
│   │   │   │   ├── search
│   │   │   │   │   ├── base.rb
│   │   │   │   │   └── variant.rb
│   │   │   │   ├── stock_configuration.rb
│   │   │   │   ├── validators
│   │   │   │   │   └── email.rb
│   │   │   │   └── version.rb
│   │   │   ├── core.rb
│   │   │   ├── deprecation.rb
│   │   │   ├── event
│   │   │   │   ├── adapters
│   │   │   │   │   └── active_support_notifications.rb
│   │   │   │   ├── configuration.rb
│   │   │   │   ├── processors
│   │   │   │   │   └── mailer_processor.rb
│   │   │   │   └── subscriber.rb
│   │   │   ├── event.rb
│   │   │   ├── i18n.rb
│   │   │   ├── localized_number.rb
│   │   │   ├── mailer_previews
│   │   │   │   ├── carton_preview.rb
│   │   │   │   ├── order_preview.rb
│   │   │   │   └── reimbursement_preview.rb
│   │   │   ├── migration_helpers.rb
│   │   │   ├── migrations.rb
│   │   │   ├── money.rb
│   │   │   ├── paranoia_deprecations.rb
│   │   │   ├── permission_sets
│   │   │   │   ├── base.rb
│   │   │   │   ├── configuration_display.rb
│   │   │   │   ├── configuration_management.rb
│   │   │   │   ├── dashboard_display.rb
│   │   │   │   ├── default_customer.rb
│   │   │   │   ├── order_display.rb
│   │   │   │   ├── order_management.rb
│   │   │   │   ├── product_display.rb
│   │   │   │   ├── product_management.rb
│   │   │   │   ├── promotion_display.rb
│   │   │   │   ├── promotion_management.rb
│   │   │   │   ├── restricted_stock_display.rb
│   │   │   │   ├── restricted_stock_management.rb
│   │   │   │   ├── stock_display.rb
│   │   │   │   ├── stock_management.rb
│   │   │   │   ├── super_user.rb
│   │   │   │   ├── user_display.rb
│   │   │   │   └── user_management.rb
│   │   │   ├── permission_sets.rb
│   │   │   ├── permitted_attributes.rb
│   │   │   ├── preferences
│   │   │   │   ├── configuration.rb
│   │   │   │   ├── preferable_class_methods.rb
│   │   │   │   ├── preferable.rb
│   │   │   │   ├── scoped_store.rb
│   │   │   │   ├── statically_configurable.rb
│   │   │   │   ├── static_model_preferences.rb
│   │   │   │   └── store.rb
│   │   │   ├── promo
│   │   │   │   └── environment.rb
│   │   │   └── testing_support
│   │   │       ├── ability_helpers.rb
│   │   │       ├── authorization_helpers.rb
│   │   │       ├── bar_ability.rb
│   │   │       ├── caching.rb
│   │   │       ├── capybara_ext.rb
│   │   │       ├── common_rake.rb
│   │   │       ├── controller_requests.rb
│   │   │       ├── dummy_app
│   │   │       │   ├── assets
│   │   │       │   │   ├── javascripts
│   │   │       │   │   │   └── spree
│   │   │       │   │   │       ├── backend
│   │   │       │   │   │       │   └── all.js
│   │   │       │   │   │       └── frontend
│   │   │       │   │   │           └── all.js
│   │   │       │   │   └── stylesheets
│   │   │       │   │       └── spree
│   │   │       │   │           ├── backend
│   │   │       │   │           │   └── all.css
│   │   │       │   │           └── frontend
│   │   │       │   │               └── all.css
│   │   │       │   ├── database.yml
│   │   │       │   ├── migrations.rb
│   │   │       │   ├── rake_tasks.rb
│   │   │       │   ├── routes.rb
│   │   │       │   └── views
│   │   │       │       └── layouts
│   │   │       │           └── application.html.erb
│   │   │       ├── dummy_app.rb
│   │   │       ├── extension_rake.rb
│   │   │       ├── factories
│   │   │       │   ├── address_factory.rb
│   │   │       │   ├── adjustment_factory.rb
│   │   │       │   ├── adjustment_reason_factory.rb
│   │   │       │   ├── calculator_factory.rb
│   │   │       │   ├── carton_factory.rb
│   │   │       │   ├── country_factory.rb
│   │   │       │   ├── credit_card_factory.rb
│   │   │       │   ├── customer_return_factory.rb
│   │   │       │   ├── image_factory.rb
│   │   │       │   ├── inventory_unit_factory.rb
│   │   │       │   ├── line_item_factory.rb
│   │   │       │   ├── option_type_factory.rb
│   │   │       │   ├── option_value_factory.rb
│   │   │       │   ├── order_factory.rb
│   │   │       │   ├── order_promotion_factory.rb
│   │   │       │   ├── payment_factory.rb
│   │   │       │   ├── payment_method_factory.rb
│   │   │       │   ├── price_factory.rb
│   │   │       │   ├── product_factory.rb
│   │   │       │   ├── product_option_type_factory.rb
│   │   │       │   ├── product_property_factory.rb
│   │   │       │   ├── promotion_category_factory.rb
│   │   │       │   ├── promotion_code_factory.rb
│   │   │       │   ├── promotion_factory.rb
│   │   │       │   ├── property_factory.rb
│   │   │       │   ├── refund_factory.rb
│   │   │       │   ├── refund_reason_factory.rb
│   │   │       │   ├── reimbursement_factory.rb
│   │   │       │   ├── reimbursement_type_factory.rb
│   │   │       │   ├── return_authorization_factory.rb
│   │   │       │   ├── return_item_factory.rb
│   │   │       │   ├── return_reason_factory.rb
│   │   │       │   ├── role_factory.rb
│   │   │       │   ├── shipment_factory.rb
│   │   │       │   ├── shipping_category_factory.rb
│   │   │       │   ├── shipping_method_factory.rb
│   │   │       │   ├── shipping_rate_factory.rb
│   │   │       │   ├── state_factory.rb
│   │   │       │   ├── stock_item_factory.rb
│   │   │       │   ├── stock_location_factory.rb
│   │   │       │   ├── stock_movement_factory.rb
│   │   │       │   ├── stock_package_factory.rb
│   │   │       │   ├── store_credit_category_factory.rb
│   │   │       │   ├── store_credit_event_factory.rb
│   │   │       │   ├── store_credit_factory.rb
│   │   │       │   ├── store_credit_reason_factory.rb
│   │   │       │   ├── store_credit_type_factory.rb
│   │   │       │   ├── store_factory.rb
│   │   │       │   ├── tax_category_factory.rb
│   │   │       │   ├── taxon_factory.rb
│   │   │       │   ├── taxonomy_factory.rb
│   │   │       │   ├── tax_rate_factory.rb
│   │   │       │   ├── user_factory.rb
│   │   │       │   ├── variant_factory.rb
│   │   │       │   ├── variant_property_rule_condition_factory.rb
│   │   │       │   ├── variant_property_rule_factory.rb
│   │   │       │   ├── variant_property_rule_value_factory.rb
│   │   │       │   └── zone_factory.rb
│   │   │       ├── factories.rb
│   │   │       ├── flash.rb
│   │   │       ├── order_walkthrough.rb
│   │   │       ├── partial_double_verification.rb
│   │   │       ├── preferences.rb
│   │   │       ├── sequences.rb
│   │   │       ├── shared_examples
│   │   │       │   └── gallery.rb
│   │   │       └── url_helpers.rb
│   │   ├── spree_core.rb
│   │   └── tasks
│   │       ├── core.rake
│   │       ├── email.rake
│   │       ├── migrations
│   │       │   ├── copy_order_bill_address_to_credit_card.rake
│   │       │   ├── migrate_shipping_rate_taxes.rake
│   │       │   ├── migrate_user_addresses.rake
│   │       │   └── rename_gateways.rake
│   │       └── order_capturing.rake
│   ├── LICENSE
│   ├── Rakefile
│   ├── README.md
│   ├── script
│   │   └── rails
│   ├── solidus_core.gemspec
│   ├── spec
│   │   ├── fixtures
│   │   │   └── thinking-cat.jpg
│   │   ├── helpers
│   │   │   ├── base_helper_spec.rb
│   │   │   ├── products_helper_spec.rb
│   │   │   └── taxons_helper_spec.rb
│   │   ├── jobs
│   │   │   └── promotion_code_batch_job_spec.rb
│   │   ├── lib
│   │   │   ├── calculated_adjustments_spec.rb
│   │   │   ├── i18n_spec.rb
│   │   │   ├── search
│   │   │   │   ├── base_spec.rb
│   │   │   │   └── variant_spec.rb
│   │   │   ├── spree
│   │   │   │   ├── core
│   │   │   │   │   ├── class_constantizer_spec.rb
│   │   │   │   │   ├── controller_helpers
│   │   │   │   │   │   ├── auth_spec.rb
│   │   │   │   │   │   ├── order_spec.rb
│   │   │   │   │   │   ├── payment_parameters_spec.rb
│   │   │   │   │   │   ├── pricing_spec.rb
│   │   │   │   │   │   ├── search_spec.rb
│   │   │   │   │   │   ├── store_spec.rb
│   │   │   │   │   │   └── strong_parameters_spec.rb
│   │   │   │   │   ├── current_store_spec.rb
│   │   │   │   │   ├── environment_extension_spec.rb
│   │   │   │   │   ├── importer
│   │   │   │   │   │   └── order_spec.rb
│   │   │   │   │   ├── role_configuration_spec.rb
│   │   │   │   │   ├── stock_configuration_spec.rb
│   │   │   │   │   ├── testing_support
│   │   │   │   │   │   ├── factories
│   │   │   │   │   │   │   ├── address_factory_spec.rb
│   │   │   │   │   │   │   ├── adjustment_factory_spec.rb
│   │   │   │   │   │   │   ├── adjustment_reason_factory_spec.rb
│   │   │   │   │   │   │   ├── calculator_factory_spec.rb
│   │   │   │   │   │   │   ├── carton_factory_spec.rb
│   │   │   │   │   │   │   ├── country_factory_spec.rb
│   │   │   │   │   │   │   ├── credit_card_factory_spec.rb
│   │   │   │   │   │   │   ├── customer_return_factory_spec.rb
│   │   │   │   │   │   │   ├── image_factory_spec.rb
│   │   │   │   │   │   │   ├── inventory_unit_factory_spec.rb
│   │   │   │   │   │   │   ├── line_item_factory_spec.rb
│   │   │   │   │   │   │   ├── option_type_factory_spec.rb
│   │   │   │   │   │   │   ├── option_value_factory_spec.rb
│   │   │   │   │   │   │   ├── order_factory_spec.rb
│   │   │   │   │   │   │   ├── order_promotion_factory_spec.rb
│   │   │   │   │   │   │   ├── payment_factory_spec.rb
│   │   │   │   │   │   │   ├── payment_method_factory_spec.rb
│   │   │   │   │   │   │   ├── price_factory_spec.rb
│   │   │   │   │   │   │   ├── product_factory_spec.rb
│   │   │   │   │   │   │   ├── product_option_type_factory_spec.rb
│   │   │   │   │   │   │   ├── product_property_factory_spec.rb
│   │   │   │   │   │   │   ├── promotion_category_factory_spec.rb
│   │   │   │   │   │   │   ├── promotion_code_factory_spec.rb
│   │   │   │   │   │   │   ├── promotion_factory_spec.rb
│   │   │   │   │   │   │   ├── property_factory_spec.rb
│   │   │   │   │   │   │   ├── refund_factory_spec.rb
│   │   │   │   │   │   │   ├── refund_reason_factory_spec.rb
│   │   │   │   │   │   │   ├── reimbursement_factory_spec.rb
│   │   │   │   │   │   │   ├── reimbursement_type_factory_spec.rb
│   │   │   │   │   │   │   ├── return_authorization_factory_spec.rb
│   │   │   │   │   │   │   ├── return_item_factory_spec.rb
│   │   │   │   │   │   │   ├── return_reason_factory_spec.rb
│   │   │   │   │   │   │   ├── role_factory_spec.rb
│   │   │   │   │   │   │   ├── shipment_factory_spec.rb
│   │   │   │   │   │   │   ├── shipping_category_factory_spec.rb
│   │   │   │   │   │   │   ├── shipping_method_factory_spec.rb
│   │   │   │   │   │   │   ├── shipping_rate_factory_spec.rb
│   │   │   │   │   │   │   ├── state_factory_spec.rb
│   │   │   │   │   │   │   ├── stock_item_factory_spec.rb
│   │   │   │   │   │   │   ├── stock_location_factory_spec.rb
│   │   │   │   │   │   │   ├── stock_movement_factory_spec.rb
│   │   │   │   │   │   │   ├── stock_package_factory_spec.rb
│   │   │   │   │   │   │   ├── store_credit_category_factory_spec.rb
│   │   │   │   │   │   │   ├── store_credit_event_factory_spec.rb
│   │   │   │   │   │   │   ├── store_credit_factory_spec.rb
│   │   │   │   │   │   │   ├── store_credit_reason_factory_spec.rb
│   │   │   │   │   │   │   ├── store_credit_type_factory_spec.rb
│   │   │   │   │   │   │   ├── store_factory_spec.rb
│   │   │   │   │   │   │   ├── tax_category_factory_spec.rb
│   │   │   │   │   │   │   ├── taxon_factory_spec.rb
│   │   │   │   │   │   │   ├── taxonomy_factory_spec.rb
│   │   │   │   │   │   │   ├── tax_rate_factory_spec.rb
│   │   │   │   │   │   │   ├── user_factory_spec.rb
│   │   │   │   │   │   │   ├── variant_factory_spec.rb
│   │   │   │   │   │   │   ├── variant_property_rule_condition_factory_spec.rb
│   │   │   │   │   │   │   ├── variant_property_rule_factory_spec.rb
│   │   │   │   │   │   │   ├── variant_property_rule_value_factory_spec.rb
│   │   │   │   │   │   │   └── zone_factory_spec.rb
│   │   │   │   │   │   └── preferences_spec.rb
│   │   │   │   │   ├── validators
│   │   │   │   │   │   └── email_spec.rb
│   │   │   │   │   └── version_spec.rb
│   │   │   │   ├── event
│   │   │   │   │   └── subscriber_spec.rb
│   │   │   │   ├── event_spec.rb
│   │   │   │   ├── localized_number_spec.rb
│   │   │   │   ├── migrations_spec.rb
│   │   │   │   ├── money_spec.rb
│   │   │   │   └── permission_sets
│   │   │   │       └── default_customer_spec.rb
│   │   │   └── tasks
│   │   │       ├── dummy_task.rake
│   │   │       ├── dummy_task_spec.rb
│   │   │       └── migrations
│   │   │           └── migrate_shipping_rate_taxes_spec.rb
│   │   ├── mailers
│   │   │   ├── carton_mailer_spec.rb
│   │   │   ├── order_mailer_spec.rb
│   │   │   ├── promotion_code_batch_mailer_spec.rb
│   │   │   ├── reimbursement_mailer_spec.rb
│   │   │   └── test_mailer_spec.rb
│   │   ├── migrate
│   │   │   └── 20190106184413_remove_code_from_spree_promotions_spec.rb
│   │   ├── models
│   │   │   └── spree
│   │   │       ├── ability_spec.rb
│   │   │       ├── address_spec.rb
│   │   │       ├── adjustment_reason_spec.rb
│   │   │       ├── adjustment_spec.rb
│   │   │       ├── app_configuration_spec.rb
│   │   │       ├── asset_spec.rb
│   │   │       ├── calculator
│   │   │       │   ├── default_tax_spec.rb
│   │   │       │   ├── distributed_amount_spec.rb
│   │   │       │   ├── flat_percent_item_total_spec.rb
│   │   │       │   ├── flat_rate_spec.rb
│   │   │       │   ├── flexi_rate_spec.rb
│   │   │       │   ├── free_shipping_spec.rb
│   │   │       │   ├── percent_on_line_item_spec.rb
│   │   │       │   ├── percent_per_item_spec.rb
│   │   │       │   ├── price_sack_spec.rb
│   │   │       │   ├── refunds
│   │   │       │   │   └── default_refund_amount_spec.rb
│   │   │       │   ├── shipping
│   │   │       │   │   ├── flat_percent_item_total_spec.rb
│   │   │       │   │   ├── flat_rate_spec.rb
│   │   │       │   │   ├── flexi_rate_spec.rb
│   │   │       │   │   ├── per_item_spec.rb
│   │   │       │   │   └── price_sack_spec.rb
│   │   │       │   ├── tiered_flat_rate_spec.rb
│   │   │       │   └── tiered_percent_spec.rb
│   │   │       ├── calculator_spec.rb
│   │   │       ├── carton_spec.rb
│   │   │       ├── classification_spec.rb
│   │   │       ├── concerns
│   │   │       │   ├── display_money_spec.rb
│   │   │       │   ├── ordered_property_value_list_spec.rb
│   │   │       │   ├── user_address_book_spec.rb
│   │   │       │   └── user_methods_spec.rb
│   │   │       ├── country_spec.rb
│   │   │       ├── credit_card_spec.rb
│   │   │       ├── customer_return_spec.rb
│   │   │       ├── distributed_amounts_handler_spec.rb
│   │   │       ├── exchange_spec.rb
│   │   │       ├── fulfilment_changer_spec.rb
│   │   │       ├── gallery
│   │   │       │   ├── product_gallery_spec.rb
│   │   │       │   └── variant_gallery_spec.rb
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
│   │   │       │   ├── finalizing_spec.rb
│   │   │       │   ├── number_generator_spec.rb
│   │   │       │   ├── outstanding_balance_integration_spec.rb
│   │   │       │   ├── payment_spec.rb
│   │   │       │   ├── risk_assessment_spec.rb
│   │   │       │   ├── state_machine_spec.rb
│   │   │       │   ├── totals_spec.rb
│   │   │       │   ├── updating_spec.rb
│   │   │       │   └── validations_spec.rb
│   │   │       ├── order_cancellations_spec.rb
│   │   │       ├── order_capturing_spec.rb
│   │   │       ├── order_contents_spec.rb
│   │   │       ├── order_inventory_spec.rb
│   │   │       ├── order_merger_spec.rb
│   │   │       ├── order_mutex_spec.rb
│   │   │       ├── order_promotion_spec.rb
│   │   │       ├── order_shipping_spec.rb
│   │   │       ├── order_spec.rb
│   │   │       ├── order_taxation_spec.rb
│   │   │       ├── order_update_attributes_spec.rb
│   │   │       ├── order_updater_spec.rb
│   │   │       ├── payment
│   │   │       │   └── cancellation_spec.rb
│   │   │       ├── payment_create_spec.rb
│   │   │       ├── payment_method
│   │   │       │   ├── bogus_credit_card_spec.rb
│   │   │       │   ├── check_spec.rb
│   │   │       │   ├── credit_card_spec.rb
│   │   │       │   ├── simple_bogus_credit_card_spec.rb
│   │   │       │   └── store_credit_spec.rb
│   │   │       ├── payment_method_spec.rb
│   │   │       ├── payment_spec.rb
│   │   │       ├── permission_sets
│   │   │       │   ├── base_spec.rb
│   │   │       │   ├── configuration_display.rb
│   │   │       │   ├── configuration_management_spec.rb
│   │   │       │   ├── dashboard_display_spec.rb
│   │   │       │   ├── order_display_spec.rb
│   │   │       │   ├── order_management_spec.rb
│   │   │       │   ├── product_display_spec.rb
│   │   │       │   ├── product_management_spec.rb
│   │   │       │   ├── promotion_display_spec.rb
│   │   │       │   ├── promotion_management_spec.rb
│   │   │       │   ├── restricted_stock_display_spec.rb
│   │   │       │   ├── restricted_stock_management_spec.rb
│   │   │       │   ├── stock_display_spec.rb
│   │   │       │   ├── stock_management_spec.rb
│   │   │       │   ├── user_display_spec.rb
│   │   │       │   └── user_management_spec.rb
│   │   │       ├── preferences
│   │   │       │   ├── configuration_spec.rb
│   │   │       │   ├── preferable_spec.rb
│   │   │       │   ├── scoped_store_spec.rb
│   │   │       │   ├── statically_configurable_spec.rb
│   │   │       │   ├── static_model_preferences_spec.rb
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
│   │   │       │   │   ├── create_quantity_adjustments_spec.rb
│   │   │       │   │   └── free_shipping_spec.rb
│   │   │       │   └── rules
│   │   │       │       ├── first_order_spec.rb
│   │   │       │       ├── first_repeat_purchase_since_spec.rb
│   │   │       │       ├── item_total_spec.rb
│   │   │       │       ├── nth_order_spec.rb
│   │   │       │       ├── one_use_per_user_spec.rb
│   │   │       │       ├── option_value_spec.rb
│   │   │       │       ├── product_spec.rb
│   │   │       │       ├── store_spec.rb
│   │   │       │       ├── taxon_spec.rb
│   │   │       │       ├── user_logged_in_spec.rb
│   │   │       │       ├── user_role_spec.rb
│   │   │       │       └── user_spec.rb
│   │   │       ├── promotion_action_spec.rb
│   │   │       ├── promotion_category_spec.rb
│   │   │       ├── promotion_code
│   │   │       │   └── batch_builder_spec.rb
│   │   │       ├── promotion_code_batch_spec.rb
│   │   │       ├── promotion_code_spec.rb
│   │   │       ├── promotion_handler
│   │   │       │   ├── cart_spec.rb
│   │   │       │   ├── coupon_spec.rb
│   │   │       │   ├── page_spec.rb
│   │   │       │   └── shipping_spec.rb
│   │   │       ├── promotion_rule_spec.rb
│   │   │       ├── promotion_spec.rb
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
│   │   │       ├── shipping_manifest_spec.rb
│   │   │       ├── shipping_method_spec.rb
│   │   │       ├── shipping_rate_spec.rb
│   │   │       ├── shipping_rate_tax_spec.rb
│   │   │       ├── state_spec.rb
│   │   │       ├── stock
│   │   │       │   ├── allocator
│   │   │       │   │   └── on_hand_first_spec.rb
│   │   │       │   ├── availability_spec.rb
│   │   │       │   ├── availability_validator_spec.rb
│   │   │       │   ├── content_item_spec.rb
│   │   │       │   ├── differentiator_spec.rb
│   │   │       │   ├── estimator_spec.rb
│   │   │       │   ├── inventory_unit_builder_spec.rb
│   │   │       │   ├── inventory_units_finalizer_spec.rb
│   │   │       │   ├── location_filter
│   │   │       │   │   └── active_spec.rb
│   │   │       │   ├── location_sorter
│   │   │       │   │   ├── default_first_spec.rb
│   │   │       │   │   └── unsorted_spec.rb
│   │   │       │   ├── package_spec.rb
│   │   │       │   ├── quantifier_spec.rb
│   │   │       │   ├── shipping_rate_selector_spec.rb
│   │   │       │   ├── shipping_rate_sorter_spec.rb
│   │   │       │   ├── simple_coordinator_spec.rb
│   │   │       │   ├── splitter
│   │   │       │   │   ├── backordered_spec.rb
│   │   │       │   │   ├── base_spec.rb
│   │   │       │   │   ├── shipping_category_spec.rb
│   │   │       │   │   └── weight_spec.rb
│   │   │       │   └── splitter_chain_spec.rb
│   │   │       ├── stock_item_spec.rb
│   │   │       ├── stock_location_spec.rb
│   │   │       ├── stock_movement_spec.rb
│   │   │       ├── stock_quantities_spec.rb
│   │   │       ├── store_credit_category_spec.rb
│   │   │       ├── store_credit_event_spec.rb
│   │   │       ├── store_credit_spec.rb
│   │   │       ├── store_selector
│   │   │       │   ├── by_server_name_spec.rb
│   │   │       │   └── legacy_spec.rb
│   │   │       ├── store_spec.rb
│   │   │       ├── tax
│   │   │       │   ├── order_adjuster_spec.rb
│   │   │       │   ├── shipping_rate_taxer_spec.rb
│   │   │       │   ├── taxation_integration_spec.rb
│   │   │       │   └── tax_location_spec.rb
│   │   │       ├── tax_calculator
│   │   │       │   └── default_spec.rb
│   │   │       ├── tax_category_spec.rb
│   │   │       ├── taxonomy_spec.rb
│   │   │       ├── taxon_spec.rb
│   │   │       ├── tax_rate_spec.rb
│   │   │       ├── unit_cancel_spec.rb
│   │   │       ├── user_spec.rb
│   │   │       ├── validations
│   │   │       │   └── db_maximum_length_validator_spec.rb
│   │   │       ├── variant
│   │   │       │   ├── price_selector_spec.rb
│   │   │       │   ├── pricing_options_spec.rb
│   │   │       │   ├── scopes_spec.rb
│   │   │       │   └── vat_price_generator_spec.rb
│   │   │       ├── variant_property_rule_condition_spec.rb
│   │   │       ├── variant_property_rule_spec.rb
│   │   │       ├── variant_property_rule_value_spec.rb
│   │   │       ├── variant_spec.rb
│   │   │       ├── wallet_payment_source_spec.rb
│   │   │       ├── wallet_spec.rb
│   │   │       └── zone_spec.rb
│   │   ├── rails_helper.rb
│   │   ├── shared_examples
│   │   │   └── calculator_shared_examples.rb
│   │   ├── spec_helper.rb
│   │   └── support
│   │       ├── big_decimal.rb
│   │       ├── concerns
│   │       │   ├── default_price.rb
│   │       │   ├── payment_source.rb
│   │       │   └── working_factories.rb
│   │       ├── dummy_ability.rb
│   │       └── shared_contexts
│   │           └── rake.rb
│   └── vendor
│       └── assets
│           ├── javascripts
│           │   ├── jquery.payment.js
│           │   └── jsuri.js
│           └── stylesheets
│               └── normalize.css
├── frontend
│   ├── app
│   │   ├── assets
│   │   │   ├── config
│   │   │   │   └── solidus_frontend_manifest.js
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
│   │   │   │   ├── icons
│   │   │   │   │   ├── add-to-cart.png
│   │   │   │   │   ├── checkout.png
│   │   │   │   │   ├── delete.png
│   │   │   │   │   └── update.png
│   │   │   │   ├── spinner.gif
│   │   │   │   └── spree
│   │   │   │       └── frontend
│   │   │   │           └── cart.png
│   │   │   ├── javascripts
│   │   │   │   └── spree
│   │   │   │       ├── frontend
│   │   │   │       │   ├── cart.js
│   │   │   │       │   ├── checkout
│   │   │   │       │   │   ├── address.js
│   │   │   │       │   │   ├── coupon-code.js
│   │   │   │       │   │   └── payment.js
│   │   │   │       │   ├── checkout.js
│   │   │   │       │   ├── locale_selector.js
│   │   │   │       │   └── product.js
│   │   │   │       └── frontend.js
│   │   │   └── stylesheets
│   │   │       └── spree
│   │   │           ├── frontend
│   │   │           │   ├── screen.css.scss
│   │   │           │   ├── _skeleton.scss
│   │   │           │   └── _variables.scss
│   │   │           └── frontend.css
│   │   ├── controllers
│   │   │   └── spree
│   │   │       ├── checkout_controller.rb
│   │   │       ├── content_controller.rb
│   │   │       ├── coupon_codes_controller.rb
│   │   │       ├── home_controller.rb
│   │   │       ├── locale_controller.rb
│   │   │       ├── orders_controller.rb
│   │   │       ├── products_controller.rb
│   │   │       ├── store_controller.rb
│   │   │       └── taxons_controller.rb
│   │   ├── helpers
│   │   │   └── spree
│   │   │       ├── orders_helper.rb
│   │   │       └── taxon_filters_helper.rb
│   │   ├── models
│   │   │   └── spree
│   │   │       └── frontend_configuration.rb
│   │   └── views
│   │       └── spree
│   │           ├── address
│   │           │   ├── _form_hidden.html.erb
│   │           │   └── _form.html.erb
│   │           ├── checkout
│   │           │   ├── _address.html.erb
│   │           │   ├── _confirm.html.erb
│   │           │   ├── _coupon_code.html.erb
│   │           │   ├── _delivery.html.erb
│   │           │   ├── edit.html.erb
│   │           │   ├── existing_payment
│   │           │   │   └── _gateway.html.erb
│   │           │   ├── payment
│   │           │   │   ├── _check.html.erb
│   │           │   │   └── _gateway.html.erb
│   │           │   ├── _payment.html.erb
│   │           │   ├── _summary.html.erb
│   │           │   └── _terms_and_conditions.en.html.erb
│   │           ├── content
│   │           │   └── cvv.html.erb
│   │           ├── coupon_codes
│   │           │   └── new.html.erb
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
│   │           ├── payments
│   │           │   └── _payment.html.erb
│   │           ├── products
│   │           │   ├── _cart_form.html.erb
│   │           │   ├── _image.html.erb
│   │           │   ├── index.html.erb
│   │           │   ├── _promotions.html.erb
│   │           │   ├── _properties.html.erb
│   │           │   ├── show.html.erb
│   │           │   ├── _taxons.html.erb
│   │           │   └── _thumbnails.html.erb
│   │           ├── shared
│   │           │   ├── _address.html.erb
│   │           │   ├── _filters.html.erb
│   │           │   ├── _footer.html.erb
│   │           │   ├── _header.html.erb
│   │           │   ├── _head.html.erb
│   │           │   ├── _image.html.erb
│   │           │   ├── _link_to_cart.html.erb
│   │           │   ├── _locale_selector.html.erb
│   │           │   ├── _login_bar_items.html.erb
│   │           │   ├── _main_nav_bar.html.erb
│   │           │   ├── _nav_bar.html.erb
│   │           │   ├── _order_details.html.erb
│   │           │   ├── _products.html.erb
│   │           │   ├── _search.html.erb
│   │           │   ├── _shipment_tracking.html.erb
│   │           │   ├── _sidebar.html.erb
│   │           │   ├── _taxonomies.html.erb
│   │           │   └── unauthorized.html.erb
│   │           ├── store
│   │           │   └── cart_link.html.erb
│   │           └── taxons
│   │               ├── show.html.erb
│   │               └── _taxon.html.erb
│   ├── config
│   │   ├── initializers
│   │   │   ├── assets.rb
│   │   │   └── canonical_rails.rb
│   │   └── routes.rb
│   ├── lib
│   │   ├── generators
│   │   │   └── solidus
│   │   │       └── views
│   │   │           └── override_generator.rb
│   │   ├── solidus_frontend.rb
│   │   ├── spree
│   │   │   ├── frontend
│   │   │   │   ├── engine.rb
│   │   │   │   └── middleware
│   │   │   │       └── seo_assist.rb
│   │   │   └── frontend.rb
│   │   ├── spree_frontend.rb
│   │   └── tasks
│   │       ├── rake_util.rb
│   │       └── taxon.rake
│   ├── LICENSE
│   ├── Rakefile
│   ├── README.md
│   ├── script
│   │   └── rails
│   ├── solidus_frontend.gemspec
│   └── spec
│       ├── controllers
│       │   ├── controller_helpers_spec.rb
│       │   ├── locale_controller_spec.rb
│       │   └── spree
│       │       ├── checkout_controller_spec.rb
│       │       ├── checkout_controller_with_views_spec.rb
│       │       ├── content_controller_spec.rb
│       │       ├── current_order_tracking_spec.rb
│       │       ├── home_controller_spec.rb
│       │       ├── orders_controller_ability_spec.rb
│       │       ├── orders_controller_spec.rb
│       │       ├── orders_controller_transitions_spec.rb
│       │       ├── products_controller_spec.rb
│       │       └── taxons_controller_spec.rb
│       ├── features
│       │   ├── address_spec.rb
│       │   ├── automatic_promotion_adjustments_spec.rb
│       │   ├── caching
│       │   │   ├── products_spec.rb
│       │   │   └── taxons_spec.rb
│       │   ├── cart_spec.rb
│       │   ├── checkout_confirm_insufficient_stock_spec.rb
│       │   ├── checkout_spec.rb
│       │   ├── checkout_unshippable_spec.rb
│       │   ├── coupon_code_spec.rb
│       │   ├── currency_spec.rb
│       │   ├── first_order_promotion_spec.rb
│       │   ├── free_shipping_promotions_spec.rb
│       │   ├── locale_spec.rb
│       │   ├── order_spec.rb
│       │   ├── products_spec.rb
│       │   ├── promotion_code_invalidation_spec.rb
│       │   ├── quantity_promotions_spec.rb
│       │   ├── taxons_spec.rb
│       │   └── template_rendering_spec.rb
│       ├── fixtures
│       │   └── thinking-cat.jpg
│       ├── generators
│       │   └── solidus
│       │       └── views
│       │           └── override_generator_spec.rb
│       ├── helpers
│       │   ├── base_helper_spec.rb
│       │   ├── order_helper_spec.rb
│       │   └── taxon_filters_helper_spec.rb
│       ├── spec_helper.rb
│       ├── support
│       │   └── shared_contexts
│       │       ├── checkout_setup.rb
│       │       ├── custom_products.rb
│       │       └── locales.rb
│       └── views
│           └── spree
│               └── checkout
│                   └── _summary_spec.rb
├── Gemfile
├── guides
│   ├── config.rb
│   ├── data
│   │   └── nav
│   │       ├── developers.yml
│   │       ├── global.yml
│   │       ├── meta.yml
│   │       └── users.yml
│   ├── Gemfile
│   ├── Gemfile.lock
│   ├── helpers
│   │   ├── image_helpers.rb
│   │   └── nav_helpers.rb
│   ├── lib
│   │   └── custom_markdown_renderer.rb
│   ├── package.json
│   ├── README.md
│   ├── source
│   │   ├── assets
│   │   │   ├── images
│   │   │   │   ├── close.svg
│   │   │   │   ├── favicon
│   │   │   │   │   ├── apple-touch-icon.png
│   │   │   │   │   ├── favicon.ico
│   │   │   │   │   └── favicon.png
│   │   │   │   ├── footer-icons.svg
│   │   │   │   ├── icons
│   │   │   │   │   ├── arrow-down.svg
│   │   │   │   │   ├── arrow-left.svg
│   │   │   │   │   ├── arrow-right.svg
│   │   │   │   │   ├── checkbox.svg
│   │   │   │   │   ├── external-link.svg
│   │   │   │   │   ├── heart-big.svg
│   │   │   │   │   ├── scalable.svg
│   │   │   │   │   ├── search.svg
│   │   │   │   │   ├── secure.svg
│   │   │   │   │   ├── slack.svg
│   │   │   │   │   ├── stable-old.svg
│   │   │   │   │   └── stable.svg
│   │   │   │   ├── logo.svg
│   │   │   │   ├── menu.svg
│   │   │   │   └── social-icons
│   │   │   │       ├── github.svg
│   │   │   │       ├── opencollective.svg
│   │   │   │       ├── slack.svg
│   │   │   │       └── twitter.svg
│   │   │   ├── javascripts
│   │   │   │   ├── common.js
│   │   │   │   ├── modernizr
│   │   │   │   │   └── modernizr.js
│   │   │   │   ├── search_index.js
│   │   │   │   ├── search.js
│   │   │   │   └── vendor
│   │   │   │       ├── popover.js
│   │   │   │       ├── prism.js
│   │   │   │       └── tooltip.js
│   │   │   └── stylesheets
│   │   │       ├── components
│   │   │       │   ├── _accordion.scss
│   │   │       │   ├── _blocks.scss
│   │   │       │   ├── _fonts.scss
│   │   │       │   ├── _footnote.scss
│   │   │       │   ├── _images.scss
│   │   │       │   ├── _layout.scss
│   │   │       │   ├── _misc.scss
│   │   │       │   ├── _navigation.scss
│   │   │       │   ├── search.scss
│   │   │       │   └── _text.scss
│   │   │       ├── _helper.scss
│   │   │       ├── mixins
│   │   │       │   └── _mixins.scss
│   │   │       ├── site.scss
│   │   │       ├── _variables.scss
│   │   │       └── vendor
│   │   │           ├── aos
│   │   │           │   ├── _animations.scss
│   │   │           │   ├── aos.scss
│   │   │           │   ├── _core.scss
│   │   │           │   └── _easing.scss
│   │   │           ├── bootstrap
│   │   │           │   ├── bootstrap.scss
│   │   │           │   └── theme
│   │   │           │       ├── _buttons.scss
│   │   │           │       ├── _card.scss
│   │   │           │       ├── _code.scss
│   │   │           │       ├── _forms.scss
│   │   │           │       ├── _grid.scss
│   │   │           │       ├── mixins
│   │   │           │       │   ├── _buttons.scss
│   │   │           │       │   └── _text-emphasis.scss
│   │   │           │       ├── _mixins.scss
│   │   │           │       ├── _nav.scss
│   │   │           │       ├── _popover.scss
│   │   │           │       ├── _reboot.scss
│   │   │           │       ├── _tables.scss
│   │   │           │       ├── _type.scss
│   │   │           │       ├── utilities
│   │   │           │       │   └── _text.scss
│   │   │           │       ├── _utilities.scss
│   │   │           │       └── _variables.scss
│   │   │           ├── nouislider
│   │   │           │   ├── nouislider.scss
│   │   │           │   └── _theme.scss
│   │   │           └── prism
│   │   │               ├── _prism.scss
│   │   │               └── _theme.scss
│   │   ├── contents.json.erb
│   │   ├── contributing.html.md
│   │   ├── developers
│   │   │   ├── adjustments
│   │   │   │   └── overview.html.md
│   │   │   ├── api
│   │   │   │   ├── endpoints.html.md
│   │   │   │   └── overview.html.md
│   │   │   ├── assets
│   │   │   │   ├── asset-management.html.md
│   │   │   │   └── override-solidus-assets.html.md
│   │   │   ├── calculators
│   │   │   │   ├── overview.html.md
│   │   │   │   ├── promotion-calculators.html.md
│   │   │   │   ├── shipping-calculators.html.md
│   │   │   │   └── tax-calculator.html.md
│   │   │   ├── events
│   │   │   │   └── overview.html.md
│   │   │   ├── extensions
│   │   │   │   ├── decorators.html.md
│   │   │   │   ├── installing-extensions.html.md
│   │   │   │   ├── testing-extensions.html.md
│   │   │   │   └── writing-extensions.html.md
│   │   │   ├── getting-started
│   │   │   │   ├── customer-flow.html.md
│   │   │   │   ├── develop-solidus.html.md
│   │   │   │   ├── first-time-installation.html.md
│   │   │   │   ├── forking-solidus.html.md
│   │   │   │   └── installation-options.html.md
│   │   │   ├── index.html.md
│   │   │   ├── inventory
│   │   │   │   ├── inventory-units.html.md
│   │   │   │   ├── overview.html.md
│   │   │   │   ├── stock-items.html.md
│   │   │   │   └── stock-movements.html.md
│   │   │   ├── locations
│   │   │   │   ├── countries-and-states.html.md
│   │   │   │   ├── overview.html.md
│   │   │   │   └── zones.html.md
│   │   │   ├── orders
│   │   │   │   ├── display-total-methods.html.md
│   │   │   │   ├── order-state-machine.html.md
│   │   │   │   ├── overview.html.md
│   │   │   │   ├── payment-states.html.md
│   │   │   │   └── update-orders.html.md
│   │   │   ├── payments
│   │   │   │   ├── overview.html.md
│   │   │   │   ├── payment-methods.html.md
│   │   │   │   ├── payment-processing.html.md
│   │   │   │   ├── payment-service-providers.html.md
│   │   │   │   ├── payments.html.md
│   │   │   │   ├── payment-sources.html.md
│   │   │   │   └── refunds.html.md
│   │   │   ├── preferences
│   │   │   │   ├── add-model-preferences.html.md
│   │   │   │   ├── app-configuration.html.md
│   │   │   │   └── class-extension-points.html.md
│   │   │   ├── products-and-variants
│   │   │   │   ├── multi-currency-support.html.md
│   │   │   │   ├── overview.html.md
│   │   │   │   ├── product-images.html.md
│   │   │   │   ├── product-properties.html.md
│   │   │   │   ├── products.html.md
│   │   │   │   ├── taxonomies-and-taxons.html.md
│   │   │   │   └── variants.html.md
│   │   │   ├── promotions
│   │   │   │   ├── overview.html.md
│   │   │   │   ├── promotion-actions.html.md
│   │   │   │   ├── promotion-handlers.html.md
│   │   │   │   └── promotion-rules.html.md
│   │   │   ├── returns
│   │   │   │   ├── customer-returns.html.md
│   │   │   │   ├── overview.html.md
│   │   │   │   ├── reimbursements.html.md
│   │   │   │   ├── reimbursement-types.html.md
│   │   │   │   ├── return-authorizations.html.md
│   │   │   │   └── return-items.html.md
│   │   │   ├── shipments
│   │   │   │   ├── cartons.html.md
│   │   │   │   ├── custom-shipping-calculators.html.md
│   │   │   │   ├── overview.html.md
│   │   │   │   ├── shipment-setup-examples.html.md
│   │   │   │   ├── shipping-method-filters.html.md
│   │   │   │   ├── solidus-active-shipping-extension.html.md
│   │   │   │   ├── split-shipments.html.md
│   │   │   │   ├── stock-allocator.html.md
│   │   │   │   ├── stock-locations-filter.html.md
│   │   │   │   ├── stock-locations-sorter.html.md
│   │   │   │   └── user-interface-for-shipments.html.md
│   │   │   ├── taxation
│   │   │   │   ├── custom-tax-calculators.html.md
│   │   │   │   ├── displaying-prices.html.md
│   │   │   │   ├── example-tax-setups.html.md
│   │   │   │   ├── overview.html.md
│   │   │   │   └── value-added-tax.html.md
│   │   │   ├── upgrades
│   │   │   │   ├── migrate-from-spree.html.md
│   │   │   │   ├── overview.html.md
│   │   │   │   └── versioning-guidelines.html.md
│   │   │   ├── users
│   │   │   │   ├── addresses.html.md
│   │   │   │   └── custom-authentication.html.md
│   │   │   └── views
│   │   │       ├── custom-frontend.html.md
│   │   │       └── override-views.html.md
│   │   ├── index.html.md
│   │   ├── layouts
│   │   │   ├── article.erb
│   │   │   ├── index.erb
│   │   │   └── layout.erb
│   │   ├── partials
│   │   │   ├── _anchor.erb
│   │   │   ├── _code_block.erb
│   │   │   ├── _feedback.erb
│   │   │   ├── _footer.erb
│   │   │   ├── _header.erb
│   │   │   ├── _nav_content.erb
│   │   │   ├── _nav.erb
│   │   │   ├── _nav_header.erb
│   │   │   ├── _nav_tree_single.erb
│   │   │   ├── _nav_tree_submenu.erb
│   │   │   ├── _security_updates.erb
│   │   │   └── _table.erb
│   │   ├── search.html.erb
│   │   └── users
│   │       ├── index.html.md
│   │       ├── orders
│   │       │   ├── overview.html.md
│   │       │   └── shipments.html.md
│   │       ├── products
│   │       │   ├── option-types.html.md
│   │       │   ├── overview.html.md
│   │       │   ├── product-details.html.md
│   │       │   ├── product-properties.html.md
│   │       │   ├── product-stock.html.md
│   │       │   └── variants.html.md
│   │       ├── promotions
│   │       │   ├── overview.html.md
│   │       │   ├── promotion-actions.html.md
│   │       │   ├── promotion-calculators.html.md
│   │       │   └── promotion-rules.html.md
│   │       ├── settings
│   │       │   ├── overview.html.md
│   │       │   ├── payments.html.md
│   │       │   ├── refunds-and-returns.html.md
│   │       │   ├── shipping.html.md
│   │       │   ├── stores.html.md
│   │       │   ├── taxes.html.md
│   │       │   └── zones.html.md
│   │       ├── stock
│   │       │   └── overview.html.md
│   │       └── users
│   │           └── overview.html.md
│   ├── webpack.common.js
│   ├── webpack.dev.js
│   ├── webpack.prod.js
│   └── yarn.lock
├── lib
│   ├── demo
│   │   ├── docker-entrypoint.sh
│   │   ├── Dockerfile
│   │   └── README.md
│   ├── sandbox.sh
│   ├── solidus.rb
│   └── spree.rb
├── LICENSE.md
├── logo.svg
├── package.json
├── Rakefile
├── README.md
├── sample
│   ├── db
│   │   ├── samples
│   │   │   ├── addresses.rb
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
│   │   │   │   └── ruby_baseball.png
│   │   │   ├── option_types.rb
│   │   │   ├── option_values.rb
│   │   │   ├── orders.rb
│   │   │   ├── payment_methods.rb
│   │   │   ├── payments.rb
│   │   │   ├── product_option_types.rb
│   │   │   ├── product_properties.rb
│   │   │   ├── products.rb
│   │   │   ├── reimbursements.rb
│   │   │   ├── shipping_categories.rb
│   │   │   ├── shipping_methods.rb
│   │   │   ├── stock.rb
│   │   │   ├── stores.rb
│   │   │   ├── tax_categories.rb
│   │   │   ├── taxonomies.rb
│   │   │   ├── taxons.rb
│   │   │   ├── tax_rates.rb
│   │   │   └── variants.rb
│   │   └── samples.rb
│   ├── lib
│   │   ├── solidus_sample.rb
│   │   ├── spree
│   │   │   └── sample.rb
│   │   ├── spree_sample.rb
│   │   └── tasks
│   │       └── sample.rake
│   ├── LICENSE
│   ├── Rakefile
│   ├── README.md
│   ├── solidus_sample.gemspec
│   └── spec
│       ├── lib
│       │   └── load_sample_spec.rb
│       └── spec_helper.rb
└── solidus.gemspec

578 directories, 2302 files
