## SD Long Term Agreements Releases

### 3.1.0

#### Enhancements

- AppSource App - The SDY LTAS Ledger Entry table was surfaced as an ODATA feed to be accessed by Power BI.

- AppSource App - ToolTips in SD Long Term Agreements were reviewed and updated.

- AppSource App - A number of UI Changes were made to the Role Centre.

- AppSource App - A minor UI change was made to the Setup Card.

- AppSource App - A minor UI change was made to the Vendor Worksheet.

- AppSource App - The Links in the About Page were updated.

- AppSource App - The logo in App was updated to the new logo.

### 3.0.1

#### Bug Fixes

- AppSource App - The SD LTA - Suggest Customer Refunds action in the Payment Journals was changed to use -(Remaining Amount) rather than ABS(Amount) when populating the Amount field on the Journal Line.

### 3.0.0

#### Enhancements

- AppSource App - Functionality was created to allow import of settlement amounts from an outside rebate system into the LTA Worksheet for creation of Credit Memos for Customers. 

- AppSource App - A new LTA Defaults FastTab was added to the Setup Card including new fields for Default Settlement Frequency, Default Rebate Type and Default Settlement Type. 

- AppSource App - When data is imported into SD Long Term Agreements from an external source automatically create an LTA Card for the Customer if one does not already exist. 

- AppSource App - Functionality was added to suggest Customer Refunds and allow Credit Memos created by SD Long Term Agreements to be applied to those Customer Refunds.  

- AppSource App - A new field Create Zero Amount Credit Memos was surfaced on the Setup Card. This field applies to Settlement Types of Credit Memo. Choose whether to create a zero amount credit memo if the settlement amount for the period was 0. 

- AppSource App - A field caption on the SD LTA Customer Imports list was updated. 

- AppSource App - A ToolTip was updated on the SD Long Term Agreements Setup card. 

- AppSource App - The ToolTip on the Credit Memo Reason Code on the Setup card was updated. 

- AppSource App - Recaption the Default Book Type on the Setup card to Default LTA Type. 

- AppSource App - The Default LTA fields on the Setup card were reordered. 

#### Bug Fixes

- AppSource App - When suggesting customer refunds from credit memos created by SD Long Term Agreements, only the first credit memo for a customer was added to the payment journal. This was fixed. 

- AppSource App - A fix was made to an error raised on creation of a Credit Memo if the Credit Limit for the Customer was reached and the Credit Limit message could not be opened on the page.

- AppSource App - The LTA No. was not stamped on LTA Detailed Ledger Entries on import from an external file. This was fixed.

### 2.3.0

#### Enhancements

- AppSource App - The SD Long Term Agreements Assisted Setup page was removed from the Tell Me search. 

- AppSource App - A change was made to limit the SD ISV Tenant Subscriptions page to display just our SD ISV AppSource Apps and not other SD PTE Apps.

#### Bug Fixes

- AppSource App - When selecting SD Long Term Agreements activity pages in the Tell Me/Search in a BCv22 environment, the activity pages were hanging.

- AppSource App - A change was made to the ISV Licence Notification procedure in SD Long Term Agreements to fix an issue that would raise an error when the language is changed from English to another language.

- AppSource App - An error was raised in the Assisted Setup import if non sequential enum values exist in the imported data. This was fixed.

### 2.2.0

#### Enhancements

- BCv21 App - The Licence Message displayed on first install of SD Long Term Agreements was changed to prompt the user to activate a free trial and to choose Assisted Setup from the Setup Card to create demo data. 

- BCv21 App - A page was created to display all the Simply Dynamics Apps and subscription details for the tenant. 

- BCv21 App - The Licence Expiry message/notification was updated to display the App Name. 

- BCv21 App - The Product Activation Page was updated to point to the new CRM URL. 

- BCv21 App - The ToolTips were updated to look at our new website. 

- BCv21 App - The links in the About Page were updated to point to new URLs. 

- BCv21 App - The SD Long Term Agreements permission object names were updated to our standard ISV naming convention.

- BCv21 App - Minor text changes were made to some pages on the Assisted Setup Wizard.

#### Bug Fixes

- BCv21 App - A fix was made to the code for licence key checks on the SD Long Term Agreements Role Centre.  

### 2.1.1

#### Enhancements

- BCv19 App - Added the Latest Version of the product and the AppSource URL to the About Page. 

- BCv19 App - Added the Latest ISV Licence Control with fix to Free Trials in Public Environments. 

