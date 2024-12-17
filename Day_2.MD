# Day 2

## Recap & Q&A from Day 1
### MorphoCloud:
**/unshelve** to make the instance online (it will automatically send an email with the updated credentials and access information once the instance becomes online. Emails cannot be sent when the instances are offline (aka shelved)

### Animator:
For both ROI and VOlume property actions, you need to have three ROIs (or Volume Properties): **Start**, **End**, and the **Interpolated** one. Start and End define the starting and ending properties and they are static (i.e., they are the keyframes). Interpolated one get updated for every frame Slicer is drawing incrementing from the start condition to the end condition. The important point, you need to make sure in the `Volume Rendering` module you have the the ROI and Volume Property fields to this interpolated ones. If you leave it set at either Start or End one nothing will happen. 

## Segmentation ##
This is a big tutorial and it is going to have two parts:
1. First we will do a self-paced exercise, and everybody will use the BrainTumor data from the Slicer's SampleData module to do the tutorial as written, which is here: https://github.com/SlicerMorph/Tutorials/tree/main/Segmentation
2. Then we will interactively explore the turtle data for more of the segmentation tools in Slicer (After 4pm). You will need to download the turtle data from MorphoSource from this link (you need to be logged in to MorphoSource for download option to be enabled). This is the URL for the data. https://www.morphosource.org/concern/media/000076039?locale=en

However, I created a NRRD file with slightly lower resolution (so things work out a bit faster), which you can load into Slicer directly using the ImportFromURL module of SlicerMorph. https://app.box.com/shared/static/e8x45ic0amudn2h5u3xwhxrhd8wdnx7s.nrrd (~30.5MB)

Other modules we will investigate are:

* **Segment Statistics:** https://slicer.readthedocs.io/en/latest/user_guide/modules/segmentstatistics.html
* **Segment Endocranium Video:** 
    * Video: https://www.youtube.com/watch?v=EAKN1GMNY98
    * Use the `ImportFromURL` module of SlicerMorph (SlicerMorph->Input Output->ImportfromURL) to obtain the example data. Simply paste this URL to the module: https://github.com/muratmaga/Hominoid_Skulls/blob/master/Pan_troglodytes/Pan_template0_cleaned.nrrd
   
* **Models:** https://slicer.readthedocs.io/en/latest/user_guide/modules/models.html
* **Colorize Volume (provided by Sandbox extension):** https://github.com/SlicerMorph/Tutorials/tree/main/ColorizeVolume
* **Quick Align:** https://github.com/SlicerMorph/Tutorials/tree/main/QuickAlign
* **Animator: Exploding Models functionality** Download the two datasets using the ImportFromUrl module:
    * https://github.com/muratmaga/mouse_CT_atlas/blob/master/data/templates/35_mic_23strain_mus_template_UCHAR.nii.gz
    * https://github.com/muratmaga/mouse_CT_atlas/blob/master/data/templates/35_mic_23strain_mus_template_UCHAR.seg.nrrd (segmentation)
      
