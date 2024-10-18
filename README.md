Experitest - SRS Server ansible role

![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

This role will install \ uninstall srs service on linux os hosts.

Requirements
------------

* [ansible-role-java8](https://github.com/nholuongut/ansible-role-for-java8) must be installed on all machines. <br>
* Supports linux os hosts only.

Role Variables
--------------

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-----:|:-----:|
| state | should the application be present or absent | present, absent | present | no |
| app_version | application version to install | string | 20.11.130 | no |
| server_port | port number for the server | number | 8090 | no |
| extra_application_properties | additional props to be override in application.properties file | dict | {} | no |
| extra_agents_xml | extend agents xml configuration | dict | {} | no |
| installation_root_folder | the root folder in which the application will be installed under srs-{version} folder | string | for linux: /opt/Experitest | no |
| java_version | java jre version to install | string | 1.8.0_221 | no |
| custom_download_url | custom url to download the installation from (zip format) | string |  | no |
| start_after_install | should application start after installation is completed | boolean | True | no |
| clear_temp_folder | remove temp folder after installation | boolean | False | no |
| clear_before_install | removing old installation before installing new version | boolean | False | no |

Example Playbook
----------------

#### [see working example](/example)

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