---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat.

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


# 🔥 News
- *2022.04*: 🎉🎉 The proposed **Varicolored Haze Dataset (VHD)** in **CVPR2022** has been released. [**Github Repository**](https://github.com/HuaYuuu/PDI2A-CVPR2022)
- *2022.03*: 🎉🎉 One paper for varicolored haze removal is accepted to **CVPR2022**!
- *2021.11*: 🎉🎉 One paper for joint image deraining and segmentation is accepted to **AAAI2022**!
- *2021.11*: 🎉🎉 The code and the corresponding dataset of the proposed category-aware aircraft landmark detection have been released [**Github Repository**](https://github.com/HuaYuuu/CALDN-pytorch-release)
- *2021.07*: 🎉🎉 One collaborate paper for knowledge-guided unsupervised deraining is accepted to **ACMMM2021**.
- *2021.06*: 🎉🎉 One collaborate paper for aircraft landmark detection is accepted to **ICIG2021**.
- *2020.12*: 🎉🎉 One paper is accepted to **IEEE Signal Processing Letter**!
- *2020.04*: 🎉🎉 One collaborate paper is accepted to **IEEE Transactions on Geoscience and Remote Sensing**.

# 📝 Publications 


<div class='paper-box'><div class='paper-box-image'><img src='images/Projects/PDI2A.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**<font color=CornflowerBlue > Physically Disentangled Intra- and Inter-domain Adaptation for Varicolored Haze Removal. </font>** 

**Yi Li**, Yi Chang, Yan Gao, Changfeng Yu, and Luxin Yan, **Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)**, 2022.

[**CVF(coming soon)**](https://huayuuu.github.io) \| [**PDF**](https://huayuuu.github.io/files/2022CVPR_PDI2A.pdf) \| [**Supplementary**](https://huayuuu.github.io/files/2022CVPR_PDI2A_Supp.pdf) \| [**Cite**](https://huayuuu.github.io/files/PDI2A_cite.txt)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/Projects/UBCN.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**<font color=CornflowerBlue > Unsupervised Image Deraining: Optimization Model Driven Deep CNN. </font>** 

**Yi Li**, Yi Chang, Changfeng Yu, and Luxin Yan, **AAAI Conference on Artificial Intelligence (AAAI)**, 2022.

[**AAAI Link**](https://www.aaai.org/AAAI22Papers/AAAI-678.LiY.pdf) \| [**PDF**](https://huayuuu.github.io/files/2022AAAI_UBCN.pdf) \| [**Supplementary**](https://huayuuu.github.io/files/2022AAAI_UBCN_Supp.pdf) \| [**Cite**](https://huayuuu.github.io/files/UBCN_cite.txt)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/Projects/UDGNet.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**<font color=CornflowerBlue > Unsupervised Image Deraining: Optimization Model Driven Deep CNN. </font>** 

Changfeng Yu, Yi Chang, **Yi Li**, Xi-le Zhao, and Luxin Yan, **Proceedings of the 29th ACM International Conference on Multimedia (ACMMM)**, 2021.

[**ACM Digital Library**](https://dl.acm.org/doi/abs/10.1145/3474085.3475441) \| [**PDF**](https://huayuuu.github.io/files/2021ACMMM_UDGNet.pdf) \| [**Cite**](https://huayuuu.github.io/files/UDGNet_cite.txt)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/Projects/SALD.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**<font color=CornflowerBlue > Skeleton-Aware Network for Aircraft Landmark Detection. </font>** 

Yuntong Ye, Yi Chang, **Yi Li**, and Luxin Yan, **International Conference on Image and Graphics (ICIG)**, 2021.

[**Springer Link**](https://link.springer.com/chapter/10.1007/978-3-030-87355-4_16) \| [**PDF**](https://huayuuu.github.io/files/2021ICIG_SALD.pdf) \| [**Cite**](https://huayuuu.github.io/files/SALD_cite.txt)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/Projects/CALDN_figure1_v8_homepage_exhibition.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**<font color=CornflowerBlue > Category-aware Aircraft Landmark Detection. </font>** 

**Yi Li**, Yi Chang, Yuntong Ye, Xu Zou, Sheng Zhong, and Luxin Yan, **IEEE Signal Processing Letter (SPL)**, 2020.

[**IEEE Xplore**](https://ieeexplore.ieee.org/abstract/document/9298853) \| [**PDF**](https://huayuuu.github.io/files/2022SPL_CALDN.pdf) \| [**Cite**](https://huayuuu.github.io/files/CLADN_cite.txt)
- We have released the code and the proposed dataset in the [**Github Repository**](https://github.com/HuaYuuu/CALDN-pytorch-release). 
- This work focuses on the perspective variant aircraft landmark detection task. We are the first to consider category discrepancy to facilitate aircraft landmark detection. Moreover, we also propose the first perspective variant aircraft landmark dataset (PVALD).
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/Projects/Toward_figure.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**<font color=CornflowerBlue > Toward Universal Stripe Removal via Wavelet-Based Deep Convolutional Neural Network. </font>** 

Yi Chang, Meiya Chen, Luxin Yan, Xi-Le Zhao, **Yi Li**, Sheng Zhong, **IEEE Transactions on Geoscience and Remote Sensing (TGRS)**, 2019.
 
[**IEEE Xplore**](https://ieeexplore.ieee.org/abstract/document/8936525) \| [**PDF**](https://huayuuu.github.io/files/2019TGRS_Toward.pdf) \| [**Cite**](https://huayuuu.github.io/files/Toward_cite.txt)

</div>
</div>


- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.