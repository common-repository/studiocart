=== eCommerce Shopping Cart and Funnel Builder - Studiocart ===

Contributors: ncstudio
Tags: eCommerce, shopping cart, sales funnel, elementor
Requires at least: 5.0.1
Tested up to: 6.5.3
Stable tag: 2.7
Requires PHP: 8.0
License: GPLv3
License URI: https://www.gnu.org/licenses/gpl-3.0.html

Create on-brand order and thank you pages for your digital products, programs, and services.

== Description ==

Studiocart is a simple, powerful plugin that has everything you need to sell digital products, programs, events, or services from your own website –– exactly the way YOU want to sell them. Whether you’re a health coach or consultant, business newbie or seasoned entrepreneur, Studiocart gives you the tools to create on-brand checkout pages and sales flows for your digital products in minutes – No coding necessary.

### FEATURES ###

* **Thank You Pages and Redirects:**
Display a custom thank you page or redirect customers to another website after they complete their purchase.

* **Embed an order form anywhere**
Use the included shortcode to turn any page on your website into a checkout page so that you can create a fully on-brand shopping experience for your customers.

* **Product Launch Automation:**
If you have a limited amount of spots to sell, or your product is only on sale during a certain window of time, Studiocart will help you automate your launch. Schedule your cart open dates, or manually turn your checkout page on and off with one click. Shut down your checkout page after a certain amount of sales and redirect cart closed visitors to a waitlist page. No matter what your sales scenario is, you have full control.

* **One-time payments, installment plans and subscriptions:**
Easily set up multiple pay options for a product and increase conversions by letting customers choose the payment plan that works best for their budget.

* **Automatically Add Buyers to a Mailing List:**
Some shopping cart plugins make you add all buyers to the same list no matter what product they buy – if they even allow you to add buyers to a mailing list at all. Studiocart lets you choose what mailing list or tag to add a buyer to on a per product basis.

