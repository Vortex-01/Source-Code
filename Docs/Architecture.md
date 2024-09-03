### **Software Architecture for Vortex-01**

#### **1. Main Components**

1. **Operating System and Hardware**
- **Raspberry Pi 4B**: Will run the operating system and main services.
- **Sensors**: Altitude, temperature and other sensors needed for the satellite to function.
- **Solar Panels and Batteries**: Power source for the satellite.
- **RF Transmitters**: For communication with Earth and other satellites.

2. **Communication Layer**
- **Communication Modem**: For data transmission and reception.
- **Communication Protocols**: TCP/IP, UDP and specific protocols for RF communication.

3. **Control and Monitoring Layer**
- **Satellite Control System**: Monitoring and adjusting the satellite systems.
- **Monitoring Interface**: Tool for viewing satellite data in real time, including sensor status and communication data.

4. **Data Processing Layer**
- **Data Processor**: Analysis and processing of received data.
- **Database**: Storage of collected data, such as satellite status, communication logs, and sensor data.

5. **Application and Services Layer**
- **Internet Service**: Management of Wi-Fi connection and bandwidth distribution.
- **Connection Management**: Control and management of network connections.
- **Software Update Service**: Updates and security patches.

6. **Security Layer**
- **Encryption**: Protects communication between the satellite and Earth. - **Authentication and Authorization**: Ensures that only authorized users can access the system.

#### **2. Data Flow**

1. **Data Collection**
- Sensors and RF communication collect data and send it to the data processor.

2. **Processing and Storage**
- Data is processed and stored in the database.

3. **Communication Management**
- Data is transmitted to the ground via RF and the Wi-Fi connection is managed to provide internet access.

4. **Monitoring Interface**
- Data and status are displayed on a monitoring interface for supervision and adjustments.
