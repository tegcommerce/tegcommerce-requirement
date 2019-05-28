# cezerin

## structure of directories and files

```
.
├── config
│   ├── admin.js
│   ├── admin.production.js
│   ├── server.js
│   ├── server.production.js
│   ├── store.js
│   └── store.production.js
├── docs
│   ├── api
│   │   ├── apps.md
│   │   ├── product-categories.md
│   │   ├── products.md
│   │   ├── README.md
│   │   └── webhooks.md
│   ├── getting-started-docker.md
│   ├── getting-started.md
│   ├── how-to-deploy-a-cezerin-on-ubuntu-16-04.md
│   ├── how-to-deploy-a-cezerin-on-ubuntu-18-04-1-github.md
│   ├── images
│   │   ├── cf-alway-https.png
│   │   ├── cf-dns.png
│   │   ├── cf-ssl.png
│   │   └── do-ip.png
│   ├── initialize-mongodb.md
│   ├── nginx.md
│   ├── README.md
│   └── structure.md
├── LICENSE
├── locales
│   ├── de.json
│   ├── en.json
│   ├── fr.json
│   ├── it.json
│   ├── ru.json
│   ├── uk.json
│   └── zh_CN.json
├── logs
│   └── README.md
├── package.json
├── package-lock.json
├── postcss.config.js
├── process.json
├── public
│   ├── admin-assets
│   │   ├── css
│   │   │   ├── flexboxgrid.min.css
│   │   │   └── style.css
│   │   ├── data
│   │   │   ├── countries.js
│   │   │   ├── currencies.js
│   │   │   └── timezones.js
│   │   ├── images
│   │   │   ├── apps
│   │   │   │   ├── facebook-customer-chat-plugin.png
│   │   │   │   ├── facebook.png
│   │   │   │   ├── google_analytics.png
│   │   │   │   ├── jivosite.png
│   │   │   │   ├── messenger.png
│   │   │   │   └── site_verification.png
│   │   │   └── shortcut.png
│   │   ├── manifest.json
│   │   └── tinymce
│   │       ├── langs
│   │       │   ├── af_ZA.js
│   │       │   ├── ar.js
│   │       │   ├── be.js
│   │       │   ├── bg_BG.js
│   │       │   ├── ca.js
│   │       │   ├── cs.js
│   │       │   ├── cy.js
│   │       │   ├── da.js
│   │       │   ├── de_AT.js
│   │       │   ├── de.js
│   │       │   ├── dv.js
│   │       │   ├── el.js
│   │       │   ├── en_CA.js
│   │       │   ├── en_GB.js
│   │       │   ├── es.js
│   │       │   ├── es_MX.js
│   │       │   ├── et.js
│   │       │   ├── fa_IR.js
│   │       │   ├── fr_FR.js
│   │       │   ├── ga.js
│   │       │   ├── gl.js
│   │       │   ├── he_IL.js
│   │       │   ├── hr.js
│   │       │   ├── hu_HU.js
│   │       │   ├── it.js
│   │       │   ├── ja.js
│   │       │   ├── kab.js
│   │       │   ├── ka_GE.js
│   │       │   ├── kk.js
│   │       │   ├── km_KH.js
│   │       │   ├── ko_KR.js
│   │       │   ├── lv.js
│   │       │   ├── nb_NO.js
│   │       │   ├── nl.js
│   │       │   ├── pl.js
│   │       │   ├── pt_BR.js
│   │       │   ├── pt_PT.js
│   │       │   ├── ro.js
│   │       │   ├── ru.js
│   │       │   ├── sk.js
│   │       │   ├── sl_SI.js
│   │       │   ├── sv_SE.js
│   │       │   ├── ta_IN.js
│   │       │   ├── ta.js
│   │       │   ├── th_TH.js
│   │       │   ├── tr.js
│   │       │   ├── tr_TR.js
│   │       │   ├── uk.js
│   │       │   ├── uk_UA.js
│   │       │   ├── uz.js
│   │       │   ├── vi_VN.js
│   │       │   ├── zh_CN.js
│   │       │   └── zh_TW.js
│   │       ├── license.txt
│   │       ├── plugins
│   │       │   ├── codesample
│   │       │   │   └── css
│   │       │   │       └── prism.css
│   │       │   ├── emoticons
│   │       │   │   └── img
│   │       │   │       ├── smiley-cool.gif
│   │       │   │       ├── smiley-cry.gif
│   │       │   │       ├── smiley-embarassed.gif
│   │       │   │       ├── smiley-foot-in-mouth.gif
│   │       │   │       ├── smiley-frown.gif
│   │       │   │       ├── smiley-innocent.gif
│   │       │   │       ├── smiley-kiss.gif
│   │       │   │       ├── smiley-laughing.gif
│   │       │   │       ├── smiley-money-mouth.gif
│   │       │   │       ├── smiley-sealed.gif
│   │       │   │       ├── smiley-smile.gif
│   │       │   │       ├── smiley-surprised.gif
│   │       │   │       ├── smiley-tongue-out.gif
│   │       │   │       ├── smiley-undecided.gif
│   │       │   │       ├── smiley-wink.gif
│   │       │   │       └── smiley-yell.gif
│   │       │   └── visualblocks
│   │       │       └── css
│   │       │           └── visualblocks.css
│   │       ├── skins
│   │       │   └── lightgray
│   │       │       ├── content.inline.min.css
│   │       │       ├── content.min.css
│   │       │       ├── content.mobile.min.css
│   │       │       ├── fonts
│   │       │       │   ├── tinymce.eot
│   │       │       │   ├── tinymce-mobile.woff
│   │       │       │   ├── tinymce-small.eot
│   │       │       │   ├── tinymce-small.svg
│   │       │       │   ├── tinymce-small.ttf
│   │       │       │   ├── tinymce-small.woff
│   │       │       │   ├── tinymce.svg
│   │       │       │   ├── tinymce.ttf
│   │       │       │   └── tinymce.woff
│   │       │       ├── img
│   │       │       │   ├── anchor.gif
│   │       │       │   ├── loader.gif
│   │       │       │   ├── object.gif
│   │       │       │   └── trans.gif
│   │       │       ├── skin.min.css
│   │       │       ├── skin.min.css.map
│   │       │       ├── skin.mobile.min.css
│   │       │       └── skin.mobile.min.css.map
│   │       └── tinymce-4.7.5.min.js
│   ├── content
│   │   └── README.md
│   └── robots.template
├── README.md
├── scripts
│   ├── theme-export.sh
│   └── theme-install.sh
├── src
│   ├── admin
│   │   └── client
│   │       ├── app.js
│   │       ├── apps
│   │       │   ├── facebook-customer-chat.js
│   │       │   ├── facebook-sdk.js
│   │       │   ├── google-analytics.js
│   │       │   ├── index.js
│   │       │   ├── jivosite.js
│   │       │   └── site-verification.js
│   │       ├── index.html
│   │       ├── index.js
│   │       ├── lib
│   │       │   ├── api.js
│   │       │   ├── apiWebSocket.js
│   │       │   ├── auth.js
│   │       │   ├── data.js
│   │       │   ├── helper.js
│   │       │   ├── settings.js
│   │       │   ├── text.js
│   │       │   └── webstoreAuth.js
│   │       ├── modules
│   │       │   ├── apps
│   │       │   │   ├── account
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── account.js
│   │       │   │   │   │   ├── details.js
│   │       │   │   │   │   ├── developer.js
│   │       │   │   │   │   └── style.css
│   │       │   │   │   └── index.js
│   │       │   │   ├── actions.js
│   │       │   │   ├── actionTypes.js
│   │       │   │   ├── appDetails
│   │       │   │   │   ├── description.js
│   │       │   │   │   ├── index.js
│   │       │   │   │   └── style.css
│   │       │   │   ├── head
│   │       │   │   │   ├── components
│   │       │   │   │   │   └── buttons.js
│   │       │   │   │   └── index.js
│   │       │   │   ├── reducer.js
│   │       │   │   ├── serviceDetails
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── actions.js
│   │       │   │   │   │   ├── description.js
│   │       │   │   │   │   ├── details.js
│   │       │   │   │   │   ├── logs.js
│   │       │   │   │   │   ├── settings.js
│   │       │   │   │   │   └── style.css
│   │       │   │   │   └── index.js
│   │       │   │   └── services
│   │       │   │       ├── components
│   │       │   │       │   ├── appItem.js
│   │       │   │       │   ├── item.js
│   │       │   │       │   ├── list.js
│   │       │   │       │   ├── serviceItem.js
│   │       │   │       │   └── style.css
│   │       │   │       └── index.js
│   │       │   ├── customerGroups
│   │       │   │   ├── actions.js
│   │       │   │   ├── actionTypes.js
│   │       │   │   ├── components
│   │       │   │   │   └── list.js
│   │       │   │   ├── edit
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── form.js
│   │       │   │   │   │   └── style.css
│   │       │   │   │   └── index.js
│   │       │   │   ├── head
│   │       │   │   │   ├── components
│   │       │   │   │   │   └── buttons.js
│   │       │   │   │   └── index.js
│   │       │   │   ├── list
│   │       │   │   │   └── index.js
│   │       │   │   ├── reducer.js
│   │       │   │   └── select
│   │       │   │       └── index.js
│   │       │   ├── customers
│   │       │   │   ├── actions.js
│   │       │   │   ├── actionTypes.js
│   │       │   │   ├── edit
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── addresses.js
│   │       │   │   │   │   ├── addressForm.js
│   │       │   │   │   │   ├── details.js
│   │       │   │   │   │   ├── orders.js
│   │       │   │   │   │   ├── style.css
│   │       │   │   │   │   ├── summaryForm.js
│   │       │   │   │   │   └── summary.js
│   │       │   │   │   └── index.js
│   │       │   │   ├── editHead
│   │       │   │   │   ├── components
│   │       │   │   │   │   └── buttons.js
│   │       │   │   │   └── index.js
│   │       │   │   ├── filter
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── fields.js
│   │       │   │   │   │   └── style.css
│   │       │   │   │   └── index.js
│   │       │   │   ├── list
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── head.js
│   │       │   │   │   │   ├── item.js
│   │       │   │   │   │   ├── list.js
│   │       │   │   │   │   └── style.css
│   │       │   │   │   └── index.js
│   │       │   │   ├── listHead
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── buttons.js
│   │       │   │   │   │   └── search.js
│   │       │   │   │   └── index.js
│   │       │   │   └── reducer.js
│   │       │   ├── files
│   │       │   │   ├── actions.js
│   │       │   │   ├── actionTypes.js
│   │       │   │   ├── list
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── fileUploader
│   │       │   │   │   │   │   ├── index.js
│   │       │   │   │   │   │   └── style.css
│   │       │   │   │   │   ├── form.js
│   │       │   │   │   │   ├── headButtons.js
│   │       │   │   │   │   └── style.css
│   │       │   │   │   ├── head.js
│   │       │   │   │   └── index.js
│   │       │   │   └── reducer.js
│   │       │   ├── head
│   │       │   │   ├── components
│   │       │   │   │   ├── appBar.js
│   │       │   │   │   └── drawer.js
│   │       │   │   └── index.js
│   │       │   ├── orders
│   │       │   │   ├── actions.js
│   │       │   │   ├── actionTypes.js
│   │       │   │   ├── edit
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── customer.js
│   │       │   │   │   │   ├── details.js
│   │       │   │   │   │   ├── items.js
│   │       │   │   │   │   ├── shippingAddressForm.js
│   │       │   │   │   │   ├── style.css
│   │       │   │   │   │   ├── summaryForm.js
│   │       │   │   │   │   ├── summary.js
│   │       │   │   │   │   └── totals.js
│   │       │   │   │   └── index.js
│   │       │   │   ├── editHead
│   │       │   │   │   ├── components
│   │       │   │   │   │   └── buttons.js
│   │       │   │   │   └── index.js
│   │       │   │   ├── list
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── head.js
│   │       │   │   │   │   ├── item.js
│   │       │   │   │   │   ├── list.js
│   │       │   │   │   │   └── style.css
│   │       │   │   │   └── index.js
│   │       │   │   ├── listFilter
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── fields.js
│   │       │   │   │   │   └── style.css
│   │       │   │   │   └── index.js
│   │       │   │   ├── listHead
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── buttons.js
│   │       │   │   │   │   └── search.js
│   │       │   │   │   └── index.js
│   │       │   │   └── reducer.js
│   │       │   ├── orderStatuses
│   │       │   │   ├── actions.js
│   │       │   │   ├── actionTypes.js
│   │       │   │   ├── components
│   │       │   │   │   └── list.js
│   │       │   │   ├── edit
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── form.js
│   │       │   │   │   │   └── style.css
│   │       │   │   │   └── index.js
│   │       │   │   ├── head
│   │       │   │   │   ├── components
│   │       │   │   │   │   └── buttons.js
│   │       │   │   │   └── index.js
│   │       │   │   ├── list
│   │       │   │   │   └── index.js
│   │       │   │   ├── reducer.js
│   │       │   │   └── select
│   │       │   │       └── index.js
│   │       │   ├── pages
│   │       │   │   ├── actions.js
│   │       │   │   ├── actionTypes.js
│   │       │   │   ├── edit
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── form.js
│   │       │   │   │   │   ├── headButtons.js
│   │       │   │   │   │   └── style.css
│   │       │   │   │   ├── head.js
│   │       │   │   │   └── index.js
│   │       │   │   ├── list
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── form.js
│   │       │   │   │   │   └── headButtons.js
│   │       │   │   │   ├── head.js
│   │       │   │   │   └── index.js
│   │       │   │   └── reducer.js
│   │       │   ├── productCategories
│   │       │   │   ├── actions.js
│   │       │   │   ├── actionTypes.js
│   │       │   │   ├── components
│   │       │   │   │   ├── list.js
│   │       │   │   │   └── multiselectList.js
│   │       │   │   ├── edit
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── form.js
│   │       │   │   │   │   └── style.css
│   │       │   │   │   └── index.js
│   │       │   │   ├── head
│   │       │   │   │   ├── components
│   │       │   │   │   │   └── buttons.js
│   │       │   │   │   └── index.js
│   │       │   │   ├── list
│   │       │   │   │   └── index.js
│   │       │   │   ├── reducer.js
│   │       │   │   └── select
│   │       │   │       └── index.js
│   │       │   ├── products
│   │       │   │   ├── actions.js
│   │       │   │   ├── actionTypes.js
│   │       │   │   ├── edit
│   │       │   │   │   ├── additional
│   │       │   │   │   │   ├── components
│   │       │   │   │   │   │   ├── form.js
│   │       │   │   │   │   │   ├── productCategoryMultiSelect.js
│   │       │   │   │   │   │   ├── productCategorySelect.js
│   │       │   │   │   │   │   └── style.css
│   │       │   │   │   │   └── index.js
│   │       │   │   │   ├── attributes
│   │       │   │   │   │   ├── components
│   │       │   │   │   │   │   ├── form.js
│   │       │   │   │   │   │   └── style.css
│   │       │   │   │   │   └── index.js
│   │       │   │   │   ├── general
│   │       │   │   │   │   ├── components
│   │       │   │   │   │   │   ├── form.js
│   │       │   │   │   │   │   └── style.css
│   │       │   │   │   │   └── index.js
│   │       │   │   │   ├── images
│   │       │   │   │   │   ├── components
│   │       │   │   │   │   │   └── images.js
│   │       │   │   │   │   └── index.js
│   │       │   │   │   ├── index.js
│   │       │   │   │   ├── inventory
│   │       │   │   │   │   ├── components
│   │       │   │   │   │   │   ├── form.js
│   │       │   │   │   │   │   └── style.css
│   │       │   │   │   │   └── index.js
│   │       │   │   │   ├── option
│   │       │   │   │   │   ├── components
│   │       │   │   │   │   │   ├── option.js
│   │       │   │   │   │   │   ├── style.css
│   │       │   │   │   │   │   └── values.js
│   │       │   │   │   │   └── index.js
│   │       │   │   │   └── variants
│   │       │   │   │       ├── components
│   │       │   │   │       │   ├── grid.js
│   │       │   │   │       │   └── style.css
│   │       │   │   │       └── index.js
│   │       │   │   ├── editHead
│   │       │   │   │   ├── components
│   │       │   │   │   │   └── buttons.js
│   │       │   │   │   └── index.js
│   │       │   │   ├── list
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── head.js
│   │       │   │   │   │   ├── item.js
│   │       │   │   │   │   ├── list.js
│   │       │   │   │   │   └── style.css
│   │       │   │   │   └── index.js
│   │       │   │   ├── listFilter
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── filter.js
│   │       │   │   │   │   └── style.css
│   │       │   │   │   └── index.js
│   │       │   │   ├── listHead
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── buttons.js
│   │       │   │   │   │   └── search.js
│   │       │   │   │   └── index.js
│   │       │   │   └── reducer.js
│   │       │   ├── reports
│   │       │   │   └── ordersBar
│   │       │   │       ├── barChart.js
│   │       │   │       ├── index.js
│   │       │   │       ├── style.css
│   │       │   │       └── utils.js
│   │       │   ├── settings
│   │       │   │   ├── actions.js
│   │       │   │   ├── actionTypes.js
│   │       │   │   ├── checkout
│   │       │   │   │   ├── components
│   │       │   │   │   │   └── form.js
│   │       │   │   │   └── index.js
│   │       │   │   ├── checkoutFields
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── form.js
│   │       │   │   │   │   └── style.css
│   │       │   │   │   └── index.js
│   │       │   │   ├── email
│   │       │   │   │   ├── components
│   │       │   │   │   │   └── form.js
│   │       │   │   │   └── index.js
│   │       │   │   ├── emailTemplates
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── form.js
│   │       │   │   │   │   └── style.css
│   │       │   │   │   └── index.js
│   │       │   │   ├── general
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── form.js
│   │       │   │   │   │   └── style.css
│   │       │   │   │   └── index.js
│   │       │   │   ├── generalLogo
│   │       │   │   │   ├── components
│   │       │   │   │   │   └── form.js
│   │       │   │   │   └── index.js
│   │       │   │   ├── paymentGateway
│   │       │   │   │   ├── availablePaymentGateways.js
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── form.js
│   │       │   │   │   │   ├── gatewaySettings.js
│   │       │   │   │   │   └── style.css
│   │       │   │   │   └── index.js
│   │       │   │   ├── payments
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── form.js
│   │       │   │   │   │   └── headButtons.js
│   │       │   │   │   ├── head.js
│   │       │   │   │   └── index.js
│   │       │   │   ├── paymentsEdit
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── form.js
│   │       │   │   │   │   ├── headButtons.js
│   │       │   │   │   │   ├── selectShipping.js
│   │       │   │   │   │   └── style.css
│   │       │   │   │   ├── head.js
│   │       │   │   │   └── index.js
│   │       │   │   ├── reducer.js
│   │       │   │   ├── shipping
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── form.js
│   │       │   │   │   │   └── headButtons.js
│   │       │   │   │   ├── head.js
│   │       │   │   │   └── index.js
│   │       │   │   ├── shippingEdit
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── fieldsEditor.js
│   │       │   │   │   │   ├── form.js
│   │       │   │   │   │   ├── headButtons.js
│   │       │   │   │   │   └── style.css
│   │       │   │   │   ├── head.js
│   │       │   │   │   └── index.js
│   │       │   │   ├── smtp
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── form.js
│   │       │   │   │   │   └── style.css
│   │       │   │   │   └── index.js
│   │       │   │   ├── theme
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── form.js
│   │       │   │   │   │   └── style.css
│   │       │   │   │   └── index.js
│   │       │   │   ├── themeSettings
│   │       │   │   │   ├── components
│   │       │   │   │   │   ├── arrayEditor.js
│   │       │   │   │   │   ├── dynamicEditControl.js
│   │       │   │   │   │   ├── form.js
│   │       │   │   │   │   ├── imageEditor.js
│   │       │   │   │   │   └── style.css
│   │       │   │   │   └── index.js
│   │       │   │   ├── tokens
│   │       │   │   │   ├── edit
│   │       │   │   │   │   ├── components
│   │       │   │   │   │   │   ├── form.js
│   │       │   │   │   │   │   └── style.css
│   │       │   │   │   │   └── index.js
│   │       │   │   │   └── list
│   │       │   │   │       ├── components
│   │       │   │   │       │   ├── form.js
│   │       │   │   │       │   └── headButtons.js
│   │       │   │   │       ├── head.js
│   │       │   │   │       └── index.js
│   │       │   │   └── webhooks
│   │       │   │       ├── edit
│   │       │   │       │   ├── components
│   │       │   │       │   │   ├── form.js
│   │       │   │       │   │   ├── headButtons.js
│   │       │   │       │   │   └── style.css
│   │       │   │       │   ├── head.js
│   │       │   │       │   └── index.js
│   │       │   │       └── list
│   │       │   │           ├── components
│   │       │   │           │   ├── form.js
│   │       │   │           │   └── headButtons.js
│   │       │   │           ├── head.js
│   │       │   │           └── index.js
│   │       │   └── shared
│   │       │       ├── confirmation
│   │       │       │   └── index.js
│   │       │       ├── deleteConfirmation
│   │       │       │   └── index.js
│   │       │       ├── editor
│   │       │       │   └── index.js
│   │       │       ├── form
│   │       │       │   └── index.js
│   │       │       ├── imageUpload
│   │       │       │   ├── index.js
│   │       │       │   └── style.css
│   │       │       ├── imageUploadMultiple
│   │       │       │   ├── index.js
│   │       │       │   ├── item.js
│   │       │       │   ├── style.css
│   │       │       │   └── uploader.js
│   │       │       ├── productSearch
│   │       │       │   └── index.js
│   │       │       └── tinymce
│   │       │           ├── components
│   │       │           │   └── TinyMCE.js
│   │       │           ├── helpers
│   │       │           │   ├── ucFirst.js
│   │       │           │   └── uuid.js
│   │       │           └── index.js
│   │       ├── rootReducer.js
│   │       └── routes
│   │           ├── apps
│   │           │   ├── index.js
│   │           │   └── login.js
│   │           ├── customers
│   │           │   ├── edit.js
│   │           │   ├── groups
│   │           │   │   └── index.js
│   │           │   └── index.js
│   │           ├── files.js
│   │           ├── home.js
│   │           ├── login.js
│   │           ├── logout.js
│   │           ├── notFound.js
│   │           ├── orders
│   │           │   ├── edit.js
│   │           │   ├── index.js
│   │           │   └── statuses
│   │           │       └── index.js
│   │           ├── pages
│   │           │   ├── edit.js
│   │           │   └── index.js
│   │           ├── products
│   │           │   ├── categories
│   │           │   │   └── index.js
│   │           │   ├── edit.js
│   │           │   └── index.js
│   │           └── settings.js
│   ├── api
│   │   └── server
│   │       ├── ajaxRouter.js
│   │       ├── apiRouter.js
│   │       ├── index.js
│   │       ├── lib
│   │       │   ├── dashboardWebSocket.js
│   │       │   ├── logger.js
│   │       │   ├── mailer.js
│   │       │   ├── mongo.js
│   │       │   ├── parse.js
│   │       │   ├── security.js
│   │       │   ├── settings.js
│   │       │   ├── utils.js
│   │       │   └── webhooks.js
│   │       ├── paymentGateways
│   │       │   ├── index.js
│   │       │   ├── LiqPay.js
│   │       │   ├── PayPalCheckout.js
│   │       │   └── StripeElements.js
│   │       ├── routes
│   │       │   ├── apps.js
│   │       │   ├── customerGroups.js
│   │       │   ├── customers.js
│   │       │   ├── files.js
│   │       │   ├── notifications.js
│   │       │   ├── orders.js
│   │       │   ├── orderStatuses.js
│   │       │   ├── pages.js
│   │       │   ├── paymentGateways.js
│   │       │   ├── paymentMethods.js
│   │       │   ├── productCategories.js
│   │       │   ├── products.js
│   │       │   ├── redirects.js
│   │       │   ├── settings.js
│   │       │   ├── shippingMethods.js
│   │       │   ├── sitemap.js
│   │       │   ├── theme.js
│   │       │   ├── tokens.js
│   │       │   └── webhooks.js
│   │       ├── services
│   │       │   ├── apps
│   │       │   │   └── settings.js
│   │       │   ├── customers
│   │       │   │   ├── customerGroups.js
│   │       │   │   └── customers.js
│   │       │   ├── files.js
│   │       │   ├── orders
│   │       │   │   ├── orderAddress.js
│   │       │   │   ├── orderDiscounts.js
│   │       │   │   ├── orderItems.js
│   │       │   │   ├── orders.js
│   │       │   │   ├── orderStatuses.js
│   │       │   │   ├── orderTransactions.js
│   │       │   │   ├── paymentMethods.js
│   │       │   │   ├── paymentMethodsLight.js
│   │       │   │   ├── shippingMethods.js
│   │       │   │   └── shippingMethodsLight.js
│   │       │   ├── pages
│   │       │   │   └── pages.js
│   │       │   ├── products
│   │       │   │   ├── images.js
│   │       │   │   ├── options.js
│   │       │   │   ├── optionValues.js
│   │       │   │   ├── productCategories.js
│   │       │   │   ├── products.js
│   │       │   │   ├── stock.js
│   │       │   │   └── variants.js
│   │       │   ├── redirects.js
│   │       │   ├── security
│   │       │   │   └── tokens.js
│   │       │   ├── settings
│   │       │   │   ├── checkoutFields.js
│   │       │   │   ├── email.js
│   │       │   │   ├── emailTemplates.js
│   │       │   │   ├── paymentGateways.js
│   │       │   │   └── settings.js
│   │       │   ├── sitemap.js
│   │       │   ├── theme
│   │       │   │   ├── assets.js
│   │       │   │   ├── placeholders.js
│   │       │   │   ├── settings.js
│   │       │   │   └── theme.js
│   │       │   └── webhooks.js
│   │       └── setup.js
│   └── store
│       ├── client
│       │   ├── api.js
│       │   ├── index.js
│       │   └── settings.js
│       ├── server
│       │   ├── api.js
│       │   ├── index.js
│       │   ├── loadState.js
│       │   ├── logger.js
│       │   ├── pageRendering.js
│       │   ├── readIndexHtml.js
│       │   ├── redirects.js
│       │   ├── robotsRendering.js
│       │   ├── settings.js
│       │   ├── sitemapRendering.js
│       │   └── themeLocales.js
│       └── shared
│           ├── actions.js
│           ├── actionTypes.js
│           ├── analytics
│           │   ├── googleAnalytics.js
│           │   └── index.js
│           ├── app.js
│           ├── containerProps.js
│           ├── containers
│           │   ├── category.js
│           │   ├── checkout.js
│           │   ├── checkoutSuccess.js
│           │   ├── index.js
│           │   ├── notfound.js
│           │   ├── page.js
│           │   ├── product.js
│           │   ├── search.js
│           │   └── shared.js
│           ├── lib
│           │   ├── helper.js
│           │   └── jsonld.js
│           ├── pageTypes.js
│           └── reducers.js
├── theme
│   ├── assets
│   │   ├── images
│   │   │   ├── arrow_back.svg
│   │   │   ├── arrow_down.svg
│   │   │   ├── arrow_right.svg
│   │   │   ├── close.svg
│   │   │   ├── icons
│   │   │   │   ├── icon-128.png
│   │   │   │   ├── icon-16.png
│   │   │   │   ├── icon-256.png
│   │   │   │   ├── icon-32.png
│   │   │   │   └── icon-512.png
│   │   │   ├── logo.png
│   │   │   ├── payment
│   │   │   │   ├── alipay.svg
│   │   │   │   ├── amex.svg
│   │   │   │   ├── diners.svg
│   │   │   │   ├── discover.svg
│   │   │   │   ├── hipercard.svg
│   │   │   │   ├── jcb.svg
│   │   │   │   ├── maestro.svg
│   │   │   │   ├── mastercard.svg
│   │   │   │   ├── paypal.svg
│   │   │   │   ├── unionpay.svg
│   │   │   │   └── visa.svg
│   │   │   ├── search.svg
│   │   │   ├── shopping-bag.svg
│   │   │   ├── slide7.jpg
│   │   │   ├── slide8.jpg
│   │   │   ├── slide9.jpg
│   │   │   ├── success.svg
│   │   │   └── thin_arrow_right.svg
│   │   ├── manifest.json
│   │   └── scss
│   │       ├── cart.scss
│   │       ├── category.scss
│   │       ├── checkout.scss
│   │       ├── custom.scss
│   │       ├── footer.scss
│   │       ├── header.scss
│   │       ├── homeSlider.scss
│   │       ├── page.scss
│   │       ├── product.scss
│   │       └── theme.scss
│   ├── index.html
│   ├── locales
│   │   ├── de.json
│   │   ├── en.json
│   │   ├── fr.json
│   │   ├── it.json
│   │   ├── ru.json
│   │   ├── uk.json
│   │   └── zh_CN.json
│   ├── package.json
│   ├── settings
│   │   ├── de.json
│   │   ├── en.json
│   │   ├── it.json
│   │   ├── ru.json
│   │   ├── settings.json
│   │   └── zh_CN.json
│   └── src
│       ├── components
│       │   ├── categoryBreadcrumbs.js
│       │   ├── checkoutForm
│       │   │   ├── index.js
│       │   │   ├── inputField.js
│       │   │   ├── paymentForm
│       │   │   │   ├── index.js
│       │   │   │   ├── LiqPay.js
│       │   │   │   ├── PayPalCheckout.js
│       │   │   │   └── StripeElements
│       │   │   │       ├── CardSection.js
│       │   │   │       ├── CheckoutForm.js
│       │   │   │       ├── index.js
│       │   │   │       └── StoreCheckout.js
│       │   │   ├── stepContacts.js
│       │   │   ├── stepPayment.js
│       │   │   ├── stepShipping.js
│       │   │   └── textareaField.js
│       │   ├── checkoutSuccess.js
│       │   ├── comments
│       │   │   └── disqus.js
│       │   ├── footer.js
│       │   ├── header
│       │   │   ├── cartIndicator.js
│       │   │   ├── cart.js
│       │   │   ├── headMenu.js
│       │   │   ├── index.js
│       │   │   └── searchBox.js
│       │   ├── homeSlider.js
│       │   ├── metaTags.js
│       │   ├── orderSummary.js
│       │   ├── pageList
│       │   │   ├── index.js
│       │   │   ├── item.js
│       │   │   └── list.js
│       │   ├── productDetails
│       │   │   ├── addToCartButton.js
│       │   │   ├── attributes.js
│       │   │   ├── breadcrumbs.js
│       │   │   ├── discountCountdown.js
│       │   │   ├── gallery.js
│       │   │   ├── index.js
│       │   │   ├── options.js
│       │   │   ├── price.js
│       │   │   ├── quantity.js
│       │   │   ├── relatedProducts.js
│       │   │   └── tags.js
│       │   ├── productFilter
│       │   │   ├── attributeFilter.js
│       │   │   ├── index.js
│       │   │   └── priceSlider.js
│       │   ├── productList
│       │   │   ├── index.js
│       │   │   ├── itemImage.js
│       │   │   ├── item.js
│       │   │   ├── itemPrice.js
│       │   │   ├── itemTags.js
│       │   │   └── loadMore.js
│       │   ├── products
│       │   │   ├── custom.js
│       │   │   └── viewed.js
│       │   └── sort.js
│       ├── containers
│       │   ├── category.js
│       │   ├── checkout.js
│       │   ├── checkoutSuccess.js
│       │   ├── index.js
│       │   ├── notfound.js
│       │   ├── page.js
│       │   ├── product.js
│       │   ├── search.js
│       │   └── shared.js
│       ├── index.js
│       └── lib
│           ├── api.js
│           ├── helper.js
│           └── settings.js
├── webpack.config.admin.js
└── webpack.config.store.js
```

228 directories, 672 files
