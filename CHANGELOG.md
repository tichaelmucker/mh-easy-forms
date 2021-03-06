# Changelog


11.11.2018 - ver 1.6.7

- Added: Administrators can assign a form to a different user
- Added: Custom checkbox and radio button 
- Added: Form Submissions: Mark as read / unread
- Added: Demo js file to change a File field label when a file is selected
- Updated: Vendors and composer.json file
- Fixed: Validation error messages with foreign languages
- Fixed: Number of forms on dashboard (for non-admin users)
- Fixed: Https issue with cloudflare when it's needed 
- Fixed: Form Builder: Select List. Options with wrong format
- Fixed: Form Builder: "Warning! preg_replace(): Unknown modifier 'P'"
- Fixed: Dashboard queries with PHP 7.2
- Fixed: FormDOM helper detects <script> tags
- Fixed: Export Form Submissions. Excludes null data
- Fixed: Installation process. Check if popen() function exists


05.09.2018 - ver 1.6.6

- Added: Dutch translation
- Added: Format number in other languages script
- Added: jQuery UI DatePicker demo in Dutch language
- Added: Form Builder: 'Alias' option to form fields
- Added: Tool to update Form Builder fields
- Added: WebHook Add-On v1.1: Set same WebHook to multiple forms
- Added: Send WebHook notifications using 'Alias' instead of field name
- Updated: Rule Builder with better interactions
- Fixed: i18n of error message when trying to change the username
- Fixed: DateRange widget with translations
- Fixed: Avatar field
- Fixed: Link to register page (in small screens)
- Fixed: reCaptcha component (Compact size)
- Fixed: Display reCaptcha in small frame.
- Fixed: Drag last component in Form Builder
- Fixed: Conditional validation when a checkbox is checked
- Fixed: Displays progress bar when form has multiple file fields
- Fixed: Small Issue displaying Form Stats.
- Fixed: Unexpected 'class' (T_CLASS) with PHP 5.4
- Fixed: Prevent load of "en-us" locale file for moment.js


13.06.2018 - ver 1.6.5

- Fixed: Pop-Up Form Designer's translations.
- Fixed: DateRangePicker translations in the Submission Manager.


08.06.2018 - ver 1.6.4

