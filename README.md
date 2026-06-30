# 3D Printable Enclosure for Raspberry Pi 5, IMX219-83 Stereo Camera & WT901BLECL IMU

This repository contains the CAD files,Drawing files. 3D-printable enclosure designed for a **Visual-Inertial Odometry (VIO)** system.

**Hardware**:
- Raspberry Pi 5
- Waveshare IMX219-83 Stereo Camera
- WT901BLECL Bluetooth 5.0 9-Axis IMU

## Features

- Optimized layout following professional VIO engineering principles
- 3 mm wall thickness for structural stability
- Clean CSI ribbon cable routing without congestion
- Dedicated ventilation for Raspberry Pi 5
- Heat-set inserts for reliable lid closure
- External spacers for mounting clearance (material efficient)
- EMI-aware component placement
- Ready for 3D printing (STL files included)

## Design Philosophy

In VIO systems, the mechanical design directly affects estimation accuracy. This enclosure prioritizes **optical precision**, **IMU performance**, **calibration stability**, and **vibration resistance** — going beyond a generic electronics box.

## Engineering Priorities

1. **Optical Accuracy**
2. **IMU Accuracy**
3. **Mechanical Rigidity**
4. **Thermal Stability**
5. **Ease of Assembly**
6. **Cable Routing**

## Component Layout
FRONT OF ENCLOSURE
Stereo Left      Stereo Right
O------------------O
|
|
IMU (Center)
----------------Rigid Mount Plate--------------
CSI Ribbon
Raspberry Pi 5
BACK OF ENCLOSURE

- **Stereo Camera**: Occupies full front face, rigidly bolted.
- **IMU**: 15–25 mm behind camera, centered on baseline, axes aligned.
- **Raspberry Pi 5**: Rear position for thermal and EMI isolation.

## Technical Specifications

- **External Dimensions**: 143.1 × 100 × 40.5 mm
- **Wall Thickness**: 3 mm
- **Materials**: ABS / PETG / Carbon-filled Nylon
- **Closure**: Heat-set inserts
- **Offsets**: External rubber or rigid spacers

## My Design Approach

- Chose a simple rectangular layout instead of stacking the Pi above the IMU (avoided increased height and complex routing).
- Ensured reasonable spacing between IMU and Raspberry Pi to reduce EMI.
- Prioritized non-congested routing for the delicate CSI ribbon cable.
- Used dynamic internal spacing for better material optimization.
- Provided external offsets (instead of built-in) to minimize material waste while maintaining clearance.

## Validation & Testing

- Dimensional accuracy and fit
- Thermal performance under load
- Vibration testing (stereo baseline stability)
- EMI and sensor data quality
- CSI signal integrity
- Recommended: FEA, thermal, and vibration analysis

## Printing & Assembly

1. Print with 0.2 mm layer height, 25–30% infill.
2. Install heat inserts in the enclosure.
3. Mount camera rigidly on front.
4. Position IMU with proper spacing.
5. Install Raspberry Pi at rear.
6. Route CSI cable with smooth bends (≥25 mm radius).
7. Attach external spacers for mounting the enclosure.

## Future Improvements

- Parametric design
- Enhanced vibration isolation
- Support for additional sensors

## Contributing

Contributions, improvements, and new variants are welcome!

## Author

**Dattatreya Nerella**

---

**Designed with focus on real VIO performance and practical 3D printing.**
