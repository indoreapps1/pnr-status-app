PNRStatusAppV3 3.0.0 [August 2012]
 - [START] 		Rewrite app for ICS / JellyBean API
 - [CHANGED]	Converted Activities to Fragments
 
PNRStatusAppV3 3.0.6 [August 2012]
 - [ADDED]		Read messages from SMS from POC
 - [CHANGED]	minSdk is now 11 to use StackView 
 
PNRStatusAppV3 3.0.10 [August 2012]
 - [CHANGED]	Resources 
 - [ADDED]		Managers for managing different data sets

PNRStatusAppV3 3.0.11 [August 2012]
 - [ADDED]		Parse MessageVo into PNRStatusVo
 - [ADDED]		Display selected message details in the box 
 - [CHANGED]	Styles
 - [ADDED]		Sort PNRMessages based on journey date
 - [OPTIMIZED]	Code Cleanup

PNRStatusAppV3 3.0.12 [September 2012]
 - [CHANGED]	Layout changes in PnrStatusView
 - [FIXED]		Parsing Berth position correctly from messages
 - [FIXED]		Set Train Current Status properly
 - [ADDED]		Better Date display with month name
 - [CHANGED]	Text Alignments in Messages View
 
PNRStatusAppV3 3.0.14 [September 2012]
 - [ADDED]		Remove a PNR Number
 - [REWRITE]	Sending data from Custom Adapters to Activities
 - [CHANGED]	Communication between activity and fragment
 
PNRStatusAppV3 3.0.15 [September 2012]
 - [CHANGED]	Layout for StackAdapter Item
 - [ADDED]		Display a message count items in StackAdapter
 - [ADDED]		Link for app's facebook page
 - [ADDED]		Execute a service instance and show the result for Checking PNRStatus
 - [FIXED]		Bug fix in parseResponse implementation
 
PNRStatusAppV3 3.0.16 [September 2012]
 - [ADDED]		Create Dialog for displaying the status details of a PNRStatus
 
PNRStatusAppV3 3.0.20 [September 2012]
 - [BUG]		An exception identified as NetworkOnMainThreadException encountered
 - [FIXED]		Use a Handler to do the newtork operation
 - [CHANGED]	Added an additonal layout for landscape for Messages View
 - [CHANGED]	The about text
 - [ADDED]		Closed some cursors
 - [ADDED]		Better icon for facebook and the ae logo in about page
 - [FIXED]		Reservation Upto was mapped wrongly.
 
PNRStatusAppV3 3.0.28 [November 2012]
 - [ADDED]		Added confirmation dialog on deleting a PNR Entry
 - [CHANGED]	PNR Number is formatted for readability.
 - [CHANGED]	Layout changes for Ticket Info page
 
PNRStatusAppV3 3.0.30 [December 2012]
 - [ADDED]		Added date and berth type fields to the Message details in Message View
 - [ADDED]		Click on the PNR Number in the PNRNumber view to copy that number to the clipboard.
 - [FIXED]		Sorting of messages based on travel date in Messages view

PNRStatusAppV3 3.0.35 [January 2013]
 - [ADDED]		Display ticket chart preparation status
 - [CHANGED]	Lint optimizations
 - [ADDED]		ProgressBar while we check for a PNR Status

=============================
Version 3.1 Code named Marvin
=============================
 
PNRStatusAppV3 3.1.10 [January 2013]
 - [ADDED]		Application now supports Android 2.2 and up
 - [FIXED]		Null Pointer fix for Messages landscape view
 - [FIXED]		Missing divider in Messages Lansdcape View
 - [FIXED]		Change Add PNR Text color for lesser versions of android
 
PNRStatusAppV3 3.1.22 [January 2013]
 - [CHANGED]	Localization of strings with the help of format strings
 - [CHANGED]	Code Cleanup
 - [CHANGED]	Code Optimization
 - [ADDED]		Click on the additonal details layout in Messages View to copy the PNR to clipboard
 - [FIXED]		Code for Copy to Clipboard on earlier versions of Android
 
PNRStatusAppV3 3.1.24 [January 2013]
 - [CHANGED]	Code Optimization
 - [CHANGED]	Modifications to Message Details View
 
PNRStatusAppV3 3.1.34 [February 2013]
 - [CHANGED]	More Localization strings
 - [CHANGED]	Reference to API11 and above are specified using fully classified name rather than import 
 - [ADDED]		Added Settings Activity
 - [FIXED]		Berth position calculation for AC3 Class
 - [FIXED]		Trim to get the class from the webservice correctly
 - [FIXED]		Berth position for RAC
 - [OPTIMIZED]	MessagesFragment
 - [ADDED]		Detect and show appropriate error message for error on parsing (invalid pnr)
 - [CHANGED]	Rewrote strings in settings
 - [FIXED]		Messages not showing current day's message if set to hide past messages
 
