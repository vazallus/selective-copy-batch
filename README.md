# selective-copy-batch
Selective Copy Batch file

C:\Users\user\folder\*.txt change the path and the file extension, then change the destination folder C:\Users\user\destination !!!

echo COPY FILES
xcopy C:\Users\user\folder\*.txt C:\Users\user\destination /S /F /-Y /I
echo DONE!
