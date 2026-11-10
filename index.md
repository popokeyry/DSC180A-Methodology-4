Ryan Conrad Atienza

ratienza@ucsd.edu

D02

Aobo Li



**What is the most interesting topic covered in your domain this quarter?**

The most interesting topic covered in our domain is the way the signal is meant to be found: we input a dark matter-like signal that's supposed to "act" like the axion in order to train the models to find the signal while looking through a multitude of frequencies. It is such an interesting idea for training/validation/testing since this signal may or may not exist, we train the models on signals we know exist (hardware-injected sinusoids), then apply them to science data where we don’t know whether a real signal is present. This makes it so that denoising is a way to search for something that might or might not be there.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

A potential investigation I'd like to pursue is to see exactly how and why FC Net outperformed the rest of the architectures. To be specific, I would want to see if it's possible at all to mix and match the different architectures to be able to create a different architecture that utilizes working parts of the rest of them, and see if it's even possible to outperform the findings in the paper. 

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**

A potential change I'd make is attempting to recreate the findings of the paper completely from scratch without knowledge of the codebase beforehand. I think that would be an interesting task especially since it could be a complete fail or we could find something without biases of the paper/codebase. I don't believe it is possible since we have seen the code and know which models work the best, but it is still an approach that I think would be worth a shot to attempt.

**What other techniques would you be interested in using in your project?**

I would want to try data augmentation, mixing noise segments or adding different varying amplitudes/signals. I would to see how the models fare against different noise, and see if we can improve the validation generalization, or even see if the models are just memorizing from the data instead of actually learning and being trained.