- BCv19 App - The Allow HTTPClient Request option is set to on by default on install of the product. 

- BCv19 App - Code was reviewed to ensure that the Licence Expiry Date prompts with 5 days to go was not stopping functionality.

#### Bug Fixes

- BCv19 App - Fixed an issue where after getting a message that the Free Trials were exceeded and clicking on the Assisted Setup action an error was raised.

- BCv19 App - The Product Activation page was updated to disable the Activate button until a Product Key is filled in. This will avoid an error being raised when Activate is chosen with no Product Key entered.

### 2.1.0

#### Enhancements

- BCv14 App - The BCv17 code base up on AppSource was converted to a BCv14 code base.

- BCv17 App - The drilldown to the LTA detailed ledger entries was removed from the factboxes. A Navigate action was surfaced on the LTA ledger entries to drill down on the LTA detailed ledger entries as per standard.

- BCv17 App - Free of Charge functionality was amended to stop FOC ledger entries from being deleted.

- BCv17 App - A prompt on change of Rebate Type in the LTA Card was recaptioned for clarity.

- BCv17 App - A minor typo fix was made to the Assisted Setup Wizard.

- BCv17 App - Caption was changed on an LTA Ledger Entries Action.

- BCv17 App - The code behind the Vendors Issued Settlements Last Month was updated to show the correct count.

- BCv17 App - On the FOC Adjustment Entry page, a blank option was removed.

- BCv17 App - The Refresh FOC Ledger action was added to the LTA Setup Card.

- BCv17 App - A minor visual change was made to the Role Centre.

- BCv17 App - The Rebate Type field was added to a number of pages.

- BCv17 App - A wizard for SD-LTAS data import was created.

- BCv17 App - The View Applied Bands action was added to the LTA Ledger Entry Details FastTab in the LTA Ledger Entry Card. 

- BCv17 App - The caption on the Ledger Entries action on the LTA Card was updated to LTA Ledger Entries.

- BCv17 App - The captions on the Bands FastTab on the LTA Card were updated for a Rebate Type of Quantity (Base).

- BCv17 App - The captions on the Bands FastTab on the LTA Card were updated for a Rebate Type of Amount.

- BCv17 App - On the SD LTAS Setup Card, the Tooltip on the Default Settlement Credit Item field was updated to say "Items must be of Type Service. Specifies the value of the "Default Settlement Credit Item" field".

- BCv17 App - The DotNet_Regex codeunit was marked for removal. This codeunit is now obsolete. The Regex codeunit on the Regex Module is now used in the SD Long Term Agreements product.

- BCv17 App - Changes were made to the Accrual/Settlement Report - increased size of the Company Address field, right aligned columns to the corresponding captions. Vat Reg, Web, Email fields were removed as they were not picking up any values.

- BCv17 App - Captions of FoC were updated to FOC. 

- BCv17 App - Additional visual changes were made to the LTA Card. Actions were recaptioned, minor typos in the FactBox were fixed, caption of FastTab was changed and a menu group was created.

- BCv17 App - Balance Summary and Balance Detail report actions were enabled for all Settlement Types.

- BCv17 App - The Accrual/Settlement Summary Report was tidied up.

- BCv17 App - A small typo in the Long Term Agreement Details FactBox was fixed.

- BCv17 App - Visual changes were made to the Vendor and Customer Long Term Agreements List Pages. Freeze frames were added, columns were reordered, actions were added to a new menu group and actions were recaptioned.

- BCv17 App - The Bands Used field was removed from the LTA Ledger Table as multiple bands can be used for the one accrual or settlement calculation on the LTA Card.

- BCv17 App - The From Value and To Value in bands was re-introduced as there was an issue in calculations across an invoice that spanned multiple bands. Having a minimum value field only does not cater for "exclusion" of value up to next band. In other words the "cut-off" value for each band is not quite clear.

- BCv17 App - A change was made to allow users select/update the LTA No. on the FOC lines.

- BCv17 App - Credit Memos produced as part of the Settlement, and FOC items, are now excluded from the next calcs of accruals and settlements. 

- BCv17 App - Two individual worksheet cues were created in the Activity Groups in the Role Centre. One cue for the Customer Worksheet and another cue for the Vendor Worksheet.

- BCv17 App - Fields, FastTabs and Cues on the SD Long Term Agreements Setup Card were recaptioned.

