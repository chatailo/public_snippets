# publicSnippets
Relatively simple code snippets either for PoCs or education

**dnsmasq.conf**

Typical DNSmasq simple configuration used in local setup with a Raspberry as a local router / DNS forwarder.

Here meant to specify default DNS servers and specific ones for censored websites.

Do not forget to retrieve an up to date hosts.conf with ads and malicious domains resolving to 127.0.0.1


**etc/sshd_config**

Typical SSHd config file with a bit of hardening.

Security tips for deployment : Disable pwd auth, activate Key authentication and review the crypto algorithms