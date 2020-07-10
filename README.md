# findDeletedReferencedPhotos
AppleScript to find photos in Macos Photos App library whose referenced file is deleted. If the Photos library does not own the images, then they can be deleted without it knowing. This script finds images that are deleted and puts them into an Album.

1. Set `listOfAlbumNamesToScan` to the list of Albums whose Photo Files need to be checked.
2. Set `nameOfDeletedImageFilesAlbum` to the name of the Album that will be created with a reference to the deleted images.
3. Set `referencedFilesFolderName` to the folder where all the photo files are normally stored. This folder (and all the subfolders) will be searched to see if the file exists.

Once the script is processed, you can select all images from the Deleted Files folder and delete them to remove them from your library. 
