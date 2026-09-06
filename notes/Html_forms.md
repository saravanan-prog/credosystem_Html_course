# HTML Forms

 An HTML form is used to `collect user input` and `send it to a server for processing`.

### 1️⃣ Basic Structure of a Form
 ```       
<form method="POST">
    <div>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" />
    </div>
    <div>
        <button type="submit">Submit</button>
    </div>
</form>
```
    
## Common Input Types

    
    -    📝 Text Input   - <input type="text" name="username" />
    -    🔐 Password     - <input type="password" name="password" />
    -    📧 Email        - <input type="email" name="email" />
    -    🔢 Number       - <input type="number" name="age" />
    -    📅 Date         - <input type="date" name="dob" />
    -    ☑️ Checkbox     - <input type="checkbox" name="subscribe" />
    -    🔘 Radio Button - <input type="radio" name="gender" value="male" /> 
    -    📤 File Upload  - <input type="file" name="file" />
    -     submit          - <input type="submit"  />
    -     button          - <input type="button" value="cancel" />
    

               
    

#   Other Form Elements
    
        📦 Textarea        - <textarea name="message"></textarea>
        
        📋 Select Dropdown - <select name="country">
                                <option value="india">India</option>
                                <option value="usa">USA</option>
                            </select>
        

#    Form Validation
    
-  👉 HTML Built-in Validation
-   Attributes :
```
    🔹 required
    🔹 minlength
    🔹 maxlength
    🔹 pattern
    🔹 min
    🔹 max
```
       
## Example: Complete Form
    
        <form action="/register" method="POST">

            <label>Name:</label>
            <input type="text" name="name" required />

            <label>Email:</label>
            <input type="email" name="email" required />

            <label>Password:</label>
            <input type="password" name="password" required minlength="6" />

            <button type="submit">Register</button>
        </form>