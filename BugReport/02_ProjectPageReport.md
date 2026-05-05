## Summary (Summarize the bug encountered concisely)

    There is a typo on the Gitlab create new project page. Instead of the word "blank" in "create blank project", there is the word "black". This is incorrect and confusing.

## Steps to reproduce

1. Open GitLab website
2. Log in with a Gitlab account
3. Go to the Create new project page (URL: https://gitlab.com/projects/new#blank_project)
4. Look at the left upper square
5. Observe that the title is actually "Create black project"

## What is the current bug behavior?

    The page shows "Create black project", and referring to a project as "black" is incorrect and doesn't make sense.

## What is the expected correct behavior?

    The page should display "Create blank project", as this is the logical way to refer to a project without template.

## Relevant logs and/or screenshots

    The screenshot is in the "Image" folder under the "Bug_Screenshot.png".

## Possible fixes

    Change the corresponding string in the HTML from "black" to "blank"

## Whom do you report/ Assign To/ Tags

        /label ~bug ~reproduced ~needs-investigation
        /cc @project-manager
        /assign @qa-tester

## Priority

    Minor

    Reasoning: The bug doesn't stop users from creating projects, it is purely visual. However, it creates confusion, and should be eliminated.
