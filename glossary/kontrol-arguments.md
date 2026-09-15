# Kontrol Arguments

| Command | Description |
| --- | --- |
| `version` | Print out the version of Kontrol. |
| `load-state` | Generate a state diff summary from an account access dict. |
| `build` | Kompile the K definition corresponding to the given output directory. |
| `prove` | Run a Foundry proof. |
| `show` | Print the CFG for a given proof. |
| `refute-node` | Refute a node and add its refutation as a subproof. |
| `unrefute-node` | Disable refutation of a node and remove the corresponding refutation subproof. |
| `split-node` | Split a node on a given branch condition. |
| `list` | List information about CFGs on disk. |
| `view-kcfg` | Explore a given proof in the KCFG visualizer. |
| `remove-node` | Remove a node and its successors. |
| `simplify-node` | Simplify a given node, and potentially replace it. |
| `step-node` | Step from a given node, adding it to the CFG. |
| `merge-nodes` | Merge multiple nodes into one branch. |
| `section-edge` | Given an edge in the graph, cut it into sections to get intermediate nodes. |
| `get-model` | Display a model for a given node. |
| `minimize-proof` | Minimize the KCFG of the proof for a given test. |
| `clean` | Remove the build artifacts and cache directories. |
| `init` | Create a new Forge project compatible with Kontrol. |
| `setup-storage` | Generate symbolic structured storage constants. |

This list follows the subcommands currently registered by Kontrol. To regenerate an existing compiled definition after Solidity or K sources change, run `kontrol build --rekompile`.
