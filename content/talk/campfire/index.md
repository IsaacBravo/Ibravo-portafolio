---
title: "Annual Conference of the Science Communication Division (DGPuK) 2024"
subtitle: "Science Communication Conference"
excerpt: "Here is my presentation along with Katharina Prasse (Uni. Mannheim), titled Detecting Manipulated Visuals: A Computational Approach in the Climate Change Discourse, at the 6th ANNUAL COMPTEXT Conference in Amsterdam."
date: 2024-06-06
date_end: "2024-06-07"
featured: true
show_post_time: false
event: "Annual Conference of the Science Communication Division (DGPuK) 2024"
event_url: https://ikmz.uzh.ch/en/aiscicomm24/
author: "Isaac Bravo & Katharina Prasse"
location: "Zurich, Switzerland"
draft: false
# layout options: single, single-sidebar
layout: single
categories:
- conference
links:
- icon: door-open
  icon_pack: fas
  name: website
  url: https://ikmz.uzh.ch/en/aiscicomm24/
#- icon: github
#  icon_pack: fab
#  name: code
#  url: https://github.com/apreshill/bakeoff
---
## Abstract:

The emergence of Artificial Intelligence (AI) models is reshaping how scientists interact with this technology when conducting research. This has led to a growing interest in the role and impact of AI in the field of scientific communication over the last few years (Schäfer, 2023). The benefits of this technology that we can find as researchers are varied (Chian & Lee, 2023; Krishnan et al., 2023). Simultaneously, manipulated images pose a misinformation risk when viewers cannot determine the credibility of what they see (He, 2021). While computer science research in this field commonly uses images from "lab scenarios" to identify manipulated content, we focus on the polarized topic of climate change to explore how manipulated images shared on Twitter may contribute to polarizing debates between believers and sceptics (deniers) in anthropogenic climate change. This study contributes to two important aspects in the debate on science communication in the age of AI: a) How manipulated images are spreading on the social media landscape, and the resulting impact on public debates, and b) how methodological advances in machine learning and computer vision can help scientists to detect and analyse manipulated images. 

Climate change is a global phenomenon which has received considerable media attention in recent decades (IPCC, 2022). Experts have recognized the urgency of addressing the impacts of this phenomenon and understanding how people perceive and engage with it (Falkenberg et al., 2022). In the digital media environment, the emergence of climate change information on social media, especially visual content, has changed how individuals understand this phenomenon and how it encourages collective action (Pearce et al., 2019). Despite the scientific evidence of the anthropocentric origin of climate change, contrarian voices still reject this reality and the related risks (though in many cases, these are minority opinions (Whitmarsh, 2011). The causes of such positions include disagreement between scientists (Patt, 2007) and people's attitudes and beliefs (Kahan et al., 2012). 

Social media allows the circulation of opinions and manipulated content that may support or deny certain beliefs or facts. However, the emergence of image generative models has made it much easier for people to create ‘deep fake’ or synthetic images, and simultaneously, computer science research has started to improve their detection (Guan, 2022). Manipulated visual content can, for example, exaggerate or misrepresent climate change-related phenomena, mislead individuals, fuel scepticism regarding the veracity of climate change, and potentially erode trust in media and scientific institutions (Capstick & Pidgeon, 2014). Due to the limited development of computational studies, previous work mainly focused on analysing visual elements of climate change using qualitative approaches and small samples (Schäfer, 2020; Harb et al., 2020; Metag et al., 2016). Notably, there is a lack of studies on the prevalence and impact of manipulated content and how users interact with this type of visual content related to climate change on social media.

This study aims to answer the following research question: Do ‘real’ vs manipulated images about climate change on Twitter lead to different levels of engagement and interactions between believers and skeptics (deniers)? This study adopts a multimodal and computational approach combining automated image and text analysis to examine more than 700,000 images, and replies shared by Twitter users in the year 2019 in the context of climate change. For the data collection, we sampled all tweets that included an image and the term "climate change" or the hashtag "#climatechange" in English. We compare methods detecting manipulated images, such as hash functions, to retrieve pairs of near-identical images, and analyse the manipulation that took place between the ‘real’ and the manipulated image within each pair. More precisely, we use the “Crop-Resistant Hash” proposed by Steinbach et al., where individual segments of the images are hashed and then compared to identify near-identical images. This method allows the matching even after major image manipulations. Then, we use different computational techniques such as topic modelling (BERTopic) and Latent Semantic Scaling (LSS) to analize and classify comments between believers and sceptics.

Preliminary results reveal user differences in the distribution of engagement between manipulated and real images, as well as a concentration of user interactions around specific topics related mainly to the consequences of climate change. Furthermore, these differences concern not only the type of visual content engaged by deniers and believers but also how these users react to it. Here, we generally see that the believers exhibit more engagement than deniers when they are exposed to real images. While manipulated images only make up a small share of the total number of images shared on Twitter, they can lead to considerable user engagement and directly impact people’s understanding of climate change. 
This study makes a theoretical and methodological contribution to the field of science communication: From a theoretical perspective, the research delves into the framing strategies adopted by believers and sceptics (deniers) on Twitter, specifically comparing the use of manipulated and real images on a polarized climate change debate. The methodological contribution lies in using a computer science approach to detect manipulated images within the context of climate change-related data. By employing advanced detection techniques, the study also contributes to our understanding of the effectiveness of existing models in discerning between authentic and manipulated content in the climate change debate on social media platforms.


## My Presentation:

<iframe src="https://drive.google.com/file/d/1AYQH1LMnY9AsIcsH_lAF8249EJHfQdDc/preview?usp=sharing" style="width:100%; height:600px;" frameborder="0"></iframe>
