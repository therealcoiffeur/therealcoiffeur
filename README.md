<div align="center">

# Security Research & Offensive Engineering 

**Vulnerability Research · Exploit Development · Red Teaming** 

I explore attack surfaces, develop exploitation techniques, and build offensive security tooling.

[Research](#research) · [Red Teaming](#red-teaming) · [Website](https://therealcoiffeur.com/) · [Conference & Talks](https://github.com/therealcoiffeur/Conferences)

</div>

## Research 🦜

*Some of my personal public vulnerability research, exploitation techniques and tooling.*

| Research area | Project | Technical focus |
| --- | --- | --- |
| **Vulnerability Research** | **[Corporate Articles](https://github.com/therealcoiffeur/Corporate-Articles)** | Published vulnerability research targeting web applications, macOS and telecommunications network equipment. |
| **Advanced Exploitation** | **[Conferences](https://github.com/therealcoiffeur/Conferences)** | Conference presentations on vulnerability research and advanced exploitation techniques. |
| **macOS Security Research** | **[mtm](https://github.com/therealcoiffeur/mtm)** (**[live](https://therealcoiffeur.github.io/mtm_static/))** | Local macOS attack-surface mapping. |
| **Race Condition Exploitation** | **[SlowHorses](https://github.com/therealcoiffeur/SlowHorses)** | Research tooling for exploiting race conditions by extending timing windows in PHP applications. |

Over the years, I have explored a wide range of operating systems, frameworks, applications, and network equipment, uncovering vulnerabilities and developing exploits along the way. For full details visit [therealcoiffeur.com](https://therealcoiffeur.com/public/).

<details>
<summary><b>View all</b></summary>

<h3>OS & Applications</h3>

<table>
  <tbody>
    <tr>
      <td>Apple macOS</td>
      <td>Linux</td>
      <td>PHP</td>
    </tr>
    <tr>
      <td>VMware Fusion</td>
      <td>Mistral AI</td>
      <td>Cato Networks</td>
    </tr>
  </tbody>
</table>

<h3>Embedded & Network Devices</h3>

<table>
  <tbody>
    <tr>
      <td>D-Link</td>
      <td>Netgear</td>
      <td>Qnap</td>
    </tr>
  </tbody>
</table>

<h3>Web Application</h3>

<table>
  <tbody>
    <tr>
      <td>AfterLogic</td>
      <td>Bolt CMS</td>
      <td>CodeIgniter4</td>
    </tr>
    <tr>
      <td>Dolibarr</td>
      <td>Dompdf</td>
      <td>Drupal</td>
    </tr>
    <tr>
      <td>Jolokia</td>
      <td>mPDF</td>
      <td>PHPBoost CMS</td>
    </tr>
    <tr>
      <td>PHPFusion</td>
      <td>PHPWord</td>
      <td>PROJECTWORLDS</td>
    </tr>
    <tr>
      <td>Rukovoditel</td>
      <td>Sendy</td>
      <td>Snappy</td>
    </tr>
    <tr>
      <td>SPIP</td>
      <td>Squiz Matrix</td>
      <td>Symfony</td>
    </tr>
    <tr>
      <td>Typo3</td>
      <td>vBulletin</td>
      <td>Wansview</td>
    </tr>
    <tr>
      <td>Wordpress</td>
      <td>YesWiki</td>
      <td>Zabbix</td>
    </tr>
  </tbody>
</table>

</details>

### Corporate Research & Publications

Technical articles published through professional research,
security assessments, and Red Team engagements.

<details>
<summary><strong>View published articles</strong></summary>

<h4>OS & Application</h4>

<table>
  <tbody>
    <tr>
      <td><a href="https://blog.quarkslab.com/ccleaner_lpe_macos.html">CCleaner</a></td>
      <td><a href="https://blog.quarkslab.com/controlplane_lpe_macos.html">ControlPlane</a></td>
      <td><a href="https://blog.quarkslab.com/exploiting-microsoft-teams-on-macos-during-a-purple-team-engagement.html">Microsoft Teams</a></td>
    </tr>
    <tr>
      <td><a href="https://blog.quarkslab.com/intego_lpe_macos_1.html">Intego X9 (Part 1)</a></td>
      <td><a href="https://blog.quarkslab.com/intego_lpe_macos_2.html">Intego X9 (Part 2)</a></td>
      <td><a href="https://blog.quarkslab.com/intego_lpe_macos_3.html">Intego X9 (Part 3)</a></td>
    </tr>
  </tbody>
</table>

<h4>Embedded & Network Devices</h4>

<table>
  <tbody>
    <tr>
      <td><a href="https://blog.quarkslab.com/how-olts-may-have-exposed-entire-isp-networks.html">VSOL OLTs / Cloud EMS</a></td>
    </tr>
  </tbody>
</table>

<h4>Web Application</h4>

<table>
  <tbody>
    <tr>
      <td><a href="https://blog.quarkslab.com/bypass-apache-superset-restrictions-to-perform-sql-injections.html">Apache Superset</a></td>
      <td><a href="https://blog.quarkslab.com/exploiting-chamilo-during-a-red-team-engagement.html">Chamilo (2024)</a></td>
      <td><a href="https://blog.quarkslab.com/chamilo-lms-its-raining-0days-hallelujah-its-raining-0days.html">Chamilo (2026)</a></td>
    </tr>
    <tr>
      <td><a href="https://blog.quarkslab.com/exploiting-glpi-during-a-red-team-engagement.html">GLPI</a></td>
      <td><a href="https://blog.quarkslab.com/php-deserialization-attacks-and-a-new-gadget-chain-in-laravel.html">Laravel</a></td>
      <td><a href="https://blog.quarkslab.com/auditing-moodles-core-hunting-for-logical-bugs.html">Moodle</a></td>
    </tr>
    <tr>
      <td><a href="https://blog.quarkslab.com/pwn-everything-bounce-everywhere-all-at-once-part-1.html">phpMyAdmin</a></td>
      <td><a href="https://blog.quarkslab.com/pwn-everything-bounce-everywhere-all-at-once-part-2.html">SOPlanning</a></td>
      <td><a href="https://blog.quarkslab.com/looking-for-vulnerabilities-in-strapi-cve-2024-34065.html">Strapi</a></td>
    </tr>
  </tbody>
</table>

</details>

## Red Teaming 🏴‍☠️

*Some of my personal public offensive security tools spanning reconnaissance, initial access, implant staging, and persistence.*

| Phase | Project | Technical focus |
| --- | --- | --- |
| **Reconnaissance** | **[GhostReconRev](https://github.com/therealcoiffeur/GhostReconRev)** | Automated reconnaissance, asset discovery, service enumeration, and evidence collection. |
| **Initial Access** | **[MalGit](https://github.com/therealcoiffeur/MalGit)** | Git configuration abuse and Remote Code Execution techniques for initial access. |
| **Implant Staging** | **[SNet](https://github.com/therealcoiffeur/SNet)** | macOS payload staging, RAM-backed execution, in-memory Mach-O loading. |
| **Implant Staging** | **[PyleLess](https://github.com/therealcoiffeur/PyleLess)** | Linux fileless stager. |
| **Persistence** | **[CapabiliTricks](https://github.com/therealcoiffeur/CapabiliTricks)** | Linux capabilities abuse for privileged persistence. |
