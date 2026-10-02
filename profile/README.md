<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yhatlabs/.github/main/profile/logos/logo-on-dark.png">
    <img alt="YHat Labs" src="https://raw.githubusercontent.com/yhatlabs/.github/main/profile/logos/logo-on-light.png" width="280">
  </picture>
</p>

YHat Labs builds foundation models for time series and tabular data, and systems that forecast real-world events. Our models are served through a hosted API; this organization holds the benchmark records and the code that reproduces them.

- 🌐 [Website](https://yhatlabs.com)
- 🔑 [Get API access](https://yhatlabs.com)
- 🤗 [Model cards on Hugging Face](https://huggingface.co/yhatlabs)
- 📊 [Benchmark results and reproduction notebooks](https://github.com/yhatlabs/yhatlabs)

## The Chakra model family

| Model | Data | What it does | Availability |
|---|---|---|---|
| [ChakraTS](https://huggingface.co/yhatlabs/ChakraTS) | time series | zero-shot probabilistic forecasting: nine quantiles per step, known-future covariates, any regular frequency | API, commercial |
| [ChakraTS-Lab](https://huggingface.co/yhatlabs/ChakraTS-Lab) | time series | research configuration of ChakraTS, used for benchmark entries | evaluation on request |
| ChakraTab | tables | classification and regression on tabular data | coming |

## Benchmarks

We evaluate on the public leaderboards under their official protocols and publish the result files and the notebooks that regenerate them: [GIFT-Eval](https://huggingface.co/spaces/Salesforce/GIFT-Eval) and [fev-bench](https://huggingface.co/spaces/autogluon/fev-bench) for time series, [TabArena](https://tabarena.ai) for tabular. Benchmark data is never used for anything other than scoring.

## Contact

[founders@yhatlabs.com](mailto:founders@yhatlabs.com)
