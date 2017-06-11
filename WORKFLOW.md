#Common workflows

##Providing info process
It is always good to have a deterministic way to understand and reproduce a problem.  
Therefore it is very helpful to have some test cases, samples of code and information about your environment.

If it is impossible to solve the problem without additional information, the issue should be marked as `need-info` to wait for new information from the author.
 
If the issue has the `need-info` tag for more than **14 days**, it should be closed as `incomplete`, but the author always can ask to reopen the issue
 

##Checking relevance process
Sometimes an issue is not actual for an author anymore: the author could find an answer somewhere else, a new version of Mocha/Node.js/dependency could solve the problem, etc.
 
 We have the **Checking relevance process** to close old issues:
 1. The issue should be marked as `probably-out-of-date`
 2. The author should be invited to the issue to comment
 3. If either the author proves that the issue is not actual or the issue does not have any updates for **14 days** - the issue should be closed 
 
#Workflows for issues

We have five types of issues:
1. Question
2. Bug
3. Feature
4. Documentation
5. Technical

##Questions
If an issue does not require any code/documentation changes, it should be marked as a `question`.  
You can find all the open questions [here](https://github.com/mochajs/mocha/issues?q=is%3Aissue+is%3Aopen+label%3Aquestion)

_TIP: Feel free to ask about everything on [Gitter](https://gitter.im/mochajs/mocha): there are more than 1500 people who can help you :-)_

###How we work with questions
1. Firstly, the issue should pass the **Providing info process**
2. Mocha has a big community and we hope that most of the questions here will be answered during the first week
3. If nobody answers for the question in 7 days, we should go into the **Checking relevance process**  
4. If the issue is actual, it should be:
    1. marked as `need-maintainer`
    2. posted to [Gitter](https://gitter.im/mochajs/mocha) once again
    3. placed to [Maintainance queue](TODO) - someone from the contributors team will answer as soon as possible
5. If 45 days have passed since the last activity, it means that (unfortunately) nobody knows the answer. The issue should be closed, but the author always can find help on [Gitter](https://gitter.im/mochajs/mocha)

##Bugs

1. Firstly, the issue should pass **Providing info process** to be sure that there is enough information to reproduce a bug
2. The bug should be placed to [the queue with not confirmed yet bugs](https://github.com/mochajs/mocha/issues?utf8=✓&q=is%3Aopen%20label%3Abug%20-label%3Aconfirmed%20)
3. Some of the maintainers should confirm or disprove the bug

Unconfirmed bugs
1. If a maintainer couldn't reproduce the wrong behaviour, the issue should be marked as `unconfirmed`
2. The author of the issue should be invited to comment the desicion 
3. If either the author proves that the issue isn't actual or the issue doesn't have any updates for **14 days** - the issue should be closed

Confirmed bugs:
1. The confirmed bug should be marked as `confirmed`
2. If nobody from the maintainance team works on this bug, the issue should also be tagged as `pr-please`
3. 
4. If 30 days have passed since the last activity, 
