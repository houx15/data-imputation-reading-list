# data-imputation-reading-list

## Survey Paper

- Miao, X., Wu, Y., Chen, L., Gao, Y., & Yin, J. (2022). An experimental survey of missing data imputation algorithms. *IEEE Transactions on Knowledge and Data Engineering*, *35*(7), 6630-6650.
- Zhu, J., Zhao, X., Sun, Y., Song, S., & Yuan, X. (2024). Relational Data Cleaning Meets Artificial Intelligence: A Survey. *Data Science and Engineering*, 1-28.



## Traditional Approaches

- **most simple methods: zero, mean, median, most frequent** (Little and Rubin, 2019)
    - Jamshidian, M., & Mata, M. (2007). Advances in analysis of mean and covariance structure when data are incomplete. In Handbook of latent variable and related models (pp. 21-44). North-Holland.
- **multiple imputation: chained equations, Amelia II, matrix factorization**
    - White, I. R., Royston, P., & Wood, A. M. (2011). Multiple imputation using chained equations: issues and guidance for practice. *Statistics in medicine*, *30*(4), 377-399.
    - Sengupta, N., Udell, M., Srebro, N., & Evans, J. (2023). Sparse Data Reconstruction, Missing Value and Multiple Imputation through Matrix Factorization. *Sociological Methodology*, *53*(1), 72-114. https://doi.org/10.1177/00811750221125799
    - Lin, W. C., & Tsai, C. F. (2020). Missing value imputation: a review and analysis of the literature (2006–2017). *Artificial Intelligence Review*, *53*, 1487-1509.
    - Miao, X., Wu, Y., Chen, L., Gao, Y., & Yin, J. (2022). An experimental survey of missing data imputation algorithms. *IEEE Transactions on Knowledge and Data Engineering*, *35*(7), 6630-6650.



## Deep Learning

### Most Simple Examples

- **kNN**: Zhang, S. (2012). Nearest neighbor selection for iteratively kNN imputation. *Journal of Systems and Software*, *85*(11), 2541-2552.

### Diffusion Models

- ⭐⭐⭐ **Diffusion models & time-series**: Tashiro, Y., Song, J., Song, Y., & Ermon, S. (2021). Csdi: Conditional score-based diffusion models for probabilistic time series imputation. *Advances in neural information processing systems*, *34*, 24804-24816.
- ⭐⭐⭐ **Diffusion models & time-series**: Alcaraz, J. M. L., & Strodthoff, N. (2022). Diffusion-based time series imputation and forecasting with structured state space models. *arXiv preprint arXiv:2208.09399*.

- **Diffusion models & time-series**: Gao, H., Shen, W., Qiu, X., Xu, R., Hu, J., & Yang, B. (2024). Diffimp: Efficient diffusion model for probabilistic time series imputation with bidirectional mamba backbone. *arXiv preprint arXiv:2410.13338*.

- ⭐⭐⭐ Wen, Y., Wang, Y., Yi, K., Ke, J., & Shen, Y. (2024, July). Diffimpute: Tabular data imputation with denoising diffusion probabilistic model. In *2024 IEEE International Conference on Multimedia and Expo (ICME)* (pp. 1-6). IEEE. 
- ⭐⭐⭐ Zheng, S., & Charoenphakdee, N. (2022). Diffusion models for missing value imputation in tabular data. *arXiv preprint arXiv:2210.17128*.
- Zhang, H., Fang, L., & Yu, P. S. (2024). Unleashing the potential of diffusion models for incomplete data imputation. *arXiv preprint arXiv:2405.20690*.
- Liu, Y., Ajanthan, T., Husain, H., & Nguyen, V. (2024, October). Self-supervision improves diffusion models for tabular data imputation. In *Proceedings of the 33rd ACM International Conference on Information and Knowledge Management* (pp. 1513-1522).

- **Diffusion model survey**: Yang, L., Zhang, Z., Song, Y., Hong, S., Xu, R., Zhao, Y., ... & Yang, M. H. (2023). Diffusion models: A comprehensive survey of methods and applications. *ACM Computing Surveys*, *56*(4), 1-39.

