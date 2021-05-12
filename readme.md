# 6 Phase PWM for LED Driver (work in progress)

### 6 PWM channels that alternate in driving a 6 LED driver, one at a time. As requested by an 
[ST Community Member](https://community.st.com/s/question/0D53W00000iD4g9SAC/how-to-generate-6-phase-shifted-60-degrees-between-each-pwm-signals-on-stm32-nucleof334r8-stm32f334r8t6-or-other-)


## Waveforms

CH1 = HRTIMA1 with 10% duty cycle  
CH2 = HRTIMB1 with 10% duty cycle  
CH3 = HRTIMC1 with 10% duty cycle  
CH4 = HRTIMD1 with 10% duty cycle  

![](https://github.com/VictorTagayun/HRTIM_6phase-PWM/blob/main/NUCLEO-G474RE_6phase-PWM/waveformcapture/DS1Z_QuickPrint151.jpg)

CH1 = HRTIMA1 with 10% duty cycle  
CH2 = HRTIME1 with 10% duty cycle (scope changed from HRTIMB1)  
CH3 = HRTIMC1 with 10% duty cycle  
CH4 = HRTIMD1 with 10% duty cycle  

![](https://github.com/VictorTagayun/HRTIM_6phase-PWM/blob/main/NUCLEO-G474RE_6phase-PWM/waveformcapture/DS1Z_QuickPrint152.jpg)

CH1 = HRTIMA1 with 10% duty cycle  
CH2 = HRTIME1 with 10% duty cycle   
CH3 = HRTIMF1 with 10% duty cycle  (scope changed from HRTIMC1)  
CH4 = HRTIMD1 with 10% duty cycle  

![](https://github.com/VictorTagayun/HRTIM_6phase-PWM/blob/main/NUCLEO-G474RE_6phase-PWM/waveformcapture/DS1Z_QuickPrint153.jpg)
