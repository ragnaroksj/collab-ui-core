## Change Log
All notable changes to this project will be documented in this file.

### v10.7.0 (2018-6-6)

#### Features

* **sub-menu**:
  * Displaying arrow and selected value if the menu item has a submenu
  * Displaying arrow and selected value if the menu item has a submenu
* **avatar**: added sizes

#### Bug Fixes

* **avatar**: fixed class name for img__hidden
* **space-list**: ellipsis overflow to attachment-bottom
* **list-item**: fix mixin issue for Sections

### v10.6.0 (2018-6-5)

#### Features

* **list-item**:
  * Rebase from master
  * Add styling for list-item separator
* **button**: added white button style
* **alert-container**: Styles for displaying alerts
* **social-list**:
  * add social list style and fix footer style
  * add social list style
* **space-list**: added types

#### Bug Fixes

* icon**: added to nav.json
* space-list**: fix header on filter type
* list-ltem**: removed SpaceList setting
* avatar**: display none for hidden

#### Refactors

* **listItem**: split mixins

### v10.5.0 (2018-5-31)

#### Features

* **sub-menu**:
  * Remove overflow auto default value for eventOverlay and using it only in required cases
  * add the docs changes for Menu
* **alert-call**: Add device selection list
* **avatar**:
  * Changing xlarge size of avatar
  * Sizing the avatars with ems
  * Review comments fixed

#### Bug Fixes:

* **listItemSection** added back flex-shrink
* **button** remove all link styles

### v10.4.0 (2018-5-21)

#### Features

* **AlertCall**: Styling for AlertCall component
* **accordion**:
  * Adding height as a modifier
  * Added dark style to accordion

### v10.3.3 (2018-5-18)

#### Bug Fixes

* **panel**: ie11 flex fix for footer

### v10.3.2 (2018-5-14)

* **media**: fix height media query

### v10.3.1 (2018-5-14)

#### Features

* **media**: add small and medium heigh media queries
* **blockquote**: make font color inherit and update border color

#### Bug Fixes

* **panel**: update logo spacing for short screens


### v10.3.0 (2018-5-11)

#### Features

* **avatar**: Add bot,failure badge, and typing types to Avatar

### v10.2.0 (2018-5-10)

#### Features

* **logos**: add cisco and webex logos to package
* **SpaceListMeeting**: added styling
* **MeetingAlert**: Styles for Meeting Alert.
* **Alert**: Updated design for Alert
* **ListItemHeader**: created SparkUI styles
* **CollapseButton**:
  * Adjusted style according to mocks
  * Implementation for CollapseButton
* **Accordion**:
  * Controlling separator by a prop
  * Adding group separator or accordion

#### Bug Fixes

* **list**: added vertical list class
* **listItem**: fixed color since form label changed to inherit


### v10.1.3 (2018-5-7)

#### Bug Fixes

* **panel**: update padding for input with icon

### v10.1.2 (2018-5-8)

#### Features

* **panels**: update styles for new design

### v10.1.1 (2018-5-7)

#### Bug Fixes

* **npm**: move cli-patch for post-install script

### v10.1.0 (2018-5-7)

#### Features

* **panel**: add panels for login, sign up and error flows

#### Bug Fixes

* **colors**: make black colors inherit for default text colors

### v10.0.0 (2018-5-4)

#### Features

* **focus**: add remove focus mixin
* **space-list**: added overview variation
* **sideNav**: code refactor
* **sideNav**: add left side navigation style
* **slider**: Fixing alignment of sliderlabel
* **sites**: add layout styles for collab sites
* **editText**: nav.json entry for editable textfield
* **Lightbox**: changes as per comments in collabui/react
* **docs**: Added back the missing docs
* **light-box**: light-box implementation

#### Bug Fixes

* **badge**: move unprefixed badge class to ng
* **typography**: remove default H tag colors
* **class name**: change summary to overview
* **avatar**: remove unecessary flex mixin
* **docs**: add missing footer section
* **spelling**: change backround to background
* **button**:
  * added mozilla prefix back in
  * per PR comments
  * abstract mixins and fix dark states
  * remove last button selector
* **buttonContainer**:
  * selectors and variables
  * applied size to button container
* **footer**: update styles to match design
* **top-bar**: update styles for sites top-bar


#### Refactors

* **popover**: update to current style standards
* **avatar**: replace class selector with variable
* **footer**: remove unused selectors

### Breaking changes

* **popover**: add cui prefix to popovers
* **breadcrumbs**: add cui prefix to breadcrumbs

### v9.0.1 (2018-4-27)

#### Bug Fixes

* **icons:** update icon font name

### v9.0.0 (2018-4-25)

#### Chores

* **release:** initial release to new GitHub Repo
