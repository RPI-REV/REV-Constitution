# REV :heart: Scrum

Implementing scrum in a traditional engineering environment.

## Introduction

In the past, REV has had a few major problems.

1. Lack of communication between GBM's
2. Lack of peer review on engineering items
3. Lack of general vision on projects

This document is proposing integrating the scrum framework into 
REV to overcome these issues. This _will_ require a major version 
bump of the REV constitution, and will be an amendment. In addition to
changing the constitution, it will also require several new tools
integrated into the REV workflow to facilitate scrum and the new
agile development tequiniques we adopt.

## Scrum

Please read the [Scrum Guide][scrumguide] before this section.

### Idealology

> Scrum is a framework for developing and sustaining complex products...
>
> The Scrum framework consists of Scrum Teams and their associated roles, events, artifacts, 
> and rules. Each component within > the framework serves a specific purpose and is essential
> to Scrum’s success and usage.
>
> [Scrum Guide][scrumguide]

Scrum hold itself to three "pillars"

- Transparency
- Inspection
- Adaptation

Each of these pillars defeats one the problems REV has had.

#### Transparency

> Significant aspects of the process must be visible to those responsible for the outcome. 
> Transparency requires those aspects be defined by a common standard so observers share 
> a common understanding of what is being seen.
>
> [Scrum Guide][scrumguide]

This addresses the issue of communication in REV. There have been many times where the average
member may have been doing some small, fairly trivial task _without_ asking anyone else 
about how it interfaces with the rest of the product, or even it's final application!
Situations like these often create issues where significant portions of work have to be
redone, or future work must deviate from the plan. In these scenarios, our team hinders 
itself from delivering a product effectively.

#### Inspection

> Scrum users must frequently inspect Scrum artifacts and progress toward a 
> Sprint Goal to detect undesirable variances...  Inspections are most beneficial 
> when diligently performed by skilled inspectors at the point of work.
>
> [Scrum Guide][scrumguide]

As a team, we have always prided ourselves upon the fact that _we_ design our cars. 
Unfortunately, in the past few years our independence has become one of our greatest downfalls.
Facing the facts, we as a team have failed at keeping our own work to a certain quality.
It is time we begin to act as our own QA team, and leave our blind faith in our members behind.
Scrum emphasizes incremental inspection of our own work, and holding ourselves responsible for it.
Properly implementing this will require a few factors, namely _peer design review_, and _testing_.

#### Adaptation

> If an inspector determines that one or more aspects of a process deviate outside acceptable limits, 
> and that the resulting product will be unacceptable, the process or the material being processed 
> must be adjusted.
> 
> [Scrum Guide][scrumguide]

The REV of 2014-2015 was a perfect example of failing in plain sight. Plans changed quickly, and 
desicions for the product were not made by the right people, causing issues to propagate across the 
team, resulting in a half-baked product. There is an urgent need for central management of the 
product on the team, and scrum so elegantly incorporates it.

### The Scrum Team

> The Scrum Team consists of a Product Owner, the Development Team, and a Scrum Master. 
> Scrum Teams are self-organizing and cross-functional. Self-organizing teams choose how best 
> to accomplish their work, rather than being directed by others outside the team.
> 
> [Scrum Guide][scrumguide]

These positions may be shared across teams, for example an Electronics Team could share a 
Scrum Master with a Drivetrain Team.

#### The Product Owner

> The Product Owner is the sole person responsible for managing the Product Backlog.
>
> Product Backlog management includes:
> - Clearly expressing Product Backlog items;
> - Ordering the items in the Product Backlog to best achieve goals and missions;
> - Optimizing the value of the work the Development Team performs;
> - Ensuring that the Product Backlog is visible, transparent, and clear to all, and shows 
>   what the Scrum Team will work on next; and,
> - Ensuring the Development Team understands items in the Product Backlog to the level needed.
>
> The Product Owner may do the above work, or have the Development Team do it. However, 
> the Product Owner remains accountable.
> 
> The Product Owner is one person, not a committee. The Product Owner may represent the desires 
> of a committee in the Product Backlog, but those wanting to change a Product Backlog item’s 
> priority must address the Product Owner.
>
> [Scrum Guide][scrumguide]

The Product Owner is the fearless leader of what goes into the product. It is their sole desicion 
on what the final product turns out to be. There may be a lot of influences on the desicions, but
ultimately the power lies in this person. This ties into the Adaption pillar, as well as REV's
third problem.

#### The Scrum Master

The Scrum Master is a servant-leader for the Scrum Team. The Scrum Master helps those outside the Scrum Team understand which of their interactions with the Scrum Team are helpful and which aren’t. The Scrum Master helps everyone change these interactions to maximize the value created by the Scrum Team.

