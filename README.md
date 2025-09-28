# -Firewall-Configuration---Assignment-4-
Configuring firewall rules using Windows Firewall / UFW to block and allow traffic, testing the rules, and restoring the original state.
Objective

To configure and test firewall rules on a system (Windows Firewall or Linux UFW), understand how traffic filtering works, and document the process.
Steps Performed

1. Open Firewall Configuration Tool
	•	Windows: Open Windows Defender Firewall with Advanced Security.

2. List Current Firewall Rules
	•	Windows: Checked Inbound Rules and Outbound Rules to view existing policies.

3. Add a Rule to Block Inbound Traffic on Port 23 (Telnet)
	•	Windows:
	•	In Inbound Rules → New Rule.
	•	Select Port → TCP → 23.
	•	Action: Block the connection.
	•	Name: Block Telnet Port 23.

4. Test the Rule
	•	Tried connecting via Telnet (telnet localhost 23).
	•	Connection failed → Rule successfully blocked traffic.

5. Add Rule to Allow SSH (Port 22)
	•	Windows: Normally allow RDP (3389), but in Linux SSH is common.

6. Remove the Test Block Rule
	•	Windows: Deleted the rule from Inbound Rules.

7. Documentation
	•	Screenshots taken of firewall rules, blocked connection, and restored state (attached in repo).

8. Summary – How Firewall Filters Traffic
	•	A firewall monitors incoming and outgoing packets.
	•	Rules decide whether to allow or block traffic based on:
	•	Port number
	•	Protocol (TCP/UDP)
	•	Direction (Inbound/Outbound)
	•	Application/Program
	•	This protects against unauthorized access while allowing safe communication.

Outcome
	•	Learned to add, test, and remove firewall rules.
	•	Understood how firewalls block/allow traffic.
	•	Gained practical knowledge of network security basics.
