# Acceleromete

📌 Descripción

Este proyecto implementa un sistema de adquisición y procesamiento de datos de un acelerómetro mediante FPGA en Verilog. Se utiliza una interfaz SPI para la comunicación con el sensor y módulos de procesamiento para interpretar los datos obtenidos.

⚙️ Requisitos

Tarjeta FPGA compatible (ejemplo: DE10-Lite, Basys 3, Nexys A7)

Software Intel Quartus Prime Lite u otro entorno de desarrollo HDL

Acelerómetro SPI (ejemplo: ADXL345, MPU6050 con adaptador SPI)

Conexión de cables jumper para la comunicación con la FPGA

Fuente de alimentación adecuada (3.3V o 5V según el acelerómetro utilizado)

📂 Estructura del Proyecto
│── PLL.v               
│── PLL_2.v             
│── PLL_2_bb.v           
│── PLL_altpll.v       
│── PLL_bb.v             
│── accel.v              
│── df.qpf               
│── df.qsf               
│── memory_RAM.v         
│── seg7.v               
│── spi_control.v        
│── spi_serdes.v         
│── README.md            
