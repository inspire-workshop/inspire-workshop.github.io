---
layout: default
---

<div class="content-section">
<div class="inline-wrapper">
<h2 id="workshop-details">Workshop Details</h2>

<p>
Welcome to the <b>RSS 2025</b> Workshop on <b>In</b>formative <b>S</b>ensing and <b>P</b>lanning for <b>I</b>ntelligent <b>R</b>obotic <b>E</b>xploration!
</p>

<p>
“So, why did the robot go to that room?”, “Did the robot find anything?”, “…Maybe. We’re not sure.”, “Can’t you tell me how confident you are?” “Not really”, “Why didn’t the robot check further or observe from a better place?” “It wasn’t programmed for that!”. 
These questions and dialogues are often expressed when deploying robots that rely on passive, fixed, and rigid methods to collect data and understand their complex environments. Contrarily, active perception and information gathering strategies allow robots to intelligently adapt their sensing and decision-making processes, which is crucial for operating in complex, dynamic environments requiring adaptability and efficiency for applications like exploration, search and rescue, mapping, and inspection. 
Perception, mapping, and planning are fundamental components of robotic information gathering.  However, their effective deployment across diverse scenarios requires a more integrated and holistic approach. With the rapid emergence of novel learning-based methods, it is crucial to revisit them from the lens of information theory – a pivotal perspective in active perception and efficient robotic information acquisition.
</p>

<p>
The workshop aims to bring together researchers and practitioners across academia, government agencies, and industry to discuss state-of-the-art methods in information gathering, involving topics like efficient path planning, sensor fusion, environmental modeling, and behavioral reasoning. 
Additionally, discussions will address the role of advanced deep learning techniques in continual learning and adaptation. Our proposed workshop will feature a structured program with invited talks, panel discussions, and interactive poster sessions. 
Presenters and panelists come from various sub-communities, including aerial, ground, and marine robotics, as well as theoretical fields such as control and information theory. Industry representatives will also provide insights into real-world applications and challenges. 
The event is designed to encourage and foster collaboration across different research areas and highlight synergies in information gathering across application domains. 
</p>

</div>
</div>

<div class="content-section">
<div class="inline-wrapper">
<h2 id="call-for-posters">Call for Posters</h2>

<h3>Topics</h3>

<ul class="default-list">
{% for topic in site.call.topics %}
    <li>{{ topic }}</li>
{% endfor %}
</ul>

<h3 id="submissions">Submission</h3>

<p>
Researchers in robotic information gathering and exploration are 
encouraged to contribute to the workshop by submitting a <b>poster</b> 
in PDF format. We encourage the submission of new ideas. The program committee 
will review each contribution, and the authors will be notified of the result.
</p>

<p>
Submission link: <a href="{{ site.call.submissions.url }}">{{ site.call.submissions.link_name }}</a>
</p>

<p>

</p>

</div>
</div>

<div class="content-section">
<div class="inline-wrapper">
<h2 id="important-dates">Important Dates</h2>

<ul class="default-list">
    {% for event in site.events %}
    <li><b>{{ event.date }}</b>: {{ event.name }}</li>
{% endfor %}
</ul>

</div>
</div>

<div class="content-section">
<div class="inline-wrapper">
<h2 id="invited-speakers">Invited Speakers</h2>

<div class="people-list">
{% for speaker in site.speakers %}
    <div class="single-person">
        <ul>
            <li>
                <img alt="{{ speaker.name }}" src="{{ speaker.photo_url }}">
            </li>
            <li>
                <a href="{{ speaker.url | relative_url }}" target="_blank">{{ speaker.name }}</a>
            </li>
            <li>{{ speaker.confirmation}}</li>
            <li>{{ speaker.role }}</li> 
            <li>{{ speaker.organization }}</li> 
            <li>{{ speaker.country }}</li>
        </ul>
    </div>
{% endfor %}
</div>
</div>
</div>

<div class="content-section">
<div class="inline-wrapper">
<h2 id="invited-panelist">Invited Panelist</h2>

