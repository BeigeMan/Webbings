# 2D Illustration of Swarm-based Insect Mating

 Swarm-based mating of insects, such as midges, typically involves
  groups, predominantly of males, centred over some marker in the
  terrain. Swarming increases the chances of a successful encounter with
  patrolling females that are attracted to the swarm. They enter it
  briefly, mate in flight, and eventually drop from the swarm to lay
  eggs elsewhere, and then expire. During this winged phase, the insects
  do not feed, so their lifetimes depend on their internal resources.

  This code gives a biologically plausible illustration of these
  features using the basic 2D physics of interacting, identical
  particles. The male/female attraction is an adjustable inverse-square
  law, reflecting the acoustic communication used in nature. We use an
  adjustable linear law for the attraction to a swarm marker. Male/male
  attraction, which is thought not to be a big factor in the swarm, is
  here turned off by default, but can be added as an adjustable
  inverse-square law.  (Above a critical strength of this attraction, 
  mob clustering will occur in the swarm.) Self-propulsion is
  accounted for by setting a minimum velocity in the swarm. The maximum
  velocity is adjustable. Ageing is accumulated individually for the
  particles from the number of flight maneuvers made: matings, take-offs
  from ground, and close encounters. These details are fixed but the
  maximum lifetime of a particle is adjustable. Expired or egg-laying
  females drop from the swarm and disappear from the scene. Expired
  males collect as debris around the marker.

  The code is fully self-contained HTML5/CSS3 JS, compatible with
  up-to-date browsers. Chrome works best. Performance depends on the
  hardware.
