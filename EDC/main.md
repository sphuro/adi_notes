<style>
html {
background-color: #111;
}
* {
font-family: "VictorMono NFM";
font-weight: bold;
background-color: #111;
color: #aaa;
}
</style>

# Electronics Design Carnival 2024 ( DAY 1 ) : 01-07-24

## Electronics System Design - Prof. Sujay Deb

### What is Engineering?
- Purposeful use of science
- making stuff
- solving problems
- employ facts of nature to build very interesting systems
- conversion of nature to Engineering systems occurs through observation and abstraction
- Take complicate things, build layers of abstraction, and simplify thing so that we can build useful systems

### Abstractions in Modern Computing Systems
- Applications
- Algorithm
- Programming Language
- OS / VM
- ISA (instruction set architecture)
- Micro-architecture
- Register-Transfer level
- Gates
- Circuits
- Devices
- Physics

- Top level layers provide application requirements
- Lower level layers provide technological constraints
- The middle three layers provide feedback to guide application and technology research directions

- Both i9-* and i3-* processors can run similar os like windows and regular applications like ms docs etc
- The software related stuff is similar
- Then what is the difference?
- The microarchitecture is different

#### Register Transfer Logic
- Performance gain => Combinational Logic takes lesser time
- Clock cycles decide the processor speed

## Clock speed
- Intel introduced pentium series in the '90s
- Pentium 1 => running at some MHz
- Pentium 2 => running at 1 GHz
- Pentium 3 => running at 3 GHz
- Pentium 4 => running at 4 GHz
- But they could not increase the clock speed further due to technological constraints, majorly, insufficient heat dissipation
- Tech people were dreaming of higher and higher performance with higher clock speeds but now they hit a power wall
- Hence, now most chips run at 3.3GHz max
- They try to achieve better performance through multi-core processors

## Apple
- Earlier macbooks has intel processors
- To break through the constraints barrier, Apple decided to take control of all the abstractions layer themselves in order to get most out of the chip and make their software work in unison with their hardware

## ISAs
- All popular ISAs are owned by companies
- ARM owned by arm; x86 owned by intel; snapdragon owned by Qualcomm
- Hence, Indians are strongly promoting the open source RISC-V architecture ( competition to ARM architecture)
- RISC: Reduced instruction set computer
- Note: both RISC-V and ARM implement the RISC ideology whereas intel's x86 follows CISC (complex instruction set computer) architecture
- RISC based processors provide low power consumption alongside high performance
- Hence, intel could not survive in the mobile devices market

## Moore's Law
- The number of transistors in an IC doubles about every two years with minimal rise in cost

## Efficiency System Design Strategy
- Efficiency: Microprocessors < General Purpose DSP (Digital Signal Processors) < Dedicated

## Future of SOC (System on a chip)
- There is a quad core CPU; multi core GPU; and accelerators for processing
- And in terms of shared resources : you habve NoC (network on chip: used for communication between computing elements) and SRAM
- Finally, you have the DRM
- Basic Computing Systems are connected through bus based communication.
- However, in multi-core systems, this would be a major bottleneck since it can communicate with a single element at a time. (not scalable)
- In order to prevent this NoC ( network on chip ) was popularized. ( scalable :tick)
    - eg. WNoC ( wireless network on chip )

## IEE iSES 2024 : December
## mail: sdeb@iiitd.ac.in

# RESOURCE OPTIMIZATION - Tarun Shekhar
- tarun.shekhar@gmail.com
- Problem Identification
- Target Audience
- Market research
- Form factor
- Begin development
- Hardware Design
- Firmware Development

## Key stages of IOT Development
- Functions and features
- Architecture
- Hardware and mechanical
- Firmware
- Cloud
- Software

## Mechanical Design
- CAD designer
- 3d printer for proto development 
- Molding tools, injection tools for final production
- Printing and Labelling

## Hardware Design (can be outsourced)
- Circuit design and component selection ( Analog, Digital, Communication, Power Supply, MCU / MPU, and other passive components )
- Schematic
- PCB Design
- Fabrication
- PCB Assembly
- Note: PCBA = PCB Assembled

