Green Apple Pay T 661 Critical Notes
=======================================

IMPORTANT: Use existing materials and documents generated during the course of your development work to extract the pertinent information to complete these questions.


## 242 – What technological obstacles did you have to overcome? 350 words max – 50 lines of 78 characters

The state of technology at the beginning of the project had several shortcomings and/or limitations,
as well as technological problems and unknown elements,
as described below:

Typically we are faced with using a tried and true e-commerce model for purchasing products,
but we quickly realized that this was not scalable,
and inadequate for the number of unique edge cases our platform required.
We hypothesized we could potentially develop an event and schedule-based hybrid application model to accomplish this.
We commenced work to overcome obstacles related to the workflow customization process,
within the typical checkout cart process.
We analysed the process to attempt to develop an approach,
such as event-based modules,
which would allow adjustment of the order status and data within the cart,
and allow these events to be created scheduled,
and repeated.

It was uncertain how we would integrate with many reporting,
device,
and system meta data processes and tools.
We were uncertain how to develop a middleware layer to achieve this,
while maintaining control and security of data,
as well as overcoming transaction performance issues.


>The distinct weakness that I see in the submission is the validity of the technical uncertainty as having benefit for the greater population,
ergo the taxpayer,
per the SR&ED documentation and law on the government website.
The technical uncertainty existed for the company,
but what is left in the cold is the certainty that the company achieve something that is of benefit to the Canadian taxpayer,
either by addressing a lingering technological work hole that they filled that is a benefit to other coders,
or other participants in the technological community,
even open source.



## 244 – What work did you perform in the tax year to overcome those technological obstacles?   700 words max - 100 lines of 78 characters

In the 2020 fiscal period, through October to November 2019, the development work was performed by our sub-contractor,
Cappers Applications, and they continued to attempt to overcome our e-commerce model limitations by integrating a better payment model.
Payment transaction abstraction needed to occur,
as there were too many payment transactions among too many nodes to be secure using known technologies.
Our hypothesis is that we could allow this payment process to be simpler with less steps;
we could potentially integrate a wallet technology within our system as a payment clearance layer.
We completed tests and developed an experimental integration path extending from Bambora API&copy; in an attempt to overcome these limitations and advance our toolset.

Due to resource constraints the SRED effort was put on hold Deceember 2019 until June 2020. No SRED work was performed during that time.

Through July 2020, our new sub-contracted Architect Temuri Imnaishvili, continued to build the baselie platform which would become the testbed that would allow us to perform experimental development and testing. The platform consisted of...  




## 246 – What technological advancements were you trying to achieve? 	350 words max - 50 lines of 78 characters

The technological objective of the project is development of a Data Brokerage Layer for School E-Commerce Systems.
We realized this layer became necessary in dealing with the voluminous amounts of information on abstract school networks.
This layer works as an intermediary that provides data and service integration between school systems,
a payment gateway,
and any school board systems.
We realized that student and payment data could be processed much more efficiently if there is a layer that can work as data broker and can processing of events and purchases ad-hoc by various user types.
We were also able to develop support for better data transaction services,
as we were able to accomplish more sophisticated,
time-delayed event updates and scheduling related to future-compensating transactions.


In this project,
we were trying to achieve development of an architectural framework which focuses on the exchange of data to facilitate the financing and payment aspects of school’s cash transactions,
related to product and scheduled event purchases.
The work done advanced the existing state of knowledge in the field of Information Technology,
specifically in the E-Commerce Pattern methodologies.


This development represents a technological advancement in the E-Commerce workflows,
as existing technology and knowledge base level at the onset of this project was limited,
as we realized that the typical e-commerce order workflow would not work for our model.
Usually e-commerce store approaches are comprised of a combination of design patterns,
such as: MVC design pattern,
factory pattern (for maintaining orders and bill generation),
and the observer pattern for updating inventories and product data.
However,
alone these would not be satisfactory in context of school’s business,
purchase events,
and application logic: purchase processes would be more complex.
Project or Campaign management API’s existed,
but they were not suitable or reliable to integrate to meet our edge cases.
There is a low certainty of integrating a scheduled,
repeatable events-driven structure into any e-commerce model,
especially when considering scalability.
Further,
there is a lack of system security,
reliability,
standards and communication protocols within the school environment.
It was difficult to integrate the Internet and E-Commerce software with some existing applications and databases.
Uncertainties required experimentation to determine an advanced process.


The work done resulted in development of an architectural framework which focuses on the exchange of data to facilitate the financing and payment aspects of a school’s cash transactions.
Our approach allows schools and companies to link their internal and external APIs more efficiently and effectively,
and manipulate data safely,
efficiently,
and more secure.
