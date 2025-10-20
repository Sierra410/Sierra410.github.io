### Sensitivity in Video Games

A lot of video games allow the players to tweak mouse/joystick sensitivity, both
to compensate for differences in different hardware, as well as to cater to
personal preferences.

In most video games, however, the sensitivity is configured by asking the player
for, effectively, a numeric value. The problem is, in all video games this value
and its relation to actual sensitivity is completely arbitrary. In one game that
value might be a floating point number between 0 and 1, in another it might be a
range from 0 to 20, 50 or 100. Sometimes no numbers are shown at all, so all
there is to see is a nondescript position on a slider.

As a result, dialing-in the sensitivity to the desired state is a
trial-and-error process.

Since the value in inputted before the player can "feel it out", I dub it
"value-to-feel" method.

### Feel-to-Value

As an alternative, I propose a method that asks the player to input the "feel",
instead of the value.

That is, instead of providing a nondescript number, the player is asked to
perform an action, such as rotating in place or aiming at an invisible target,
that has been shown only briefly.

By measuring the distance the mouse has been moved, or the time a joystick has
been tilted to perform the make-pretend action, the desired sensitivity can be
calculated and applied.

If, instead of rotating in place, the player is asked to aim at a briefly shown
target, the vertical and the horizontal components of the movement vector can be
considered separately. From that, both different sensitivity values for vertical
and horizontal movement may be derived, as well as whether the player would like
their horizontal and/or vertical axis to be inverted.

---

A web-based demo showcasing the "rotate-90-degrees" approach is available
[**here**](https://sierra410.github.io/Example.html)
