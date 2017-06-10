# Workflow Guidelines 

## Preparation
The project has to be **prepared to a maximum**, all aspects and pages have to be thought and discussed before implementation. 
> A guide for the preparation of the project is available [here](https://github.com/Our-Company-Ltd/our-workflow/wiki/1.-Project-Preparation). 

## Files
Each project should have 2 files:
- `README.md` contains all the important information about the project
- `CONTRIBUTING.md` contains a guide for helping code, giving feedback and reporting bugs

## Issues
There are two issue types in the project lifetime: _planning & discussion_ and _feedback & bugs_.

> Every project should start with a _briefing discussion_ issue (named "briefing discussion") mentioning all requirements to start and execute the project. This issue helps filling and editing the `README.md` file.

### planning & discussion issues
* All the validated documents and remarks have to be mentioned in an issue 
* The issue will sit (opened or closed) in the first column of the project `Planning and Document Validation` and can then be moved by the assignee or project manager in other column throughout the lifetime of the project.
* All feedback and answers should be written down during the conception. Either in a general issue or in separate issues.
* Each issue should have a maximum of discriminated task marked as such in its description. 
* All the issues should be associated with the right project and **always** have at least one assignee. 
* All the issues should be associated with the right milestone. 

### feedback & bugs issues
* All feedback should be filled with a maximum of labels possible from the 1., 2. and 3. sections.
* All feedback should be assigned to someone, in case of doubt, assign to the most credible(s) team member. 
* A member that is not competent should re-assign the issue or step out of the assignee list if other members are assigned.
* Each Issue should contain a maximum of feedback and if possible a _steps to reproduce_ the behaviour.
* the reporter of the issue should check if the issue does not already exist.
* the title of the issue should be short and concise, using keywords to understand the area and the scope of the issue. (ex: _loading of image on home page_ instead of _i saw some pictures loading slowly_) 
* the description of the issues is the place to **mention people**, **other issues**, **links** and **screenshots** and longer descriptive text.
* english is preferred. 

### Lifetime of a feedback or bug issue
**Creation of the issue**
The client or the team create new issues following the guidelines. The issue is likely placed in `Triage`

**Evaluation**
The team evaluates the issue and includes it in the workflow after making sure everybody involved has a clear view of what is at stake and that the requirements from the guidelines are matched. The issue has to be placed in the project in the right column  `Planning and Document Validation`, `New` or `Ready for implementation`. After this stage, the project, milestones, priority and kind (sections 1., 2. and 3. of the labels) of the issue should be filled. 

**Discussion**
If the elements of the implementation or resolution of the issue are not obvious and require expertise from someone else, a team member with the right competencies should be assigned. If the work is outside of the scope of the agreed work with Our Company Ltd, the client should be notified and solutions should discussed with him. The issue can be marked with a label of the section 4.2 if it doesn't enter the scope of the current project.

**Ready for resolution / implementation**
The team member(s) with the right competencies is(are) assigned to the issue and is(are) then responsible for the resolution of the issue. A maximum of feedback about the resolution should be included in the feed of the issue. The issue is marked with a label of the section 4.1. The issue is placed in the column `Ready for implementation` or `Done` of the project.

**Resolution**
The resolution of the issue should be marked with the commit code if possible or any information mentioning how the issue has been solved. The issue is then assigned to the tester if it needs test or to the project manager if it needs client approbation of the resolution. The issue is placed in the column `Test` or `Done` of the project.

**Testing**
The issue should be tested and is then assigned to the project manager. The issue is placed in the column `Done` of the project. If the resolution does not pass the test, the issue is place in the column `Ready for implementation` and re-assigned to the last assignee who resolved the issue.

**Closing**
After evaluation of the resolution, the issue can be closed either by the project manager or the client. The issue is in the `Done` column of the project.
