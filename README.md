# Lightspin 2022 Top Seven Cloud Attack Paths

At Lightspin, our graph-based technology views cloud environments from the perspective of the potential attacker to provide a comprehensive view of imposed risks and assets. By connecting the dots between environments and asking specific context-related questions to understand the criticality of the possible exploitable vulnerabilities, Lightspin empowers organizations with the focus and prioritization they need to remediate the critical attack paths that matter most in their environments.

Based on Lightspin proprietary data, research, and our tracking of cloud security trends in the market, our research team has compiled a list of the 2022 Top 7 Cloud Attack Paths across AWS, Azure, GCP, and Kubernetes as seen on the Lightspin Cloud Native Application Protection Platform (CNAPP). The attack paths were selected based on frequency, criticality, and impact. Our attack paths are based on Lightspin’s cloud attack path taxonomy and tie to the [MITRE ATT&CK Cloud Matrix for Enterprise](https://attack.mitre.org/). This repo includes the applicable MITRE ATT&CK TTPs with formatting in `.xls`, `.json`, and `.svg` vended from the [MITRE ATT&CK Navigator](https://mitre-attack.github.io/attack-navigator/) for easy reference and utility in reproduction, table-top exercises, threat modeling, etc.

## On MITRE Mappings

Based on research conducted by the Lightspin team on aggregated data within the Lightspin CNAPP as well open and closed source research related to our Top Seven Attack Paths, we mapped out MITRE ATT&CK Techniques based on what was observed and what would be feasible for an adversary to carry out in a public cloud environment. The mappings sought to strike a balance being overly exhaustive and too precautius, our intention is for external teams to use our research along with the MITRE ATT&CK mappings to conduct table-top and live exercises to assess their own cloud defenses. You can supplement these exercises with our open-source offerings such as [Red-Kube](https://github.com/lightspin-tech/red-kube) and our free offerings such as [Recon.cloud](https://recon.cloud/) for higher fidelity cloud-specific findings an adversary can possibly see or employ against you.

## Attack Paths

1. [Exploitable public workload leading to privilege escalation](./exploitable-public-workload-priv-esc/)
2. [Private workload with admin permissions](./private-workload-admin/)
3. [Cleartext cloud credentials discovered on workload](./cleartext-creds-on-workload/)
4. [Identity with bad hygiene](./identity-bad-hygeine/)
5. [Unauthenticated public access to data store](./unauthenticated-public-datastore/)
6. [3rd party cross environment / account access leading to privilege escalation](./3rd-party-cross-env-priv-esc/)
7. [SSH keys discovered on workload leading to lateral movement](./ssh-keys-lateral-movement/)