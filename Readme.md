Step 1:
Create your paythin project

Step 2: Write a python script(any sample code)

Step 3: Create requirement File which enlist your project dependencies

Step 4: Create Github Action Folder by following command "mkdir -p .github/workflows"

(a) it will create ".github" folder and inside it , it will create the "workflows" folder.

Step 5: Add "security.yml" file to inside workflows folder.This file will be automatically detacted by "Github Action". Inside this file you can write your code about the security and add ristriction that if somemake a pull requst it will scan the dependencies.
