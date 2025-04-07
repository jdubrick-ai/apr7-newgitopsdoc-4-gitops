# AI Software Template Gitops

This repository contains the necessary content required for managing Gitops. It was created as part of an AI Software Template. The associated source component is available for reference through the **Overview** tab. You can find an example of this below.

![Overview Tab](./images/overview-dependency.png)
Based on the input from the AI Software Template, a deployment with the following characterisics was made:

**Model Service:** [llama.cpp]( https://github.com/containers/ai-lab-recipes/tree/main/model_servers/llamacpp_python)

**Port:** 8001

An application built from https://github.com/jdubrick-ai/apr7-newgitopsdoc-4 will be stored in [quay.io/jdubrick-ai/apr7-newgitopsdoc-4](https://quay.io/jdubrick-ai/apr7-newgitopsdoc-4) and deployed via Gitops. This application is accessible on port **8501**.