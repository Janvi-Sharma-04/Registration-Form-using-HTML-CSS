# Registration Form

This is a simple and responsive registration form created using HTML and CSS. The form can be used for user registration on websites, applications, or other platforms.

## Features

- **Clean Design:** Simple and user-friendly interface.
- **Responsive Layout:** Adjusts to different screen sizes, making it mobile-friendly.
- **Customizable:** Easy to modify and adapt to your needs.

## Preview

![image](https://github.com/user-attachments/assets/5c6877aa-e7bf-45a0-95eb-1aedee090aeb)


## How to Use

1. Clone or download the repository.
   ```bash
   git clone https://github.com/Janvi-Sharma-04/Registration-form-using-HTML-CSS.git
   ```

2. Open the `index.html` file in any modern web browser.

3. Modify the HTML and CSS files to customize the form as per your requirements.

## Files Included

- **index.html**: Contains the structure of the registration form.
- **style.css**: Includes all the styling rules for the form.

## Code Highlights

### HTML Example
```html
<form action="#">
            <h2>Registration form</h2>
            <table>
                <tr>
                    <td>First Name</td>
                    <td><input type="text" placeholder="Enter First Name"></td>
                </tr>
                <tr>
                    <td>Last Name</td>
                    <td><input type="text" placeholder="Enter Last Name"></td>
                </tr>
                <tr>
                    <td>Username</td>
                    <td><input type="text" placeholder="Enter Username"></td>
                </tr>
                <tr>
                    <td>Email</td>
                    <td><input type="email" placeholder="Enter Email"></td>
                </tr>
                <tr>
                    <td>Password</td>
                    <td><input type="password" placeholder="Enter Password"></td>
                </tr>
                <tr>
                    <td>Gender</td>
                    <td>
                        <input type="radio" name="gender" value="male"> Male
                        <input type="radio" name="gender" value="female"> Female
                    </td>
                </tr>
                <tr>
                    <td>Hobby</td>
                    <td>
                        <input type="checkbox" name="hobby" value="reading"> Reading
                        <input type="checkbox" name="hobby" value="writing"> Writing
                        <input type="checkbox" name="hobby" value="singing"> Singing
                    </td>
                </tr>
                <tr>
                    <td>City</td>
                    <td><input type="text" placeholder="Enter City"></td>
                </tr>
                <tr>
                    <td>Country</td>
                    <td><input type="text" placeholder="Enter Country"></td>
                </tr>
                <tr>
                    <td>Select Car</td>
                    <td>
                        <select>
                            <option value="select car">Select Car</option>
                            <option value="audi">audi</option>
                            <option value="swift">Swift</option>
                            <option value="volvo">volvo</option>
                        </select>
                    </td>
                </tr>
                <tr>
                    <td>Comment</td>
                    <td><textarea rows="3" placeholder="The cat was playing in the garden."></textarea></td>
                </tr>
                <tr>
                    <td colspan="2" class="buttons">
                        <button type="submit">Save</button>
                        <button type="reset">Reset</button>
                    </td>
                </tr>
            </table>
        </form>
```

### CSS Example
```css
.form {
    width: 400px;
    margin: 50px auto;
    padding: 20px;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
}

table {
    width: 100%;
    border-collapse: separate;
    border-spacing: 0 10px;
}

td {
    padding: 10px;
    font-size: 14px;
}

input[type="text"], input[type="email"], input[type="password"], textarea, select {
    width: 100%;
    padding: 10px;
    border-radius: 20px;
    border: 1px solid #ccc;
    font-size: 14px;
    outline: none;
    transition: border-color 0.3s ease;
}

input[type="text"]:focus, input[type="email"]:focus, input[type="password"]:focus, textarea:focus, select:focus {
    border-color: #007bff;
}

textarea {
    resize: none;
}

.buttons {
    text-align: center;
}

button {
    padding: 10px 20px;
    margin: 0 5px;
    border-radius: 20px;
    border: none;
    background-color: #ddc136;
    color: white;
    font-size: 14px;
    cursor: pointer;
}

button[type="reset"] {
    background-color: #40a8ce;
}

button:hover {
    opacity: 0.8;
}
```
Thank you for visiting! 😊
