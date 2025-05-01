# Memory Optimization

- Internal on-chip memory
    - Supports System boot for: SPI interface, eMMC interface, SD/MMC interface

- Share Memory in the voltage domain of VD_LOGIC, totally 1MByte
- PMU SRAM in VD_PMU for low power application, totally 64KByte 

- External off-chip memory 
    - Dynamic Memory Interface 
        - Compatible with JEDEC standards LPDDR4/LPDDR4X/LPDDR5 
        - Support four channels, each channel 16bits data widths
        - Support up to 2 ranks (chip selects) for each channel 
        - Totally up to 32GB address space 
        - Low power modes, such as power-down and self-refresh for SDRAM 
    
    - eMMC Interface 
        - Fully compliant with JEDEC eMMC 5.1 and eMMC 5.0 specification
        - Backward compliant with eMMC 4.51 and earlier versions specification. 
        - Support HS400, HS200, DDR50 and legacy operating modes 
        Support three data bus width: 1bit, 4bits or 8bits 

{Adding More: Soon.}