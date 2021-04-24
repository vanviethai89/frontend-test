# Frontend test

## Explanation
* The TodoApp was re-structured to three parts:
  * **Storage**: works with LocalStorage, which helps to store data.
  * **Notification**: helps to show notification.
  * **TodoApp**: works with UI, event.
* The `"Add"` button has been removed, instead the user press `"Enter"` to finish.
* All `alert()` have been replaced to `HTML POPUP NOTIFICATION` for better user experience.
* The data is saved directly to `localStorage`, so when after page refresh or browser restart, the data is still there. 
