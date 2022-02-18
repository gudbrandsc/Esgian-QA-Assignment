# Esgian-QA-Assignment

# Recruitment task for testers

Create Python script that will test following GitHub functionality:
* listing commit comments
* creating commit comments

through GitHub API calls

### Test scenario that should be implemented:

1. Check that Auth is working as expected, and the commit is found.

2. Create some comment for commit a28ac0baa982be9b913caf40e071c8ef84fee4c0 of this repository and validate that it was created.

3. Delete a comment from from the commit, and verify that it does not exist. 

4. Check that you are unable to create a comment without any text i.e comment=""  

### Take into consideration:

* Use basic authentication for the requests.
* Finding and understanding API documentation is part of the task.
* Test server responses when sending incorrect input.

### Submitting solution

Your solution (.py) file should be sent to nils.heieren(a)esgian_com
