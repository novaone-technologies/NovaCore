# System Component 

- MCU
    - Three Cortex-M0 MCUs inside RK3588
    - MCU in VD_PMU integrate 16KB Cache and 16KB TCM 
    - MCU in VD_NPU integrate 16KB Cache and 64KB TCM 
    - MCU in PD_CENTER integrate 32KB TCM
    - Integrated Programmable Interrupt Controller, all IRQ lines connected to GIC for CPU also connect to MCU in VD_PMU(PMU_M0) and PD_CENTER(DDR_M0)
    - Integrated Debug Controller with JTAG interface 

- CRU (clock & reset unit)
    - Support total 18 PLLs to generate all clocks
    - One oscillator with 24MHz clock input 
    - Support clock gating control for individual components 
    - Support global soft-reset control for whole chip, also individual soft-reset for each component 

- PMU
    - Multiple configurable work modes to save power by different frequency or automatic clock gating control or power domain on/off control 
    - Lots of wakeup sources in different mode 
    - Support 10 separate voltage domains 
    -  Support 45 separate power domains, which can be power up/down by software based on different application scenes 

- Timer
    -  Support 12 secure timers with 64bits counter and interrupt-based operation 
    - Support 18 non-secure timers with 64bits counter and interrupt-based operation 
    - Support two operation modes: free-running and user-defined count for each timer
    - Support timer work state checkable 

- PWM
    - Support 16 on-chip PWMs(PWM0~PWM15) with interrupt-based operation
    - Programmable pre-scaled operation to bus clock and then further scaled 
    - Embedded 32-bit timer/counter facility
    - Support capture mode 
    - Support continuous mode or one-shot mode 
    - Provides reference mode and output various duty-cycle waveform 
    - Optimized for IR application for PWM3, PWM7, PWM11, PWM15 

[More Soon: ]