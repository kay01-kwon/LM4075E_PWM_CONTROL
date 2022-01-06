# LM4075E_PWM_CONTROL

Both actuator

Topic to subscribe to:

/encoder_data, /des_pos

The two topic shares the same message(lm4075e_msgs/Int32).

Message Field

<img src="lm4075e_pwm_control/picture/Two_actuator_subscribe.png" width="680" height="100" />

When you just want to execute one actuator...

```
roslaunch lm4075e_pwm_control one_lm4075e_pwm_control.laun
```

Launch Info

<img src="lm4075e_pwm_control/picture/one_lm4075e_pwm_control_launch.png" width="680" height="280" />
