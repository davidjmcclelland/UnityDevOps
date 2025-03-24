---
icon: cloud-arrow-down
---

# Cloud/Web App VCS

Much like GitHub, UVCS can be accessed and used from a browser.

When working with a distributed team it is best to set up on the web so that the result will be accessible to all without any delay required to sync up.&#x20;

1. Access DevOps->Version Control
2. Click Create Project
3. Name Project
4. Create Repository for Project Files
5. Connect Build Automation to source control
6. Return to previous page
7. Set up build configurations: click Configure, pick WebGL.
8. The default settings should appear in the editoable fields in the Basic Info page. Pick Windows 11 under Builder OS and Version.
9. Make sure Auto detect Unity Version is not checked
10. Click Next - accept STANDARD machine, click Next
11. Click Auto-build and Save configuration.
12. Click Overview (top selection below DevOps submenu)
13. Invite team members (click Invite to project) using email addresses.
14. Open Unity Hub, click New Project.
15. Select Core VR Core. Download template if necessary.
16. Name project identical to that used in step 3 above.
17. Ensure checkboxes are checked for Connect to Unity Cloud and Use Unity Version Control.
18. Open Repository details and change the name to match the repository name if it is different. It may be named the same as the project name by default.
19. The project will open in Unity Editor. Open the Unity VCS client app.
20. Make sure you are in the organization in which the project and repo were created.
21. The name of the Workspace may be shown as \[projectName] \[YY-MM-DD-##-##-\[RepoName] in UVCS and in the Unity Editor UVCS view. Click the Open Workspace icon to the Right of the name when hovered over.
22. The Assets and other folders that Unity VCS tracks will be marked as checked out. Other folders will be set to ignored automatically.
23. Click Pending Changes, add a comment and check in.
24. Click Sync to Cloud. The src repo should already be visible as \[projectName]/\[repoName]@\[userName@unity. Select it.
25. Click Add dst repo and pick Server userName@unity
26. Select the repo name that matches the name described in step 21.
27. Expand the dst repo  - it should reveal a node "Incoming branches - 1 branch" and /main node nested below it.
28. Click Pull Visible from the button bar. It should show "All branches are up to date" when finished.
29. Returning to browser, navigate to DevOps->Version Control->Repositories
30. Click the repo created in step 4: it should now contain Assets, Packages and ProjectSettings folders. The Last changeset column should show the commit messages created in step 23.

To browse project repositories, you must enter DevOps->Version Control->Repositories->\[specific repository name]->\[project name]



<figure><img src="../../../.gitbook/assets/image (3) (1).png" alt=""><figcaption></figcaption></figure>
