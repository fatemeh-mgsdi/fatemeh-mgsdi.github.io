---
title: Create Github page
author: fatemeh
date: 2023-01-11 06:02:00 -0500
categories: [Tutorial]
tags: [github page]
---
As a developer, you may want to have a personal website or blog. Somewhere to place your resume, or blog about different things you'd like to talk about. There are multiple solutions for having such blog, but is this post we're going through steps to create your blog by using github pages. We're going to withe some HTML code, and then publish it in [some_name].github.io page, and you'll see it will deploy all your changes and everyone can visit that site. In this way, you developed your own website for free. <br>So let's dig in!

### Prerequisites

I assume you already have a Github account and know how to create, clone, commit and push your changes to a git repository!



### Create Github page!

1. Create a new repository, name it `<GH_USERNAME>.github.io`, where `GH_USERNAME` is your GitHub username. Also, make sure the repository is **public**, and then click the **Create repository** button. 

2. Clone the repository in your local system.

3. Create an **index.html** file in the root directory of the repository. 

4. Go to [this link](https://github.com/fatemeh-mgsdi/blog-documents/blob/main/create-github-page/index.html) and copy the content to **index.html**, or you can use this command instead in your repository root directory:

    ```console
    wget https://github.com/fatemeh-mgsdi/blog-documents/blob/main/create-github-page/index.html
    ```

    

5. In your repository, go to **Settings** and in the sidebar, click **Pages**.

   ![pages](https://user-images.githubusercontent.com/33480382/211783479-10deadbd-b7b0-4ca4-986c-92577ee816b4.png)

   

6. Choose the main branch you've pushed your code to and click on **Save**.

    ![branch](https://user-images.githubusercontent.com/33480382/211783935-1f5e38a6-4520-4f34-bfa1-6157e350ba21.png)



7. Now if you go to **Actions** tab, you can see the deploy job is running!

    ![actions](https://user-images.githubusercontent.com/33480382/211785844-8308a08e-c82c-4146-a380-e499c753b352.png)

    Wait for a little bit, and you'll see the workflow is over:

    ![workflow](https://user-images.githubusercontent.com/33480382/211785656-01241f28-440b-400c-9040-d8cd14e7e5df.png)

       

Now simply visit `<GH_USERNAME>.github.io` .

You can update your code, add some style to your blog and customize it; After each push, all workflows will re-run again and all the changes will be deployed.

In the incoming posts, we'll go through all these steps, and add a theme to our website!<br>You can share your thoughts, questions or any suggestions you have via:<br>
Email: <fatemeh.maghsoudi76@gmail.com> <br>
LinkedIn: [https://www.linkedin.com/in/fatemehmaghsoudi](https://www.linkedin.com/in/fatemehmaghsoudi)



 