<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=30&duration=3000&pause=800&color=FF0000&center=true&vCenter=true&width=700&lines=Hi%2C+I'm+Happy+Ramani+%F0%9F%91%8B;Splunk+Engineer+%40+CrossRealms;SIEM+%C2%B7+Data+Onboarding+%C2%B7+Automation" alt="Happy Ramani" />

<p>
<em>I make machine data useful — onboarding it cleanly, alerting on what matters,<br/>and automating the parts nobody should be doing by hand.</em>
</p>

<a href="mailto:happyramani86@gmail.com"><img src="https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=gmail&logoColor=FF0000" alt="email" /></a>
<img src="https://komarev.com/ghpvc/?username=cr-hramani&style=for-the-badge&color=FF0000&label=PROFILE+VIEWS" alt="profile views" />

</div>

---

### `~/whoami`

```yaml
role:      Splunk Engineer @ CrossRealms International
focus:     SIEM engineering, data onboarding, detection content, automation
domains:   banking · fintech · enterprise security operations
scale:     multi-site indexer clusters, search head clusters, distributed deployments
approach:  fix the pipeline, not the symptom — parsing, timestamps, and trust
           problems cause more "Splunk is broken" tickets than Splunk ever does
```

---

### What I actually do

- **Data onboarding that survives contact with reality** — `props.conf` / `transforms.conf` tuning, line breaking, timestamp and timezone correctness, sourcetype design, and the CIM mapping that makes it all searchable
- **SIEM engineering** — correlation searches, notable events, alert suppression and lifecycle, integration with ITSM and ticketing
- **Syslog architecture** — syslog-ng collectors feeding Splunk at scale, per-source routing, disk buffering, and the boring reliability work that prevents silent data loss
- **Splunk app & TA development** — custom search commands, modular inputs, REST handlers, dashboards in Simple XML and Studio
- **Automation** — Ansible-driven environment configuration, Python tooling, and Git-backed config management across customer estates

---

### Toolbox

**Splunk**

<img src="https://img.shields.io/badge/Splunk_Enterprise-000000?style=for-the-badge&logo=splunk&logoColor=FF0000" />
<img src="https://img.shields.io/badge/SPL-0D1117?style=for-the-badge&logoColor=FF0000" />
<img src="https://img.shields.io/badge/Splunk_ES-0D1117?style=for-the-badge&logoColor=FF0000" />
<img src="https://img.shields.io/badge/DB_Connect-0D1117?style=for-the-badge&logoColor=FF0000" />
<img src="https://img.shields.io/badge/Data_Models-0D1117?style=for-the-badge&logoColor=FF0000" />

**Languages & Scripting**

<img src="https://img.shields.io/badge/Python-0D1117?style=for-the-badge&logo=python&logoColor=FF0000" />
<img src="https://img.shields.io/badge/Bash-0D1117?style=for-the-badge&logo=gnubash&logoColor=FF0000" />
<img src="https://img.shields.io/badge/PowerShell-0D1117?style=for-the-badge&logo=powershell&logoColor=FF0000" />
<img src="https://img.shields.io/badge/Regex-0D1117?style=for-the-badge&logo=regex&logoColor=FF0000" />

**Platforms & Infrastructure**

<img src="https://img.shields.io/badge/Linux-0D1117?style=for-the-badge&logo=linux&logoColor=FF0000" />
<img src="https://img.shields.io/badge/RHEL-0D1117?style=for-the-badge&logo=redhat&logoColor=FF0000" />
<img src="https://img.shields.io/badge/Ubuntu-0D1117?style=for-the-badge&logo=ubuntu&logoColor=FF0000" />
<img src="https://img.shields.io/badge/AWS-0D1117?style=for-the-badge&logo=amazonaws&logoColor=FF0000" />
<img src="https://img.shields.io/badge/Docker-0D1117?style=for-the-badge&logo=docker&logoColor=FF0000" />
<img src="https://img.shields.io/badge/syslog--ng-0D1117?style=for-the-badge&logoColor=FF0000" />

**Automation & Workflow**

<img src="https://img.shields.io/badge/Ansible-0D1117?style=for-the-badge&logo=ansible&logoColor=FF0000" />
<img src="https://img.shields.io/badge/Git-0D1117?style=for-the-badge&logo=git&logoColor=FF0000" />
<img src="https://img.shields.io/badge/GitHub_Actions-0D1117?style=for-the-badge&logo=githubactions&logoColor=FF0000" />
<img src="https://img.shields.io/badge/Jira-0D1117?style=for-the-badge&logo=jira&logoColor=FF0000" />

---

### Things I've learned the hard way

> A `LINE_BREAKER` that doesn't match your data doesn't fail loudly — it silently truncates 99% of every batch and reports success.

> `TZ` in `props.conf` describes the timezone the raw string is *written* in, not the one you want to *see* it in. Getting that backwards costs you three hours, literally.

> If two services fight over a port, whoever binds first wins — and the loser takes every other input on that daemon down with it.

---

<div align="center">

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=cr-hramani&bg_color=0D1117&color=FFFFFF&line=FF0000&point=FF0000&area=true&area_color=3A0D0D&hide_border=true" alt="contribution graph" />

<br/>

**Got a Splunk problem that doesn't make sense?** I probably enjoy those.

<a href="mailto:happyramani86@gmail.com"><img src="https://img.shields.io/badge/Get_in_touch-FF0000?style=for-the-badge&logo=minutemailer&logoColor=white" alt="contact" /></a>

</div>
