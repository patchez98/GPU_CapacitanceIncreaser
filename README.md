# Meanwell_EPP_CapacitanceIncreaser

# Purpose
This board is intened to improve stability in PCs that struggle due to high instantaneous current draw in modern GPUs. It adds a bunch of capacitance in a board that screws onto the Meanwell EPP-series PSU's 12V output, in the hopes that it can help the PSU deal with current spikes better. I currently am running a 12V system with a MeanWell EPP-400 that struggles with peak current draw on a 3060ti.

## Form factor
The current version uses a small PCB that is slightly narrower than the EPP and mounts using the screw terminals. It has two XT30 outputs. One is intended for the GPU, one for the plugin DC-DC ATX board and CPU. I only put a single output for the DC-DC and CPU power since some DC-DC boards are intended for passthrough. 

## Capabilities
XT30s are rated for 15A continuous, 30A peak current rating. At 12V, this is 180W continuous, 360W peak. My 3060ti pulls 200W, but I'll keep an eye on it and see how the connector heats up after long use. It has a lot of copper to sink heat into and some nearby airflow, so it should be fine. If I don't make an XT60 version, mine didn't catch on fire.
