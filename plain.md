---
layout: default
---
<div class="home">
    <h1>USW Capability Model</h1>


{% for member in site.data.capTeach %}
<h2>{{ member.Name }}</h2>

   <p>{{ member.Documentation }}</p> 

    {% for item in member.levelTwo %}
    <h3>{{ item.Name }}</h3> 
    
        <p>{{ item.Documentation }}</p> 

        {% for itemtwo in item.levelThree %}
        <h4>{{ itemtwo.Name }}</h4> 
        

        <p>{{ itemtwo.Documentation }}</p>

        {% endfor %}
    {% endfor %}




{% endfor %}

{% for member in site.data.capResearch %}
<h2>{{ member.Name }}</h2>

   <p>{{ member.Documentation }}</p> 

    {% for item in member.levelTwo %}
    <h3>{{ item.Name }}</h3> 
    
        <p>{{ item.Documentation }}</p> 

        {% for itemtwo in item.levelThree %}
        <h4>{{ itemtwo.Name }}</h4> 
        
       <p>{{ itemtwo.Documentation }}</p>
        {% endfor %}
    {% endfor %}




{% endfor %}

{% for member in site.data.capCommercial %}
<h2>{{ member.Name }}</h2>

   <p>{{ member.Documentation }}</p> 

    {% for item in member.levelTwo %}
    <h3>{{ item.Name }}</h3> 
    
        <p>{{ item.Documentation }}</p> 

        {% for itemtwo in item.levelThree %}
        <h4>{{ itemtwo.Name }}</h4> 
        
       <p>{{ itemtwo.Documentation }}</p>
        {% endfor %}
    {% endfor %}



{% endfor %}
{% for member in site.data.capEnabling %}
<h2>{{ member.Name }}</h2>

   <p>{{ member.Documentation }}</p> 

    {% for item in member.levelTwo %}
    <h3>{{ item.Name }}</h3> 
    
        <p>{{ item.Documentation }}</p> 

        {% for itemtwo in item.levelThree %}
        <h4>{{ itemtwo.Name }}</h4> 
        
       <p>{{ itemtwo.Documentation }}</p>
        {% endfor %}
    {% endfor %}



{% endfor %}
{% for member in site.data.capStrategy %}
<h2>{{ member.Name }}</h2>

   <p>{{ member.Documentation }}</p> 

    {% for item in member.levelTwo %}
    <h3>{{ item.Name }}</h3> 
    
        <p>{{ item.Documentation }}</p> 

        {% for itemtwo in item.levelThree %}
        <h4>{{ itemtwo.Name }}</h4> 
        
       <p>{{ itemtwo.Documentation }}</p>
        {% endfor %}
    {% endfor %}




{% endfor %}

</div>
