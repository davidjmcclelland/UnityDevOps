---
icon: cloud-arrow-down
---

# Cloud/Web App VCS

Much like GitHub, UVCS can be accessed and used from a browser.

When working with a distributed team it is best to set up on the web so that the result will be accessible to all without any delay required to sync up.&#x20;

<details>

<summary>Create Project</summary>

<img src="../../../.gitbook/assets/image (28).png" alt="Cloud Browser Environment" data-size="original">

1. Access DevOps->Version Control
2. Click Create Project
3. Name Project

</details>

<details>

<summary>Create Repository and Configure Automation</summary>

<img src="../../../.gitbook/assets/image (29).png" alt="" data-size="original">

* **Create Repository for Project Files**

- Return to overview page

* **Connect Build Automation** to source control

- Return to overview page

* **Set up build configurations**: click Configure, pick WebGL.

- The default settings should appear in the editable fields in the Basic Info page. Pick Windows 11 under Builder OS and Version.

* Make sure Auto detect Unity Version is _not_ checked

- Click Next - accept STANDARD machine, click Next

* Click Auto-build and Save configuration.

</details>

1. Return to overview page
2. **Invite team members** (click Invite to project) using email addresses.

Note that Team members must be added to the project _and_ the organization:

<div align="left"><figure><img src="../../../.gitbook/assets/image (30).png" alt="" width="359"><figcaption><p>Project members</p></figcaption></figure></div>

<div align="left"><figure><img src="../../../.gitbook/assets/image (31).png" alt="" width="375"><figcaption><p>Organization Members</p></figcaption></figure></div>

Users must also be assigned seats in your subscription:

<div align="left"><figure><img src="../../../.gitbook/assets/image (32).png" alt="" width="375"><figcaption><p>Assigned Seats: The two invited accounts can't access the Project</p></figcaption></figure></div>

1. Open Unity Hub, click New Project.
2. Select Core VR. Download template if necessary.
3. Name project identical to that used in step 3 above.
4. Ensure checkboxes are checked for Connect to Unity Cloud and Use Unity Version Control.
5. Open Repository details and change the name to match the repository name if it is different. It may be named the same as the project name by default.
6. The project will open in Unity Editor.&#x20;

<div align="left"><figure><img src="../../../.gitbook/assets/image (33).png" alt="" width="375"><figcaption><p>Unity Editor with VR Sample Scene open</p></figcaption></figure></div>

1. Open the Unity VCS client app.
2. Make sure you are in the organization in which the project and repo were created.

<figure><img src="../../../.gitbook/assets/image (34).png" alt=""><figcaption><p>UVCS App Home View</p></figcaption></figure>

1. The name of the Workspace may be shown as \[projectName] \[YY-MM-DD-##-##-\[RepoName] in UVCS and in the Unity Editor UVCS view. Click the Open Workspace icon to the Right of the name when hovered over.

<figure><img src="../../../.gitbook/assets/image (35).png" alt=""><figcaption><p>Click Open Workspace</p></figcaption></figure>

1. The Assets and other folders that Unity VCS tracks will be marked as checked out. Other folders will be set to ignored automatically.
2. Click Pending Changes, add a comment and check in.
3. Click Sync to Cloud. The src repo should already be visible as \[projectName]/\[repoName]@\[userName@unity. Select it.
4. Click Add dst repo and pick Server userName@unity
5. Select the repo name that matches the name described in step 21.
6. Expand the dst repo  - it should reveal a node "Incoming branches - 1 branch" and /main node nested below it.

<figure><img src="../../../.gitbook/assets/image (36).png" alt=""><figcaption><p>Typical sync view with changes coming from Cloud and going to cloud</p></figcaption></figure>

1. Click Pull Visible from the button bar. It should show "All branches are up to date" when finished.
2. Returning to browser, navigate to DevOps->Version Control->Repositories
3. Click the repo created in step 4: it should now contain Assets, Packages and ProjectSettings folders. The Last changeset column should show the commit messages created in step 23.

To browse project repositories, you must enter DevOps->Version Control->Repositories->\[specific repository name]->\[project name]



<figure><img src="../../../.gitbook/assets/image (3) (1).png" alt=""><figcaption></figcaption></figure>
