# Quality of Service (QoS)

**QoS** assists a congested network by prioritising traffic that is time-sensitive over a non time-sensitive traffic. For example voice traffic will be prioritised over data traffic, one of the reasons is because voice packets can never be resent (*uses UDP*) but data traffic can be resent (*if TCP is utilised*).

If one of the voice packets is lost, Digital Signal Processor (DSP) is employed to patch it with what it thinks the audio should be. However, this can be an major issue if many packets are lost.

## What causes network congestions?
Network congestions can occur when there is a large network traffic transmitted to the network than what the network can actually handle (*the traffic sent is bigger than network's bandwidth*). This causes packets to be queued (*creates congestion*) until there are memory resources to transport them.

During this period of congestion, new packets will be delayed until previous packets are being processed. Consequently, packets will be dropped when the memory of the device transporting them gets full.
