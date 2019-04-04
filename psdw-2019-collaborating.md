<!-- .slide: data-background-size="cover" style="padding-left: 80px" data-background="./img/2019/psdw/bg-1.png" -->

<h1 style="text-align: left; font-size: 80px;">Collaborating with Core</h1>
<p style="text-align: left; font-size: 30px;">Carsten Piepel</p>
<p style="text-align: left; font-size: 30px;"><a href="https://github.com/carstenpiepel">@carstenpiepel</a></p>
<p style="text-align: left; font-size: 30px;">Slides: <a href="https://bit.ly/2I7YxVY"><code>http://bit.ly/abc123</code></a></p>

---

<!-- .slide: data-background="./img/2019/psdw/bg-2.png" -->

<p class="fragment fade-in">It's not all about</p> 
## Bugs, bugs, bugs


<aside class="notes">
 - Caveat that the information discussed here is based on my subjective experience and not necessarily factually correct (but it works, most of the time)
 - I had the dea for this talk because I find myself explaining how to file software defects and get them addressed quite regularly
 - After giving this further thought that there is a lot more to it than software defects
</aside>

---

<!-- .slide: data-background="./img/2019/psdw/bg-1.png" -->

## Why collaborate?

* Complexity <!-- .element: class="fragment" -->

* Continous change <!-- .element: class="fragment" -->

<aside class="notes">
 - Complex software: The ArcGIS software platform is becoming increasingly more complex. Think of ArcGIS Enterprise will it's components, a wide range of capabilities, and embedded third-party products. Another example is the proliferation of SDKs and APIs.
 - Evolving software: Software doesn't stand still. Today's expert knowledge will be obsolete tomorrow.
 - New products: In that context, Esri continues to release new products, both for developers and non-developers (Insights, Excalibur, Mission Management, Python API, Notebook Server, R-ArcGIS Bridge, etc.)
 - But also ...
</aside>

---

<!-- .slide: data-background="./img/2019/psdw/bg-2.png" -->

## Smart people

<img alt="Margaret Hamilton" src="https://upload.wikimedia.org/wikipedia/commons/d/db/Margaret_Hamilton_-_restoration.jpg" style="width: 30%; height: 30%">

<aside class="notes">
 - Smart people: Margaret Hamilton is topical because she invented the term software engineering and because was a literal rocket scientist who helped develop on-board flight software for the Apollo space program. There are a many incredibly smart people at Esri as well. Together we can achieve better outcomes than as individuals.
</aside>

---

<!-- .slide: data-background="./img/2019/psdw/bg-4.png" -->

## (Org chart goes here)

---

<!-- .slide: data-background="./img/2019/psdw/bg-1.png" -->

## How to reach out?

1. Direct to peers and managers <!-- .element: class="fragment" -->

1. Teams (or Slack, if you must) <!-- .element: class="fragment" -->

1. AskArcGISXYZPM@esri.com e-mail aliases <!-- .element: class="fragment" -->

1. Specialist (sp-xyz@esri.com) e-mail aliases <!-- .element: class="fragment" -->

1. Targeted outreach to core teams and individuals <!-- .element: class="fragment" -->


