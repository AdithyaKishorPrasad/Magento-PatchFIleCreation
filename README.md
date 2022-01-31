# Magento-PatchFIleCreation

STEP 1: Copy and Paste the modified conent on the OrigionalFile.
STEP 2: git diff OrigionalFilePath > modifildFile.patch
STEP 3: git checkout OrigionalFile
STEP 4: Verify: git apply modifildFile.patch
STEP 5: DONE,Check the file you can see the changes after running patch script.
STEP 6: git checkout OrigionalFile
STEP 7: place the new created patch file inside root(Project Folder)>>patches (directory) >> modifildFile.patch
STEP 8: END!

