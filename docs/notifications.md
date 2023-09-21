> Notifications are messages that communicate information to the user. The two main types of notifications are alerts and toast notifications.

## Usage

Use notifications to inform users of updates or changes to the system. Communicating with users and providing immediate feedback are important for building trust. While notifications are an effective method of communicating with users, they are disruptive and should be used sparingly.

### Good Principles

* __Informational__ - provide important information I.e. updates on the entire system or regarding an app’s processes. 
* __Durational__ – the display duration could be permanent, stays on the screen forcing the user to perform an action or appear temporarily, disappear on their own without requiring user input to be dismissed. 
* __Contextual__ - placed in the most suitable area of the UI. Alert banners on the top, toasts on the bottom. 

### Types

* __Alert__ - notification which affects the entire system. 
* __Toast__ – serves as a feedback & confirmation mechanism after the user takes an action. 

## Alerts

Alerts communicate a state that affects the entire system, not just a feature or page. It persists over a session and appears without the user initiating the action. The alert didn’t disappear automatically, it stays until the user perform an action or alternatively dismiss the alert. 

Those notifications provide limited space for content, and therefore the content must be short and concise. A user should be able to quickly scan the notification, be apprised of the situation, and know what to do next.

### Anatomy

<img src="https://user-images.githubusercontent.com/10553294/81702263-b8c09480-9473-11ea-83be-944841e3f943.png" width="100%" alt="Alert"/>

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Alert Icon | [Action Icon](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/iconography?id=add-delete-and-alerts) Alert Icon give additional visual information of the current Alert. |
| 2 | Alert Container | Displayed by stroke around an alert content. Containers improve the discoverability of the alert by creating a contrast with the surrounding content. Access to the rest of the UI is enabled, but the alert will stay until the user perform an action. |
| 3 | Alert Body | Displays a description of the alert. Should be short and concise, enough informative for the user. |
| 4 | Action Link | Action link allowing the user to perform an action (_Learn more, Log out, etc._) |
| 5 | Dismiss Icon | [Close Icon](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/iconography?id=content) will dismiss the alert. |

### Behavior

An alert displays an important, succinct message, and provides actions for users to address (or dismiss the banner). Require user action or should be dismissed.

Alerts should be displayed at the top of the screen, below a top app bar. They’re persistent and nonmodal, allowing the user to either ignore them or interact with them at any time. Only one alert should be shown at a time.

They have Action Icons which helps the user for easier scanning and understanding the alert content.

Typically, alerts are displayed in specific colors stands for different states.

__Appearing__ 

> Alerts normally appear when a screen loads content.

__Dismissing__ 

> Alerts must remain on screen until dismissed by the user.

#### Focus state

<img src="https://user-images.githubusercontent.com/10553294/81702284-bd854880-9473-11ea-8ab8-ea08f42d6d53.png" width="100%" alt="Alert"/>

> On focus, the alert or the dismiss icon is outlined with a `3px` border. The border color is `#566FE6`. 

#### Hover state

<img src="https://user-images.githubusercontent.com/10553294/81702300-c249fc80-9473-11ea-8bfa-a9ae2beaaaa7.png" width="100%" alt="Alert"/>

> On hover state, the alert container or the dismiss icon background changes color to `30%` of `#C8C9C7`. 

#### Alert Variations & Roles

Currently, we have four main variations of alerts I.e. default, info, warning and error. By the content we define the role of the alert and chose the proper variation.

<img src="https://user-images.githubusercontent.com/10553294/81702312-c6761a00-9473-11ea-9a64-0b92d90cc818.png" width="100%" alt="Alert"/>

| # | Variation | Description |
| - | --------- | ----------- |
| 1 | Default | [Info Icon](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/iconography?id=add-delete-and-alerts) Icons & Body color is `#FFFFFF`. The alert container color is `80%` of `#4A4F54` |
| 2 | Info | [Info Icon](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/iconography?id=add-delete-and-alerts) Icons & Body color is `#FFFFFF`. The alert container color is `80%` of `#006580` |
| 3 | Warning | [Warning Icon](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/iconography?id=add-delete-and-alerts) Icons & Body color is `#000000`. The alert container color is `80%` of `#FF9E18` |
| 4 | Error | [Error Icon](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/iconography?id=add-delete-and-alerts) Icons & Body color is `#FFFFFF`. The alert container color is `80%` of `#D22630` |

### Specifications

<img src="https://user-images.githubusercontent.com/10553294/81702328-cb3ace00-9473-11ea-8bab-e34781e22bcc.png" width="100%" alt="Alert"/>

| Element | Attribute | Value |
| ------- | --------- | ----- |
| Alert Icon | <ul><li>Size</li><li>Color</li><li>Top/Bottom Padding</li><li>Left Padding</li></ul> | <ul><li>Check Iconography</li><li>`#333333`</li><li>`1.5em`</li><li>`2em`</li></ul> |
| Alert Body | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li><li>Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`1em`</li><li>`#333333`</li><li>Sentence-case</li><li>`1.5em`</li></ul> |
| Dismiss Icon | <ul><li>Size</li><li>Color</li><li>Top/Bottom Padding</li><li>Left Padding</li></ul> | <ul><li>Check Iconography</li><li>#333333</li><li>`1.5em`</li><li>`2em`</li></ul> |

!> Check Iconography https://amplify.git-pages.ecd.axway.org/design-system-2020/#/iconography?id=add-delete-and-alerts The colors depends on the roles. Check Alert Variations & Roles section. 

### Responsive Grid

#### 1140

<img src="https://user-images.githubusercontent.com/10553294/81702347-d130af00-9473-11ea-9c48-90854cbbbaae.png" width="100%" alt="Alert"/>

