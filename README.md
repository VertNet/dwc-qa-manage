# dwc-qa-manage
Repository to handle the management of the Darwin Core Hour as well as the community input to the [tdwg/dwc-qa](https://github.com/tdwg/dwc-qa) repository, keeping it separate from the [Q&A repository](https://github.com/tdwg/dwc-qa)  to shield subscribers from irrelevant issues.

All notes taken during the Darwin Core Hour webinars and during the management meetings can be found at:     
[DwC Hour Team Collaborative Notes from 2018 Webinars](https://docs.google.com/document/d/1rL6KwWSs8SiNmBjkXDeJgOI2QxqIFBE0X9p9NaiSSYM/edit#heading=h.kpyjvlet70pa) (archived [2017 notes](DarwinCoreHour_Notes_2017.pdf)).

# How do we manage the DwC Q&A site?
## The 7 Steps

The processing of an issue that has been submitted through the web input form happens in a series of 7 steps. These steps are meant for us be followed so that we can be consistent in the treatment of questions and answers and so that we achieve our goal: that people get their answers! :)

So, the steps are as follows, you can also check the graph below for a summary:

**1. _New submission._** A new question gets submitted via the web-form. This question is automatically turned into an issue in the Darwin Core Questions & Answers GitHub site. It also gets labelled as “form submission”, so that we know that this issue is coming from the web-form (an issue could also come directly from GitHub).

**2. _First Labelling._** We now have to take a look at this new issue. When we do, we will label it further. First, we will label it “new”. Then, we will add other labels (categories) that indicate the type of question that was submitted. For example, if the issue says: “I’d like to know more about how to use and clean taxonomy fields”, we would add the labels “term - Taxon” and “data quality”. So, at this step, this issue will have 4 labels (“form submission”, “new”, “term - Taxon” and “data quality”).

**3. _Answering._** This is a critical step. And as such, it should be taken responsibly. 
Rule: We will consider an issue has been Answered if and only if it was FULLY addressed and we are confident that our responses are complete and accurate enough.
Of course, one might want to provide partial answers, comments, suggestions, etc., and one should do so! But we would NOT say the issue is Answered until it complies with the previous rule.
Now, if we are happy with the answer, a critical thing has to happen: the answer has to reach the person who submitted the issue. This is somewhat tricky, because the way in which that can happen depends on whether the person provided her/his email address and/or GitHub username in the web-form. So 3 possibilities:
* the person did not provide any contact information. Sadly, too bad for them, because we have no direct way to reach out to them. There’s nothing we can do.
* the person provided email address. If this is the case, and they did not provide a GitHub username, we must send the answer via email. The easiest way to do this is to answer the question by responding the email GitHub sends about the issue and add the email of the submitter to those who receive the message. Otherwise, after creating the answer in a comment to the issue in GitHub, also send that comment and a link to the GitHub issue to the email of the submitter. In doing this, we will make sure the answer gets to the person AND to the list, so that he/she now has the list address and, hence, a new way in ;)
* the person provided GitHub username. Awesome! She/he will get the answers automatically. No need for us to send it to them specifically.

**4. _Second Labelling._** Once the Answer is sent out, we will get rid of the label “new” on the issue and we will add another label: “answered”.

**5. _Documenting._** Yes, another critical step! :D Documenting means turning the answers we give into permanent documentation, which will reside in the corresponding sub-pages in the Wiki. As before, we will say an issue is Documented when all topics it raises are covered by existing or new documentation that we create. Once that is accomplished, we will label the issue as “documented”. Do NOT get rid of the label "answered", the issue should now have both "answered" and "documented".

**6. _Telling it's documented._** We are almost there… We have now answered and documented the issue. What’s left is to actually say in the issue thread that there is permanent documentation that addresses it. We will do so by posting a comment in the issue where we say “Documentation for this issue can be found in BLA”, where BLA will be the links (urls) to the corresponding Wiki subpages, we must list all that are pertinent.

**7. _Closing._** Voilà! We have closed the loop now. People got their answers and documentation has been augmented for everyone to use. Now, feel free to CLOSE the issue. Do it, don’t be shy :)





## Summary graph:
![alt tag](https://github.com/VertNet/dwc-qa-manage/blob/master/ManagementWorkflow.png)
