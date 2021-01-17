Let's assume that the application is coded with Python.

Specific tools for linting could be Flake8, Pylint and pycodestyle. For testing, we can use Python's own unittests, pytests or integration tests. The unittests have some nice ready-made commands such as assert*(). In terms of building packages, python-build or wheel can be exploited.

Continuous integration service can be set up with Jenkins, GitHub Actions, CircleCI, Travis etc. There are many good options from which to deside.

Different continuous integration setups have its own pros and cons. Self-hosted environments provide us freedom and scalability. The downside is that we must create our own plugins if they don't exist and we want to try some different technology. That takes time or new workers must be hired. However, that is also the positive side: we have the freedom to build almost whatever we want. The cloud-based environments are more limited: they provide some ready-made plugins but not for every case. Cloud-based environments can also be expensive with a large team, but they provide simplicity. In self-hosted environments, we have to ourselves take care of it's maintenance.  

With a team of 6 people, it's up to them to decide whether they take a self-hosted environment or cloud-based environment. It can depend on the skill level, interest, technology and time of the team members: do they have time to take care of the maintenance of the self-hosted environment or do they just use cloud-based ready and more limited environment.