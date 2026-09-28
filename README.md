# Saleforce-Advanced-Fomula-Calculator-Sandbox
The Advanced Salesforce Formula Editor is a standalone sandbox environment designed for building, testing, and evaluating Salesforce formulas and validation rules directly in your browser. It operates as a single-page application requiring no backend infrastructure.
**✨ # FeaturesMock Org Schema:**

Create and manage custom objects and fields to simulate your Salesforce environment.   
**Comprehensive Field Types**: Support for various field types including Text, Number, Currency, Percent, Checkbox, Picklist, and read-only Formula fields.   
**Dual Editor Modes**: Dedicated tabs for building standard Formula Fields and Error Condition Validation Rules.   

**Live Evaluation & Syntax Checking:** Test your formulas against the mocked data you created and catch syntax errors instantly.

**Validation Rule Testing**: Set custom error messages and test whether your rule evaluates to TRUE (triggering the error) or FALSE (passing).   

**Built-in Function Catalog:** A searchable sidebar categorized into Math and Logical functions. It provides descriptions, syntax formats, and expected output examples for functions like ABS, IF, ISPICKVAL, ISBLANK, and more.   

**Quick Insert:** Click "Insert" on any function or field to instantly add it to your current cursor position in the editor.   

**Dark Mode:** Built-in theme toggle for comfortable viewing in both light and dark environments.

This project is built as a self-contained HTML file utilizing modern frontend libraries via CDN:React 18 & ReactDOM: For component-based UI rendering and state management.   Babel (Standalone): To compile JSX directly in the browser.   Tailwind CSS: For styling, responsive design, and dark mode configuration.   Phosphor Icons: For all UI iconography.   Google Fonts: Utilizing 'DM Sans' for clean typography.

**INSTALLATION "**

git clone https://github.com/<YOUR-GITHUB-USERNAME>/advanced-salesforce-formula-editor.git

**Running the Application**   
Locate the ADVANCED Salesforce Formula editor.html file.   Double-click the file to open it in any modern web browser (Chrome, Firefox, Edge, Safari).



**Test and Evaluate:**

Click Check Syntax to verify that your fields and functions are valid.   Click Evaluate Field or Test Rule to execute the formula against the dummy data you provided in the left panel. The result or validation error will appear in the panel below the editor.
