# Seam-Carving---IMP301
A project to implement Image Processing Subject's "Seam carving" algorithm.
# Run
## crop_c(img, scale_c, t)
* scale_c: percent of the remaining picture along columns (for ex: 0.7)
* t: 'bw' for backward seam carving
## crop_r(img, scale_r)
* scale_r: percent of the remaining picture along rows

## seams_insertion(img, num_add)
* num_add: number of columns to be added

## seam_carve(img, forward_energy, num_add)
* improved by forward energy

# Docs
* https://docs.google.com/presentation/d/1Lu2x7cmrna54h-etCnoO2mXPOKwoEWD4fcp8ZSbn8W8/edit

# References
* https://www.win.tue.nl/~wstahw/edu/2IV05/seamcarving.pdf
* https://avikdas.com/2019/07/29/improved-seam-carving-with-forward-energy.html
* https://karthikkaranth.me/blog/implementing-seam-carving-with-python
* https://en.wikipedia.org/wiki/Seam_carving
* https://github.com/andrewdcampbell/seam-carving/blob/master/seam_carving.py
