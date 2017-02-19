#+TITLE: tzsp2pcap

* Introduction
This is a simple utility to listen for [[http://en.wikipedia.org/wiki/TZSP][TaZmen Sniffer Protocol]] (TZSP)
packets and output the contents on stdout in pcap format. It has only
been lightly tested with Mikrotik RouterOS products, and may need
alterations to work with other devices.

* Example usage
: tzsp2pcap -f | wireshark -k -i -
