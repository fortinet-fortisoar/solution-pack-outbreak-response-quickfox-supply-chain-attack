# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 

# Overview 

FortiGuard Labs has uncovered a long-running supply chain compromise targeting QuickFox, a Windows VPN/network acceleration application primarily used by overseas Chinese users. Attackers tampered with official Windows installers to deploy a custom backdoor tracked as FDMTP, enabling selective victim profiling and post-compromise access. The campaign has reportedly been active since August 2025 before being publicly disclosed in August 2026. 

 The **Outbreak Response - QuickFox Supply Chain Attack** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/2.3.0/docs/background-information.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*.

 The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/quickfox-supply-chain-attack) contains information about the outbreak alert **Outbreak Response - QuickFox Supply Chain Attack**. 

## Background: 

Unlike opportunistic malware campaigns, the trojanized QuickFox installer fingerprints each system and deploys the FDMTP backdoor only when attacker-defined criteria are met, indicating a highly selective espionage operation rather than indiscriminate malware distribution. Because the incident resulted from a compromised software supply chain rather than a vulnerability in the application itself, no CVE has been assigned.

QuickFox is a network acceleration application that combines VPN and proxy technologies to help overseas Chinese users securely access online services hosted in mainland China. Its primary user base includes expatriates, international students, business travelers, and organizations requiring access to China-based applications and services.

Based on QuickFox's intended user base, the United States, Canada, Australia, the United Kingdom, and Japan are likely among the regions with the highest exposure. However, these represent expected deployment locations rather than confirmed victim telemetry, as no country-specific compromise data has been published. 

## Announced: 

Publicly confirmed affected versions are 3.0.51.0–3.59.5, with 3.59.6 serving as the clean release.
 

## Latest Developments: 

August 4, 2026: FortiGuard Labs publicly discloses campaign.
https://www.fortinet.com/blog/threat-research/quickfox-supply-chain-attack-used-to-deploy-fdmtp-implant

August 1, 2026: QuickFox releases version 3.59.6 removing malicious components. 

# Next Steps
 | [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) | 
 |--------------------------------------------|----------------------------------------------|------------------------|------------------------------|