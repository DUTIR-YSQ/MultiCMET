# MultiCMET
This is the official implementation for “MultiCMET: A Novel Chinese Benchmark for Understanding Multimodal Metaphor” (EMNLP Findings 2023)

# Info

MultiCMET, a multimodal Chinese metaphor dataset, consisting of 13,820 text-image pairs of advertisements with manual annotations of the occurrence of metaphors, source and target domain categories, and sentiments metaphors convey. 

The collection of the Chinese dataset consists of two parts. 

1.The first part is called "ZH_pbs. csv", which collects potential Chinese advertising metaphor samples by searching for keywords related to "advertising" and "metaphor" on Baidu and Bing. The first column is the ID of the image. The second column contains image links, which can be used to access imag. The third column indicates whether it is a metaphor, with 1 representing metaphor and 0 representing literal meaning. The fifth and sixth columns represent the source domain type and the target domain type, respectively. The types include: 1: relationship, 2: communication, 3: attribute, 4: psychological_feature, 5: person, 6: plant, 7: animal, 8: process, 9: event, 10: substance, 11: natural_object, 12: artifact, and 13: location. The seventh column represents the type of emotion, which includes -1: negative, 0: neutral, 1: positive.

2.The second part is called "ZH_ifs. csv", which collects potential Chinese metaphorical advertising samples from the large-scale Chinese commercial advertising dataset publicly released in the 2021 iFlytek Advertising Image Classification Competition. The first column represents the image ID, which corresponds to the ID in the 2021 advertising dataset and can be used to retrieve images. The second column indicates whether it is a metaphor, with 1 representing metaphor and 0 representing literal meaning. The third and fourth columns represent the source domain type and the target domain type, respectively. The types include: 1: relationship, 2: communication, 3: attribute, 4: psychological_feature, 5: person, 6: plant, 7: animal, 8: process, 9: event, 10: substance, 11: natural_object, 12: artifact, and 13: location. The fifth column represents the type of emotion, which includes -1: negative, 0: neutral, 1: positive.s.

# Citation
Dongyu Zhang, Jingwei Yu, Senyuan Jin, Liang Yang, and Hongfei Lin. 2023. MultiCMET: A Novel Chinese Benchmark for Understanding Multimodal Metaphor. In Findings of the Association for Computational Linguistics: EMNLP 2023, pages 6141–6154, Singapore. Association for Computational Linguistics.
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

---
