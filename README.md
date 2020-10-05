# docker-pyinstaller-ci

PyInstaller for Windows inside Docker (using Wine). Usable for GitLab CI.

This is a very simple image built on top of [engineervix/pyinstaller-windows](https://hub.docker.com/r/engineervix/pyinstaller-windows/) ([source](https://github.com/engineervix/docker-pyinstaller)). It only removes the entrypoint script, making it possible (and very easy) to use this image in [GitLab CI](https://about.gitlab.com/gitlab-ci/).

> This is a fork of [schnouki/pyinstaller-windows-ci](https://hub.docker.com/r/schnouki/pyinstaller-windows-ci/). 
The only difference is that **schnouki/pyinstaller-windows-ci** is built on top of [cdrx/pyinstaller-windows](https://hub.docker.com/r/cdrx/pyinstaller-windows/), from which [engineervix/pyinstaller-windows](https://hub.docker.com/r/engineervix/pyinstaller-windows/) was forked.

> The parent projects use Ubuntu 12.04 / 14.04 / 16.04. The forks were created to use Ubuntu 20.04 / 18.04, and some newer python releases (patches)
