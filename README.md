# Impeller-stress-prediction
Calculate stress and natural frequency of centrifugal fan's impeller

Input data included:
- Model name of impeller
- Rotating speed of impeller (in Rpm / 1000)
- D2: Main Diameter of impeller (m)
- DB: Inner Diameter of impeller (m)
- tm: Main plate thickness (mm)
- ts: Side plate thickness (mm)
- ti: Middle plate thickness (mm)
- tv: Vane thickness (mm)
- Rib: Number of rib inside airfoil vane
- hasMouthRing: use a mouth ring at side plate or not
- isStraightSide: use straight side design of side plate or not
- hasRimOut: has outer rim for side plate or not
- hasRimIn: has inner rim for side plate or not
- hasVaneRimIn: has inner rim for vane or not
- hasVaneRimOut: has outer rim for vane or not

Output data included:
- Weight: Weight of impeller in kg
- GD2: Inertial moment of impeller
- Sm: Main plate stress (Mpa)
- Ss: Side plate stress (Mpa)
- Sv: Vane stress (Mpa)
- Si: Middle plate stress (Mpa)
- Frequency: Natural frequency of impeller (Hz) 