<div class="people-list">
{% for panelist in site.panelists %}
    <div class="single-person">
        <ul>
            <li>
                <img alt="{{ panelist.name }}" src="{{ panelist.photo_url }}">
            </li>
            <li>
                <a href="{{ panelist.url | relative_url }}" target="_blank">{{ panelist.name }}</a>
            </li>
            <li>{{ panelist.role }}</li> 
            <li>{{ panelist.organization }}</li> 
            <li>{{ panelist.country }}</li>
        </ul>
    </div>
{% endfor %}
</div>
</div>
</div>

<div class="content-section">
<div class="inline-wrapper">
<h2 id="workshop-organizers">Workshop Organizers</h2>

<div class="people-list">
{% for organizer in site.organizers %}
    <div class="single-person">
        <ul>
            <li>
                <img alt="{{ organizer.name }}" src="{{ organizer.photo_url }}">
            </li>
            <li>
                <a href="{{ organizer.url | relative_url }}" target="_blank">{{ organizer.name }}</a>
            </li>
            <li>{{ organizer.role }}</li> 
            <li>{{ organizer.organization }}</li> 
            <li>{{ organizer.country }}</li>
        </ul>
    </div>
{% endfor %}
</div>

<span style="font-weight: bold; text-align: center; display: block; margin-top: 20px;">
Contact us at: m.popovic@tudelft.nl
</span>

</div>
</div>

<div class="content-section">
<div class="inline-wrapper">
<h2 id="involved-institutions">Involved Institutions</h2>

<div id="institution-logos">
    {% for institution in site.institutions %}
        <div class="institution-logo">
            <a href="{{ institution.url }}" target="_blank">
                <img alt="{{ institution.name}}" src="{{ institution.logo_url}}">
            </a>
        </div>
    {% endfor %}
</div>
</div>
</div>

<div class="content-section">
<div class="inline-wrapper">
<h2 id="workshop-program">Workshop Program</h2>

<div id="program-table">
    <div class="program-row">
        <div>08:15 AM</div>
        <div>Welcome message</div>
        <div></div>
    </div>
    <div class="program-row">
        <div>08:30 AM</div>
        <div>Sensing: Hermann Blum, Antonella Barišić, (Martin Saska)</div>
        <div></div>
    </div>
    <div class="program-row">
        <div>09:50 AM</div>
        <div>Poster spotlight talks</div>
        <div></div>
    </div>
    <div class="program-row">
        <div>10:00 AM</div>
        <div>Coffee break and posters</div>
        <div></div>
    </div>
    <div class="program-row">
        <div>10:30 AM</div>
        <div>Information theory: Graeme Best</div>
        <div></div>
    </div>
    <div class="program-row">
        <div>11:00 AM</div>
        <div>Planning: Hyondong Oh, Nare Karpetyan, (Jen Jen Chung)</div>
        <div></div>
    </div>
    <div class="program-row">
        <div>12:20 PM</div>
        <div>Poster spotlight talks</div>
        <div></div>
    </div>
    <div class="program-row">
        <div>12:30 PM</div>
        <div>Lunch break and posters</div>
        <div></div>
    </div>
    <div class="program-row">
        <div>02:00 PM</div>
        <div>Mapping: Lukas Schmid, Marco Hutter</div>
        <div></div>    
    </div>
    <div class="program-row">
        <div>02:50 PM</div>
        <div>Poster spotlight talks</div>
        <div></div>
    </div>
    <div class="program-row">
        <div>03:00 PM</div>
        <div>Coffee break and posters</div>
        <div></div>
    </div>
    <div class="program-row">
        <div>03:30 PM</div>
        <div>Panel discussion: TBA</div>
        <div></div>    
    </div>
    <div class="program-row">
        <div>04:30 PM</div>
        <div>Industry: Peter Karkus, Ali-akbar Agha-Mohammadi</div>
        <div></div>
    </div>
    <div class="program-row">
        <div>05:30 PM</div>
        <div>Closing remarks</div>
        <div></div>
    </div>
</div>
</div>
</div>
