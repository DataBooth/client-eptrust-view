## EP Trust - Task/request tracking

Task and request tracking for Maxine and David Cook - [https://eptrust.org.au](https://eptrust.org.au)


TODO: https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-an-issues-only-repository

### Creating an issues-only repository

GitHub does not provide issues-only access permissions, but you can accomplish this using a second repository which contains only the issues.

1. Create a private repository to host the source code from your project. [DONE]
2. Create a second repository with the permissions you desire to host the issue tracker. [DONE]
3. Add a README file to the issues repository explaining the purpose of this repository and linking to the issues section. [DONE]
4. Set your collaborators or teams to give access to the repositories as you desire.

Note: Users with write access to both can reference and close issues back and forth across the repositories, but those without the required permissions will see references that contain a minimum of information.

For example, if you pushed a commit to the private repository's default branch with a message that read Fixes `organization/public-repo#12`, the issue would be closed, but only users with the proper permissions would see the cross-repository reference indicating the commit that closed the issue. Without the permissions, a reference still appears, but the details are omitted.
