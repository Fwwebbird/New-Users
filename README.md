# Barcode Guns - Latest Build Updates and Notes

## What Everything Does:

### Order:
- Opens email and immediately adds Jodi and Mike to the recipients.
- Attaches PDF to that email, and asks what is going to be ordered so you don't have to type it all out.

### Barcode Guns:
- Creates a text file that generates code for Accuterm to make a new Barcode user.

### Accuterm/CRM:
- Opens Rundeck and loads a text file that contains all the necessary information for Katie.

### Webb Email:
- Opens a textbox to enter the email groups the user will be in. **Note:** You don't need to enter allusers or their branch.
- Also opens the new mailbox and alias page in Postfix. 
- **Note:** Ensure you're logged into Postfix before running this or it will do nothing, forcing multiple login sessions.

### Elevate:
- Opens the Elevate tab.

Some people are requesting automation, but there are no plans for that (at this time 😉).

---

## Updates:

### 9/30/24:
- Made the "If ordering, save PDF first!!" label text red if there is no PDF saved within the last 10 minutes and green if there is.
