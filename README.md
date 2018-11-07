### Quick Links
[DHG RFC Board](https://github.com/auzbuckley/RFC_test/projects/1)  
Slack Channel: #dhg-rfc  
[RFC Template](https://github.com/auzbuckley/RFC_test/blob/master/RFCs/rfc_template.md)

## What are RFCs?
RFCs (Requests for Comments) are intended to help make decision-making more collaborative and transparent. They are used mostly for _internal solution proposals_ i.e. process changes, (most) tech solutioning and optimizing, job advertisements. RFCs are intended to be lightweight and relatively quick to create and review.

## How are they different from the Opportunity Canvas (IRIS)?
The Opportunity Canvas is specifically for product opportunities or what could be considered as _external_ solutions. Usually this comes in the form of new feature ideas. Essentially, the rule of thumb is: if your proposal is likely going to require coordinated effort of development teams to ship something to our customers, then this is Opportunity Canvas territory.

## Process Overview
1. Find a sponsor (this will be the person who ultimately has authority to approve your RFC). This can be your manager.
2. Write and submit your RFC
3. Briefly present your idea during Friday Reviews.
4. Respond to comments
5. Evaluate feedback with your sponsor
6. Close or Merge the RFC (Communicated during Friday reviews?)
7. If merged, your RFC will be discussed and prioritized in Product & Tech Council depending on complexity and effort.

## Getting started
There might be a bit of steep learning curve, but fear not. Here is a quick step-by-step on how to submit an RFC without the need for console skills.

**Step 1: SETUP**  
Although it is possible to write your RFC entirely within Github, it might be easier to use an editor that can visualize markdown* such as [Atom](https://atom.io/) or [StackEdit](https://stackedit.io/app#). This means you won't need to deal with commits or branches until your first draft is ready for review.

**Note:** Markdown (the markup language used for formatting text in Github) can be a bit tricky to get the hang of if you're not used to it. Incidently, you might find helpful some tips on how to write Markdown  [here](https://help.github.com/articles/basic-writing-and-formatting-syntax/)

**Step 2: WRITE**  
In your text editor of choice:
1. Create a new file and paste in the contents of the `RFCs/RFC_template.md` file. Write your RFC, making sure to fill out the template.
2. Save your changes locally.

**Step 3: SUBMIT**  
When you've finished your masterpiece:
1. Go to the folder `RFCs` and click `upload file`. Find and select your RFC file.
2. Once uploaded, at the bottom, leave the short commit message `Submit RFC [title]`.
3. Select `Create a new branch for this commit and start a pull request.`. Name the branch with the following naming convention: `RFC-Your-title-here`. This will split your work away from the main Master branch.
4. Click `Commit changes`. This will create a Pull Request, essentially requiring review before it can be merged back into Master.
5. Your pull request has now been submitted. A trigger has been sent to our RFC slack channel to request review, and a card has automatically been created in our DHG RFC Github project board. Now is your time to sit back, and... get back to work.

**Step 5: REVIEW & EDIT**  
People may start commenting on your PR (Pull Request for those of you less nerdy people) which you can view by selecting `Pull Requests` and choosing yours.
You can reply to comments, or you can make an amendment directly from within Github. Just edit the file and when you're done leave an appropriate short commit message summarizing the change(s) you made.

## Guidelines  
**Authors:** Try to keep your RFC as brief and succinct as possible  
**Reviewers:** Comments on RFCs should be constructive. If you have a concern, please offer an alternative solution if you can. If the comment thread starts to grow, go talk face-to-face.

