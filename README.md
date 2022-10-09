# GPU_CapacitanceIncreaser

# Purpose
This board is intened to improve stability in PCs that struggle due to high instantaneous current draw in modern GPUs. It adds a bunch of capacitance in a board that plugs into an 8-pin PCIe power connector, in the hopes that it can help the PSU deal with current spikes better. I currently am running a 12V system with a MeanWell EPP-400, so this project is focused on that or other custom-wired 12V systems.

## Form factor
The current version uses an 8-pin PCIe power receptacle salvaged from any random cable or purchased online in order to plug into the GPU. Unfortunately, PCB-mount PCIe receptacles are not something I have found, so it's kinda sketchy mounting. The connection to the power supply is simple wire holes, for 12AWG wire, as you are probably custom wiring this system anyways.
