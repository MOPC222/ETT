# Engineering Tech Tree

### This fork is based on the ETT update 25052025 fetched from CKAN/Spacedock. The repo was forked off outdated 2016 repository in case ProbusThrax decides to update it in the future.  
## Yonge Tech Trees Plugin is still a hard dependency.  
## What's new?
- Sizeable edits were made to the tree, all nodes are now aligned to the grid more strictly.
- New connections in Airframes branch, complex mechanical systems now require Bearings (old Nanolathing).
- New connections in CommandModules branch, requiring more cross-research for high-end parts.
- New Ablators-Reentry branch - intended to separate heat shields from Sterling Systems extensive heat management parts list. Probably less useful without the mod, might make a patch to enable it conditionally.
- Changed patching order: ETT doesn't apply as FINAL anymore, so other part patches with :LAST or :FINAL directive can be loaded on top of it.

## Mod support added:  
- Kerbalism (only tested with KerbalismSimplex)  
- RealBattery (upgrades correctly assigned to Electrics branch)  
- Engine Ignitor (upgrades assigned to correct places for stock parts, mods support WIP)  
- Taerobee  
- OpenCockpit  
- MoreServos  
- Interkosmos  
- Inflatable PicoPort  
- Supplementary Electric Engines  
- InternalRCS (partial, the mod is quite bloated so I only use like 3 parts from it)  
- TarsierSpaceTech  
- ResearchBodies  
- KerBalloons  
- More Airplane Parts  
## Mod support rebalanced/updated:  
- AirplanePlus  
- SterlingSystems (partially, mainly heat management. Parts list at the time of the commit)  
