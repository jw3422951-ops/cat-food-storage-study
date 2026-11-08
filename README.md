# Automatic Cat Feeder

I built an automatic cat feeder and investigated how container type and silica gel affected dry cat food during storage.

[CAD animations](#prototype-and-mechanism) · [Experiment photos](#experiment-photos) · [Full experiment report (PDF)](reports/cat-food-storage-experiment.pdf)

## Prototype and mechanism

I assembled the CAD components, resolved part interference, and worked on the motion of the internal motor and gears. I created motion simulations to show how the assembly and underside mechanism move.

| Assembly motion | Underside mechanism |
| --- | --- |
| <img src="assets/assembly-animation.gif" alt="CAD animation of the complete automatic cat feeder assembly" width="320"> | <img src="assets/underside-animation.gif" alt="CAD animation of the underside of the automatic cat feeder" width="255"> |

[CAD model (STL)](cad/automatic-cat-feeder.stl) · [Assembly animation (MP4)](assets/assembly-animation.mp4?raw=true) · [Underside animation (MP4)](assets/underside-animation.mp4?raw=true)

## Food-storage investigation

I compared plastic and aluminum foil containers with 0, 1, 2, or 4 g of silica gel. Each of the eight treatments used three independent containers with 30 g of cat food per container, for **24 containers** in total.

| Measurement | What I recorded |
| --- | --- |
| Loss on drying (LoD) | Mass lost during heating, used as a moisture-related indicator |
| Thin-layer chromatography (TLC) | Iodine-stained signals from hexane extracts, measured with ImageJ |
| pH | Measurements of aqueous cat-food extracts |

### Results

- **Loss on drying.** On Day 14, the silica gel groups lost less mass during drying than their respective controls. On Day 21, the difference persisted in the foil groups. The differences in the plastic groups were inconclusive.
- **TLC.** On Day 21, the 1 g and 2 g foil groups had higher spot intensities than the foil control. The 4 g comparison and the matched foil-versus-plastic comparisons were inconclusive.

Loss on drying can include volatile substances besides water. I used TLC spot intensity as a relative signal from the extracts and compared pH readings within each day because of calibration limitations.

*The final TLC measurements were taken on Day 21. Some references in the archived report label that test Day 20.*

### Experiment photos

<a href="assets/storage-experiment-containers.jpg"><img src="assets/storage-experiment-containers.jpg" alt="Lidded containers arranged for the cat-food storage experiment" width="360"></a>

*Containers used in the storage experiment.*

<a href="assets/cat-food-hexane-extraction.jpg"><img src="assets/cat-food-hexane-extraction.jpg" alt="Test tubes holding cat-food samples during hexane extraction" width="480"></a>

*Cat-food samples during hexane extraction before TLC. The plate was developed with a mixture of hexane and ethyl acetate.*

[Back to my GitHub profile](https://github.com/jw3422951-ops)
