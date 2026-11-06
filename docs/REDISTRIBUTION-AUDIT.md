# Third-Party Mod Redistribution Audit

**Pack:** Buns & Bush: ZepheirWinds Edition  
**Pack version:** 1.0.0  
**Minecraft:** 1.21.1  
**Loader:** NeoForge 21.1.265  
**Distribution under review:** Private GitHub Release containing a Prism Launcher instance export ZIP  
**Audit status:** In progress — not clearance to redistribute every bundled JAR

## Purpose and scope

This register tracks the third-party mod files included in the v1.0.0 instance export and the public licensing or modpack-permission information located for their projects.

A download through Prism Launcher identifies the installation method, not necessarily the original file host or the permission to re-host the downloaded JAR. Prism's built-in mod downloader can obtain files from different providers. The exact provider and exact file must be checked where platform-specific permission is relied upon.

This review distinguishes:

- **License permits redistribution:** the identified project license appears to allow redistribution, subject to its notice, attribution, source-code, and other requirements.
- **Conditional / author permission:** the project page permits modpack use or redistribution only under stated conditions. Conditions must be followed.
- **Do not bundle pending permission:** the project is marked All Rights Reserved or explicitly prohibits reposting, and no applicable permission for this GitHub ZIP has been established.
- **Unverified:** the exact project, file version, applicable license, or permission has not yet been confirmed.

A project's Modrinth or CurseForge presence alone is not treated as blanket permission to upload its JAR to a separate GitHub-hosted ZIP. Platform-specific modpack permissions must be read within their stated scope. This is an informational compliance review, not legal advice.

## Findings verified so far

| Included file | Project identified | Public license / permission found | Preliminary treatment | Evidence |
|---|---|---|---|---|
| `ae2wtlib-19.5.1.jar` | Applied Energistics 2 Wireless Terminals (AE2WTLib) | Modrinth project lists MIT. | License permits redistribution, subject to retaining the MIT copyright and license notice. Confirm the exact 19.5.1 artifact and source. | https://modrinth.com/mod/applied-energistics-2-wireless-terminals |
| `aether-1.21.1-1.5.10-neoforge.jar` | The Aether | Modrinth lists a Custom license; the exact custom terms and bundled asset rights still need review. | Unverified — do not assume the code license covers all assets or the whole JAR. | https://modrinth.com/mod/aether |
| `Apotheosis-1.21.1-8.9.0.jar` | Apotheosis | Current Modrinth project page lists MIT. This corrects an earlier preliminary note that incorrectly described it as ARR. | License appears to permit redistribution, subject to retaining notices. Confirm the license for the exact 8.9.0 release. | https://modrinth.com/mod/apotheosis |
| `artifacts-neoforge-13.2.5.jar` | Artifacts | Modrinth project lists MIT. | License appears to permit redistribution, subject to retaining notices. Confirm exact artifact/source. | https://modrinth.com/mod/artifacts |
| `bettercombat-neoforge-2.4.0+1.21.1.jar` | Better Combat | Modrinth project lists ARR. No separate permission for re-hosting this JAR on GitHub has been established. | Do not bundle pending explicit permission or a verified applicable author grant. | https://modrinth.com/mod/better-combat |
| `comforts-neoforge-9.0.5+1.21.1.jar` | Comforts | Modrinth project lists LGPL-3.0-or-later. | License appears to permit redistribution if LGPL obligations are met, including preserving notices and providing the applicable license/source access. Confirm exact artifact. | https://modrinth.com/mod/comforts |
| `create-1.21.1-6.0.10.jar` | Create | Modrinth project lists the custom Create Mod License, not a standard MIT/Apache license. | Unverified until the custom license text and exact release terms are reviewed. | https://modrinth.com/mod/create |
| `Create Encased-1.21.1-1.10.0-fix1.jar` | Create Encased | Project states modpack use is allowed but reposting the mod on another website is not. | Do not bundle in the GitHub ZIP. Have Prism users download it from its official CurseForge or Modrinth project instead. | https://modrinth.com/mod/create-encased |
| `create-central-kitchen-2.6.2b.jar` | Create: Central Kitchen | Modrinth project lists LGPL-3.0-or-later. | License appears to permit redistribution if LGPL obligations are met. Confirm this exact file/version and notices. | https://modrinth.com/mod/create-central-kitchen |
| `create-enchantment-industry-2.5.4b.jar` | Create: Enchantment Industry / possible legacy fork | Current project page lists LGPL-3.0-or-later, but the filename/version may correspond to a legacy or separate 1.21.1 NeoForge build. | Unverified until the exact project and release are matched. | https://modrinth.com/mod/create-enchantment-industry |
| `createdeco-2.1.3.jar` | Create Deco | Modrinth project lists MIT. | License appears to permit redistribution, subject to retaining notices. Confirm exact artifact/source. | https://modrinth.com/mod/create-deco |
| `FarmersDelight-1.21.1-1.3.4.jar` | Farmer's Delight | Modrinth project lists MIT and its description expressly permits modpack use with credit. | License appears to permit redistribution; include required copyright/license notice and credit. | https://modrinth.com/mod/farmers-delight |
| `farmersrespite-1.21.1-3.0.1.jar` | Farmer's Respite (project match/version not yet confirmed) | A similarly named Modrinth project currently lists ARR and does not establish permission for this exact NeoForge 1.21.1 file. | Unverified — exact project and author terms must be matched before bundling. | https://modrinth.com/project/farmers-respite |
| `irons_spellbooks-1.21.1-3.16.3.jar` | Iron's Spells 'n Spellbooks | Modrinth project lists ARR. No GitHub re-hosting permission has been established. | Do not bundle pending explicit permission. | https://modrinth.com/mod/irons-spells-n-spellbooks |
| `Jade-1.21.1-NeoForge-15.10.6.jar` | Jade | Modrinth project lists CC-BY-NC-SA-4.0. | Conditional: retain attribution and license notices, indicate changes if any, share adaptations under the same license, and do not use commercially. Confirm scope of any included assets. | https://modrinth.com/mod/jade |
| `jei-1.21.1-neoforge-19.70.0.469.jar` | Just Enough Items (JEI) | Modrinth project lists MIT and expressly says it can be included in modpacks. | License appears to permit redistribution, subject to retaining notices. | https://modrinth.com/mod/jei |
| `modernfix-neoforge-5.27.27+mc1.21.1.jar` | ModernFix | Modrinth project lists LGPL-3.0-only. | License appears to permit redistribution if LGPL obligations are met. Confirm exact release and notices. | https://modrinth.com/mod/modernfix |
| `Patchouli-1.21.1-93-NEOFORGE.jar` | Patchouli | Modrinth project lists CC-BY-NC-SA-3.0. | Conditional: attribution, non-commercial use, share-alike and license-notice requirements apply. | https://modrinth.com/mod/patchouli |
| `waystones-neoforge-1.21.1-21.1.46.jar` | Waystones | Modrinth project lists ARR. No explicit permission for this separate GitHub-hosted ZIP has yet been verified. | Do not bundle pending confirmation of author permission applicable to this distribution. | https://modrinth.com/mod/waystones |
| `xaerominimap-neoforge-1.21.1-26.6.0.jar` | Xaero's Minimap | Project is ARR but author explicitly permits modpack use subject to conditions. For distribution outside CurseForge/Modrinth, provide an easily accessible official project link to users. Monetization outside those platforms requires written permission. | Conditional: include official project link; do not monetize outside CF/Modrinth without written permission; keep pack name/description distinct. | https://modrinth.com/mod/xaeros-minimap |
| `xaeroworldmap-neoforge-1.21.1-1.47.0.jar` | Xaero's World Map | Project is ARR but author explicitly permits modpack use subject to conditions. For distribution outside CurseForge/Modrinth, provide an easily accessible official project link to users. Monetization outside those platforms requires written permission. | Conditional: include official project link; do not monetize outside CF/Modrinth without written permission; keep pack name/description distinct. | https://modrinth.com/mod/xaeros-world-map |

