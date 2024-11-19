# Brian Burns Talks
This is a collection of some of the talks that I have given at conferences,  meetups, and workshops.  

## [AI-Assisted Outfitting](https://drive.google.com/file/d/1eVnvv5di0aQyhy6CopKf3okkW2I3r0xn/view?usp=sharing)
**Date:** November 11th, 2024    
**Event:** [Georgia Tech MSA Professional Development Summit](https://www.analytics.gatech.edu/10th-anniversary/professional-development-summit)    

A brief update on AI-based processes to assist in creating outfits for Nordstrom Digital Services.

---
## [Representation Learning Driven Outfit Creation: Assisting Styling to Scale](https://drive.google.com/file/d/1O7dxjmkjOfvyrUzcDqI19UIl8R0-In4m/view?usp=sharing)
**Date:** August 25th, 2021  
**Event:** [Data Science Salon: Applying AI & Machine Learning to Retail and E-commerce](https://www.datascience.salon/retail-and-ecommerce/)    

Nordstrom Digital Stylists create outfits to help our customers look good and feel great. They are asked to create outfits for several reasons: to serve an individual customer, to contribute to a thematic curation, to showcase an individual product, and more! During peak events with lots of new inventory such as the holidays and large sales, demand for their expertise can be enormous. In service of helping our stylists, we have created a machine learning based outfit creation/completion service leveraging Nordstrom’s extensive dataset of expertly created outfits and a hybrid graph based and representation learning approach. Given an initial item or set of items, we create outfits out of available inventory that are difficult to decern from those created by stylists, even by our stylists themselves. Join this talk to hear more about Nordstrom’s approach and results from their recent Anniversary Sale.

---
## [The Data Science/ML Case Study: Format Overview, Advice and Examples](https://docs.google.com/presentation/d/1yOmuFncPaeymOX5kAjg40w91XDkyxjbDTS2MqrosVis/edit?usp=sharing)
**Date:** October 23rd, 2020    
**Event:** Georgia Tech. M.S. in Analytics Career Workshop: Technical Interviewing

This presentation focuses on the case study (a.k.a. problem solving) interview format for Data Scientists, which was one of a few interview formats covered at the workshop with co-speaker Dr. Beverly Wright.  **The focus is to prepare aspiring data scientists for this type of interview and offer advice from my years on the other side of the interview table.**  

---
## [Testing for CRAN: Docker-Based r-devel Testing](https://docs.google.com/presentation/d/1vLjVeKPAdRfESF3jHoXp84Ff0KoMtEMm00RZ24_6SWM/edit?usp=sharing)
**Date:** May 30th, 2020    
**Event:** [satRday Chicago 2020 Conference](https://chicago2020.satrdays.org/)    
**Recording:** [YouTube (15 minutes)](https://www.youtube.com/watch?v=xA7l7N2ktFk&feature=youtu.be&start=8630&end=9794)

Testing your package before uploading to CRAN can be a bear! You’ve just done all this great work to polish and test your package on your R setup and now (as CRAN requires) you need to test it all again on the latest development version of R, called r-devel. Skipping this is tempting but often a more time consuming battle than testing and iterating locally (also, ethics, amiright). In this talk, I will demonstrate a process to build your own CRAN compliant testing process from publicly maintained docker images in a time saving and repeatable fashion. It’s the same process used to prepare pkgnet submissions. The step-by-step is available on the CONTRIBUTING page in the github repository. Some knowledge of docker and/or CRAN submission process would be helpful but is not a must have.

---
## [Recursive Package Dependencies: Unraveling A Tangled Web](https://docs.google.com/presentation/d/1QZAaPm11bC9OofagPnArP0W1GeG6jwAxthZwaoDzDWk/edit?usp=sharing)
**Date:** April 27th, 2019    
**Event:** [satRday Chicago 2019 Conference](https://chicago2019.satrdays.org/)

What are you REALLY adding to your R package when you add that dependency? Nearly all R packages have dependencies, or in other words, separate packages that are utilized to provide a set of functions for the original package. They’re great. Often, they provide stellar, community-validated code that would take significant time and effort to create yourself. However, you’re relying on more than the code in a dependency—you’re counting on that dependency and all of its dependencies, recursively, to be stable: to be updated for newer versions of R, to be maintained with good versioning, and to have no breaking changes. If not, then when any dependency fails, it can mean lots of work for you to resolve the issue. In this talk, we’ll discuss best practices with package dependencies, including how to judge the true risk of a dependency and the effort to replace it.

---
## [Lightning Talk: One Function From pkgnet](https://docs.google.com/presentation/d/1AdzDzFkT7v3ByYRmRVjIXY4efTbEK7br6eF-Jlh4oXI/edit?usp=sharing)
**Date:** January 23rd, 2019    
**Event:** [Chicago R User Group - One Liner Lightning Talks](https://chicago-r-user-group.github.io/)

Presenting the R function `pkgnet::CreatePackageReport()` and the value that can be derived from this one line of code.
