# bicopter_control
Study on controlling a bicopter blimp

## Simulation
- [https://github.com/Jarvis-X/bicopter_control/blob/main/bicopter.ttt](bicopter.ttt) is a CoppeliaSim simulation environment composed of a bicopter blimp along with some other example robots (a robotic arm and a standard quadrotor.)
Upon starting the simulation, a LUA child script attached to the `bicopterBody` object controls the bicopter to follow the position and orientation of the `target` object, (`target(1)`, if a `Quadrotor` object is present.) During simulation, the user can actively change the position and orientation of the target.
- On line 55 of the child script of `bicopterBody`, the variable `remote_API` determines if we want to use remote calls to control the bicopter blimp instead of the native controller implemented in the LUA script.
