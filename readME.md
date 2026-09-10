Uyiosa Nehikhuere

# Reflection

## Widget Tree, State, and Lifecycle

What surprised me most was seeing how a small change in state can cause Flutter to rebuild the relevant part of the widget tree. The widgets themselves are not permanent screen elements; Flutter uses them to describe what the interface should look like and then updates the display when the state changes.

The concept that took the longest to click for me was the difference between stateless and stateful widgets. It finally made sense when I understood that a `StatelessWidget` depends only on the values it receives, while a `StatefulWidget` can keep changing information in its separate state object. Using `setState()` made the connection clear because changing the state tells Flutter to build the UI again with the new values.

## GitHub Workflow

The least familiar part of the GitHub workflow was working with branches, commits, and pull requests while coordinating changes with another person. I worked through it by practicing the sequence of creating a branch, making a focused commit, pushing it, and reviewing the pull request before merging. Clear communication about which files each person was editing also helped reduce confusion.

## What I Would Do Differently

If I rebuilt this activity from scratch tomorrow, I would agree on branch names, file ownership, and a commit plan before starting. I would also make smaller commits, test each change before pushing it, and communicate earlier when I was unsure about a design or implementation choice.

## Peer Feedback

One contribution from my teammate that was genuinely helpful was helping discuss and organize the GitHub workflow before changes were merged. This made it easier to understand what had changed and reduced the chance of accidentally overwriting each other's work.

One piece of constructive feedback is that my teammate could communicate progress and possible blockers a little earlier. Short updates while working would make it easier to coordinate tasks and respond before a small issue becomes a larger one.

One thing I learned from watching my teammate approach a problem was the value of breaking the task into smaller steps before writing code. That approach made the work easier to review and helped keep the solution focused.

When we had disagreements or possible merge conflicts, we talked through the differences, compared the code, and agreed on the version that best matched the activity requirements. Next time, I would pull the latest branch more frequently and resolve conflicts sooner instead of waiting until the end of the activity.