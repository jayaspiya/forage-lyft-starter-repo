# Project Overview

Lyft is in the process of rolling out a new rental fleet in the hopes of encouraging more connected, sustainable cities across the US.

Your team has inherited an urgent project from a fellow colleague here at Lyft who had to make a pivot to a different project. The colleague was in the process of developing a component that is used by the rental fleet’s new logistics system. Unfortunately that component was only partially completed and your team’s responsibility is to now finalize that component and make it functional.

The component itself is responsible for determining whether cars in Lyft’s new rental fleet should be serviced when they are returned. The work you will do on this component will be carried through the each of the tasks within this program.

## Criteria for car servicing

The rental cars depends on the engine & the battery for car servicing.

Service Criteria are as follows:

| Parts             | Service criteria                      |
|-------------------|---------------------------------------|
| Capulet Engine    | Once every 30,000 miles               |
| Willoughby Engine | Once every 60,000 miles               |
| Sternman Engine   | Only when the warning indicator is on |
| Spindler Battery  | Once every 2 years                    |
| Nubbin Battery    | Once every 4 years                    |

There are five car models, each with a different engine-battery combination.

| Car        | Engine            | Battery          |
|------------|-------------------|------------------|
| Calliope   | Capulet Engine    | Spindler Battery |
| Glissade   | Willoughby Engine | Spindler Battery |
| Palindrome | Sternman Engine   | Spindler Battery |
| Rorschach  | Willoughby Engine | Nubbin Battery   |
| Thovex     | Capulet Engine    | Nubbin Battery   |


## Draft a new architecture
Create a new architecture that allows easy extensibility to add new service criteria.
