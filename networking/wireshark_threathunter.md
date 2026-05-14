# Lab: Wireshark, tcpdump, and protocols. Let's dance.

You are a Security Analyst attached to the Incident Response (IR) team at Wanaopera Ltd.

Earlier this week, the company began receiving extortion emails from an unknown threat actor claiming to have successfully exfiltrated confidential corporate documents from the internal network. The attacker is demanding a payment of 1 BTC in exchange for not leaking the allegedly stolen data publicly.

Management has provided your team with a [packet capture file (.pcap)](https://github.com/DunteCityzen/Lab-Exercises/blob/main/networking/wireshark_threathunter.pcap) collected during the suspected compromise window. Your task is to analyze the traffic and determine whether the attacker’s claims are legitimate.

## Your investigation should answer the following questions:

1. Was sensitive data actually exfiltrated?
2. Which system(s) were involved in the compromise?
3. What credentials, if any, were leveraged by the attacker?
4. Which protocol(s) and techniques were used during the attack?
5. What evidence supports your conclusions?

## Hints:

* Not all traffic in the capture is relevant. Filter out the noise and focus on anomalous or suspicious communications.
* Identify any credentials exposed or reused during the attack lifecycle.
* Pay close attention to protocols commonly associated with file transfer, remote access, or data movement.
* Following a suspicious stream or session may reveal the attacker’s actions in sequence.

## Deliverable:
Prepare a brief writeup summarizing your findings and key things that you learnt from the exercise.
