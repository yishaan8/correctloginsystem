Login system project
Background:

You are working on a feature branch named feature/login-system on a shared project repo. This branch is fairly active — you and your teammates have pushed several commits and made some fixes along the way.

You just finished implementing the login feature and pushed five commits labeled chronologically as A through E. Here’s a quick summary:

A: Base feature setup and project scaffolding.

B: Added UI components for login.

C: Implemented backend API integration.

D: Added form validation and error handling.

E: Minor bug fix and styling tweaks.

The Situation:

After pushing all these commits, the team discovered a critical bug introduced in commit D. The bug causes login validation to fail silently, creating confusion for users. Additionally, commit E, which you pushed as a “quick fix,” didn’t actually resolve the issue and introduced some unnecessary changes.

Your manager has asked you to fix the bug and prepare the branch for the upcoming sprint review.

Your Goals:

You need to manage the branch carefully considering the following constraints:

Commits A through E have already been pushed to the shared remote.

Other teammates might have pulled and started building on feature/login-system as well.

You want to minimize disruption to others while fixing the bug.

You want to be able to review, test, and possibly amend your recent commits before pushing changes again.

You also want the flexibility to selectively discard some changes but keep others in your local workspace for refinement.

Tasks for You to Solve:
1. Undo the bug in commit D but keep your project history clean and collaborative-friendly.

You must create a change that reverses the effects of the buggy commit but without rewriting or deleting history.

The fix should be explicitly visible in the project history.

Consider what will happen to the commit history after this fix.



2. Review the last commit E (the quick fix that failed) and prepare to improve it.

You want to remove commit E from your local history but keep its changes ready for reworking.

The changes should be kept in a way that you can easily modify the files before committing again.

No need to affect the remote branch yet — this is local cleanup before pushing.



3. You want to temporarily undo commits C and D because they introduce a complex problem you want to isolate.

You want to keep the changes made by C and D available in your working directory but unstaged, so you can carefully select which changes to include in the next commit.

You plan to rewrite history locally and will force-push only after thorough testing.



4. After some tests, you realize the changes from commits C, D, and E are completely unsuitable and want to discard them all permanently.

You want to restore the branch to the state it was at commit B, erasing all changes in your working directory and staging area related to later commits.

This action is irreversible unless you have backups.

You need to be cautious and certain that this is the best option.



Reflection Questions:

When is it better to use a strategy that adds a new commit reversing changes, versus rewriting history?

How do the different options affect your working directory and staging area?

What are the risks of rewriting history in a shared branch? How can you mitigate them?

How does keeping changes staged vs unstaged impact your workflow during fixes?

When is it absolutely necessary to discard local changes entirely, and how do you prepare for that safely?
