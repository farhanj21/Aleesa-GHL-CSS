# CSS Styling Legend

## Sidebar

### `#sidebar-v2` : entire left sidebar container
* `.flex-grow` (inside sidebar) : scrollable content column inside sidebar
* `.lead-connector`, `nav`, `.hl_nav-header`, `.hl_nav-settings` : internal sidebar layout sections
* `#sidebar-v2 a.group` : navigation items
* `#sidebar-v2 a.group img` : menu icons
* `#sidebar-v2 i.nav-fa-icon`, `i.sm-button`, `i[class*="fa-"]` : any icon inside sidebar
* `.menu-title` : section headers inside sidebar.
*  `.agency-logo` : app logo on top of sidebar.
*  `#backButtonv2` , `#backButtonv2 i` , `#backButtonv2 span` : back button on sidebar
*  `#location-switcher-sidbar-v2` : switcher on top of sidebar
*  `svg.hl_location_icon rect` , `svg.hl_location_icon path` : icons in switcher menu
*  `.switcher-caret-holder i` : caret icons on switcher


## Location Switcher (Dropdown)

### `.hl_v2-location_switcher` : entire location switcher popup
* `.hl_v2-location_switcher input[type="search"]` , `.hl_v2-location_switcher input[type="search"]::placeholder` : search box inside switcher
* `.hl_swicher-heading` : labels are RECENT, ALL ACCOUNTS
* `.hl_location-title` , `.hl_location-recent` : account names
* `.hl_text-overflow` : secondary address text
* `.bg-gray-200` : circular initial icon
* `.hl_account.active` : currently selected account
* `.hl_pinned-fade` : pin icons
* `#location-list` : scrollable list of locations

## Header (All Screens)
`h1_header` : main header container
* `.hl_header--avatar .avatar_img, .user-info-card .avatar_img` : profile dropdown avatar
* `.hl_header--dropdown .dropdown-item` : dropdown menu items
* `#recent_activities-toggle` : notifications button
* `#recent_activities-toggle i` : icon inside notifications button
* `#canny_logs-toggle` : changelog button
* `#canny_logs-toggle i` : icon inside changelog button
* `#hl_header--copilot-icon` : AI button
* `#hl_header--copilot-icon svg circle` : inner circle of AI button
* `#hl_header--copilot-icon svg path` : icon inside AI button

## Dashboard

`#location-dashboard_btn--edit-dashboard` , `#location-dashboard_btn--edit-dashboard svg`: edit dashboard button on dashboard page

## Conversations

### Mini Navigation Panel (Right Side Icon Bar)
`.mini-panel` : main mini-panel container
* `.mini-panel > div[class*="cursor-pointer"]` : all mini-panel action buttons
* `.mini-panel > div[class*="cursor-pointer"] svg` : icons inside mini-panel buttons
* `.mini-panel hr` : divider line inside mini-panel

### Notes in Mini Panel
`.new-crp--notes` : main notes container background
* `.new-crp--notes button` : primary “Add Note” button styling
* `.p-[8px].pr-[6px].text-gray-600.cursor-pointer.group` : individual note card container
* `.p-[8px].pr-[6px].text-gray-600 > .flex.items-center.justify-between` : note header container (Created by, date)
* `.p-[8px].pr-[6px].text-gray-600 > .flex.items-center.justify-between span` : note header labels (uppercase metadata)
* `div[class*="rich-text-container"]` : call summary wrapper 
* `div[class*="rich-text-content"]` : actual call summary text block
* `.text-xs.leading-[18px].text-gray-600.flex.items-center.h-6` : date/footer area under each note

### Header
`#central-panel-header` : main conversation header container (background, border, shadow)
`.conversation-header-text` : contact name title 
* `.message-header-actions .button-group button` : header button group
* `.message-header-actions .button-group button:hover svg path` : header icons
* `.message-header-actions .button-group button:first-child` : left-rounded button
* `.message-header-actions .button-group button:last-child` : right-rounded button
* `#activityDropdownMenuButton` : main activity dropdown trigger button
* `.activityDropdownMenu` : dropdown menu container
* `.activityDropdownMenu .dropdown-item` : individual dropdown item
* `.activityFilterCheckbox` : checkboxes inside dropdown

### Conversation List (Left Sidebar) 
`.messages-list--item-v2` : main conversation list item container
* `.message-list--avatar.avatar` : avatar + checkbox wrapper
* `#allCheckbox` : master checkbox 
* `.avatar[data-v-011e3426]` : avatar container
* .`avatar_img[data-v-011e3426]` : circular avatar initial
* `.avatar[data-v-011e3426] .icon.icon-v2` : small status badge inside avatar
* `.avatar[data-v-011e3426] .icon.icon-v2 div` : inner wrapper for badge
* `.time-date` : purple time/date badge
* `.messages-list--item-v2 .badge` : unread message count badge
* `.flex.content-center.truncate p` : preview message text
* `.messages-list--item-v2 > div[style*="grid-template-columns"]` : main grid 
* `.messages-list--item-v2 > div > div > div[style*="grid-template-rows"]` : row spacing inside preview text column
* `[class*="tab"].active,[class*="tab"][aria-selected="true"]` : currently active tab
* `.messages-list--item-v2.active, .messages-list--item-v2[aria-selected="true"], .messages-list--item-v2.selected` : currently active conversation
* `.conversations-list::-webkit-scrollbar` : main vertical scrollbar container for conversation list
* `.conversations-list::-webkit-scrollbar-track` : scrollbar track (background area behind the thumb)
* `.conversations-list::-webkit-scrollbar-thumb` : draggable scrollbar thumb (default state)
