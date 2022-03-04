## an example of a tested .cfg file for klipper is included here
### be sure to edit this to suit your specific board, setup and wiring!

### it is advised to use the following TMC settings in klipper when running an AWD setup:

spi_speed: 1000000

stealthchop_threshold: 0

driver_IHOLDDELAY: 6

driver_TPOWERDOWN: 10

driver_TBL: 2

driver_TOFF: 4

driver_HEND: 5

driver_HSTRT: 0

driver_tpfd: 0

driver_pwm_autoscale: True

driver_pwm_autograd: True

driver_pwm_freq: 2

driver_PWM_GRAD: 0

driver_PWM_OFS: 0

driver_PWM_REG: 0

driver_PWM_LIM: 0

interpolate: false


[credits to M3NT8L and EvoMoto from Hevort for these settings]
