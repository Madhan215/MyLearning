#### Patrons are assigned to one of six main categories:

- Adult
  - Jenis patron yang paling umum, biasanya digunakan untuk kategori 'Patron' umum.
- Child
    - Patron anak-anak dapat memiliki wali untuk dilampirkan pada mereka.
- Staff
  - Pustakawan (dan pekerja perpustakaan) harus diberi kategori staf sehingga Anda dapat mengatur izin mereka dan memberi mereka akses ke klien staf.
- Organizational
  - Pelindung organisasi adalah organisasi. Organisasi dapat digunakan sebagai penjamin untuk pelindung Profesional.
- Professional
  - Patron profesional dapat dihubungkan dengan patron Organisasi
- Statistical
  - Jenis pelindung ini hanya digunakan untuk tujuan statistik, seperti penggunaan item di rumah.

#### Patron Permission Defined

- Access to all librarian functions (superlibrarian)
    - This permission grants access to all areas. If selected, specific sub-permissions cannot be selected.
- Check out and check in items (circulate) 
- Staff access, allows viewing of catalogue in staff interface (catalogue) Required for staff login.
- Manage Koha system settings (Administration panel) (parameters) 
- Add, modify and view patron information (borrowers) 
- Set user permissions (permissions)
- Place and modify holds for patrons (reserveforothers) 
- Edit catalog (Modify bibliographic/holdings data) (editcatalogue) 
- Manage patrons fines and fees (updatecharges) 
- Acquisition management (acquisition) 
- Suggestions management (suggestions) 
- Use all tools (expand for granular tools permissions) (tools) 
- Edit authorities (editauthorities)
- Manage serial subscriptions (serials) 
- Allow access to the reports module (reports) 
- Allow staff members to modify permissions, usernames, and passwords for other staff members (staffaccess)
- Course reserves (coursereserves) 
- Koha plugins (plugins) 
- Lists (lists) 
- Patron clubs (clubs) 
- Create and modify Interlibrary loan requests (ill)
- Self check modules (self_check) 
- Manage stockrotation operations (stockrotation) 
- OPAC problem reports management (problem_reports) 
- Recalls (recalls)

#### Rincian 

- superlibrarian
– Access to all librarian functions
  - Note
With this selected there is no need to choose any other permissions
-  circulate
   - Check out and check in items
   - This section can be expanded (Learn more)