### Graph-based

**bipartite graph**

- ⭐⭐⭐ You, J., Ma, X., Ding, Y., Kochenderfer, M. J., & Leskovec, J. (2020). Handling missing data with graph representation learning. *Advances in Neural Information Processing Systems*, *33*, 19075-19087.

**similarity-based network information**

- ⭐⭐⭐ Zhong, J., Gui, N., & Ye, W. (2023, June). Data imputation with iterative graph reconstruction. In *Proceedings of the AAAI Conference on Artificial Intelligence* (Vol. 37, No. 9, pp. 11399-11407).
- **network inference in causal inference**: Forastiere, L., Mealli, F., Wu, A., & Airoldi, E. M. (2022). Estimating causal effects under network interference with Bayesian generalized propensity scores. *Journal of Machine Learning Research*, *23*(289), 1-61.

### Time Series

- ⭐⭐⭐ **survey**: Wang, J., Du, W., Cao, W., Zhang, K., Wang, W., Liang, Y., & Wen, Q. (2024). Deep learning for multivariate time series imputation: A survey. *arXiv preprint arXiv:2402.04059*.
- Du, W., Wang, J., Qian, L., Yang, Y., Ibrahim, Z., Liu, F., ... & Wen, Q. (2024). Tsi-bench: Benchmarking time series imputation. *arXiv preprint arXiv:2406.12747*.
- Richter, A., Ijaradar, J., Wetzker, U., Jain, V., & Frotzscher, A. (2024). A Survey on Multivariate Time Series Imputation using Adversarial Learning. *IEEE access*.

### Other

- **GAN (Generative Adversarial Nets)** 
    - Yoon, J., Jordon, J., & Schaar, M. (2018, July). Gain: Missing data imputation using generative adversarial nets. In *International conference on machine learning* (pp. 5689-5698). PMLR.
- **Gaussian distribution-based imputation**
    - Wang, J., Zhang, Y., Wang, K., Lin, X., & Zhang, W. (2024). Missing data imputation with uncertainty-driven network. *Proceedings of the ACM on Management of Data*, *2*(3), 1-25.
- **Distribution matching**
    - Zhao, H., Sun, K., Dezfouli, A., & Bonilla, E. V. (2023, July). Transformed distribution matching for missing value imputation. In *International Conference on Machine Learning* (pp. 42159-42186). PMLR.
- **A pre-trained BERT model**
    - Wang, S., Zhou, W., Wang, S., & Zheng, R. (2024). TREB: a BERT attempt for imputing tabular data imputation. *arXiv preprint arXiv:2410.00022*.

## LLM-based Imputation

- Jaimovitch-López, G., Ferri, C., Hernández-Orallo, J., Martínez-Plumed, F., & Ramírez-Quintana, M. J. (2023). Can language models automate data wrangling?. *Machine Learning*, *112*(6), 2053-2082.
- Zhang, H., Dong, Y., Xiao, C., & Oyamada, M. (2023). Large language models as data preprocessors. *arXiv preprint arXiv:2308.16361*.

### Prompt-based

- **similarity-based example selection**
    - Ashlesha, A., Manatkar, A., Chavda, B., & Patel, H. (2024, June). An Automatic Prompt Generation System for Tabular Data Tasks. In *Annual Conference of the North American Chapter of the Association for Computational Linguistics*.
    - Lim, J., An, S., Woo, G., Kim, C., & Jeon, J. J. Context-Driven Missing Data Imputation via Large Language Model.
- ⭐⭐⭐ **few-shot learning and confidence-based voting**: He, X., Ban, Y., Zou, J., Wei, T., Cook, C. B., & He, J. (2024). LLM-Forest: Ensemble Learning of LLMs with Graph-Augmented Prompts for Data Imputation. *arXiv preprint arXiv:2410.21520*.

### Fine-tuning

