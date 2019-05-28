saleor
├── apollo.config.js
├── app.json
├── CHANGELOG.md
├── common.env
├── deployment
│   └── elasticbeanstalk
│       └── Dockerrun.aws.json
├── docker-compose.override.yml
├── docker-compose.yml
├── Dockerfile
├── docs
│   ├── architecture
│   │   ├── events.rst
│   │   ├── gdpr.rst
│   │   ├── graphql.rst
│   │   ├── i18n.rst
│   │   ├── money.rst
│   │   ├── orders.rst
│   │   ├── page.rst
│   │   ├── payments.rst
│   │   ├── products.rst
│   │   ├── search.rst
│   │   ├── settings.rst
│   │   ├── shippings.rst
│   │   ├── stock.rst
│   │   ├── thumbnails.rst
│   │   └── translations.rst
│   ├── architecture.rst
│   ├── conf.py
│   ├── contributing
│   │   ├── coding-style.rst
│   │   ├── editorconfig.rst
│   │   └── naming.rst
│   ├── contributing.rst
│   ├── customization
│   │   ├── backend.rst
│   │   ├── ci.rst
│   │   ├── docker.rst
│   │   ├── emails.rst
│   │   ├── frontend.rst
│   │   ├── i18n.rst
│   │   ├── pypy.rst
│   │   ├── templates.rst
│   │   └── tests.rst
│   ├── customization.rst
│   ├── deployment
│   │   ├── docker.rst
│   │   ├── gcs.rst
│   │   ├── heroku.rst
│   │   └── s3.rst
│   ├── deployment.rst
│   ├── gettingstarted
│   │   ├── configuration.rst
│   │   ├── dev-tools.rst
│   │   ├── example-data.rst
│   │   ├── installation-linux.rst
│   │   ├── installation-macos.rst
│   │   ├── installation-windows.rst
│   │   └── superuser.rst
│   ├── gettingstarted.rst
│   ├── guides
│   │   ├── email_integration.rst
│   │   ├── navigation.rst
│   │   ├── orders.rst
│   │   ├── payments.rst
│   │   ├── recaptcha.rst
│   │   └── taxes.rst
│   ├── guides.rst
│   ├── img
│   │   └── product_class_tree.png
│   ├── index.rst
│   ├── integrations
│   │   ├── elasticsearch.rst
│   │   ├── emailmarkup.rst
│   │   ├── googleanalytics.rst
│   │   ├── googleforretail.rst
│   │   ├── openexchangerates.rst
│   │   ├── sentry.rst
│   │   ├── seo.rst
│   │   └── smo.rst
│   ├── integrations.rst
│   ├── logo.svg
│   ├── make.bat
│   ├── Makefile
│   ├── payment-gateways
│   │   ├── braintree.rst
│   │   ├── razorpay.rst
│   │   └── stripe.rst
│   └── payment-gateways.rst
├── LICENSE
├── locale
│   ├── ar
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── az
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── bg
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── bn
│   │   └── LC_MESSAGES
│   │       ├── django.mo
│   │       └── django.po
│   ├── ca
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── cs
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── da
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── de
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── en
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── es
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── es_CO
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── et
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── fa
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── fr
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── hi
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── hu
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── hy
│   │   └── LC_MESSAGES
│   │       ├── django.mo
│   │       └── django.po
│   ├── id
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── it
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── ja
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── ko
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── mn
│   │   └── LC_MESSAGES
│   │       ├── django.mo
│   │       └── django.po
│   ├── nb
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── nl
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── pl
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── pt
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── pt_BR
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── ro
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── ru
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── sk
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── sl
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── sq
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── sr
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── sv
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── sw
│   │   └── LC_MESSAGES
│   │       ├── django.mo
│   │       └── django.po
│   ├── th
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── tr
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── uk
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── vi
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   ├── zh_Hans
│   │   └── LC_MESSAGES
│   │       ├── djangojs.mo
│   │       ├── djangojs.po
│   │       ├── django.mo
│   │       └── django.po
│   └── zh_Hant
│       └── LC_MESSAGES
│           ├── djangojs.mo
│           ├── djangojs.po
│           ├── django.mo
│           └── django.po
├── manage.py
├── package.json
├── package-lock.json
├── Pipfile
├── Pipfile.lock
├── Procfile
├── pyproject.toml
├── README.md
├── requirements_dev.txt
├── requirements.txt
├── runtime.txt
├── saleor
│   ├── account
│   │   ├── backends
│   │   │   ├── facebook.py
│   │   │   ├── google.py
│   │   │   └── __init__.py
│   │   ├── emails.py
│   │   ├── events.py
│   │   ├── forms.py
│   │   ├── i18n.py
│   │   ├── impersonate.py
│   │   ├── __init__.py
│   │   ├── management
│   │   │   ├── commands
│   │   │   │   ├── changepassword.py
│   │   │   │   ├── createsuperuser.py
│   │   │   │   └── __init__.py
│   │   │   └── __init__.py
│   │   ├── migrations
│   │   │   ├── 0001_initial.py
│   │   │   ├── 0002_auto_20150907_0602.py
│   │   │   ├── 0003_auto_20151104_1102.py
│   │   │   ├── 0004_auto_20160114_0419.py
│   │   │   ├── 0005_auto_20160205_0651.py
│   │   │   ├── 0006_auto_20160829_0819.py
│   │   │   ├── 0007_auto_20161115_0940.py
│   │   │   ├── 0008_auto_20161115_1011.py
│   │   │   ├── 0009_auto_20170206_0407.py
│   │   │   ├── 0010_auto_20170919_0839.py
│   │   │   ├── 0011_auto_20171110_0552.py
│   │   │   ├── 0012_auto_20171117_0846.py
│   │   │   ├── 0013_auto_20171120_0521.py
│   │   │   ├── 0014_auto_20171129_1004.py
│   │   │   ├── 0015_auto_20171213_0734.py
│   │   │   ├── 0016_auto_20180108_0814.py
│   │   │   ├── 0017_auto_20180206_0957.py
│   │   │   ├── 0018_auto_20180426_0641.py
│   │   │   ├── 0019_auto_20180528_1205.py
│   │   │   ├── 0020_user_token.py
│   │   │   ├── 0021_unique_token.py
│   │   │   ├── 0022_auto_20180718_0956.py
│   │   │   ├── 0023_auto_20180719_0520.py
│   │   │   ├── 0024_auto_20181011_0737.py
│   │   │   ├── 0025_auto_20190314_0550.py
│   │   │   ├── 0026_user_avatar.py
│   │   │   ├── 0027_customerevent.py
│   │   │   └── __init__.py
│   │   ├── models.py
│   │   ├── templatetags
│   │   │   ├── i18n_address_tags.py
│   │   │   └── __init__.py
│   │   ├── thumbnails.py
│   │   ├── urls.py
│   │   ├── utils.py
│   │   ├── validators.py
│   │   ├── views.py
│   │   └── widgets.py
│   ├── celeryconf.py
│   ├── checkout
│   │   ├── context_processors.py
│   │   ├── forms.py
│   │   ├── __init__.py
│   │   ├── migrations
│   │   │   ├── 0001_auto_20170113_0435.py
│   │   │   ├── 0001_initial.py
│   │   │   ├── 0002_auto_20161014_1221.py
│   │   │   ├── 0002_auto_20170206_0407.py
│   │   │   ├── 0003_auto_20170906_0556.py
│   │   │   ├── 0004_auto_20171129_1004.py
│   │   │   ├── 0005_auto_20180108_0814.py
│   │   │   ├── 0006_auto_20180221_0825.py
│   │   │   ├── 0007_merge_cart_with_checkout.py
│   │   │   ├── 0008_rename_tables.py
│   │   │   ├── 0009_cart_translated_discount_name.py
│   │   │   ├── 0010_auto_20180822_0720.py
│   │   │   ├── 0011_auto_20180913_0817.py
│   │   │   ├── 0012_remove_cartline_data.py
│   │   │   ├── 0013_auto_20180913_0841.py
│   │   │   ├── 0014_auto_20180921_0751.py
│   │   │   ├── 0015_auto_20181017_1346.py
│   │   │   ├── 0016_auto_20190112_0506.py
│   │   │   ├── 0017_auto_20190130_0207.py
│   │   │   ├── 0018_auto_20190410_0132.py
│   │   │   ├── fix_empty_data_in_lines.py
│   │   │   └── __init__.py
│   │   ├── models.py
│   │   ├── urls.py
│   │   ├── utils.py
│   │   └── views
│   │       ├── discount.py
│   │       ├── __init__.py
│   │       ├── shipping.py
│   │       ├── summary.py
│   │       └── validators.py
│   ├── core
│   │   ├── analytics.py
│   │   ├── context_processors.py
│   │   ├── emails.py
│   │   ├── exceptions.py
│   │   ├── filters.py
│   │   ├── i18n.py
│   │   ├── __init__.py
│   │   ├── management
│   │   │   ├── commands
│   │   │   │   ├── create_thumbnails.py
│   │   │   │   ├── __init__.py
│   │   │   │   └── populatedb.py
│   │   │   └── __init__.py
│   │   ├── middleware.py
│   │   ├── migrations
│   │   │   └── __init__.py
│   │   ├── models.py
│   │   ├── permissions.py
│   │   ├── sitemaps.py
│   │   ├── storages.py
│   │   ├── templatetags
│   │   │   ├── attributes.py
│   │   │   ├── dashboard.py
│   │   │   ├── __init__.py
│   │   │   ├── markdown.py
│   │   │   ├── materializecss.py
│   │   │   ├── placeholder.py
│   │   │   ├── shop.py
│   │   │   ├── status.py
│   │   │   ├── taxed_prices.py
│   │   │   ├── urls.py
│   │   │   └── version.py
│   │   ├── urls.py
│   │   ├── utils
│   │   │   ├── filters.py
│   │   │   ├── form_renderer.py
│   │   │   ├── __init__.py
│   │   │   ├── json_serializer.py
│   │   │   ├── random_data.py
│   │   │   ├── taxes.py
│   │   │   ├── text.py
│   │   │   └── translations.py
│   │   ├── views.py
│   │   └── weight.py
│   ├── dashboard
│   │   ├── category
│   │   │   ├── filters.py
│   │   │   ├── forms.py
│   │   │   ├── __init__.py
│   │   │   ├── urls.py
│   │   │   └── views.py
│   │   ├── collection
│   │   │   ├── filters.py
│   │   │   ├── forms.py
│   │   │   ├── __init__.py
│   │   │   ├── urls.py
│   │   │   └── views.py
│   │   ├── customer
│   │   │   ├── filters.py
│   │   │   ├── forms.py
│   │   │   ├── __init__.py
│   │   │   ├── urls.py
│   │   │   └── views.py
│   │   ├── discount
│   │   │   ├── filters.py
│   │   │   ├── forms.py
│   │   │   ├── __init__.py
│   │   │   ├── urls.py
│   │   │   └── views.py
│   │   ├── emails.py
│   │   ├── forms.py
│   │   ├── __init__.py
│   │   ├── locale
│   │   │   ├── ar
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── az
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── bg
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── bn
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── ca
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── cs
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── da
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── de
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── en
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── es
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── es_CO
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── et
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── fa
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── fr
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── hi
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── hu
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── hy
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── id
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── it
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── ja
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── ko
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── lt
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── mn
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── nb
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── nl
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── pl
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── pt
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── pt_BR
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── ro
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── ru
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── sk
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── sl
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── sq
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── sr
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── sv
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── sw
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── th
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── tr
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── uk
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── vi
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   ├── zh_Hans
│   │   │   │   └── LC_MESSAGES
│   │   │   │       ├── django.mo
│   │   │   │       └── django.po
│   │   │   └── zh_Hant
│   │   │       └── LC_MESSAGES
│   │   │           ├── django.mo
│   │   │           └── django.po
│   │   ├── menu
│   │   │   ├── filters.py
│   │   │   ├── forms.py
│   │   │   ├── __init__.py
│   │   │   ├── urls.py
│   │   │   ├── utils.py
│   │   │   └── views.py
│   │   ├── order
│   │   │   ├── filters.py
│   │   │   ├── forms.py
│   │   │   ├── __init__.py
│   │   │   ├── urls.py
│   │   │   ├── utils.py
│   │   │   └── views.py
│   │   ├── page
│   │   │   ├── filters.py
│   │   │   ├── forms.py
│   │   │   ├── __init__.py
│   │   │   ├── urls.py
│   │   │   └── views.py
│   │   ├── product
│   │   │   ├── filters.py
│   │   │   ├── forms.py
│   │   │   ├── __init__.py
│   │   │   ├── urls.py
│   │   │   ├── views.py
│   │   │   └── widgets.py
│   │   ├── search
│   │   │   ├── forms.py
│   │   │   ├── __init__.py
│   │   │   ├── urls.py
│   │   │   └── views.py
│   │   ├── seo
│   │   │   ├── fields.py
│   │   │   └── utils.py
│   │   ├── shipping
│   │   │   ├── filters.py
│   │   │   ├── forms.py
│   │   │   ├── __init__.py
│   │   │   ├── urls.py
│   │   │   └── views.py
│   │   ├── sites
│   │   │   ├── forms.py
│   │   │   ├── __init__.py
│   │   │   ├── urls.py
│   │   │   └── views.py
│   │   ├── staff
│   │   │   ├── filters.py
│   │   │   ├── forms.py
│   │   │   ├── __init__.py
│   │   │   ├── urls.py
│   │   │   ├── utils.py
│   │   │   └── views.py
│   │   ├── taxes
│   │   │   ├── filters.py
│   │   │   ├── forms.py
│   │   │   ├── __init__.py
│   │   │   ├── urls.py
│   │   │   └── views.py
│   │   ├── templatetags
│   │   │   ├── chips.py
│   │   │   ├── __init__.py
│   │   │   ├── orders.py
│   │   │   └── utils.py
│   │   ├── urls.py
│   │   ├── views.py
│   │   └── widgets.py
│   ├── data_feeds
│   │   ├── google_merchant.py
│   │   ├── __init__.py
│   │   ├── management
│   │   │   ├── commands
│   │   │   │   ├── __init__.py
│   │   │   │   └── update_feeds.py
│   │   │   └── __init__.py
│   │   └── urls.py
│   ├── discount
│   │   ├── __init__.py
│   │   ├── migrations
│   │   │   ├── 0001_initial.py
│   │   │   ├── 0002_voucher.py
│   │   │   ├── 0003_auto_20160207_0534.py
│   │   │   ├── 0004_auto_20170206_0407.py
│   │   │   ├── 0005_auto_20170919_0839.py
│   │   │   ├── 0006_auto_20171129_1004.py
│   │   │   ├── 0007_auto_20180108_0814.py
│   │   │   ├── 0008_sale_collections.py
│   │   │   ├── 0009_auto_20180719_0520.py
│   │   │   ├── 0010_auto_20180724_1251.py
│   │   │   ├── 0011_auto_20180803_0528.py
│   │   │   ├── 0012_auto_20190329_0836.py
│   │   │   └── __init__.py
│   │   ├── models.py
│   │   ├── templatetags
│   │   │   ├── __init__.py
│   │   │   └── voucher.py
│   │   └── utils.py
│   ├── graphql
│   │   ├── account
│   │   │   ├── bulk_mutations.py
│   │   │   ├── enums.py
│   │   │   ├── fields.py
│   │   │   ├── filters.py
│   │   │   ├── i18n.py
│   │   │   ├── __init__.py
│   │   │   ├── mutations.py
│   │   │   ├── resolvers.py
│   │   │   ├── schema.py
│   │   │   ├── types.py
│   │   │   └── utils.py
│   │   ├── api.py
│   │   ├── checkout
│   │   │   ├── __init__.py
│   │   │   ├── mutations.py
│   │   │   ├── resolvers.py
│   │   │   ├── schema.py
│   │   │   └── types.py
│   │   ├── core
│   │   │   ├── connection.py
│   │   │   ├── enums.py
│   │   │   ├── fields.py
│   │   │   ├── filters.py
│   │   │   ├── __init__.py
│   │   │   ├── mutations.py
│   │   │   ├── scalars.py
│   │   │   ├── schema.py
│   │   │   ├── types
│   │   │   │   ├── common.py
│   │   │   │   ├── converter.py
│   │   │   │   ├── filter_input.py
│   │   │   │   ├── __init__.py
│   │   │   │   ├── money.py
│   │   │   │   └── upload.py
│   │   │   └── utils.py
│   │   ├── descriptions.py
│   │   ├── discount
│   │   │   ├── bulk_mutations.py
│   │   │   ├── enums.py
│   │   │   ├── filters.py
│   │   │   ├── __init__.py
│   │   │   ├── mutations.py
│   │   │   ├── resolvers.py
│   │   │   ├── schema.py
│   │   │   └── types.py
│   │   ├── __init__.py
│   │   ├── management
│   │   │   ├── commands
│   │   │   │   ├── get_graphql_schema.py
│   │   │   │   └── __init__.py
│   │   │   └── __init__.py
│   │   ├── menu
│   │   │   ├── bulk_mutations.py
│   │   │   ├── enums.py
│   │   │   ├── __init__.py
│   │   │   ├── mutations.py
│   │   │   ├── resolvers.py
│   │   │   ├── schema.py
│   │   │   └── types.py
│   │   ├── middleware.py
│   │   ├── order
│   │   │   ├── bulk_mutations
│   │   │   │   ├── draft_orders.py
│   │   │   │   ├── __init__.py
│   │   │   │   └── orders.py
│   │   │   ├── enums.py
│   │   │   ├── filters.py
│   │   │   ├── __init__.py
│   │   │   ├── mutations
│   │   │   │   ├── draft_orders.py
│   │   │   │   ├── fulfillments.py
│   │   │   │   ├── __init__.py
│   │   │   │   └── orders.py
│   │   │   ├── resolvers.py
│   │   │   ├── schema.py
│   │   │   ├── types.py
│   │   │   └── utils.py
│   │   ├── page
│   │   │   ├── bulk_mutations.py
│   │   │   ├── __init__.py
│   │   │   ├── mutations.py
│   │   │   ├── resolvers.py
│   │   │   ├── schema.py
│   │   │   └── types.py
│   │   ├── payment
│   │   │   ├── enums.py
│   │   │   ├── __init__.py
│   │   │   ├── mutations.py
│   │   │   ├── resolvers.py
│   │   │   ├── schema.py
│   │   │   └── types.py
│   │   ├── product
│   │   │   ├── bulk_mutations
│   │   │   │   ├── attributes.py
│   │   │   │   ├── __init__.py
│   │   │   │   └── products.py
│   │   │   ├── descriptions.py
│   │   │   ├── enums.py
│   │   │   ├── filters.py
│   │   │   ├── __init__.py
│   │   │   ├── mutations
│   │   │   │   ├── attributes.py
│   │   │   │   ├── digital_contents.py
│   │   │   │   ├── __init__.py
│   │   │   │   └── products.py
│   │   │   ├── resolvers.py
│   │   │   ├── scalars.py
│   │   │   ├── schema.py
│   │   │   ├── types
│   │   │   │   ├── attributes.py
│   │   │   │   ├── digital_contents.py
│   │   │   │   ├── __init__.py
│   │   │   │   └── products.py
│   │   │   └── utils.py
│   │   ├── schema.graphql
│   │   ├── shipping
│   │   │   ├── bulk_mutations.py
│   │   │   ├── enums.py
│   │   │   ├── __init__.py
│   │   │   ├── mutations.py
│   │   │   ├── resolvers.py
│   │   │   ├── schema.py
│   │   │   └── types.py
│   │   ├── shop
│   │   │   ├── enums.py
│   │   │   ├── __init__.py
│   │   │   ├── mutations.py
│   │   │   ├── schema.py
│   │   │   └── types.py
│   │   ├── translations
│   │   │   ├── enums.py
│   │   │   ├── __init__.py
│   │   │   ├── mutations.py
│   │   │   ├── resolvers.py
│   │   │   ├── schema.py
│   │   │   └── types.py
│   │   ├── utils.py
│   │   └── views.py
│   ├── __init__.py
│   ├── menu
│   │   ├── __init__.py
│   │   ├── migrations
│   │   │   ├── 0001_initial.py
│   │   │   ├── 0002_auto_20180319_0412.py
│   │   │   ├── 0003_auto_20180405_0854.py
│   │   │   ├── 0004_sort_order_index.py
│   │   │   ├── 0005_auto_20180719_0520.py
│   │   │   ├── 0006_auto_20180803_0528.py
│   │   │   ├── 0007_auto_20180807_0547.py
│   │   │   ├── 0008_menu_json_content_new.py
│   │   │   ├── 0009_remove_menu_json_content.py
│   │   │   ├── 0010_auto_20180913_0841.py
│   │   │   ├── 0011_auto_20181204_0004.py
│   │   │   ├── 0012_auto_20190104_0443.py
│   │   │   ├── 0013_auto_20190507_0309.py
│   │   │   └── __init__.py
│   │   └── models.py
│   ├── order
│   │   ├── emails.py
│   │   ├── events.py
│   │   ├── forms.py
│   │   ├── __init__.py
│   │   ├── migrations
│   │   │   ├── 0001_initial.py
│   │   │   ├── 0002_auto_20150820_1955.py
│   │   │   ├── 0003_auto_20150825_1433.py
│   │   │   ├── 0004_order_total.py
│   │   │   ├── 0005_deliverygroup_last_updated.py
│   │   │   ├── 0006_deliverygroup_shipping_method.py
│   │   │   ├── 0007_deliverygroup_tracking_number.py
│   │   │   ├── 0008_auto_20151026_0820.py
│   │   │   ├── 0009_auto_20151201_0820.py
│   │   │   ├── 0010_auto_20160119_0541.py
│   │   │   ├── 0011_auto_20160207_0534.py
│   │   │   ├── 0012_auto_20160216_1032.py
│   │   │   ├── 0013_auto_20160906_0741.py
│   │   │   ├── 0014_auto_20161028_0955.py
│   │   │   ├── 0015_auto_20170206_0407.py
│   │   │   ├── 0016_order_language_code.py
│   │   │   ├── 0017_auto_20170906_0556.py
│   │   │   ├── 0018_auto_20170919_0839.py
│   │   │   ├── 0019_auto_20171109_1423.py
│   │   │   ├── 0020_auto_20171123_0609.py
│   │   │   ├── 0021_auto_20171129_1004.py
│   │   │   ├── 0022_auto_20171205_0428.py
│   │   │   ├── 0023_auto_20171206_0506.py
│   │   │   ├── 0024_remove_order_status.py
│   │   │   ├── 0025_auto_20171214_1015.py
│   │   │   ├── 0026_auto_20171218_0428.py
│   │   │   ├── 0027_auto_20180108_0814.py
│   │   │   ├── 0028_status_fsm.py
│   │   │   ├── 0029_auto_20180111_0845.py
│   │   │   ├── 0030_auto_20180118_0605.py
│   │   │   ├── 0031_auto_20180119_0405.py
│   │   │   ├── 0032_orderline_is_shipping_required.py
│   │   │   ├── 0033_auto_20180123_0832.py
│   │   │   ├── 0034_auto_20180221_1056.py
│   │   │   ├── 0035_auto_20180221_1057.py
│   │   │   ├── 0036_remove_order_total_tax.py
│   │   │   ├── 0037_auto_20180228_0450.py
│   │   │   ├── 0038_auto_20180228_0451.py
│   │   │   ├── 0039_auto_20180312_1203.py
│   │   │   ├── 0040_auto_20180210_0422.py
│   │   │   ├── 0041_auto_20180222_0458.py
│   │   │   ├── 0042_auto_20180227_0436.py
│   │   │   ├── 0043_auto_20180322_0655.py
│   │   │   ├── 0044_auto_20180326_1055.py
│   │   │   ├── 0045_auto_20180329_0142.py
│   │   │   ├── 0046_order_line_taxes.py
│   │   │   ├── 0047_order_line_name_length.py
│   │   │   ├── 0048_auto_20180629_1055.py
│   │   │   ├── 0049_auto_20180719_0520.py
│   │   │   ├── 0050_auto_20180803_0337.py
│   │   │   ├── 0050_auto_20180803_0528.py
│   │   │   ├── 0051_merge_20180807_0704.py
│   │   │   ├── 0052_auto_20180822_0720.py
│   │   │   ├── 0053_orderevent.py
│   │   │   ├── 0054_move_data_to_order_events.py
│   │   │   ├── 0055_remove_order_note_order_history_entry.py
│   │   │   ├── 0056_auto_20180911_1541.py
│   │   │   ├── 0057_orderevent_parameters_new.py
│   │   │   ├── 0058_remove_orderevent_parameters.py
│   │   │   ├── 0059_auto_20180913_0841.py
│   │   │   ├── 0060_auto_20180919_0731.py
│   │   │   ├── 0061_auto_20180920_0859.py
│   │   │   ├── 0062_auto_20180921_0949.py
│   │   │   ├── 0063_auto_20180926_0446.py
│   │   │   ├── 0064_auto_20181016_0819.py
│   │   │   ├── 0065_auto_20181017_1346.py
│   │   │   ├── 0066_auto_20181023_0319.py
│   │   │   ├── 0067_auto_20181102_1054.py
│   │   │   ├── 0068_order_checkout_token.py
│   │   │   ├── 0069_auto_20190225_2305.py
│   │   │   ├── 0070_drop_update_event_and_rename_events.py
│   │   │   └── __init__.py
│   │   ├── models.py
│   │   ├── urls.py
│   │   ├── utils.py
│   │   └── views.py
│   ├── page
│   │   ├── __init__.py
│   │   ├── migrations
│   │   │   ├── 0001_initial.py
│   │   │   ├── 0002_auto_20180321_0417.py
│   │   │   ├── 0003_auto_20180719_0520.py
│   │   │   ├── 0004_auto_20180803_0528.py
│   │   │   ├── 0005_auto_20190208_0456.py
│   │   │   ├── 0006_auto_20190220_1928.py
│   │   │   ├── 0007_auto_20190225_0252.py
│   │   │   └── __init__.py
│   │   ├── models.py
│   │   ├── urls.py
│   │   ├── utils.py
│   │   └── views.py
│   ├── payment
│   │   ├── gateways
│   │   │   ├── braintree
│   │   │   │   ├── errors.py
│   │   │   │   ├── forms.py
│   │   │   │   └── __init__.py
│   │   │   ├── dummy
│   │   │   │   ├── forms.py
│   │   │   │   └── __init__.py
│   │   │   ├── __init__.py
│   │   │   ├── razorpay
│   │   │   │   ├── errors.py
│   │   │   │   ├── forms.py
│   │   │   │   ├── __init__.py
│   │   │   │   └── utils.py
│   │   │   └── stripe
│   │   │       ├── errors.py
│   │   │       ├── forms.py
│   │   │       ├── __init__.py
│   │   │       └── utils.py
│   │   ├── __init__.py
│   │   ├── interface.py
│   │   ├── migrations
│   │   │   ├── 0001_initial.py
│   │   │   ├── 0002_transfer_payment_to_payment_method.py
│   │   │   ├── 0003_rename_payment_method_to_payment.py
│   │   │   ├── 0004_auto_20181206_0031.py
│   │   │   ├── 0005_auto_20190104_0443.py
│   │   │   ├── 0006_auto_20190109_0358.py
│   │   │   ├── 0007_auto_20190125_0242.py
│   │   │   ├── 0007_auto_20190206_0938.py
│   │   │   ├── 0008_merge_20190214_0447.py
│   │   │   ├── 0009_convert_to_partially_charged_and_partially_refunded.py
│   │   │   ├── 0010_auto_20190220_2001.py
│   │   │   ├── 0011_auto_20190516_0901.py
│   │   │   └── __init__.py
│   │   ├── models.py
│   │   └── utils.py
│   ├── product
│   │   ├── filters.py
│   │   ├── forms.py
│   │   ├── __init__.py
│   │   ├── migrations
│   │   │   ├── 0001_initial.py
│   │   │   ├── 0002_auto_20150722_0545.py
│   │   │   ├── 0003_auto_20150820_1955.py
│   │   │   ├── 0003_auto_20150820_2016.py
│   │   │   ├── 0004_merge.py
│   │   │   ├── 0005_auto_20150825_1433.py
│   │   │   ├── 0006_product_updated_at.py
│   │   │   ├── 0007_auto_20160112_1025.py
│   │   │   ├── 0008_auto_20160114_0733.py
│   │   │   ├── 0009_discount_categories.py
│   │   │   ├── 0010_auto_20160129_0826.py
│   │   │   ├── 0011_stock_quantity_allocated.py
│   │   │   ├── 0012_auto_20160218_0812.py
│   │   │   ├── 0013_auto_20161130_0608.py
│   │   │   ├── 0013_auto_20161207_0555.py
│   │   │   ├── 0014_auto_20161207_0840.py
│   │   │   ├── 0014_remove_productvariant_attributes.py
│   │   │   ├── 0015_productvariant_attributes.py
│   │   │   ├── 0015_transfer_locations.py
│   │   │   ├── 0016_auto_20161204_0311.py
│   │   │   ├── 0016_auto_20161207_0843.py
│   │   │   ├── 0017_attributechoicevalue_slug.py
│   │   │   ├── 0017_remove_stock_location.py
│   │   │   ├── 0018_auto_20161207_0844.py
│   │   │   ├── 0018_auto_20161212_0725.py
│   │   │   ├── 0019_auto_20161212_0230.py
│   │   │   ├── 0020_attribute_data_to_class.py
│   │   │   ├── 0021_add_hstore_extension.py
│   │   │   ├── 0022_auto_20161212_0301.py
│   │   │   ├── 0023_auto_20161211_1912.py
│   │   │   ├── 0024_migrate_json_data.py
│   │   │   ├── 0025_auto_20161219_0517.py
│   │   │   ├── 0026_auto_20161230_0347.py
│   │   │   ├── 0026_merge_20161221_0845.py
│   │   │   ├── 0027_auto_20170113_0435.py
│   │   │   ├── 0028_merge_20170116_1016.py
│   │   │   ├── 0029_product_is_featured.py
│   │   │   ├── 0030_auto_20170206_0407.py
│   │   │   ├── 0031_auto_20170206_0601.py
│   │   │   ├── 0032_auto_20170216_0438.py
│   │   │   ├── 0033_auto_20170227_0757.py
│   │   │   ├── 0034_product_is_published.py
│   │   │   ├── 0035_auto_20170919_0846.py
│   │   │   ├── 0036_auto_20171115_0608.py
│   │   │   ├── 0037_auto_20171124_0847.py
│   │   │   ├── 0037_auto_20171129_1004.py
│   │   │   ├── 0038_auto_20171129_0616.py
│   │   │   ├── 0039_merge_20171130_0727.py
│   │   │   ├── 0040_auto_20171205_0428.py
│   │   │   ├── 0041_auto_20171205_0546.py
│   │   │   ├── 0042_auto_20171206_0501.py
│   │   │   ├── 0043_auto_20171207_0839.py
│   │   │   ├── 0044_auto_20180108_0814.py
│   │   │   ├── 0045_md_to_html.py
│   │   │   ├── 0046_product_category.py
│   │   │   ├── 0047_auto_20180117_0359.py
│   │   │   ├── 0048_product_class_to_type.py
│   │   │   ├── 0049_collection.py
│   │   │   ├── 0050_auto_20180131_0746.py
│   │   │   ├── 0051_auto_20180202_1106.py
│   │   │   ├── 0052_slug_field_length.py
│   │   │   ├── 0053_auto_20180305_1002.py
│   │   │   ├── 0053_product_seo_description.py
│   │   │   ├── 0054_merge_20180320_1108.py
│   │   │   ├── 0055_auto_20180321_0417.py
│   │   │   ├── 0056_auto_20180330_0321.py
│   │   │   ├── 0057_auto_20180403_0852.py
│   │   │   ├── 0058_auto_20180329_0142.py
│   │   │   ├── 0059_generate_variant_name_from_attrs.py
│   │   │   ├── 0060_collection_is_published.py
│   │   │   ├── 0061_product_taxes.py
│   │   │   ├── 0062_sortable_models.py
│   │   │   ├── 0063_required_attr_value_order.py
│   │   │   ├── 0064_productvariant_handle_stock.py
│   │   │   ├── 0065_auto_20180719_0520.py
│   │   │   ├── 0066_auto_20180803_0528.py
│   │   │   ├── 0067_remove_product_is_featured.py
│   │   │   ├── 0068_auto_20180822_0720.py
│   │   │   ├── 0069_auto_20180912_0326.py
│   │   │   ├── 0070_auto_20180912_0329.py
│   │   │   ├── 0071_attributechoicevalue_value.py
│   │   │   ├── 0072_auto_20180925_1048.py
│   │   │   ├── 0073_auto_20181010_0729.py
│   │   │   ├── 0074_auto_20181010_0730.py
│   │   │   ├── 0075_auto_20181010_0842.py
│   │   │   ├── 0076_auto_20181012_1146.py
│   │   │   ├── 0077_generate_versatile_background_images.py
│   │   │   ├── 0078_auto_20181120_0437.py
│   │   │   ├── 0079_default_tax_rate_instead_of_empty_field.py
│   │   │   ├── 0080_auto_20181214_0440.py
│   │   │   ├── 0080_collection_published_date.py
│   │   │   ├── 0081_auto_20181218_0024.py
│   │   │   ├── 0081_merge_20181215_1659.py
│   │   │   ├── 0082_merge_20181219_1440.py
│   │   │   ├── 0083_auto_20190104_0443.py
│   │   │   ├── 0084_auto_20190122_0113.py
│   │   │   ├── 0085_auto_20190125_0025.py
│   │   │   ├── 0086_product_publication_date.py
│   │   │   ├── 0087_auto_20190208_0326.py
│   │   │   ├── 0088_auto_20190220_1928.py
│   │   │   ├── 0089_auto_20190225_0252.py
│   │   │   ├── 0090_auto_20190328_0608.py
│   │   │   ├── 0091_auto_20190402_0853.py
│   │   │   ├── 0092_auto_20190507_0309.py
│   │   │   └── __init__.py
│   │   ├── models.py
│   │   ├── tasks.py
│   │   ├── templatetags
│   │   │   ├── __init__.py
│   │   │   └── product_images.py
│   │   ├── thumbnails.py
│   │   ├── urls.py
│   │   ├── utils
│   │   │   ├── attributes.py
│   │   │   ├── availability.py
│   │   │   ├── costs.py
│   │   │   ├── digital_products.py
│   │   │   ├── __init__.py
│   │   │   └── variants_picker.py
│   │   └── views.py
│   ├── search
│   │   ├── backends
│   │   │   ├── elasticsearch_dashboard.py
│   │   │   ├── elasticsearch.py
│   │   │   ├── elasticsearch_storefront.py
│   │   │   ├── __init__.py
│   │   │   ├── picker.py
│   │   │   ├── postgresql_dashboard.py
│   │   │   ├── postgresql.py
│   │   │   ├── postgresql_storefront.py
│   │   │   ├── test_elasticsearch_dashboard.py
│   │   │   └── test_elasticsearch_storefront.py
│   │   ├── documents.py
│   │   ├── forms.py
│   │   ├── __init__.py
│   │   ├── management
│   │   │   ├── commands
│   │   │   │   └── __init__.py
│   │   │   └── __init__.py
│   │   ├── migrations
│   │   │   └── __init__.py
│   │   ├── urls.py
│   │   └── views.py
│   ├── seo
│   │   ├── __init__.py
│   │   ├── models.py
│   │   └── schema
│   │       ├── email.py
│   │       ├── __init__.py
│   │       ├── product.py
│   │       └── webpage.py
│   ├── settings.py
│   ├── shipping
│   │   ├── __init__.py
│   │   ├── migrations
│   │   │   ├── 0001_initial.py
│   │   │   ├── 0002_auto_20160906_0741.py
│   │   │   ├── 0003_auto_20170116_0700.py
│   │   │   ├── 0004_auto_20170206_0407.py
│   │   │   ├── 0005_auto_20170906_0556.py
│   │   │   ├── 0006_auto_20171109_0908.py
│   │   │   ├── 0007_auto_20171129_1004.py
│   │   │   ├── 0008_auto_20180108_0814.py
│   │   │   ├── 0009_auto_20180629_1055.py
│   │   │   ├── 0010_auto_20180719_0520.py
│   │   │   ├── 0011_auto_20180802_1238.py
│   │   │   ├── 0012_remove_legacy_shipping_methods.py
│   │   │   ├── 0013_auto_20180822_0721.py
│   │   │   ├── 0014_auto_20180920_0956.py
│   │   │   ├── 0015_auto_20190305_0640.py
│   │   │   └── __init__.py
│   │   ├── models.py
│   │   └── utils.py
│   ├── site
│   │   ├── context_processors.py
│   │   ├── __init__.py
│   │   ├── migrations
│   │   │   ├── 0001_initial.py
│   │   │   ├── 0002_add_default_data.py
│   │   │   ├── 0003_sitesettings_description.py
│   │   │   ├── 0004_auto_20170221_0426.py
│   │   │   ├── 0005_auto_20170906_0556.py
│   │   │   ├── 0006_auto_20171025_0454.py
│   │   │   ├── 0007_auto_20171027_0856.py
│   │   │   ├── 0008_auto_20171027_0856.py
│   │   │   ├── 0009_auto_20171109_0849.py
│   │   │   ├── 0010_auto_20171113_0958.py
│   │   │   ├── 0011_auto_20180108_0814.py
│   │   │   ├── 0012_auto_20180405_0757.py
│   │   │   ├── 0013_assign_default_menus.py
│   │   │   ├── 0014_handle_taxes.py
│   │   │   ├── 0015_sitesettings_handle_stock_by_default.py
│   │   │   ├── 0016_auto_20180719_0520.py
│   │   │   ├── 0017_auto_20180803_0528.py
│   │   │   ├── 0018_sitesettings_homepage_collection.py
│   │   │   ├── 0019_sitesettings_default_weight_unit.py
│   │   │   ├── 0020_auto_20190301_0336.py
│   │   │   ├── 0021_auto_20190326_0521.py
│   │   │   └── __init__.py
│   │   ├── models.py
│   │   ├── patch_sites.py
│   │   └── utils.py
│   ├── static
│   │   ├── dashboard
│   │   │   ├── images
│   │   │   │   ├── account-circle.svg
│   │   │   │   ├── add.svg
│   │   │   │   ├── arrow-drop-down.svg
│   │   │   │   ├── arrow-left.svg
│   │   │   │   ├── chevron-left.svg
│   │   │   │   ├── chevron-right.svg
│   │   │   │   ├── close.svg
│   │   │   │   ├── collections.svg
│   │   │   │   ├── description.svg
│   │   │   │   ├── done.svg
│   │   │   │   ├── editor
│   │   │   │   │   ├── align_center.svg
│   │   │   │   │   ├── align_justify.svg
│   │   │   │   │   ├── align_left.svg
│   │   │   │   │   ├── align_right.svg
│   │   │   │   │   ├── format_clear.svg
│   │   │   │   │   ├── insert_link.svg
│   │   │   │   │   ├── insert_photo.svg
│   │   │   │   │   └── quote.svg
│   │   │   │   ├── edit.svg
│   │   │   │   ├── email.svg
│   │   │   │   ├── help.svg
│   │   │   │   ├── history.svg
│   │   │   │   ├── logo.svg
│   │   │   │   ├── mobile-menu.svg
│   │   │   │   ├── more-vert.svg
│   │   │   │   ├── payment.svg
│   │   │   │   ├── phone.svg
│   │   │   │   ├── reorder.svg
│   │   │   │   ├── search.svg
│   │   │   │   ├── store.svg
│   │   │   │   └── style.svg
│   │   │   ├── js
│   │   │   │   ├── components
│   │   │   │   │   ├── async-form.js
│   │   │   │   │   ├── bulk-actions.js
│   │   │   │   │   ├── datepicker.js
│   │   │   │   │   ├── editor.js
│   │   │   │   │   ├── filters.js
│   │   │   │   │   ├── google-preview.js
│   │   │   │   │   ├── image-gallery.js
│   │   │   │   │   ├── index.js
│   │   │   │   │   ├── load-action.js
│   │   │   │   │   ├── messages.js
│   │   │   │   │   ├── misc.js
│   │   │   │   │   ├── modal.js
│   │   │   │   │   ├── search.js
│   │   │   │   │   ├── selects.js
│   │   │   │   │   ├── side-menu.js
│   │   │   │   │   ├── sortable.js
│   │   │   │   │   ├── tab.js
│   │   │   │   │   ├── utils.js
│   │   │   │   │   └── vouchers.js
│   │   │   │   ├── dashboard.js
│   │   │   │   └── document.js
│   │   │   └── scss
│   │   │       ├── components
│   │   │       │   ├── _breadcrumbs.scss
│   │   │       │   ├── _buttons.scss
│   │   │       │   ├── _card-collapse.scss
│   │   │       │   ├── _chars-left.scss
│   │   │       │   ├── _data-table.scss
│   │   │       │   ├── _dropzone.scss
│   │   │       │   ├── _form.scss
│   │   │       │   ├── _formset.scss
│   │   │       │   ├── _global.scss
│   │   │       │   ├── _google-preview.scss
│   │   │       │   ├── _list.scss
│   │   │       │   ├── _menu.scss
│   │   │       │   ├── _modals.scss
│   │   │       │   ├── _nav.scss
│   │   │       │   ├── _pagination.scss
│   │   │       │   ├── _ppoi.scss
│   │   │       │   ├── _product-gallery.scss
│   │   │       │   ├── _rich-text-editor.scss
│   │   │       │   ├── _search.scss
│   │   │       │   ├── _select2.scss
│   │   │       │   ├── _tabs.scss
│   │   │       │   ├── _timeline.scss
│   │   │       │   └── _zero-page.scss
│   │   │       ├── dashboard.scss
│   │   │       ├── document.scss
│   │   │       ├── layouts
│   │   │       │   ├── _orders.scss
│   │   │       │   ├── _product-details.scss
│   │   │       │   ├── _search-results.scss
│   │   │       │   └── _style-guide.scss
│   │   │       ├── print.scss
│   │   │       └── variables.scss
│   │   ├── dashboard-next
│   │   │   ├── auth
│   │   │   │   ├── AuthProvider.tsx
│   │   │   │   ├── components
│   │   │   │   │   ├── LoginLoading
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── LoginLoading.tsx
│   │   │   │   │   ├── LoginPage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── LoginPage.tsx
│   │   │   │   │   └── SectionRoute.tsx
│   │   │   │   ├── index.tsx
│   │   │   │   ├── misc.ts
│   │   │   │   ├── mutations.ts
│   │   │   │   ├── types
│   │   │   │   │   ├── TokenAuth.ts
│   │   │   │   │   ├── User.ts
│   │   │   │   │   └── VerifyToken.ts
│   │   │   │   └── views
│   │   │   │       └── Login.tsx
│   │   │   ├── Baseline.tsx
│   │   │   ├── categories
│   │   │   │   ├── components
│   │   │   │   │   ├── CategoryBackground
│   │   │   │   │   │   ├── CategoryBackground.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── CategoryCreatePage
│   │   │   │   │   │   ├── CategoryCreatePage.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── CategoryDeleteDialog
│   │   │   │   │   │   ├── CategoryDeleteDialog.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── CategoryDetailsForm
│   │   │   │   │   │   ├── CategoryDetailsForm.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── CategoryList
│   │   │   │   │   │   ├── CategoryList.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── CategoryListPage
│   │   │   │   │   │   ├── CategoryListPage.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── CategoryProducts
│   │   │   │   │   │   ├── CategoryProducts.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── CategoryProductsCard
│   │   │   │   │   │   ├── CategoryProductsCard.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   └── CategoryUpdatePage
│   │   │   │   │       ├── CategoryUpdatePage.tsx
│   │   │   │   │       └── index.ts
│   │   │   │   ├── fixtures.ts
│   │   │   │   ├── index.tsx
│   │   │   │   ├── mutations.ts
│   │   │   │   ├── queries.ts
│   │   │   │   ├── types
│   │   │   │   │   ├── CategoryBulkDelete.ts
│   │   │   │   │   ├── CategoryCreate.ts
│   │   │   │   │   ├── CategoryDelete.ts
│   │   │   │   │   ├── CategoryDetailsFragment.ts
│   │   │   │   │   ├── CategoryDetails.ts
│   │   │   │   │   ├── CategoryProperties.ts
│   │   │   │   │   ├── CategoryUpdate.ts
│   │   │   │   │   ├── RootCategories.ts
│   │   │   │   │   └── RootCategoryChildren.ts
│   │   │   │   ├── urls.ts
│   │   │   │   └── views
│   │   │   │       ├── CategoryCreate.tsx
│   │   │   │       ├── CategoryDetails.tsx
│   │   │   │       └── CategoryList.tsx
│   │   │   ├── collections
│   │   │   │   ├── components
│   │   │   │   │   ├── CollectionCreatePage
│   │   │   │   │   │   ├── CollectionCreatePage.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── CollectionDetails
│   │   │   │   │   │   ├── CollectionDetails.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── CollectionDetailsPage
│   │   │   │   │   │   ├── CollectionDetailsPage.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── CollectionImage
│   │   │   │   │   │   ├── CollectionImage.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── CollectionList
│   │   │   │   │   │   ├── CollectionList.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── CollectionListPage
│   │   │   │   │   │   ├── CollectionListPage.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── CollectionProducts
│   │   │   │   │   │   ├── CollectionProducts.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   └── CollectionStatus
│   │   │   │   │       ├── CollectionStatus.tsx
│   │   │   │   │       └── index.ts
│   │   │   │   ├── containers
│   │   │   │   │   └── CollectionOperations.tsx
│   │   │   │   ├── fixtures.ts
│   │   │   │   ├── index.tsx
│   │   │   │   ├── mutations.ts
│   │   │   │   ├── queries.ts
│   │   │   │   ├── types
│   │   │   │   │   ├── AssignHomepageCollection.ts
│   │   │   │   │   ├── CollectionAssignProduct.ts
│   │   │   │   │   ├── CollectionBulkDelete.ts
│   │   │   │   │   ├── CollectionBulkPublish.ts
│   │   │   │   │   ├── CollectionDetailsFragment.ts
│   │   │   │   │   ├── CollectionDetails.ts
│   │   │   │   │   ├── CollectionFragment.ts
│   │   │   │   │   ├── CollectionList.ts
│   │   │   │   │   ├── CollectionProductFragment.ts
│   │   │   │   │   ├── CollectionUpdate.ts
│   │   │   │   │   ├── CollectionUpdateWithHomepage.ts
│   │   │   │   │   ├── CreateCollection.ts
│   │   │   │   │   ├── RemoveCollection.ts
│   │   │   │   │   ├── SearchProducts.ts
│   │   │   │   │   └── UnassignCollectionProduct.ts
│   │   │   │   ├── urls.ts
│   │   │   │   └── views
│   │   │   │       ├── CollectionCreate.tsx
│   │   │   │       ├── CollectionDetails.tsx
│   │   │   │       └── CollectionList.tsx
│   │   │   ├── components
│   │   │   │   ├── ActionDialog
│   │   │   │   │   ├── ActionDialog.tsx
│   │   │   │   │   └── index.ts
│   │   │   │   ├── AddressEdit
│   │   │   │   │   ├── AddressEdit.tsx
│   │   │   │   │   └── index.ts
│   │   │   │   ├── AddressFormatter
│   │   │   │   │   ├── AddressFormatter.tsx
│   │   │   │   │   └── index.ts
│   │   │   │   ├── AppHeader
│   │   │   │   │   ├── AppHeader.tsx
│   │   │   │   │   └── index.ts
│   │   │   │   ├── AppLayout
│   │   │   │   │   ├── AppActionContext.tsx
│   │   │   │   │   ├── AppHeaderContext.tsx
│   │   │   │   │   ├── AppLayout.tsx
│   │   │   │   │   ├── consts.ts
│   │   │   │   │   ├── index.ts
│   │   │   │   │   ├── MenuList.tsx
│   │   │   │   │   ├── MenuNested.tsx
│   │   │   │   │   ├── menuStructure.ts
│   │   │   │   │   ├── ResponsiveDrawer.tsx
│   │   │   │   │   └── ThemeSwitch.tsx
│   │   │   │   ├── AppProgress
│   │   │   │   │   └── index.tsx
│   │   │   │   ├── AssignCategoryDialog
│   │   │   │   │   ├── AssignCategoryDialog.tsx
│   │   │   │   │   └── index.ts
│   │   │   │   ├── AssignCollectionDialog
│   │   │   │   │   ├── AssignCollectionDialog.tsx
│   │   │   │   │   └── index.ts
│   │   │   │   ├── AssignProductDialog
│   │   │   │   │   ├── AssignProductDialog.tsx
│   │   │   │   │   └── index.ts
│   │   │   │   ├── AutocompleteSelectMenu
│   │   │   │   │   ├── AutocompleteSelectMenu.test.ts
│   │   │   │   │   ├── AutocompleteSelectMenu.tsx
│   │   │   │   │   └── index.ts
│   │   │   │   ├── CardMenu
│   │   │   │   │   ├── CardMenu.tsx
│   │   │   │   │   └── index.ts
│   │   │   │   ├── CardSpacer.tsx
│   │   │   │   ├── CardTitle
│   │   │   │   │   ├── CardTitle.tsx
│   │   │   │   │   └── index.ts
│   │   │   │   ├── Checkbox
│   │   │   │   │   ├── Checkbox.tsx
│   │   │   │   │   └── index.ts
│   │   │   │   ├── Chip
│   │   │   │   │   ├── Chip.tsx
│   │   │   │   │   └── index.ts
│   │   │   │   ├── ConfirmButton
│   │   │   │   │   ├── ConfirmButton.tsx
│   │   │   │   │   └── index.ts
│   │   │   │   ├── ConfirmFormLeaveDialog.tsx
│   │   │   │   ├── Container.tsx
│   │   │   │   ├── ControlledCheckbox.tsx
│   │   │   │   ├── ControlledSwitch.tsx
│   │   │   │   ├── CountryList
│   │   │   │   │   ├── CountryList.tsx
│   │   │   │   │   └── index.ts
│   │   │   │   ├── Date
│   │   │   │   │   ├── DateContext.tsx
│   │   │   │   │   ├── DateProvider.tsx
│   │   │   │   │   ├── Date.test.tsx
│   │   │   │   │   ├── DateTime.tsx
│   │   │   │   │   ├── Date.tsx
│   │   │   │   │   └── index.ts
│   │   │   │   ├── DebounceForm.tsx
│   │   │   │   ├── Debounce.tsx
│   │   │   │   ├── DraftRenderer.tsx
│   │   │   │   ├── Dropzone.tsx
│   │   │   │   ├── EditableTableCell
│   │   │   │   │   ├── EditableTableCell.tsx
│   │   │   │   │   └── index.ts
│   │   │   │   ├── ErrorMessageCard
│   │   │   │   │   ├── ErrorMessageCard.tsx
│   │   │   │   │   └── index.ts
│   │   │   │   ├── ErrorPage
│   │   │   │   │   ├── ErrorPage.tsx
│   │   │   │   │   └── index.ts
│   │   │   │   ├── ExtendedPageHeader
│   │   │   │   │   ├── ExtendedPageHeader.tsx
│   │   │   │   │   └── index.ts
│   │   │   │   ├── ExternalLink
│   │   │   │   │   ├── ExternalLink.tsx
│   │   │   │   │   └── index.ts
│   │   │   │   ├── FileUpload
│   │   │   │   │   ├── FileUpload.tsx
│   │   │   │   │   └── index.ts
│   │   │   │   ├── FilterCard
│   │   │   │   │   ├── FilterCard.tsx
│   │   │   │   │   └── index.ts
│   │   │   │   ├── Form
│   │   │   │   │   ├── FormActions.tsx
│   │   │   │   │   ├── FormContext.tsx
│   │   │   │   │   ├── Form.tsx
│   │   │   │   │   └── index.ts
│   │   │   │   ├── FormSpacer.tsx
│   │   │   │   ├── Grid
│   │   │   │   │   ├── Grid.tsx
│   │   │   │   │   └── index.ts
│   │   │   │   ├── Hr.tsx
│   │   │   │   ├── IconButtonTableCell
│   │   │   │   │   ├── IconButtonTableCell.tsx
│   │   │   │   │   └── index.ts
│   │   │   │   ├── ImageTile
│   │   │   │   │   ├── ImageTile.tsx
│   │   │   │   │   └── index.ts
│   │   │   │   ├── ImageUpload
│   │   │   │   │   ├── ImageUpload.tsx
│   │   │   │   │   └── index.tsx
│   │   │   │   ├── LanguageSwitch
│   │   │   │   │   ├── index.ts
│   │   │   │   │   └── LanguageSwitch.tsx
│   │   │   │   ├── Link.tsx
│   │   │   │   ├── ListField
│   │   │   │   │   ├── index.ts
│   │   │   │   │   └── ListField.tsx
│   │   │   │   ├── Locale
│   │   │   │   │   ├── index.ts
│   │   │   │   │   └── Locale.tsx
│   │   │   │   ├── MenuToggle.tsx
│   │   │   │   ├── messages
│   │   │   │   │   ├── index.ts
│   │   │   │   │   └── MessageManager.tsx
│   │   │   │   ├── Money
│   │   │   │   │   ├── index.ts
│   │   │   │   │   └── Money.tsx
│   │   │   │   ├── MoneyRange
│   │   │   │   │   ├── index.ts
│   │   │   │   │   └── MoneyRange.tsx
│   │   │   │   ├── MultiAutocompleteSelectField
│   │   │   │   │   ├── index.ts
│   │   │   │   │   └── MultiAutocompleteSelectField.tsx
│   │   │   │   ├── MultiSelectField
│   │   │   │   │   ├── index.ts
│   │   │   │   │   └── MultiSelectField.tsx
│   │   │   │   ├── NotFoundPage
│   │   │   │   │   ├── index.ts
│   │   │   │   │   └── NotFoundPage.tsx
│   │   │   │   ├── PageHeader
│   │   │   │   │   ├── index.ts
│   │   │   │   │   └── PageHeader.tsx
│   │   │   │   ├── Percent
│   │   │   │   │   ├── index.ts
│   │   │   │   │   └── Percent.tsx
│   │   │   │   ├── PhoneField
│   │   │   │   │   ├── index.ts
│   │   │   │   │   └── PhoneField.tsx
│   │   │   │   ├── PriceField
│   │   │   │   │   ├── index.ts
│   │   │   │   │   └── PriceField.tsx
│   │   │   │   ├── ProductList
│   │   │   │   │   ├── index.ts
│   │   │   │   │   └── ProductList.tsx
│   │   │   │   ├── RichTextEditor
│   │   │   │   │   ├── ImageEntity.tsx
│   │   │   │   │   ├── ImageSource.tsx
│   │   │   │   │   ├── index.ts
│   │   │   │   │   ├── LinkEntity.tsx
│   │   │   │   │   ├── LinkSource.tsx
│   │   │   │   │   └── RichTextEditor.tsx
│   │   │   │   ├── SaveButtonBar
│   │   │   │   │   ├── index.ts
│   │   │   │   │   └── SaveButtonBar.tsx
│   │   │   │   ├── SeoForm
│   │   │   │   │   ├── index.ts
│   │   │   │   │   └── SeoForm.tsx
│   │   │   │   ├── Shop
│   │   │   │   │   ├── index.tsx
│   │   │   │   │   ├── query.ts
│   │   │   │   │   └── types
│   │   │   │   │       └── ShopInfo.ts
│   │   │   │   ├── SingleAutocompleteSelectField
│   │   │   │   │   ├── index.ts
│   │   │   │   │   └── SingleAutocompleteSelectField.tsx
│   │   │   │   ├── SingleSelectField
│   │   │   │   │   ├── index.ts
│   │   │   │   │   └── SingleSelectField.tsx
│   │   │   │   ├── Skeleton.tsx
│   │   │   │   ├── StatusLabel
│   │   │   │   │   ├── index.ts
│   │   │   │   │   └── StatusLabel.tsx
│   │   │   │   ├── Tab
│   │   │   │   │   ├── index.ts
│   │   │   │   │   ├── TabContainer.tsx
│   │   │   │   │   ├── Tabs.tsx
│   │   │   │   │   └── Tab.tsx
│   │   │   │   ├── TableCellAvatar
│   │   │   │   │   ├── index.ts
│   │   │   │   │   └── TableCellAvatar.tsx
│   │   │   │   ├── TableFilter
│   │   │   │   │   ├── FilterChips.tsx
│   │   │   │   │   ├── FilterTabs.tsx
│   │   │   │   │   ├── FilterTab.tsx
│   │   │   │   │   └── index.ts
│   │   │   │   ├── TableHead
│   │   │   │   │   ├── index.ts
│   │   │   │   │   └── TableHead.tsx
│   │   │   │   ├── TablePagination
│   │   │   │   │   ├── index.ts
│   │   │   │   │   ├── TablePaginationActions.tsx
│   │   │   │   │   └── TablePagination.tsx
│   │   │   │   ├── TextFieldWithChoice
│   │   │   │   │   ├── index.ts
│   │   │   │   │   └── TextFieldWithChoice.tsx
│   │   │   │   ├── Theme
│   │   │   │   │   ├── index.ts
│   │   │   │   │   └── ThemeProvider.tsx
│   │   │   │   ├── Timeline
│   │   │   │   │   ├── index.ts
│   │   │   │   │   ├── TimelineEvent.tsx
│   │   │   │   │   ├── TimelineNote.tsx
│   │   │   │   │   └── Timeline.tsx
│   │   │   │   ├── Timezone
│   │   │   │   │   ├── index.ts
│   │   │   │   │   └── Timezone.tsx
│   │   │   │   ├── Weight
│   │   │   │   │   ├── index.ts
│   │   │   │   │   └── Weight.tsx
│   │   │   │   ├── WeightRange
│   │   │   │   │   ├── index.ts
│   │   │   │   │   └── WeightRange.tsx
│   │   │   │   └── WindowTitle
│   │   │   │       └── index.tsx
│   │   │   ├── config.ts
│   │   │   ├── configuration
│   │   │   │   ├── ConfigurationPage.tsx
│   │   │   │   └── index.tsx
│   │   │   ├── containers
│   │   │   │   ├── SearchCategories
│   │   │   │   │   ├── index.tsx
│   │   │   │   │   ├── query.ts
│   │   │   │   │   └── types
│   │   │   │   │       └── SearchCategories.ts
│   │   │   │   ├── SearchCollections
│   │   │   │   │   ├── index.tsx
│   │   │   │   │   ├── query.ts
│   │   │   │   │   └── types
│   │   │   │   │       └── SearchCollections.ts
│   │   │   │   ├── SearchPages
│   │   │   │   │   ├── index.tsx
│   │   │   │   │   ├── query.ts
│   │   │   │   │   └── types
│   │   │   │   │       └── SearchPages.ts
│   │   │   │   └── SearchProducts
│   │   │   │       ├── index.tsx
│   │   │   │       ├── query.ts
│   │   │   │       └── types
│   │   │   │           └── SearchProducts.ts
│   │   │   ├── customers
│   │   │   │   ├── components
│   │   │   │   │   ├── CustomerAddress
│   │   │   │   │   │   ├── CustomerAddress.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── CustomerAddressDialog
│   │   │   │   │   │   ├── CustomerAddressDialog.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── CustomerAddresses
│   │   │   │   │   │   ├── CustomerAddresses.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── CustomerAddressListPage
│   │   │   │   │   │   ├── CustomerAddressListPage.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── CustomerCreateAddress
│   │   │   │   │   │   ├── CustomerCreateAddress.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── CustomerCreateDetails
│   │   │   │   │   │   ├── CustomerCreateDetails.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── CustomerCreateNote
│   │   │   │   │   │   ├── CustomerCreateNote.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── CustomerCreatePage
│   │   │   │   │   │   ├── CustomerCreatePage.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── CustomerDetails
│   │   │   │   │   │   ├── CustomerDetails.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── CustomerDetailsPage
│   │   │   │   │   │   ├── CustomerDetailsPage.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── CustomerList
│   │   │   │   │   │   ├── CustomerList.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── CustomerListPage
│   │   │   │   │   │   ├── CustomerListPage.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── CustomerOrders
│   │   │   │   │   │   ├── CustomerOrders.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   └── CustomerStats
│   │   │   │   │       ├── CustomerStats.tsx
│   │   │   │   │       └── index.ts
│   │   │   │   ├── fixtures.ts
│   │   │   │   ├── index.tsx
│   │   │   │   ├── mutations.ts
│   │   │   │   ├── queries.ts
│   │   │   │   ├── types
│   │   │   │   │   ├── BulkRemoveCustomers.ts
│   │   │   │   │   ├── CreateCustomerAddress.ts
│   │   │   │   │   ├── CreateCustomer.ts
│   │   │   │   │   ├── CustomerAddressesFragment.ts
│   │   │   │   │   ├── CustomerAddresses.ts
│   │   │   │   │   ├── CustomerCreateData.ts
│   │   │   │   │   ├── CustomerDetailsFragment.ts
│   │   │   │   │   ├── CustomerDetails.ts
│   │   │   │   │   ├── CustomerFragment.ts
│   │   │   │   │   ├── ListCustomers.ts
│   │   │   │   │   ├── RemoveCustomerAddress.ts
│   │   │   │   │   ├── RemoveCustomer.ts
│   │   │   │   │   ├── SetCustomerDefaultAddress.ts
│   │   │   │   │   ├── UpdateCustomerAddress.ts
│   │   │   │   │   └── UpdateCustomer.ts
│   │   │   │   ├── types.ts
│   │   │   │   ├── urls.ts
│   │   │   │   └── views
│   │   │   │       ├── CustomerAddresses.tsx
│   │   │   │       ├── CustomerCreate.tsx
│   │   │   │       ├── CustomerDetails.tsx
│   │   │   │       └── CustomerList.tsx
│   │   │   ├── discounts
│   │   │   │   ├── components
│   │   │   │   │   ├── DiscountCategories
│   │   │   │   │   │   ├── DiscountCategories.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── DiscountCollections
│   │   │   │   │   │   ├── DiscountCollections.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── DiscountCountrySelectDialog
│   │   │   │   │   │   ├── DiscountCountrySelectDialog.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── DiscountProducts
│   │   │   │   │   │   ├── DiscountProducts.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── SaleCreatePage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── SaleCreatePage.tsx
│   │   │   │   │   ├── SaleDetailsPage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── SaleDetailsPage.tsx
│   │   │   │   │   ├── SaleInfo
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── SaleInfo.tsx
│   │   │   │   │   ├── SaleList
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── SaleList.tsx
│   │   │   │   │   ├── SaleListPage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── SaleListPage.tsx
│   │   │   │   │   ├── SalePricing
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── SalePricing.tsx
│   │   │   │   │   ├── SaleSummary
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── SaleSummary.tsx
│   │   │   │   │   ├── VoucherCreatePage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── VoucherCreatePage.tsx
│   │   │   │   │   ├── VoucherDetailsPage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── VoucherDetailsPage.tsx
│   │   │   │   │   ├── VoucherInfo
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── VoucherInfo.tsx
│   │   │   │   │   ├── VoucherList
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── VoucherList.tsx
│   │   │   │   │   ├── VoucherListPage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── VoucherListPage.tsx
│   │   │   │   │   ├── VoucherOptions
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── VoucherOptions.tsx
│   │   │   │   │   └── VoucherSummary
│   │   │   │   │       ├── index.ts
│   │   │   │   │       └── VoucherSummary.tsx
│   │   │   │   ├── fixtures.ts
│   │   │   │   ├── index.tsx
│   │   │   │   ├── mutations.ts
│   │   │   │   ├── queries.ts
│   │   │   │   ├── translations.ts
│   │   │   │   ├── types
│   │   │   │   │   ├── SaleBulkDelete.ts
│   │   │   │   │   ├── SaleCataloguesAdd.ts
│   │   │   │   │   ├── SaleCataloguesRemove.ts
│   │   │   │   │   ├── SaleCreate.ts
│   │   │   │   │   ├── SaleDelete.ts
│   │   │   │   │   ├── SaleDetailsFragment.ts
│   │   │   │   │   ├── SaleDetails.ts
│   │   │   │   │   ├── SaleFragment.ts
│   │   │   │   │   ├── SaleList.ts
│   │   │   │   │   ├── SaleUpdate.ts
│   │   │   │   │   ├── VoucherBulkDelete.ts
│   │   │   │   │   ├── VoucherCataloguesAdd.ts
│   │   │   │   │   ├── VoucherCataloguesRemove.ts
│   │   │   │   │   ├── VoucherCreate.ts
│   │   │   │   │   ├── VoucherDelete.ts
│   │   │   │   │   ├── VoucherDetailsFragment.ts
│   │   │   │   │   ├── VoucherDetails.ts
│   │   │   │   │   ├── VoucherFragment.ts
│   │   │   │   │   ├── VoucherList.ts
│   │   │   │   │   └── VoucherUpdate.ts
│   │   │   │   ├── urls.ts
│   │   │   │   └── views
│   │   │   │       ├── SaleCreate.tsx
│   │   │   │       ├── SaleDetails.tsx
│   │   │   │       ├── SaleList.tsx
│   │   │   │       ├── VoucherCreate.tsx
│   │   │   │       ├── VoucherDetails.tsx
│   │   │   │       └── VoucherList.tsx
│   │   │   ├── fixtures.ts
│   │   │   ├── home
│   │   │   │   ├── components
│   │   │   │   │   ├── HomeActivityCard
│   │   │   │   │   │   ├── activityMessages.ts
│   │   │   │   │   │   ├── HomeActivityCard.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── HomeAnalyticsCard
│   │   │   │   │   │   ├── HomeAnalyticsCard.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── HomeHeader
│   │   │   │   │   │   ├── HomeHeader.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── HomeNotificationTable
│   │   │   │   │   │   ├── HomeNotificationTable.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── HomePage
│   │   │   │   │   │   ├── HomePage.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── HomeProductListCard
│   │   │   │   │   │   ├── HomeProductListCard.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   └── HomeScreen.tsx
│   │   │   │   ├── fixtures.ts
│   │   │   │   ├── index.tsx
│   │   │   │   ├── queries.ts
│   │   │   │   ├── types
│   │   │   │   │   └── Home.ts
│   │   │   │   └── views
│   │   │   │       └── index.tsx
│   │   │   ├── hooks
│   │   │   │   ├── useBulkActions.ts
│   │   │   │   ├── useNavigator.ts
│   │   │   │   ├── useNotifier.ts
│   │   │   │   ├── usePaginator.ts
│   │   │   │   ├── useScroll.ts
│   │   │   │   ├── useShop.ts
│   │   │   │   ├── useTheme.ts
│   │   │   │   └── useUser.ts
│   │   │   ├── i18n.ts
│   │   │   ├── icons
│   │   │   │   ├── AccountCircle.tsx
│   │   │   │   ├── ArrowDropdown.tsx
│   │   │   │   ├── Ballot.tsx
│   │   │   │   ├── BoldIcon.tsx
│   │   │   │   ├── Draggable.tsx
│   │   │   │   ├── Folder.tsx
│   │   │   │   ├── HeaderOne.tsx
│   │   │   │   ├── HeaderThree.tsx
│   │   │   │   ├── HeaderTwo.tsx
│   │   │   │   ├── Home.tsx
│   │   │   │   ├── Image.tsx
│   │   │   │   ├── ItalicIcon.tsx
│   │   │   │   ├── LinkIcon.tsx
│   │   │   │   ├── LocalShipping.tsx
│   │   │   │   ├── Monetization.tsx
│   │   │   │   ├── Moon.tsx
│   │   │   │   ├── Navigation.tsx
│   │   │   │   ├── NoPhoto.tsx
│   │   │   │   ├── OrderedListIcon.tsx
│   │   │   │   ├── Orders.tsx
│   │   │   │   ├── Pages.tsx
│   │   │   │   ├── ProductTypes.tsx
│   │   │   │   ├── QuotationIcon.tsx
│   │   │   │   ├── Sales.tsx
│   │   │   │   ├── ShippingMethods.tsx
│   │   │   │   ├── Shop.tsx
│   │   │   │   ├── SiteSettings.tsx
│   │   │   │   ├── StaffMembers.tsx
│   │   │   │   ├── StoreMall.tsx
│   │   │   │   ├── StrikethroughIcon.tsx
│   │   │   │   ├── Sun.tsx
│   │   │   │   ├── Taxes.tsx
│   │   │   │   ├── Truck.tsx
│   │   │   │   ├── UnorderedListIcon.tsx
│   │   │   │   └── Unstyled.tsx
│   │   │   ├── index.tsx
│   │   │   ├── misc.ts
│   │   │   ├── mutations.tsx
│   │   │   ├── navigation
│   │   │   │   ├── components
│   │   │   │   │   ├── MenuCreateDialog
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── MenuCreateDialog.tsx
│   │   │   │   │   ├── MenuDetailsPage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   ├── MenuDetailsPage.tsx
│   │   │   │   │   │   ├── __snapshots__
│   │   │   │   │   │   │   └── tree.test.ts.snap
│   │   │   │   │   │   ├── tree.test.ts
│   │   │   │   │   │   └── tree.ts
│   │   │   │   │   ├── MenuItemDialog
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── MenuItemDialog.tsx
│   │   │   │   │   ├── MenuItems
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   ├── MenuItems.tsx
│   │   │   │   │   │   ├── __snapshots__
│   │   │   │   │   │   │   └── tree.test.ts.snap
│   │   │   │   │   │   ├── tree.test.ts
│   │   │   │   │   │   └── tree.ts
│   │   │   │   │   ├── MenuList
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── MenuList.tsx
│   │   │   │   │   ├── MenuListPage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── MenuListPage.tsx
│   │   │   │   │   └── MenuProperties
│   │   │   │   │       ├── index.ts
│   │   │   │   │       └── MenuProperties.tsx
│   │   │   │   ├── fixtures.ts
│   │   │   │   ├── index.tsx
│   │   │   │   ├── mutations.ts
│   │   │   │   ├── queries.ts
│   │   │   │   ├── types
│   │   │   │   │   ├── MenuBulkDelete.ts
│   │   │   │   │   ├── MenuCreate.ts
│   │   │   │   │   ├── MenuDelete.ts
│   │   │   │   │   ├── MenuDetailsFragment.ts
│   │   │   │   │   ├── MenuDetails.ts
│   │   │   │   │   ├── MenuFragment.ts
│   │   │   │   │   ├── MenuItemCreate.ts
│   │   │   │   │   ├── MenuItemFragment.ts
│   │   │   │   │   ├── MenuItemNestedFragment.ts
│   │   │   │   │   ├── MenuItemUpdate.ts
│   │   │   │   │   ├── MenuList.ts
│   │   │   │   │   └── MenuUpdate.ts
│   │   │   │   ├── urls.ts
│   │   │   │   └── views
│   │   │   │       ├── MenuDetails
│   │   │   │       │   ├── index.tsx
│   │   │   │       │   ├── successHandlers.ts
│   │   │   │       │   └── utils.ts
│   │   │   │       └── MenuList.tsx
│   │   │   ├── NotFound.tsx
│   │   │   ├── orders
│   │   │   │   ├── components
│   │   │   │   │   ├── OrderAddressEditDialog
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── OrderAddressEditDialog.tsx
│   │   │   │   │   ├── OrderBulkCancelDialog
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── OrderBulkCancelDialog.tsx
│   │   │   │   │   ├── OrderCancelDialog
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── OrderCancelDialog.tsx
│   │   │   │   │   ├── OrderCustomer
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── OrderCustomer.tsx
│   │   │   │   │   ├── OrderCustomerEditDialog
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── OrderCustomerEditDialog.tsx
│   │   │   │   │   ├── OrderCustomerNote
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── OrderCustomerNote.tsx
│   │   │   │   │   ├── OrderDetailsPage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── OrderDetailsPage.tsx
│   │   │   │   │   ├── OrderDraftCancelDialog
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── OrderDraftCancelDialog.tsx
│   │   │   │   │   ├── OrderDraftDetails
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── OrderDraftDetails.tsx
│   │   │   │   │   ├── OrderDraftDetailsProducts
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── OrderDraftDetailsProducts.tsx
│   │   │   │   │   ├── OrderDraftDetailsSummary
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── OrderDraftDetailsSummary.tsx
│   │   │   │   │   ├── OrderDraftFinalizeDialog
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── OrderDraftFinalizeDialog.tsx
│   │   │   │   │   ├── OrderDraftList
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── OrderDraftList.tsx
│   │   │   │   │   ├── OrderDraftListPage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── OrderDraftListPage.tsx
│   │   │   │   │   ├── OrderDraftPage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── OrderDraftPage.tsx
│   │   │   │   │   ├── OrderFulfillment
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── OrderFulfillment.tsx
│   │   │   │   │   ├── OrderFulfillmentCancelDialog
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── OrderFulfillmentCancelDialog.tsx
│   │   │   │   │   ├── OrderFulfillmentDialog
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── OrderFulfillmentDialog.tsx
│   │   │   │   │   ├── OrderFulfillmentTrackingDialog
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── OrderFulfillmentTrackingDialog.tsx
│   │   │   │   │   ├── OrderHistory
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── OrderHistory.tsx
│   │   │   │   │   ├── OrderList
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── OrderList.tsx
│   │   │   │   │   ├── OrderListFilter
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── OrderListFilter.tsx
│   │   │   │   │   ├── OrderListPage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── OrderListPage.tsx
│   │   │   │   │   ├── OrderMarkAsPaidDialog
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── OrderMarkAsPaidDialog.tsx
│   │   │   │   │   ├── OrderPayment
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── OrderPayment.tsx
│   │   │   │   │   ├── OrderPaymentDialog
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── OrderPaymentDialog.tsx
│   │   │   │   │   ├── OrderPaymentVoidDialog
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── OrderPaymentVoidDialog.tsx
│   │   │   │   │   ├── OrderProductAddDialog
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── OrderProductAddDialog.tsx
│   │   │   │   │   ├── OrderShippingMethodEditDialog
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── OrderShippingMethodEditDialog.tsx
│   │   │   │   │   └── OrderUnfulfilledItems
│   │   │   │   │       ├── index.ts
│   │   │   │   │       └── OrderUnfulfilledItems.tsx
│   │   │   │   ├── containers
│   │   │   │   │   ├── OrderOperations.tsx
│   │   │   │   │   ├── OrderVariantSearch.tsx
│   │   │   │   │   └── UserSearch.tsx
│   │   │   │   ├── fixtures.ts
│   │   │   │   ├── index.tsx
│   │   │   │   ├── misc.ts
│   │   │   │   ├── mutations.ts
│   │   │   │   ├── queries.ts
│   │   │   │   ├── types
│   │   │   │   │   ├── AddressFragment.ts
│   │   │   │   │   ├── OrderAddNote.ts
│   │   │   │   │   ├── OrderBulkCancel.ts
│   │   │   │   │   ├── OrderCancel.ts
│   │   │   │   │   ├── OrderCapture.ts
│   │   │   │   │   ├── OrderCreateFulfillment.ts
│   │   │   │   │   ├── OrderDetailsFragment.ts
│   │   │   │   │   ├── OrderDetails.ts
│   │   │   │   │   ├── OrderDraftBulkCancel.ts
│   │   │   │   │   ├── OrderDraftCancel.ts
│   │   │   │   │   ├── OrderDraftCreate.ts
│   │   │   │   │   ├── OrderDraftFinalize.ts
│   │   │   │   │   ├── OrderDraftList.ts
│   │   │   │   │   ├── OrderDraftUpdate.ts
│   │   │   │   │   ├── OrderEventFragment.ts
│   │   │   │   │   ├── OrderFulfillmentCancel.ts
│   │   │   │   │   ├── OrderFulfillmentUpdateTracking.ts
│   │   │   │   │   ├── OrderLineDelete.ts
│   │   │   │   │   ├── OrderLineFragment.ts
│   │   │   │   │   ├── OrderLinesAdd.ts
│   │   │   │   │   ├── OrderLineUpdate.ts
│   │   │   │   │   ├── OrderList.ts
│   │   │   │   │   ├── OrderMarkAsPaid.ts
│   │   │   │   │   ├── OrderRefund.ts
│   │   │   │   │   ├── OrderRelease.ts
│   │   │   │   │   ├── OrderShippingMethods.ts
│   │   │   │   │   ├── OrderShippingMethodUpdate.ts
│   │   │   │   │   ├── OrderUpdate.ts
│   │   │   │   │   ├── OrderVariantSearch.ts
│   │   │   │   │   ├── OrderVoid.ts
│   │   │   │   │   └── UserSearch.ts
│   │   │   │   ├── urls.ts
│   │   │   │   └── views
│   │   │   │       ├── OrderDetails
│   │   │   │       │   ├── index.tsx
│   │   │   │       │   └── OrderDetailsMessages.tsx
│   │   │   │       ├── OrderDraftList.tsx
│   │   │   │       └── OrderList.tsx
│   │   │   ├── pages
│   │   │   │   ├── components
│   │   │   │   │   ├── PageAvailability
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── PageAvailability.tsx
│   │   │   │   │   ├── PageDetailsPage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── PageDetailsPage.tsx
│   │   │   │   │   ├── PageInfo
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── PageInfo.tsx
│   │   │   │   │   ├── PageList
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── PageList.tsx
│   │   │   │   │   ├── PageListPage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── PageListPage.tsx
│   │   │   │   │   └── PageSlug
│   │   │   │   │       ├── index.ts
│   │   │   │   │       └── PageSlug.tsx
│   │   │   │   ├── fixtures.ts
│   │   │   │   ├── index.tsx
│   │   │   │   ├── mutations.ts
│   │   │   │   ├── queries.ts
│   │   │   │   ├── types
│   │   │   │   │   ├── PageBulkPublish.ts
│   │   │   │   │   ├── PageBulkRemove.ts
│   │   │   │   │   ├── PageCreate.ts
│   │   │   │   │   ├── PageDetailsFragment.ts
│   │   │   │   │   ├── PageDetails.ts
│   │   │   │   │   ├── PageFragment.ts
│   │   │   │   │   ├── PageList.ts
│   │   │   │   │   ├── PageRemove.ts
│   │   │   │   │   └── PageUpdate.ts
│   │   │   │   ├── urls.ts
│   │   │   │   └── views
│   │   │   │       ├── PageCreate.tsx
│   │   │   │       ├── PageDetails.tsx
│   │   │   │       └── PageList.tsx
│   │   │   ├── products
│   │   │   │   ├── components
│   │   │   │   │   ├── ProductAvailabilityForm
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductAvailabilityForm.tsx
│   │   │   │   │   ├── ProductCategoryAndCollectionsForm
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductCategoryAndCollectionsForm.tsx
│   │   │   │   │   ├── ProductCreatePage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductCreatePage.tsx
│   │   │   │   │   ├── ProductDetailsForm
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductDetailsForm.tsx
│   │   │   │   │   ├── ProductImageNavigation
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductImageNavigation.tsx
│   │   │   │   │   ├── ProductImagePage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductImagePage.tsx
│   │   │   │   │   ├── ProductImages
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductImages.tsx
│   │   │   │   │   ├── ProductListCard
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductListCard.tsx
│   │   │   │   │   ├── ProductListFilter
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductListFilter.tsx
│   │   │   │   │   ├── ProductOrganization
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductOrganization.tsx
│   │   │   │   │   ├── ProductPricing
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductPricing.tsx
│   │   │   │   │   ├── ProductStock
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductStock.tsx
│   │   │   │   │   ├── ProductUpdatePage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductUpdatePage.tsx
│   │   │   │   │   ├── ProductVariantAttributes
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductVariantAttributes.tsx
│   │   │   │   │   ├── ProductVariantCreatePage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductVariantCreatePage.tsx
│   │   │   │   │   ├── ProductVariantDeleteDialog
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductVariantDeleteDialog.tsx
│   │   │   │   │   ├── ProductVariantImages
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductVariantImages.tsx
│   │   │   │   │   ├── ProductVariantImageSelectDialog
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductVariantImageSelectDialog.tsx
│   │   │   │   │   ├── ProductVariantNavigation
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductVariantNavigation.tsx
│   │   │   │   │   ├── ProductVariantPage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductVariantPage.tsx
│   │   │   │   │   ├── ProductVariantPrice
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductVariantPrice.tsx
│   │   │   │   │   ├── ProductVariants
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductVariants.tsx
│   │   │   │   │   └── ProductVariantStock
│   │   │   │   │       ├── index.ts
│   │   │   │   │       └── ProductVariantStock.tsx
│   │   │   │   ├── containers
│   │   │   │   │   ├── CategorySearch.tsx
│   │   │   │   │   ├── CollectionSearch.tsx
│   │   │   │   │   ├── ProductImagesReorder.tsx
│   │   │   │   │   ├── ProductUpdateOperations.tsx
│   │   │   │   │   └── ProductVariantOperations.tsx
│   │   │   │   ├── fixtures.ts
│   │   │   │   ├── index.tsx
│   │   │   │   ├── misc.ts
│   │   │   │   ├── mutations.ts
│   │   │   │   ├── queries.ts
│   │   │   │   ├── types
│   │   │   │   │   ├── CategorySearch.ts
│   │   │   │   │   ├── CollectionSearch.ts
│   │   │   │   │   ├── Money.ts
│   │   │   │   │   ├── productBulkDelete.ts
│   │   │   │   │   ├── productBulkPublish.ts
│   │   │   │   │   ├── ProductCreateData.ts
│   │   │   │   │   ├── ProductCreate.ts
│   │   │   │   │   ├── ProductDelete.ts
│   │   │   │   │   ├── ProductDetails.ts
│   │   │   │   │   ├── ProductFragment.ts
│   │   │   │   │   ├── ProductImageById.ts
│   │   │   │   │   ├── ProductImageCreate.ts
│   │   │   │   │   ├── ProductImageDelete.ts
│   │   │   │   │   ├── ProductImageFragment.ts
│   │   │   │   │   ├── ProductImageReorder.ts
│   │   │   │   │   ├── ProductImage.ts
│   │   │   │   │   ├── ProductImageUpdate.ts
│   │   │   │   │   ├── ProductList.ts
│   │   │   │   │   ├── Product.ts
│   │   │   │   │   ├── ProductUpdate.ts
│   │   │   │   │   ├── ProductVariantBulkDelete.ts
│   │   │   │   │   ├── ProductVariantCreateData.ts
│   │   │   │   │   ├── ProductVariantDetails.ts
│   │   │   │   │   ├── ProductVariant.ts
│   │   │   │   │   ├── SimpleProductUpdate.ts
│   │   │   │   │   ├── VariantCreate.ts
│   │   │   │   │   ├── VariantDelete.ts
│   │   │   │   │   ├── VariantImageAssign.ts
│   │   │   │   │   ├── VariantImageUnassign.ts
│   │   │   │   │   └── VariantUpdate.ts
│   │   │   │   ├── urls.ts
│   │   │   │   └── views
│   │   │   │       ├── ProductCreate.tsx
│   │   │   │       ├── ProductImage.tsx
│   │   │   │       ├── ProductList.tsx
│   │   │   │       ├── ProductUpdate.tsx
│   │   │   │       ├── ProductVariantCreate.tsx
│   │   │   │       └── ProductVariant.tsx
│   │   │   ├── productTypes
│   │   │   │   ├── components
│   │   │   │   │   ├── ProductTypeAttributeEditDialog
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductTypeAttributeEditDialog.tsx
│   │   │   │   │   ├── ProductTypeAttributes
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductTypeAttributes.tsx
│   │   │   │   │   ├── ProductTypeCreatePage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductTypeCreatePage.tsx
│   │   │   │   │   ├── ProductTypeDetails
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductTypeDetails.tsx
│   │   │   │   │   ├── ProductTypeDetailsPage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductTypeDetailsPage.tsx
│   │   │   │   │   ├── ProductTypeList
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductTypeList.tsx
│   │   │   │   │   ├── ProductTypeListPage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductTypeListPage.tsx
│   │   │   │   │   ├── ProductTypeShipping
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ProductTypeShipping.tsx
│   │   │   │   │   └── ProductTypeTaxes
│   │   │   │   │       ├── index.ts
│   │   │   │   │       └── ProductTypeTaxes.tsx
│   │   │   │   ├── containers
│   │   │   │   │   ├── AttributeSearch.tsx
│   │   │   │   │   └── ProductTypeOperations.tsx
│   │   │   │   ├── fixtures.ts
│   │   │   │   ├── index.tsx
│   │   │   │   ├── mutations.ts
│   │   │   │   ├── queries.ts
│   │   │   │   ├── types
│   │   │   │   │   ├── AttributeCreate.ts
│   │   │   │   │   ├── AttributeDelete.ts
│   │   │   │   │   ├── AttributeFragment.ts
│   │   │   │   │   ├── AttributeUpdate.ts
│   │   │   │   │   ├── ProductTypeBulkDelete.ts
│   │   │   │   │   ├── ProductTypeCreateData.ts
│   │   │   │   │   ├── ProductTypeCreate.ts
│   │   │   │   │   ├── ProductTypeDelete.ts
│   │   │   │   │   ├── ProductTypeDetailsFragment.ts
│   │   │   │   │   ├── ProductTypeDetails.ts
│   │   │   │   │   ├── ProductTypeFragment.ts
│   │   │   │   │   ├── ProductTypeList.ts
│   │   │   │   │   ├── ProductTypeUpdate.ts
│   │   │   │   │   └── SearchAttribute.ts
│   │   │   │   ├── urls.ts
│   │   │   │   └── views
│   │   │   │       ├── ProductTypeCreate.tsx
│   │   │   │       ├── ProductTypeList.tsx
│   │   │   │       └── ProductTypeUpdate
│   │   │   │           ├── errors.tsx
│   │   │   │           ├── index.tsx
│   │   │   │           └── urls.ts
│   │   │   ├── queries.tsx
│   │   │   ├── shipping
│   │   │   │   ├── components
│   │   │   │   │   ├── ShippingWeightUnitForm
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ShippingWeightUnitForm.tsx
│   │   │   │   │   ├── ShippingZoneCountriesAssignDialog
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ShippingZoneCountriesAssignDialog.tsx
│   │   │   │   │   ├── ShippingZoneCreatePage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ShippingZoneCreatePage.tsx
│   │   │   │   │   ├── ShippingZoneDetailsPage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ShippingZoneDetailsPage.tsx
│   │   │   │   │   ├── ShippingZoneInfo
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ShippingZoneInfo.tsx
│   │   │   │   │   ├── ShippingZoneRateDialog
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ShippingZoneRateDialog.tsx
│   │   │   │   │   ├── ShippingZoneRates
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ShippingZoneRates.tsx
│   │   │   │   │   ├── ShippingZonesList
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── ShippingZonesList.tsx
│   │   │   │   │   └── ShippingZonesListPage
│   │   │   │   │       ├── index.ts
│   │   │   │   │       └── ShippingZonesListPage.tsx
│   │   │   │   ├── fixtures.ts
│   │   │   │   ├── index.tsx
│   │   │   │   ├── mutations.ts
│   │   │   │   ├── queries.ts
│   │   │   │   ├── types
│   │   │   │   │   ├── BulkDeleteShippingRate.ts
│   │   │   │   │   ├── BulkDeleteShippingZone.ts
│   │   │   │   │   ├── CreateShippingRate.ts
│   │   │   │   │   ├── CreateShippingZone.ts
│   │   │   │   │   ├── DeleteShippingRate.ts
│   │   │   │   │   ├── DeleteShippingZone.ts
│   │   │   │   │   ├── ShippingMethodFragment.ts
│   │   │   │   │   ├── ShippingZoneDetailsFragment.ts
│   │   │   │   │   ├── ShippingZoneFragment.ts
│   │   │   │   │   ├── ShippingZones.ts
│   │   │   │   │   ├── ShippingZone.ts
│   │   │   │   │   ├── UpdateDefaultWeightUnit.ts
│   │   │   │   │   ├── UpdateShippingRate.ts
│   │   │   │   │   └── UpdateShippingZone.ts
│   │   │   │   ├── urls.ts
│   │   │   │   └── views
│   │   │   │       ├── ShippingZoneCreate.tsx
│   │   │   │       ├── ShippingZoneDetails
│   │   │   │       │   ├── index.tsx
│   │   │   │       │   ├── ShippingZoneDetailsDialogs.tsx
│   │   │   │       │   └── ShippingZoneOperations.tsx
│   │   │   │       └── ShippingZonesList.tsx
│   │   │   ├── siteSettings
│   │   │   │   ├── components
│   │   │   │   │   ├── SiteSettingsDetails
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── SiteSettingsDetails.tsx
│   │   │   │   │   ├── SiteSettingsKeyDialog
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── SiteSettingsKeyDialog.tsx
│   │   │   │   │   ├── SiteSettingsKeys
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── SiteSettingsKeys.tsx
│   │   │   │   │   └── SiteSettingsPage
│   │   │   │   │       ├── index.ts
│   │   │   │   │       └── SiteSettingsPage.tsx
│   │   │   │   ├── fixtures.ts
│   │   │   │   ├── index.tsx
│   │   │   │   ├── mutations.ts
│   │   │   │   ├── queries.ts
│   │   │   │   ├── types
│   │   │   │   │   ├── AuthorizationKeyAdd.ts
│   │   │   │   │   ├── AuthorizationKeyDelete.ts
│   │   │   │   │   ├── ShopFragment.ts
│   │   │   │   │   ├── ShopSettingsUpdate.ts
│   │   │   │   │   └── SiteSettings.ts
│   │   │   │   ├── urls.ts
│   │   │   │   └── views
│   │   │   │       └── index.tsx
│   │   │   ├── staff
│   │   │   │   ├── components
│   │   │   │   │   ├── StaffAddMemberDialog
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── StaffAddMemberDialog.tsx
│   │   │   │   │   ├── StaffDetailsPage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── StaffDetailsPage.tsx
│   │   │   │   │   ├── StaffList
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── StaffList.tsx
│   │   │   │   │   ├── StaffListPage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── StaffListPage.tsx
│   │   │   │   │   ├── StaffPermissions
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── StaffPermissions.tsx
│   │   │   │   │   ├── StaffProperties
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── StaffProperties.tsx
│   │   │   │   │   └── StaffStatus
│   │   │   │   │       ├── index.ts
│   │   │   │   │       └── StaffStatus.tsx
│   │   │   │   ├── fixtures.ts
│   │   │   │   ├── index.tsx
│   │   │   │   ├── mutations.ts
│   │   │   │   ├── queries.ts
│   │   │   │   ├── types
│   │   │   │   │   ├── StaffAvatarDelete.ts
│   │   │   │   │   ├── StaffAvatarUpdate.ts
│   │   │   │   │   ├── StaffList.ts
│   │   │   │   │   ├── StaffMemberAdd.ts
│   │   │   │   │   ├── StaffMemberDelete.ts
│   │   │   │   │   ├── StaffMemberDetailsFragment.ts
│   │   │   │   │   ├── StaffMemberDetails.ts
│   │   │   │   │   ├── StaffMemberFragment.ts
│   │   │   │   │   └── StaffMemberUpdate.ts
│   │   │   │   ├── urls.ts
│   │   │   │   └── views
│   │   │   │       ├── StaffDetails.tsx
│   │   │   │       └── StaffList.tsx
│   │   │   ├── storybook
│   │   │   │   ├── CardDecorator.tsx
│   │   │   │   ├── config.js
│   │   │   │   ├── Decorator.tsx
│   │   │   │   ├── misc.ts
│   │   │   │   ├── mock.tsx
│   │   │   │   ├── __snapshots__
│   │   │   │   │   └── Stories.test.ts.snap
│   │   │   │   ├── stories
│   │   │   │   │   ├── auth
│   │   │   │   │   │   ├── LoginLoading.tsx
│   │   │   │   │   │   └── LoginPage.tsx
│   │   │   │   │   ├── categories
│   │   │   │   │   │   ├── CategoryCreatePage.tsx
│   │   │   │   │   │   ├── CategoryListPage.tsx
│   │   │   │   │   │   ├── CategoryProducts.tsx
│   │   │   │   │   │   └── CategoryUpdatePage.tsx
│   │   │   │   │   ├── collections
│   │   │   │   │   │   ├── CollectionCreatePage.tsx
│   │   │   │   │   │   ├── CollectionDetailsPage.tsx
│   │   │   │   │   │   └── CollectionListPage.tsx
│   │   │   │   │   ├── components
│   │   │   │   │   │   ├── ActionDialog.tsx
│   │   │   │   │   │   ├── AddressEdit.tsx
│   │   │   │   │   │   ├── AddressFormatter.tsx
│   │   │   │   │   │   ├── AutocompleteSelectMenu.tsx
│   │   │   │   │   │   ├── CardMenu.tsx
│   │   │   │   │   │   ├── Checkbox.tsx
│   │   │   │   │   │   ├── Chip.tsx
│   │   │   │   │   │   ├── DateTime.tsx
│   │   │   │   │   │   ├── Date.tsx
│   │   │   │   │   │   ├── EditableTableCell.tsx
│   │   │   │   │   │   ├── ErrorMessageCard.tsx
│   │   │   │   │   │   ├── ErrorPage.tsx
│   │   │   │   │   │   ├── ExternalLink.tsx
│   │   │   │   │   │   ├── FileUpload.tsx
│   │   │   │   │   │   ├── messages.tsx
│   │   │   │   │   │   ├── MoneyRange.tsx
│   │   │   │   │   │   ├── Money.tsx
│   │   │   │   │   │   ├── MultiAutocompleteSelectField.tsx
│   │   │   │   │   │   ├── MultiSelectField.tsx
│   │   │   │   │   │   ├── NotFoundPage.tsx
│   │   │   │   │   │   ├── PageHeader.tsx
│   │   │   │   │   │   ├── Percent.tsx
│   │   │   │   │   │   ├── PhoneField.tsx
│   │   │   │   │   │   ├── PriceField.tsx
│   │   │   │   │   │   ├── RichTextEditor.tsx
│   │   │   │   │   │   ├── SaveButtonBar.tsx
│   │   │   │   │   │   ├── SingleAutocompleteSelectField.tsx
│   │   │   │   │   │   ├── SingleSelectField.tsx
│   │   │   │   │   │   ├── Skeleton.tsx
│   │   │   │   │   │   ├── StatusLabel.tsx
│   │   │   │   │   │   ├── TablePagination.tsx
│   │   │   │   │   │   ├── Timeline.tsx
│   │   │   │   │   │   ├── WeightRange.tsx
│   │   │   │   │   │   └── Weight.tsx
│   │   │   │   │   ├── configuration
│   │   │   │   │   │   └── ConfigurationPage.tsx
│   │   │   │   │   ├── customers
│   │   │   │   │   │   ├── CustomerAddressDialog.tsx
│   │   │   │   │   │   ├── CustomerAddressListPage.tsx
│   │   │   │   │   │   ├── CustomerCreatePage.tsx
│   │   │   │   │   │   ├── CustomerDetailsPage.tsx
│   │   │   │   │   │   └── CustomerListPage.tsx
│   │   │   │   │   ├── discounts
│   │   │   │   │   │   ├── DiscountCountrySelectDialog.tsx
│   │   │   │   │   │   ├── SaleCreatePage.tsx
│   │   │   │   │   │   ├── SaleDetailsPage.tsx
│   │   │   │   │   │   ├── SaleListPage.tsx
│   │   │   │   │   │   ├── VoucherCreatePage.tsx
│   │   │   │   │   │   ├── VoucherDetailsPage.tsx
│   │   │   │   │   │   └── VoucherListPage.tsx
│   │   │   │   │   ├── home
│   │   │   │   │   │   └── HomePage.tsx
│   │   │   │   │   ├── navigation
│   │   │   │   │   │   ├── MenuCreateDialog.tsx
│   │   │   │   │   │   ├── MenuDetailsPage.tsx
│   │   │   │   │   │   ├── MenuItemDialog.tsx
│   │   │   │   │   │   └── MenuListPage.tsx
│   │   │   │   │   ├── orders
│   │   │   │   │   │   ├── OrderAddressEditDialog.tsx
│   │   │   │   │   │   ├── OrderBulkCancelDialog.tsx
│   │   │   │   │   │   ├── OrderCancelDialog.tsx
│   │   │   │   │   │   ├── OrderCustomerEditDialog.tsx
│   │   │   │   │   │   ├── OrderCustomer.tsx
│   │   │   │   │   │   ├── OrderDetailsPage.tsx
│   │   │   │   │   │   ├── OrderDraftCancelDialog.tsx
│   │   │   │   │   │   ├── OrderDraftFinalizeDialog.tsx
│   │   │   │   │   │   ├── OrderDraftListPage.tsx
│   │   │   │   │   │   ├── OrderDraftPage.tsx
│   │   │   │   │   │   ├── OrderFulfillmentCancelDialog.tsx
│   │   │   │   │   │   ├── OrderFulfillmentDialog.tsx
│   │   │   │   │   │   ├── OrderFulfillmentTrackingDialog.tsx
│   │   │   │   │   │   ├── OrderHistory.tsx
│   │   │   │   │   │   ├── OrderListPage.tsx
│   │   │   │   │   │   ├── OrderMarkAsPaidDialog.tsx
│   │   │   │   │   │   ├── OrderPaymentDialog.tsx
│   │   │   │   │   │   ├── OrderPaymentVoidDialog.tsx
│   │   │   │   │   │   ├── OrderProductAddDialog.tsx
│   │   │   │   │   │   └── OrderShippingMethodEditDialog.tsx
│   │   │   │   │   ├── pages
│   │   │   │   │   │   ├── PageDetailsPage.tsx
│   │   │   │   │   │   └── PageListPage.tsx
│   │   │   │   │   ├── products
│   │   │   │   │   │   ├── ProductCreatePage.tsx
│   │   │   │   │   │   ├── ProductImagePage.tsx
│   │   │   │   │   │   ├── ProductListCard.tsx
│   │   │   │   │   │   ├── ProductUpdatePage.tsx
│   │   │   │   │   │   ├── ProductVariantCreatePage.tsx
│   │   │   │   │   │   ├── ProductVariantImageSelectDialog.tsx
│   │   │   │   │   │   └── ProductVariantPage.tsx
│   │   │   │   │   ├── productTypes
│   │   │   │   │   │   ├── ProductTypeAttributeEditDialog.tsx
│   │   │   │   │   │   ├── ProductTypeCreatePage.tsx
│   │   │   │   │   │   ├── ProductTypeDetailsPage.tsx
│   │   │   │   │   │   └── ProductTypeListPage.tsx
│   │   │   │   │   ├── shipping
│   │   │   │   │   │   ├── ShippingZoneCountriesAssignDialog.tsx
│   │   │   │   │   │   ├── ShippingZoneCreatePage.tsx
│   │   │   │   │   │   ├── ShippingZoneDetailsPage.tsx
│   │   │   │   │   │   ├── ShippingZoneRateDialog.tsx
│   │   │   │   │   │   └── ShippingZonesListPage.tsx
│   │   │   │   │   ├── siteSettings
│   │   │   │   │   │   ├── SiteSettingsKeyDialog.tsx
│   │   │   │   │   │   └── SiteSettingsPage.tsx
│   │   │   │   │   ├── staff
│   │   │   │   │   │   ├── StaffDetailsPage.tsx
│   │   │   │   │   │   └── StaffListPage.tsx
│   │   │   │   │   ├── taxes
│   │   │   │   │   │   ├── CountryListPage.tsx
│   │   │   │   │   │   ├── CountryTaxesPage.tsx
│   │   │   │   │   │   └── fixtures.ts
│   │   │   │   │   └── translations
│   │   │   │   │       ├── TranslationsEntitiesListPage.tsx
│   │   │   │   │       └── TranslationsLanguageListPage.tsx
│   │   │   │   ├── Stories.test.ts
│   │   │   │   └── webpack.config.js
│   │   │   ├── taxes
│   │   │   │   ├── components
│   │   │   │   │   ├── CountryList
│   │   │   │   │   │   ├── CountryList.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── CountryListPage
│   │   │   │   │   │   ├── CountryListPage.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   ├── CountryTaxesPage
│   │   │   │   │   │   ├── CountryTaxesPage.tsx
│   │   │   │   │   │   └── index.ts
│   │   │   │   │   └── TaxConfiguration
│   │   │   │   │       ├── index.ts
│   │   │   │   │       └── TaxConfiguration.tsx
│   │   │   │   ├── index.tsx
│   │   │   │   ├── mutations.ts
│   │   │   │   ├── queries.ts
│   │   │   │   ├── types
│   │   │   │   │   ├── CountryFragment.ts
│   │   │   │   │   ├── CountryList.ts
│   │   │   │   │   ├── CountryWithTaxesFragment.ts
│   │   │   │   │   ├── FetchTaxes.ts
│   │   │   │   │   ├── ShopTaxesFragment.ts
│   │   │   │   │   └── UpdateTaxSettings.ts
│   │   │   │   ├── urls.ts
│   │   │   │   └── views
│   │   │   │       ├── CountryList.tsx
│   │   │   │       └── CountryTaxes.tsx
│   │   │   ├── theme.ts
│   │   │   ├── translations
│   │   │   │   ├── components
│   │   │   │   │   ├── TranslationFields
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   ├── TranslationFieldsLong.tsx
│   │   │   │   │   │   ├── TranslationFieldsRich.tsx
│   │   │   │   │   │   ├── TranslationFieldsSave.tsx
│   │   │   │   │   │   ├── TranslationFieldsShort.tsx
│   │   │   │   │   │   └── TranslationFields.tsx
│   │   │   │   │   ├── TranslationsCategoriesPage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── TranslationsCategoriesPage.tsx
│   │   │   │   │   ├── TranslationsCollectionsPage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── TranslationsCollectionsPage.tsx
│   │   │   │   │   ├── TranslationsEntitiesList
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── TranslationsEntitiesList.tsx
│   │   │   │   │   ├── TranslationsEntitiesListPage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── TranslationsEntitiesListPage.tsx
│   │   │   │   │   ├── TranslationsLanguageList
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── TranslationsLanguageList.tsx
│   │   │   │   │   ├── TranslationsLanguageListPage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── TranslationsLanguageListPage.tsx
│   │   │   │   │   ├── TranslationsPagesPage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── TranslationsPagesPage.tsx
│   │   │   │   │   ├── TranslationsProductsPage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── TranslationsProductsPage.tsx
│   │   │   │   │   ├── TranslationsProductTypesPage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── TranslationsProductTypesPage.tsx
│   │   │   │   │   ├── TranslationsSalesPage
│   │   │   │   │   │   ├── index.ts
│   │   │   │   │   │   └── TranslationsSalesPage.tsx
│   │   │   │   │   └── TranslationsVouchersPage
│   │   │   │   │       ├── index.ts
│   │   │   │   │       └── TranslationsVouchersPage.tsx
│   │   │   │   ├── fixtures.ts
│   │   │   │   ├── index.tsx
│   │   │   │   ├── mutations.ts
│   │   │   │   ├── queries.ts
│   │   │   │   ├── types
│   │   │   │   │   ├── AttributeTranslationFragment.ts
│   │   │   │   │   ├── CategoryTranslationDetails.ts
│   │   │   │   │   ├── CategoryTranslationFragment.ts
│   │   │   │   │   ├── CategoryTranslations.ts
│   │   │   │   │   ├── CollectionTranslationDetails.ts
│   │   │   │   │   ├── CollectionTranslationFragment.ts
│   │   │   │   │   ├── CollectionTranslations.ts
│   │   │   │   │   ├── PageTranslationDetails.ts
│   │   │   │   │   ├── PageTranslationFragment.ts
│   │   │   │   │   ├── PageTranslations.ts
│   │   │   │   │   ├── ProductTranslationDetails.ts
│   │   │   │   │   ├── ProductTranslationFragment.ts
│   │   │   │   │   ├── ProductTranslations.ts
│   │   │   │   │   ├── ProductTypeTranslationDetails.ts
│   │   │   │   │   ├── ProductTypeTranslationFragment.ts
│   │   │   │   │   ├── ProductTypeTranslations.ts
│   │   │   │   │   ├── SaleTranslationDetails.ts
│   │   │   │   │   ├── SaleTranslationFragment.ts
│   │   │   │   │   ├── SaleTranslations.ts
│   │   │   │   │   ├── ShippingMethodTranslationFragment.ts
│   │   │   │   │   ├── TranslationsEntitiesPage.ts
│   │   │   │   │   ├── UpdateAttributeTranslations.ts
│   │   │   │   │   ├── UpdateAttributeValueTranslations.ts
│   │   │   │   │   ├── UpdateCategoryTranslations.ts
│   │   │   │   │   ├── UpdateCollectionTranslations.ts
│   │   │   │   │   ├── UpdatePageTranslations.ts
│   │   │   │   │   ├── UpdateProductTranslations.ts
│   │   │   │   │   ├── UpdateSaleTranslations.ts
│   │   │   │   │   ├── UpdateVoucherTranslations.ts
│   │   │   │   │   ├── VoucherTranslationDetails.ts
│   │   │   │   │   ├── VoucherTranslationFragment.ts
│   │   │   │   │   └── VoucherTranslations.ts
│   │   │   │   ├── urls.ts
│   │   │   │   └── views
│   │   │   │       ├── TranslationsCategories.tsx
│   │   │   │       ├── TranslationsCollections.tsx
│   │   │   │       ├── TranslationsEntities.tsx
│   │   │   │       ├── TranslationsLanguageList.tsx
│   │   │   │       ├── TranslationsPages.tsx
│   │   │   │       ├── TranslationsProducts.tsx
│   │   │   │       ├── TranslationsProductTypes.tsx
│   │   │   │       ├── TranslationsSales.tsx
│   │   │   │       └── TranslationsVouchers.tsx
│   │   │   ├── types
│   │   │   │   ├── globalTypes.ts
│   │   │   │   └── PageInfoFragment.ts
│   │   │   └── types.ts
│   │   ├── favicons
│   │   │   ├── android-chrome-192x192.png
│   │   │   ├── android-chrome-512x512.png
│   │   │   ├── apple-touch-icon.png
│   │   │   ├── browserconfig.xml
│   │   │   ├── favicon-16x16.png
│   │   │   ├── favicon-32x32.png
│   │   │   ├── favicon.ico
│   │   │   ├── mstile-144x144.png
│   │   │   ├── mstile-150x150.png
│   │   │   ├── mstile-310x150.png
│   │   │   ├── mstile-310x310.png
│   │   │   ├── mstile-70x70.png
│   │   │   └── safari-pinned-tab.svg
│   │   ├── fonts
│   │   │   ├── 2C8496_1_0.eot
│   │   │   ├── 2C8496_1_0.ttf
│   │   │   ├── 2C8496_1_0.woff
│   │   │   ├── 2C8496_1_0.woff2
│   │   │   ├── Lato-Bold.ttf
│   │   │   ├── Lato-Bold.woff
│   │   │   ├── Lato-Bold.woff2
│   │   │   ├── Lato-Light.ttf
│   │   │   ├── Lato-Light.woff
│   │   │   ├── Lato-Light.woff2
│   │   │   ├── Lato-Regular.ttf
│   │   │   ├── Lato-Regular.woff
│   │   │   └── Lato-Regular.woff2
│   │   ├── images
│   │   │   ├── arrow-down-icon.svg
│   │   │   ├── arrow-down.svg
│   │   │   ├── arrow-left.svg
│   │   │   ├── arrow-select.svg
│   │   │   ├── arrow-up-icon.svg
│   │   │   ├── arrow-up.svg
│   │   │   ├── avatars
│   │   │   │   ├── avatar10.png
│   │   │   │   ├── avatar11.png
│   │   │   │   ├── avatar12.png
│   │   │   │   ├── avatar1.png
│   │   │   │   ├── avatar2.png
│   │   │   │   ├── avatar3.png
│   │   │   │   ├── avatar4.png
│   │   │   │   ├── avatar5.png
│   │   │   │   ├── avatar6.png
│   │   │   │   ├── avatar7.png
│   │   │   │   ├── avatar8.png
│   │   │   │   └── avatar9.png
│   │   │   ├── block1.jpg
│   │   │   ├── block2.jpg
│   │   │   ├── block3.jpg
│   │   │   ├── checkout-bg2x.png
│   │   │   ├── checkout-bg.png
│   │   │   ├── checkout.svg
│   │   │   ├── chevron-down.svg
│   │   │   ├── chevron-up.svg
│   │   │   ├── close.svg
│   │   │   ├── confirm-order-bg2x.png
│   │   │   ├── confirm-order-bg.png
│   │   │   ├── delete.svg
│   │   │   ├── dribbble-logo.svg
│   │   │   ├── edit.svg
│   │   │   ├── empty-checkout-bg2x.png
│   │   │   ├── empty-checkout-bg.png
│   │   │   ├── facebook-logo.svg
│   │   │   ├── favicon.svg
│   │   │   ├── filter-icon.svg
│   │   │   ├── gallery-arrow.svg
│   │   │   ├── github-logo.svg
│   │   │   ├── google-logo.svg
│   │   │   ├── instagram-logo.svg
│   │   │   ├── linkedin-logo.svg
│   │   │   ├── loader.svg
│   │   │   ├── login-background.svg
│   │   │   ├── login-bg2x.png
│   │   │   ├── login-bg.png
│   │   │   ├── logo-dark.svg
│   │   │   ├── logo-light.svg
│   │   │   ├── logo-white.svg
│   │   │   ├── meetup-logo.svg
│   │   │   ├── mobile-menu.svg
│   │   │   ├── no-results-bg.svg
│   │   │   ├── not-found-404.svg
│   │   │   ├── pass-invisible.svg
│   │   │   ├── pass-visible.svg
│   │   │   ├── photo-icon.svg
│   │   │   ├── placeholder1080x1080.png
│   │   │   ├── placeholder120x120.png
│   │   │   ├── placeholder255x255.png
│   │   │   ├── placeholder540x540.png
│   │   │   ├── placeholder60x60.png
│   │   │   ├── reset-bg.png
│   │   │   ├── sale-bg.svg
│   │   │   ├── sample-product2.jpg
│   │   │   ├── sample-product.jpg
│   │   │   ├── search.svg
│   │   │   ├── twitter-logo.svg
│   │   │   └── what.svg
│   │   ├── js
│   │   │   ├── components
│   │   │   │   ├── address-form.js
│   │   │   │   ├── checkout.js
│   │   │   │   ├── footer.js
│   │   │   │   ├── language-picker.js
│   │   │   │   ├── misc.js
│   │   │   │   ├── navbar.js
│   │   │   │   ├── password-input.js
│   │   │   │   ├── product-filters.js
│   │   │   │   ├── sorter.js
│   │   │   │   ├── styleguide.js
│   │   │   │   ├── variantPicker
│   │   │   │   │   ├── AttributeSelectionWidget.js
│   │   │   │   │   ├── QuantityInput.js
│   │   │   │   │   ├── VariantPicker.js
│   │   │   │   │   └── VariantPrice.js
│   │   │   │   └── variant-picker.js
│   │   │   ├── storefront.js
│   │   │   └── stores
│   │   │       └── variantPicker.js
│   │   ├── placeholders
│   │   │   ├── products-list
│   │   │   │   ├── accessories.jpg
│   │   │   │   ├── apparel.jpg
│   │   │   │   ├── clothing.jpg
│   │   │   │   ├── groceries.jpg
│   │   │   │   └── summer.jpg
│   │   │   ├── saleordemoproduct_beer-01_1.png
│   │   │   ├── saleordemoproduct_beer-01_2.png
│   │   │   ├── saleordemoproduct_beer-02_1.png
│   │   │   ├── saleordemoproduct_beer-02_2.png
│   │   │   ├── saleordemoproduct_cl_bogo01_1.png
│   │   │   ├── saleordemoproduct_cl_bogo02_1.png
│   │   │   ├── saleordemoproduct_cl_bogo03_1.png
│   │   │   ├── saleordemoproduct_cl_bogo04_1.png
│   │   │   ├── saleordemoproduct_cl_bogo04_2.png
│   │   │   ├── saleordemoproduct_cl_boot01_1.png
│   │   │   ├── saleordemoproduct_cl_boot01_2.png
│   │   │   ├── saleordemoproduct_cl_boot01_3.png
│   │   │   ├── saleordemoproduct_cl_boot03_1.png
│   │   │   ├── saleordemoproduct_cl_boot03_2.png
│   │   │   ├── saleordemoproduct_cl_boot06_1.png
│   │   │   ├── saleordemoproduct_cl_boot06_2.png
│   │   │   ├── saleordemoproduct_cl_boot07_1.png
│   │   │   ├── saleordemoproduct_cl_boot07_2.png
│   │   │   ├── saleordemoproduct_cl_polo01.png
│   │   │   ├── saleordemoproduct_cl_polo02.png
│   │   │   ├── saleordemoproduct_cl_polo03-woman.png
│   │   │   ├── saleordemoproduct_cl_polo04-woman.png
│   │   │   ├── saleordemoproduct_cuschion01.png
│   │   │   ├── saleordemoproduct_cuschion02.png
│   │   │   ├── saleordemoproduct_fd_juice_01.png
│   │   │   ├── saleordemoproduct_fd_juice_02.png
│   │   │   ├── saleordemoproduct_fd_juice_03.png
│   │   │   ├── saleordemoproduct_fd_juice_04.png
│   │   │   ├── saleordemoproduct_fd_juice_05.png
│   │   │   ├── saleordemoproduct_fd_juice_06.png
│   │   │   ├── saleordemoproduct_paints_01.png
│   │   │   ├── saleordemoproduct_paints_02.png
│   │   │   ├── saleordemoproduct_paints_03.png
│   │   │   ├── saleordemoproduct_paints_04.png
│   │   │   ├── saleordemoproduct_paints_05.png
│   │   │   ├── saleordemoproduct_sneakers_01_1.png
│   │   │   ├── saleordemoproduct_sneakers_01_2.png
│   │   │   ├── saleordemoproduct_sneakers_01_3.png
│   │   │   ├── saleordemoproduct_sneakers_01_4.png
│   │   │   ├── saleordemoproduct_sneakers_02_1.png
│   │   │   ├── saleordemoproduct_sneakers_02_2.png
│   │   │   ├── saleordemoproduct_sneakers_02_3.png
│   │   │   ├── saleordemoproduct_sneakers_02_4.png
│   │   │   ├── saleordemoproduct_wine-red.png
│   │   │   └── saleordemoproduct_wine-white.png
│   │   ├── populatedb_data.json
│   │   └── scss
│   │       ├── components
│   │       │   ├── _breadcrumbs.scss
│   │       │   ├── _buttons.scss
│   │       │   ├── _cards.scss
│   │       │   ├── _checkout-dropdown.scss
│   │       │   ├── _filters.scss
│   │       │   ├── _footer.scss
│   │       │   ├── _forms.scss
│   │       │   ├── _header.scss
│   │       │   ├── _labels.scss
│   │       │   ├── _language-picker.scss
│   │       │   ├── _loader.scss
│   │       │   ├── _pagination.scss
│   │       │   ├── _table.scss
│   │       │   ├── _tabs.scss
│   │       │   ├── _typography.scss
│   │       │   └── _variant-picker.scss
│   │       ├── layouts
│   │       │   ├── _account.scss
│   │       │   ├── _checkout.scss
│   │       │   ├── _home.scss
│   │       │   ├── _login.scss
│   │       │   ├── _no-results.scss
│   │       │   ├── _order-details.scss
│   │       │   ├── _payment.scss
│   │       │   ├── _product-list.scss
│   │       │   ├── _product-page.scss
│   │       │   └── _styleguide.scss
│   │       ├── storefront.scss
│   │       └── variables.scss
│   ├── urls.py
│   └── wsgi
│       ├── health_check.py
│       ├── __init__.py
│       └── uwsgi.ini
├── scripts
│   ├── deploy_master.sh
│   └── push_static.sh
├── setup.cfg
├── templates
│   ├── 404.html
│   ├── account
│   │   ├── account_delete_prompt.html
│   │   ├── address_delete.html
│   │   ├── address_edit.html
│   │   ├── details.html
│   │   ├── login.html
│   │   ├── partials
│   │   │   ├── already_logged_in.html
│   │   │   └── login_form.html
│   │   ├── password_change.html
│   │   ├── password_reset_base.html
│   │   ├── password_reset_done.html
│   │   ├── password_reset_from_key_done.html
│   │   ├── password_reset_from_key.html
│   │   ├── password_reset.html
│   │   ├── signup.html
│   │   └── snippets
│   │       ├── address_form.html
│   │       ├── datalist.html
│   │       └── phone_prefix_widget.html
│   ├── base.html
│   ├── category
│   │   ├── filters.html
│   │   └── index.html
│   ├── checkout
│   │   ├── details.html
│   │   ├── index.html
│   │   ├── login.html
│   │   ├── payment.html
│   │   ├── shipping_address.html
│   │   ├── shipping_method.html
│   │   ├── snippets
│   │   │   ├── addresses_form.html
│   │   │   ├── addresses_form_panel.html
│   │   │   └── voucher_form.html
│   │   ├── _subtotal_table.html
│   │   ├── summary.html
│   │   └── summary_without_shipping.html
│   ├── checkout_dropdown.html
│   ├── collection
│   │   └── index.html
│   ├── dashboard
│   │   ├── base.html
│   │   ├── base_modal.html
│   │   ├── base_zero_page.html
│   │   ├── category
│   │   │   ├── detail.html
│   │   │   ├── form.html
│   │   │   ├── list.html
│   │   │   ├── modal
│   │   │   │   └── confirm_delete.html
│   │   │   └── zero_page.html
│   │   ├── collection
│   │   │   ├── confirm_delete.html
│   │   │   ├── detail.html
│   │   │   ├── list.html
│   │   │   └── zero_page.html
│   │   ├── customer
│   │   │   ├── detail.html
│   │   │   ├── form.html
│   │   │   ├── list.html
│   │   │   ├── modal
│   │   │   │   ├── add_note.html
│   │   │   │   ├── confirm_delete.html
│   │   │   │   └── confirm_promote.html
│   │   │   └── zero_page.html
│   │   ├── discount
│   │   │   ├── sale
│   │   │   │   ├── form.html
│   │   │   │   ├── list.html
│   │   │   │   ├── modal
│   │   │   │   │   └── confirm_delete.html
│   │   │   │   └── zero_page.html
│   │   │   └── voucher
│   │   │       ├── form.html
│   │   │       ├── list.html
│   │   │       ├── modal
│   │   │       │   └── confirm_delete.html
│   │   │       └── zero_page.html
│   │   ├── includes
│   │   │   ├── _address.html
│   │   │   ├── _back_link.html
│   │   │   ├── _bulk_actions_bar.html
│   │   │   ├── _collection_availability.html
│   │   │   ├── _filters.html
│   │   │   ├── _google_preview.html
│   │   │   ├── _menu_items.html
│   │   │   ├── _page_availability.html
│   │   │   ├── _pagination.html
│   │   │   └── _sorting_header.html
│   │   ├── index.html
│   │   ├── menu
│   │   │   ├── detail.html
│   │   │   ├── form.html
│   │   │   ├── item
│   │   │   │   ├── detail.html
│   │   │   │   ├── form.html
│   │   │   │   └── modal
│   │   │   │       └── confirm_delete.html
│   │   │   ├── list.html
│   │   │   ├── modal
│   │   │   │   └── confirm_delete.html
│   │   │   └── zero_page.html
│   │   ├── next.html
│   │   ├── order
│   │   │   ├── address_form.html
│   │   │   ├── detail.html
│   │   │   ├── fulfillment.html
│   │   │   ├── list.html
│   │   │   ├── modal
│   │   │   │   ├── add_note.html
│   │   │   │   ├── add_variant_to_order.html
│   │   │   │   ├── cancel_fulfillment.html
│   │   │   │   ├── cancel_line.html
│   │   │   │   ├── cancel_order.html
│   │   │   │   ├── capture.html
│   │   │   │   ├── change_quantity.html
│   │   │   │   ├── create_order.html
│   │   │   │   ├── edit_customer.html
│   │   │   │   ├── edit_discount.html
│   │   │   │   ├── edit_shipping.html
│   │   │   │   ├── edit_voucher.html
│   │   │   │   ├── fulfillment_tracking.html
│   │   │   │   ├── mark_as_paid.html
│   │   │   │   ├── refund.html
│   │   │   │   ├── remove_order.html
│   │   │   │   └── void.html
│   │   │   ├── pdf
│   │   │   │   ├── base_pdf.html
│   │   │   │   ├── invoice.html
│   │   │   │   └── packing_slip.html
│   │   │   ├── widget
│   │   │   │   └── phone_prefix_widget.html
│   │   │   └── zero_page.html
│   │   ├── page
│   │   │   ├── detail.html
│   │   │   ├── form.html
│   │   │   ├── list.html
│   │   │   ├── modal_delete.html
│   │   │   └── zero_page.html
│   │   ├── product
│   │   │   ├── attribute
│   │   │   │   ├── detail.html
│   │   │   │   ├── form.html
│   │   │   │   ├── list.html
│   │   │   │   ├── modal
│   │   │   │   │   └── attribute_confirm_delete.html
│   │   │   │   ├── values
│   │   │   │   │   ├── form.html
│   │   │   │   │   └── modal
│   │   │   │   │       └── confirm_delete.html
│   │   │   │   └── zero_page.html
│   │   │   ├── detail.html
│   │   │   ├── form.html
│   │   │   ├── list.html
│   │   │   ├── modal
│   │   │   │   ├── confirm_delete.html
│   │   │   │   └── select_type.html
│   │   │   ├── product_image
│   │   │   │   ├── form.html
│   │   │   │   ├── list.html
│   │   │   │   ├── modal
│   │   │   │   │   └── confirm_delete.html
│   │   │   │   └── versatile_image.html
│   │   │   ├── product_type
│   │   │   │   ├── form.html
│   │   │   │   ├── list.html
│   │   │   │   ├── modal
│   │   │   │   │   └── confirm_delete.html
│   │   │   │   └── zero_page.html
│   │   │   ├── product_variant
│   │   │   │   ├── detail.html
│   │   │   │   ├── form.html
│   │   │   │   ├── _image_select.html
│   │   │   │   └── modal
│   │   │   │       ├── confirm_delete.html
│   │   │   │       └── select_images.html
│   │   │   └── zero_page.html
│   │   ├── search
│   │   │   └── results.html
│   │   ├── shipping
│   │   │   ├── detail.html
│   │   │   ├── form.html
│   │   │   ├── list.html
│   │   │   ├── methods
│   │   │   │   ├── form.html
│   │   │   │   └── _shipping_methods_table.html
│   │   │   ├── modal
│   │   │   │   ├── confirm_delete.html
│   │   │   │   └── method_confirm_delete.html
│   │   │   ├── weight_widget.html
│   │   │   └── zero_page.html
│   │   ├── sites
│   │   │   ├── authorization_keys
│   │   │   │   └── form.html
│   │   │   ├── detail.html
│   │   │   ├── form.html
│   │   │   └── modal
│   │   │       └── confirm_delete.html
│   │   ├── staff
│   │   │   ├── detail.html
│   │   │   ├── list.html
│   │   │   ├── modal
│   │   │   │   └── confirm_delete.html
│   │   │   └── zero_page.html
│   │   ├── styleguide
│   │   │   └── index.html
│   │   └── taxes
│   │       ├── details.html
│   │       ├── form.html
│   │       ├── list.html
│   │       └── zero_page.html
│   ├── favicon.html
│   ├── footer_menu.html
│   ├── formatted_address.html
│   ├── graphql
│   │   └── playground.html
│   ├── home.html
│   ├── _language_picker.html
│   ├── _language_picker_modal.html
│   ├── manifest.json
│   ├── materializecssform
│   │   ├── field.html
│   │   ├── form.html
│   │   ├── formset.html
│   │   └── LICENSE
│   ├── menu.html
│   ├── order
│   │   ├── checkout_success_anonymous.html
│   │   ├── checkout_success.html
│   │   ├── details.html
│   │   ├── _ordered_items_table.html
│   │   ├── payment
│   │   │   ├── braintree.html
│   │   │   ├── details.html
│   │   │   ├── dummy.html
│   │   │   ├── razorpay.html
│   │   │   └── stripe.html
│   │   └── payment.html
│   ├── page
│   │   └── details.html
│   ├── payments
│   │   └── credit_card_expiry_widget.html
│   ├── price.html
│   ├── prices
│   │   └── widget.html
│   ├── product
│   │   ├── details.html
│   │   ├── _filters.html
│   │   ├── _items.html
│   │   ├── _price_range.html
│   │   └── product_list_base.html
│   ├── search
│   │   └── results.html
│   ├── status_label.html
│   ├── styleguide.html
│   ├── templated_email
│   │   ├── account
│   │   │   ├── account_delete.email
│   │   │   └── password_reset.email
│   │   ├── compiled
│   │   ├── dashboard
│   │   │   ├── customer
│   │   │   │   └── set_password.email
│   │   │   └── staff
│   │   │       ├── promote_customer.email
│   │   │       └── set_password.email
│   │   ├── order
│   │   │   ├── confirm_fulfillment.email
│   │   │   ├── confirm_order.email
│   │   │   ├── payment
│   │   │   │   └── confirm_payment.email
│   │   │   └── update_fulfillment.email
│   │   ├── shared
│   │   │   ├── _footer.email
│   │   │   └── _header.email
│   │   └── source
│   │       ├── account_delete.mjml
│   │       ├── confirm_fulfillment.mjml
│   │       ├── confirm_order.mjml
│   │       ├── confirm_payment.mjml
│   │       ├── partials
│   │       │   ├── _fulfillment_lines.mjml
│   │       │   └── _order_lines.mjml
│   │       ├── password_reset.mjml
│   │       ├── promote_customer.mjml
│   │       ├── set_customer_password.mjml
│   │       ├── set_password.mjml
│   │       ├── shared
│   │       │   ├── footer.mjml
│   │       │   ├── header.mjml
│   │       │   └── styles.mjml
│   │       └── update_fulfillment.mjml
│   └── weight_field_widget.html
├── tests
│   ├── api
│   │   ├── conftest.py
│   │   ├── __init__.py
│   │   ├── test_account_events.py
│   │   ├── test_account.py
│   │   ├── test_attributes.py
│   │   ├── test_base_mutation.py
│   │   ├── test_bulk_delete.py
│   │   ├── test_category.py
│   │   ├── test_checkout.py
│   │   ├── test_collection.py
│   │   ├── test_core.py
│   │   ├── test_digital_content.py
│   │   ├── test_discount.py
│   │   ├── test_fulfillment.py
│   │   ├── test_graphql.py
│   │   ├── test_homepage.py
│   │   ├── test_menu.py
│   │   ├── test_order.py
│   │   ├── test_page.py
│   │   ├── test_payment.py
│   │   ├── test_product.py
│   │   ├── test_shipping_method.py
│   │   ├── test_shop.py
│   │   ├── test_translations.py
│   │   ├── test_variant_pricing.py
│   │   ├── test_variant.py
│   │   ├── test_view.py
│   │   └── utils.py
│   ├── cassettes
│   │   ├── test_dashboard_search_orders_by_user_email.yaml
│   │   ├── test_dashboard_search_orders_by_user_name_without_address.yaml
│   │   ├── test_dashboard_search_orders_by_user_name.yaml
│   │   ├── test_dashboard_search_orders_by_user.yaml
│   │   ├── test_dashboard_search_user_by_email.yaml
│   │   ├── test_dashboard_search_user_name_without_address.yaml
│   │   ├── test_dashboard_search_user_name.yaml
│   │   ├── test_dashboard_search_with_empty_results.yaml
│   │   ├── test_dashboard_search_with_product_result.yaml
│   │   ├── test_new_search_doesnt_show_unpublished.yaml
│   │   ├── test_new_search_with_empty_results.yaml
│   │   └── test_new_search_with_result.yaml
│   ├── conftest.py
│   ├── dashboard
│   │   ├── __init__.py
│   │   ├── test_category.py
│   │   ├── test_chips.py
│   │   ├── test_collection.py
│   │   ├── test_customer.py
│   │   ├── test_discounts.py
│   │   ├── test_forms.py
│   │   ├── test_menu.py
│   │   ├── test_order.py
│   │   ├── test_page.py
│   │   ├── test_permissions.py
│   │   ├── test_product.py
│   │   ├── test_shipping.py
│   │   ├── test_site_settings.py
│   │   ├── test_staff.py
│   │   ├── test_taxes.py
│   │   ├── test_templatetags.py
│   │   └── test_utils.py
│   ├── dummy_password_hasher.py
│   ├── gateway
│   │   ├── __init__.py
│   │   ├── test_braintree.py
│   │   ├── test_dummy.py
│   │   ├── test_razorpay.py
│   │   └── test_stripe.py
│   ├── __init__.py
│   ├── runner.py
│   ├── settings.py
│   ├── test_account.py
│   ├── test_analytics.py
│   ├── test_asynchronous_tasks.py
│   ├── test_cart.py
│   ├── test_category.py
│   ├── test_checkout.py
│   ├── test_collection.py
│   ├── test_core.py
│   ├── test_data_feeds.py
│   ├── test_discounts.py
│   ├── test_elasticsearch.py
│   ├── test_emails.py
│   ├── test_impersonation.py
│   ├── test_order.py
│   ├── test_order_utils.py
│   ├── test_page.py
│   ├── test_payment.py
│   ├── test_postgresql_search.py
│   ├── test_product_attributes.py
│   ├── test_product_availability.py
│   ├── test_product.py
│   ├── test_product_tags.py
│   ├── test_registration.py
│   ├── test_seo_schema.py
│   ├── test_shipping.py
│   ├── test_sitemap.py
│   ├── test_templatetags.py
│   ├── test_translation.py
│   └── utils.py
├── tox.ini
├── tsconfig.json
├── tslint.json
├── webpack.config.js
└── webpack.d.ts

710 directories, 2685 files