> ##### Scrum Master Service to the Product Owner
> The Scrum Master serves the Product Owner in several ways, including:
> - Finding techniques for effective Product Backlog management;
> - Helping the Scrum Team understand the need for clear and concise Product Backlog items;
> - Understanding product planning in an empirical environment;
> - Ensuring the Product Owner knows how to arrange the Product Backlog to maximize value;
> - Understanding and practicing agility; and,
> - Facilitating Scrum events as requested or needed.
>
> ##### Scrum Master Service to the Development Team
> The Scrum Master serves the Development Team in several ways, including:
> - Coaching the Development Team in self-organization and cross-functionality;
> - Helping the Development Team to create high-value products;
> - Removing impediments to the Development Team’s progress;
> - Facilitating Scrum events as requested or needed; and,
> - Coaching the Development Team in organizational environments in which Scrum is not yet fully adopted and understood.
>
> ##### Scrum Master Service to the Organization
> The Scrum Master serves the organization in several ways, including:
> - Leading and coaching the organization in its Scrum adoption;
> - Planning Scrum implementations within the organization;
> - Helping employees and stakeholders understand and enact Scrum and empirical product development;
> - Causing change that increases the productivity of the Scrum Team; and,
> - Working with other Scrum Masters to increase the effectiveness of the application of Scrum in the organization.
>
> [Scrum Guide][scrumguide]

Together with the Product Owner, these two roles can be seen as the breakup of our current Project
Manager. The Scrum Master makes sure we stay on track, and the Product Owner helps us accomplish 
our goals. These roles are both __non-technical__. It is important the distiction is made, because 
the development process is meant to be left to the Development Team to allow for maximum creativity and
freedom to apply new ideas, as well as provide a speration of ideas and implementation.

#### The Developent Team

The Development Team consists of the rest of the Scrum Team. As mentioned before, these teams are
_self-organizing_. This means the Scrum Master and Product Owner do not have a say in how they operate.
In the past, REV has never operated like this. We have always enforced a somewhat strict model on Systems, 
and left the rest to the System Lead. Altough this isn't a bad idea, it disagrees with scrum. One of the 
major ideas of scrum is that it must be used in its entirety, so adopting scrum would probably spell an
end to the idea of Lead-Assistant Lead rule.

## REV & Scrum

### Problem with REV's Structure

The main issue with how the REV team is structured is that it is entirely focused on purchasing. 
The sole reason for leads meeetings in the 2014-2015 year was for purchasing items for the car. 
There are better ways to structure the team to integrate scrum, and to better represent exactly what we want out
of the Leads.

### Integrating Scrum

Integrating scrum into REV will take a considerable amount of work. One of the most controversial
tasks is the mapping of our current Officers and Leads to new positions under the framework. The 
ideas in this section will probably be heavily debated, but whatever.

#### The Project Manager

REV is a very project-oriented club, as the goal of many members is to learn in the process of our
projects. In the past, we have only had one project per year. As REV has grown though, our team has
began taking on two projects per year. A single "Project Manager" for _two_  projects doesn't make sense.
To effectively manage the project, it should be the sole concern. The idea of two Project Managers has been 
tossed around, and that fits scrum perfectly. One Product Owner per product. So the traditional role of
Project Manager would transition to Product Owner, and the amount of Product Owners would vary depending on
the amount of products. 

The main difference here is that __the Product Owner is not technical__. The Product Owner should not be making
any technical desicions for the team at all. It is a very important distiction because it lets the team 
working on the product use what best suits them, rather than what management decides. This marks an important 
point, because all of REV's Project Managers have been some of the most hands-on members of the team.

#### The Scrum Master

The Scrum Master will be a new role for REV. It is common for a company to share a Scrum Master between teams, 
because their primary concern isn't the product, but how the teams themselves are functioning. In addition, 
they can provide a common link across many teams. This role is also non-technical.

#### Leads

Leads will remain as is, one per team. The reason for keeping leads is that they provide a good contact point 
and can provide central knowledge for the team. The difference here is that it will not be the Lead's job 
to manage that team, but instead the job of the team itself. The Lead will still do huge amounts of work, 
as well as help others with their tasks. It is not their job to delegate tasks though, as members should take 
the tasks themselves, emphasizing how the team is self-organizing. Leads will be appointed by a vote of Officers.

#### Assistant Leads

This is kind of a grey area, but the Assistant Lead will no longer formally exist. I believe this is 
the correct course because it will emphasize how the teams self-organize. The Lead may feel free to 
designate one or more persons as Assistant Leads, but they will not exist as far as the Constitution
is concerned.

#### Officers

A variable number of Officers in a club isn't a good thing. The management should be a fairy stable 
place. For this reason, the position of Scrum Master will be made an officer. This is done because 
it gives a view of how the projects are going for the current leadership, it puts someone on the project-facing
side of REV into the desicion making process for Leads, and give balance for elected officals, reducing the 
number of appointments made.

The role of Product Owner will _not_ be an Officer because there are a varible number of them, and if a new project
is started mid-year, and new Officer should not come on board.

#### Leadership

The Leadership will be the President, Vice President, Project Manager(s), and Leads.

[scrumguide]: http://www.scrumguides.org/scrum-guide.html "Scrum Guide"