If the staff member has ‘circulate’ permissions they have the ability to perform all of these actions. If you would like
to control circulation permissions on a more granular level choose from these options:
• circulate_remaining_permissions
– Remaining circulation permissions
– All circulation rights except those covered by permissions listed below
• force_checkout
– Force checkout if a limitation exists
– With this permission a librarian will be allowed to override a check out restriction in the following cases:
* age restriction
* the item is issued to another patron
* the item is not for loan
* the patron has overdue items
* the item is lost
* the item is a high demand item
* the item is on hold
• manage_restrictions
– Manage restrictions for accounts
– Grants permission to the staff member to lift a restriction that might be on the patron’s record
• overdues_report
– Execute overdue items report
– The permission to run the overdues reports found under Circulation
• override_renewals
– Override blocked renewals
– Requires that the staff member also has circulate_remaining_permissions
• catalogue
– Required for staff login. Staff access, allows viewing the catalogue in staff client
* Important
Must be given to all staff members to allow them to login to the staff client
• parameters
– Manage Koha system systems (Administration panel)
– This section can be expanded (Learn more)
If the staff member has ‘parameters’ permissions they have the ability to perform all of these actions. If you would
like to control parameter permissions on a more granular level choose from these options:
• manage_circ_rules
– Manage circulation rules
– The ability to access the Circulation and fines rules in the administration area
• parameters_remaining_permissions
– Remaining system parameters permissions
– The ability to access all areas in Administration (other than the Circulation and fine rules)
• borrowers
– Add or modify patrons
• permissions
– Set user permissions
• reserveforothers
– Place and modify holds for patrons
– This section can be expanded (Learn more)
If the staff member has ‘reserveforothers’ permissions they have the ability to perform all of these actions. If you
would like to control holds permissions on a more granular level choose from these options:
• modify_holds_priority
– Modify holds priority
– Allow staff members to alter the holds priority (moving patrons up and down the queue)
• place_holds
– Place holds for patrons
• editcatalogue
– Edit Catalog (Modify bibliographic/holdings data)
– This section can be expanded (Learn more)
If the staff member has ‘editcatalogue’ permissions they have the ability to perform all of these actions. If you would
like to control cataloging permissions on a more granular level choose from these options:
• delete_all_items
– Delete all items at once
– Ability to use the ‘Delete all items’ option found under the ‘Edit’ menu in cataloging
• edit_catalogue
– Edit catalog (Modify bibliographic/holdings data)
– Ability to access all cataloging functions via the Cataloging page
• edit_items
– Edit items
– Ability to make edits to item/holdings records, but not bibliographic records
• edit_items_restricted
– Limit item modification to subfields defined in the SubfieldsToAllowForRestrictedEditing preference
– Note
Please note that edit_items permission is still required
• fast_cataloging
– Fast cataloging
– The ability to catalog using only the Fast Add Framework found on the Circulation page
• updatecharges
– Manage patrons fines and fees
– This section can be expanded (Learn more)
If a staff member has ‘updatecharges’ permission they have the ability to perform all of these actions. If you would
like to control fines and charges permissions on a more granular level choose from these options:
• remaining_permissions
– Remaining permissions for managing fines and fees other than the ability to write off charges
• writeoff
– Write off fines and fees
• acquisition
– Acquisition and/or suggestion management
– This section can be expanded (Learn more)
If the staff member has ‘acquisition’ permissions they have the ability to perform all of these actions. If you would
like to control acquisitions permissions on a more granular level choose from these options:
• budget_add_del
– Add and delete budgets (but can’t modify budgets)
• budget_manage
– Manage budgets
• budget_manage_all
– Manage all budgets
budget_modify
– Modify budget (can’t create lines, but can modify existing ones)
• contracts_manage
– Manage contracts
• group_manage
– Manage orders and basket groups
• order_manage
– Manage orders and baskets
• order_manage_all
– Manage all orders and baskets, regardless of restrictions on them
• order_receive
– Manage orders and baskets
• period_manage
– Manage periods
• planning_manage
– Manage budget planning
• vendors_manage
– Manage vendors
• management
– Set library management params (deprecated)
* Important
This permission level no longer controls anything.
• tools
– Use all tools
– This section can be expanded (Learn more)
If the staff member has ‘tools’ permissions they have the ability to access and use all items under the Tools menu.
If you would like to control which tools staff members have access to on a more granular level choose from these
options:
• batch_upload_patron_images
– Upload patron images in batch or one at a time
– Access to the Image Upload Tool
• delete_anonymize_patrons
– Delete old borrowers and anonymize circulation/reading history (deletes borrower reading history)
– Access to the Anonymize Patron Tool
• edit_calendar
– Define days when the library is closed
– Access to the Calendar/Holidays Tool
• edit_news
– Write news for the OPAC and staff interfaces
– Access to the News Tool
• edit_notice_status_triggers
– Set notice/status triggers for overdue items
– Access to the Overdue Notice Status/Triggers Tool
• edit_notices
– Define notices
– Access to the Notices Tool
• export_catalog
– Export bibliographic, authorities and holdings data
– Access to the Export Data Tool
• import_patrons
– Import patron data
– Access to the Import Patrons Tool
• inventory
– Perform inventory (stocktaking) of your catalog
– Access to the Inventory Tool
• items_batchdel
– Perform batch deletion of items
– Access to the Batch Item Deletion Tool
• items_batchmod
– Perform batch modification of items
– Access to the Batch Item Modification Tool
• items_batchmod_restricted
– Limit batch item modification to subfields defined in the SubfieldsToAllowForRestrictedBatchmod preference
– Note
Please note that items_batchmod permission is still required
• label_creator
– Create printable labels and barcodes from catalog and patron data
– Access to the Label Creator and Quick Label Creator Tools
• manage_csv_profiles
– Manage CSV export profiles
– Access to the CSV Profiles Tool
• manage_staged_marc
– Manage staged MARC records, including completing and reversing imports
– Access to the Manage Staged MARC Records Tool
• moderate_comments
– Moderate patron comments
– Access to the Comments Tool
• moderate_tags
– Moderate patron tags
– Access to the Tags Tool
• records_batchdel
– Perform batch deletion of records (bibliographic or authority)
– Access to the Batch Record Deletion Tool
• rotating_collections
– Manage rotating collections
– Access to the Rotating Collections Tool
• schedule_tasks
– Schedule tasks to run
– Access to the Task Scheduler Tool
• stage_marc_import
– Stage MARC records into the reservoir
– Access to the Stage MARC Records Tool
• upload_general_files
– Upload any file
– Access to upload files via the Upload Tool
• upload_local_cover_images
– Upload local cover images
– Access to the Upload Local Cover Image Tool as well as permission to add and delete local cover images
from the bib detail page
• upload_manage
– Manage uploaded files
– Access to uploaded files via the Upload Tool
Note
upload_general_files permission is required for this permission
• view_system_logs
– Browse the system logs
– Access to the Log Viewer Tool
• editauthorities
– Edit Authorities
• serials
– Manage serial subscriptions
– This section can be expanded (Learn more)
If the staff member has ‘serials’ permissions they have the ability to perform all of these actions. If you would like to
control serials permissions on a more granular level choose from these options:
• check_expiration
– Check the expiration of a serial
• claim_serials
– Claim missing serials via the Claims section
• create_subscription
– Create a new subscription
• delete_subscription
– Delete an existing subscription
• edit_subscription
– Edit an existing subscription
– This permission does not include the ability to delete or create a subscription
• receive_serials
– Serials receiving
– Receive serials on existing subscriptions
• renew_subscription
– Renew a subscription
• routing
– Routing
– Manage routing lists
• superserials
– Manage subscriptions from any branch (only applies when IndependantBranches is used)
• reports
– Allow access to the reports module
– Reports found on the Circulation page are not controlled by this permission
– This section can be expanded (Learn more)
If the staff member has ‘reports’ permissions they have the ability to perform all of these actions. If you would like to
control reports permissions on a more granular level choose from these options:
• create_reports
– Create SQL Reports
– The ability to create and edit but not run SQL reports
• execute_reports
– Execute SQL Reports
– The ability to run but not create or edit SQL reports
• staffaccess
– Allow staff members to modify permissions for other staff members
– Important
Requires the borrowers permission above
• plugins
– Koha plugins
– This section can be expanded (Learn more)
If the staff member has ‘plugins’ permissions they have the ability to perform all of these actions. If you would like to
control reports permissions on a more granular level choose from these options:
• configure
– Configure plugins
– The ability to run the ‘configure’ section of a plugin if it has one
• manage
– Manage plugins
– The ability to install or uninstall plugins
• report
– Use report plugins
– The ability to use report plugins
• tool
– Use tool plugins
– The ability to use tool plugins
• lists
– Koha Lists
– Important
All staff have permission to create and modify their own lists, this permission is only necessary
if you’d like to give a staff member permission to delete public lists that they have not created.
– This section can be expanded (Learn more)
All staff members have permission to access lists. This section only needs to be checked off if you want to give
permission to a staff member to delete public lists that they have no created themselves.
• delete_public_lists
– Delete public lists