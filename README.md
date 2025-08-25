# Awesome ICS/SCADA Writeups

![awesome badge](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
![GitHub Repo stars](https://img.shields.io/github/stars/neutrinoguy/awesome-ics-writeups?style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/neutrinoguy/awesome-ics-writeups?style=flat-square)
----------

A collection of writeups related to ICS/SCADA hacking. This covers areas like OT, IoT and IIoT. It includes exploitation writeups, vendor blogs, talks, CTF writeups etc. 

:new: Awesome ICS/SCADA/OT related videos can be found here: [Awesome-ICS-Videos](awesome-ics-videos.md)

:full_moon: = Full details 
:first_quarter_moon: = Partial details
:new_moon: = No details 

:warning: **Disclaimer: The work linked here is solely owned by the respective authors. This is just a collection of them.** :warning:

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

### AWESEC
- https://awesec.com/advisories/AWE-2022-059.html



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
- https://claroty.com/team82/research/white-papers/evil-plc-attack-weaponizing-plcs
- https://claroty.com/team82/research/jumping-nat-to-shut-down-electric-devices
- https://claroty.com/team82/research/the-race-to-native-code-execution-in-plcs-using-rce-to-uncover-siemens-simatic-s7-1200-1500-hardcoded-cryptographic-keys
- https://claroty.com/team82/research/an-oil-and-gas-weak-spot-flow-computers
- https://claroty.com/team82/research/hacking-ics-historians-the-pivot-point-from-it-to-ot
- https://claroty.com/team82/research/the-silent-spy-among-us-modern-attacks-against-smart-intercoms
- https://claroty.com/team82/research/triple-threat-breaking-teltonika-routers-three-ways
- https://claroty.com/team82/research/the-path-to-the-cloud-is-filled-with-holes-exploiting-4g-edge-routers
- https://claroty.com/team82/research/dicom-demystified-exploring-the-underbelly-of-medical-imaging
- https://claroty.com/team82/research/opc-ua-deep-dive-history-of-the-opc-ua-protocol (OPC-UA Series)
- https://claroty.com/team82/research/unpacking-the-blackjack-groups-fuxnet-malware (ICS Malware)
- https://claroty.com/team82/research/exploiting-a-classic-deserialization-vulnerability-in-siemens-simatic-energy-manager
- https://claroty.com/team82/research/exploiting-honeywell-controledge-virtualuoc 
- https://claroty.com/team82/research/threat-modeling-industrial-environments-using-virtual-factories-part-1
- https://claroty.com/team82/research/practical-and-theoretical-attacks-in-the-industrial-landscape-part-2
- https://claroty.com/team82/research/bypassing-rockwell-automation-logix-controllers-local-chassis-security-protection
- https://claroty.com/team82/research/mms-under-the-microscope-examining-the-security-of-a-power-automation-standard
- https://claroty.com/team82/research/delving-into-windows-ce-lets-build-an-embedded-windows-application
- https://claroty.com/team82/research/delving-into-windows-ce-part-2-analyzing-windows-ce-debugging-constructs
- https://claroty.com/team82/research/hack-the-emulated-planet-vulnerability-hunting-on-planet-wgs-804hpt-industrial-switches
- https://claroty.com/team82/research/the-insecure-iot-cloud-strikes-again-rce-on-ruijie-cloud-connected-devices
- https://claroty.com/team82/research/inside-a-new-ot-iot-cyber-weapon-iocontrol (ICS Malware)
- https://claroty.com/team82/research/delving-into-windows-ce-lets-build-an-embedded-windows-application
- https://claroty.com/team82/research/delving-into-windows-ce-part-2-analyzing-windows-ce-debugging-constructs
- https://claroty.com/team82/research/delving-into-windows-ce-part3-introducing-team82s-open-source-debugger
- https://claroty.com/team82/research/delving-into-windows-ce-part-4-vulnerability-research-into-a-windows-ce-based-hmi-used-in-the-wild
- https://claroty.com/team82/research/attention-high-voltage-exploring-the-attack-surface-of-the-rockwell-automation-powermonitor-1000
- https://claroty.com/team82/research/cascading-chaos-a-got-oriented-exploit-story
- https://claroty.com/team82/research/turning-camera-surveillance-on-its-axis




### Compass Security
- https://blog.compass-security.com/2024/03/pwn2own-toronto-2023-part-1-how-it-all-started/
- https://blog.compass-security.com/2024/03/pwn2own-toronto-2023-part-2-exploring-the-attack-surface/
- https://blog.compass-security.com/2024/03/pwn2own-toronto-2023-part-3-exploration/
- https://blog.compass-security.com/2024/03/pwn2own-toronto-2023-part-4-memory-corruption-analysis/
- https://blog.compass-security.com/2024/03/pwn2own-toronto-2023-part-5-the-exploit/
- https://blog.compass-security.com/2024/08/a-patchdiffing-journey-tp-link-omada/


### CrowdStrike
- https://www.crowdstrike.com/blog/how-to-pwn2own-the-cisco-rv340-router/


### CyberDanube
- https://cyberdanube.com/security-research/authenticated-remote-code-execution-in-ewon-flexy-205/
- https://cyberdanube.com/security-research/multiple-vulnerabilities-in-abb-ac500v3/
- https://cyberdanube.com/security-research/st-polten-uas-path-traversal-in-korenix-jetport/
- https://cyberdanube.com/security-research/st-polten-uas-stored-cross-site-scripting-in-seh-utnserver-pro/
- https://cyberdanube.com/security-research/st-polten-uas-multiple-vulnerabilities-in-oring-iap/
- https://cyberdanube.com/security-research/multiple-vulnerabilities-in-riello-netman-204/
- https://cyberdanube.com/security-research/authenticated-command-injection-in-helmholz-rex100-router/
- https://cyberdanube.com/security-research/multiple-vulnerabilities-in-perten-processplus/
- https://cyberdanube.com/security-research/multiple-vulnerabilities-in-korenix-jetport/
- https://cyberdanube.com/security-research/multiple-vulnerabilities-in-seh-untserver-pro/
- https://cyberdanube.com/security-research/multiple-vulnerabilities-in-advantech-eki-15xx-series/
- https://cyberdanube.com/security-research/authenticated-command-injection-in-hirschmann-belden-bat-c2/
- https://cyberdanube.com/security-research/multiple-vulnerabilities-in-delta-electronics-dx-2100-l1-cn/
- https://cyberdanube.com/security-research/authenticated-command-injection-in-delta-electronics-dvw-w02w2-e2/
- https://cyberdanube.com/security-research/multiple-cyber-security-iot-vulnerabilities-in-industrial-router/


### CyberArk
- https://www.cyberark.com/resources/threat-research-blog/bug-hunting-stories-schneider-electric-the-andover-continuum-web-client

### Cynerio
- https://assets.website-files.com/5d2ad783e06f4c19469d363a/625551dd440d0b187fa96d38_JekyllBot-5-Vulnerability-Disclosure-Report.pdf

### Dragos
- https://hub.dragos.com/hubfs/116-Whitepapers/Dragos_ChernoviteWP_v2b.pdf [Malware]
- https://www.dragos.com/blog/industry-news/chernovite-pipedream-malware-targeting-industrial-control-systems/
- https://hub.dragos.com/hubfs/116-Whitepapers/Dragos_SB_COSMICENERGY_June23_FINAL_WEB.pdf [Malware]

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
 - https://www.tenable.com/security/research/tra-2022-33
 - https://www.tenable.com/security/research/tra-2022-32
 - https://www.tenable.com/security/research/tra-2022-23
 - https://www.tenable.com/security/research/tra-2022-22
 - https://www.tenable.com/security/research/tra-2022-13
 - https://www.tenable.com/security/research/tra-2023-13
 - https://www.tenable.com/security/research/tra-2022-22


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
- https://ics-cert.kaspersky.com/publications/reports/2022/09/29/the-secrets-of-schneider-electrics-umas-protocol/


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
- https://research.nccgroup.com/wp-content/uploads/2022/07/pwn2own-3-bugs-technical-external.pdf
- https://research.nccgroup.com/wp-content/uploads/2022/07/pwn2own-how-to-win-external.pdf 


### Onekey
- https://onekey.com/blog/advisory-festo-cecc-x-m1-command-injection-vulnerabilities/
- https://onekey.com/blog/security-advisory-wago-unauthenticated-config-export-vulnerability/
- https://onekey.com/blog/security-advisory-netmodule-multiple-vulnerabilities/ 


### OTORIO
- https://www.otorio.com/blog/airlink-acemanager-vulnerabilities/
- https://go.otorio.com/hubfs/Whitepapers%20and%20Reports/whitepaper%20-%20Industrial%20wireless%20IoT%20research.pdf
- https://www.otorio.com/blog/exploiting-automation-license-manager-using-dfs-for-pcs-7-takeover/
- https://www.otorio.com/blog/hijacking-abb-800xa-communication-for-admin-privileges/


### Palo Alto
- https://unit42.paloaltonetworks.com/vulnerabilities-in-iconics-software-suite/



### Zero day Initiative
 - https://www.zerodayinitiative.com/blog/2020/8/24/cve-2020-10611-achieving-code-execution-on-the-triangle-microworks-scada-data-gateway 
 - https://www.zerodayinitiative.com/blog/2020/6/10/a-trio-of-bugs-used-to-exploit-inductive-automation-at-pwn2own-miami 
 - https://www.thezdi.com/blog/2020/9/30/the-anatomy-of-a-bug-door-dissecting-two-d-link-router-authentication-bypasses 
 - https://www.thezdi.com/blog/2020/7/22/chaining-5-bugs-for-code-execution-on-the-rockwell-factorytalk-hmi-at-pwn2own-miami
 - https://www.zerodayinitiative.com/blog/2020/1/15/reliably-finding-and-exploiting-icsscada-bugs
 - https://www.thezdi.com/blog/2020/9/9/performing-sql-backflips-to-achieve-code-execution-on-schneider-electrics-ecostruxure-operator-terminal-expert-at-pwn2own-miami-2020
 - https://www.zerodayinitiative.com/blog/2023/2/6/pwn2owning-two-hosts-at-the-same-time-abusing-inductive-automation-ignitions-custom-deserialization
 - https://www.zerodayinitiative.com/blog/2023/9/7/looking-at-the-chargepoint-home-flex-threat-landscape
 - https://www.zerodayinitiative.com/blog/2024/10/2/from-pwn2own-automotive-more-autel-maxicharger-vulnerabilities
 - https://www.zerodayinitiative.com/blog/2024/8/22/from-pwn2own-automotive-taking-over-the-autel-maxicharger
 - https://www.zerodayinitiative.com/blog/2024/7/25/multiple-vulnerabilities-in-the-deep-sea-electronics-dse855
 - https://www.zerodayinitiative.com/blog/2024/5/23/mindshare-decapping-chips-for-electromagnetic-fault-injection-emfi
 - https://www.zerodayinitiative.com/blog/2025/6/18/extracting-embedded-multimediacard-emmc-contents-in-system


### Jfrog (Vdoo)
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
- https://www.nozominetworks.com/blog/how-iot-botnets-evade-detection-and-analysis/ [Malware]
- https://www.nozominetworks.com/blog/how-iot-botnets-evade-detection-and-analysis-part-2/ [Malware]
- https://www.nozominetworks.com/blog/vulnerabilities-in-bmc-firmware-affect-ot-iot-device-security-part-1/
- https://www.nozominetworks.com/blog/flaws-in-hitachi-relion-650-670-series-ieds-update-mechanism/
- https://www.nozominetworks.com/blog/protecting-the-phoenix-unveiling-critical-vulnerabilities-in-phoenix-contact-hmi-part-3
- https://www.nozominetworks.com/blog/dji-mavic-3-drone-research-part-1-firmware-analysis
- https://www.nozominetworks.com/blog/dji-mavic-3-drone-research-part-2-vulnerability-analysis
- https://www.nozominetworks.com/blog/critical-vulnerabilities-found-in-tridium-niagara-framework


### Mandiant
- https://www.mandiant.com/resources/incontroller-state-sponsored-ics-tool [Malware]
- https://www.mandiant.com/resources/industroyer-v2-old-malware-new-tricks [Malware]
- https://www.mandiant.com/resources/blog/sandworm-disrupts-power-ukraine-operational-technology [APT]  
- https://cloud.google.com/blog/topics/threat-intelligence/securing-protection-relays-modern-substations

### Medigate
- https://www.medigate.io/lexmark-printers-firmware-extraction-part-a/
- https://www.medigate.io/lexmark-printers-firmware-extraction-part-b/
- https://www.medigate.io/lexmark-printers-firmware-extraction-part-c/

### Microsoft
- https://msrc-blog.microsoft.com/2021/04/29/badalloc-memory-allocation-vulnerabilities-could-affect-wide-range-of-iot-and-ot-devices-in-industrial-medical-and-enterprise-networks/


### Rapid-7
- https://www.rapid7.com/blog/post/2019/12/09/how-i-shut-down-a-test-factory-with-a-single-layer-2-packet/


### Redballoon Security 
- https://redballoonsecurity.com/siemens-discovery/

### Redfox Security
- https://redfoxsec.com/blog/plc-hacking-part-1/
- https://redfoxsec.com/blog/plc-hacking-part-2/


### Saiflow 
- https://www.saiflow.com/how-mishandling-of-websockets-can-cause-dos-and-energy-theft/
- https://www.saiflow.com/hijacking-chargers-identifier-to-cause-dos/
- https://www.saiflow.com/the-impact-of-api-vulnerabilities-on-csms-services-charging-network-operators-the-use-case-of-abb-chargersync/
- https://www.saiflow.com/abb-terra-ac-improper-authentication-can-lead-to-evse-takeover-cve-2023-0863-cve-2023-0864/


### Scadafence
- https://www.scadafence.com/wp-content/uploads/2022/04/SCADAfence-Hack-The-Port-Report-2022.pdf [Whitepaper]
- https://blog.scadafence.com/scadafence-discovers-first-cves-detected-in-alerton-plcs

### Sector7
- https://sector7.computest.nl/post/2022-07-opc-ua-net-standard-trusted-application-check-bypass/
- https://sector7.computest.nl/post/2022-07-inductive-automation-ignition-rce/

### SSD Disclousre 
- https://ssd-disclosure.com/ssd-advisory-hongdian-h8922-multiple-vulnerabilities/


### WeLiveSecurity
- https://www.welivesecurity.com/wp-content/uploads/2018/10/ESET_GreyEnergy.pdf [Malware]
- https://www.welivesecurity.com/2022/04/12/industroyer2-industroyer-reloaded/ [Malware]

### Viettel Security 
- https://blog.viettelcybersecurity.com/security-wall-of-s7commplus-part-1/
- https://blog.viettelcybersecurity.com/security-wall-of-s7commplus-3/


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
- https://trenchant.io/two-lines-of-jscript-for-20000-pwn2own-miami-2022/
- https://guillaumebour.fr/articles/security_testing_pacemaker_ecosystem/part_1_introduction_context_methodology/ (5 Part Series)
- https://www.mnemonic.io/resources/blog/reverse-engineering-an-ev-charger/
- https://www.guidepointsecurity.com/blog/guidepoint-security-researcher-discovers-vulnerability-in-the-integrity-of-common-hmi-client-server-protocol/
- https://trenchant.io/two-lines-of-jscript-for-20000-pwn2own-miami-2022/
- https://starlabs.sg/blog/2023/02-gotta-kep-tcha-em-all-bypassing-anti-debugging-methods-in-kepserver/
- https://www.reversemode.com/2023/04/losing-control-over-schneiders.html
- https://eclypsium.com/blog/vendor-re-use-opens-the-aperture-on-many-vulnerabilities/
- https://vulncheck.com/blog/solarview-exploitation
- https://www.sentinelone.com/labs/acidrain-a-modem-wiper-rains-down-on-europe/ [Malware]
- https://adlumin.com/post/powerdrop-a-new-insidious-powershell-script-for-command-and-control-attacks-targets-u-s-aerospace-defense-industry/ [Malware]
- https://duck.moe/blog/blutacc/ 
- https://sektorcert.dk/wp-content/uploads/2023/11/SektorCERT-The-attack-against-Danish-critical-infrastructure-TLP-CLEAR.pdf [APT]
- https://petrusviet.medium.com/cve-2023-50220-inductive-automation-ignition-xml-deserialization-to-rce-7b395412c6cf
- https://eclypsium.com/blog/flatlined-analyzing-pulse-secure-firmware-and-bypassing-integrity-checking/
- https://www.shielder.com/blog/2022/03/reversing-embedded-device-bootloader-u-boot-p.1/


 
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
