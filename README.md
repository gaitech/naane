# naane
authentication should align with authorisation. 

The purpose of this investigation is to provide hyper-local resource sharing using safe-enough authentication, based on the resource being shared.

The issue, we claim, is that we don't authorise based on the object that needs access. Authenticating a Bank transaction is not the same as authenticating a user requesting a car ride. 

What if an {individual, a resource, or a state machine}  has a permaent, multi-faceted digital presence and based on the requirement of the {person, a resource or a state machine}  accessing it, the authentication challenge/mechanism changes.

A website today can either have anonymous user or a registered, logged in user. What if user was allowed much finer grained access, based on level of authentication provided, which may actually be something as obtuse and having an expired payed plan. 

as another example, lets take the case of a car ride-share. This really only requires information about where the person wants to go and whether a vehicle is available. No major checks required of either the rider or the vehicle owner. But for the same scenario, suppose the ride required is for a female after 9pm in Delhi. This would require a strict authentication mechanism of the vehicle owner as well as driver of the vehicle.