## Important conditions and notices

### MIT-licensed projects

For each exact file confirmed to be under MIT, include the applicable copyright and permission notice with the redistributed copy. Do not assume that a project page's current license necessarily proves the license attached to every historical release.

### LGPL projects

For LGPL-licensed projects, preserve copyright and license notices and satisfy the applicable LGPL terms. Where required, provide the corresponding source code or a valid way to obtain it. Do not describe LGPL as permission to omit the license obligations.

### Creative Commons BY-NC-SA projects

For Jade and Patchouli, preserve attribution and license information, identify modifications if made, and respect the NonCommercial and ShareAlike conditions. A private, no-fee friend group may be non-commercial in practice, but that is not a substitute for reviewing the exact license scope and any included third-party assets.

### ARR projects and explicit modpack permissions

An ARR label does not necessarily prevent all modpack use if the author separately grants permission. However, the permission must actually cover the proposed distribution method. Conditions such as linking to the official project page, non-monetization, or restrictions on re-hosting must be followed.

### Create Encased

The author explicitly says modpack use is allowed but reposting the mod on another website is not. The JAR should therefore be removed from the GitHub ZIP and obtained by each player through the official project host, unless the author grants a specific exception.

## Remaining audit work

The full JAR inventory supplied by the pack maintainer contains many additional files that have not yet been individually matched to their exact projects, release licenses, and original file hosts. Those entries remain **unverified** and are not cleared by this document.

The current Prism workflow is known (built-in Download Mods interface), but the original provider for each installed JAR has not yet been established. Where permission depends on the file being hosted on Modrinth or CurseForge, verify the exact downloaded file's provider rather than inferring it from the project name.

Before publishing the 1.0.0 ZIP:

1. Match every JAR to its exact project and version.
2. Establish the original host for each file where platform-specific permission is relevant.
3. Remove files whose authors prohibit re-hosting, unless a valid exception is obtained.
4. Include required third-party copyright/license notices and source links.
5. Re-export the Prism instance after any changes.
6. Test-import the final ZIP in a clean Prism instance.

**Release gate:** This audit is in progress. It is not a representation that all third-party files in the pack are approved for redistribution.
