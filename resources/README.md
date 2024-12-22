This README.MD is included to talk about resources.


Resources in a docker container show the host resources, so what if we made it possible to show the docker container's resources

We are able to spoof the ram amount and usage.

Even if you dare to make it insanely high, if the host doesnt have the amount of ram or is still capped by "-m"

it will make the host crash/container apps will crash after exceeding the limit.



What about cpu?

You can spoof every cpu info. Again the limits apply.
