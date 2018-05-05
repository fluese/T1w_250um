# T1-weighted in vivo human whole brain MRI dataset with an ultrahigh isotropic resolution of 250 μm

This data set is supplementary to the ultra high resolution T1-weighted MPRAGE
data set with an isotropic resolution of 250 µm. It consists of the source data
used to generate the resulting data set by averaging. Each volulme has a native
isotropic resolution of 250 µm with a total number of eight volumes.
Additionally, a PD-weighted GRE was acquired in the first session. Furthermore,
isotropic 1 and 0.5 mm T1-weighted data of the same subject acquired with the
same sequence has been included. All data was acquired using prospective motion
correction.

In case of the 250 µm data the original motion tracking log is included in
plain text. Additionally, the translational displacement in mm and rotation in
° has been extracted and are included as MAT-files for easier data handling. To
allow a quick first impression of the magnitude of the motion, motion plots are
included in TIFF format.

Detailed information on the experimental setup of the prospective motion
correction can be found in Stucht et al. [Highest resolution in vivo human
brain MRI using prospective motion corection. PloS one 10, e0133921 (2015)] and
for an in-depth explanation of the hardware and validate we refer to Maclaren
et al. [Measurement and correction of microscopic head motion during magnetic
resonance imaging of the brain. PloS one 7, e48088 (2012)].

The data is structured as follows. In sessions 01 to 05 data with an isotropic
resolution of 250 µm were acquired. In session 06 and 07 the 0.5 and 1 mm data
was acquired, respectively. Sequence protocols are included in the root
directory of each session in PDF format and metadata of each acquisition is
included in the sessions folder in JSON format.

In case of any further questions please feel free to contact Falk Luesebrink
(falk dot luesebrink at ovgu dot de).

Brief legend for the plain text log files:

Label | Description
---|---
LT | System time
F | Frame number
XYZ | Marker position in camera coordinates (translation)
Q | Marker position in quaternions (rotation)
FT | Frame time
