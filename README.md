# Edge-Fed Microstrip Patch Antenna Design using HFSS

## Objective
To design and simulate an edge-fed microstrip patch antenna using a substrate of dielectric constant (εr = 3) and thickness (h = 20 mil), and analyze its return loss performance.

## Tool Used
- ANSYS HFSS

## Design Details
- Feeding Technique: Edge Feed (Microstrip Line Feed)
- Dielectric Constant (εr): 3
- Substrate Thickness: 20 mil
- Operating Frequency: ~2.6 GHz

## Results

### Return Loss (S11)
[S11 Plot](s11_plot_2_6ghz.jpg)

- The antenna resonates around **2.6 GHz**
- Return Loss reaches approximately **-15 dB to -20 dB**
- Indicates acceptable impedance matching

### Antenna Geometry
[Antenna Layout](antenna_layout.jpg)

- Standard rectangular microstrip patch
- Edge-fed using microstrip line

### Port Impedance (Optional)
[Port Zo](zo_plot.jpg)

- Impedance variation observed around resonance

---

## Observations
- Edge feeding provides a simple and effective matching technique
- Proper feed position and width are critical for achieving good return loss
- The antenna shows stable performance around the resonant frequency

---

## Conclusion
The edge-fed microstrip patch antenna achieved resonance near 2.6 GHz with acceptable return loss, demonstrating effective impedance matching using a simple feed structure.

---

## Future Work
- Compare with Quarter Wave Transformer (QWT) feed
- Improve matching to achieve S11 < -20 dB
