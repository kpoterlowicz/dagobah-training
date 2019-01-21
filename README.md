![gat_pennstate_logo_wtext.png](docs/shared-images/gat_pennstate_logo_wtext.png)
# Intro to Galaxy Administration @ Pennsylvania State University

**Monday 1/28/2019 - Friday 2/1/2019**

jump to [Monday](#monday) | [Tuesday](#tuesday) | [Wednesday](#wednesday) | [Thursday](#thursday) | [Friday](#friday)

Built slides have [an index](https://galaxyproject.github.io/dagobah-training/2019-pennstate/).

Join the chat at https://gitter.im/dagobah-training/Lobby

[Galaxy Training material](http://galaxyproject.github.io/training-material/)

### Location

TBA, State College, Pennsylvania, USA

## Training VM instances

TODO fill this section

List of training instances is available in [TODO]. Please pick one instance and enter your name in the user column.

2 cores, 4 GiB memory, and 20 GiB disk, Ubuntu 16.04

We are using instances from the [Jetstream cloud](https://jetstream-cloud.org/), image ID _acb53109-941f-4593-9bf8-4a53cb9e0739_.

## Timetable

_Timetable with sessions and material will be continuously updated towards the workshop._

### Basic Sessions

#### Monday
**28th January**

| **Time** | **Topic** | **Links** | **Instructor** |
| -------- | --------- | --------- | ----------- |
| 08:30 | Registration | | |
| 09:00 | Welcome and introduction | [Slides](https://galaxyproject.github.io/dagobah-training/2019-pennstate/00-intro/intro.html) | All |
| 09:20 | Deployment and platform options | [Slides](https://galaxyproject.github.io/training-material/topics/admin/tutorials/deployment-platforms-options/slides.html#1) | (M) |
| 9:45 | Intro to Ansible | [Slides](https://galaxyproject.github.io/dagobah-training/2019-pennstate/14-ansible/ansible-introduction.html#1) |  |
| 10:45 | Break (coffee & snacks) | | |
| 11:00 | Basic Galaxy server | [Exercise](https://github.com/galaxyproject/dagobah-training/blob/2019-pennstate/sessions/14-ansible/ex2-galaxy-ansible.md)|  |
| 12:30 | Lunch (catered) | |
| 13:30 | Gearing towards production | [Slides](https://galaxyproject.github.io/dagobah-training/2019-pennstate/03-production-basics/production.html), [Exercise](sessions/03-production-basics/ex1-first-steps.md)| (N) |
| 13:45 | PostgreSQL | [PostgreSQL Slides](https://galaxyproject.github.io/dagobah-training/2019-pennstate/03-production-basics/databases.html), [PostgreSQL Exercise](sessions/03-production-basics/ex2-postgres.md) |
| 14:30 | NGINX | [NGINX Slides](https://galaxyproject.github.io/dagobah-training/2019-pennstate/03-production-basics/webservers.html), [NGINX Exercise](sessions/03-production-basics/ex3-nginx.md) | (N) |
| 15:00 | Extending your installation: FTP, SMTP, and more | [Slides](https://galaxyproject.github.io/dagobah-training/2019-pennstate/06-extending-installation/extending.html), [Exercise](sessions/06-extending-installation/ex1-proftpd.md) | (M) |
| 15:35 | Break (coffee & snacks) | | |
| 15:45 | Reference Data | [Slides](https://galaxyproject.github.io/dagobah-training/2019-pennstate/05-reference-genomes/reference_genomes.html), [Exercise](sessions/05-reference-genomes/ex1-reference-genomes.md) | (S) |
| 18:00 | Close Day 1 | |  |


#### Tuesday
**29th January**

| **Time** | **Topic** | **Links** | **Instructor** |
| -------- | --------- | --------- | ----------- |
| 09:00 | Welcome and questions | | |
| 09:15 | Ephemeris | | (J)(M)|
| 09:30 | Managing Galaxy tools | [Exercise](sessions/04-tool-shed/ex-tool-management.md) | (M) |
| 10:30 | Users, Groups, and Quotas | [Slides](http://galaxyproject.github.io/training-material/topics/admin/tutorials/users-groups-quotas/slides.html) | (M) |
| 10:50 | Break (coffee & snacks) | | |
| 11:00 | Introduction to the Galaxy Tool Shed: Identifying and installing well-defined tools | [Slides (Shed)](https://galaxyproject.github.io/dagobah-training/2019-pennstate/04-tool-shed/shed_intro.html), [Slides (Tools)](https://galaxyproject.github.io/dagobah-training/2019-pennstate/04-tool-shed/tool_installation.html), [Slides (Dependencies)](https://galaxyproject.github.io/dagobah-training/2019-pennstate/04-tool-shed/tool-dependencies.html)| (H)(S)(M) |
| 12:00 | Lunch (on your own) | | |
| 13:30 | Improving the web serving experience with uWSGI | [Slides](https://galaxyproject.github.io/dagobah-training/2019-pennstate/10-uwsgi/uwsgi.html), [Exercise](sessions/10-uwsgi/ex1-uwsgi.md) | (N) |
| 15:45 | Controlling Galaxy with systemd and supervisor | [Slides](https://galaxyproject.github.io/dagobah-training/2019-pennstate/11-systemd-supervisor/systemd-supervisor.html), [Exercise](sessions/11-systemd-supervisor/ex1-supervisor.md) | (N) |
| 16:30 | Using and configuring external authentication services | [Slides](https://galaxyproject.github.io/dagobah-training/2019-pennstate/13-external-auth/external-auth.html), [PAM Auth Exercise](sessions/13-external-auth/ex1-pam-auth.md), [Upstream Auth Exercise](sessions/13-external-auth/ex2-upstream-auth.md) | |
| 17:00 | Close Day 2 | |  |


### Advanced Sessions

#### Wednesday
**30th January**

| **Time** | **Topic** | **Links** | **Instructor** |
| -------- | --------- | --------- | ----------- |
| 09:00 | Welcome and questions | | |
| 09:15 | Exploring the Galaxy job configuration file | [Slides](https://galaxyproject.github.io/dagobah-training/2019-pennstate/15-job-conf/job_conf.html) | (J) |
| 09:45 | Connecting Galaxy to a compute cluster | [Slides](http://galaxyproject.github.io/training-material/topics/admin/tutorials/connect-to-compute-cluster/slides.html), [Exercise](http://galaxyproject.github.io/training-material/topics/admin/tutorials/connect-to-compute-cluster/tutorial.html) | (N) |
| 10:20 | Break (coffee & snacks) | | |
| 10:40 | Compute cluster continued | | |
| 12:00 | Lunch (catered) | | |
| 13:00 | Storage management and using heterogeneous storage services | [Slides](https://galaxyproject.github.io/dagobah-training/2019-pennstate/19-storage/storage.html), [Exercise](sessions/19-storage/ex1-objectstore.md) | |
| 14:00 | Using heterogeneous compute resources | [Slides](https://galaxyproject.github.io/dagobah-training/2019-pennstate/17-heterogenous/heterogeneous.html), [Exercise](sessions/17-heterogenous/ex1-pulsar.md) | |
| 15:00 | Break (coffee & snacks) | | |
| 15:20 | compute resources continued | | |
| 17:00 | Close day 3 | |  |


#### Thursday
**31th January**

| **Time** | **Topic** | **Links** | **Instructor** |
| -------- | --------- | --------- | ----------- |
| 09:00 | Welcome and questions | | |
| 09:15 | Containerize all the things: Galaxy in Docker and Docker in Galaxy | [Docker Slides](https://galaxy.slides.com/bgruening/the-galaxy-docker-project), [Conda Slides](http://galaxy.slides.com/bgruening/deck-7#/), [Galaxy Docker tool example](https://github.com/apetkau/galaxy-hackathon-2014/tree/master/smalt)| (J) |
| 10:45 | Break (coffee & snacks) | | |
| 11:00 | Running Ethercalc in Galaxy with Galaxy Interactive Environments | **EXERCISE** | |
| 12:00 | Lunch (catered)| | |
| 13:00 | Cloudbursting | **SLIDES** | |
| 14:00 | Server monitoring and maintenance | [Slides](http://galaxyproject.github.io/training-material/topics/admin/tutorials/monitoring-maintenance/slides.html), [Exercise 1](http://galaxyproject.github.io/training-material/topics/admin/tutorials/monitoring-maintenance/tutorial.html), [Exercise 2](sessions/22-troubleshooting/ex1-sentry.md)  **GRAFANA** **SENTRY**| (H) |
| 15:15 | Break (coffee & snacks) | | |
| 15:30 | monitoring & maintenance continued | | |
| 17:00 | Wrap up and close | | |


#### Friday
**1st February**

| **Time** | **Topic** | **Links** | **Instructor** |
| -------- | --------- | --------- | ----------- |
| 09:00 | Welcome and questions | | |
| 09:15 | Upgrading to a new Galaxy release | [Slides](https://galaxyproject.github.io/dagobah-training/2019-pennstate/08-upgrading-release/upgrading.html) | (M) |
| 10:00 | Break (coffee & snacks) | | |
| 10:15 | What's newer than year? | **SLIDES** | (N) |
| 12:00 | Lunch (catered) | | |
| 13:00 | When things go wrong: Galaxy Server Troubleshooting | [Slides](https://galaxyproject.github.io/dagobah-training/2019-pennstate/22-troubleshooting/troubleshooting.html) | (N) |
| 15:00 | Wrap up and close | | |

### Instructors

* (S)imon Gladman - Melbourne Bioinformatics, University of Melbourne, Australia
* (H)elena Rasche - ELIXIR Galaxy WG, Elixir Germany, de.NBI, University of Freiburg, Germany
* (N)ate Coraor - Galaxy Project, Penn State University, USA
* (J)ohn Chilton - Galaxy Project, Penn State University, USA
* (M)artin Čech - Galaxy Project, Penn State University, USA