#### 1024

<img src="https://user-images.githubusercontent.com/10553294/81702358-d55ccc80-9473-11ea-8292-20b4a1e8ccd0.png" width="100%" alt="Alert"/>

#### 839

<img src="https://user-images.githubusercontent.com/10553294/81702369-d8f05380-9473-11ea-9f4a-ada6b67c5a68.png" width="100%" alt="Alert"/>

## Toasts

Provide brief messages about app processes at the bottom of the screen. Toast inform users of a process that an app has performed or will perform. They appear temporarily, towards the bottom of the screen. 

They appear without warning, and don't require user interaction. They automatically disappear from the screen after a minimum of four seconds, and a maximum of ten seconds. 

### Anatomy

<img src="https://user-images.githubusercontent.com/10553294/81705295-903a9980-9477-11ea-91a3-fafab80ea6f7.png" width="100%" alt="Toast" />

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Toast Icon | [Action Icon](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/iconography?id=add-delete-and-alerts) Toast Icon give additional visual information of the current Toast. |
| 2 | Toast Container | Displayed by stroke around a toast content. Containers improve the discoverability of the alert by creating a contrast with the surrounding content. Access to the rest of the UI is enabled, automatically disappear without any required user action. |
| 3 | Toast Body | Displays a description of the toast. Should be short and concise, enough informative for the user. |
| 4 | Action Link | Action link allowing the user to perform an action (_Learn more, Log out, etc._) |
| 5 | Dismiss Icon | [Close Icon](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/iconography?id=content) will dismiss the alert. |


### Behavior

Toasts are non-modal, time-based window elements used to display short messages; they usually appear at the top of the screen and disappear after a few seconds.

__Dismissal__

Toasts dismiss automatically after five seconds on the screen. They can also include a close button so users can dismiss them sooner. Toasts cover content on the screen so they should always be easily dismissed.

#### Focus state

<img src="https://user-images.githubusercontent.com/10553294/81705311-94ff4d80-9477-11ea-880c-ae5ea602b434.png" width="100%" alt="Toast" />



> On focus, the toast or the dismiss icon is outlined with a `3px` border. The border color is `#566FE6`. 

#### Hover state
<img src="https://user-images.githubusercontent.com/10553294/81705321-992b6b00-9477-11ea-8b07-eedc99d67ffd.png" width="100%" alt="Toast" />


> On hover state, the alert container or the dismiss icon background changes color to 30% of #C8C9C7. 

#### Toast Variations & Roles 

Currently, we have four main variations of toasts I.e. default, info, warning and error. By the content we define the role of the toast and chose the proper variation.

<img src="https://user-images.githubusercontent.com/10553294/81705355-a183a600-9477-11ea-9191-906b8a5d4e12.png" width="100%" />

| # | Variation | Description |
| - | --------- | ----------- |
| 1 | Default | [Info Icon](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/iconography?id=add-delete-and-alerts) Icons & Body color is `#FFFFFF`. The alert container color is `80%` of `#4A4F54` |
| 2 | Info | [Info Icon](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/iconography?id=add-delete-and-alerts) Icons & Body color is `#FFFFFF`. The alert container color is `80%` of `#006580` |
| 3 | Warning | [Warning Icon](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/iconography?id=add-delete-and-alerts) Icons & Body color is `#000000`. The alert container color is `80%` of `#FF9E18` |
| 4 | Error | [Error Icon](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/iconography?id=add-delete-and-alerts) Icons & Body color is `#FFFFFF`. The alert container color is `80%` of `#D22630` |

### Specifications

<img src="https://user-images.githubusercontent.com/10553294/81705385-a9434a80-9477-11ea-85b3-8081195d3205.png" width="100%" alt="Toast" />

| Element | Attribute | Value |
| ------- | --------- | ----- |
| Toast Icon | <ul><li>Size</li><li>Color</li><li>Top/Bottom/Left Padding</li></ul> | <ul><li>Check Iconography</li><li>`#333333`</li><li>`1.5em`</li></ul> |
| Toast Body | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li><li>Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`1em`</li><li>`#333333`</li><li>Sentence-case</li><li>`1.5em`</li></ul> |
| Dismiss Icon | <ul><li>Size</li><li>Color</li><li>Top/Bottom Padding</li><li>Left Padding</li></ul> | <ul><li>Check Iconography</li><li>#333333</li><li>`1.5em`</li><li>`2em`</li></ul> |

!> Check Iconography https://amplify.git-pages.ecd.axway.org/design-system-2020/#/iconography?id=add-delete-and-alerts The colors depends on the roles. Check Alert Variations & Roles section. 

#### Multiple Toasts

<img src="https://user-images.githubusercontent.com/10553294/81705405-aea09500-9477-11ea-8ad2-6558807305a5.png" width="100%" alt="Toast" />

| Element | Attribute | Value |
| ------- | --------- | ----- |
| Toast | <ul><li>Padding</li></ul> | <ul><li>`1.5em`</li></ul> |

### Responsive Grid

#### 1140

<img src="https://user-images.githubusercontent.com/10553294/81705434-b3fddf80-9477-11ea-9019-572179a6195e.png" width="100%" alt="Toast" />

#### 1024

<img src="https://user-images.githubusercontent.com/10553294/81705453-b8c29380-9477-11ea-9020-9ca82ddfd88e.png" width="100%" alt="Toast" />

#### 839
<img src="https://user-images.githubusercontent.com/10553294/81705471-bd874780-9477-11ea-850f-99c0a0339c73.png" width="100%" alt="Toast" />