###Delta between 5.1.0.5046 SP5 GA Release and 5.1.0.5048 SP5 HF1 ###

DTP-55041	CC-294316 Incoming calls cause phone (TLS with SRTP) to crash immediately when SDP missing rtpmap
DTP-53696	Add support for sending dummy classic stun packets to resolve delay in media setup
A new parameter is added:
Parameter: enable classic stun
Description: When enabled (1), phone sends  dummy classic stun packet before sending/receiving the media
Input Range: 0 (disable), 1 (enable)
Default Value: 0(disable)
 