## Firmware Development
- Should be in line with the hardware functioning
- MCU/MPU Selection
- Deciding Communication

## Cloud and Software Development- AArchitecture
- Hosting
- Database Managerment
- Communication Protocol
- UI/UX
- Backend Development
- Frontend Developent
- Testing with hardware

## Resource optimization
- Optimization of man power (HR)
- Time optimization
- Outsourcing
- Taking help from semiconductor companies like free samples and eval boards, 

## TDK Company : Semiconductor ( based in japan )

## Supply Chain
1. Final Product Manufacturing (10-20%) (screwdriving technique : just assmebly)
2. Product Design and Development
3. Component Manufacturing
4. Component Design and Development
5. Raw material processing and refining
6. Mining and Extraction

> Just S.No.1 occurs in India. Rest of the stuff has been controlled by China

## OPTIMIZATION
- Man Power
- Hardware and Software
- Financial
- Time

# DAY 2 (02-07-24)

## IOT Paradox
> "Simplicity Sells, Complexity scales"

## IOT Simplified
- Edge : where the action is hapenning
- Gateway : communication portal
- Cloud

## IOT key components
- Sensors
- Connectivity ( Edge / Cloud )
- Intelligence and data analytics
- Security and Trust
- Efficient and cost saving

## Network protocols in terms of distance
- NFC
- EMV
- WPAN
- WHAN
- WFAN : wireless Field area network
- WLAN
- WNAN
- Cellular

## Connectivity
- Unlicensed : Under 2MHz signal strength : free
- Licensed => eg: Cellular

## Embedded software
- Discover
    - Consulting
- Create
    Design and Implementation
- Scale
    Continuous Improvement
<hr>

- MCU frmware
- Linux
- Android
- Middleware and application
    - Multimedia
    - Domain Specific protocols and stacks
- Computer Vision and AI/ML 
- Silicon
    - FPGA
    - Pro and Post silicon validation
<hr>

- Hardware Design
- Firmware Development
    - Board software package
- QA and Testing (Debugging)

## MCU Firmware
- OS
- Chipsets
- TOols (IDE)
- Middleware and SDKs (Software development kit)
- UI/UX
- Protocols and peripherals
    - Serial bus
    - UART
    - Wireless
- Optimization
    - Power
    - Memory
    - Boot time

## ARM: Under the hood
- OSI Architecture

1. Physical layers
    - Sensors
    - Radio
    - Cortex-M
2. Data Layer
    - Drivers
    - CMSIS
3. Network Layer
    - IPv4
    - IPv6
    - 6loWPAN
4. Transport layer
    - TLD
    - DTL
5. Application Layer
    - Cpp APIs
    - Applications
    - Community Libraries

## Cloud Development
- Edge
    - Device Provisioning
        - Discovery
        - Connection
        - Authentication
        - Registration
        - Self Provisioning
    - Device Management
        - Confi
        - Rule based automation
        - Cloud data transfer
        - Off boarding
    - Device Monitoring
        - Performance monitoring
        - Troubleshooting
    - Device update and Diagnostics
- Gateway
- Cloud
    - Application Dev
        - API management
    - Application config & management
        - Gateway management

## Cybersec
- Discover
    - Security Scoping and Requrement Assessment
- Treat
    - Dev Sec Ops
- Maintain
    - Governance and risk compliance

## Designing and IOT Device
- Hardware design and prototyping
- Industrial Design and mechanical engineering
- Firmware development
- Software / application development
- Design for Manufacturing
- Testing and certifications

# Interfacing with sensors and actuators - Tarun

## Sensor
- Detects change in the environment and responds to some output

## Actuator
- Part of a device that helps it to achieve physical movements by converting energy, often electrical, air or hydraulic into mechanical force

## Interfacing
- Sensors: send a signal
- Actuator : convert a signal to energy
- Can we simply connect a sensor and an actuator?
    - No
    - Not every sensor signal needs to be converted to transducer movement
    - Often, data needs to be processed before actually being sent to transducer