PNRStatusAppV3 3.1.52 [May 2013]
 - [CHANGED]	Better images for Share Icon
 - [ADDED]		Day name along with journey date for tickets from inbox 
 - [CHANGED]	ShareIcon is an ImageButton now
 - [CHANGED]	ShareIcon sizing issue fixed
 - [ADDED]		Select service to be used in Preferences
 - [ADDED]		Choose between PNRAPI or IndianRail as service
 - [FIXED]		Changes to parsing for new PNRAPI service
 - [FIXED]		Day name for journey date was incorrect
 - [ADDED]		Show the selected service in the Preferences Page
 - [OPTIMIZED]	Code Cleanup
 - [ADDED]		Style value for Dialog based on OS Version
 - [FIXED]		Translation spelling correction

 PNRStatusAppV3 3.1.60 [June 2013]
 - [CHANGED]	Built with Android 4.2.2 SDK
 - [CHANGED]	Implemented themes properly pre honeycomb and post (Holo)
 - [FIXED]		Divider image on Messages list was visible when there was no messages to show
 - [OPTIMIZED]	Optimized MessagesFragment View
 - [ADDED]		Indicate to teh user in case there are no messages in Message View
 
 PNRStatusAppV3 3.1.68 [July 2013]
 - [ADDED]		Added utility class DialogUtils for utility methods for displaying Dialogs
 - [ADDED]		Added strings for License
 - [OPTIMIZED]	Removed unused code
 - [ADDED]		One more dialog style added with titlebar
 - [ADDED]		Added layout and text for License Dialog
 - [OPTIMIZED]	Improved the way of showing License Dialog
 
PNRStatusAppV3 3.1.86 [August 2013]
 - [CHANGED]	Able to reflect settings changes for 
 - [OPTIMIZED]	Layout Optimizations
 - [ADDED]		Dark Message image for no PNR messages found
 - [CHANGED]	PNR Buttons are now image buttons
 - [ADDED]		Settings with icon moved to actionbar if supported 
 
PNRStatusAppV3 3.1.92 [October 2013]
 - [ADDED]		Add icon for the add prn button
 - [CHANGED]	Moved resources to XMLs
 - [CHANGED]	Hero screen layout
 - [ADDED]		Disabled state for the Info button
 - [CHANGED]	The Ticket details Popup is standardized
 
PNRStatusAppV3 3.1.95 [November 2013]
 - [CHANGED]	Build target API is 18
 - [CHANGED]	Minor layout tweaks
 - [CHANGED]	Minor message change
 
PNRStatusAppV3 3.1.97 [December 2013]
 - [CHANGED]	File organization
 - [CHANGED]	App Icon change
 
PNRStatusAppV3 3.1.98 [December 2013]
 - [ADDED]	Workarounds to work with indianrail

==============================
Version 3.2 Code named Marvin2
==============================
 
PNRStatusAppV3 3.2.10 [March 2014]
 - [CHANGED]	Using apache http client for network
 - [CHANGED]	Exception handling
 - [CHANGED]	UI Tweaks
 
PNRStatusAppV3 3.2.18 [March 2014]
 - [ADDED]		Custom header for ticket info dialog, which includes the share icon
 - [CHANGED]	Reset status when check button is clicked
 - [OPTIMIZED]	Code cleanup
 - [ADDED]		Apache HttpClient for http operations

PNRStatusAppV3 3.2.25 [March 2014]
 - [ADDED]		PNRStatusService
 - [CHANGED]	No highlight color when list is highlighted 
 - [CHANGED]	Text resources and layouts
 - [ADDED]		Logger wrapper to log data only in development mode
 - [CHANGED]	Code Cleanup

PNRStatusAppV3 3.2.30 [March 2014]
 - [ADDED]		Tips section in about screen
 - [CHANGED]	to PagerTabStrip
 - [CHANGED]	Default service to PNR Status Service
 - [CHANGED]	Order of status services in preference page
 - [ADDED]		Prevent adding same pnr number again
 - [ADDED]		Basic support for tablet screen
 
PNRStatusAppV3 3.2.40 [April 2014]
 - [ADDED]		Tablet screen optimizations
 
PNRStatusAppV3 3.2.44 [June 2014]
 - [CHANGED]	PNR Message display corrections
 
PNRStatusAppV3 3.2.5 [May 2016]
 - [ADDED]		IRCTCPNRService
 - [CHANGED]	UI Tweaks