- BCv17 App - A minor mod was made to the Balance Detail and Balance Summary Report.

- BCv17 App - A new page was created to display the information on the drilldowns on the Worksheet Lines - to display the records that make up the Total Quantity (Base)/Total Amount/Total Accrual Amount/ Total Settlement Amount.

- BCv17 App - Changes were made to the Vendor Worksheet and FactBox - a freeze frame was added, columns were re-ordered, a new FactBox was created for the Worksheet.

- BCv17 App - Changes were made to the Customer Worksheet and FactBox - a freeze frame was added, columns were re-ordered, a new FactBox was created for the Worksheet. 

- BCv17 App - A freeze frame was added to the SD LTA Ledger Entries page and columns were reordered. 

- BCv17 App - Changes were made to the Role Centre - A new cues were created. Two Activity Groups were created one for Customer and the other for Vendor. Other cues were recaptioned.

- BCv17 App - In the SD Long Term Agreements Worksheet, if suggest accruals or suggest settlements records exist, an error is now raised that the records will be removed and recalculated.  

- BCv17 App - Changes were made to the LTA Card. The FactBox on the LTA Card was modified, the difference between Suggested Accruals and Issues Accruals was made clearer.

- BCv17 App - The Name/Caption Book was removed from the product we now reference Long Term Agreements (LTAs) and not Book or LTA Book.

- BCv17 App - Changes were made to stamp the from period on the the LTA FactBox so users can easily see when the last period was run for the LTA. 

- BCv17 App - KPIs of Active LTAs and Inactive LTAs were added to the SD Long Term Agreements Setup.

- BCv17 App - Updated the functionality to allow users to highlight and confirm the selected lines in the SD LTA Worksheet.

- BCv17 App - Settlements and Accruals are filtering on the Posting Date from the Customer Ledger Entry or Vendor Ledger Entry.

- BCv17 App - Captions were updated on Actions to allow for future translations.

- BCv17 App - Visual changes were made to the SD Long Term Agreements Setup Card. Actions were renamed and the SD LTA Job Queues pages were restructured as per SD Bulk Mailer and SD Case Manager where users can create their own job for SD Long Term Agreements.

- BCv17 App - Licencing functionality was added to the SD Long Term Agreements and an Action added to the Setup Card.

- BCv17 App - Visual changes were made to the Role Centre.

- BCv17 App - A Test Package was created for AppSource validation.

- BCv17 App - On the LTA list, change the Free of Charge Ledger Action to be enabled only for an LTA record with a Settlement Type of Free Of Charge.

- BCv17 App - Updated the Free of Charge functionality to allow users to add the LTA No. to the Free of Charge Ledger Entry. Updated the Free of Charge functionality to only search for those CLE or VLE lines that are stamped with the Free of Charge code on the LTA Card.

- BCv17 App - Updated the SD Long Term Agreements Activity Pages in the Role Centre to be searchable in the Tell Me.

- BCv17 App - Permission sets were created for SD Long Term Agreements.

- BCv17 App - Added a notification on open of the Free of Charge Ledger Entry Page to synchronise new Item Ledger Entries.

- BCv17 App - When the SD Long Term Agreements Setup card is opened a notification is raised if the SD LTA Job Queue is not set to Ready.

- BCv17 App - On the Accruals Details Report, the date/time formatting was changed.

- BCv17 App - On the Accruals Report, the date/time formatting was changed.

- BCv17 App - When the LTA Card is set to enabled, certain fields and FastTabs are now marked as non-editable. 

- BCv17 App - The order of fields and FastTabs were changed and tidied up on the LTA Card.

- BCv17 App - The Default Free of Charge Reason Code on the SD Long Term Agreements Setup card is now defaulting into the Free of Charge Manual Adjustments page.

- BCv17 App - When creating manual adjustments for Free of Charge settlements when the user selects the LTA No. the No. and Return Reason Code are now defaulted into the adjustment page from the LTA.

- BCv17 App - Made a change to the LTA Card, if manual numbering is allowed then do not show the LTA No field on the card as per standard Dynamics 365 Business Central behaviouer.

- BCv17 App - Updated the page caption on the SD Long Term Agreements List page.

- BCv17 App - Updated the caption on the SD Long Term Agreements Card.

- BCv17 App - A modification was made to the LTA FoC Handler Codeunit to change the field ILE Document Type from Option to Enum.

- BCv17 App - A modification was made to the LTA FoC Handler Codeunit to change the field ILE Entry Type from Option to Enum.

