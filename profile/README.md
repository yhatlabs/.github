<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yhatlabs/.github/main/profile/logos/logo-on-dark.png">
    <img alt="YHat Labs" src="https://raw.githubusercontent.com/yhatlabs/.github/main/profile/logos/logo-on-light.png" width="280">
  </picture>
</p>

YHat Labs builds foundation AI models for tabular data: ChakraTS forecasts any time series and ChakraTab predicts on any table, pretrained, one API call, no training or tuning. We also build systems that forecast real-world events. This organization holds the benchmark records and the code that reproduces them.

- 🌐 [Models and results](https://yhatlabs.com/models)
- 🔑 [Request API access](https://yhatlabs.com/models/access)
- 🤗 [Model cards on Hugging Face](https://huggingface.co/yhatlabs)
- 📊 [Benchmark results and reproduction notebooks](https://github.com/yhatlabs/yhatlabs)

## The Chakra model family

| Model | Data | What it does | Availability |
|---|---|---|---|
| [ChakraTS](https://huggingface.co/yhatlabs/ChakraTS) | time series | zero-shot probabilistic forecasting: nine quantiles per step, known-future covariates, any regular frequency | API, commercial |
| [ChakraTS-Lab](https://huggingface.co/yhatlabs/ChakraTS-Lab) | time series | research configuration of ChakraTS, used for benchmark entries | evaluation on request |
| [ChakraTab](https://huggingface.co/yhatlabs/ChakraTab) | tables | classification and regression with class probabilities | API, commercial |

## Benchmarks

We evaluate on the public leaderboards under their official protocols and publish the result files and the notebooks that regenerate them. Standing as of October 2026:

| Benchmark | Model | Standing |
|---|---|---|
| [fev-bench](https://huggingface.co/spaces/autogluon/fev-bench) | ChakraTS | 1st by win rate, 2nd by skill score |
| [TIME](https://huggingface.co/spaces/Real-TSF/TIME-leaderboard) | ChakraTS | 2nd of 31 |
| [GIFT-Eval](https://huggingface.co/spaces/Salesforce/GIFT-Eval) | ChakraTS | 3rd overall (under review) |
| [TabArena](https://tabarena.ai) | ChakraTab | top 5 (under review) |

Result files and reproduction notebooks: [yhatlabs/yhatlabs](https://github.com/yhatlabs/yhatlabs). Benchmark data is never used for anything other than scoring.

## Contact

[founders@yhatlabs.com](mailto:founders@yhatlabs.com)
