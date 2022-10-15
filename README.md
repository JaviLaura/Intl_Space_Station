# Intl_Space_Station
#After an instantaneous worldwide power outage, verbal communications with the International Space Station (ISS) have been disconnected. Fortunately the reliable Deep Space Network (DSN) is able to access some information about the state of the station. This information is accessible by API and will help us confirm the astronauts well being. Begin by verifying the identities of the astronauts currently in space and adding them to a list.

Now that we've verifed that all the astronauts are safely aboard the ISS, we need to ensure that it's still moving at the expected velocity (the ISS usually travels at around 7 km/sec. This is the speed required to remain in orbit at 400 kms altitude).

Velocity should be computed in terms of km/sec. Fetch the latitude and longitude coordinates of the ISS at two different times. Then find the difference in distance (km) and time (sec) to compute the velocity!

Note: Because of the curvature of the earth, calculating distance can be tricky. Make sure to use the distance() function to make your calculations, which takes curvature into account.

