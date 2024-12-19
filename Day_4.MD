## Cont Morphometrics Tools in SlicerMorph  from Day 3

* [MarkupEditor: to subset or delete points from a dense pointcloud interactively](https://github.com/SlicerMorph/Tutorials/tree/main/MarkupsEditor)
* [Surface Toolbox](https://slicer.readthedocs.io/en/latest/user_guide/modules/surfacetoolbox.html#surface-toolbox)
* [PlaceLMGrid](https://github.com/SlicerMorph/Tutorials/blob/main/GridBasedLandmarking/README.md)
* [Dynamic Modeler](https://slicer.readthedocs.io/en/latest/user_guide/modules/dynamicmodeler.html#dynamic-modeler)
* [SlicerMorphR](https://github.com/SlicerMorph/Tutorials/blob/main/GPA_3/parser_and_sample_R_analysis.md)

## Exercise for today
* Go through the PlaceLMGrid tutorial above as written. However make sure you use the data link specified for the USP Course for this exercise. Additionally you may have to use the `Surface Toolbox` module's **Smoothing** function to place patches more smoothly. Then run your data with the GPA module.

[**Link to download 4 merged samples to use in the GPA**](https://github.com/muratmaga/USP_Course/blob/main/GridExample.zip)

* Use the SLicerMorphR tutorial above to load your data into R and and geomorph and "slide" the semi landmarks and then bring them back to SlicerMorph for visualization. If you do not already have R and Rstudio on your computer, you can use the MorphoCloud. To do that, first  **/unshelve** your session, and log into it, open a terminal window and type this command and hit enter: 
```
curl https://jetstream2.exosphere.app/exosphere/assets/scripts/mount_ceph.py | sudo python3 - mount \
  --access-rule-name="MorphoCloudCephShare-ro" \
  --access-rule-key="AQAIDi1nKwbRFRAA9KKHUddANj6Ywj8ag7N9pg==" \
  --share-path="149.165.158.38:6789,149.165.158.22:6789,149.165.158.54:6789,149.165.158.70:6789,149.165.158.86:6789:/volumes/_nogroup/60bf684c-51d1-4abb-93f5-188d4d164111/1fe273cd-1e4d-4087-ad2b-01d548a16fe0" \
  --share-name="MorphoCloudCephShare"
```
this command will make the necessary R libraries availables to you. You only need to do this once. After you completed this step, to launch Rstudio, type these to commands to start Rstudio:
```
module load rstudio
rstudio
```

## If time permits
* Image Registration (Dental surgery example)
* Programmatically doing tasks in Slicer (scripting)
* MEMOS and deep learning based segmentation. 



