# Unity Build Automation

Running a build on a local development machine is a blocking task that generally takes over all available resources.

Build Automation offloads the Unity build processing to a cloud instance and frees up developers to use Unity Editor instead of waiting for a build to complete.

{% embed url="https://cloud.unity.com/home/organizations/2475807756479/projects/1860fe12-bd1d-4976-b14a-f3f7634da086/devops/overview" %}
free demo Devops landing page
{% endembed %}





| Feature                     | Description                                                                                                            |
| --------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| Notification & Alerts Panel | Sends notifications to your team whenever a new build is exported.                                                     |
| Past Build History          | Displays information such as average build time, build size, number of successful builds, and number of failed builds. |
| Configuration Panel         | Allows configuration of build targets and source control project settings.                                             |

### Automated (Static) Testing

C# scripts are compiled in the editor, so static testing is of very limited benefit to a build. It is of much more benefit to test some of the more generic and repetitive tests, like graphics performance.

### Artifact Center

Successful builds product artifacts which are tagged against the build and code change in order to run regression tests and generally keep track of an increasing number of binaries.

Artifact center supports tags, filters, searches, distribution and sharing of artifacts

Deploy game versions to a specific environment, such as the development, staging, or user acceptance test (UAT) environments.

Unity Version Control and Unity Build Automation send game files to test servers or digital stores, either manually or automatically. Set up these tools so that when a developer approves a new version of a game, that version gets deployed to the staging environment and sends a notification to QA team so that they can start downloading and testing the build right away.
