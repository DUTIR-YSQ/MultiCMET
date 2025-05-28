# 🧠 MultiCMET

**Official implementation for**  
**_“MultiCMET: A Novel Chinese Benchmark for Understanding Multimodal Metaphor”_**  
📄 *Findings of the Association for Computational Linguistics: EMNLP 2023*

---

## 📘 Overview

**MultiCMET** is a large-scale **Chinese multimodal metaphor** dataset designed for fine-grained research on metaphor understanding in advertising contexts.

- **Total samples**: 13,820 **text–image pairs**
- **Annotations** include:
  - Metaphor presence (binary)
  - Source domain category (13 types)
  - Target domain category (13 types)
  - Emotion conveyed (positive / neutral / negative)

---

## 📂 Dataset Structure

The dataset consists of two subsets:

### 1. `ZH_pbs.csv`

- **Source**: Web-crawled using keywords related to “advertising” and “metaphor” on Baidu and Bing.
- **Fields**:

  | Column | Description |
  |--------|-------------|
  | 1      | Image ID |
  | 2      | Image URL |
  | 3      | Metaphor label (`1` = metaphor, `0` = literal) |
  | 5      | Source domain type (1–13) |
  | 6      | Target domain type (1–13) |
  | 7      | Emotion (`-1` = negative, `0` = neutral, `1` = positive) |

### 2. `ZH_ifs.csv`

- **Source**: 2021 iFlytek Chinese Ad Image Classification Competition dataset.
- **Fields**:

  | Column | Description |
  |--------|-------------|
  | 1      | Image ID (matches iFlytek dataset) |
  | 2      | Metaphor label |
  | 3      | Source domain type |
  | 4      | Target domain type |
  | 5      | Emotion |

### Domain Types (1–13)

1. Relationship  
2. Communication  
3. Attribute  
4. Psychological Feature  
5. Person  
6. Plant  
7. Animal  
8. Process  
9. Event  
10. Substance  
11. Natural Object  
12. Artifact  
13. Location

---

## 🔖 Citation

If you use **MultiCMET**, please cite the following paper:

```bibtex
@inproceedings{zhang2023multicmet,
  title     = {MultiCMET: A Novel Chinese Benchmark for Understanding Multimodal Metaphor},
  author    = {Zhang, Dongyu and Yu, Jingwei and Jin, Senyuan and Yang, Liang and Lin, Hongfei},
  booktitle = {Findings of the Association for Computational Linguistics: EMNLP 2023},
  pages     = {6141--6154},
  year      = {2023},
  address   = {Singapore},
  publisher = {Association for Computational Linguistics}
}

## 🔬 Explore More Research from Our Lab

**Important❗**  If you use any of our lab's datasets, please make sure to cite them in the above format❗

1. **[MultiMET: A Multimodal Dataset for Metaphor Understanding (ACL 2021)](https://github.com/DUTIR-YSQ/MultiMET)**  
   A foundational multimodal dataset for metaphor understanding, combining text and visual modalities.  
   **Citation Format**:  
   Dongyu Zhang, Minghao Zhang, Heting Zhang, Liang Yang, and Hongfei Lin. 2021. MultiMET: A Multimodal Dataset for Metaphor Understanding. In Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing (Volume 1: Long Papers), pages 3214–3225, Online. Association for Computational Linguistics.

2. **[Cultural Bias Matters: A Cross-Cultural Benchmark Dataset and Sentiment-Enriched Model for Understanding Multimodal Metaphors (ACL 2025)](https://github.com/DUTIR-YSQ/MultiMM)**  
   A cross-cultural benchmark dataset that incorporates sentiment signals to improve multimodal metaphor detection across languages.  
   **Citation Format**:  
   Senqi Yang, Dongyu Zhang, Jing Ren, Ziqi Xu, Xiuzhen Zhang, Yiliao Song, Hongfei Lin, and Feng Xia. 2025. *Cultural Bias Matters: A Cross-Cultural Benchmark Dataset and Sentiment-Enriched Model for Understanding Multimodal Metaphors*. In *Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)*, pages XX–XX, **Vienna, Austria**. Association for Computational Linguistics.

3. **[EmoMeta: A Chinese Multimodal Metaphor Dataset and Novel Method for Emotion Classification (WWW 2025)](https://github.com/DUTIR-YSQ/EmoMeta)**  
   A new Chinese dataset and method for emotion classification based on multimodal metaphors.  
   **Citation Format**:  
   Lu, X., Liu, Y., Zhang, D., Wu, Z., Ren, J., & Xia, F. (2025, May). EmoMeta: A Multimodal Dataset for Fine-grained Emotion Classification in Chinese Metaphors. In Companion Proceedings of the ACM on Web Conference 2025 (pp. 3080-3083).

4. **[MultiCMET: A Novel Chinese Benchmark for Understanding Multimodal Metaphor (EMNLP 2023)](https://github.com/DUTIR-YSQ/MultiCMET)**  
   A high-quality Chinese benchmark designed to support multimodal metaphor understanding in NLP and vision-language tasks.  
   **Citation Format**:  
   Zhang, D., Yu, J., Jin, S., Yang, L., & Lin, H. (2023, December). Multicmet: A novel Chinese benchmark for understanding multimodal metaphor. In Findings of the Association for Computational Linguistics: EMNLP 2023 (pp. 6141-6154).


## 📚 References (BibTeX)

```bibtex
@inproceedings{zhang2021multimet,
  title     = {MultiMET: A multimodal dataset for metaphor understanding},
  author    = {Zhang, Dongyu and Zhang, Minghao and Zhang, Heting and Yang, Liang and Lin, Hongfei},
  booktitle = {Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing (Volume 1: Long Papers)},
  pages     = {3214--3225},
  year      = {2021}
}

@inproceedings{yang2025cultural,
  title     = {Cultural Bias Matters: A Cross-Cultural Benchmark Dataset and Sentiment-Enriched Model for Understanding Multimodal Metaphors},
  author    = {Yang, Senqi and Zhang, Dongyu and Ren, Jing and Xu, Ziqi and Zhang, Xiuzhen and Song, Yiliao and Lin, Hongfei and Xia, Feng},
  booktitle = {Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)},
  pages     = {XX--XX},
  year      = {2025},
  address   = {Vienna, Austria},
  publisher = {Association for Computational Linguistics}
}

@inproceedings{lu2025emometa,
  title     = {EmoMeta: A Multimodal Dataset for Fine-grained Emotion Classification in Chinese Metaphors},
  author    = {Lu, Xingyuan and Liu, Yuxi and Zhang, Dongyu and Wu, Zhiyao and Ren, Jing and Xia, Feng},
  booktitle = {Companion Proceedings of the ACM on Web Conference 2025},
  pages     = {3080--3083},
  year      = {2025}
}

@inproceedings{zhang2023multicmet,
  title     = {Multicmet: A novel chinese benchmark for understanding multimodal metaphor},
  author    = {Zhang, Dongyu and Yu, Jingwei and Jin, Senyuan and Yang, Liang and Lin, Hongfei},
  booktitle = {Findings of the Association for Computational Linguistics: EMNLP 2023},
  pages     = {6141--6154},
  year      = {2023}
}