- Added: Copy Multiple Fields by using Conditional Rules
- Added: Sender Information on the exported CSV / Excel file
- Added: Intl-Tel-Input.js with User's Country Lookup (ipinfo.io)
- Added: Auto Submit when a Radio Button is selected
- Added: Multiple emails (separated by commas) on Notification Settings
- Updated: CSRF validation on forms by default
- Updated: English as default language when a new user registers
- Updated: Vendors and composer.json file
- Fixed: Date format when form language is Arabic
- Fixed: Select List field on Form Builder
- Fixed: English to French translation
- Fixed: Duplicate records when calculating daily statistics
- Fixed: Date filter ('Today') when exporting form submissions
- Fixed: Edit Form Submission when form has a token. Eg. {{{STRIPE}}
- Fixed: Setup. Catch Guzzle Exception to detect non-friendly urls.
- Fixed: Implements DateRangePicker's i18n in the Submission Manager.


05.12.2017 - ver 1.6.3

- Added: Adds Referrer Information to Email Notifications, WebHooks and more.


03.12.2017 - ver 1.6.2

- Fixed: Migration files


02.12.2017 - ver 1.6.1

- Fixed: Logout link (New AccessControl logic)


29.11.2017 - ver 1.6

- Added: Export Form Submissions as MS Excel
- Added: Filter Form Submissions by Date Range
- Improved: Vendors (PHP v7.2 compatibility)
- Improved: jQuery UI Datepicker compatibility with conditional rules
- Fixed: Form Widget compatibility with IE11
- Fixed: Translate some missing strings
- Fixed: RTL format in Forms.
- Fixed: RTL format in alerts and breadcrumbs


08.10.2017 - ver 1.5.5

- Fixed: Form Builder (Radio Button, Checkbox, Select List)


01.10.2017 - ver 1.5.4

- Added: Translation into Portuguese language
- Changed: New .htaccess file for a better compatibility with shared hostings


24.09.2017 - ver 1.5.3

- Fixed: Step redirection. Modules: Setup, Update and Addons


23.09.2017 - ver 1.5.2

- Fixed: Guzzle 5.3.1 and PHP 7.1 compatibility. @app/vendor
- Fixed: WYSIWYG Editor and Field variables. @app/helpers/Html.php
- Fixed: PopUp Form: ScrollToTop after Submit. @app/static_files/js/form.widget.js
- Fixed: Domain communication on mobile devices. @app/static_files/js/form.widget.js


13.09.2017 - ver 1.5.1

- Fixed: WYSIWYG Editor. File Updated: @app/helpers/Html.php


01.09.2017 - ver 1.5

- Added: Pop-Up Designer
- Added: Export CSV file with Date Range
- Added: New Wysiwyg editor: summernote (Tables, videos and more)
- Added: Store images in email notifications and confirmations
- Added: Purchase Code activation in the install script
- Added: Option to enable the async email notifications in the params.php file
- Added: Javascript file to show how to use bootstrap-slider.js
- Improved: Add tables and images in email messages
- Improved: IP address client detection
- Improved: Performance page displays command to run the cron
- Improved: SMTP settings. Password field must be re-entered before updating
- Improved: Install script alerts if there isn't internet connection
- Improved: If @app/easy_forms.sql exists, install script alerts to remove it
- Improved: Install DB by using the @app/easy_forms.sql file first
- Improved: Change cron job command to run web cron by default
- Improved: Install script alerts if the PHP CLI version is invalid
- Improved: Use 'php' instead 'stmp' by default configuration to send emails
- Fixed: UTF-8 compatibility in Form Submissions on Polish language
- Fixed: Translate some missing strings
- Fixed: Click on the 'Search' button on the User Manager
- Fixed: Email notification without Reply-To
- Removed: Button to run the cron via UI
- Removed: Indonesian language
- Removed: Trumbowyg editor
- Removed: OLD and Unused js files


19.06.2017 - ver 1.4.2

- Added: Embed a Pop-Up Form
- Added: Compress uploaded images by the forms
- Added: New language: Turkish
- Improved: Vendors updated
- Improved: Apache configuration to prevent X-Frame-Options issue
- Improved: Rule Engine: Copy HTML content from one HTML element to another
- Improved: Reduces the time to resize the form when the window is resized
- Fixed: Form Builder access restriction
- Fixed: URL validation in Confirmation Settings


01.04.2017 - ver 1.4.1

- Added: Restrict access to the Login page by IP addresses
- Added: Administrators can assign Themes to another users
- Added: Field Variables in the Redirection URL
- Added: Remove javascript code in the HTML generated by the Form Builder
- Improved: Hide empty fields in the email notifications and confirmations
- Improved: Access to Forms and Themes by advanced users
- Improved:
- Fixed: Conditional validation with double css class
- Fixed: Email notifications in text plain
- Fixed: Email notifications without no-reply email address
- Fixed: Translate Password Protected Form label
- Fixed: Form Validation with two select lists
- Fixed: Form Builder access by an Advanced User
- Fixed: Multi Step forms with pages without any field
- Fixed: Html tags in a Hidden Field (Form Builder)
- Fixed: Form Widget (postMessage) in some versions of IE


28.01.2017 - ver 1.4

- Added: Duplicate Forms
- Added: Duplicate Conditional Rules
- Added: Show / Hide empty fields on Submission Details
- Improved: reCaptcha validation message
- Improved: Detect when a field is visible using a Container CSS class to validate it
- Fixed: Limit the number of words on Hide/Show columns (Submission Details)
- Fixed: Refresh comments in Submission Details
- Fixed: Double quotes on Hidden Fields (Form Builder)
- Fixed: Update referrer when the form is displayed in the same domain


16.11.2016 - ver 1.3.9

- Added: Javascript file to load jQuery DatePicker, ComboDate and Int-Tel-Input
- Added: Comment System to the Submission Manager
- Improved: Conditional rules are updated when the Form is updated by using the Form Builder.
- Improved: Submission Manager can search for non-Latin characters (Korean, Chinese and others).
- Improved: Changes the algorithm to skip between the pages on a multi-step form by using conditional rules
- Improved: Shows a confirmation message when pressing the Delete button in the Form Builder
- Fixed: An array is turned to string before validating it on the server.
- Fixed: Submission Manager Design
- Fixed: Validates a required field on the current page to skip to another by using conditional rules


17.09.2016 - ver 1.3.8

- Added: PHP Rule Engine
- Added: Conditional Validation when a field is hidden
- Improved: Export CSV file now includes uploaded files
- Improved: Conditional Rules in a Multi-Step Form
- Fixed: Remove unused tokens in custom messages
- Fixed: CSS no-padding-left and no-padding-right
- Fixed: File names uploaded with mobile devices
- Fixed: Step 5 of Installer
- Fixed: Single quotes into titles (Form Builder)
- Fixed: Form Builder save labels with Chinese characters
- Fixed: Delete Submission with a Basic User account
- Fixed: Edit Submission with a single quote in a select list


15.08.2016 - ver 1.3.7

- Added: Demo folder with javascript widgets
- Added: MetaTag Generator
- Added: SlugHelper
- Added: Rule Builder. Use Drag and Drop to change rule position.
- Improved: Installer detects PHP CLI version
- Improved: Vendors updated
- Improved: Form Embed now support autoadvance feature
- Improved: Custom SluggableBehavior
- Improved: Mail Queue
- Improved: Rule Builder Notification
- Improved: Submission Manager displays alert when a file is uploading
- Fixed: Empty Snippet
- Fixed: reCaptcha Field Position
- Fixed: Star Rating demo
- Fixed: Report Builder in PHP 7
- Fixed: Form Builder (array_key_exists)
- Fixed: Cron status code (200)
- Fixed: Submission Copy in Email Confirmation


07.07.2016 - ver 1.3.6

- Added: File Management in the Submission Manager
- Added: Restrict Websites where you can embed forms
- Added: Opposite actions on Rule Builder
- Added: WebHooks demo files
- Added: Javascript demo files
- Added: primaryKey() method on Models
- Improved: Form Builder D&D on touch screen
- Improved: Select multiple email fields in order to send email confirmations
- Improved: Customize sender name on email confirmation
- Improved: WebHooks data
- Improved: Cron via web
- Improved: Required checkbox validation
- Fixed: First column CSV export 
- Fixed: Submission Manager access
- Fixed: Labels on Email notifications
- Fixed: PHP tag on Form Builder
- Fixed: MySQL commands with table prefix
- Fixed: "options is not defined" on disabled forms


28.05.2016 - ver 1.3.5

- Added: Attach files to confirmation emails
- Added: Customize email subject with form submission data
- Added: Wysiwyg Editor to edit email text
- Added: Translation into Italian and Thai languages
- Added: Delete button to delete a field in the Form Builder
- Added: Google Place demo in a field
- Added: Combo Date demo
- Added: Start Rating demo
- Added: Implements RTL or LTR direction depending on the selected language
- Added: Export Form Submissions as CSV file via command line
- Improved: Conditional Rules can analyze multiple values separated by "|"
- Improved: Expands number of allowed tags in the email message body
- Improved: Advanced users can use templates created by admin
- Improved: Advanced users can manage their own templates
- Improved: Form Widget allows to add pixels to calculate the page OffsetTop
- Improved: Cron in Windows Environment
- Improved: Data structure for storing Form Submissions
- Improved: Rules Engine detects when a user presses "X" in IE
- Fixed: Console Component in Windows Server
- Fixed: Edit Form Submissions with unique fields
- Fixed: Form Tracker when friendly urls have been disabled
- Fixed: Date Field translation in the Form Builder
- Fixed: Click event in the Form Builder fields
- Fixed: Advanced users can save conditional rules
- Fixed: MySQL query in Dashboard
- Fixed: Previous step in a form without titles
- Fixed: "Select List" is opened twice with when the Form has conditional rules


20.04.2016 - ver 1.3.4

- Added: Delete Stats
- Added: Enable / Disable jQuery elements with conditional rules
- Added: New language: French
- Added: Implements Relation Trait behavior to handle master-detail relationships
- Added: FormEvent notifies the system when a form has been updated
- Added: Validation SMTP when configuring Mail Server
- Removed: Remove file validation on Submission Manager
- Improved: Load Google Maps JS file without protocol (schema)
- Improved: Check if the environment is Windows before running console commands
- Improved: Compatible validation patterns between client and server
- Improved: Modifies DateTime-Local field validation
- Improved: More than 20 conditional rules per page
- Improved: Reduces required width to display a form with horizontal layout
- Improved: DatePicker demo with Months and Years selector
- Improved: Allows configuring Mail Server with an API's access
- Improved: Scroll after performing an action on a form
- Improved: Reduces Form padding when displaying on smartphones
- Improved: Thank You message with variables
- Improved: Submission Manager doesn't show disabled field columns.
- Improved: Form Embed can detect when the answer came from an add-on
- Fixed: Press Enter key in a MultiStep Form
- Fixed: Field validation without label
- Fixed: Disabled fields aren't required by the server.
- Fixed: Form auto resizing protected by password.
- Fixed: Form embed code without box
- Fixed: Previous button in MultiStep Form
- Fixed: User registration validation with Captcha
- Fixed: Upload any kind of file (No validation)
- Fixed: Submission Manager: Access to upload files.
- Fixed: BulkActions in other language: Javascript alert with double quotes.
- Fixed: Check that the Select List options have text.
- Fixed: MultiStep Form creation with IE
- Fixed: Load Form Submission when accessed directly from an external link.
- Fixed: Displays notification message with several values per field


06.03.2016 - ver 1.3.3

- Added: Environment definition in console
- Added: Buttons' Support in conditional rules
- Added: New languages: German, Simplified Chinese and Traditional Chinese
- Added: CRON tool via web
- Added: Repeat Password before to change it
- Added: New oOperators to Hidden field in Rule Builder
- Removed: DB file alert message
- Improved: Responsive design with better resizing
- Improved: Cron message when installation process finished
- Improved: Confirmation / Notification messages with variables
- Improved: Form Submission Notification as plain text
- Fixed: Submission Manager is empty on Windows Server
- Fixed: Geo location. IP is not in the database
- Fixed: IE9 and IE10 form resizing
- Fixed: Edit Form Submission as Basic User
- Fixed: Unserialize() error on notifications
- Fixed: Submission Manager with hidden fields
- Fixed: Label of Hidden fields in Rule Builder


05.02.2016 - ver 1.3.2

- Added: Save a form as template
- Added: Select a different PHP version to run Cron Jobs
- Improved: Modules installer: Setup, Update and Addons
- Improved: Console component
- Improved: Download files from the Submission Manager
- Improved: Display multiple forms in the same page
- Improved: Form Builder detects when a field is deleted and shows an alert
- Improved: Filters (OFF state)
- Fixed: Export CSV File
- Fixed: Multi-Step Form with Progress Bar without titles


30.01.2016 - ver 1.3.1

- Added: Console component
- Deprecated: ConsoleHelper
- Improved: Setup / Update modules
- Improved: Cron
- Improved: Tel field validation message
- Fixed: Dashboard for advanced users
- Fixed: Performance tool
- Fixed: Required fields without labels
- Fixed: Actions buttons for advanced users
- Fixed: Google Analytics add-on event handler


25.01.2016 - ver 1.3

- Added: User registration page
- Added: Login page without password
- Added: Enable / Disable user registration from Site Settings
- Added: Add captcha to user registration from Site Settings
- Added: Set a default user rol from Site Settings
- Added: New user role: 'Advanced User' and 'User' now is 'Basic User'
- Added: Display Form Manager 'Actions' button to all users
- Added: Refresh cache tool
- Added: HTTP and HTTPS protocols supported
- Added: Print form submission
- Added: Format Number action on Form Rules
- Added: Indonesian translation
- Improved: Grid Views footer design
- Improved: Check user permissions
- Improved: Change login page when 'anyone can register' is enabled
- Improved: Addons module can update each addon version
- Improved: Install Process, update and uninstall addons
- Improved: Addons module events
- Improved: User module updated to new version
- Improved: Upload File validation on Multi Step forms
- Improved: Multi-Step forms pager
- Improved: Button component now supports 'button' input type
- Improved: Form Builder. Add images or icons to checkboxes or radio buttons
- Improved: Form Builder. Add icons to buttons
- Improved: Form Builder. New button input type: 'button'
- Fixed: Setup module error message
- Fixed: Export CSV file with 'file' fields
- Fixed: Reset password email
- Fixed: Delete multiple themes
- Fixed: Delete multiple templates
- Fixed: Default local IP for testing
- Fixed: XSS vulnerability on Submission Manager


14.01.2016 - ver 1.2

- Added: Pre-fill Form Widget with default values
- Added: Password Protected Forms
- Added: Filters in Form Manager, Templates and Themes
- Added: Rules Engine. If the condition is not met, the skip to step will be reset
- Improved: Form Builder with duplicated fields detector
- Improved: Form Settings design
- Improved: New migrations
- Improved: Spanish language translation
- Improved: Vendors updated
- Improved: Submission Event Handler with multiple cc and multiple bcc
- Fixed: Email notifications with array value
- Fixed: Resize Form Widget on IE
- Fixed: ThemeSearch table prefix
- Fixed: UserSearch profile attribute
- Fixed: Validate the field type only if input has a value
- Fixed: Form Builder without mod_rewrite
- Fixed: Delete Multiple Action on Form Manager
- Fixed: Form Builder's checkbox and radio button edition on Firefox
- Fixed: Form Builder's checkbox and radio button edition on Firefox
- Fixed: Dashboard Labels on Firefox


07.01.2016 - ver 1.1

- Added: Webhooks Add-on
- Added: Forms with Friendly Urls
- Added: Update Module
- Added: Now Easy Forms works without mod_rewrite
- Added: 'record' param to Form Widget
- Added: Cron jobs configuration with params
- Added: Email delivery with PHP mail() function
- Improved: Glyphicons version 1.9.2
- Improved: Run migrations on background
- Improved: Redirection and messaging after form submission
- Improved: In-App Analytics configurations
- Improved: Dashboard dates
- Improved: Add icon to Rule Builder error message
- Improved: Add icon to Report Builder success message
- Improved: Spanish translation
- Improved: Button custom text on multi-step forms
- Fixed: Show / hide columns on Submission Manager
- Fixed: Form Manager with table prefix
- Fixed: Submission event handler
- Fixed: Log out link
- Fixed: Export submissions as CSV file

29.12.2015 - Initial release