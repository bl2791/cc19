# cc19 [IT'S NOT DONE YET. DO NOT FORK NOW]
Community contributions for STAT GR 5702 Fall 2019

The class projects will be collected as a bookdown page. You can visit [this link](https://jtr13.github.io/cc19/) to see how it will look like. 

## Submission Steps
1. Give your project a concise, descriptive name. For instance, name it `base_r_ggplot_graph` or something similar if your work is about constrasting/working with base R graphics and GGplot graphics. Your project name should be words only and joined with underscores, i.e. **No whitespace in the name.** We will use `sample_project` as the project name in this tutorial. 
2. Fork [cc19 repo (this repo)](https://github.com/jtr13/cc19) and create your own branch named as the project name given in step 1, which in our case, is `sample_project`. For more information on Github workflow, please refer to [this tutorial](https://edav.info/github.html#branching-someone-elses-repo).
3. Clone/download the fork repo to your local computer.
4. Create a `Rmd` file, named after your project name. In our example, it should be `sample_project.Rmd`. Put it in the root directory of the repo. With regard to content of this file, you should refer to the instructions of this homework on coursework. Two more details on this file: 
    1. No YAML header
    2. The first line should be your project name (this does not have to be exact same as the project folder name). Use one \# to indicate that it is a header. One \# header must not be used anywhere else in the document.
    3. The second line should be blank. For example:
   ```
    # Base R graphics vs. GGplot graphics

    Your content starts here. 
   ```
5. Knit your `Rmd` file into a `html` file, and put it under directory `html/`. In our example, it should be `html/sample_project.html`. 
6. [OPTIONAL] If you have other resources (such as images) included in your project, create a folder under `resources/`. In our example, it should be `resources/sample_project/`. Put the resources files here. 
7. When you are ready to submit your project, push your branch to your remote repo. Follow [this tutorial](https://help.github.com/en/articles/creating-a-pull-request-from-a-fork) to create a pull request. If you follow the steps, we will merge it to the master branch. 

## FAQ
### What should I expect after creating a pull request? 
1. Within a week after you create a pull request, we will apply a label to it and assign an administrater who will review all the files you submit to see if they meet the requirements. 
2. It will take some time before we can process all the pull requests, so as long as you see your pull request has been labeled and assigned to an administrater, don't worry. 
3. However, if the admin contacts you under the pull request, that usually means your files fail to meet some requirements. The admin will clearly state what goes wrong, so please fix them as soon as possible. 

### Other questions
If you encounter other problems, please send us an issue and we will look into it. 
