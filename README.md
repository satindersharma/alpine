# alpine



` mkdir -p /run/openrc`
`touch /run/openrc/softlevel`

`rc-service docker start`

`rc-status docker status`

### this is working

### one time

`rc-update add docker default`

### to run everytime, when you start wsl run this only
`openrc default`


`apk list --installed`


### to see all status

`rc-status`


### know the version of linux
`cat /etc/os-release`

### know th ecpu ram usage
`top`
