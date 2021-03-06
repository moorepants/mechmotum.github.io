=================================
What Caused Chloé Dygert's Crash?
=================================

:date: 2020-9-29 00:00:00
:tags: bicycle, wobble, shimmy, sports, engineering
:category: outreach
:slug: dygert-crash
:authors: Jason K. Moore, Marco Reijne
:summary: Back of the napkin analysis and commentary on Chloé Dygert's 2020 UCI
          Road World Championships crash.

`Chloé Dygert`_ had a race ending crash on September 24th, 2020 in the `UCI
Road World Championships`_. The crash was caught quite clearly on video. The
bicycle starts oscillating during a right turn decent and she loses directional
control of the bicycle. She ultimately collided with a guard rail and incurred
major injuries. You can watch for yourself in the video below:

.. _Chloé Dygert: https://en.wikipedia.org/wiki/Chlo%C3%A9_Dygert
.. _UCI Road World Championships: https://en.wikipedia.org/wiki/UCI_Road_World_Championships

.. raw:: html

   <div style="text-align: center;">
   <iframe
     width="560"
     height="315"
     src="https://www.youtube.com/embed/rEzFIQmDJYU"
     frameborder="0"
     allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
     allowfullscreen>
   </iframe>
   </div>

The video has made its round on the internet and collected various commentary.
For example, on the Single Track Vehicle Dynamics discussion list there are
`several perspectives`_. As is common with videos showing oscillation of this
nature, the words "wobble" and "shimmy" are often brought up.

.. _several perspectives: https://groups.google.com/forum/#!msg/stvdy/K932UhSVOAs/uUJE83YuBAAJ

What is "wobble" and "shimmy" of a bicycle?
===========================================

The words (speed) wobble and shimmy are both interchangeably used in academic
and popular literature without a unique or definitive definition. Both terms
are used to describe higher frequency oscillations that single track vehicles
(bicycles, motorcycles, and similar vehicles) sometimes exhibit
[Wikipedia2020]_. In this case, "higher frequencies" refers to being higher
than the vehicle's weave oscillation frequency. Weave is the fundamental steer
and roll oscillation that occurs in the 0 to 4 Hz bandwidth for bicycles
traveling at speeds below 20 m/s (72 km/h, 45 mph). In addition to the
frequency differences, at higher speeds this wobble/shimmy oscillation can grow
in magnitude (unstable) whereas weave oscillations become more damped (stable)
as the speed increases.

Wobble/shimmy oscillations are attributed to the effective flexibility of the
bicycle frame between the contact patches of the two tires. This flexibility is
primarily a combination of the flex in the tire carcass and structural
stiffness of the frame and wheels. On the other hand, weave oscillations are
present even if the bicycle and tires are infinitely stiff, i.e. weave is a
function purely of the assembly of rigid bodies (wheels, fork, frame, ground)
and the nature of their connections.

Advanced dynamics models of bicycles are able to predict the wobble/shimmy
oscillation ([Plöchl2012]_, [Klinger2014]_) and, at least in these papers,
wobble *is* specifically defined. These models show that:

- at speeds > 13 m/s (45 km/h) the wobble frequency of oscillation is between 8
  and 12 Hz
- the dominant motion during wobble is the oscillation of the handle bar and
  fork about the steering axis and this steer motion has an amplitude magnitude
  of 3-5X that of the roll motion
- there is a speed threshold (2-6 m/s) at which the oscillation will tend to be
  unstable and grow; above this threshold damping this oscillation is the
  responsibility of the rider
- slowing down will dampen the oscillations

This video shows a steer dominant high frequency oscillation that qualitatively
matches the wobble/shimmy model predictions to give an idea of what these
research papers are modeling:

.. raw:: html

   <div style="text-align: center;">
   <iframe
     width="560"
     height="315"
     src="https://www.youtube.com/embed/vSNjpQPdrX4?start=27"
     frameborder="0"
     allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
     allowfullscreen>
   </iframe>
   </div>

Did Chloé Dygert experience wobble/shimmy?
==========================================

After watching Dygert's crash frame-by-frame, we make some observations:

