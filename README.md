# bedtools-example-script
Most bedtools intersect scripts look relatively similar, here is an example slurm batch script that uses bedtools intersect function to determine regions of overlap on two files with genome data
All intersections were performed using bedtools 2.26
-a: specifies the first file
-b: specifies the second file
intersect will report the regions that b overlaps a, reporting it on a.
Bedtools also has a number of additional options, such as -sb, which in this case will write b for any intersect of a and b, this tells you what the featuer of b is that is overlapping a. 
Bedtools intersect documentation: https://bedtools.readthedocs.io/en/latest/content/tools/intersect.html
