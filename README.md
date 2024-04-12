# sonaric-gui

sonaric-gui basic template

## Prerequisites

- [Install Monk](https://docs.monk.io/docs/get-monk)
- [Register and Login Monk](https://docs.monk.io/docs/acc-and-auth)
- [Add Cloud Provider](https://docs.monk.io/docs/cloud-provider)
- [Add Instance](https://docs.monk.io/docs/multi-cloud)

### Make sure monkd is running

```bash
foo@bar:~$ monk status
daemon: ready
auth: logged in
not connected to cluster
```

## Clone Repository

```bash
git clone https://github.com/monk-io/sonaric-gui
```

## Load Template

```bash
cd sonaric-gui
monk load MANIFEST
```

### Let's take a look at the themes I have installed

```bash
foo@bar:~$ monk list sonaric-gui
✔ Got the list
Type      Template                      Repository  Version  Tags
runnable  sonaric-gui/latest     local       -        -

```
## Check web gui

`http://localhost:44004`

## Stop, remove and clean up workloads and templates

```bash
monk purge sonaric-gui/latest
```
