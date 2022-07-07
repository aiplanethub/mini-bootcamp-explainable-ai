# Other Explainable AI Tools

## Learning Objectives

* ELI5
* Skater
* What-If Tool
* Azure ML

We’ve learned about 2 Explainable AI Frameworks - LIME and SHAP.

There are more such tools/frameworks that we can utilize for model interpretation. Let’s have a look at those briefly. You can explore them in detail if you find any of them interesting.


## ELI5

* ELI5 is a Python package that helps debug machine learning classifiers and explain their predictions in an easy-to-understand and intuitive way.
* It is perhaps the easiest of the three machine learning frameworks since it involves minimal documentation reading!
* However, it doesn’t support true model-agnostic interpretations, and support for models is mainly limited to tree-based and other parametric/linear models.
* You can install it using `pip install eli5`.



## Skater

* Skater is a unified framework to enable Model Interpretation for all forms of models to help one build an Interpretable machine learning system often needed for real-world use-cases using a model-agnostic approach.
* It is an open-source python library designed to demystify the learned structures of a black box model both globally(inference based on a complete data set) and locally(inference about an individual prediction).
* You can typically install Skater using a simple `pip install skater`.




## What-If Tool

* The What-If Tool (WIT) provides an easy-to-use interface to expand understanding of a black-box classification or regression ML model.
* With the plugin, you can perform inference on a large set of examples and visualize the results in various ways.
* The tool’s purpose is to give people a simple, intuitive, and powerful way to play with a trained ML model on a data set through a visual interface with absolutely no code required.
* The tool can be accessed through TensorBoard or as an extension in a Jupyter or Colab notebook.
* A custom prediction function can load any model and provide additional customizations to the What-If Tool, including feature attribution methods like SHAP, Integrated Gradients, or SmoothGrad.
* Here’s the What-if Tool demo for the dataset we used for SHAP implementation(UCI Dataset).














<iframe width="560" height="315" src="https://www.youtube.com/embed/qTUUwfG1vSs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>










* Look at the beautiful interactive visualizations it creates: [https://pair-code.github.io/what-if-tool/demos/uci.html](https://pair-code.github.io/what-if-tool/demos/uci.html)

## Azure ML

Azure ML proposes its own version of SHAP and alternative tools, adding interactive dashboards.

You can learn how to use its interpretability package [here](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-machine-learning-interpretability-aml).

### Additional Resources

This article outlines 8 Explainable AI Frameworks. You can go through it if you wish to explore more! 

https://analyticsindiamag.com/8-explainable-ai-frameworks-driving-a-new-paradigm-for-transparency-in-ai/