+++
canonical_url = ""
content_img_alt = ""
content_img_path = ""
date = 2020-12-26T00:00:00Z
draft = true
excerpt = "When companies develop software products, it is rather common that the decisions regarding the implementation of new features is done based on different people's opinions. However, this can lead to suboptimal results. It is more efficient to lead development work based on data - this is called data-driven development."
layout = "post"
subtitle = ""
thumb_img_alt = ""
thumb_img_path = ""
title = "Data-Driven Development - Develop software based on evidence, not opinions"

+++
When companies develop software products, it is rather common that 
the decisions regarding the implementation of new features is done based
 on different people's opinions.

**In practice the situation in the company can go like this:**

**Developer A**: The customer wants to somehow access the product search 
easier. How should we make the search feature more accessible?

**Developer B**: Let's have the search bar on the top of the header, where it is pretty much the first thing that can be seen!

**Developer C**: How about having a striking button that opens a modal where the search can be performed!?

**Product Owner**: Back in the day, we solved this problem like this: 
\[some suboptimal solution that works, but is not what the customer 
necessary wants or means (for example the search box is fixed to the web
 page where it can distract the users)]. Let's do it this way!

**Developers A, B and C**: Okay, let's go with that...

This kind of decision making can lead to **suboptimal** solutions where 
time is wasted on developing features that the customer doesn't want or 
need. It is easy to make decisions based on opinions - by quickly 
selecting a certain solution the work can start fast and an illusion of 
efficient software development is created.

Luckily, the modern trends of software development like Continuous 
Integration and Delivery (CI / CD) make it possible to develop software 
with a new, data-driven approach.

Below, you can see the HYPEX model (Bosch and Olsson 2014) that addresses the process of data-driven development. It involves many interesting concepts like MVF (Minimum Viable Feature).



![](/images/hypex.png)



References:

Olsson, H., Bosch, J., 2014. The HYPEX Model: From Opinions to Data-Driven Software Development 155–164. <https://doi.org/10.1007/978-3-319-11283-1-13>