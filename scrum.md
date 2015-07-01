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
Unfortunately, in the past few years our indepences has become one of our greatest downfalls.
Facing the facts, we as a team have failed at keeping our own work to a certain quality.
It is time we begin to act as our own QA team, and leave our blind faith in our members behind.
Scrum emphasizes incremental inspection of our own work, and hollding ourselves responsible for it.
Properly implmenting this will require a few factors, namely _peer design review_, and _testing_.

#### Adaptation

> If an inspector determines that one or more aspects of a process deviate outside acceptable limits, 
> and that the resulting product will be unacceptable, the process or the material being processed 
> must be adjusted.
> 
> [Scrum Guide][scrumguide]

The REV of 2014-2015 was a perfect example of failing in plain sight. Plans changed quickly, and 
desicions for the product were not made by the right people, causing issues to propogate across the 
team, resulting in a half-baked product. There is an urgent need for centeral mangement of the 
product on the team, and scrum so elegently incorperates it.

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

[scrumguide]: http://www.scrumguides.org/scrum-guide.html "Scrum Guide"
