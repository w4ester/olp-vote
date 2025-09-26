Quick HTML voting form that displays the items, allows voting, and sends the results via email. 

Here's the complete index.html:

## Key Features:
1. **Clean, Professional Design** - Modern gradient design with responsive layout that works on all devices
2. **Three Voting Items** - Each displays the document name, type (Recommendation/Action), and a link to view the document
3. **Voting Options** - Each item has Approve/Reject/Abstain radio buttons with visual feedback
4. **Email Integration** - Submit button creates a formatted email to both recipients (william.forrester@maryland.gov and stephanie.tuckfield1@maryland.gov)
5. **Validation** - Ensures all items are voted on before submission
6. **User-Friendly** - Visual feedback when selections are made, clear instructions, and confirmation after email opens

## How It Works:
1. Users review each document via the provided links
2. Select their vote for each item
3. Click Submit to generate an email with:
   - All voting choices clearly formatted
   - Timestamp of submission
   - Professional email structure

The form automatically opens the default email client with both recipients, subject line, and formatted vote results ready to send. After the email client opens, 
users get a confirmation prompt to optionally reset the form.

The design is fully self-contained in a single HTML file - just save it as `index.html` and open in any browser!
