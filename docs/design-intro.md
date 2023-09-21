## What is a Design System Versus a Style Guide?

I think before we dive into how we are tackling it this time, let's get the nomenclature right.  What we need is a Design System not just a unified StyleGuide. The difference is that a Design System (DS) is repeatable components with extensive guidelines on how and when to use them. In some companies, they may include code but normally it is just the documentation.  A StyleGuide is normally the real code.  And just the code.  Here is a great article on what is a Design System is and how it differs from a StyleGuide: [https://www.invisionapp.com/inside-design/guide-to-design-systems/](https://www.invisionapp.com/inside-design/guide-to-design-systems/).

## And Who Uses It - Or is it just Another Thing?

Design System or the goal to have one has sort of swept over many large corporations that often share the same problem that Axway has.  The companies have either several older applications while building new ones and have used different frameworks or have acquired different companies and suddenly face inconsistency across their platforms. The term Design System is also often called Modular Design or Atom Design which explains how to build a Design System from a UI/UX* approach.  

Design System is a thing that will stay.  Many companies have built extensive design systems that can be used off the shelf or be modified to fits another company's needs.  The most well-known DS is probably Material Design by Google: [https://material.io/design/](https://material.io/design/).  Here is though a link to some of the systems that exist out there: [https://designsystemsrepo.com/design-systems/](https://designsystemsrepo.com/design-systems/).

## What Challenges Do We Face at Axway with Implementation?

We are facing one big problem that I have not encountered at the other companies where I helped building DS.  We are short-staffed in UX and Dev.

I admit I might have been spoiled that I was used to having a team of 13 UX designers where 2 designers were product designers or UI designers (I hope everyone knows the difference between UI Design, UX Design, Information Architect and Product Design!). One designer lived design, HTML and CSS.  The other was always excited about colors, fonts, and iconography. I was also used to work with teams who had dedicated front-end developers who just focused on accessibility and implementation of the design.  

It was not surprising to me when I talked to 10-12 different developers and leads that the biggest fear was refactoring the UI.  Several people implied that they have no bandwidth to refactor the UI to a new framework. What brought the big question up how many frameworks do we have to accommodate? And the "old discussion" what framework will we be using came up. What would be the refactoring cost be?  And have they to do this again? 

## What if there is NO (or little) Refactoring?

I admit it may be a bit of a reach- but what can we do without asking teams to refactor and join the React UI developers? Not that I am pro React - but they are about 50% of the Amplify product line!

I talked to different leads again where new exciting technology concepts came up like Micro Front-ends, but that was then dismissed as too complex for where we are at.  We need to find a solution that can be framework independent.

Some companies have solved their problem with DS exactly that way. They build a DS that is framework independent.  Salesforce is probably the biggest known DS which has remained framework agnostic and their system is called the Lightning Design System. In other words, the Lightning Design System provides such as Material Design all the information and Guidelines on how to use and implement the modules but is not specific to the framework.  Now, Material Design has a React UI called Material UI.  It does not require however to use React as a framework.

## So, How Do We Get There?

We can use the Axway React UI 2016 where we can use the basic codebase as a template for many of our modules.  The style guide is pretty complex and robust.

What is missing is tons of documentation and updates to make it compliant with accessibility.  We may also want to add some bits and pieces to accommodate the responsive design.

And the challenge with it is all in React what won't be a problem for all the teams that are on the React UI, but we will have to generate a generic HTML+CSS to make it easier to import to custom frameworks. We will need help with that.

But, let's get there step-by-step.  If you are curious to check out how we are progressing on this, check it out on confluence at [https://techweb.axway.com/confluence/x/-N6dDQ](https://techweb.axway.com/confluence/x/-N6dDQ)

## References

Here are some great references for newbies in the field: [https://atomicdesign.bradfrost.com/](https://atomicdesign.bradfrost.com/) or [https://www.smashingmagazine.com/2016/06/designing-modular-ui-systems-via-style-guide-driven-development/](https://www.smashingmagazine.com/2016/06/designing-modular-ui-systems-via-style-guide-driven-development/).