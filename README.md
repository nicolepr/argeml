### NOTE: The source code is temporarily unavailable
* We are currently working on some internal issues.
* Feel free to contact me ([nicolep@ucy.ac.cy](nicolep@ucy.ac.cy)) if you need any support.

# ArgEML

## Overview
<p>ArgEML is a general Explainable Machine Learning framework and methodology based on Argumentation [1][2]. It was developed from a novel approach that integrates sub-symbolic methods with logical methods of argumentation to provide explainable solutions to learning problems [3]. In the framework of ArgEML, argumentation is used both as a naturally suitable target language for ML and explanations of the ML predictions as well as the foundation for new notions and metrics that drive the machine learning process.The ArgEML learning methodology is a case of symbolic supervised learning, that can be applied in automatic or hybrid mode, on top of other symbolic or non-symbolic learners that would generate an initial learning theory. Our specific choice of argumentation framework for ArgEML is that of the structured argumentation framework of Gorgias [4], a logic-based preference argumentation framework.</p>
<p>The ArgEML application provides two modes of operation, (a) automatic, and (b) hybrid. In the automatic mode of operation, the application accepts as input a dataset, while in the hybrid mode, the application also accepts as input the results of an external ML model’s execution on the input dataset. The current implementation can process the results of the inTrees library. The application interacts with the SWI-Prolog component for the evaluation of the Gorgias argumentation theories learned.</p>

### Related work
<ol>
<li>[Explainable Machine Learning via Argumentation](https://www.springerprofessional.de/explainable-machine-learning-via-argumentation/26208920).</li>
<li>[Argumentation-based Explainable Machine Learning (ArgEML): a Real-life Use Case on Gynecological Cancer] (https://ceur-ws.org/Vol-3208/paper1.pdf).</li>
<li>[Integrating Machine Learning with Symbolic Reasoning to Build an Explainable AI Model for Stroke Prediction] (https://ieeexplore.ieee.org/document/8941679).</li>
<li>[Gorgias-B] (http://gorgiasb.tuc.gr/).</li>
</ol>

