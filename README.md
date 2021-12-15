<div align="center" markdown>

# Metric Learning Collection

collection of tools to work with metric learning tasks

---

<p float="left">
  <img src="?raw=true" style="width:100%;"/>
</p>


<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#bundles">Bundles</a> •
  <a href="#for-developers">For Developers</a> • 
  <a href="#about-us">About Us</a> 

</p>

</div>

---

# Overview

This collection is designed to cover **Metric Learning** tasks using [**Supervisely**](https://supervise.ly/).  
The collection consists of **Bundles**.  
Each **Bundle** is demonstrated on one domain as an example, but can be applied to other domains as well.

# Bundles


<details>
  <summary style='font-size: 20px'>🧃 Retail Bundle — label images using updatable reference database</summary>
   
  
<div align="center" markdown>  




<p float="left">
  <img src="https://github.com/supervisely-ecosystem/metric-learning-collection/releases/download/v0.0.1/retail-bundle-demo.gif?raw=true" style="width:80%;"/>
</p>
 
 
  

 

<p align="center">
  <a href="#retail-bundle-map">Map</a> •
  <a href="#retail-bundle-launch">Launch</a> •
  <a href="#retail-bundle-applications">Applications</a> 

</p>
<hr/>
   
</div>


### Retail Bundle map
<p>this map illustrates how each application in the bundle connected to each other</p>
<img src="https://imgur.com/pwPAdqb.png" style="width:100%;"/>


--- 



### Retail Bundle launch
<img src="https://imgur.com/ejK0mHt.png" style="width:100%;"/>



--- 



### Retail Bundle applications



<img data-key="sly-module-link" data-module-slug="supervisely-ecosystem/import-csv-catalog" src="https://imgur.com/NtiwR4g.png" width="350px" style='padding-bottom: 20px'/>  

<img data-key="sly-module-link" data-module-slug="supervisely-ecosystem/gl-metric-learning/supervisely/serve" src="https://imgur.com/A3BW6hP.png" width="350px" style='padding-bottom: 10px'/>

<img data-key="sly-module-link" data-module-slug="supervisely-ecosystem/gl-metric-learning/supervisely/calculator" src="https://imgur.com/QL90cJS.png" width="350px" style='padding-bottom: 20px'/>  

<img data-key="sly-module-link" data-module-slug="supervisely-ecosystem/gl-metric-learning/supervisely/similarity-calculator" src="https://imgur.com/WptA30Z.png" width="350px" style='padding-bottom: 20px'/>  

<img data-key="sly-module-link" data-module-slug="supervisely-ecosystem/gl-metric-learning/supervisely/labeling-tool" src="https://imgur.com/8HQvAuT.png" width="350px" style=''/>  

  
</details>



# For Developers
You can use sources from from any application to create your own.

You can also refer to our documentation:

- [How to create Superivsely APP](https://github.com/supervisely-ecosystem/how-to-create-app)
- [Learn SDK Basics with IPython Notebooks](https://sdk.docs.supervise.ly/rst_templates/notebooks/notebooks.html)  
- [Complete Python SDK](https://sdk.docs.supervise.ly/sdk_packages.html)

# About us

You can think of [Supervisely](https://supervise.ly/) as an Operating System available via Web Browser to help you solve Computer Vision tasks. The idea is to unify all the relevant tools that may be needed to make the development process as smooth and fast as possible.

More concretely, Supervisely includes the following functionality:
 - Data labeling for images, videos, 3D point cloud and volumetric medical images (dicom)
 - Data visualization and quality control
 - State-Of-The-Art Deep Learning models for segmentation, detection, classification and other tasks
 - Interactive tools for model performance analysis
 - Specialized Deep Learning models to speed up data labeling (aka AI-assisted labeling)
 - Synthetic data generation tools
 - Instruments to make it easier to collaborate for data scientists, data labelers, domain experts and software engineers

One challenge is to make it possible for everyone to train and apply SOTA Deep Learning models directly from the Web Browser. To address it, we introduce an open sourced Supervisely Agent. All you need to do is to execute a single command on your machine with the GPU that installs the Agent. After that, you keep working in the browser and all the GPU related computations will be performed on the connected machine(s).

- for technical support please leave issues, questions or suggestions in our [repo](https://github.com/supervisely-ecosystem/mmclassification). Our team will try to help.
- also we can chat in slack channel [![](https://img.shields.io/badge/slack-chat-green.svg?logo=slack)](https://supervise.ly/slack)
- if you are interested in Supervisely Enterprise Edition (EE) please send us a [request](https://supervise.ly/enterprise/?demo) or email Yuri Borisov at [sales@supervise.ly](sales@supervise.ly)