- Hayat, A., & Hasan, M. R. (2024). CLAIM Your Data: Enhancing Imputation Accuracy with Contextual Large Language Models. *arXiv preprint arXiv:2405.17712*.
- **Table fine-tuning**: Li, P., He, Y., Yashar, D., Cui, W., Ge, S., Zhang, H., ... & Chaudhuri, S. (2024). Table-gpt: Table fine-tuned gpt for diverse table tasks. *Proceedings of the ACM on Management of Data*, *2*(3), 1-28.

### Other Approaches

- ⭐⭐⭐ **LLM-based embeddings and DCN**: Kim, J., & Lee, B. (2023). Ai-augmented surveys: Leveraging large language models and surveys for opinion prediction. *arXiv preprint arXiv:2305.09620*.



### LLMs for time-series data

- ⭐⭐⭐ **LLM's ability in time-series forecasting and imputation**: Gruver, N., Finzi, M., Qiu, S., & Wilson, A. G. (2023). Large language models are zero-shot time series forecasters. *Advances in Neural Information Processing Systems*, *36*, 19622-19635.
- Jiang, Y., Pan, Z., Zhang, X., Garg, S., Schneider, A., Nevmyvaka, Y., & Song, D. (2024). Empowering time series analysis with large language models: A survey. *arXiv preprint arXiv:2402.03182*.
- Merrill, M. A., Tan, M., Gupta, V., Hartvigsen, T., & Althoff, T. (2024). Language models still struggle to zero-shot reason about time series. *arXiv preprint arXiv:2404.11757*.
- Ye, J., Zhang, W., Yi, K., Yu, Y., Li, Z., Li, J., & Tsung, F. (2024). A survey of time series foundation models: Generalizing time series representation with large language model. *arXiv preprint arXiv:2405.02358*.

### Tabular Data Representation and Reasoning

- ⭐⭐⭐ Fang, X., Xu, W., Tan, F. A., Zhang, J., Hu, Z., Qi, Y., ... & Faloutsos, C. (2024). Large Language Models (LLMs) on Tabular Data: Prediction, Generation, and Understanding--A Survey. *arXiv preprint arXiv:2402.17944*.
- ⭐⭐⭐ Hollmann, N., Müller, S., Purucker, L., Krishnakumar, A., Körfer, M., Hoo, S. B., ... & Hutter, F. (2025). Accurate predictions on small data with a tabular foundation model. *Nature*, *637*(8045), 319-326.
- ⭐⭐⭐ Badaro, G., Saeed, M., & Papotti, P. (2023). Transformers for tabular data representation: A survey of models and applications. *Transactions of the Association for Computational Linguistics*, *11*, 227-249.
- Jiang, J., Zhou, K., Dong, Z., Ye, K., Zhao, W. X., & Wen, J. R. (2023). Structgpt: A general framework for large language model to reason over structured data. *arXiv preprint arXiv:2305.09645*.
- Gong, H., Sun, Y., Feng, X., Qin, B., Bi, W., Liu, X., & Liu, T. (2020, December). Tablegpt: Few-shot table-to-text generation with table structure reconstruction and content matching. In *Proceedings of the 28th International Conference on Computational Linguistics* (pp. 1978-1988).
- Ye, Y., Hui, B., Yang, M., Li, B., Huang, F., & Li, Y. (2023, July). Large language models are versatile decomposers: Decomposing evidence and questions for table-based reasoning. In *Proceedings of the 46th international ACM SIGIR conference on research and development in information retrieval* (pp. 174-184).
- Sui, Y., Zou, J., Zhou, M., He, X., Du, L., Han, S., & Zhang, D. (2023). Tap4llm: Table provider on sampling, augmenting, and packing semi-structured data for large language model reasoning. *arXiv preprint arXiv:2312.09039*.
- Carballo, K. V., Na, L., Ma, Y., Boussioux, L., Zeng, C., Soenksen, L. R., & Bertsimas, D. (2022). Tabtext: a flexible and contextual approach to tabular data representation. *arXiv preprint arXiv:2206.10381*.
- 