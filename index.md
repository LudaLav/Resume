<html lang="en">
<head>
<meta charset="UTF-8">
<title>Ludmila Lavochkina</title>
<style>
body {
    color: #000000;
    background: #EEEEEE;
    font: 1.1em "Times New Roman";
    line-height: 1.2;
    margin: 40px 0;
}
#resume {
    margin: 0 auto;
    max-width: 800px;
    padding: 40px 60px;
    background: #FFFFFF;
    border: 1px solid #CCCCCC;
    box-shadow: 2px 2px 4px #AAAAAA;
    -webkit-box-shadow: 2px 2px 4px #AAAAAA;
}
h1 {
    text-transform: uppercase;
    text-align: center;
    font-size: 200%;
    margin: 0;
    padding: 0;
}
h2 {
    border-bottom: 1px solid #000000;
    text-transform: uppercase;
    font-size: 130%;
    margin: 1em 0 0 0;
    padding: 0;
}
h3 {
    font-size: 100%;
    margin: 0.8em 0 0.3em 0;
    padding: 0;
    display: flex;
    justify-content: space-between;
}
p {
    margin: 0 0 0.5em 0;
    padding: 0;
    }
ul {
    padding: 0;
    margin: 0 1.5em;
    }
/* ul immediately after h1 = contact list */
h1 + ul {
    text-align: center;
    margin: 0;
    padding: 0;
    }
h1 + ul > li {
    display: inline;
    white-space: pre;
    list-style-type: none;
}
h1 + ul > li:after {
    content: "  \2022  ";
}
h1 + ul > li:last-child:after {
    content: "";
}
/* p immediately after contact list = summary */
h1 + ul + p {
    margin: 1em 0;
}
@media print {
    body {
        font-size: 10pt;
        margin: 0;
        padding: 0;
        background: none;
    }
    #resume {
        margin: 0;
        padding: 0;
        border: 0px;
        background: none;
        box-shadow: none;
        -webkit-box-shadow: none;
    }
    /* Make links black in PDF */
    /* Move this outside the print block to apply this in HTML too */
    a, a:link, a:visited, a:hover {
        color: #000000;
        text-decoration: underline;
    }
}
@page {
    /* Change margins and paper size of PDF */
    /* https://developer.mozilla.org/en-US/docs/Web/CSS/@page */
    size: letter;
    margin: 0.5in 0.8in;
}
@media screen and (max-width: 800px) {
    body {
        font-size: 16pt;
        margin: 0;
        padding: 0;
        background: #FFFFFF !important;
    }
    #resume {
        margin: 0;
        padding: 1em;
        border: 0px;
        background: none;
        box-shadow: none;
        -webkit-box-shadow: none;
    }
}

</style>
</head>
<body>
<div id="resume">
<!-- The (first) h1 will be used as the <title> of the HTML page -->
<h1>Ludmila Lavochkina</h1>
<!-- The unordered list immediately after the h1 will be formatted on a single
line. It is intended to be used for contact details -->
<ul>
<li><a>luri.exp@gmail.com</a></li>
<li>(972) 522-355-860</li>
<li>Haifa, Israel</li>
</ul>
<!-- The paragraph after the h1 and ul and before the first h2 is optional. It
is intended to be used for a short summary. -->
<p>QA Tester Full Stack Automation. </p>

<h2>Experience</h2>
<!-- You have to wrap the "left" and "right" half of these headings in spans by
hand -->
<h3><span>Final project at graduation</span> <span> 2022 &ndash;  2023</span></h3>
<p>TestNG, Selenium, Jenkins, TestNG, Appium.
</p>
<ul>
<li>Tests in WEB environment using WebDriver</li>
<li>Data entry, comparison and availability.</li>
<li>Tests in Android environment (Appium),With the help of AndroidDriver.</li>
<li>Tests:Electron Apps, Desktop Apps, Rest API, Angular Apps</li>
</ul>
<h3><span>Work in a factory for the production of industrial machinery</span> <span> 2003 &ndash;  2022</span></h3>
<p>Sketcher, Production Planning and Control (PP&C)</p>
<ul>
<li>Parts and assembly drawings, electrical drawings<p>
<li>PP&C: processing orders from the moment they are received.</li>
<li>Management and documentation of inventory and raw materials</li>
<h3><span>Kitchen and electrical goods store</span> <span> 2003 </span></h3>
<p>Building a website and customer database for a kitchen and electrical goods store</p>

<h2>Projects</h2>
<h3><span>TestNG - Final Project</span> <span>2022</span></h3>
<h3><span>Information systems in an electronics factory - Final Project</span> <span>2001</span></h3>

<h2>Education</h2>
<h3><span>Atid College - QA Automation Full Stack</span> <span>2022 &ndash; 2023</span></h3>
<h3><span>Galil Maarvi College - Production Planning and Control (PP&C)</span> <span>1999 &ndash; 2021</span></h3>

<h2>Skills</h2>
<ul>
<li>Power Point, MS Project,SolidEdge, Cimatron, Visio.</li>
<li>Programming Language: Java, IDE-Intellij.</li>
<li>Data Formats:JSON, XML, HTML, XSD,CSS.</li>
<li>Platforms:Selenium, Jenkins, TestNG, Appium.</li>
<li>Protocols:TCP/IP.</li>
</ul></div>
</body>
</html>
