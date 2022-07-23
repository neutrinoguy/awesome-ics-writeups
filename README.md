# Awesome ICS/SCADA Writeups

![awesome badge](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
![GitHub Repo stars](https://img.shields.io/github/stars/neutrinoguy/awesome-ics-writeups?style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/neutrinoguy/awesome-ics-writeups?style=flat-square)
----------

A collection of writeups related to ICS/SCADA hacking. This covers areas like OT, IoT and IIoT. It includes exploitation writeups, vendor blogs, talks, CTF writeups etc.

:full_moon: = Full details 
:first_quarter_moon: = Partial details
:new_moon: = No details 

**Disclaimer: The work linked here is solely owned by the respective authors. This is just a collection of them.**

### Airbus
- https://airbus-cyber-security.com/remote-code-execution-on-ecostruxure-plc-simulator/ [:full_moon:]
- https://airbus-cyber-security.com/abusing-a-shared-memory-for-getting-a-local-privilege-escalation-on-the-schneider-electric-modbus-serial-driver-cve-2020-7523/ [:full_moon:]
- https://airbus-cyber-security.com/applying-a-stuxnet-type-attack-to-a-modicon-plc/ [:full_moon:]

### Applied Risk
- https://applied-risk.com/resources/multiple-vulnerabilities-in-moxa-iologik-e1200-series
- https://applied-risk.com/resources/exploiting-a-kunbus-gateway-module-for-modbus-tcp-2
- https://applied-risk.com/resources/ge_ifix_advisory

### Armis
- https://info.armis.com/rs/645-PDC-047/images/Urgent11%20Technical%20White%20Paper.pdf
- https://www.armis.com/research/modipwn/ 
- https://www.armis.com/research/pwnedpiper/

### Claroty
- https://www.claroty.com/2020/05/14/security-flaws-in-software-based-plc-enable-remote-code-execution-on-windows-box/
- https://www.claroty.com/2020/11/10/blog-research-schneider-m221-plcs/
- https://www.claroty.com/2020/12/17/blog-research-rce-vulnerability-in-wago-firmware/
- https://www.claroty.com/2020/07/15/cve-2020-14511/
- https://www.claroty.com/2020/05/28/eds-subsystem-vulnerabilities-expose-ot-assets-to-malicious-file-delivery/
- https://www.claroty.com/2021/05/28/blog-research-race-to-native-code-execution-in-plcs/
- https://www.claroty.com/2021/02/25/blog-research-critical-authentication-bypass-in-rockwell-software/
- https://www.claroty.com/2021/03/23/blog-research-vulnerabilities-in-tbox-rtus/
- https://www.claroty.com/2021/04/01/blog-research-critical-vulnerabilities-found-in-rockwell-factorytalk-assetcentre/
- https://www.claroty.com/2021/08/31/blog-research-crashing-sip-clients-with-a-single-slash/
- https://www.claroty.com/2021/11/19/blog-research-all-roads-lead-to-openvpn-pwning-industrial-remote-access-clients/
- https://www.claroty.com/2021/12/13/blog-research-bugs-in-the-cloud-how-one-vulnerability-exposed-offline-devices-to-a-security-risk/
- https://claroty.com/2021/09/21/blog-research-securing-network-management-systems-nagios-xi/
- https://www.claroty.com/2022/02/10/blog-research-securing-network-management-systems-moxa-mxview/
- https://claroty.com/2022/03/31/blog-research-hiding-code-on-rockwell-automation-plcs/
- https://claroty.com/2022/04/14/blog-research-blinding-snort-breaking-the-modbus-ot-preprocessor/
- https://claroty.com/2022/05/11/blog-research-from-project-file-to-code-execution-exploiting-vulnerabilities-in-xinje-plc-program-tool/
- https://claroty.com/2022/06/16/blog-research-securing-network-management-systems-part-3-siemens-sinec-nms/


### CrowdStrike
- https://www.crowdstrike.com/blog/how-to-pwn2own-the-cisco-rv340-router/ 


### CyberArk
- https://www.cyberark.com/resources/threat-research-blog/bug-hunting-stories-schneider-electric-the-andover-continuum-web-client

### Cynerio
- https://assets.website-files.com/5d2ad783e06f4c19469d363a/625551dd440d0b187fa96d38_JekyllBot-5-Vulnerability-Disclosure-Report.pdf

### Dragos
- https://hub.dragos.com/hubfs/116-Whitepapers/Dragos_ChernoviteWP_v2b.pdf [Malware]
- https://www.dragos.com/blog/industry-news/chernovite-pipedream-malware-targeting-industrial-control-systems/

### Tenable
 - https://medium.com/tenable-techblog/plc-bug-hunt-fa3a0aeae9ab
 - https://medium.com/tenable-techblog/examining-crypto-and-bypassing-authentication-in-schneider-electric-plcs-m340-m580-f37cf9f3ff34
 - https://www.tenable.com/security/research/tra-2021-50
 - https://www.tenable.com/security/research/tra-2021-47
 - https://www.tenable.com/security/research/tra-2021-40
 - https://www.tenable.com/security/research/tra-2021-28
 - https://www.tenable.com/security/research/tra-2021-24
 - https://www.tenable.com/security/research/tra-2021-51
 - https://medium.com/tenable-techblog/arris-cable-modem-teardown-5e294b7007eb

### Trend Micro
- https://documents.trendmicro.com/assets/wp/wp-industrial-robot-security.pdf
- https://www.trendmicro.com/en_us/research/20/e/fake-company-real-threats-building-a-fake-manufacturing-system-for-a-sting.html
- https://www.trendmicro.com/en_us/research/20/e/fake-company-real-threats-the-reality-of-cyberattacks-on-factories.html
- https://documents.trendmicro.com/assets/wp/wp-hacker-machine-interface.pdf  


### Kaspersky
- https://ics-cert.kaspersky.com/reports/2018/03/12/somebodys-watching-when-cameras-are-more-than-just-smart/
- https://ics-cert.kaspersky.com/reports/2018/02/28/iot-hack-how-to-break-a-smart-home-again/
- https://ics-cert.kaspersky.com/reports/2019/01/22/security-research-thingspro-suite-iiot-gateway-and-device-manager-by-moxa/
- https://ics-cert.kaspersky.com/reports/2019/09/18/security-research-codesys-runtime-a-plc-control-framework-part-1/
- https://ics-cert.kaspersky.com/reports/2019/09/18/security-research-codesys-runtime-a-plc-control-framework-part-2/
- https://ics-cert.kaspersky.com/reports/2019/09/18/security-research-codesys-runtime-a-plc-control-framework-part-3/
- https://ics-cert.kaspersky.com/reports/2020/10/08/montysthree-industrial-espionage-with-steganography-and-a-russian-accent-on-both-sides/
- https://ics-cert.kaspersky.com/publications/reports/2022/05/23/isapwn-research-on-the-security-of-isagraf-runtime/


### Fireeye
 - https://www.fireeye.com/blog/threat-research/2020/07/financially-motivated-actors-are-expanding-access-into-ot.html
 - https://www.fireeye.com/blog/threat-research/2019/04/triton-actor-ttp-profile-custom-attack-tools-detections.html
 - https://www.fireeye.com/blog/threat-research/2018/05/rooting-logitech-harmony-hub-improving-iot-security.html
 - https://www.fireeye.com/blog/threat-research/2021/02/solarcity-exploitation-of-x2e-iot-device-part-one.html
 - https://www.fireeye.com/blog/threat-research/2021/02/solarcity-exploitation-of-x2e-iot-device-part-two.html


### Fortinet
- https://www.fortinet.com/blog/threat-research/ekans-ransomware-targeting-ot-ics-systems [Malware]


### Forescout
- https://www.forescout.com/company/resources/amnesia33-how-tcp-ip-stacks-breed-critical-vulnerabilities-in-iot-ot-and-it-devices/ [:first_quarter_moon:]
- https://www.forescout.com/company/blog/numberjack-forescout-research-labs-finds-nine-isn-generation-vulnerabilities-affecting-tcpip-stacks/
- https://www.forescout.com/company/resources/namewreck-breaking-and-fixing-dns-implementations/
- https://www.forescout.com/resources/infrahalt-discovering-mitigating-large-scale-ot-vulnerabilities/
- https://www.forescout.com/resources/nucleus13-research-report-dissecting-the-nucleus-tcpip-stack/
- https://www.forescout.com/resources/project-memoria-lookback-report/

### McAfee
- https://www.mcafee.com/blogs/other-blogs/mcafee-labs/hvacking-understanding-the-delta-between-security-and-reality/

### Netresec
- https://www.netresec.com/?page=Blog&month=2014-11&post=Observing-the-Havex-RAT [Malware]
- https://www.netresec.com/?page=Blog&month=2014-10&post=Full-Disclosure-of-Havex-Trojans [Malware]
- https://www.netresec.com/?page=Blog&month=2012-08&post=SCADA-Network-Forensics-with-IEC-104
- https://www.netresec.com/?page=Blog&month=2022-04&post=Industroyer2-IEC-104-Analysis [Malware]


### NCC Group
- https://research.nccgroup.com/2022/03/24/remote-code-execution-on-western-digital-pr4100-nas-cve-2022-23121/  


### Zero day Initiative
 - https://www.zerodayinitiative.com/blog/2020/8/24/cve-2020-10611-achieving-code-execution-on-the-triangle-microworks-scada-data-gateway 
 - https://www.zerodayinitiative.com/blog/2020/6/10/a-trio-of-bugs-used-to-exploit-inductive-automation-at-pwn2own-miami 
 - https://www.thezdi.com/blog/2020/9/30/the-anatomy-of-a-bug-door-dissecting-two-d-link-router-authentication-bypasses 
 - https://www.thezdi.com/blog/2020/7/22/chaining-5-bugs-for-code-execution-on-the-rockwell-factorytalk-hmi-at-pwn2own-miami
 - https://www.zerodayinitiative.com/blog/2020/1/15/reliably-finding-and-exploiting-icsscada-bugs
 - https://www.thezdi.com/blog/2020/9/9/performing-sql-backflips-to-achieve-code-execution-on-schneider-electrics-ecostruxure-operator-terminal-expert-at-pwn2own-miami-2020 

### Vdoo
- https://www.vdoo.com/blog/vdoo-discovers-significant-vulnerabilities-in-axis-cameras [:full_moon:]
- https://www.vdoo.com/blog/significant-vulnerability-in-hikvision-cameras [:full_moon:]
- https://www.vdoo.com/blog/giving-back-securing-open-source-iot-projects [:full_moon:]
- https://www.vdoo.com/blog/vdoo-has-found-major-vulnerabilities-in-foscam-cameras [:full_moon:]
- https://www.vdoo.com/blog/cve-2020-25860-significant-vulnerability-discovered-rauc-embedded-firmware-update-framework
- https://www.vdoo.com/blog/realtek-rtl8195a-vulnerabilities-discovered

### Nozomi Networks
- https://www.nozominetworks.com/downloads/US/Nozomi-Networks-GreyEnergy-Dissecting-the-Malware.pdf [Malware]
- https://www.nozominetworks.com/downloads/US/Nozomi-Networks-TRITON-The-First-SIS-Cyberattack.pdf [Malware]
- https://www.nozominetworks.com/blog/industroyer2-nozomi-networks-labs-analyzes-the-iec-104-payload/ [Malware]
- https://www.nozominetworks.com/downloads/US/Nozomi-Networks-WP-Industroyer2.pdf [Malware]


### Mandiant
- https://www.mandiant.com/resources/incontroller-state-sponsored-ics-tool [Malware]
- https://www.mandiant.com/resources/industroyer-v2-old-malware-new-tricks [Malware]  

### Medigate
- https://www.medigate.io/lexmark-printers-firmware-extraction-part-a/
- https://www.medigate.io/lexmark-printers-firmware-extraction-part-b/
- https://www.medigate.io/lexmark-printers-firmware-extraction-part-c/

### Microsoft
- https://msrc-blog.microsoft.com/2021/04/29/badalloc-memory-allocation-vulnerabilities-could-affect-wide-range-of-iot-and-ot-devices-in-industrial-medical-and-enterprise-networks/

### Redfox Security
- https://redfoxsec.com/blog/plc-hacking-part-1/
- https://redfoxsec.com/blog/plc-hacking-part-2/


### Scadafence
- https://www.scadafence.com/wp-content/uploads/2022/04/SCADAfence-Hack-The-Port-Report-2022.pdf [Whitepaper]

### Sector7
- https://sector7.computest.nl/post/2022-07-opc-ua-net-standard-trusted-application-check-bypass/
- https://sector7.computest.nl/post/2022-07-inductive-automation-ignition-rce/

### WeLiveSecurity
- https://www.welivesecurity.com/wp-content/uploads/2018/10/ESET_GreyEnergy.pdf [Malware]
- https://www.welivesecurity.com/2022/04/12/industroyer2-industroyer-reloaded/ [Malware]

### Miscellaneous

- https://stepfunc.io/blog/tmw-bug-chain-and-rust/  
- http://muffsec.com/blog/?p=608 
- https://medium.com/cognite/pwn2own-or-not2pwn-part-1-3f152c44563e [:full_moon:]
- https://medium.com/cognite/pwn2own-or-not2pwn-part-2-5-a-brief-tale-of-free-0days-e1df142eb815 [:full_moon:]
https://medium.com/cognite/pwn2own-or-not2pwn-part-3-the-lazy-mans-escalation-392fd00a0ec8 [:full_moon:]
- https://www.jsof-tech.com/wp-content/uploads/2020/06/JSOF_Ripple20_Technical_Whitepaper_June20.pdf [:first_quarter_moon:]
- https://www.vanimpe.eu/2017/03/23/shodan-telling-us-ics-belgium/
- http://www.scada.sl/2013/01/sux.html 
- http://www.scada.sl/2018/09/how-to-hack-sd-wan-and-keep-your-sanity.html
- https://1modm.github.io/CVE-2019-12480.html 
- https://vimeo.com/53806381 [:new_moon:]
- https://www.trustwave.com/en-us/resources/blogs/spiderlabs-blog/vulnerabilities-in-schneider-electric-somachine-and-m221-plc/ [:full_moon:]
- https://www.trustwave.com/en-us/resources/blogs/spiderlabs-blog/attacking-scada-part-ii-vulnerabilities-in-schneider-electric-ecostruxure-machine-expert-and-m221-plc/
- https://www.trustwave.com/en-us/resources/blogs/spiderlabs-blog/attacking-scada-part-iii-hardcoded-salt-in-schneider-electric-ecostruxure-machine-expert-cve-2020-28214/
- https://ioactive.com/warcodes-attacking-ics-through-industrial-barcode-scanners/
- https://www.domaintools.com/resources/blog/def-con-ics-ctf [CTF]
- https://srcincite.io/blog/2020/02/18/silent-schneider-revealing-a-hidden-patch-in-ecostruxure-operator-terminal-expert.html
- https://www.atredis.com/blog/2018/5/14/ge-healthcare-mac-5500-vulnerabilities
- https://media.ccc.de/v/34c3-8956-scada_-_gateway_to_s_hell
- https://www.synacktiv.com/publications/izi-izi-pwn2own-ics-miami.html
- https://labs.f-secure.com/archive/offensive-ics-exploitation-a-technical-description/ [CTF]
- https://grimminck.medium.com/running-a-fake-power-plant-on-the-internet-for-a-month-4a624f685aaa 
- https://medium.com/@npcole/packet-modification-attack-on-plc-with-arp-spoofing-mitm-attack-f0c4d58e3e83
- https://halcyonic.net/2019-04-21-rockwell-zero-day/
- https://www.midnightbluelabs.com/blog/2018/1/16/analyzing-the-triton-industrial-malware [Malware]
- https://isc.sans.edu/forums/diary/Looking+for+malicious+traffic+in+electrical+SCADA+networks+part+1/17967
- https://isc.sans.edu/forums/diary/Looking+for+malicious+traffic+in+electrical+SCADA+networks+part+2+solving+problems+with+DNP3+Secure+Authentication+Version+5/17981
- https://isc.sans.edu/forums/diary/Authentication+Issues+between+entities+during+protocol+message+exchange+in+SCADA+Systems/13927
- https://sergiusechel.medium.com/misconfiguration-in-ilc-gsm-gprs-devices-leaves-over-1-200-ics-devices-vulnerable-to-attacks-over-82c2d4a91561
- https://www.redtimmy.com/iot-ics-armageddon-hacking-devices-like-theres-no-tomorrow-part-1/



 
### Cisco Talos
- https://talosintelligence.com/vulnerability_reports/TALOS-2020-1140 [:full_moon:]
- https://talosintelligence.com/vulnerability_reports/TALOS-2020-1003 [:first_quarter_moon:]
- https://talosintelligence.com/vulnerability_reports/TALOS-2019-0771 [:full_moon:]
- https://talosintelligence.com/vulnerability_reports/TALOS-2017-0445 [:full_moon:]
- https://talosintelligence.com/vulnerability_reports/TALOS-2020-1026
- https://talosintelligence.com/vulnerability_reports/TALOS-2020-1025
- https://talosintelligence.com/vulnerability_reports/TALOS-2020-1024
- https://talosintelligence.com/vulnerability_reports/TALOS-2020-1069
- https://talosintelligence.com/vulnerability_reports/TALOS-2016-0184
- https://talosintelligence.com/vulnerability_reports/TALOS-2020-1144
- https://talosintelligence.com/vulnerability_reports/TALOS-2019-0868
- https://talosintelligence.com/vulnerability_reports/TALOS-2019-0825
- https://talosintelligence.com/vulnerability_reports/TALOS-2019-0827
- https://talosintelligence.com/vulnerability_reports/TALOS-2019-0847
- https://talosintelligence.com/vulnerability_reports/TALOS-2019-0822
- https://talosintelligence.com/vulnerability_reports/TALOS-2019-0824
- https://talosintelligence.com/vulnerability_reports/TALOS-2020-1144
- https://talosintelligence.com/vulnerability_reports/TALOS-2019-0851
- https://talosintelligence.com/vulnerability_reports/TALOS-2019-0823
- https://talosintelligence.com/vulnerability_reports/TALOS-2019-0826
- https://talosintelligence.com/vulnerability_reports/TALOS-2019-0866
- https://talosintelligence.com/vulnerability_reports/TALOS-2019-0867
- https://talosintelligence.com/vulnerability_reports/TALOS-2019-0808
- https://talosintelligence.com/vulnerability_reports/TALOS-2019-0807
- https://talosintelligence.com/vulnerability_reports/TALOS-2018-0736
- https://talosintelligence.com/vulnerability_reports/TALOS-2019-0806
- https://talosintelligence.com/vulnerability_reports/TALOS-2019-0766
- https://talosintelligence.com/vulnerability_reports/TALOS-2018-0735
- https://talosintelligence.com/vulnerability_reports/TALOS-2019-0763
- https://talosintelligence.com/vulnerability_reports/TALOS-2018-0737
- https://talosintelligence.com/vulnerability_reports/TALOS-2019-0764
- https://talosintelligence.com/vulnerability_reports/TALOS-2019-0765
- https://talosintelligence.com/vulnerability_reports/TALOS-2018-0738
- https://talosintelligence.com/vulnerability_reports/TALOS-2018-0745
- https://talosintelligence.com/vulnerability_reports/TALOS-2018-0739
- https://talosintelligence.com/vulnerability_reports/TALOS-2018-0743
- https://talosintelligence.com/vulnerability_reports/TALOS-2019-0768
- https://talosintelligence.com/vulnerability_reports/TALOS-2018-0740
- https://talosintelligence.com/vulnerability_reports/TALOS-2018-0741
- https://talosintelligence.com/vulnerability_reports/TALOS-2019-0769
- https://talosintelligence.com/vulnerability_reports/TALOS-2018-0742
- https://talosintelligence.com/vulnerability_reports/TALOS-2019-0770
- https://talosintelligence.com/vulnerability_reports/TALOS-2019-0767
- https://talosintelligence.com/vulnerability_reports/TALOS-2019-0868
- https://talosintelligence.com/vulnerability_reports/TALOS-2019-0825
- https://talosintelligence.com/vulnerability_reports/TALOS-2019-0827
- https://talosintelligence.com/vulnerability_reports/TALOS-2019-0847
- https://talosintelligence.com/vulnerability_reports/TALOS-2019-0822
- https://talosintelligence.com/vulnerability_reports/TALOS-2019-0824
- https://talosintelligence.com/vulnerability_reports/TALOS-2020-1174
- https://talosintelligence.com/vulnerability_reports/TALOS-2020-1184
- https://talosintelligence.com/vulnerability_reports/TALOS-2020-1008
- https://talosintelligence.com/vulnerability_reports/TALOS-2020-1169
- https://talosintelligence.com/vulnerability_reports/TALOS-2020-1168
- https://talosintelligence.com/vulnerability_reports/TALOS-2021-1236
- https://talosintelligence.com/vulnerability_reports/TALOS-2021-1273
- https://talosintelligence.com/vulnerability_reports/TALOS-2021-1271
- https://talosintelligence.com/vulnerability_reports/TALOS-2021-1272
- https://talosintelligence.com/vulnerability_reports/TALOS-2021-1270
- https://talosintelligence.com/vulnerability_reports/TALOS-2021-1274
- https://talosintelligence.com/vulnerability_reports/TALOS-2021-1306
- https://talosintelligence.com/vulnerability_reports/TALOS-2021-1304
- https://talosintelligence.com/vulnerability_reports/TALOS-2021-1303
- https://talosintelligence.com/vulnerability_reports/TALOS-2021-1301
- https://talosintelligence.com/vulnerability_reports/TALOS-2021-1302
- https://talosintelligence.com/vulnerability_reports/TALOS-2021-1300
- https://talosintelligence.com/vulnerability_reports/TALOS-2021-1305


----------
**Have a writeup that can fit here, feel free to raise a Pull Request. :octocat:** 

*To-do*

- [ ] Classify writeups under separate sections.
- [ ] Add details classification to each writeup.
- [ ] Add Contributing Instructions.
- [ ] Add Conference Talks on ICS/OT/IIoT
