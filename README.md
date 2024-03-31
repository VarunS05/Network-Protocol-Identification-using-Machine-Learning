# Network-Protocol-Identification-using-Machine-Learning

This project aims to develop a machine learning model to predict network protocols based on provided network traffic data. The dataset contains various features such as packet count, byte count, duration, source and destination IP addresses, port numbers, etc., which will be used to train and evaluate the model.

Dataset
The dataset used in this project contains network traffic data captured from a network environment. It consists of the following columns:

dt: Timestamp of the network traffic data
switch: Network switch identifier
src: Source IP address
dst: Destination IP address
pktcount: Number of packets transmitted
bytecount: Number of bytes transmitted
dur: Duration of the communication session
dur_nsec: Duration in nanoseconds
tot_dur: Total duration
flows: Number of flows
packetins: Packet insertions
pktperflow: Packets per flow
byteperflow: Bytes per flow
pktrate: Packet rate
Pairflow: Pair flow
Protocol: Target variable indicating the protocol (e.g., UDP, TCP, ICMP)
port_no: Port number
tx_bytes: Bytes transmitted
rx_bytes: Bytes received
tx_kbps: Transmission rate in kilobytes per second
rx_kbps: Reception rate in kilobytes per second
tot_kbps: Total rate in kilobytes per second
label: Label indicating the presence of an attack (0 for no attack, 1 for attack)