- She's likely traveling at a speed between 9 m/s (32 km/h, 20 mph) and 13 m/s
  (47 km/h, 29 mph)
- She is in a steady rightward turn, with a large roll angle of about 30
  degrees or so.
- She is not pedaling during the event.
- She is initially bounced from her seat and the oscillation builds with her
  disconnecting more and more from the seat. This left her fully connected to
  the bicycle only at the time trial bars and at the pedals.
- The magnitudes of the steer and roll angles during oscillation are of similar
  magnitude.
- The frequency of oscillation is approximately 4.2 Hz.

The last two points would seem to indicate that this isn't wobble/shimmy; at
least not by the definition espoused by the academic literature. The frequency
is half what it should be and it isn't steer dominant. The video of Dygert
shows clearly different oscillations than that shown in the "Bicycle Shimmy"
video above. We aren't likely seeing wobble/shimmy in Dygert's crash but the
initial jolt visible in the video surely excited an unstable oscillation. The
large bump may have played a significant role in initiating the subsequent
cascading effects. There is also the possibility of the rider effectively
causing the instability. This is well documented in aircraft as "pilot induced
oscillations", but seems less likely as it requires more activity on the
rider's part.

Here is a video that has similarities to Dygert's oscillation. In this video,
the rider's pelvis seems fairly firmly connected to the seat. The oscillations
are similar in magnitude for steer and roll and a frame-by-frame analysis
estimate gives a 2 Hz oscillation frequency, which also doesn't fit the bill to
be wobble/shimmy. Interestingly, it occurs with the more solid seat-rider
coupling and not at a hard roll angle.

.. raw:: html

   <div style="text-align: center;">
   <iframe
     width="560"
     height="315"
     src="https://www.youtube.com/embed/VfngbsIUSj8?start=27"
     frameborder="0"
     allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
     allowfullscreen>
   </iframe>
   </div>

Conclusion
==========

One important assumption in the wobble/shimmy academic literature is that the
rider's pelvis is firmly connected to the seat in the models. With Dygert's
pelvis disconnected from the seat, that bicycle-rider system is thus different
than these models. The interactions of the rider's flexible body with the
bicycle in Dygert's riding position may very well destabilize the weave
oscillation. For example, [Moore2012a]_ shows that simply adding the inertial
effects of the rider's arms to the handlebars can have a destabilizing effect.

A second important assumption in the models in the academic literature is that
the nominal roll angle of the bicycle is zero. At a roll angle of 30 degrees,
the predicted frequencies of wobble/shimmy oscillation could be lower and the
steer and roll amplitudes similar in magnitude. This would then better match
what we observe with Dygert's crash. At large roll angles like this, the
vehicle could also have an easily destabilized lower frequency weave
oscillation. But there are no studies of these phenomena in hard steady turns
for bicycles.

**So, what caused Chloé Dygert's crash?** Given the limited information and
barring there were no mechanical failures, our best idea is that a bump excited
an unstable weave-like oscillation during the descent. The high speed and large
roll angle as well as Dygert's time trial body position and her disconnection
from the seat may have all contributed to this instability.

Developing a predictive model of the rider being loosely coupled to the bicycle
could help answer whether there are aspects of the bicycle's design or seating
position which could minimize the chance of this happening. Studying
perturbations around large roll angles could also offer more insight. And,
lastly, a rider control model could help determine whether there is something
the rider could actively do to stop this and regain control (besides slowing
down). These types of analyses take more time and resources, but could likely
pin down the cause more concretely.

Acknowledgements
================

We thank Jaap Meijaard for some helpful comments as well as the folks on the
Single Track Vehicle Dynamics discussion list for providing food-for-thought.
Yumiko Henneberry contributed copy editing.

References
==========

.. [Wikipedia2020] https://en.wikipedia.org/wiki/Bicycle_and_motorcycle_dynamics#Wobble
.. [Plöchl2012] Plöchl, Manfred, Johannes Edelmann, Bernhard Angrosch, and
   Christoph Ott. “On the Wobble Mode of a Bicycle.” Vehicle System Dynamics
   50, no. 3 (March 1, 2012): 415–29. https://doi.org/10.1080/00423114.2011.594164.
