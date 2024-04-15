![image](https://github.com/achann297/security-groups/assets/162517715/a9386e6b-ea3e-44c2-9d25-d3a750612d62)



<h1>Security Groups and Permissions</h1>
Users, Admins, or Guests on a domain can be set to a certain group and have set permissions added to them through the domain controller. It can be done through both Windows 10 or Windows 11. In this example, Windows 11 will be used to show how to add permissions to a group.

<h2>Giving Read Access to a Guest Account.</h2>

![image](https://github.com/achann297/security-groups/assets/162517715/c8ad17ec-dea1-4215-a817-564e14cb00fc)

A sample folder is created to show how to edit permissions.
- Right click on the sample folder, and click properties.
- Click on the Security tab
- In the Security tab, there is a button that says edit in the middle where it says "To change permissions, click Edit."

![image](https://github.com/achann297/security-groups/assets/162517715/e6ffa48e-c7dd-4cc9-945c-e1df52cc7572)

- In the edit screen, click add to add a new group or username
- In the blank box at the bottom, type in "Guest" and click OK.
- Now in the "Group or user names" box, Guest should be added as a user.

![image](https://github.com/achann297/security-groups/assets/162517715/ddf60659-bd8b-49ae-b4fe-7bf5c22070b3)

- Now that user is added, permissions can be set for Guest in the box below.
- Read & Execute are selected as default, the permissions that will be done for guest for this folder will be read only.
- De-select Read & Execute and make sure "Read" is the only selection on Allow.
- Click Apply and hit ok, then hit ok again to close the folder properties

![image](https://github.com/achann297/security-groups/assets/162517715/eae8dd64-e078-4073-bfd1-382d28db7cba)

Anything that is created in the folder, for example a Word Document, can now be accessed to Guests but only with the option to read the file. This means the guest users cannot edit the file or delete the file at all, thus allowing the group of guests to read a document without affecting the file itself.
