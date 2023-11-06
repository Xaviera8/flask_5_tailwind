# flask_5_tailwind

1.On Azure, create a storage account. Create a container with the anonymous access level set to "container". 

2. After deployment, enter the container and upload a video file from your local device. 

3. Afer the upload is complete you can click the file to find additional information. Copy the path of the URL. 

4. Under Security and Networking, select Front Door and CDN. Set up a an Azure CDN. 

5. In a new tab, enter the CDN hostname followed by the path from for file uploaded to the storage account. Assuming this was done correctly you should be able to view your uploaded content. Save this link

6. In Google Cloud, create a folder that contains a template folder as well as an app.py.

7. In the templates folder, create an html file that contains the link that you saved.

8. Run your flask applications.

