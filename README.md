# EMR Workshop samples


## Run book

The following run book contains guidance for accessing the AWS Event Engine and outliens what workshops we are completing today. 
[Workshop link](https://catalog.us-east-1.prod.workshops.aws/workshops/3c29bc13-0f30-42f7-9f97-4ce8e2ef9b17/en-US)

## Hints and tips for sample notebooks

The following provides some specifici tips you may need to be aware of when running the sample notebooks.

[Massey University lecture runsheet (PDF)](MasseyLecture-RunSheet.pdf)


### Visualize-data-with-pandas-matplotlib

After first cell “pip install matplotlib “ and the 13th Cell “ from sklearn.datasets import * “ you may need to restart the Kernel.  To do this either:
1. Right click on your notebook and select **RESTART KERNEL** from the context menu.
2. Click the **RESTART KERNEL** icon, ( the one that looks like a REFRESH icon ) in the  menu bar at the top of the notebook.

Note that you may need to re-run your cells from the top of the notebook after a kernel restart.

### Word-count-wth-spark 

The **SET UP** instructions asks you to create an **S3 Bucket**. The last cell writes the final file to the bucket you set up.  You can either skip the last cell, or create a S3 bucket as per the instructions below, then complete run the last cell.

1. Switch to the AWS Console tab in your web browser 
2. in the Search box in the top navigation bar type **S3**, then select S3 from the list of results that gets displayed.
3. Click the orange **CREATE BUCKET** button on the right hand side of the screen
4. In the BUCKET NAME field enter the following replacing [your initials with your initials  : results-bucket-<your initials>  e.g results-bucket-ch
    
    *NOTE: bucket names need to be globally unique. If it fails to create try adding a 4 random numbers to the end of your bucket name. E.g results-bucket-ch-4673*
5. Scroll to the bottom of the page and click the **CREATE BUTTON** page
