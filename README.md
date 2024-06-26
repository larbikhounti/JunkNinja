# JunkNinja
a detailed list explaining what makes a message spam from a technical perspective. 

# scanning steps
## Header Checks
- From: Verify the sender's address. []
- Subject: Analyze the email subject for spam indicators.
- Return Path: Check the return path address.
- From Email: Confirm the authenticity of the sender's email address.
- From Domain: Assess the reputation of the sender's domain.
- Domain Reputation
- Domain Reputation: Evaluate the overall reputation of the domain.
- Domain A Record IP Reputation: Check the reputation of the domain's A record IP address.
- Domain SPF IP Reputation: Verify the reputation of the IP address listed in the domain's SPF record.
- Domain SPF Include Domain Reputation: Assess the reputation of any domains included in the SPF record.
- Domain SPF Include Domain A Record Reputation: Evaluate the A record reputation of domains included in the SPF record.
- Domain SPF Include Domain SPF IP or Domains Reputation: Check the reputation of IP addresses or domains included in the SPF record.
## body check 
- Domain Reputation: Assess the reputation of any domains mentioned in the email body.
- Domain Relevance: Verify the relevance of domains to the email content.
- Message Length: Analyze the length of the email message.
- Spam Link Patterns: Check for patterns associated with spam links.
- IP Reputation: Evaluate the reputation of IP addresses linked in the email body.
