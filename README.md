# Calibrated Perplexity for Robust AI-Generated Text Detection Across Languages and Genres

<!-- Change `kisnikser/m1p-template` to `intsystems/your-repository`-->
[![License](https://badgen.net/github/license/kisnikser/m1p-template?color=green)](https://github.com/kisnikser/m1p-template/blob/main/LICENSE)
[![GitHub Contributors](https://img.shields.io/github/contributors/kisnikser/m1p-template)](https://github.com/kisnikser/m1p-template/graphs/contributors)
[![GitHub Issues](https://img.shields.io/github/issues-closed/kisnikser/m1p-template.svg?color=0088ff)](https://github.com/kisnikser/m1p-template/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr-closed/kisnikser/m1p-template.svg?color=7f29d6)](https://github.com/kisnikser/m1p-template/pulls)

<table>
    <tr>
        <td align="left"> <b> Author </b> </td>
        <td> Vladimir Chaikin </td>
    </tr>
    <tr>
        <td align="left"> <b> Consultant </b> </td>
        <td> German Gritsai </td>
    </tr>
    <tr>
        <td align="left"> <b> Advisor </b> </td>
        <td> Andriy Grabovoy, PhD </td>
    </tr>
</table>

## Assets

- [LinkReview](LINKREVIEW.md)
- [Code](code)
- [Paper](paper/main.pdf)
- [Slides](slides/main.pdf)

## Abstract

This paper invistigates the problem of robust AI-generated text detection under distribution shift. While simple perplexity is a simple solution for such detection, its oppurtunities lose significantly on out-of-domain data. We propose a novel method - calibrated perplexity - which normalizes raw perplexity scores using domain-specific language model baselines. This approach constructs a stable feature space less sensitive to text length, genre, and language variations. Experiments across multiple domains and languages are going to demonstrate improved in-domain and out-of-domain detection accuracy compared to standard perplexity-based methods.

## Citation

If you find our work helpful, please cite us.
```BibTeX
@article{citekey,
    title={Title},
    author={Name Surname, Name Surname (consultant), Name Surname (advisor)},
    year={2025}
}
```

## Licence

Our project is MIT licensed. See [LICENSE](LICENSE) for details.
