# Automatic Cat Feeder

An automatic cat feeder project combining a physical prototype, mechanical CAD and motion simulation, and a cat-food storage investigation.

A physical prototype has been built. The animations below show the CAD mechanism.

[Read the food-storage experiment report (PDF)](reports/cat-food-storage-experiment.pdf)

## Assembly animation

![Animated CAD view of the automatic cat feeder assembly.](assets/assembly-animation.gif)

## Underside mechanism

![Animated underside view of the automatic cat feeder mechanism.](assets/underside-animation.gif)

## My contributions - Wenhao Jia

- **Biology component:** investigated the effects of container type and silica gel amount on cat-food storage, as documented in the experiment report.
- **Motion simulation:** created the CAD animations and displacement simulations.
- **Assembly:** assembled the CAD components and resolved part overlap and interference issues.
- **Drive mechanism:** worked on the internal motor-and-gear structure and its motion.
- **Physical prototype:** built the device.

## Food-storage investigation

**Report:** *Effects of Container Type and Silica Gel Amount on Cat Food Storage*

The investigation examined storage conditions relevant to the feeder's food compartment. It compared **plastic and aluminum foil containers** with **0, 1, 2, or 4 g of silica gel**, using **30 g of cat food per container** and **three independent containers per treatment**: eight treatments and 24 containers in total.

| Measurement | What was recorded |
| --- | --- |
| Loss on drying (LoD) | Mass lost during heating, used as a moisture-related indicator |
| Thin-layer chromatography (TLC) | Iodine-stained signals from hexane extracts, measured with ImageJ |
| pH | Measurements of aqueous cat-food extracts |

### Experiment photos

<a href="assets/storage-experiment-containers.jpg"><img src="assets/storage-experiment-containers.jpg" alt="Lidded containers arranged for the cat-food storage experiment" width="400"></a>

*Containers used in the storage experiment.*

<a href="assets/cat-food-hexane-extraction.jpg"><img src="assets/cat-food-hexane-extraction.jpg" alt="Test tubes holding cat-food samples during hexane extraction" width="520"></a>

*Cat-food samples during hexane extraction before thin-layer chromatography. The TLC plate was developed using a mixture of hexane and ethyl acetate.*

### Observations reported in the tables

- Silica gel treatments had lower LoD than their respective controls on Day 14. On Day 21, the lower LoD persisted in the foil treatments; the plastic treatments did not show a statistically significant difference from the plastic control.
- The Day 21 TLC measurements did not show a consistent increase in signal with increasing silica gel amount. The 1 g and 2 g foil treatments had higher signals than the foil control, while the 4 g treatment did not reach statistical significance.
- The matched foil-versus-plastic TLC comparisons did not reach statistical significance at any tested silica gel amount.

*Timing clarification: The project author confirmed that the final TLC measurements were taken on Day 21. References to Day 20 for those measurements in the archived report refer to the same Day 21 test.*

**Interpretation limits:** LoD can include volatile substances other than water. The TLC signal does not directly quantify vitamin E or total fat. Because of calibration limitations, pH was interpreted through within-day comparisons. The original report contains the methods, tables, statistical comparisons, and discussion; no independent reanalysis is presented here.

[Open the complete original report](reports/cat-food-storage-experiment.pdf)

## Project files

| File | Description |
| --- | --- |
| [Food-storage experiment report (PDF)](reports/cat-food-storage-experiment.pdf) | Original report for the biology component |
| [CAD model (STL)](cad/automatic-cat-feeder.stl) | Original exported 3D model |
| [Assembly animation (MP4)](assets/assembly-animation.mp4) | Original animation recording |
| [Underside animation (MP4)](assets/underside-animation.mp4) | Original animation recording of the underside |

The looping images above are CAD motion previews. The original model and MP4 recordings are included for download.
