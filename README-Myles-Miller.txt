## Team Roster — In-Class 1 v3

| Member            | GitHub Username | Contribution           |
| ----------------- | --------------- | ---------------------- |
| Myles Miller      | @ozemoya        | Completed questions 1, 2, and 3 |
| Uyiosa Nehikheure | @Icecoldblack   | Completed questions 4 and 5 |

In Class 01b Reflection

What surprised you most about how the widget tree, state, or lifecycle actually behaves once you saw it applied in the app?

The most surprising part was how many parts of the screen changed together when a user selected a new tab. I knew the tab bar and page view were connected, but I did not fully understand that the TabController was also updating the label in the bottom bar. Seeing that happen in the finished app made the widget tree feel less abstract.

Which concept took the longest to click for you, and what finally made it make sense?

Controllers and lifecycle took the longest to click for me. At first, calling dispose() felt like an extra step that did not change anything visible. It made sense once I connected it to the TabController animation and listener. The controller is created when the state begins, used while the screen is open, and cleaned up when the state ends. That helped me understand why Flutter developers pair initState() with dispose().

What part of the GitHub workflow felt least familiar, and how did you work through it?

The part of the GitHub workflow I paid the most attention to was making sure the repository contained the right project files and the latest changes. I worked through it by checking the project status before committing, using clear commit messages, and confirming that the pushed repository showed the updated files. This made Git feel more like a record of the project than just a place to upload code.

If you rebuilt this activity from scratch tomorrow, what would you do differently?

If I rebuilt this activity tomorrow, I would start by writing the tab list and all four page placeholders before adding the individual widgets. That would make the tab-count relationship clear from the beginning. I would also update the widget tests as soon as I replaced the starter demo, instead of waiting until the end to discover that the old counter test no longer matched the app.

Peer Feedback and Reflection


Describe one specific contribution from your teammate that you found genuinely helpful, and why.

Uyiosa was especially helpful when we were checking the tab navigation. He looked at the app from the user's point of view and pointed out that it was important for the selected tab label and page content to stay in sync. That feedback helped me pay closer attention to how the TabController connected the TabBar, TabBarView, and bottom label.

Share one piece of constructive feedback that could help your teammate collaborate even more effectively next time.

One thing that could make the next collaboration smoother is agreeing on file responsibilities at the beginning. For example, we could decide who is handling the main app code, tests, and written responses before we begin. That would make it easier to track progress and avoid overlapping changes.

What is one thing you learned from watching how your teammate approached a problem?

Watching Uyiosa work taught me the value of testing one change at a time. Instead of changing several widgets and then trying to figure out what caused an issue, he focused on one part of the screen and checked it before moving on. I can use that approach in future Flutter projects because it should make debugging less confusing.

How did the two of you resolve any disagreements or merge conflicts, and what would you try differently next time?

We did not have a major disagreement or merge conflict during this activity. When we had different ideas about how a part of the app should work, we talked through what the assignment required and chose the option that best matched the instructions. Next time, I would commit smaller changes more often and agree on file ownership earlier so the work stays organized.
