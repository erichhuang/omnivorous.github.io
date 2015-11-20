---
published: true
---



## Microservices & Medicine
`Data Science is an interdisciplinary field about processes and systems to extract knowledge or insights from large volumes of data in various forms, either structured or unstructured (Wikipedia)` 

Medicine is the ultimate data science. When you're sitting across a patient in an exam room, you are summarizing structured data (e.g. laboratory tests) and unstructured data (e.g. clinic notes, journal articles) into a decision that (hopefully) represents the best interpretation of all those data according to the needs of your patient. 

More than a year ago, the computer scientist and blogger, Martin Fowler, wrote a wonderful post (with his colleague James Lewis) about ["Microservices"](http://martinfowler.com/articles/microservices.html), an architectural style for breaking applications into "service" components that can operate independently. Put their way:

> ...The microservice architectural style is an approach to
 developing a single application as a suite of small services, each running in
 its own process and communicating with lightweight mechanisms, often an HTTP
 resource API. These services are built around business capabilities and
 independently deployable by fully automated deployment machinery...
 
So what on earth does this have to do with healthcare and biomedical research? We've got people to take care of, cures to discover, why should we care about the architectural style of software for God's sake?

One trendy (and correct concept) is that healthcare providers and health systems should learn from and optimize for their patients continuously. 

Surely, we do this already when we take care of a patient one way, find that things didn't work out as expected and then try something different the next time we see a similar patient. But how do we make this individualized experiential knowledge common knowledge? How do we represent such knowledge in a way our peers can assimilate? How do we scale the data intake and knowledge extraction process so that the wisdom we might gain as an individual primary care provider or transplant surgeon can be shared and used by our peers?

**This is what "Learning Health Systems" are about** and where architecture matters. This architecture has to support a continuous cycle of healthcare delivery, data collection, knowledge generation, and a new "learned" cycle of data-informed delivery.

Given this, why is a "microservices" architecture better for a modern health system? 

Healthcare is complex: we receive data from multiple sources. These sources might include a next generation sequencing machine, "conventional" laboratory assays, free text notes from an electronic health record, reports from external diagnostic test vendors, even the latest article from the New England Journal of Medicine; and that's setting aside the accumulated knowledge about groups of similar patients who's genomic, social, and clinical characteristics similarly influence their health and their responses to different interventions.

You can imagine that how we care for a patient is very much due to the aggregation and integration of all these data sources





