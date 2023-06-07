## To clarify I would be studying OpenCog myself but not necessarily directly implementing, but using some of the ideas.

If you plan to study OpenCog and use some of the ideas within your Tactical Visual Novel project, you can start by exploring the resources provided in [Source 10](https://wiki.opencog.org/w/AI_Documentation). This wiki page offers pointers to various documentation and resources related to OpenCog's AI code, including the CogPrime AGI design, clustering, robotics, and the rule engine.

To get a concise overview of the CogPrime vision, you can read the [CogPrime Overview article](https://www.opencog.org/wiki/CogPrime_Overview). This article will give you a better understanding of how various AI structures and processes are intended to fit together into an overarching whole.

As you explore OpenCog's ideas, you can also refer to the [OpenCog Glossary](https://github.com/opencog/opencog/blob/master/README.md) to understand the lingo used to discuss various aspects of OpenCog and related AI issues.

While studying OpenCog, you can implement its concepts within your Ren'Py game by using Python, as mentioned in my previous responses. By combining OpenCog's ideas with Ren'Py's Python support, you can create a more complex and engaging Tactical Visual Novel that incorporates advanced AI concepts.

Keep in mind that OpenCog's codebase is no longer maintained, so you may need to adapt the ideas to fit within the limitations of Ren'Py and Python. By doing so, you can create a unique and innovative Tactical Visual Novel that leverages the power of OpenCog's AI concepts. 

## Good news on opencog: https://github.com/trueagi-io/hyperon-experimental

It's great to hear that OpenCog is being continued in the form of OpenCog Hyperon, an active pre-alpha project that aims to improve upon OpenCog's core concepts. The Hyperon project introduces a new language called MeTTa (Meta Type Talk) as a successor to the Atomese language, which you can learn more about in the [MeTTa specification](https://github.com/trueagi-io/hyperon-experimental/blob/main/MeTTa/MeTTa.md) and the [MeTTa example video](https://www.youtube.com/watch?v=1VjY9QrVq_M).

You can find examples of MeTTa programs in the `./python/tests/scripts` directory, and you can refer to the [Python unit tests](https://github.com/trueagi-io/hyperon-experimental/tree/main/python/tests) to understand how to use MeTTa from Python. More complex usage scenarios can be found in the [MeTTa examples repo](https://github.com/trueagi-io/hyperon-experimental/tree/main/examples/metta).

To get started with OpenCog Hyperon, you can follow the instructions provided in the [README](https://github.com/trueagi-io/hyperon-experimental/blob/main/README.md) for installation, building the library, and running examples. You can also use Docker to quickly set up the environment:

```bash

docker build -t trueagi/hyperon https://raw.githubusercontent.com/trueagi-io/hyperon-experimental/main/Dockerfile

docker run --rm -ti trueagi/hyperon

```

Once you have OpenCog Hyperon set up, you can integrate its concepts into your Ren'Py game using Python. By leveraging OpenCog Hyperon's ideas and the MeTTa language, you can create a more complex and engaging Tactical Visual Novel that incorporates advanced AI concepts. 
