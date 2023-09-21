> Dialogs inform users about a task and can contain critical information, require decisions, or involve multiple tasks. Modal are used to display content in a layer above the app.

## Usage

A dialog is a type of modal window that appears in front of app content to provide critical information or ask for a decision. Dialogs disable all app functionality when they appear, and remain on screen until confirmed, dismissed, or a required action has been taken. This paradigm is used in cases such as the creation or editing of a record, as well as various types of messaging and wizards.

### Good Principles

* __Focused__ – should grab the user’s attention. Use when you want to interrupt a user’s current task to catch the user’s full attention to something more important.
* __Direct__ - should be dedicated to completing a task.
* __Helpful__ - should appear in response to a user task or an action. Use when you want to show additional information without losing the context of the parent page.

The Modal Dialogs should be used for critical information that requires a specific user task or decision I.e. Errors, Yes/No questions, etc. If the necessary action is more complex, require adding information, filling a form, etc. It’s better to go with an independent page or Full-size screen Dialog.

### What NOT to use Dialogs for

Please do __NOT__ use Modal Dialogs for none of the following use cases:
1. __The Number of Elements and Option__ - Dialogs should never appear partially on screen. You shouldn't use a dialog which contains scrolling content. Once you have a more complex case than Agree/Disagree statement, please use a single page instead.
2. __The Number of Action__ - Dialogs should not include more than two actions. A third action, such as “Learn more,” navigates away from the dialog, potentially leaving the task unfinished. Use full-size expandable dialog instead.
3. __Do NOT Include Multiple Steps in Dialog__ - Breaking a complex task into multiple steps is a great idea, but it’s also generally a sign that something is too complex to ask users to complete within the confines of a dialog.

## Anatomy

<img src="https://user-images.githubusercontent.com/10553294/80494267-272f2e00-896f-11ea-9ec0-41f7f36d1fed.png" width="100%" alt="Modal Dialog" />

| # | Component Name | Guidelines |
| ------- | --------- | ----- |
| 1 | Title | Displays the Modal Title. Should be brief and descriptive. |
| 2 | Modal Container | Displayed by stroke around a modal content. Containers improve the discoverability of the modals by creating a contrast with the surrounding content. Access to the rest of the UI is disabled until the modal is addressed. |
| 3 | Description of Modal (Body) | Displays a description of the modal. There should be a character count limit for this text area. The height depends on the text length. |
| 4 | Secondary Button | Typically provide the actions of “Cancel” or “Close” as options. Reference see the Buttons. |
| 5 | Primary Button | Displays the CTA that are applicable to the card items.  Examples agree, edit, delete, share, like, etc. Typically provide the actions of “Agree” as options. |

> side-by-side buttons display buttons provide the actions of “Disagree” and “Agree” as options. 

### Modal Dialog with Subtitle

<img src="https://user-images.githubusercontent.com/10553294/80494282-2bf3e200-896f-11ea-8cbf-cc1d258d5b9f.png" width="100%" alt="Modal Dialog" />

| # | Component Name | Guidelines |
| ------- | --------- | ----- |
| 6 | Subtitle | Displays the Modal Subtitle. Should provide additional important details, again be brief and descriptive. |

## Behavior

> Dialogs appear without warning, requiring users to stop their current task. They should be used sparingly, as not every choice or setting warrants interruption.

Modals retain focus until dismissed or action has been taken, such as made a choice. They shouldn’t be obscured by other elements or appear partially on screen, apart from full-screen dialogs. Access to the rest of the UI is disabled until the modal is addressed.

### Focus State

<img src="https://user-images.githubusercontent.com/10553294/80494315-34e4b380-896f-11ea-9e26-23b22a4c9fac.png" width="100%" alt="Modal Dialog" />

> On focus, a modal is outlined with a 3px border. The border color is #566FE6. 

### Hover State

<img src="https://user-images.githubusercontent.com/10553294/80494323-3910d100-896f-11ea-8171-556407382677.png" width="100%" alt="Modal Dialog" />

> On hover state, the modal container changes color (the final color is still TBD). For testing the bg color is #E9EAEA. 

### Active State
<img src="https://user-images.githubusercontent.com/10553294/80494331-3d3cee80-896f-11ea-9e6a-ecf57469b91b.png"  width="100%" alt="Modal Dialog" />

> If an item is currently selected, the modal container changes colors (final colors are still TBD).  For testing the icons and text are #FFFFFF and the bg color is #407CA0. 

## Specification

<img src="https://user-images.githubusercontent.com/10553294/80494374-4928b080-896f-11ea-9788-33e147a303df.png" width="100%" alt="Modal Dialog" />

<!-- <ul><li></li></ul> -->
| Element | Attribute | Value |
| ------- | --------- | ----- |
| Modal Title | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Case</li><li>Color</li><li>Top Padding</li><li>Left Padding</li><li>Bottom Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`2em`</li><li>Sentence case</li><li>`#000000`</li><li>`2.5em`</li><li>`2em`</li><li>`1.5em`</li></ul> |
| Modal Description (Body) | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Case</li><li>Color</li><li>Top Padding</li><li>Left/Right Padding</li><li>Bottom Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`1em`</li><li>Sentence case</li><li>`#333333`</li><li>`1.5em`</li><li>`2em`</li><li>`1em`</li></ul> |
| Primary/Secondary Button Pair Reference Buttons | <ul><li>Top Padding</li><li>Right Padding</li><li>Bottom Padding</li><li>Padding btw the Buttons</li></ul> | <ul><li>`1em`</li><li>`2em`</li><li>`2.5em`</li><li>`1.5em`</li></ul> |

### Modal Dialog with Subtitle

<img src="https://user-images.githubusercontent.com/10553294/80494405-4e85fb00-896f-11ea-8258-ca2458f041df.png" width="100%" alt="Modal Dialog" />

| Element | Attribute | Value |
| ------- | --------- | ----- |
| Modal Title | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Case</li><li>Color</li><li>Top Padding</li><li>Left Padding</li><li>Bottom Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`2em`</li><li>Sentence case</li><li>`#000000`</li><li>`2.5em`</li><li>`2em`</li><li>`1.25em`</li></ul> |
| Modal SubTitle | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Case</li><li>Color</li><li>Top Padding</li><li>Left Padding</li><li>Bottom Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`1em`</li><li>Sentence case</li><li>`#000000`</li><li>`1.25em`</li><li>`2em`</li><li>`1.5em`</li></ul> |
| Modal Description (Body) | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Case</li><li>Color</li><li>Top Padding</li><li>Left/Right Padding</li><li>Bottom Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`1em`</li><li>Sentence case</li><li>`#333333`</li><li>`1.5em`</li><li>`2em`</li><li>`1em`</li></ul> |
| Primary/Secondary Button Pair Reference Buttons | <ul><li>Top Padding</li><li>Right Padding</li><li>Bottom Padding</li><li>Padding btw the Buttons</li></ul> | <ul><li>`1em`</li><li>`2em`</li><li>`2.5em`</li><li>`1.5em`</li></ul> |

## Responsive Grid

### 1400+

<img src="https://user-images.githubusercontent.com/10553294/80494445-547bdc00-896f-11ea-8de1-9f5ce0474e0a.png" width="100%" alt="Modal Dialog" />

### 1024+

<img src="https://user-images.githubusercontent.com/10553294/80494460-58a7f980-896f-11ea-8f31-6725d7a1066d.png" width="100%" alt="Modal Dialog" />

### 839+
<img src="https://user-images.githubusercontent.com/10553294/80494481-5cd41700-896f-11ea-889a-c952768dd85d.png" width="100%" alt="Modal Dialog" />