---
title: About *Apartheid Heritage(s)*
layout: about
permalink: /about.html
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html %}

{% include feature/nav-menu.html sections="About the Collection;About the About Page" %}

## About the Apartheid Heritage(s) Collection

This collection of digital resources is an extension of the 3D spatial historical analysis of Soweto, the historic Black township near Johannesburg, South Africa.
The items in this collection were selected to encourage researchers to reimagine spaces by asking themseleves questions such as: 

- what is spatial history?
- are space and place the same thing?
- how do spaces influence and affect places?

[Click here](https://apartheidheritages.org/) to learn more about the *Apartheid Heritage(s)* project and 3D spatial historical publication.

## Using the *Apartheid Heritage(s)* Digital Archive

We want you to explore these digital objects and consider their history from a critical perspective. 

Feel free to explore the archive by searching for objects by specific metadata categories, such as:
-subject
-date
-location


When viewing an object, please pay special attention to the description field. The descriptions have been carefully researched in order to provide a historical background and context to the object. 

After the description of every image, there is a statement that reads, "For additional context, please consider:" followed by a list of concepts and events. These have been included to encourage the user to think critically about the object they are viewing, the spatial history, and the critical role of digital archives in pushing against normative historical narratives.

{% include feature/card.html header="Description example" text="This 1977 photo shows a member of the South African Police's Security Branch, which was a special task force formed for the explicit purpose of crushing anti-apartheid movements. On June 19, 1977, the one-year anniversary of the Soweto Uprising, officers patrolled Black townships, shooting bird-shot, tear gas, and ammunition into Black demonstrators and protesters. The SAP Security Branch officer wears a camouflage uniform and carries tear-gas launcher attached to what appears to be an assault style rifle, one of the many weapons and riot gear used by police. Behind him are other SAP officers and white South African onlookers. 
<strong>For additional context, please consider: South Africa Police's Security Branch targets anti-apartheid activists; Police state; Militarized police; Police and military in Black neighborhoods; Treatment of Black people by the police; Military enforcement of white sumpremacy; Sharpeville; Soweto Uprising; Police and military seen as an occupying force in Black townships; Compulsory military service of White South African men </strong>" objectid="Firing_Teargas_Soweto_South_Africa_1977" width="25" centered=true %}


{% include feature/button.html text="Button Link to Somewhere" link="https://collectionbuilder.github.io/" color="success" centered=true %}
  
- Alerts -- > `{% raw %}{% include feature/alert.html text="this is an *alert* that 'warns' a user" color="warning" align="center" %}{% endraw %}`

{% include feature/alert.html text="This is an *alert* that 'warns' a user with centrally aligned text." color="warning" align="center"  %}

<div class="container-box">
<button type="button" class="btn btn-info btn-lg" data-toggle="modal" data-target="#myModal">Contact Us</button>
</div>

<!-- Modal -->
<div id="myModal" class="modal fade" role="dialog">
  <div class="modal-dialog">

<!-- Modal content-->
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal">×</button>
<h4 class="modal-title">Contact Us</h4>
</div>
<div class="modal-body">

        <form role="form" method="post" id="reused_form">
        <p>
            Send your message in the form below and we will get back to you as early as possible.
        </p>

        <div class="form-group">
            <label for="name">
                Name:</label>
            <input type="text" class="form-control"
            id="name" name="name"   required maxlength="50">

        </div>
        <div class="form-group">
            <label for="email">
                Email:</label>
            <input type="email" class="form-control"
            id="email" name="email" required maxlength="50">
        </div>
        <div class="form-group">
            <label for="name">
                Message:</label>
            <textarea class="form-control" type="textarea" name="message"
            id="message" placeholder="Your Message Here"
            maxlength="6000" rows="7"></textarea>
        </div>
        <button type="submit" class="btn btn-lg btn-success btn-block" id="btnContactUs">Post It! →</button>

    </form>
    <div id="success_message" style="width:100%; height:100%; display:none; ">
        <h3>Sent your message successfully!</h3>
    </div>
    <div id="error_message"
    style="width:100%; height:100%; display:none; ">
        <h3>Error</h3>
        Sorry there was an error sending your form.

    </div>
</div>

</div>

 </div>
</div>
