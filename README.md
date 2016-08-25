# 3D-printed-horn-antennas
This repository is for models and documents to help in the 3D printing of horn antennas for ham radio microwave. 

The first horn is a 10GHz elliptical taper horn designed in OpenSCAD. The script will be included as soon as it's double-checked for compatibility with recent updates of OpenSCAD. 

The horn model that is produced by the OpenSCAD script is in two parts because my Ultimaker2 3D printer is not quite large enough to print the entire horn at once.

The waveguide.stl model is the section of the model that has a hole for an SMA connector. A real waveguide connector that allows the horn to be connectued up directly to waveguide feed (and includes something like an integrated RF choke) is an improvement mentioned in the QEX article that we are interested in doing for the next edition. A "real" waveguide transition would swap in directly for the waveguide model included in this first edition of this horn project. 

The reason I used SMA and coax is because that was what I was familiar with. Since then, I have become more familiar with and comfortable with working with waveguides. 

The horn-part.stl is the elliptical taper horn model. This fits right up to the various waveguide models. As of today, there is one waveguide model (the SMA hole version). I used PLA to print and superglue to connect. 

If you have the right type of waveguide, then just print out the horn-part. 

Other improvements under serious consideration are breaking up the model even smaller to make the prints less scary to print (40 hours!). 
And, making the corners and edges rounded to make the conductive paint stick better in these areas. 