<aside class="notes">
  - In about this order of escalation
  - Be courteous
  - Get someone to make an introduction
  - Good e-mail practices (needs a beginning, a middle part, and an ending; be concise; include evidence; anticipate recipient's questions and responses)
  - Don't approach individual developers without their manager's permission (might be a one-time thing)
</aside>

---

<!-- .slide: data-background="./img/2019/psdw/bg-1.png" -->

## Always: Holistic testing

<img alt="Derek Law on Twitter: Some cool #OpsDashboard for #arcgis beta #apps created during holistic testing today #esri #GIS #dashboard #betatesting @Esri @ArcGISApps" src="https://pbs.twimg.com/media/DM9x6mvVwAAKt0R.jpg" style="width: 70%; height: 70%">

[Credit: Derek Law on Twitter](https://twitter.com/GIS_Bandit/status/923081712388661248) <!-- .element: style="position:absolute; bottom:20px; right:20px; font-size:0.5em" -->

<aside class="notes">
  - How has participated in a holistic testing session? If you haven't, holistic testing provides an opportunity for audiences outside of development team(s) to test realistic scenarios (as oposed to tightly scripted scenarios)
  - In my experience, it works best for established software products (not so well for new software products)
  - Esri attendees get invited directly (because their expertise is known and requested) and notifications are sent to managers (at least to the CTO)
  - Great opportunity to make yourself known
</aside>

---

<!-- .slide: data-background="./img/2019/psdw/bg-3.png" -->

## Engagements: Planning

* Validate designs and receive recommendations <!-- .element: class="fragment" -->

* Request enhancements <!-- .element: class="fragment" -->

* Ask for permission <!-- .element: class="fragment" -->


<aside class="notes">
  - The planning stage of a development engagement, either pre-proposal or during the requirements and design phase, is great opportunity for validting the feasibility of a specific implementation approach. That's also a the right time for approaching core teams to provide feedback on design approaches, to discuss the possibility of enhancing core software to meet specific needs your effort my have, or to bless non-standard/new/inventive approaches.
  - When asking for enhancements, describing challenges with the existing implementations is preferable over proposing a solution
  - Of course, reserve this for efforts that real require this kind of due diligence (not for garden variety efforts)
  - Office of the CTO can help with this
</aside>

---

<!-- .slide: data-background="./img/2019/psdw/bg-2.png" -->

## Engagements: Implementation

* Software defect lifecycle: PS Incident -> Case -> Bug -> "CR" -> Hot Fix -> Patch -> Release <!-- .element: class="fragment" -->
 - Needs to be reproducible <!-- .element: class="fragment" -->

* Enhancement request lifecycle: PS Incident -> Case -> Enhancement -> "CR" -> Release <!-- .element: class="fragment" -->

* Can work backwards too (start with CR) <!-- .element: class="fragment" -->

* It is possible to attach a case to an existing bug or enhancement request <!-- .element: class="fragment" -->

* ArcGIS ideas <!-- .element: class="fragment" -->

* Customer Advocacy <!-- .element: class="fragment" -->


<aside class="notes">
  - Implementation in the broad sense applies to both development or configuration activities. The doing phase of an engagement ...
  - Jaco Baca
</aside>

---

<!-- .slide: data-background="./img/2019/psdw/bg-1.png" -->

## Demo

---

<!-- .slide: data-background="./img/2019/psdw/bg-2.png" -->

## Charging guidance

* Once bug record has been created, PM/TA can request unbillable charge code <!-- .element: class="fragment" -->

* Diagnosing and reporting of defect as well as testing of fixes are eligible <!-- .element: class="fragment" -->

* Workarounds are not eligible! <!-- .element: class="fragment" -->


<aside class="notes">
</aside>

---

<!-- .slide: data-background="./img/2019/psdw/bg-2.png" -->

## Ask yourself ...

* Should we send a paying PS customer to tech suppport? <!-- .element: class="fragment" -->
 - Might well depend on the lifecycle stage of any given customer relationship <!-- .element: class="fragment" -->

* What can we do to smooth out the tech support experience? <!-- .element: class="fragment" -->

* Should PS help escalate? <!-- .element: class="fragment" -->


<aside class="notes">
</aside>

---

<!-- .slide: data-background="./img/2019/psdw/bg-3.png" -->

## Engagements: Post implementation


<img alt="After action review" src="https://media.defense.gov/2018/Jan/23/2001868567/3836/3836/0/180118-M-TM546-092A.JPG" style="width: 50%; height: 50%">

<aside class="notes">
 - What happened, why it happened, and how it can be done better
 - What worked and didn't work
</aside>

---

<!-- .slide: data-background="./img/2019/psdw/bg-4.png" -->

## Don't forget ...


<img alt="Stronger together" src="https://upload.wikimedia.org/wikipedia/commons/7/7c/Stronger_Together.png" style="width: 50%; height: 50%">

<aside class="notes">
</aside>

---
