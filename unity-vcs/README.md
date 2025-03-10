# Unity VCS

*

    | Description                                   | Platforms                                                                     |
    | --------------------------------------------- | ----------------------------------------------------------------------------- |
    | Unity Version Control client application      | Installer for Windows, Mac, Linux                                             |
    | Unity DevOps web dashboard                    | Browser                                                                       |
    | Editor plugin for Unity or Unreal game engine | Unity Editor plugin: Access Unity Editor plugin using Version Control package |

Run the installer for Unity DevOps Version Control that should have already been downloaded in an earlier step. Once installed, launch it and pick from the 2 choices shown. I always choose the Left side.

{% embed url="https://www.plasticscm.com/download/downloadinstaller/last/plasticscm/windows/cloudedition" %}
Link to UVCS Windows installer
{% endembed %}

<figure><img src="../.gitbook/assets/image (3) (1).png" alt=""><figcaption><p>The Right side will launch Gluon.</p></figcaption></figure>

You will need to log into Unity again to use the UVCS. Again, it makes sense that a developer can work form multiple companies from the same UVCS instance, so this should map to the Cloud account you intend to access. Click on the option to log in using your Unity account and it will bring up your repository instantly.&#x20;

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

{% hint style="danger" %}
Click the Settings button on the upper Right to open the UVCS preferences, pick Other Options, change Default Workspace to $HOME/workspaces or whatever location makes sense.
{% endhint %}

{% hint style="info" %}
To change from UVCS, click the preferences button and choose "Switch to Gluon".
{% endhint %}

To use UVCS from inside the Unity Editor, open Unity Version Control from the Window menu.

<figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption><p>Step one of setup was done using the Unity Cloud Dashboard</p></figcaption></figure>

Once logged in, a UVCS workspace must be created or located. Since one was created in an earlier step using the client software, it should be set to the same location here.

This prompt is a bit overloaded with options. Do not change over to Gluon at this stage.&#x20;

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption><p>too many choices!</p></figcaption></figure>

Clicking the ... button next to Repository field to see what Unity has selected by default:

<figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption><p>default settings are a Unity guess</p></figcaption></figure>

It is a better idea to choose to create a new repository in your organization that corresponds to how the same project is set up via the UVCS Cleint.