- BCv17 App - Duplicate menus actions in pages were removed.

- BCv17 App - Tooltips were added to page fields and to actions.

- BCv17 App - Assisted Setup functionality and an action was added to the SD Long Term Agreements Setup Card. This imports an xml file from GitHub with default setup values.

- BCv17 App - Translation units were added to the product.

- BCv17 App - Name, description and related fields were increased as per standard Dynamics 365 Business Central.

#### Bug Fixes

- BCv17 App - The Issued Settlements Last Month cue was not filtering correctly.

- BCv17 App - Captions on the Bands FastTab in the LTA Card were updated.

- BCv17 App - The entries in the FOC Ledger Entry had the incorrect sign.

- BCv17 App - The Tiered Bands in the LTA Cards were calculating incorrectly. This functionality is now fixed.

- BCv17 App - As the Recalculate Line Action on the Worksheet was not recalcing correctly, this action was removed as the suggest accruals action and the suggest settlements action are recalcing.

- BCv17 App - Fixed an issue where if an LTA Book was copied into the same year and error was raised.

- BCv17 App - Fixed an error that was raise when Suggesting Accruals on an LTA with a Settlement Type of FoC. 

- BCv17 App - A fix was made where an item line cannot be added to an already created and enabled LTA.

- BCv17 App - Fixed an issue where in the FOC Adjustment Entry Page, the Source No - Customer No. or Vendor No. is not refreshing when the Source Type is changed.

- BCv17 App - Fixed an issue where when changing the Rebate Type on an LTA and selecting no to the prompt to change, the Rebate Type was updated anyway. 

- BCv17 App - In the SD Long Term Agreements list when choosing the Copy LTA action and choosing no to the prompt to copy the book, the records in the list were incorrectly filtered down to show only one record in the list.

- BCv17 App - Fixed an issue where when an FOC ledger line for an LTA was archived, FOC lines for other LTAs ere displayed in the page.


### 2.0.0

#### Enhancements

- BCv14 App - Changes were made to the Worksheet functionality to filter out the Settlement Types when calculating the Accruals/Settlements. A change was also made to exclude the Credit Memos generated by the LTA functionality from being included in the next periods by stamping the LTA Book No. onto the Your Reference field. During the settlement/accrual generation we exclude any credit document that has an existing book number in the Your Reference field. FOC items generated by the LTA functionality are excluded from the next periods by checking the return reason codes assigned on any book and excluding aby posted sales/purchase invoice/credit lines with the same value from the calculation.

- BCv14 App - Visual changes were made to the Worksheet - the Calculate action was renamed to Recalculate Worksheet.

- BCv14 App - A Role Centre Page was created for the product,

- BCv14 App - Visual changes were made to the Book Card. The Band Type field was renamed to Rebate Type.

- BCv14 App - A change was made to the Accrual/Settlement Detail Report to add an option to show the breakdown of the details and document no. The document no.s that make up the line are shown if the detail option is chosen.

- BCv14 App - Changes were made to the Accrual Settlement Report to review why lines weren't coming through on the report.

- BCv14 App - Added licensing and Assisted Setup to the product.

- BCv14 App - The Usage Category property was updated to allow users search for the SD-LTA pages in the Tell Me.

- BCv14 App - Remove the default filters Related Type and Settlement Type from the request page when the Suggest Accruals and Suggest Settlements are chosen from the Customer Worksheet.

- BCv14 App - Default the Reason Code specified in the LTA Setup to the LTA Book.

- BCv14 App - Updated the caption on the Report Request page for the reports from Group 1 to Options.

- BCv14 App - Visual changes were made to the LTA Book to display the Items and Items Categories lists one under the other rather than displaying the lists side by side.

- BCv14 App - A change was made to the LTA Book Card to remove the white space between the Bands FastTab and the Inclusions FastTab.

- BCv14 App - The logic around the default settings in the Job Queue Card when the LTA Job Queue action in the LTA Setup Card was reviewed.

- BCv14 App - Fixed a message raised when the About Action was selected.

- BCv14 App - Added a product logo to the App.

- BCv14 App - Converted the work in progress v2.0.0 2018 code base to D365BC AL extensions.

- BCv14 App - Renamed Actions in the Customer and Vendor Worksheets.

- BCv14 App - Changes were made to the Bands to remove Type and To Value.

- BCv14 App - Removed the Product Groups from the SD - LTA Setup.

