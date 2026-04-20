# Autodesk Maya (autodesk-maya)

Autodesk Maya is a comprehensive 3D computer graphics application used for creating interactive 3D applications including video games, animated films, TV series, and visual effects. Maya provides multiple programming APIs including a Python API, C++ plugin API, MEL scripting language, USD integration, and Bifrost visual programming environment for extending and automating Maya workflows and creating custom tools and plugins.

**URL:** [https://raw.githubusercontent.com/api-evangelist/autodesk-maya/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/autodesk-maya/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - 3D Graphics, Animation, Game Development, Modeling, Rendering, Visual Effects, VFX, CAD

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-19

## APIs

### Maya Python API

Python API for scripting and extending Maya functionality, providing access to Maya's scene graph and node architecture. Includes Python API 2.0 with a more Pythonic workflow and improved performance via maya.api.OpenMaya, as well as Python API 1.0 via maya.OpenMaya and the maya.cmds wrapper for MEL commands.

**Human URL:** [https://help.autodesk.com/view/MAYAUL/2026/ENU/](https://help.autodesk.com/view/MAYAUL/2026/ENU/)

#### Tags:

 - Automation, Python, Scripting

#### Properties

- [Documentation](https://help.autodesk.com/view/MAYAUL/2024/ENU/?guid=Maya_SDK_MERGED_Maya_Python_API_Maya_Python_API_2_0_html)
- [APIReference](https://help.autodesk.com/view/MAYAUL/2024/ENU/?guid=Maya_SDK_py_ref_index_html)
- [GettingStarted](https://help.autodesk.com/view/MAYAUL/2024/ENU/?guid=Maya_SDK_MERGED_Maya_Python_API_Python_API_2_0_Quick_Start_html)

### Maya C++ API

C++ API providing low-level access to Maya's core functionality for creating plugins, custom nodes, and high-performance tools. The API is organized into functional libraries including OpenMaya, OpenMayaUI, OpenMayaAnim, OpenMayaFX, and OpenMayaRender.

**Human URL:** [https://help.autodesk.com/view/MAYAUL/2026/ENU/](https://help.autodesk.com/view/MAYAUL/2026/ENU/)

#### Tags:

 - C++, Native, Performance, Plugins

#### Properties

- [Documentation](https://help.autodesk.com/view/MAYAUL/2024/ENU/?guid=Maya_SDK_MERGED_cpp_ref_index_html)
- [APIReference](https://help.autodesk.com/view/MAYAUL/2024/ENU/?guid=Maya_SDK_cpp_ref_index_html)
- [GettingStarted](https://help.autodesk.com/view/MAYAUL/2024/ENU/?guid=Maya_SDK_MERGED_Maya_SDK_Maya_SDK_html)

### Maya Commands (MEL)

Maya Embedded Language (MEL) scripting interface for automating tasks and customizing Maya workflows. MEL provides direct access to Maya commands and is the foundation of Maya's scripting capabilities.

**Human URL:** [https://help.autodesk.com/view/MAYAUL/2026/ENU/](https://help.autodesk.com/view/MAYAUL/2026/ENU/)

#### Tags:

 - Automation, Commands, MEL, Scripting

#### Properties

- [Documentation](https://help.autodesk.com/view/MAYAUL/2024/ENU/?guid=__CommandsPython_index_html)
- [APIReference](https://help.autodesk.com/view/MAYAUL/2024/ENU/?guid=__Commands_index_html)

### Maya USD API

Universal Scene Description (USD) integration for Maya, enabling exchange of 3D content between applications. Provides tools for importing, exporting, and working with USD stages and layers within Maya.

**Human URL:** [https://help.autodesk.com/view/MAYAUL/2026/ENU/](https://help.autodesk.com/view/MAYAUL/2026/ENU/)

#### Tags:

 - Interchange, Pipeline, Scene Description, USD

#### Properties

- [Documentation](https://help.autodesk.com/view/MAYAUL/2024/ENU/?guid=GUID-C7DB6AF9-653E-4B49-93D6-F9C2D0865B85)
- [GitHubRepository](https://github.com/Autodesk/maya-usd)

### Maya Bifrost API

Bifrost is Maya's visual programming environment for creating simulation and procedural effects. It provides a node-based graph editor for building complex effects including fluids, particles, destruction, and procedural geometry, with SDK support for custom node development.

**Human URL:** [https://help.autodesk.com/view/MAYAUL/2026/ENU/?guid=GUID-1223AA4F-1CD7-473C-87EA-C16C6B28F7FD](https://help.autodesk.com/view/MAYAUL/2026/ENU/?guid=GUID-1223AA4F-1CD7-473C-87EA-C16C6B28F7FD)

#### Tags:

 - Bifrost, Particles, Procedural Effects, Simulation, Visual Programming

#### Properties

- [Documentation](https://help.autodesk.com/view/MAYAUL/2026/ENU/?guid=Bifrost_MayaPlugin_bifrost_for_maya_html)
- [GitHubRepository](https://github.com/Autodesk/bifrost-usd)

## Common Properties

- [Portal](https://www.autodesk.com/developer-network/platform-technologies/maya)
- [Documentation](https://help.autodesk.com/view/MAYADEV/2026/ENU/)
- [Support](https://forums.autodesk.com/t5/maya-programming/bd-p/area-c-maya-programming)
- [Blog](https://www.autodesk.com/blogs/maya/)
- [Tutorials](https://tutorials.autodesk.io/)
- [ReleaseNotes](https://help.autodesk.com/view/MAYAUL/2026/ENU/?guid=MAYA_RELEASENOTES_2026_RELEASE_NOTES_HTML)
- [TermsOfService](https://www.autodesk.com/company/legal-notices-trademarks/terms-of-service-autodesk360-web-services)
- [GitHubOrganization](https://github.com/autodesk-platform-services)

## Features

| Name | Description |
|------|-------------|
| Python API 2.0 | Modern Pythonic API with improved performance and a cleaner interface for accessing Maya's node architecture and scene graph via maya.api.OpenMaya. |
| C++ Plugin SDK | Low-level C++ API for high-performance plugin development with access to Maya's full internal architecture through OpenMaya functional libraries. |
| MEL Scripting | Maya Embedded Language for command-line scripting, UI automation, and batch processing of Maya scenes and assets. |
| USD Integration | Universal Scene Description support for importing, exporting, and working with USD assets within Maya for cross-application 3D content pipelines. |
| Bifrost Visual Programming | Node-based visual programming environment for creating procedural effects, simulations, and custom workflows without traditional coding. |
| Custom Node Development | Create custom dependency graph nodes, deformers, and shape nodes that integrate natively into Maya's scene graph and evaluation system. |

## Use Cases

| Name | Description |
|------|-------------|
| VFX Pipeline Integration | Integrating Maya into visual effects production pipelines with custom tools, asset management systems, and render farm automation. |
| Game Asset Automation | Automating game asset creation, optimization, and export workflows for game engines like Unreal Engine and Unity through Maya scripting. |
| Animation Workflow Tools | Building custom rigging systems, animation controls, and workflow tools to accelerate character animation production for film and TV. |
| Procedural Content Generation | Using Bifrost and Python APIs to generate procedural geometry, textures, and scene content for games, visualization, and architectural projects. |
| DCC Pipeline Development | Developing studio pipeline tools that automate scene assembly, asset tracking, and data interchange between Maya and other DCC applications. |

## Integrations

| Name | Description |
|------|-------------|
| Autodesk Arnold | Integration with Arnold renderer via the MtoA (Maya to Arnold) plugin for photorealistic rendering of Maya scenes. |
| Unreal Engine | USD-based pipeline integration with Unreal Engine for game asset export and visualization workflows. |
| ShotGrid (Flow Production Tracking) | Integration with Autodesk ShotGrid for production tracking, asset management, and review workflows in film and TV production. |
| Houdini | Interoperability with SideFX Houdini via USD and Alembic for visual effects simulation and procedural content pipelines. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
