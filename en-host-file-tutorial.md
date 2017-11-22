Changing the host file for development purposes.
Opening a wrong file or missing some steps could break your computer. Please use with care.
Intent is to acces old or development sites that are not publicly anymore under their previous domain and where changing the domain is not possible on the site side.

## Step 1. 
Find a nopepad icon. Easiest way is to open up a start menu and type in "notepad". Right click on the notepad menu and select "Run as Administrator". This is critical step, otherwise this will not work.

![]({{site.baseurl}}/assets/images/hostfile.PNG)

## Step 2. 
Once Notepad is opened up, choose New->Open

![]({{site.baseurl}}/assets/images/hostfile2.PNG)

## Step 3. 
Navigate to the folder shown -> C:\Windows\System32\drivers\etc. You should see empty folder. Choose "All files" instead of "Text Documents" from right below as seen in the image. Now four files are visible, choose "hosts" and open

![]({{site.baseurl}}/assets/images/hostfile3.PNG)

## Step 4. 
Once "hosts" file is open, this is where the domain records can be changed for your computer only. 
Create new line below the text and add server ip and server domain seperated by one space as shown in the image. Once it is done, click File->save. Do not close the notepad.

![]({{site.baseurl}}/assets/images/hostfile4.PNG)

## Step 5. 
Now opening a web browser if navigating to the domain you entered, new site should come. If this does not happen, opening a incognito window will usually help.

For reversing changes just remove the line you entered in the hosts file and click save again. Now notepad can be closed.

