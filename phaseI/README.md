# Phase I: Analyzing Users, Competitors, and Initial Designs <br>
## Student Scheulder UX Team <br>
*Avery Pound* <br>
*Austin Devine* <br>
*Dominic London* <br>

<img src="https://user-images.githubusercontent.com/79026876/193378027-05cbc062-d08a-41ef-acef-65f18c07fd07.jpeg" width="368"/>

# Methods <br>


## Exploratory Competitive Analysis <br>


| Product              | Strengths                                                                                                                                                                | Weaknesses                                                                                                                                          | Quality | Price | Platform             |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------- | ------- | ----- | -------------------- |
| CSU Chico's product  | can schedule                                                                                                                                                             | confusing                                                                                                                                           | 6       | NA    | web, mobile          |
| Starbucks' Teamworks | easily view schedule<br>Request change or swap shifts<br>Offer shifts for swap<br>Notifications when shifts offered or requested<br>Request time off<br>Direct messaging | Changes not always reported to users<br>Cannot see coworkers' schedules<br>Interface feels clunky<br>Not integrated with exta-curricular activities | 8       | NA    | web, mobile, desktop |
| BlackBoard           | Highly customizable                                                                                                                                                      | Too many convoluted features                                                                                                                        | 4       | NA    | web, iOS, Android    |
| Canvas               | Clarity of features                                                                                                                                                      | less fully featured                                                                                                                                 | 6       | NA    | web, iOS, Android    | 


## Hueristic Evaluation of Chico State's Scheduler <br>
### Visibility of System Status | 4
#### misc
- calling it "Scheduler Builder (Scheduler)" is redundant 
   and kind of a chore to read the whole line
- system status is NOT readily visible
- long process to see if a given class's time conflicts with your schedule

#### Tabs
- must constantly swap between different programs in the system 
	- one for seeing classes offered that semester
	- the other is for seeing the scheduling possibilities
- the webapp does not allow for more than one tab to be used at a time
	- this causes all sorts of annoying issues

#### Match system & real world | 5
- the calendar/planner-looking part of the application maps nicely
   to what we are used to when scheduling. It should be used much
   much more extensively, only comes into play for maybe 20-28%
- not very intuitive scheduling, mostly just walls of text

#### User control and freedom | 4
- the user has all the control, however that control feels heavily limited
- the only-one-tab issue mentioned earlier makes it challenging to 
   keep the classes you are wanting to reference readily available. 
- user can add, drop, waitlist, and do other things for a class
   so it wins some points there

#### Consistency and standards | 2
- "enroll in class" is the name of the page where you can *see* 
   offered courses, but you can *not enroll* through this page. 
- "schedule builder (scheduler)" is not only confusing to read,
   but further muddies the water on what page does what
- "shopping cart" is the page where we can see classes in our "cart"
   but not yet acted on. This seems lazy. I don't shop for classes with a cart.
   I think the phrasing used is important, and this degrades the whole 
   experience by bringing up strange feelings that I don't associate with school.

#### Error prevention | 6
- there's a decent feature which blocks students 
   from scheduling overlapping courses
- that same function acts differently for advisors/faculty
	- yes, this is expected
	- i think too much trust is placed in faculty knowing the program thoroughly
	- my advisor scheduled me with overlapping courses accidentally
- gets over a 5 because I have never accidentally spent money on the site

#### Recognition rather than recall | 2
- the web app completely relies on users to be writing down information
- by not allowing the user to access the website from multiple tabs, 
   they completely prevent the user from easily navigating the process
- i would prefer some persistent variables off to the side of the screen, 
   maybe somewhere i could add classes just to hold for later or for different tabs
- i find myself having to write down all the classes and times im interested in 

#### Flexibility and efficiency of use | 2
- there is no flexibility or added efficiency the more you know the program
- sheer speed of doing the exact same process can help,
   but after years of interacting with the service I've never
   found it to be quick

#### Aesthetic and minimalist design | 5
- the page is reasonably minimal
- the use of *red* is a bit garish, distracting
- the use of *white* backgrounds is harsh on the eyes
	esp when many users, especially students, use "dark mode"
- there is only relevant info, however it is not laid out very well


#### Help users recover from errors | 4
- i've run into several errors where the page freezes
  the only solution being to reload the page and start over
- the use of the site is so limited in scope that it prevents most errors
- the guard rails are very strong and high

