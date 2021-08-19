<html lang="en">
    
## Welcome to the Sexual Harassment Application


<!-- Use the [editor on GitHub](https://github.com/spirradical/Sexual-Harassment-App-Demo/edit/gh-pages/index.md) to maintain and preview the content for this website in Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/spirradical/Sexual-Harassment-App-Demo/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

-->


<head>



Please fill out the following information:
    


<div class="quiz">

<h2 class="quiz-question">1. Are you an employer?</h2>
<ul data-quiz-question="1">
    <li class="quiz-answer" data-quiz-answer="a">Yes</li>
    <li class="quiz-answer" data-quiz-answer="b">No, I am an employee</li>
    <li class="quiz-answer" data-quiz-answer="c">No, I am a contractor</li>
    <li class="quiz-answer" data-quiz-answer="d">No, I am an interested person</li>
</ul>
     
<h2 class="quiz-question">2. How did you become aware of the alleged sexual harassment? (tick where applicable)</h2>
<ul data-quiz-question="2">
    <li class="quiz-answer" data-quiz-answer="a">Notification of claim by the Human Rights Commission (Cth)</li>
    <li class="quiz-answer" data-quiz-answer="b">Notification of a claim by the state body</li>
    <li class="quiz-answer" data-quiz-answer="c">Workers compensation claim received</li>
    <li class="quiz-answer" data-quiz-answer="d">Written complaint received from victim or bystander</li>
    <li class="quiz-answer" data-quiz-answer="e">Verbal complaint received from victim, bystander or affected person</li>
    <li class="quiz-answer" data-quiz-answer="f">You witnessed or were told of the behaviour</li>
    <li class="quiz-answer" data-quiz-answer="a">Evidence such as an email, CCTV etc.</li>
</ul>
    
<h2 class="quiz-question">3. Where did the potential sexual harassment take place?</h2>
<ul data-quiz-question="3">
    <li class="quiz-answer" data-quiz-answer="a">New South Wales</li>
    <li class="quiz-answer" data-quiz-answer="b">Queensland</li>
    <li class="quiz-answer" data-quiz-answer="c">Victoria</li>
    <li class="quiz-answer" data-quiz-answer="d">Australian Capital territory</li>
    <li class="quiz-answer" data-quiz-answer="e">South Australia</li>
    <li class="quiz-answer" data-quiz-answer="f">Western Australia</li>
    <li class="quiz-answer" data-quiz-answer="g">Northern Territory</li>
    <li class="quiz-answer" data-quiz-answer="h">Tasmania</li>
</ul>
    
<h2 class="quiz-question">4. Have you conducted a workplace investigation?</h2>
<ul data-quiz-question="4">
    <li class="quiz-answer" data-quiz-answer="a">Yes - allegations substantiated</li>
    <li class="quiz-answer" data-quiz-answer="b">Yes - allegations not substantiated</li>
    <li class="quiz-answer" data-quiz-answer="c">Yes - yet to be completed</li>
    <li class="quiz-answer" data-quiz-answer="d">No</li>
</ul>
    
<h2 class="quiz-question">5. Do you have any of the following policies or procedures? (tick where applicable)</h2>
<ul data-quiz-question="5">
    <li class="quiz-answer" data-quiz-answer="a">Work health and safety policy</li>
    <li class="quiz-answer" data-quiz-answer="b">Sexual harassment policy</li>
    <li class="quiz-answer" data-quiz-answer="c">Code of conduct</li>
    <li class="quiz-answer" data-quiz-answer="d">Disciplinary policy</li>
    <li class="quiz-answer" data-quiz-answer="e">Complaints or grievance handling</li>
</ul>
    
<h2 class="quiz-question">6. Does your organisation provide sexual harassment training?</h2>
<ul data-quiz-question="6">
    <li class="quiz-answer" data-quiz-answer="a">Yes - only at induction</li>
    <li class="quiz-answer" data-quiz-answer="b">Yes - at least annually</li>
    <li class="quiz-answer" data-quiz-answer="c">Yes - less than annually</li>
    <li class="quiz-answer" data-quiz-answer="d">Yes - I don't recall when the last training was held</li>
    <li class="quiz-answer" data-quiz-answer="e">No</li>
    <li class="quiz-answer" data-quiz-answer="f">Not sure</li>
</ul>
    
</div>
    
<h2 class="quiz-question">7. Contact details provided?</h2>
<ul data-quiz-question="7">
    <li class="quiz-answer" data-quiz-answer="a">Yes</li>
    <li class="quiz-answer" data-quiz-answer="b">No</li>
</ul>
    
<div class="quiz-result"></div>

    
</head> 

<body>
    <style>
        
        body {
  margin:0;
  padding:20px;
}
.quiz {
  padding:0 30px 20px 30px;
  max-width:960px;
  margin:0 auto;
  
  ul {
    list-style:none;
    padding:0;
    margin:0;
  }
}
.quiz-question {
  font-weight:bold;
  display:block;
  padding:30px 0 10px 0;
  margin:0;
}
.quiz-answer {
  margin:0;
  padding:10px;
  background:#f7f7f7;
  margin-bottom:5px;
  cursor: pointer;
  
  &:hover {
    background:#eee;
  }
  
  &:before {
    content:"";
    display:inline-block;
    width:15px;
    height:15px;
    border:1px solid #ccc;
    background:#fff;
    vertical-align:middle;
    margin-right:10px;
  }
  
  &.active {
    &:before {
      background-color:#333;
      border-color:#333;
    }
  }
  &.correct {
    &:before {
      background-color:green;
      border-color:green;
    }
  }
  &.incorrect {
    &:before {
      background-color:red;
      border-color:red;
    }
  }
  &.active.correct {
    &:before {
      outline: 2px solid green;
      outline-offset: 2px;
    }
  }
}
.quiz-result {
  max-width:960px;
  margin:0 auto;
  font-weight:bold;
  text-align:center;
  color: #fff;
  padding:20px;
  
  &.good {
    background: green;
  }
  &.mid {
    background: orange;
  }
  &.bad {
    background: red;
  }
}        
    </style>
   
    
    <script
    
    

       

    
    </script>
    
    
</body>


   
