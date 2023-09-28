---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---
<div class="home">
    <h1>USW Capability Model</h1>

    <p class="intro">A business capability defines <em>what</em> a business does at its core. This differs from <em>how</em> things are done, <em>where they are done</em>, or <em>by whom</em>.
    <a href="http://ucisa-uk-he-capability-model.coventry.ac.uk/capability-definition/">UCISA Definition</a>
    </p>

{% for member in site.data.capTeach %}
<h2><a class="toggle CapLevelOne" href="#{{ member.ID }}">{{ member.Name }}</a></h2>
<div class="toggle-content"  id="{{ member.ID }}">
   <p class="CapLevelOneDesc">{{ member.Documentation }}</p> 

    {% for item in member.levelTwo %}
    <h3><a class="toggle CapLevelTwo" href="#{{ item.ID }}">{{ item.Name }}</a></h3> 
    <div class="toggle-content"  id="{{ item.ID }}">
        <p class="CapLevelTwoDesc">{{ item.Documentation }}</p> 

        {% for itemtwo in item.levelThree %}
        <h4><a class="toggle CapLevelThree" href="#{{ itemtwo.ID }}">{{ itemtwo.Name }}</a></h4> 
        <div class="toggle-content"  id="{{ itemtwo.ID }}">

        <p class="CapLevelThreeDesc">{{ itemtwo.Documentation }}</p>
        </div>
        {% endfor %}
    </div>
    {% endfor %}


    </div>

{% endfor %}

{% for member in site.data.capResearch %}
<h2><a class="toggle CapLevelOne" href="#{{ member.ID }}">{{ member.Name }}</a></h2>
<div class="toggle-content"  id="{{ member.ID }}">
   <p class="CapLevelOneDesc">{{ member.Documentation }}</p> 

    {% for item in member.levelTwo %}
    <h3><a class="toggle CapLevelTwo" href="#{{ item.ID }}">{{ item.Name }}</a></h3> 
    <div class="toggle-content"  id="{{ item.ID }}">
        <p class="CapLevelTwoDesc">{{ item.Documentation }}</p> 

        {% for itemtwo in item.levelThree %}
        <h4><a class="toggle CapLevelThree" href="#{{ itemtwo.ID }}">{{ itemtwo.Name }}</a></h4> 
        <div class="toggle-content"  id="{{ itemtwo.ID }}">
       <p class="CapLevelThreeDesc">{{ itemtwo.Documentation }}</p>
        </div>
        {% endfor %}
    </div>
    {% endfor %}


    </div>

{% endfor %}

{% for member in site.data.capCommercial %}
<h2><a class="toggle CapLevelOne" href="#{{ member.ID }}">{{ member.Name }}</a></h2>
<div class="toggle-content"  id="{{ member.ID }}">
   <p class="CapLevelOneDesc">{{ member.Documentation }}</p> 

    {% for item in member.levelTwo %}
    <h3><a class="toggle CapLevelTwo" href="#{{ item.ID }}">{{ item.Name }}</a></h3> 
    <div class="toggle-content"  id="{{ item.ID }}">
        <p class="CapLevelTwoDesc">{{ item.Documentation }}</p> 

        {% for itemtwo in item.levelThree %}
        <h4><a class="toggle CapLevelThree" href="#{{ itemtwo.ID }}">{{ itemtwo.Name }}</a></h4> 
        <div class="toggle-content"  id="{{ itemtwo.ID }}">
       <p class="CapLevelThreeDesc">{{ itemtwo.Documentation }}</p>
        </div>
        {% endfor %}
    </div>
    {% endfor %}


    </div>

{% endfor %}
{% for member in site.data.capEnabling %}
<h2><a class="toggle CapLevelOne" href="#{{ member.ID }}">{{ member.Name }}</a></h2>
<div class="toggle-content"  id="{{ member.ID }}">
   <p class="CapLevelOneDesc">{{ member.Documentation }}</p> 

    {% for item in member.levelTwo %}
    <h3><a class="toggle CapLevelTwo" href="#{{ item.ID }}">{{ item.Name }}</a></h3> 
    <div class="toggle-content"  id="{{ item.ID }}">
        <p class="CapLevelTwoDesc">{{ item.Documentation }}</p> 

        {% for itemtwo in item.levelThree %}
        <h4><a class="toggle CapLevelThree" href="#{{ itemtwo.ID }}">{{ itemtwo.Name }}</a></h4> 
        <div class="toggle-content"  id="{{ itemtwo.ID }}">
       <p class="CapLevelThreeDesc">{{ itemtwo.Documentation }}</p>
        </div>
        {% endfor %}
    </div>
    {% endfor %}


    </div>

{% endfor %}
{% for member in site.data.capStrategy %}
<h2><a class="toggle CapLevelOne" href="#{{ member.ID }}">{{ member.Name }}</a></h2>
<div class="toggle-content"  id="{{ member.ID }}">
   <p class="CapLevelOneDesc">{{ member.Documentation }}</p> 

    {% for item in member.levelTwo %}
    <h3><a class="toggle CapLevelTwo" href="#{{ item.ID }}">{{ item.Name }}</a></h3> 
    <div class="toggle-content"  id="{{ item.ID }}">
        <p class="CapLevelTwoDesc">{{ item.Documentation }}</p> 

        {% for itemtwo in item.levelThree %}
        <h4><a class="toggle CapLevelThree" href="#{{ itemtwo.ID }}">{{ itemtwo.Name }}</a></h4> 
        <div class="toggle-content"  id="{{ itemtwo.ID }}">
       <p class="CapLevelThreeDesc">{{ itemtwo.Documentation }}</p>
        </div>
        {% endfor %}
    </div>
    {% endfor %}


    </div>

{% endfor %}

</div>
