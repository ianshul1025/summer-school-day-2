1. CSS Types Used:

1.1 Inline CSS  
Inline CSS is used in the <body> tag to set the background color to light grey (#f0f0f0).

1.2 Internal CSS  
Internal CSS is written inside the <style> tag in the head section.  
It is used to style the .bio text, contact links using a[href], and hover effects.

1.3 External CSS  
Most of the design is handled in the external CSS file (style.css).  
This includes layout, card styling, image styling, text formatting, spacing, and shadow.

2. CSS Selectors Used:

2.1 Element Selector  
Used for body, h1, h2, and p to give general text styles and spacing.

2.2 ID Selector  
#card is used to style the main profile card box.  
#profile-pic is used to give size, shape, and border to the profile image.

2.3 Class Selector  
.bio is used for styling the short paragraph about me.  
.hobby is used for each individual hobby text line.  
.card (optional) can be used to apply border and shadow if needed.

2.4 Group Selector  
h1, h2 are grouped to apply the same color and margin.

2.5 Descendant Selector  
.contact p is used to style only the paragraphs inside the contact section.

2.6 Attribute Selector  
.contact a[href] is used to style all contact links and a hover color effect.
