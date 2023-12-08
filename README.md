# Video Conferencing for Computer Department

## Design and deploy Multimedia Protocol based Multithreaded Video Conferencing client-server for the computer department

**Project Link:** [https://cncp.netlify.app/](https://cncp.netlify.app/)

### Limitations of TCP

- TCP does retransmissions.
- Unbounded delays.
- No provision for time stampings.
- TCP does not support multicast.
- TCP congestion control unsuitable for real-time transport.

### RTP Requirements

#### Sequencing

- Report packet loss.
- Report packet reordering.
- Perform out-of-order decoding.

#### Time Stamping and Buffering

- Time stamping and buffering.
- Payload type identification.
- Cover up errors from lost packets by using adjacency redundancy in most adjacent frames.

### RTP (Real-Time Transport Protocol)

- Network protocol for delivering audio and video over IP networks.
- Used in communication and entertainment systems involving streaming media (e.g., telephony, video teleconference, television services, and web-based push-to-talk features).
- Runs over User Datagram Protocol (UDP).
- Used in conjunction with the RTP Control Protocol (RTCP).
- While RTP carries the media streams, RTCP is used to monitor transmission statistics and quality of service (QoS) and aids synchronization of multiple streams.
