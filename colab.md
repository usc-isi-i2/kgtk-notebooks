# Running an ISI Google Colab Notebook

List of steps required to be able to run the ISI Google colab Notebooks.

### 1. Make a copy of the [notebook](https://colab.research.google.com/drive/15JnQA_Uk17Q7u3CADmjwrv7Nkaf2_d9j) to your Google Drive.

The link specified here is a sample notebook. Click on `Save a copy in Drive` from the `File` menu as shown.

![Save a Copy](media/readme-1.png "Save a copy")

This will create a copy of the notebook in your Google Drive.

2. Install `kgtk`

First cell installs [kgtk](https://github.com/usc-isi-i2/kgtk).

Sometimes, you'll see an error while installing `kgtk`, like this:

![Restart Runtime](media/readme-2.png "Restart Runtime")

This is because of a conflict in Google Colab's python environment. You have to click on
the `Restart Runtime` button. 

You do not have to install `kgtk` again.

3. Other installations.

If a notebook installs other libraries, such as `graph-tools` and a similar error
 shows up, (same as in Step 2), clicking on `Restart Runtime` will resolve it.

4. Run  all cells.

Now, simply run all the cells. The notebook should run successfully.

## Google Colab Caveats

- The colab VM and python environment is ephemeral. The VM will reset after a while, all the installed libraries and files produced will be lost. 
- You can [connect a google drive](https://www.marktechpost.com/2019/06/07/how-to-connect-google-colab-with-google-drive/) to the colab notebook to read from and save to.
- Users can run the same colab notebook by sharing it with a link. This can have unwanted complications in case multiple people run the same cell at the same time.


