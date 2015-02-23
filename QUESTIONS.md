# Culture of Quality Questions

* Are there unit tests and functional tests, and are they run every build ?

* What is the the current code coverage of those tests ?

* Is the the coverage reported on every build ?

* Is there a minimum accpetable coverage (e.g. 80% coverage) that is required for a build to pass

* Are there well defined performance critera for the software such that it can be tested every release ?

* Does code have a standard logging mechanism ?

* Does code have a debug mode where any exceptions can be easily retrieved and analyzed.

* Are performance tests run regularity ?
 
* Are the results of theses tests recorded in a central datastore ?

* Does every error message presented to the user have a unquie error id that can be traced to a single line of code?

* Does development build debug and measurement features into the software ?

* Does QA collaborate on these features ?

* Are interfaces owned by individuals such they are a central communication point for changes and documentation?

* If a bug is found, is a new unit test automatically recreated.  Is the unit test named with the bug number (e.g. test37231?)

* Is there a way to record and playback traffic into the software system to reproduce crashes.

* Is there a way to record live traffic and use to to generate test cases ?

* Does the development team have a way to document and report technical debt at every build?

* Are these quality metrics (unit test coverage, technical debt, etc.) reported in a place that is visible to everyone all the time ?

* Does code swallow any exceptions, if so is there an automated way to detect this when the code is built?

* Are Development and QA seperate teams or are members of each in the same team so they are co-located and can collaborate more easily?

* Does QA happen after Develpoment or are QA and Development an iterative process ?

* Is Documentation tested for usefulness, completeness, and understandability ?

* Is there a reward or recoginitionn for those that supply quality information and documenation ?

* To what degree, and how early are the users of the product involved in the development and qa process ?

* To what degree is Automation and Continuous Integration used in the development and QA process ?

* To what degree are Automation and Coninuous Integration prioritized in the project plan ?

* In the organization, does QA address quality of information, documentation, and communication as well as the software itself ?

* Does the culture care about quality?  How can you tell ?