- BCv14 App - Customer and Vendor FactBoxes were created for the Worksheets with last dates and values for the customer or vendor.

- BCv14 App - A separate Vendor Worksheet and a separate Customer Worksheet were created.

- BCv14 App - Created a Rebate Report.

- BCv14 App - Added a new FOC product ledger to the Product.

- BCv14 App - Created a new settlement function allowing users to specify and create the settlement type - credit note/report/FOC product.

- BCv14 App - Created an accrual function to automate journal creation. There are two report options a summary report option and a detail report option.

- BCv14 App - Added a count of activity ledger lines and last accrual and last settlement dates to the LTA Book list and LTA Book card pages.

- BCv14 App - Updated the Activity Panel - added the Setup and Worksheet to the activity group.

- BCv14 App - Added an option to the LTA Worksheet to allow users to close books in bulk.

#### Bug Fixes

- BCv14 App - Fixed an issue in calculating the accrual amount for Quantity Base.

- BCv14 App - Replaced to TODAY function used in the Worksheet calculations with the WORKDATE function.

- BCv14 App - An error was raised when the Import/Export actions on the SD LTA Setup Card were chosen. This functionality is now obsolete and the actions and code were removed.

- BCv14 App - Fixed an issue with calculations in the Worksheet.

### 1.0.2

#### Enhancements

- Removed the Chart objects from the build and renumbered the objects.

- Increased length of Item Category Code in SD-FBLT Item Category to 20 chars to handle length in NAV versions later than 2016.

- Removed standard NAV OneNote, Notes and Links from the Setup Card.

- Updated the About page and surfaced on the Setup Card.

#### Bug Fixes

- Fixed an issue where the G/L Account Code in the LTA Book Setup is not copied to the LTA Ledger Entry Detail Line.


### 1.0.1

#### Enhancements

- Long Term Agreements was split out into it's own project.

- Role Center Activities were split out into individual pages.

- Renamed Namespace to Simply Dynamics.

### 1.0.0

#### Enhancements

LTA module: 
- Upgraded, renamed and renumbered code for LTA module. 
- Initial Code Merge. 
- Created Readme.txt. 
- Reordered pages. 
- Code restructure. 
- Created Event Hooks for LTA module. 
- Created and LTA Setup Card and table. 
- Created Charts for the LTA module and display in the Role Centre. 
- Created XMLports for Import/Export of Setup and Data. 
- Created a Role Center.
- Generated Help files. 
- Add an option to open Sales Invoices and Credit Memos from the LTA Ledger Entry Lines on the LTA Ledger Entry Card. 
- UI improvements to the LTA Book Card. 
- Reordered fields in the General FastTab of the LTA Book Card for ease of user input. 
- Display the Item No. and the Item Description fields by default in the SD-FB LTA Price Group Line Page. 

MGP module: 
- Upgraded, renamed and renumbered code for MGP module. 
- Initial Code Merge. 
- Created Readme.txt. 
- Reordered pages. 
- Code restructure. 
- Renamed the List option to Standard to reflect functionality. 
- Created Charts for the MGP module and display in the Role Centre. 
- Created XMLports for Import/Export of Setup and Data. 
- Created a Role Center. 
- Generated Help files. 
- Added a new flowField on the MGP Price Group table to count the number of records on the Price Group Line. 
- Group the Price List report by Item Category Code 
- In the Price Group Line Page - ensure the start and end dates are within the price book header start and end dates. 
- In the Price Group Line Page, to facilitate ease of data entry, on insert of a new line, default the UOM to the Item Sales UOM. 
- In the Price Group List, show the number of price lines associated with the Price Book. Allow KPI drill down to the Price Line Page. 
- In the Price Line Worksheet, change the Action Caption from Select prices to Get Prices. 
- Price Line Worksheet to allow the user to filter and make price changes easier, flow fields to the Item Category and Product Group were added to the table to allow users to filter and select for easier price changes. 

