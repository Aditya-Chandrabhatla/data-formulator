<h1>
    <img src="./public/favicon.ico" alt="Data Formulator icon" width="28"> <b>Data Formulator: Create Rich Visualizations with AI</b>
</h1>

<div>
    
[![arxiv](https://img.shields.io/badge/Paper-arXiv:2408.16119-b31b1b.svg)](https://arxiv.org/abs/2408.16119)&ensp;
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)&ensp;

</div>

Transform data and create rich visualizations iteratively with AI 🪄. Try Data Formulator now in GitHub Codespaces!

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/microsoft/data-formulator?quickstart=1)


<kbd>
  <a target="_blank" rel="noopener noreferrer" href="https://codespaces.new/microsoft/data-formulator?quickstart=1" title="open Data Formulator in GitHub Codespaces"><img src="public/data-formulator-screenshot.png"></a>
</kbd>

## Overview

**Data Formulator** is an application from Microsoft Research that uses large language models to transform data, expediting the practice of data visualization.

To create rich visualizations, data analysts often need to iterate back and forth among data processing and chart specification to achieve their goals. To achieve this, analysts need proficiency in data transformation and visualization tools, and they also spend effort managing the iteration history. This can be challenging!

Data Formulator is an AI-powered tool for analysts to iteratively create rich visualizations. Unlike most chat-based AI tools where users need to describe everything in natural language, Data Formulator combines user interface interactions (UI) with natural language (NL) inputs. This blended approach makes it easier for users to describe their chart designs while delegating data transformation to AI. 

Check out these cool Data Formulator features that can help you create impressive visualizations!
* Using the **blended UI and NL inputs** to describe the chart. 
* Utilizing **data threads** to navigate the history and reuse previous results to create new ones instead of starting from scratch every time.

## Get Started

Choose one of the following options to set up Data Formulator:

- **Option 1: Codespaces**
  
  Use Codespaces for an easy setup experience, as everything is preconfigured to get you up and running quickly. For more details, see [CODESPACES.md](CODESPACES.md).
  
  [![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/microsoft/data-formulator?quickstart=1)

- **Option 2: Local Installation**
  
  Opt for a local installation if you prefer full control over your development environment and the ability to customize the setup to your specific needs. For detailed instructions, refer to [DEVELOPMENT.md](DEVELOPMENT.md).


## Using Data Formulator

Once you’ve completed the setup using either option, follow these steps to start using Data Formulator:

### The basics of data visualization
* Provide OpenAI keys and select a model (GPT-4o suggested) and choose a dataset  
* Choose a visualization type
* Drag and drop data fields to the encoding shelf to create visualization


https://github.com/user-attachments/assets/0fbea012-1d2d-46c3-a923-b1fc5eb5e5b8


### Create visualization beyond the initial dataset (powered by 🤖)
* Add new field names in the encoding shelf, describe the chart intent
* Click the **Formulate** button
* Inspect the code behind the concept
* Follow up the chart to create new ones

https://github.com/user-attachments/assets/160c69d2-f42d-435c-9ff3-b1229b5bddba

https://github.com/user-attachments/assets/c93b3e84-8ca8-49ae-80ea-f91ceef34acb

Repeat this process as needed to explore and understand your data. Your explorations are trackable in the **Data Threads** panel. 

## Developers

Follow the [developers' instructions](DEVELOPMENT.md) to build your new data analysis tools on top of Data Formulator.


## Research Papers
* [Data Formulator 2: Iteratively Creating Rich Visualizations with AI](https://arxiv.org/abs/2408.16119)

```
@article{wang2024dataformulator2iteratively,
      title={Data Formulator 2: Iteratively Creating Rich Visualizations with AI}, 
      author={Chenglong Wang and Bongshin Lee and Steven Drucker and Dan Marshall and Jianfeng Gao},
      year={2024},
      booktitle={ArXiv preprint arXiv:2408.16119},
}
```

* [Data Formulator: AI-powered Concept-driven Visualization Authoring](https://arxiv.org/abs/2309.10094)

```
@article{wang2023data,
  title={Data Formulator: AI-powered Concept-driven Visualization Authoring},
  author={Wang, Chenglong and Thompson, John and Lee, Bongshin},
  journal={IEEE Transactions on Visualization and Computer Graphics},
  year={2023},
  publisher={IEEE}
}
```


## Contributing

This project welcomes contributions and suggestions. Most contributions require you to
agree to a Contributor License Agreement (CLA) declaring that you have the right to,
and actually do, grant us the rights to use your contribution. For details, visit
https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need
to provide a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the
instructions provided by the bot. You will only need to do this once across all repositories using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/)
or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
