# Callbox_Macro

Edit Callbox Data will take the export from Haul It and modify the data to be imported into the callbox.

  1. There is a stop in the macro so that it can not be ran on the file if it was already done.
  2. It identifies important columns such as the date, driver ID, and the clock in time.
  3. Sorts by clock in time and removes any duplicate entries for the driver so that only their first load is shown.
  4. Splits the name column into first and last name columns.
  5. Makes a messsage column that concatinates the day, clock in time, load information, and location.
  6. Search and replace some abbrivations and product names so that the callbox reads them correctly.
  7. Saves the file on the users desktop with the current date.

Default Message will change the message to notify drivers that the information isn't updated yet and to try again later.

  1. Edits the message column.
  2. Saves the file with the current date and "Default Message" so that it is eaisly identified
