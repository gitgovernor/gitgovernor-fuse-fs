# gitgovernor-fuse-fs
A Virtual Filesystem using Fuse and Git to expose the Illusion of working in a none git versioned directory

The Idea is not new but we will improve that a lot :D
- https://github.com/presslabs/gitfs

This works also with @gitgovernor/gitgovernor-fuse-git repositorys which are also not a new idea its a extra fuse-fs written to work with git at scale.


## Use cases
Here are some interristing real life use cases 

### Simple TimeTracking backend
this is a baybe born by git and the + PoO Algorytm used by DIREKTSPEED's blockchain Technology 
we simply use @direktspeed/fuse-daemon loading @gitgovernor/gitgovernor-fuse-fs to mount a remote git repo and expose it via ssh and sftp protocol then we use @direktspeed/timetracker which offers a nice cli integration 


#### DIREKTSPEED TimeTracker

```
ttime 30min
ttime start //=> if time for a project is running already shows existing running + default 
ttime stop
ttime start project-name
ttime stop project-name
ttime status
ttime -30m
ttime -30h

```
