# Cat Food Storage Study and Automatic Feeder

How do container type and silica gel affect dry cat food while it waits to be dispensed? I designed and ran a study with 24 containers and wrote the report. I tracked loss on drying, pH, and a relative signal from lipid-soluble extracts to understand what changes during storage. The question grew out of building an automatic feeder with Shuoqi Yang and Shaoxuan Xiong.

[Full experiment report (PDF)](reports/cat-food-storage-experiment.pdf) · [Results](#results) · [Experiment photos](#experiment-photos) · [Feeder prototype and CAD](#prototype-and-mechanism)

## Food chemistry and preservation

I compared plastic and aluminum foil containers with 0, 1, 2, or 4 g of silica gel. Each of the eight treatments used three independent containers with 30 g of cat food per container.

| Measurement | What I recorded |
| --- | --- |
| Loss on drying (LoD) | Mass lost during heating, used as a moisture-related indicator |
| Thin-layer chromatography (TLC) | Iodine-stained signals from hexane extracts, measured with ImageJ |
| pH | Measurements of aqueous cat-food extracts |

### Results

- **Loss on drying.** On Day 14, the silica gel groups lost less mass during drying than their respective controls. On Day 21, the difference persisted in the foil groups. The foil group with 4 g of silica gel averaged 4.50% loss on drying, compared with 7.60% for the foil control. The differences in the plastic groups were inconclusive.
- **TLC.** On Day 21, the 1 g and 2 g foil groups had higher spot intensities than the foil control. The 4 g comparison and the matched foil-versus-plastic comparisons were inconclusive.
- **pH.** The foil groups had slightly lower pH than the plastic groups on Days 14 and 21. I compared readings within each day because of calibration limitations.

![Grouped bar chart of loss on drying by container type and silica gel amount on Days 0, 14, and 21](assets/loss-on-drying.svg)

*Bars show group means. Error bars show one sample standard deviation above and below each mean, calculated from the weighing records (three independent containers per treatment and day). See Table 1 in the [full report](reports/cat-food-storage-experiment.pdf).*

Loss on drying can include volatile substances besides water. I used TLC spot intensity as a relative signal from the extracts. These preliminary results guide which container and desiccant combinations I would test next in the feeder's storage compartment.

### Experiment photos

<a href="assets/storage-experiment-containers.jpg"><img src="assets/storage-experiment-containers.jpg" alt="Lidded containers arranged for the cat-food storage experiment" width="360"></a>

*Containers used in the storage experiment.*

<a href="assets/cat-food-hexane-extraction.jpg"><img src="assets/cat-food-hexane-extraction.jpg" alt="Test tubes holding cat-food samples during hexane extraction" width="480"></a>

*Cat-food samples during hexane extraction before TLC. The plate was developed with a mixture of hexane and ethyl acetate.*

## Prototype and mechanism

The team built a feeder that moves dry food from a hopper through a motor-driven dispensing mechanism into a tray. Physical testing revealed jamming and leakage around the outlet. **Shuoqi Yang** led the mechanical design and fabrication and revised the outlet and guide path. **Shaoxuan Xiong** developed the motor controls and tested two motor configurations.

**My contribution.** I helped build the prototype, created CAD models of the motor and gears, assembled the components in CAD, and resolved interference between parts. I made the animations below to show how the assembly and underside mechanism move.

| Assembly motion | Underside mechanism |
| --- | --- |
| <img src="assets/assembly-animation.gif" alt="CAD animation of the complete automatic cat feeder assembly" width="320"> | <img src="assets/underside-animation.gif" alt="CAD animation of the underside of the automatic cat feeder" width="255"> |

[Team prototype and test videos](https://github.com/jw3422951-ops/automatic-cat-feeder-fork#project-videos) · [Mechanical design and full STEP assembly](https://github.com/jw3422951-ops/automatic-cat-feeder-fork/blob/main/docs/mechanical-design.md) · [Motor and automation](https://github.com/jw3422951-ops/automatic-cat-feeder-fork/blob/main/docs/motor-and-automation.md)

[CAD model (STL)](cad/automatic-cat-feeder.stl) · [Assembly animation (MP4)](assets/assembly-animation.mp4?raw=true) · [Underside animation (MP4)](assets/underside-animation.mp4?raw=true)

[Back to my GitHub profile](https://github.com/jw3422951-ops)
