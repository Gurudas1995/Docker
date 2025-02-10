# Docker
===========================================================================
# Docker volume
> Challanges in Data managment
    > Data reliability
    > Log Data
    > Abstraction
    > Frequent data change
    > Migrating data
> Docker volume mount types
    > Bind out --> Filesystem
    > Volume --> Docker area
    > tmpfs mount --> Memory
=========================================================================================================
# docker Networking
container are designed to be isolated, however they talks to each other using network e.g app container talks with database container to retirve data
 Docker netowork drivers
 1. bridge - default
 2. host - removes isolation between container and docker host and use host networks
 3. overlay - connect container from different host, enable sworm services to communicate each other
 4. macvlan - used mac address to assign it to container making it appear as a physical device on networks
 5. none - container diabled for all networking
================================================================================================================= 
