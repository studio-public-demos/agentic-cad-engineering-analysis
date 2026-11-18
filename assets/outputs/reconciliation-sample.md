# Representative CAD-to-GA reconciliation (sanitized example)

> Sample values only — does not correspond to any customer product.

| GA item | Drawing qty | CAD interpretation | Match status |
|---|---|---|---|
| Fuse holder (with link) | 12 | 12 fuse-holder assemblies identified on the mounting plate | matched |
| Disconnect switch | 1 | 1 switch assembly identified | matched |
| Output busbar | 2 | 2 output-busbar geometries located | matched |
| Input busbar (+Ve / -Ve) | 2 | 2 input-busbar geometries located | matched |
| Surge protective device | 1 | 1 SPD geometry identified | matched |
| Earthing terminal | 1 | 1 terminal geometry identified | matched |
| Enclosure (FRP) | 1 | 1 enclosure body + 1 cover | matched |
| Mounting plate | 1 | 1 mounting plate geometry | matched |

## Exception (reported, not assumed)
An additional fuse-related CAD instance was detected outside the primary
assembly. It is reported as *"engineering clarification required"* and is not
assumed to be a design error.
