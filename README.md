# What are RFCs?

RFCs (Requests for Comments) are intended to help make decision-making more collaborative and transparent. They are used mostly for internal solution proposals i.e. process changes, tech solutioning, and anything that is not addressing an external business or product opportunity - for which the Opportunity Canvas is more suitable.

# But I've never used github before... isn't it for developers?
There might be a bit of steep learning curve, but fear not, you won't need to use the console :) Here is a quick step-by-step on how to submit an RFC via github.

**Step 1. Prepare yourself man!**  
Although it is possible to write your RFC entirely within Github, it might be easier to use an editor where you can visualize markdown* such as [Atom](https://atom.io/) or [StackEdit](https://stackedit.io/app#).

**Note:** Markdown (the markup language used for formatting text in Github) can be a bit tricky to get the hang of if you're not used to it. Incidently, you might find helpful some tips on how to write Markdown  [here](https://help.github.com/articles/basic-writing-and-formatting-syntax/)

**Step 2. Get on with it already**  
In your text editor of choice:
1. Create a new file
2. Create a new file and paste in the contents of the `RFCs/RFC_template.md` file. Write your RFC, making sure to fill out the template.
3. Save your changes locally.

**Step 3. Submit your RFC!**  
When you've finished your master piece:
1. Go to the folder `RFCs` and click `upload file`. Find and select your RFC file.
2. Once uploaded, at the bottom, leave the short commit message `Submit RFC [title]`.
3. Select `Create a new branch for this commit and start a pull request.` and name the branch with the following naming convention: `RFC-Your-title-here`. This will split your work away from the main Master branch.
4. Click `Commit changes`. This will create a Pull Request, essentially requiring review before it can be merged back into Master.

**Step 4. Your time will come...**  
Your pull request has now been submitted and a trigger has been sent to our RFC slack channel to request review. Now is your time to sit back, and... get back to work.

**Step 5. No one is perfect.**  
People may start commenting on your PR (Pull Request for those of you less nerdy people) which you can view by selecting `Pull Requests` and choosing yours.
You can reply to comments, or you can make an amendment directly from within Github. Just edit the file and when you're done leave an appropriate short commit message summarizing the change(s) you made.