How to Use Studiocart
[youtube https://www.youtube.com/watch?v=uLDxhqXMhLY]

### LISTEN TO WHAT PEOPLE HAVE TO SAY: ###

➡️ “If you need a funnel, this is the one! I was looking for a simple to use funnel program for WordPress and stumbled upon Studiocart. So impressed with this product - I envision big things.”

➡️ “Studiocart is really built with the eye of a marketer to sell your products, licenses, courses, etc. with great efficiency… SC gives you really all the tools/flexibility you need, without all the work and bugs that come with custom built solutions.”

➡️ “Wow, this is making it so easy for me to ditch WooCommerce finally. Do you think you ever need some kind of funnel builder? Get Studiocart now and you will have the easiest with really good support.”

➡️ “Tremendous value and features compared to other similar products out there.”

**Want to know all the latest news and be part of the Studiocart community?** Join our Facebook [Studiocart Community group!](https://www.facebook.com/groups/457152288834427)

== Installation ==

1. Upload the plugin files to the `/wp-content/plugins` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress
3. Use the Settings->Studiocart->Settings screen to configure the plugin

== Frequently Asked Questions ==

= What payment processors can I use with Studiocart? =
Studiocart fully supports Stripe and PayPal. [Upgrade to Pro to add-on Square, Mollie and Razorpay.](https://www.studiocart.co/) 

= Does Studiocart work in my language? =
Studiocart works in English, but can be translated into another language with a free translation plugin like [Loco Translate.](https://www.studiocart.co/docs/general/how-to-translate-studiocart-into-another-language/)

= What integrations are available? =
Studiocart currently works with ActiveCampaign, MailChimp, ConvertKit, MemberVault and MailPoet - Upgrade to Pro for [more integration options.](https://www.studiocart.co/integrations/) 

= I have a question not listed here? =
Email us at support@studiocart.co

== Screenshots ==

1. Create beautiful, on-brand, high-converting checkout pages.
2. Embed an order form anywhere on your website.
3. Schedule when your order page is accessible and select what visitors see when the cart is closed.
4. Setup multiple pay options for a product including one-time payments, installment plans and ongoing subscriptions.
5. Easily configure what happens after an order is placed with a few clicks.

== Changelog ==

= 2.7 =
* New: Sales dashboard widget
* New: More search filters for orders and subscriptions

= 2.6.4 =
* New: sc_update_stripe_invoice_during_checkout filter
* New: sc_order_summary_item_name filter
* Fix: admin CSS conflict with WP Fusion
* Fix: Change stripe statement_descriptor_suffix paramter
* Fix: Unable to change Stripe card

= 2.6.3 =
* Update: Fix for Stripe invoice webhook update
* Fix: Error when MailChimp group or tag dropdowns are empty
* Fix: Missing product settings for privacy and terms checkbox

= 2.6.2 =
* Update: Added debug log info when creating order items
* Fix: Payment plan not selected when using 'plan' URL parameter
* Fix: Stripe webhook not updating order status on payment reattempts

= 2.6.1 =
* Fix: Unexpected results when converting 4 digit or more prices to cents
* Fix: ConvertKit and MailChimp integration dropdown fields not saving
* Fix: Intermittent "Unauthorized" error when viewing invoices

= 2.6 =
* New: Secure download links
* New: Order complete email
* New: Attach PDF invoice to order emails
* New: Subscription cancel integration
* New: Order refund integration
* New: Store report email
* New: Support for multiple checkout forms on a single page
* Update: Update script to standardize currency formatting in database
* Fix: Inconsistent currency formatting for non-US formats
* Fix: Warning errors

= 2.5.22 =
* Update: Add phone and address to order exports
* Fix: Stuck checkout page with Google recaptcha and Stripe 3DS secure payment
* Fix: Warning errors
* Fix: Show sub_amount in webhook payload
* Fix: Apply email template to new user welcome emails

= 2.5.21 =
* Fix: Receipt tax format 

= 2.5.20 =
Update: Freemius SDK v2.5.10
Update: add wpfc_exclude_current_page function for WP Fastest Cache

= 2.5.19 =
* New: Filter sc_subtotal_label
* New: Filter sc_company_name_field_id
* Update: Reset product view and conversion stats
* Update: Freemius SDK 2.5.6
* Fix: Incorrect number formatting when using custom decimal separator

= 2.5.18 =
* Fix: Discounted subscriptions show the full discount amount instead of the recurring discount amount
* Fix: Warning errors
* Fix: Optional address fields show as required when editing products
* Fix: Allow selection of on sale options when creating manual orders
* Fix: New role field in update user integration missing on load

= 2.5.17 =
* New: User capabilities and "Cart Manager", "Cart Admin" user roles 
* Update: Personalization tag for invoice links
* Update: Dompdf 2.0
* Update: Add checkout page URL to order data for site admin orders

= 2.5.16 =
* New: Shortcodes sc_customer_bought_product and sc_customer_has_subscription
* Update: Dynamic template for PDF invoice
* Fix: Google universal tag transation ID
* Fix: Strings not translating in customer account area
* Fix: Manually editing upsell order removes product details

= 2.5.15 =
* Update: Load Studiocart files on Studiocart pages only
* Fix: Warning errors
* Fix: Trigger renewal failed integrations for "Uncollectible" status
* Fix: signup_consent field missing from webhook payload if not checked
* Fix: Duplicate order post in case of failed Stripe payments
* Fix: Error when using bulk updater
* Fix: Incorrect VAT amount shown in webhook body

= 2.5.14 =
* New: bulk update
* New: sc_product shortcode
* Fix: Custom invoice number bug

= 2.5.13 =
* New: filter sc_stripe_api_version
* New: filter sc_webhook_url_type
* New: filter sc_email_template_customer_info
* New: Add change address fields to account and edit user profile pages
* Update: Show manage subscription button for more subscription statuses
* Update: Pay latest unpaid invoice when customer updates their card
* Update: Hash Google Captcha secret key field
* Update: Edit subscriber information in admin dashboard
* Fix: Completed orders not counted when a product has a customer purchase limit
* Fix: Separate sign up fee on invoice, confirmation
* Fix: Coupon discount amount in email is always 0
* Fix: Edit order address fields not working
* Fix: Create User integration doesn't link the original subscription to the new user account
* Fix: Make Phone and Address Line 2 fields optional by default
* Fix: Order status not updating when Stripe subscription is recovered
* Fix: Name missing when adding customers to ConvertKit with no form selected

= 2.5.12 =
* New: filter sc_current_user_orders_meta_query_args
* New: Thousands and decimal separator currency settings
* New: Filter: sc_admin_notification_email
* Fix: Customer purchase limit not working with Stripe orders
* Fix: Checkout form not submitting some Stripe orders

= 2.5.11 =
* New: Order received email for COD orders
* Update: "tab: shortcode attribute to display my account tabs separately
* Update: Hide subscriptions cancellation setting when creating installment plans
* Fix: Incorrect order amount formatting in CSV export when using 0 decimal places

= 2.5.10 =
* New: filters sc_valid_sub_statuses_for_pause_restart and sc_is_sub_type_valid_for_pause_restart
* Update: Invoice links that can be viewed without logging in
* Fix: Warning errors

= 2.5.9 =
* New: Purchase notes field in product settings
* New: Order details view in customer account page
* Update: Disable confirmation email when adding existing Mailpoet subscribers to a new list

= 2.5.8 = 
* Update: Add getting started video course to Resources
* Update: Show free orders in customer account page

= 2.5.7 =
* Update: submit button styles

= 2.5.6 =
* Update: Select Google Analytics version for purchase event tracking
* Update: Some integration fields not visible

= 2.5.5 = 
* Update: Autologin and opt-in/consent product settings moved to Integrations tab
* Update: Pass country locale to PayPal
* Update: HTML changes for tax description
* Fix: Payment plan dropdowns in product settings are blank if no label is filled in 
* Fix: Product ID not passed when creating Stripe payment intent

= 2.5.4.1 = 
* Fix: Admin UI fixes and tweaks

= 2.5.4 = 
* New: Custom Invoice numbering
* New: "Edit Profile" tab in customer account area
* Update: templating and API functions
* Update: ActiveCampaign SDK update

= 2.5.3 = 
* New: Order refund email notification

= 2.5.2 = 
* Fix: Update default payment method for Stripe if missing
* Fix: Phone field not showing

= 2.5.1 = 
* New: Filter sc_use_default_authentication_logic
* Update: Add "user" key for storing user info in order data
* Fix: Tracking scripts missing order ID
* Fix: Warning error on new products

= 2.5 = 
* New: Import custom tax rates via CSV 
* New: Google Analytics purchase tracking
* Fix: Prevent redirect to Studiocart login page from other plugin login pages
* Fix: PayPal subscription pause not working
* Fix: PayPal thank you page redirect
* Fix: Warning error on new orders
* Fix: Subscription renewal order amount not showing tax

= 2.4.2.1 =
* Fix: Default field info not saved after rearranging field order

= 2.4.2 =
* New: Filter sc_select_page_post_types
* Update: Add email template file 
* Fix: Manual orders have a 0 amount
* Fix: Incorrect post ID in function sc_maybe_rebuild_custom_post_data
* Fix: Handle "Stripe customer ID missing" error on customer account page

= 2.4.1 =
* Update: Add invoice download link to admin order page
* Update: hide_login attribute added to my_account shortcode
* Update: show VAT number on invoices
* Fix: Stripe webhook not created when keys are changed
* Fix: New order email confirmations sent for subscription renewals
* Fix: Remove duplicate update user integration field
* Fix: login url personalization tag returning page ID instead of URL

= 2.4 =
* New: Email previews and test sends
* New: Add password reset to login form
* New: Insert personalization tag helper for email body fields

= 2.3.3.2 =
* Update: Create user integration now updates existing user roles
* Update: WYSIWYG editor for order emails
* Update: Separate line item for sign up fee on order confirmation email
* Fix: User ID not added to subscriptions when creating new users
* Fix: Cancel button still visible after canceling subscription

= 2.3.3.1 =
* Fix: "Invalid subscription ID" error when cancelling subscription from customer account page

= 2.3.3 =
* New: Filter studiocart_product
* New: Filter sc_valid_sub_statuses_for_cancel
* New: Filter sc_is_sub_type_valid_for_cancel
* Fix: Admin color picker field plugin conflict

= 2.3.2.7 =
* Fix: Validation not working for state dropdown

= 2.3.2.6 =
* New: studiocart_order_created and studiocart_order_updated actions
* Update: Move product "Tax Status" setting to General tab
* Update: Minor admin UI updates

= 2.3.2.3 =
* Fix: Error when using upload image field
* Fix: Stripe Tax IDs not updating

= 2.3.2.1 =
* Fix: Enhanced State and Country dropdowns not working with shortcode

= 2.3.2 =
* New: Function sc_maybe_format_date()
* Update: Added all order information to sc_get_orders()
* Update: Auto remove spaces in payment plan IDs 
* Fix: Pay What You Want only charging minimum amount
* Fix: My Account Order table not scrolling on mobile
* Fix: Page hangs when purchasing upsell with COD gateway
* Fix: Warning errors in debug mode
* Fix: PayPal PDT settings missing
* Fix: Valid VAT number failing validation

= 2.3.1 =
* Update: Rename product stats to submission stats
* Update: Freemius SDK version 2.4.3 
* Update: RTL css for order form
* Fix: Checkout error with taxes after changing Stripe mode

= 2.3 =
* New: Tax and VAT Support 
* New: sc_plan shortcode for showing payment plan name and price
* New: sc_after_validate_meta action 
* New: Global Order and Subscription emails
* New: studiocart_account shortocde for customer account
* New: Name your price payment plan
* Update: Cancel subscriptions at end of current billing period
* Update: Add sc_before_create_main_order action to subscriptions

= 2.2.8.12 =
* Update: Add "Hide plan?" switch to all payment plan types
* Fix: Repeater field selections can move to wrong set of repeater fields

= 2.2.8.11 =
* Fix: Server side validation not ignoring required fields when hidden

= 2.2.8.9 =
* Update: Additional server side validation of checkout form
* Update: Add custom field map to ActiveCampaign integration

= 2.2.8.7 =
* Update: Do nonce check before creating Stripe payment intent

= 2.2.8.6 =
* Fix: Create pending order before sending a payment intent to Stripe for one time charges
* Fix: Warning errors

= 2.2.8.5 =
* Update: Allow personalization tags in tracking fields
* Fix: ActiveCampaign unsubscribe integration adds tag instead of removes

= 2.2.8.4 =
* Fix: Code optimization for "Select User" dropdown
* Fix: Stripe error with subscriptions when adding an order bump

= 2.2.8.3 =
* New: New action sc_stripe_invoice_response

= 2.2.8.2 =
* Fix: Warning errors

= 2.2.8.1 =
* Fix: Browser autocomplete changing value in Stripe key field

= 2.2.8 =
* New: subscription renewal integrations
* New: New filter sc_charge_amount
* Update: Add description for set up fee on Stripe receipt
* Fix: PayPal error when checking out daily subscriptions
* Fix: PayPal upsell integrations not running when using PDT
* Fix: Integrations not running when when first payment attempt in a subscription fails

= 2.2.7.4 =
* New: sc_paypal_payment_vars, sc_mailchimp_merge_data filters, sc_paypal_recurring_payment_data action
* Fix: New orders not created for PayPal subscription renewal payments
* Fix: Invalid ID error message when cancelling some subscriptions
* Fix: PayPal webhook returning 403 error on some websites 
* Fix: PayPal not triggering integrations when PDT is active and using a redirect
* Fix: Check Stripe subscription orders by charge ID not invoice ID

= 2.2.7.3 =
* Update: Remove limit on amount of related orders shown
* Fix: Redirect url not handling & and @ symbols
* Fix: Default thank you page redirects to URL set in default product page redirect
* Fix: LastPass autofilling password fields

= 2.2.7.2 =
* Update: Make subscription interval translatable
* Fix: Selectize script enqueued incorrectly
* Fix: PayPal subscriptions not creating new orders

= 2.2.7.1 =
* Fix: Order info shortcodes not working on first upsell page
* Fix: Public product name not used on Stripe subscription invoices
* Fix: Admin javascript errors

= 2.2.7 =
* Fix: Error handling for rest hooks
* Fix: Special characters throwing off character count for Stripe statement description text
* Fix: Custom field personalization tags not working in notification emails

= 2.2.6.4 =
* Fix: Settings field values changing due to autocomplete
 
= 2.2.6.3 =
* Fix: Error creating new customers in Stripe

= 2.2.6.2 =
* New: new action 'studiocart_after_order_created'
* New: Redirect default product pages to a custom page
* Fix: New Stripe customer IDs always created instead of checking for an existing customer ID

= 2.2.6.1 =
* Fix: Duplicate prices being created in Stripe

= 2.2.6 =
* New: {username} personalization tag
* New: Verify PayPal payments with PDT 
* New: Verify Stripe payments when checkout form is submitted
* Fix: Product purchased integrations running for PayPal renewal orders
* Fix: Product tag and category metaboxes missing
* Fix: HTML emails adding extra lines

= 2.2.5.7 =
* Fix: Warning errors

 2.2.5.3 =
* Update: Store product name with order data 
* Update: Add all integration event triggers to resthook API
* Update: Separate order info shortcodes for product name and plan name
* Update: Support description text for checkout form fields
* Fix: Order page url not saved with subscriptions orders
* Fix: Shortcode default styles

= 2.2.5.2 =
* Fix: Admin order styling

= 2.2.5.1 =
* New: Have multiple triggers for a single integration
* Update: Limit for pulled MailChimp tags and groups increased to 100
* Update: Help text and link to doc on going live with Stripe subscriptions added to Stripe API dropdown
* Fix: Empty error message shown when trying to cancel a live PayPal subscription
* Fix: stripe.js scripts loading site-wide
* Fix: styles and scripts conflicts with other plugins in WP admin
* Fix: Incorrect next payment date shown on subscription details page for PayPal subscriptions

= 2.2.5 =
* Update: Render line breaks in email notifications
* Update: Help text for "on sale" checkbox
* Update: Generate more secure passwords when creating new users
* Update: Checkbox error formatting
* Update: Text field for ActiveCampaign tags
* Fix: Empty value saved as order amount for free orders
* Fix: Stripe refunds not working for subscription orders

= 2.2.4.2 =
* Fix: Incorrect order amount sent to Stripe when using zero decimal currencies
* Fix: Warning errors when WP_DEBUG set to true 

= 2.2.4.1 =
* Update: Security hardening

= 2.2.4 =
* Fix: Error when trying to purchase a Stripe subscription 
* Fix: Warning errors when WP_DEBUG set to true 

= 2.2.3 =
* Fix: Wrong product shown in subscription orders for duplicated products 
* Fix: Style conflict with Kadence Blocks editor styles
* Fix: Stripe sometimes produces an error message when checking out a subscription on mobile  

= 2.2.2 =
* Fix: Security hardening
* Fix: Problems creating and saving Stripe orders if credit card info isn't submitted correctly on the first try. 

= 2.2.1.14 =
* Update: Added "Cancelled" status to WishList Member integration
* Update: Added custom fields to personalization tags
* Fix: Plan ID not sent to Zapier
* Fix: Security hardening

= 2.2.1.11 =
* New: Compatibility with WordPress' GDPR compliance functionality
* Update: Added WishList Member custom fields for Stripe ID and order ID
* Fix: Fluent CRM integration not showing up on some websites
* Fix: Warning errors in WP_Debug mode

= 2.2.1.9 =
* Fix: Stripe secret keys visible by default in Payment Method Settings

= 2.2.1.8 =
* Update: Add descriptions to Stripe subscription products and one-time charges

= 2.2.1.7 =
* Fix: Phone number missing from Stripe orders
* Fix: Personalization tag exposed if info isn't present

= 2.2.1.6 =
* Fix: SendFox only pulling a maximum of 10 lists
* Fix: Unable to set number of decimals for currencies to "0"

= 2.2.1.2 =
* Fix: Username and password from custom fields not used with subscription orders
* Fix: Warning error on product edit page
* Fix: PayPal orders stuck in "pending" status

= 2.2.1 =
* Fix: Unable to check some checkboxes in product repeater fields

= 2.2.0 =
* Update: Product settings UI styling
* Fix: Warning messages in debug mode
* Fix: {customer_phone} personalization tag not working
* Fix: Stripe and PayPal refund/cancel subscription buttons not working

= 2.1.29 =
* Update: Order form page scripts moved to public javascript file
* Fix: ConvertKit tags list not refreshing
* Fix: Stripe webhook sometimes reporting a 400 error when successful, 
* Fix: Webhook not firing for lead captured trigger

= 2.1.28 =
* New: Turn on option to show full price when on sale
* Fix: Warning messages in debug mode
* Fix: Name personalization tag not working
* Fix: No order info on thank you page when paying COD
* Fix: ConvertKit tags not refreshing

= 2.1.27 =
* Fix: Test code present in order forms and integrations

= 2.1.26 =
* New: Integration trigger for pending order created
* Update: apply product settings to order forms rendered by shortcode
* Fix: Product name and amount personalization tags displaying incorrect information,
* Fix: Fatal error caused by sc_localize_datetime function
* Fix: Unexpected order form behavior when a payment plan is switched from one type to a another (e.g. from one-time charge to free)

= 2.1.25 =
* New: Setting to turn off Studiocart's product template so you can use one from your theme or page builder
* Fix: International phone numbers fail order form validation
* Fix: Some order form text not translatable
* Update: The order form shortcode can now be used dynamically for use in custom single product templates
* Update: Removed ConvertKit API PHP wrapper
* Update: Show error messages in order form shortcode
* Update: Add product and order amount info to personalization tags and shortcodes
* Update: Link to additional test cards added to Stripe test-mode message on order form

= 2.1.24 =
* Fix: Rewew Lists button not working
* Fix: Error on new install because no currency selection is found

= 2.1.23 =
* New: Support for right currency symbol positions
* Update: Add nocache headers to redirects
* Fix: Initial payment is not charged at the same time as the sign-up fee when using PayPal 

= 2.1.22 =
* Fix: ActiveCampaign not fetching lists and tags
* Fix: PayPal throwing an error on one-time charges when address fields are disabled 
* Update: Clearer wording of recurring payment text under order form total
* Update: Load language file on 'init' hook instead of 'plugins loaded'
* Update: Changed "Amount Paid" to "Total" on order details confirmation
* Update: Check site origin for subscription invoices in Stripe webhook

= 2.1.21 =
* Fix: Stripe error shown when saving a product for the first time

= 2.1.19 =
* Fix: Incorrect amount due shown in some cases on the order form

= 2.1.18 =
* New: Recurring payments for PayPal
* New: Add sign up fees and free trials for recurring payment plans
* New: Added new filters, studiocart_order_details_link and studiocart_subscription_details_link
* New: Freemius SDK update to version 2.4.2
* Improvement: UI changes for managing payment processors and integration settings
* Improvement: Global on/off toggles for all payment methods (Cash on Delivery, Stripe and PayPal)
* Improvement: Validation for required product fields
* Improvement: Can now issue partial refunds for both PayPal and Stripe
* Fix: Internal product title still showing up when a public title has been entered
* Fix: Unable to clear out date picker fields
* Fix: Inconsistent formatting for prices on order confirmation page
* Fix: Warning errors on some sites after a 2nd attempt at submitting the order form

= 2.1.17 =
* Improvement: Admin responsive styling

= 2.1.16 =
* Fix: No payment method info is shown on checkout forms when using only PayPal

= 2.1.15 =
* Fix: Missing API keys for multisite subsites
* Fix: Fatal error in some installations caused by FluentCRM integration 

= 2.1.14 =
* Fix: studiocart_order_form_fields filter wasn't working on 2-step forms

= 2.1.13 =
* Bug Fix: Public product title bug fix
* Improvement: Render html in email notifications
* New: function sc_get_order_user_id
* Thank You page template mobile css
* Integration label changes

= 2.1.12 =
* Code optimizations for integrations

= 2.1.11 =
* Enhancement: Add total amount paid to order receipt

= 2.1.10 =
* Bug Fix: Error when saving a product with a recurring payment plan when switching Stripe modes

= 2.1.9 =
* Bug Fix: New user ID not added to order information when created by the Add User integration
* Record pay method as 'manual' for manually created orders

= 2.1.8 =
* Bug Fix: Subscription/order post columns showing the wrong info, not sorting properly 
* Bug Fix: Public product title not being sent to payment processor

= 2.1.7 =
* Bug fix: Order based coupon validation
* Bug fix: Change product input field name causing warning errors
* New $studiocart global for storage of NCS_Cart_Public class

= 2.1.6 =
* PayPal payment gateway

= 2.1.5 =
* Set order form default field values via url
* New filter: studiocart_order_form_fields

= 2.1.4 =
* Product page styling fixes
* New filter: studiocart_slug
* Simplified URLs in order stats

= 2.1.3 =
* Bug fix: resolve admin warning errors

= 2.1.0 =
* New product template
* Change 'pending-payment' status to 'pending'
* Add site origin url to Stripe metdata
* Bug Fix: Do integrations on manual orders and on status change
* Bug Fix: Allow manual/COD orders

= 2.0.153 =
* Bug Fix: On sale pricing not sent to Stripe

= 2.0.151 = 
* Code clean up

= 2.0.15 =
* Public product name field
* Filterable variable for plugin name
* payment plan UX edits

= 2.0.14 =
* Bug Fix: Add plan id for one time charges
* Bug Fix: Hide integration fields when no action selected

= 2.0.13 =
* Payment methods filter and logic
* Dropdown styling, tracking scripts positioning

= 2.0.12 =
* Javascript tracking fields for products
* Order receipt and shortcode
* Initiated status changed to "pending payment", 
* Free product processing
* Page conversion tracking
* Add all Stripe supported currencies
* Bug Fix: checkout shortcode hide labels arg
* Bug Fix: restrict save_order action to edit post page
* Bug Fix: order form validation
* Bug Fix: option settings checkbox default value 
* Bug Fix: stripe statement descriptor max length

= 2.0.1 =
* Add support for tags to ActiveCampaign integration
* Add reports page
* Upgrade Stripe API to payment intents for charges, subscriptions, coupons, and order bumps
* Add "Accept Terms" checkbox
* Bug Fix: Upsell decline url

= 2.0.0 =
* Override $scp global in date functions
* Add ActiveCampaign integration
* Stripe test mode message on checkout page
* Admin fields rewrite, remove Carbon Fields
* Hide phone field toggle
* Facebook ad event tracking
* Bug Fix: Upsell redirect url
* Bug Fix: add tags/groups to existing MailChimp subscribers
* Bug Fix: Create manual order error
* Bug Fix: Refund error

= 1.0.2 =
* Translatable text update
* Add payment plan selection to integrations
* Add merge fields to notification emails

= 1.0.1.1 =
* Change limit on MC tags to 100 
* Add pay plan selection to integrations 
* Bug Fix: Add step=“any” to price fields
* Bug Fix: Incorrect formatting of order total on checkout page
* Bug Fix: Update subscription next bill date after subsequent charges
 
= 1.0.1 =
* Removes Stripe scripts on non-checkout pages
* Plugin internationalization 
 
= 1.0.0 =
* First Release