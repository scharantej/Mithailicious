## Flask Application Design: Sweet India

### HTML Files:

1. **index.html**:
   - This will be the homepage of the site, providing a brief introduction to Indian sweets and their significance in Indian culture.
   - It should have links to other pages that delve into specific categories of sweets.

2. **laddu.html**:
   - This page will provide detailed information about Laddu, one of the most popular Indian sweets.
   - It should include a description of different types of Laddu, recipes, and interesting facts about its origin and variations across regions.
   - May include images and videos of Laddu making and variations.

3. **jalebi.html**:
   - This page will showcase Jalebi, another cherished Indian sweet.
   - It should provide recipes, variations, and cultural significance of Jalebi.

4. **barfi.html**:
   - This page will be dedicated to Barfi, a delectable milk-based sweet.
   - It should include a variety of recipes, along with information on the history and preparation techniques of Barfi.

5. **gulabjamun.html**:
   - This page will focus on Gulab Jamun, a widely loved syrupy sweet.
   - It should provide recipes, preparation tips, and interesting facts about its origins and significance in Indian festivals and celebrations.

### Routes:

1. **@app.route('/')**:
   - This route will handle the homepage of the website.
   - It will render the "index.html" file, displaying the introductory content and links to specific sweet pages.

2. **@app.route('/laddu')**:
   - This route will handle requests for the Laddu page.
   - It will render the "laddu.html" file, providing detailed information about Laddu.

3. **@app.route('/jalebi')**:
   - This route will handle requests for the Jalebi page.
   - It will render the "jalebi.html" file, offering information and recipes related to Jalebi.

4. **@app.route('/barfi')**:
   - This route will handle requests for the Barfi page.
   - It will render the "barfi.html" file, providing recipes and information about Barfi.

5. **@app.route('/gulabjamun')**:
   - This route will handle requests for the Gulab Jamun page.
   - It will render the "gulabjamun.html" file, displaying recipes, preparation tips, and interesting facts about Gulab Jamun.

6. **@app.route('/about')**:
   - This route will handle requests for an "About" page.
   - It will render an "about.html" file, introducing the purpose of the website and the team behind it.

7. **@app.route('/contact')**:
   - This route will handle requests for a "Contact" page.
   - It will render a "contact.html" file, providing a form for users to send messages or inquiries related to the website or Indian sweets.