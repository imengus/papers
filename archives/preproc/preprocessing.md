.
.
.
.
/home/ilkin/fsl/bin/bet mprage.nii.gz anat_brain -R -f 0.25 -g 0
/home/ilkin/fsl/bin/bet rest func_brain -F -f 0.5 -g 0
fslroi func_brain func_brain5 5 -1
/home/ilkin/fsl/bin/fast -t 2 -n 3 -H 0.1 -I 4 -l 20.0 -o func_brain5 fast/func_brain5
fslmaths func_brain5.nii.gz -s 2.12 func_sm