## Protocols
- Processor does not interact with the physical sensors or actuators directly
- Development boards use protocols like UART, SPI, I2C (scl and sda)
- The sender should know that the receiver received the data successfully
- Protocols
    - Ensure smooth data movement
    - Both sender and receiver know

## Serial Protocol
- Eg: we have to transfer 9 bits from point 1 to point 2
    - You can use either serial communication (one bit at a time using a single data path) or parallel
    - We prefer serial protocol

### UART protocol
- Universal Asynchronous Receiver Transmitter
- Two signals:
    1. Transmitter (TX)
    2. Receiver (Rx)
- Baudrate
- You receive 8 bits from the data bus in parallel and it is sent using serial communication by converting it to serial (serialization), UART specifically and then you convert it back to parallel bits so that it can be transferred further using data bus (de-serialization)

| UART 1 | UART 2 |
|--------|--------|
| RX     | RX     |
| TX     | TX     |

### Packet structure of UART

| Start bit | Data Frame | Parity Bit | Stop Bit   |
|-----------|------------|------------|------------|
| 1 bit     | 5-9 bits   | 0-1 bit    | 1-2 bit(s) |

- Parity bit : prevents from sending signals with noise
- Stop bit : converts from low to high when the transmission needs to stop

## I2C protocol
- Inter-Integrated Circuit

| Master |     | Slave |
|--------|-----|-------|
| SDA    | <-> | SDA   |
| SCL    | --> | SCL   |

- Half Duplex : Single controller sends data at a time
- SDA is bidirectional : but only one can send at a time
- Two Wire serial communication protocol using serial data line and serial clock line
- Sent in strict byte packets with a unique address for each target device
- Several Transmission rates
    - Slow
    - Normal
    - Fast
    - Very fast
- If we have to use multiple UART, we have to redefine another receiver but with I2C we can use same I2C bus for several oled displays and sensors

### I2C Communication
- First SDA is pulled down then SCL is pulled down. Now i2c is initialized
- Then you send the address frame bits : (which address to send to) : 7/8 bit address : Last bit is Read / Write (bar) (i.e. Read when bit is high and write when bit is low)
- Then ACK bit (acknowledgement from receiver : 1 - data received or 0 - data not received)
    - If not received then the communication is restarted
- Now, Data Frame bits (8 bits) and once again ACK for acknowledgement
- Then, SDA goes from 0 to 1 THEN SCL goes from 0 to 1
- And the clock peaks whenever the data needs to be scanned by the receiver
- Everything read at positive edge of clock cycle

## SPI Interface
- Serial Peripheral Interface
- 4 signals
    - CS (bar) : chip select (inverted)
    - SCLK : serial clock
    - SDI / MISO : serial data in (main in / subnode out)
    - SDO / MOSI : serial data out (main out / subnode in)
- One main and one / multiple subnodes
- Bidirectional, duplex communication
- Higher freq than i2c communication
- There hasn't been many cases where we need to speak in both directions at the same time even in sensors / displays / human interface devices

### SPI Communication

| SPI Mode | CPOL | CPHA | Clock polarity | Clock phase used to sample and or shift the data       |
|----------|------|------|----------------|--------------------------------------------------------|
| 0        | 0    | 0    | Logical Low    | data sampled: rising edge; shifted out in falling edge |
| 1        | 0    | 1    | Logical Low    | data sampled: falling edge; shifted out in rising edge |
| 2        | 1    | 0    | Logical High   | data sampled: falling edge; shifted out in rising edge |
| 3        | 1    | 1    | Logical High   | data sampled: rising edge; shifted out in falling edge |

- In regular SPI mode and in multi subnode spi communication, you can read from any ONE of the those at a time since you cannot make out where the data is coming from because we are using different chip selects
- Daisy chaining : not supported on all SPI devices
    - SDO to SDI; SDO to SDI... and so on
    - Delayed data input (data in after 24 cycles if we have 3 of those receivers and each take 8 cycles because of common CS(bar))
    - Save on Chip select by using the same on all