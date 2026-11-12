The voting application simply allows users to vote between Dogs and Cats and see the live results.

I had the environment ready before the assessment by doing some research so it was really helpful in terms of understanding how flisk works and makes it easier to manage and run local deveplopment environment.

Flisk auto discovers the services via Docker compose which is great automation and frees the developer from having to configure lot of things. It makes it really straightforward to manage the local environment. Which I know from my experience that sometimes takes days to get all the setup right.
 
I know about the basic flisk commands and how flisk works and what it is supposed to do. I also understand that diagnosis is really easy by running “flisk doctor” command.  Flisk doctor again is great because it is again a great diagnostic tool that is just 1 command away. This is really great peice of automation and helps you see tthe environment and service readiness. This again saves a lot of time.

Similarly there are other utilities also “flisk resources”, “flisk network” etc. You can see Service endpoints by running “flisk networks” command. 
 
“flisk ui” is again a great utility because it is sigle pane of glass for the local developer environment that gives you comprehensive picture without having to look for the things.

## What was hard
There were some minor challenges initially but I think that was just because of little bit unfamiliarity issue. Otherwise it all makse sense and is lot lot easier than trouble shooting. I also noticed that minor issues like network port conflicts are auto resolved by selecting alternative ports without lifting a finger. Furthermore, when working with this project “flisk up” command started all 5 services but excluded the seed because it belonged to seed profile, which again is great because this is sort of thing that a developer needs to remember and flisk seamlessly handles.

Best place to getting started with Flisk is “flisk --help”

Flisk solves one key problem we all face today, a sunstantial portion of code is being written by AI but it comes back to developer to run and verify the behavious and Flisk makes it simpler.
