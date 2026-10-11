---
layout: default
title: About
---

<div class="hero">
  <img class="avatar" src="{{ '/assets/img/bea-happy.jpeg' | relative_url }}" alt="Photo of {{ site.name }}">
  <div class="hero-text">
    <h1>{{ site.name }}</h1>
    <p class="lead">{{ site.tagline }}</p>
    <p class="muted small">📍 {{ site.location }}</p>
  </div>
</div>

<div class="buttons">
  <a class="btn primary" href="{{ '/cv/' | relative_url }}">View my CV</a>
  <a class="btn" href="{{ site.links.linkedin }}" target="_blank" rel="noopener">LinkedIn</a>
  <a class="btn" href="{{ site.links.github }}" target="_blank" rel="noopener">GitHub</a>
</div>

## whoami

I am passionate about cryptographic engineering, hardware and embedded security, and privacy-enhancing technologies. I am particularly interested in the intersection of cryptography and secure system design, as well as the mechanisms that enable privacy and security at both the hardware and software levels.

Beyond technical aspects of security, I am fascinated by the philosophical and societal dimensions of digital privacy, particularly questions surrounding surveillance capitalism, digital autonomy, and the growing collection and exploitation of personal data. I am interested in how cryptographic techniques and privacy-preserving technologies can help address these challenges.

My goal is to contribute to the development of secure systems that not only protect data but also respect individual privacy and autonomy.

Outside the technical world, I am a rock climber and an enthusiastic explorer of the outdoors. I try to seek out new experiences, push beyond my comfort zone, and confront the fears that come with doing something unfamiliar. For me, climbing is as much about patience, problem-solving, and trusting the process as it is about reaching the top.
When I am not studying or climbing, I enjoy working with my hands and exploring different forms of creative expression. I shoot film photography and I practice pottery. These crafts offer a counterbalance to my technical work, allowing me to slow down, experiment, and engage with the world in a more tangible way.

Whether I am exploring the inner workings of secure systems, finding my way up a climbing route, or creating something by hand, I am driven by curiosity, a willingness to challenge myself, and a desire to understand how things work.

<div class="callout">
  <span class="status"><span class="dot"></span>Open to opportunities</span>
  <h2>Seeking a 2027 Cybersecurity Research Internship</h2>
  <p>
    I’m currently looking for a research internship starting in February 2027 in the field of cybersecurity. I’m particularly interested in offensive security, cryptographic engineering, and hardware security, with a strong focus on side-channel attacks against post-quantum cryptographic implementations.
  </p>
  <p>
    I’m eager to contribute to challenging research projects, deepen my technical expertise, and explore the security of cryptographic implementations from both a theoretical and practical perspective. I’m especially interested in opportunities involving hands-on security research, vulnerability analysis, and the evaluation of real-world implementations.
  </p>
  <p>
    If your team is looking for an intern or knows of any relevant opportunities, I’d love to connect and discuss how I could contribute to your research!
  </p>
  <div class="buttons">
    <a class="btn primary" href="mailto:{{ site.email }}?subject=Cybersecurity%20research%20internship%202027">Get In Touch</a>
    <a class="btn" href="{{ '/cv/' | relative_url }}">View my CV</a>
  </div>
</div>

<!-- ## What you'll find here -->

<div class="cards">
  <a class="card" href="{{ '/experience/' | relative_url }}" style="text-decoration:none">
    <h3>Experience</h3>
    <p>Where I've worked and what I care about professionally.</p>
  </a>
  <a class="card" href="{{ '/hobbies/' | relative_url }}" style="text-decoration:none">
    <h3>Hobbies</h3>
    <p>What I get up to when I'm not working.</p>
  </a>
  <a class="card" href="{{ '/cv/' | relative_url }}" style="text-decoration:none">
    <h3>CV</h3>
    <p>My full CV, to read online or download as PDF.</p>
  </a>
</div>

## Get In Touch

The easiest way to reach me is by [email](mailto:{{ site.email }}) or on
[LinkedIn]({{ site.links.linkedin }}).
