# Godot MCP Servers

Model Context Protocol servers, Godot editor plugins, and companion tools for AI-assisted Godot development.

Last reviewed: 2026-06-18.

Stars and forks were checked against GitHub on the review date. Treat them as a rough popularity signal, not a quality guarantee.

## Ranked Godot MCP Servers

| Rank | Repository | Stars / forks | Best for | Notes |
|---:|---|---:|---|---|
| 1 | [Coding-Solo/godot-mcp](https://github.com/Coding-Solo/godot-mcp) | 4,250 / 401 | Baseline Godot MCP server. | MIT-licensed MCP server for launching the Godot editor, running projects, capturing debug output, controlling execution, inspecting projects, and managing scenes. |
| 2 | [hi-godot/godot-ai](https://github.com/hi-godot/godot-ai) | 603 / 38 | Polished live-editor workflow. | MIT-licensed Godot AI/MCP toolkit with broad live-editor operations for scenes, nodes, scripts, signals, UI, materials, animation, particles, cameras, and environments. Latest checked release: `v2.7.5`, published 2026-06-14. |
| 3 | [ee0pdt/Godot-MCP](https://github.com/ee0pdt/Godot-MCP) | 581 / 64 | Editor and project manipulation. | MIT-licensed MCP integration for creating and editing Godot games with scene, node, script, project, and command workflows. |
| 4 | [youichi-uda/godot-mcp-pro](https://github.com/youichi-uda/godot-mcp-pro) | 440 / 58 | Large pro toolset. | Public repo contains the Godot addon/plugin; README advertises a paid Node.js MCP server with a large tool surface for scene, animation, 3D, physics, particles, audio, shaders, input simulation, runtime analysis, navigation, and testing. |
| 5 | [tomyud1/godot-mcp](https://github.com/tomyud1/godot-mcp) | 366 / 40 | Simple plugin plus MCP server setup. | MIT-licensed Godot 4.x MCP server and plugin with an approachable `npx` setup path, AssetLib-oriented workflow, project visualizer, and 42 advertised tools. Latest checked release: `v0.5.0`, published 2026-04-21. |
| 6 | [tugcantopaloglu/godot-mcp](https://github.com/tugcantopaloglu/godot-mcp) | 277 / 48 | Broad open tool coverage. | MIT-licensed Godot 4.x MCP server expanding the Coding-Solo approach with 149 advertised tools across networking, 2D/3D rendering, UI, audio, animation trees, file I/O, runtime GDScript execution, scene manipulation, signals, physics, and project creation. |
| 7 | [HaD0Yun/Doyunha-Gopeak](https://github.com/HaD0Yun/Doyunha-Gopeak) | 211 / 23 | Edit, run, inspect loop. | MIT-licensed GoPeak MCP server advertising 95+ tools for scene management, GDScript LSP, DAP debugging, screenshot capture, input injection, ClassDB introspection, and CC0 asset search. Review network binding and authentication behavior before use. |
| 8 | [3ddelano/gdai-mcp-plugin-godot](https://github.com/3ddelano/gdai-mcp-plugin-godot) | 88 / 4 | Godot addon/plugin integration. | MCP server integration for Godot that lets tools create scenes, resources, and scripts, and read errors from the editor. |
| 9 | [bradypp/godot-mcp](https://github.com/bradypp/godot-mcp) | 86 / 13 | Alternative MCP middleware. | MIT-licensed middleware between AI assistants and Godot that validates requests, executes Godot operations, and returns success/error feedback for project management, run, and debug workflows. |
| 10 | [Dokujaa/Godot-MCP](https://github.com/Dokujaa/Godot-MCP) | 49 / 5 | Modular external process communication. | Godot MCP plugin for communication between external processes and Godot; README focuses on Claude Desktop controlling or interacting with the Godot editor. Also listed on [MCP Servers](https://mcpservers.org/servers/Dokujaa/Godot-MCP). |
| 11 | [gregario/godot-forge](https://github.com/gregario/godot-forge) | 7 / 3 | Docs, analysis, and test-running companion. | MIT-licensed Godot 4 MCP server with tools for API docs search, project info, script analysis, scene analysis, and GUT/GdUnit4 test running. Useful as a companion to editor-control servers. |
| 12 | [telagod/kooix-godot-mcp](https://github.com/telagod/kooix-godot-mcp) | 4 / 3 | Project analysis and diagnosis angle. | MIT-licensed Godot MCP server focused on project analysis, code generation, error diagnosis, performance insights, and architecture guidance. Registry listings may show different popularity stats than GitHub. |

## Practical Shortlist

| Use case | Start with | Why |
|---|---|---|
| Default editor/run/debug automation | [Coding-Solo/godot-mcp](https://github.com/Coding-Solo/godot-mcp) | Largest community signal and the clearest baseline for launching Godot, running projects, and capturing debug output. |
| Most polished live-editor experience | [hi-godot/godot-ai](https://github.com/hi-godot/godot-ai) | Broad operations, recent releases, and practical coverage across editor objects, scripts, UI, materials, particles, cameras, and environments. |
| Maximum open tool surface | [tugcantopaloglu/godot-mcp](https://github.com/tugcantopaloglu/godot-mcp) | Large advertised tool count and broad Godot 4 engine coverage, including runtime execution and scene manipulation. |
| Simpler approachable setup | [tomyud1/godot-mcp](https://github.com/tomyud1/godot-mcp) | Godot 4.x plugin plus `npx` server workflow, AssetLib-oriented setup, and a smaller tool surface than the largest servers. |
| Docs, tests, and static checks | [gregario/godot-forge](https://github.com/gregario/godot-forge) | Pairs well with an editor-control MCP server by adding Godot 4 docs search, script/scene analysis, and test runner tools. |

## Security Notes

MCP servers that can edit scenes, run scripts, execute GDScript, inject input, launch Godot, or expose a local port should be treated like development tools with code-execution privileges.

- Prefer localhost-only bindings and avoid exposing MCP servers to your LAN.
- Check authentication, host binding, and port configuration before starting a server.
- Review high-power tools such as runtime GDScript execution, file I/O, shell execution, and input injection.
- Run against a disposable branch or test project first, especially when evaluating a new MCP server.
- See [Coding-Solo/godot-mcp issue 85](https://github.com/Coding-Solo/godot-mcp/issues/85) for a public discussion about insecure runtime binding behavior reported in a related Godot MCP tool.
