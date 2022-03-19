# List-of-all-the-events-in-magento-2

# File                                                                            Event name


app/code/Magento/Authorizenet/Controller/Directpost/Payment/Place.php   				checkout_directpost_placeOrder
app/code/Magento/Backend/Block/System/Store/Edit/AbstractForm.php   					adminhtml_store_edit_form_prepare_form
app/code/Magento/Backend/Block/Template.php 								adminhtml_block_html_before
app/code/Magento/Backend/Block/Widget/Grid.php  							backend_block_widget_grid_prepare_grid_before
app/code/Magento/Backend/Console/Command/CacheCleanCommand.php  					adminhtml_cache_flush_system
app/code/Magento/Backend/Console/Command/CacheFlushCommand.php  					adminhtml_cache_flush_all
app/code/Magento/Backend/Controller/Adminhtml/Cache/CleanImages.php 					clean_catalog_images_cache_after
app/code/Magento/Backend/Controller/Adminhtml/Cache/CleanMedia.php  					clean_media_cache_after
app/code/Magento/Backend/Controller/Adminhtml/Cache/CleanStaticFiles.php    				clean_static_files_cache_after
app/code/Magento/Backend/Controller/Adminhtml/Cache/FlushAll.php    					adminhtml_cache_flush_all
app/code/Magento/Backend/Controller/Adminhtml/Cache/FlushSystem.php 					adminhtml_cache_flush_system
app/code/Magento/Backend/Controller/Adminhtml/System/Design/Save.php    				theme_save_after
app/code/Magento/Backend/Controller/Adminhtml/System/Store/DeleteStorePost.php 				store_delete
app/code/Magento/Backend/Controller/Adminhtml/System/Store/Save.php 					store_group_save
app/code/Magento/Backend/Controller/Adminhtml/System/Store/Save.php 					NO_MATCH
app/code/Magento/Backend/Model/Auth.php 								backend_auth_user_login_success
app/code/Magento/Backend/Model/Auth.php 								backend_auth_user_login_failed
app/code/Magento/Backend/Model/Auth.php 								backend_auth_user_login_failed
app/code/Magento/Bundle/Block/Catalog/Product/View/Type/Bundle.php  					catalog_product_option_price_configuration_after
app/code/Magento/Bundle/Model/Product/Price.php 							prepare_catalog_product_collection_prices
app/code/Magento/Bundle/Model/Product/Price.php 							catalog_product_get_final_price
app/code/Magento/Bundle/Model/Product/Price.php 							catalog_product_get_final_price
app/code/Magento/Bundle/Model/ResourceModel/Indexer/Price.php   					catalog_product_prepare_index_select
app/code/Magento/Bundle/Pricing/Price/BundleSelectionPrice.php  					catalog_product_get_final_price
app/code/Magento/Catalog/Block/Adminhtml/Category/Tab/Attributes.php    				adminhtml_catalog_category_edit_prepare_form
app/code/Magento/Catalog/Block/Adminhtml/Category/Tabs.php  						adminhtml_catalog_category_tabs
app/code/Magento/Catalog/Block/Adminhtml/Category/Tree.php  						adminhtml_catalog_category_tree_is_moveable
app/code/Magento/Catalog/Block/Adminhtml/Category/Tree.php  						adminhtml_catalog_category_tree_can_add_root_category
app/code/Magento/Catalog/Block/Adminhtml/Category/Tree.php  						adminhtml_catalog_category_tree_can_add_sub_category
app/code/Magento/Catalog/Block/Adminhtml/Product/Attribute/Edit/Tab/Advanced.php    			product_attribute_form_build
app/code/Magento/Catalog/Block/Adminhtml/Product/Attribute/Edit/Tab/Front.php   			product_attribute_form_build_front_tab
app/code/Magento/Catalog/Block/Adminhtml/Product/Attribute/Edit/Tab/Front.php   			adminhtml_catalog_product_attribute_edit_frontend_prepare_form
app/code/Magento/Catalog/Block/Adminhtml/Product/Attribute/Edit/Tab/Main.php    			adminhtml_product_attribute_types
app/code/Magento/Catalog/Block/Adminhtml/Product/Attribute/Edit/Tab/Main.php    			product_attribute_form_build_main_tab
app/code/Magento/Catalog/Block/Adminhtml/Product/Attribute/Grid.php 					product_attribute_grid_build
app/code/Magento/Catalog/Block/Adminhtml/Product/Attribute/NewAttribute/Product/Attributes.php  	adminhtml_catalog_product_edit_prepare_form
app/code/Magento/Catalog/Block/Adminhtml/Product/Attribute/NewAttribute/Product/Attributes.php  	adminhtml_catalog_product_edit_element_types
app/code/Magento/Catalog/Block/Adminhtml/Product/Attribute/Set/Main.php 				adminhtml_catalog_product_attribute_set_main_html_before
app/code/Magento/Catalog/Block/Adminhtml/Product/Attribute/Set/Toolbar/Main.php 		      adminhtml_catalog_product_attribute_set_toolbar_main_html_before
app/code/Magento/Catalog/Block/Adminhtml/Product/Edit/Action/Attribute/Tab/Attributes.php   		adminhtml_catalog_product_form_prepare_excluded_field_list
app/code/Magento/Catalog/Block/Adminhtml/Product/Edit/Tab/Attributes/Create.php 		      adminhtml_catalog_product_edit_tab_attributes_create_html_before
app/code/Magento/Catalog/Block/Adminhtml/Product/Edit/Tab/Attributes.php    				adminhtml_catalog_product_edit_prepare_form
app/code/Magento/Catalog/Block/Adminhtml/Product/Edit/Tab/Attributes.php    				adminhtml_catalog_product_edit_element_types
app/code/Magento/Catalog/Block/Adminhtml/Product/Grid.php   						adminhtml_catalog_product_grid_prepare_massaction
app/code/Magento/Catalog/Block/Adminhtml/Product/Helper/Form/Gallery/Content.php    			catalog_product_gallery_prepare_layout
app/code/Magento/Catalog/Block/Product/AbstractProduct.php  						catalog_block_product_status_display
app/code/Magento/Catalog/Block/Product/ListProduct.php  						catalog_block_product_list_collection
app/code/Magento/Catalog/Block/Product/ProductList/Upsell.php   					catalog_product_upsell
app/code/Magento/Catalog/Block/Product/View/Options.php 						catalog_product_option_price_configuration_after
app/code/Magento/Catalog/Block/Product/View.php 							catalog_product_view_config
app/code/Magento/Catalog/Block/Rss/Category.php 							rss_catalog_category_xml_callback
app/code/Magento/Catalog/Block/Rss/Product/NewProducts.php  						rss_catalog_new_xml_callback
app/code/Magento/Catalog/Block/Rss/Product/Special.php  						rss_catalog_special_xml_callback
app/code/Magento/Catalog/Block/ShortcutButtons.php  							shortcut_buttons_container
app/code/Magento/Catalog/Controller/Adminhtml/Category/Delete.php   					catalog_controller_category_delete
app/code/Magento/Catalog/Controller/Adminhtml/Category/Edit.php 					category_prepare_ajax_response
app/code/Magento/Catalog/Controller/Adminhtml/Category/Save.php 					catalog_category_prepare_save
app/code/Magento/Catalog/Controller/Adminhtml/Product/Action/Attribute/Save.php 			catalog_product_to_website_change
app/code/Magento/Catalog/Controller/Adminhtml/Product/Edit.php  					catalog_product_edit_action
app/code/Magento/Catalog/Controller/Adminhtml/Product/Gallery/Upload.php    				catalog_product_gallery_upload_image_after
app/code/Magento/Catalog/Controller/Adminhtml/Product/NewAction.php 					catalog_product_new_action
app/code/Magento/Catalog/Controller/Adminhtml/Product/Save.php  					controller_action_catalog_product_save_entity_after
app/code/Magento/Catalog/Controller/Category/View.php   						catalog_controller_category_init_after
app/code/Magento/Catalog/Controller/Product/Compare/Add.php 						catalog_product_compare_add_product
app/code/Magento/Catalog/Controller/Product/Compare/Remove.php  					catalog_product_compare_remove_product
app/code/Magento/Catalog/Helper/Product/View.php    							catalog_controller_product_view
app/code/Magento/Catalog/Helper/Product.php 								catalog_controller_product_init_before
app/code/Magento/Catalog/Helper/Product.php 								catalog_controller_product_init_after
app/code/Magento/Catalog/Model/Category.php 								_move_before
app/code/Magento/Catalog/Model/Category.php 								_move_after
app/code/Magento/Catalog/Model/Category.php 								category_move
app/code/Magento/Catalog/Model/Product/Action.php   							catalog_product_attribute_update_before
app/code/Magento/Catalog/Model/Product/Attribute/Source/Inputtype.php   				adminhtml_product_attribute_types
app/code/Magento/Catalog/Model/Product/Type/AbstractType.php    					NO_MATCH
app/code/Magento/Catalog/Model/Product/Type/Price.php   						catalog_product_get_final_price
app/code/Magento/Catalog/Model/Product.php  								_validate_before
app/code/Magento/Catalog/Model/Product.php  								_validate_after
app/code/Magento/Catalog/Model/Product.php  								catalog_product_is_salable_before
app/code/Magento/Catalog/Model/Product.php  								catalog_product_is_salable_after
app/code/Magento/Catalog/Model/ResourceModel/Category/Collection.php    				_load_before
app/code/Magento/Catalog/Model/ResourceModel/Category/Collection.php    				_load_after
app/code/Magento/Catalog/Model/ResourceModel/Category/Collection.php    				_add_is_active_filter
app/code/Magento/Catalog/Model/ResourceModel/Category/Flat/Collection.php   				_load_before
app/code/Magento/Catalog/Model/ResourceModel/Category/Flat/Collection.php   				_load_after
app/code/Magento/Catalog/Model/ResourceModel/Category/Flat/Collection.php   				_add_is_active_filter
app/code/Magento/Catalog/Model/ResourceModel/Category/Flat.php  					catalog_category_tree_init_inactive_category_ids
app/code/Magento/Catalog/Model/ResourceModel/Category/Flat.php  					catalog_category_flat_loadnodes_before
app/code/Magento/Catalog/Model/ResourceModel/Category/Tree.php  					catalog_category_tree_init_inactive_category_ids
app/code/Magento/Catalog/Model/ResourceModel/Category.php   						catalog_category_change_products
app/code/Magento/Catalog/Model/ResourceModel/Product/Collection.php 					catalog_prepare_price_select
app/code/Magento/Catalog/Model/ResourceModel/Product/Collection.php 					catalog_product_collection_load_after
app/code/Magento/Catalog/Model/ResourceModel/Product/Collection.php 					catalog_product_collection_before_add_count_to_categories
app/code/Magento/Catalog/Model/ResourceModel/Product/Collection.php 					catalog_product_collection_apply_limitations_after
app/code/Magento/Catalog/Model/ResourceModel/Product/Compare/Item/Collection.php    			catalog_product_compare_item_collection_clear
app/code/Magento/Catalog/Model/ResourceModel/Product/Indexer/Eav/AbstractEav.php    			prepare_catalog_product_index_select
app/code/Magento/Catalog/Model/ResourceModel/Product/Indexer/Eav/Decimal.php    			prepare_catalog_product_index_select
app/code/Magento/Catalog/Model/ResourceModel/Product/Indexer/Eav/Source.php 				prepare_catalog_product_index_select
app/code/Magento/Catalog/Model/ResourceModel/Product/Indexer/Eav/Source.php 				prepare_catalog_product_index_select
app/code/Magento/Catalog/Model/ResourceModel/Product/Indexer/Price/DefaultPrice.php 			prepare_catalog_product_index_select
app/code/Magento/Catalog/Model/ResourceModel/Product.php    						catalog_product_delete_after_done
app/code/Magento/Catalog/Model/Rss/Product/NotifyStock.php  						rss_catalog_notify_stock_collection_select
app/code/Magento/Catalog/Plugin/Model/Product/Action/UpdateAttributesFlushCache.php 			clean_cache_by_tags
app/code/Magento/CatalogImportExport/Model/Import/Product.php   					catalog_product_import_bunch_delete_after
app/code/Magento/CatalogImportExport/Model/Import/Product.php   					catalog_product_import_finish_before
app/code/Magento/CatalogImportExport/Model/Import/Product.php   					catalog_product_import_bunch_save_after
app/code/Magento/CatalogInventory/Model/Indexer/Stock/AbstractAction.php    				clean_cache_by_tags
app/code/Magento/CatalogRule/Block/Adminhtml/Promo/Catalog/Edit/Tab/Main.php    			adminhtml_promo_catalog_edit_tab_main_prepare_form
app/code/Magento/CatalogRule/Controller/Adminhtml/Promo/Catalog/Save.php    				adminhtml_controller_catalogrule_prepare_save
app/code/Magento/CatalogRule/Model/Indexer/AbstractIndexer.php  					clean_cache_by_tags
app/code/Magento/CatalogSearch/Model/Indexer/Fulltext/Action/DataProvider.php   			catelogsearch_searchable_attributes_load_after
app/code/Magento/CatalogSearch/Model/Indexer/Fulltext/Action/Full.php   				catelogsearch_searchable_attributes_load_after
app/code/Magento/CatalogSearch/Model/ResourceModel/Fulltext.php 					catalogsearch_reset_search_result
app/code/Magento/Checkout/Block/QuoteShortcutButtons.php    						shortcut_buttons_container
app/code/Magento/Checkout/Controller/Cart/Add.php   							checkout_cart_add_product_complete
app/code/Magento/Checkout/Controller/Cart/UpdateItemOptions.php 					checkout_cart_update_item_complete
app/code/Magento/Checkout/Controller/Onepage/SaveOrder.php  						checkout_controller_onepage_saveOrder
app/code/Magento/Checkout/Controller/Onepage/Success.php    						checkout_onepage_controller_success_action
app/code/Magento/Checkout/Helper/Data.php   								checkout_allow_guest
app/code/Magento/Checkout/Model/Cart.php    								checkout_cart_product_add_after
app/code/Magento/Checkout/Model/Cart.php    								checkout_cart_update_items_before
app/code/Magento/Checkout/Model/Cart.php    								checkout_cart_update_items_after
app/code/Magento/Checkout/Model/Cart.php    								checkout_cart_save_before
app/code/Magento/Checkout/Model/Cart.php    								checkout_cart_save_after
app/code/Magento/Checkout/Model/Cart.php    								checkout_cart_product_update_after
app/code/Magento/Checkout/Model/Session.php 								custom_quote_process
app/code/Magento/Checkout/Model/Session.php 								checkout_quote_init
app/code/Magento/Checkout/Model/Session.php 								load_customer_quote_before
app/code/Magento/Checkout/Model/Session.php 								checkout_quote_destroy
app/code/Magento/Checkout/Model/Session.php 								restore_quote
app/code/Magento/Checkout/Model/Type/Onepage.php    							checkout_type_onepage_save_order_after
app/code/Magento/Checkout/Model/Type/Onepage.php    							checkout_submit_all_after
app/code/Magento/Cms/Block/Adminhtml/Page/Edit/Tab/Content.php  					adminhtml_cms_page_edit_tab_content_prepare_form
app/code/Magento/Cms/Block/Adminhtml/Page/Edit/Tab/Design.php   					adminhtml_cms_page_edit_tab_design_prepare_form
app/code/Magento/Cms/Block/Adminhtml/Page/Edit/Tab/Main.php 						adminhtml_cms_page_edit_tab_main_prepare_form
app/code/Magento/Cms/Block/Adminhtml/Page/Edit/Tab/Meta.php 						adminhtml_cms_page_edit_tab_meta_prepare_form
app/code/Magento/Cms/Controller/Adminhtml/Page/Delete.php   						adminhtml_cmspage_on_delete
app/code/Magento/Cms/Controller/Adminhtml/Page/Delete.php   						adminhtml_cmspage_on_delete
app/code/Magento/Cms/Controller/Adminhtml/Page/Save.php 						cms_page_prepare_save
app/code/Magento/Cms/Controller/Router.php  								cms_controller_router_match_before
app/code/Magento/Cms/Helper/Page.php    								cms_page_render
app/code/Magento/Cms/Helper/Wysiwyg/Images.php  							cms_wysiwyg_images_static_urls_allowed
app/code/Magento/Config/Block/System/Config/Form/Fieldset/Modules/DisableOutput.php 			adminhtml_system_config_advanced_disableoutput_render_before
app/code/Magento/Config/Model/Config.php    								NO_MATCH
app/code/Magento/ConfigurableProduct/Model/Product/Validator/Plugin.php 				catalog_product_validate_variations_before
app/code/Magento/Cookie/Controller/Index/NoCookies.php  						controller_action_nocookies
app/code/Magento/CurrencySymbol/Model/System/Currencysymbol.php 					admin_system_config_changed_section_currency_before_reinit
app/code/Magento/CurrencySymbol/Model/System/Currencysymbol.php 					admin_system_config_changed_section_currency
app/code/Magento/Customer/Block/Adminhtml/Edit/Tab/Carts.php    					adminhtml_block_html_before
app/code/Magento/Customer/Controller/Account/CreatePost.php 						customer_register_success
app/code/Magento/Customer/Controller/Adminhtml/Index/Save.php   					adminhtml_customer_prepare_save
app/code/Magento/Customer/Controller/Adminhtml/Index/Save.php   					adminhtml_customer_save_after
app/code/Magento/Customer/Model/AccountManagement.php   						customer_customer_authenticated
app/code/Magento/Customer/Model/AccountManagement.php   						customer_data_object_login
app/code/Magento/Customer/Model/Address/AbstractAddress.php 						customer_address_format
app/code/Magento/Customer/Model/Customer.php    							customer_customer_authenticated
app/code/Magento/Customer/Model/Customer.php    							customer_validate
app/code/Magento/Customer/Model/ResourceModel/CustomerRepository.php    				customer_save_after_data_object
app/code/Magento/Customer/Model/Session.php 								customer_session_init
app/code/Magento/Customer/Model/Session.php 								customer_login
app/code/Magento/Customer/Model/Session.php 								customer_data_object_login
app/code/Magento/Customer/Model/Session.php 								customer_login
app/code/Magento/Customer/Model/Session.php 								customer_data_object_login
app/code/Magento/Customer/Model/Session.php 								customer_logout
app/code/Magento/Customer/Model/Visitor.php 								visitor_init
app/code/Magento/Customer/Model/Visitor.php 								visitor_activity_save
app/code/Magento/Eav/Block/Adminhtml/Attribute/Edit/Main/AbstractMain.php   				adminhtml_block_eav_attribute_edit_form_init
app/code/Magento/Eav/Model/Entity/Collection/AbstractCollection.php 					eav_collection_abstract_load_before
app/code/Magento/GiftMessage/Block/Message/Inline.php   						gift_options_prepare_items
app/code/Magento/GroupedProduct/Model/ResourceModel/Product/Indexer/Price/Grouped.php   		catalog_product_prepare_index_select
app/code/Magento/Indexer/Model/Processor/InvalidateCache.php    					clean_cache_after_reindex
app/code/Magento/Multishipping/Controller/Checkout/ShippingPost.php 					checkout_controller_multishipping_shipping_post
app/code/Magento/Multishipping/Controller/Checkout/Success.php  					multishipping_checkout_controller_success_action
app/code/Magento/Multishipping/Model/Checkout/Type/Multishipping.php    				checkout_type_multishipping_set_shipping_items
app/code/Magento/Multishipping/Model/Checkout/Type/Multishipping.php    				checkout_type_multishipping_create_orders_single
app/code/Magento/Multishipping/Model/Checkout/Type/Multishipping.php    				checkout_submit_all_after
app/code/Magento/Multishipping/Model/Checkout/Type/Multishipping.php    				checkout_multishipping_refund_all
app/code/Magento/PageCache/Model/Cache/Type.php 							adminhtml_cache_refresh_type
app/code/Magento/PageCache/Model/Layout/DepersonalizePlugin.php 					depersonalize_clear_session
app/code/Magento/Payment/Block/Form/Cc.php  								payment_form_block_to_html_before
app/code/Magento/Payment/Model/Cart.php 								payment_cart_collect_items_and_amounts
app/code/Magento/Payment/Model/Method/AbstractMethod.php    						payment_method_is_active
app/code/Magento/Payment/Model/Method/Adapter.php   							payment_method_is_active
app/code/Magento/Payment/Model/Method/Adapter.php   							payment_method_assign_data_
app/code/Magento/Paypal/Controller/Express/AbstractExpress/PlaceOrder.php   				paypal_express_place_order_success
app/code/Magento/Persistent/Controller/Index/UnsetCookie.php    					persistent_session_expired
app/code/Magento/Persistent/Observer/CheckExpirePersistentQuoteObserver.php 				persistent_session_expired
app/code/Magento/Quote/Model/Cart/Totals/ItemConverter.php  						items_additional_data
app/code/Magento/Quote/Model/Quote/Address/ToOrder.php  						sales_convert_quote_to_order
app/code/Magento/Quote/Model/Quote/Item.php 								sales_quote_item_qty_set_after
app/code/Magento/Quote/Model/Quote/Item.php 								sales_quote_item_set_product
app/code/Magento/Quote/Model/Quote/Payment.php 								_import_data_before
app/code/Magento/Quote/Model/Quote/TotalsCollector.php  						sales_quote_collect_totals_before
app/code/Magento/Quote/Model/Quote/TotalsCollector.php  						sales_quote_collect_totals_after
app/code/Magento/Quote/Model/Quote/TotalsCollector.php  						sales_quote_address_collect_totals_before
app/code/Magento/Quote/Model/Quote/TotalsCollector.php  						sales_quote_address_collect_totals_after
app/code/Magento/Quote/Model/Quote.php  								sales_quote_remove_item
app/code/Magento/Quote/Model/Quote.php  								sales_quote_add_item
app/code/Magento/Quote/Model/Quote.php  								sales_quote_product_add_after
app/code/Magento/Quote/Model/Quote.php  								_merge_before
app/code/Magento/Quote/Model/Quote.php  								_merge_after
app/code/Magento/Quote/Model/QuoteManagement.php   							checkout_submit_before
app/code/Magento/Quote/Model/QuoteManagement.php    							checkout_submit_all_after
app/code/Magento/Quote/Model/QuoteManagement.php    							sales_model_service_quote_submit_before
app/code/Magento/Quote/Model/QuoteManagement.php    							sales_model_service_quote_submit_success
app/code/Magento/Quote/Model/QuoteManagement.php    							sales_model_service_quote_submit_failure
app/code/Magento/Quote/Model/ResourceModel/Quote/Address/Collection.php					_load_after
app/code/Magento/Quote/Model/ResourceModel/Quote/Item/Collection.php    				prepare_catalog_product_collection_prices
app/code/Magento/Quote/Model/ResourceModel/Quote/Item/Collection.php    				sales_quote_item_collection_products_after_load
app/code/Magento/Reports/Block/Adminhtml/Grid.php   							adminhtml_widget_grid_filter_collection
app/code/Magento/Reports/Model/ResourceModel/Order/Collection.php   					sales_prepare_amount_expression
app/code/Magento/Review/Controller/Product.php  							review_controller_product_init_before
app/code/Magento/Review/Controller/Product.php  							review_controller_product_init
app/code/Magento/Review/Controller/Product.php  							review_controller_product_init_after
app/code/Magento/Review/Model/ResourceModel/Rating/Collection.php   					rating_rating_collection_load_before
app/code/Magento/Review/Model/ResourceModel/Review/Collection.php   					review_review_collection_load_before
app/code/Magento/Review/Model/Rss.php   								rss_catalog_review_collection_select
app/code/Magento/Sales/Block/Adminhtml/Reorder/Renderer/Action.php  					adminhtml_customer_orders_add_action_renderer
app/code/Magento/Sales/Controller/Adminhtml/Order/AddressSave.php   					admin_sales_order_address_update
app/code/Magento/Sales/Controller/Adminhtml/Order/Create.php    					adminhtml_sales_order_create_process_data_before
app/code/Magento/Sales/Controller/Adminhtml/Order/Create.php    					adminhtml_sales_order_create_process_data
app/code/Magento/Sales/Controller/Adminhtml/Order/CreditmemoLoader.php  				adminhtml_sales_order_creditmemo_register_before
app/code/Magento/Sales/Model/AdminOrder/Create.php  							sales_convert_order_to_quote
app/code/Magento/Sales/Model/AdminOrder/Create.php 							sales_convert_order_item_to_quote_item
app/code/Magento/Sales/Model/AdminOrder/Create.php  							checkout_submit_all_after
app/code/Magento/Sales/Model/Config/Backend/Email/AsyncSending.php  					sales_email_general_async_sending
app/code/Magento/Sales/Model/Config/Backend/Grid/AsyncIndexing.php  					dev_grid_async_indexing
app/code/Magento/Sales/Model/Order/Address/Renderer.php 						customer_address_format
app/code/Magento/Sales/Model/Order/Email/Sender/CreditmemoCommentSender.php 				email_creditmemo_comment_set_template_vars_before
app/code/Magento/Sales/Model/Order/Email/Sender/CreditmemoSender.php    				email_creditmemo_set_template_vars_before
app/code/Magento/Sales/Model/Order/Email/Sender/InvoiceCommentSender.php    				email_invoice_comment_set_template_vars_before
app/code/Magento/Sales/Model/Order/Email/Sender/InvoiceSender.php   					email_invoice_set_template_vars_before
app/code/Magento/Sales/Model/Order/Email/Sender/OrderCommentSender.php  				email_order_comment_set_template_vars_before
app/code/Magento/Sales/Model/Order/Email/Sender/OrderSender.php 					email_order_set_template_vars_before
app/code/Magento/Sales/Model/Order/Email/Sender/ShipmentCommentSender.php   				email_shipment_comment_set_template_vars_before
app/code/Magento/Sales/Model/Order/Email/Sender/ShipmentSender.php  					email_shipment_set_template_vars_before
app/code/Magento/Sales/Model/Order/Invoice.php  							sales_order_invoice_pay
app/code/Magento/Sales/Model/Order/Invoice.php  							sales_order_invoice_cancel
app/code/Magento/Sales/Model/Order/Invoice.php  							sales_order_invoice_register
app/code/Magento/Sales/Model/Order/Item.php 								sales_order_item_cancel
app/code/Magento/Sales/Model/Order/Payment/Operations/CaptureOperation.php  				sales_order_payment_capture
app/code/Magento/Sales/Model/Order/Payment/Transaction.php  						_html_txn_id
app/code/Magento/Sales/Model/Order/Payment.php  							sales_order_payment_place_start
app/code/Magento/Sales/Model/Order/Payment.php  							sales_order_payment_place_end
app/code/Magento/Sales/Model/Order/Payment.php  							sales_order_payment_pay
app/code/Magento/Sales/Model/Order/Payment.php  							sales_order_payment_cancel_invoice
app/code/Magento/Sales/Model/Order/Payment.php  							sales_order_payment_void
app/code/Magento/Sales/Model/Order/Payment.php  							sales_order_payment_refund
app/code/Magento/Sales/Model/Order/Payment.php  							sales_order_payment_cancel_creditmemo
app/code/Magento/Sales/Model/Order/Payment.php  							sales_order_payment_cancel
app/code/Magento/Sales/Model/Order/Status.php   							sales_order_status_unassign
app/code/Magento/Sales/Model/Order.php  								sales_order_place_before
app/code/Magento/Sales/Model/Order.php  								sales_order_place_after
app/code/Magento/Sales/Model/Order.php  								order_cancel_after
app/code/Magento/Sales/Model/ResourceModel/Attribute.php    						_save_attribute_before
app/code/Magento/Sales/Model/ResourceModel/Attribute.php    						_save_attribute_after
app/code/Magento/Sales/Model/ResourceModel/Order/Address/Collection.php 				_load_after
