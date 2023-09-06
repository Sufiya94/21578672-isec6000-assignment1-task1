# 21578672-isec6000-assignment1-task1
21578672-isec6000-assignment1-task1
a. Log in to your Google Cloud Console.
1.	I have login into Google Cloud Console
2.	I have successfully created an account and created a new project.
3.	Filled in Project Details:
a) Project Name: (21578672-ISEC6000-Task1)
5.After creating my project on Google Cloud Console, I was redirected to the project dashboard.
<img width="452" alt="image" src="https://github.com/Sufiya94/21578672-isec6000-assignment1-task1/assets/143176929/f62d061d-c99f-4bd7-83c7-575541b63061">
b) Create a Kubernetes cluster on GKE tool.
1.	I have Selected my Project:
2.	I have accessed the "Kubernetes Engine" option in the left-hand menu.
3.	I have created a New standard Cluster.
4.	Configured my Cluster:
Cluster Basics:
Name: isec6000-cluster-task1 
Location: Australia-southeast1-a
5.	Once the cluster is created, I have connected it to the Kubernetes engine.

<img width="338" alt="image" src="https://github.com/Sufiya94/21578672-isec6000-assignment1-task1/assets/143176929/b4b19d32-e1dd-44ba-988f-01701bc67fd2">
c. Configure your cluster settings:
If you're looking to set up cluster settings for a typical use case, Kubernetes can serve as a useful reference point. The initial step involves selecting a cluster management tool such as Google GKE. Depending on the tool you choose, you'll then need to take care of provisioning the cluster nodes. Once that's done, you can utilize kubectl or a deployment tool to effectively deploy and oversee your applications on the cluster.
<img width="497" alt="image" src="https://github.com/Sufiya94/21578672-isec6000-assignment1-task1/assets/143176929/5283b619-1c21-4013-9fe8-2febf8f0ca9e">
d. Choosing the desired Kubernetes version.
Choosing the right Kubernetes version for your cluster is an essential step that can have a significant impact on your application's compatibility and access to new features and security updates. We suggest starting by reviewing the release notes for all available Kubernetes versions. Doing so will offer valuable insights into the latest features, bug fixes, and security updates that accompany each release.
<img width="466" alt="image" src="https://github.com/Sufiya94/21578672-isec6000-assignment1-task1/assets/143176929/4445b29c-8ef6-4ac8-b008-6c1d8e276c00">
e.	Click "Create" to provision your GKE cluster.
Now, the cluster has been fully created and is ready for use.
<img width="419" alt="image" src="https://github.com/Sufiya94/21578672-isec6000-assignment1-task1/assets/143176929/1c64ade0-2adf-40e6-b55c-ea14b3512953">
2. Install and configure kubectl to manage your Kubernetes cluster.
a) After creating the GKE cluster, you will need to configure your local environment to use kubectl to interact with this cluster.
After creating the GKE cluster, I configured kubectl to use the credentials by authenticating it with the cluster using the command in the terminal.
<img width="366" alt="image" src="https://github.com/Sufiya94/21578672-isec6000-assignment1-task1/assets/143176929/ef2281a0-18e5-4111-a995-35691c902dc7">
b) In the Google Cloud Console, navigate to the "Kubernetes Engine" > "Clusters"
     section and click the "Connect" button next to your cluster.
<img width="443" alt="image" src="https://github.com/Sufiya94/21578672-isec6000-assignment1-task1/assets/143176929/d6b6d047-58e2-4c75-84bd-135387a2e70f">
c)Follow the instructions to authenticate kubectl with your GKE cluster.
If you want to authenticate kubectl with your Google Kubernetes Engine (GKE) cluster, you'll need to use Google Cloud SDK (gcloud) for authentication. The following steps will guide you through the process:
1.	Open a terminal and run the following command to initialize gcloud and authenticate with your Google Cloud account: 
`gcloud init`
2. Set the Project and Zone: If you have multiple projects and zones in your Google Cloud account, set the default project and zone for gcloud. Replace [PROJECT_ID] and [ZONE] with your specific project and zone:
gcloud config set project [PROJECT_ID]
gcloud config set compute/zone [ZONE]
<img width="377" alt="image" src="https://github.com/Sufiya94/21578672-isec6000-assignment1-task1/assets/143176929/c54ca654-8818-469c-ac05-6cafd2d7b237">
3. Set up a private GitHub repository to store your project files.
I logged in to my GitHub account and proceeded to create a new repository. To do so, I clicked on the "+" icon located in the top-right corner of the GitHub dashboard, then selected "New Repository" from the dropdown menu. Next, I filled out the repository name as "21578672-isec6000-assignment1-task1" and selected the repository visibility to be public. Finally, I initialized the repository with a README file.
https://github.com/Sufiya94/21578672-isec6000-assignment1-task1
<img width="359" alt="image" src="https://github.com/Sufiya94/21578672-isec6000-assignment1-task1/assets/143176929/59a537aa-54c1-493c-983b-d198b0f54db6">

