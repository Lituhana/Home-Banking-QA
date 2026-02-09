# 🐛 BUG-02: Application Freeze

**Severity:** - Critical  
**Priority:** - High  
**Status:** - Open 

## 📝 Description:

The application's UI freezes completely if the user cancels the **oldest** "Plazo Fijo" first. If the newest one is cancelled first, the system remains stable. This indicates a potential logic error in how the application manages the index or state of the list after the first element is removed.

## 🐾 Steps to Reproduce:

1. Log in and navigate to the "Plazos Fijos" section.
2. Ensure there are at least two active fixed terms.
3. Cancel the oldest one ($50,000 / 90 days) first.
4. Try to cancel the newest loan or interact with any other button.
5. Observation: The UI becomes unresponsive.

*Note: If the newest one ($30,000 / 60 days) is cancelled first, the bug does not trigger.*

---------------------------------------------------------------------------------------------------------------------

### ⏰📋 Expected Result:

The application should maintain state integrity and remain responsive regardless of the order in which items are removed from the list.

---------------------------------------------------------------------------------------------------------------------

### 🐞📋 Obtained Result:

Cancelling the first item in the list seems to break the page flow and causes it to freeze completely. After this action, no other buttons or links work, including the "Logout" button, and the user is forced to refresh the browser to continue using the site.

---------------------------------------------------------------------------------------------------------------------