Catch Weight and Expiry Dates module: 
- Created new tables, pages and associated functionality for Item Extended FANDB, Item Units, Item Shelf Life, Item Shelf Life Worksheet, Item Units Worksheet Created Readme.txt. 
- Reordered pages. 
- Keep extended item table in sync with item table using events. 
- Created a chart for the Catch Weight and Expiry Dates module and display in the Role Centre. 
- Created XMLports for Import/Export of Setup and Data. 
- Created a Role Center. 
- Generated Help files. 
- Created and Item List Page. 
- Created Extended Item Card Part Page. 
- Fixed the vertical alignment of the fields in the SD-FB Item Card. 
- In the Item Card SD-FB Item Card fixed the width of the SD FB fields in the Catch Weight Fast tab (the Avg and Min Weight fields). 
- In the SD-FB Item Shelf Life List page, displayed the Item description of the Item in Item No. 
- In the Stock Units Worksheet, displayed the Item Description for the Item No. 
- In the SD-FB Item List, moved the Catch Weight Enforcement and Shelf Life Enforcement columns beside the Item Description column.

#### Bug Fixes

LTA module: 
- Fixed bug whereby filters were not applying correctly if two LTA Books exist for the same Customer. 
- Settlement Amount and Total Settlement Amounts are calculating incorrectly. 
- In the LTA Book Page, in the Accrual/Settlement Fast Tab, the Field Captions are not displaying in full. 
- Fix the LTA Setup - No. Series to act as per standard NAV number series. 
- Calculation issue with LTA - refactored the code and restructured it to improve the functionality and to make it easier to understand from an end users point of view. 
- G/L Account not being stamped in the LTA Ledger Card - when the LTA Worksheet generates Accruals or Settlements, the G/L account on the LTA Book is not being stamped on the LTA Ledger Entry. 
- Error thrown when selecting the Accrual/Settlement Report Action from the LTA Worksheet. 
- Start and end dates on the Price Group Line should be within Price Group Header start and end dates. 
- Display the Item No. and Item Description by default in the SD-FB LTA Price Group Line Page, currently users would have to select choose columns to display the Item No. and Item Description. 
- LTA - Accrual Calculation - A Credit Memo quantity is treated as an Invoice quantity in the Accrual and Settlement Calculations. The amount for Credit Memo is being calculated as a positive amount rather than as a negative amount. 

Catch Weight and Expiry Dates module: 
- Fix spelling mistake in the SD-FB Item Card.
- In the Freeze Down Journal and the Reclass Journal fields in the SD-FB Item Extended Card and the SD-FB Item Card incorrect Journal Templates are displaying on drilldown. The Freeze Down Journal displays a list of Journals with a Journal Template Name of "RECLASS". While the Reclass Journal displays a list of Journals with a Journal Template Name of "Phys. Inv". 
- In the SD-FB Item Shelf Life List Page, fields are not being re-set/updated on change of Cross-Reference Type. 
- Drilling down on the Customer Min Shelf Life rules and the Vendor Min Shelf Life Rules from these pages is showing records for all Item Nos and not the Item that the user is currently on. 
- In the SD-FB Item Card selecting the Catch Weights and Shelf Life Action raises an error.
- Users should not be able to insert records into the Item Units Page. This page should be read only. 
- The following fields were moved from the Item Extended table to a Setup table - Freeze Down Journal Template, Freeze Down Journal Batch, Campaign Location Code, Campaign Reclass Journal Temp., Campaign Reclass Journal Batch. 
- SD-FB Item Shelf Life WrkSheet - do not allow manual record input into this page. The only field users can update is the Confirm Action Checkbox. 
- A rename record message is raised on input of record into the SD-FB Item Shelf Life List Page. 
- The Description field on the Item-Cross References Page should be non-editable. 
- The Description field on the Item Shelf Life Worksheet should be non-editable. 
- In the Role Centre in the Catch Weights and Shelf Life Activity Group, the Cue link was renamed to Item Shelf Life to match the Navigation Pane. 
- Removed the New Item Unit link in the Role Centre from the Catch Weights and Shelf Life Activity Group as users cannot manually create an Item Unit Ledger. 
- Unit Stock Worksheet - when entries are calculated, records that have no stock location are not brought into the worksheet.
- The Item Units Stock Worksheet should calculate the current unit item count up to the specified posting date (..Posting Date). 
- In the Goods In Shelf Life functionality, when receiving a PO the Expiration Date, calculated off the Default Purchase Shelf Life for the Item, is raising an error as the Expiration Date calculation (using the default Shelf Life) and the Shelf Life check is using different logic. 
- The Shelf Life functionality on the Purchase Line is re-setting the user updated Expiration Dates back to the system calculated date. 
- There is a blank Description field on the SD-FB Item Shelf Life Worksheet Page. 
- Movements for Catch Weight Items received in are not being stamped to the SD-FB Item Unit Ledger table.