.. [Klinger2014] Klinger, Florian, Julia Nusime, Johannes Edelmann, and Manfred
   Plöchl. “Wobble of a Racing Bicycle with a Rider Hands on and Hands off the
   Handlebar.” Vehicle System Dynamics 52, no. sup1 (May 30, 2014): 51–68.
   https://doi.org/10.1080/00423114.2013.877592.
.. [Moore2012a] http://moorepants.github.io/dissertation/extensions.html#rider-arms
.. [Moore2012b] http://moorepants.github.io/dissertation/parameterstudy.html#bicycles-with-riders

Notes
=====

- Women time trial-ers average about 45 km/h (12.5 m/s), so she should have
  been going faster than this going down hill (but she isn't pedaling).
- [Plöchl2012]_ shows wobble frequencies between 6 and 9 Hz for 0 to 20 m/s in
  Figure 4. Same figure shows the wobble mode unstable from about 4 to 20 m/s.
  This is for a model with rider lean and the but attached to the seat.
- [Klinger2014]_ shows wobble between 8 and 12 Hz for 0 to 20 m/s for leaned
  over hands on handlebars (no rider lean DOF).
- Figure 6.10 in [Moore2012b]_ shows that the weave frequency for a bicycle
  without a rider can get higher 10 rad/s (1.6 Hz) at 7 m/s, maybe it would be
  close to 4 Hz at 13 m/s?? But weave should be damped and stable at these
  speeds.

Dygert Crash Video
------------------

- Going downhill
- Rightward curve
- Large lean angle to the right
- The magnitude of roll is dominant. The steer and roll magnitudes are similar,
  more like weave that a steering dominated wobble/shimmy.
- Riding a custom Felt bicycle
- She kept cycling holding on to the time trial bars. Can you can damp
  oscillations as good in that position?
- Can the geometry of the time trial bike and the different mass distribution
  due to the different rider position have influence on the wobble frequency (a
  time trial bike is definitely different in geometry than a normal racing bike
  which Klungel might have used in his experiments)?
- Here is a map of the course by Imola:
  https://www.cyclingweekly.com/news/racing/uci-road-world-championships-465806
- 4:09 to 4:10 the seat of the bike bounces upward, maybe a bump in the road?
- 4:10 to 4:19 She bounces once on the seat and then a second time with her
  butt disconnecting from the seat. The bicycle leans further rightward during
  this process.
- 4:19 to 4:23 bounces back down on the seat
- 4:23 to 4:27 bounces back up off the seat, bike is even further leaned hard
  to the right
- 4:27 to 5:02 connects back down to the seat (much harder it seems), bike
  leans back to the left just before connecting (but still at hard right roll
  angle)

The follow csv file, ``dygert-oscillation-data.csv`` gives the second and frame
number for the peak left/right motions of the seat.

.. sourcecode:: none

   second,frame,side
   4,27,right
   5,01,left
   5,06,right
   5,10,left
   5,13,right
   5,16,left
   5,19,right
   5,23,left
   5,26,right
   5,29,left
   6,03,right
   6,06,left
   6,09,right
   6,13,left
   6,16,right
   6,20,left
   6,24,right

Some code to calculate frequency:

.. sourcecode:: python

   import pandas as pd
   df = pd.read_csv('dygert-oscillation-data.csv')
   fps = 30
   df['time'] = df['second'] + (df['frame'] - 1)/fps
   period = 2*df['time'].diff().mean()
   frequency_hz = 1/period
   frequency_hz

Wintergreen Cycling Camp Video
------------------------------

- guy's butt is connected to the seat the whole time (much more than Dygert)
- downhill in dropbar position
- got 2.18 Hz from this video, which is half that of Dygert and also much
  lowered that the expected wobble mode.

``wintergreen.csv`` giving timings of left/right peaks of seat motion:

.. sourcecode:: none

   second,frame,side
   31,29,left
   32,06,right
   32,13,left
   32,20,right
   32,26,left
   33,03,right
   33,08,left
   33,15,right
   33,24,left
