# M2BSE-Net

Build Virtual Ears for Robots: Monaural Speech Enhancement with Virtual Antiphasic Binaural Speech Mapping

The studies of binaural hearing indicated considerable benefits of the spatial information of sound sources for speech understanding in adverse acoustic environment. However, mainstream monaural speech enhancement methods cannot benefit from such spatial information. In this paper, we propose to enhance the noisy speech that carries self-generated virtual spatial information for the more superior performance under challenging scenarios and present a novel monaural speech enhancement model with the virtual antiphasic binaural speech mapping network. The proposed model is a 2-stage network and trained within a multi-task learning framework. The key steps are 1) applying several supervised monaural to binaural speech mapping blocks at early layers of network to map the monaural noisy speech into antiphasic binaural signal, in which the desired speech and noise be perceived to be opposite directions and thus more discriminative spatial information can be observed, and then 2) enhancing the mapped antiphasic binaural signal at late layers of the network with multi-head cross attention for fully exploiting the spatial information. The experimental results demonstrate the superior performance of the network against the state-of-the-art monaural SE methods.

Submitted to AAAI 2023.
The source code will be released here soon
