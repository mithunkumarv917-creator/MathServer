
## Date:16/10/2025

## AIM:
 To design a website to calculate the power of a lamp filament in an incandescent bulb in the server side. 


## FORMULA:
P = I<sup>2</sup>R
<br> P --> Power (in watts)
<br> I --> Intensity
<br> R --> Resistance

## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Create python programs for views and urls to perform server side processing.

### Step 5:
Create a HTML file to implement form based input and output.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<!DOCTYPE html>
<html>
<head>
<meta charset='utf-8'>
<meta http-equiv='X-UA-Compatible' content='IE=edge'>
<title>Area of Surface</title>
<meta name='viewport' content='width=device-width, initial-scale=1'>
<style type="text/css">
body {
    background: linear-gradient(to bottom right, #a8edea, #fed6e3); /* soft gradient */
    font-family: 'Georgia', serif;
}
.edge {
    width: 100%;
    padding-top: 250px;
    text-align: center;
}
.box {
    display: inline-block;
    border: 4px dashed #e0e0e0;
    width: 500px;
    min-height: 300px;
    font-size: 20px;
    background-color: #142850; /* navy blue */
    border-radius: 15px;
    box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
}
.formelt {
    color: #f1f1f1;
    text-align: center;
    margin-top: 7px;
    margin-bottom: 6px;
}
h1 {
    color: #ffcb05; /* gold */
    padding-top: 20px;
}
input[type="text"] {
    padding: 5px;
    border-radius: 5px;
    border: 1px solid #ccc;
}
input[type="submit"] {
    background-color: #ffcb05;
    border: none;
    border-radius: 5px;
    padding: 5px 10px;
    cursor: pointer;
    font-weight: bold;
}
input[type="submit"]:hover {
    background-color: #ffd84d;
}
</style>
</head>
<body>
<div class="edge">
    <div class="box">
        <h1>Surface area of a Right Cylinder</h1>
        <form method="POST">
            {% csrf_token %}
            <div class="formelt">
                Radius: <input type="text" name="radius" value="{{r}}"> m<br/>
            </div>
            <div class="formelt">
                Height: <input type="text" name="height" value="{{h}}"> m<br/>
            </div>
            <div class="formelt">
                <input type="submit" value="Calculate"><br/>
            </div>
            <div class="formelt">
                Area: <input type="text" name="area" value="{{area}}"> m<sup>2</sup><br/>
            </div>
        </form>
    </div>
</div>
</body>
</html>


```


## SERVER SIDE PROCESSING:
<img width="1508" height="935" alt="Screenshot 2025-10-13 102956" src="https://github.com/user-attachments/assets/9190ec77-6256-48f3-ae3b-1143844e4905" />


## HOMEPAGE:
<img width="1536" height="1024" alt="2f6ecf6f-6ab4-4c3e-afca-77d9730b9354" src="https://github.com/user-attachments/assets/22e1d1eb-7bab-4678-aa95-a521e37393d7" />
## RESULT:
The program for performing server side processing is completed successfully.
