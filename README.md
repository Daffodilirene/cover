# Ex.05 Book Cover Page Design
## Date:14.12.2025

## AIM:
To design a book back cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
cover.html

<html>
    <head>
        <title>Cover Page</title>
        <link href="styles.css" rel="stylesheet"> 
    </head>
    <body>
        <div class="container">
            <h2> About the Book</h2>
            <font color="white"><p>
            This book<span class="highlight">&quot;Cyberion: Foundations of Cyber Security&quot;</span>introduces readers to the essentials of digital safety and protection. It clearly explains how computers, networks, and data systems work behind the scenes, helping first-year B.E. Cyber Security students understand the basics with ease.
            The book covers important topics like networking fundamentals, operating systems, cyber attacks, ethical hacking basics, threat analysis, and digital forensics. It also emphasizes online safety and the growing need for cyber professionals.
            Cyberion is the perfect starting guide for beginners—simple, practical, and designed to build a strong foundation for future cybersecurity learning.
            </p></font>
            <div class="quote">
                &quot;To protect the digital world, curiosity is the first step&quot;
            </div>
            <div class="author">
            
                <img  src="myphoto.jpeg",width="50", height="50">
                
                    <b> Daffodil Irene.S</b><br>
                    student of B.E Cyber Security<br>
                    Daffodil Irene is a first-year B.E. Cyber Security student with a strong interest in digital protection.Her writing reflects her curiosity, clarity, and dedication to learning.Cyberion is her introduction to the world of cybersecurity education.
                
            </div>
            <div class="footer">
                <b>Daffodil Irene.S (25002685)</b>
                <b>Price: &#8377; 450</b></div>
            </div>
        </div>    
    </body>
</html>



styles.css


body
{
    background:rgba(134, 9, 134, 0.795)
}
.container
{
    width:515px;
    height:600px;
    image-orientation:flip;
    background-image:url('violet.jpg');
    background-size:cover;
    background-position:center;
    padding:10px;
    margin-left:500px;
    border-width:10px;
    border-spacing:5px;
    border-style:solid;
    border-color:rgb(250, 242, 250);
    ;
    
    
}
h2
{
    color:whitesmoke;
    border-bottom: 5px solid rgb(239, 223, 244);
    padding-bottom:10px;
    
}
.highlight {
   background-color: #e74efb; 
   color: #ffffff; 
   display: inline-block;
}
.quote
{
    background:#cd43fb;
    padding:12px;
    margin:15px 0;
    border-left:5px solid #7b1195;

}
.author
{
    background: purple;
    padding:12px;
    gap:15px;
    align-items: center;
    border:10px solid #ccc;


}
.footer
{
    background: #a022d6;
    color:white;
    padding:10px;
    margin-top:flex;
    display:flex;
    justify-content: center;
}










```


## OUTPUT:
![alt text](<Screenshot (34).png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