#### Help and documentation | 1
- I've found that the website is devoid of a help page
- No one is currently iterating on the software, so it is only getting worse
   as it interacts with newer and newer operating systems and browsers
- No documentation that I can find

---

# Findings <br>
## Competitive Analysis Findings<br>

From our close inspection of an array of similar applications we have found some features and concepts that may benefit us moving forward. <br>
We looked at the Stabucks _Teamworks_ application. It is what they use to run schedules at almost all franchises of the massive chain. <br>
While it is not directly designed to schedule students, it is a scheduling application and while it is used largely by a college-aged audience.<br>
The average age of a Starbucks barista is 24. <br>

We found that the ability to 'swap' scheduled events was a useful feature, and potentially one students could take advantage of. <br>
There is a simple waitlist system in place at our school, California State University Chico. <br>
But a more complex system wherein students could add and drop classes conditionally, with dynamic parameters, could benefit students. <br>

The ability to request time off in _Teamworks_ is not so dissimilar to our proposed functionality<br>
of being able to add extra-curricular events to your school scheduling application. This way you <br>
will get immediate feedback on time conflicts. We want to avoid giving our users any unneunnecessary headaches. <br>

## Heuristic Findings

By studying closely the process by which we ourselves schedule and navigate classes, <br>
we came to some harsh realities about the user experience. <br>

We found that a majority of the time the user is kept in the dark about their prospective schedule, <br>
and has a very limited view of the system they are interacting with. <br> 
The clunky site we are used to offers no suggestions when things go arwy, <br>
and you must walk back your steps very carefully if you encounter an error. <br>

The student must keep a working calendar in their head, <br>
and keep track of what classes are offered when, <br>
because the scheduling application helps them with none of this. <br>
The extremely limited view at any given time tells the student very little.<br>


## Personas and Scenarios Findings

After precisely narrowing down our user base, and discussing extensively about how they live, <br>
we constructed detailed scenarios for our well-imagined users. <br>
We found that a very common use case is students who must keep track of their extra-curricular activities <br>
on their own while navigating the system. This is _normal_ but does not have to be. <br>
We found that what our users _really_ care about, is a scheduling tool <br>
which takes theie whole life into account and not just a few classes. <br>

## Sketches and Diagrams Findings

Our resident artist, Austin Devine, had a lot to teach us about design. <br>
The evolution of our visual representations can be seen in our "Sketches and Daigrams" page. <br>
By not just imagining, but seeing with our own eyes a layout and potential look and feel for the page, <br>
we learned a lot about usability of our product. <br>

We found that it is really easy to clutter a page. We care a lot about transparency and <br>
giving the user the most power we possibly can. This approach, however, can lead <br>
to the page becoming completely filled with not-totally-necessary information. <br>
This creates a lot of _visual noise_ which makes it even harder to complete the task at hand. <br>
With elegant design and dynamic web features, we can bring the power of computation <br>
into the hands of students. They should be able to see what is relevant when it is relevant, <br>
and not have to search all over the school's website for information we could easily provide! <br>

# Conclusions & Recommendations  <br>
Information is king. <br>
We want to give the user power. We want them to feel like they see all their choices. <br>
Sometimes scheduling classes can impart "fear of missing out" as the student thinks <br>
they may be missing some great combination of classes that would be perfect for them. <br> 

We want to make things easier for students. <br>
By allowing our users to add events as they please, and block off time dynamically, <br>
we make the process of finding classes at times that work much easier. <br>

We need to completely get rid of the current system wherein a user cannot have <br>
both the class catelogue/schedule open along with their current scheduling tool. <br>
This is an obvious oversight as it is crucial when dealing with time conflicts, errors, <br>
or any other issues that may arise. <br> 

# Caveats <br>

In our competitive analysis there is a glaringly empty column, the prices. It is difficult to get an idea of what <br>
schools or companies pay for these services. We do know that some of them are paid for in a yearly flat rate, <br>
and some are paid-per-student using the service. Starbucks' _Teamworks_ is even harder to pin down a price on, <br>
as I believe it is developed 'in-house.' 

Given that we have such limited experience with other school's scheduling systems we had to go with the obvious choice. <br>
We have the most time spent and most intimate knowledge of the Chico State scheduling system, so it seems like a good choice. <br>
We recognize that this could introduce bias into our analysis as we have to use the service 'for real,' and cannot be neutral. <br>
