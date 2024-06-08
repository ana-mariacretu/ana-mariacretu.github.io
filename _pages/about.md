---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from:  
- /about/  
- /about.html
---

I am a postdoc in the [SPRING Lab](https://spring.epfl.ch/) at EPFL, headed by Prof. Carmela Troncoso. My position is funded by the [CYD Distinguished Postdoctoral Fellowship](https://www.epfl.ch/research/funding/epfl-programmes/cyd/cyd-postdoc/) of the Cyber-Defense Campus, where my main collaborator is Dr. Raphael Meier.

I completed my PhD in the [Computational Privacy Group](https://cpg.doc.ic.ac.uk/index.html) at [Imperial College London](https://www.imperial.ac.uk/), advised by [Dr. Yves-Alexandre de Montjoye](http://www.demontjoye.com/index.html). My research lies at the intersection between machine learning, privacy, and security. I study privacy and security vulnerabilities in data processing technologies: machine learning models, query-based systems, and perceptual hashing-based client-side scanning, through the lens of automated attacks. Through a rigorous study of privacy vulnerabilities, my research can inform the design of principled countermeasures allowing to prevent them and, ultimately, to use data safely.

# News {#news}

08/06/2024: New paper "A Zero Auxiliary Knowledge Membership Inference Attack on Aggregate Location Data" accepted in PoPETS 2024! Joint work with Vincent Guan, Florent Guépin and Yves-Alexandre de Montjoye. 

05/06/2024: New paper [Correlation inference attacks against machine learning models](https://arxiv.org/abs/2112.08806) accepted in Science Advances! Joint work with Florent Guépin and Yves-Alexandre de Montjoye.

26/02/2024: New paper [Re-pseudonymization Strategies for Smart Meter Data Are Not Robust to Deep Learning Profiling Attacks](https://arxiv.org/abs/2404.03948) accepted at CODASPY 2024! Joint work with Miruna Rusu and Yves-Alexandre de Montjoye.

01/02/2024: New paper [Investigating the Effect of Misalignment on Membership Privacy in the White-box Setting](https://arxiv.org/abs/2306.05093) accepted at PoPETS 2024! Joint work with Daniel Jones, Yves-Alexandre de Montjoye, and Shruti Tople.

22/01/2024: I attended the discussion panel of the [Synthetic Data for Biomedical Applications](https://www.datascience.ch/event/synthetic-data-for-biomedical-applications) workshop organised by CHUV and the Swiss Data Science Center.

More news [here](https://ana-mariacretu.github.io/news-archive/).

# Publications {#publications}
## Peer-reviewed articles
<small>\* denotes joint first authorship.</small>
<ol reversed>

  <li>
   <b>Crețu A.-M.*</b>, Guépin F.* and de Montjoye Y.-A. Correlation inference attacks against machine learning models. <i> To appear in Science Advances </i> <a href="https://arxiv.org/abs/2112.08806">[arXiv]</a> <a href="https://github.com/computationalprivacy/ml-correlation-inference">[Code]</a>
  </li>
   
   <li>
   <b>Cretu A.-M.*</b>, Rusu, M.*, and de Montjoye Y.-A. Re-pseudonymization Strategies for Smart Meter Data Are Not Robust to Deep Learning Profiling Attacks. <i> To appear in the Proceedings of the Fourteenth ACM Conference on Data and Application Security and Privacy (CODASPY '24). </i> <a href="https://arxiv.org/abs/2404.03948">[Paper]</a> 
  </li>
   
   <li>
   <b>Cretu A.-M.</b>, Jones, D., de Montjoye Y.-A., and Tople, S. Investigating the Effect of Misalignment on Membership Privacy in the White-box Setting. <i> To appear in the Proceedings on Privacy Enhancing Technologies 2024(3) (PoPETS 2024). </i> <a href="https://arxiv.org/pdf/2306.05093.pdf">[Paper]</a> <a href="https://github.com/microsoft/shadow-realignment-mia">[Code]</a>
  </li>
 
   <li>
   Guépin, F.*, Meeus, M.*, <b>Crețu A.-M.</b>, and de Montjoye Y.-A. Synthetic is all you need: removing the auxiliary data assumption for membership inference attacks against synthetic data. In <i> 18th DPM International Workshop on Data Privacy Management (DPM 2023).</i> <a href="https://link.springer.com/chapter/10.1007/978-3-031-54204-6_10">[Paper]</a> <a href="https://github.com/computationalprivacy/MIA-synthetic">[Code]</a>
  </li>

   <li>
   Meeus, M.*, Guépin, F.*, <b>Crețu A.-M.</b>, and de Montjoye Y.-A. Achilles' Heels: Vulnerable Record Identification in Synthetic Data Publishing. In <i>28th European Symposium on Research in Computer Security (ESORICS 2023).</i> <a href="https://link.springer.com/chapter/10.1007/978-3-031-51476-0_19">[Paper]</a> <a href="https://github.com/computationalprivacy/MIA-synthetic">[Code]</a>
  </li>
  
  <li>
   Jain S., <b>Crețu A.-M.</b>, Cully, A. and de Montjoye Y.-A. Deep perceptual hashing algorithms with hidden dual-purpose: when client-side scanning does facial recognition. In <i>2023 IEEE Symposium on Security and Privacy (SP).</i> <a href="https://www.computer.org/csdl/proceedings-article/sp/2023/933600a234/1NrbXDL6b2U"> [Paper] </a>
   <ul>
       <li> Featured in 
        <a href="https://www.imperial.ac.uk/news/244952/tech-mandated-online-safety-bill-could/"> Imperial News</a>
        and 
        <a href="https://www.lesoir.be/517145/article/2023-06-02/comment-leurope-entend-scanner-nos-conversations-privees-sur-whatsapp-ou-signal">Le soir</a>. </li>
       <li> Cited as evidence in the <a href="https://haddadi.github.io/UKOSBOpenletter.pdf">Open Letter from Security and Privacy Researchers in relation to the Online Safety Bill</a>.
       </li>
   </ul>
  </li>
 
   <li>
   <b>Crețu A.-M.*</b>, Houssiau, F.*, Cully, A. and de Montjoye Y.-A. QuerySnout: Automating the discovery of attribute inference
attacks against query-based systems. <i>In Proceedings of the 2022 ACM SIGSAC Conference on Computer and Communications Security (CCS '22).</i> <a href="https://dl.acm.org/doi/10.1145/3548606.3560581"> [Paper] </a> <a href="https://arxiv.org/abs/2211.05249">[Extended arXiv version]</a> <a href="https://github.com/computationalprivacy/querysnout">[Code]</a>
  </li>
  
  <li>
   <b>Crețu A.-M.</b>, Monti F., Marrone S., Dong X., Bronstein M. and de Montjoye Y.-A. Interaction data are identifiable even across long periods of time. <i> Nature Communications 13, 313 (2022).</i> <a href="https://doi.org/10.1038/s41467-021-27714-6">[Paper]</a>
    <ul>
      <li> Presented at the ACM CCS Privacy Preserving Machine Learning 2021 workshop  (<a href="https://ppml-workshop.github.io/">PPML 2021</a>). <b><font color="red">Contributed talk.</font></b> </li>
      <li> Presented at the NeurIPS Privacy and Machine Learning 2021 workshop (<a href="https://nips.cc/Conferences/2021/ScheduleMultitrack?event=21873">PriML 2021</a>).</li>
      <li> Featured in <a href="https://techcrunch.com/2022/02/24/implement-differential-privacy-to-power-up-data-sharing-and-cooperation/">TechCrunch</a> and <a href="https://www.sciencenews.org/article/ai-identify-anonymous-data-phone-neural-network">Science News.</a>
      </li>
    </ul>
  </li>
  
  <li>
    Jain S.*, <b>Crețu A.-M.*</b> and de Montjoye Y.-A. Adversarial Detection Avoidance Attacks: Evaluating the robustness of perceptual hashing-based client-side scanning. <i> 31st USENIX Security Symposium (USENIX Security 22) </i> <a href="https://www.usenix.org/conference/usenixsecurity22/presentation/jain">[Paper]</a> <a href="https://arxiv.org/abs/2106.09820">[Extended arXiv version]</a>
    <ul>
      <li> Cited by Ofcom (UK's communications regulator) in their <a href="https://www.ofcom.org.uk/research-and-data/online-research/overview-of-perceptual-hashing-technology"> Overview of Perceptual Hashing Technology </a> report.</li>
      <li> Presented at the NeurIPS Privacy and Machine Learning 2021 workshop (<a href="https://nips.cc/Conferences/2021/ScheduleMultitrack?event=21873">PriML 2021</a>).</li>
      <li> Presented at the Conference on Applied Machine Learning for Information Security 2021 (<a href="https://www.camlis.org/">CAMLIS 2021</a>). <b><font color="red">Oral presentation.</font></b></li>
      <li> Presented as a talk at the 14th Workshop on Hot Topics in Privacy Enhancing Technologies (<a href="https://petsymposium.org/2021/hotpets.php">HotPETS 2021</a>).</li>
      <li> Featured in <a href="https://www.imperial.ac.uk/news/231778/proposed-illegal-image-detectors-devices-easily/">Imperial College London News</a> and <a href="https://www.lesoir.be/517145/article/2023-06-02/comment-leurope-entend-scanner-nos-conversations-privees-sur-whatsapp-ou-signal">Le soir</a>.</li>
    </ul>
  </li>
  
  <li> 
    Kocijan V., Camburu O.-M., <b>Crețu A.-M.</b>, Yordanov Y., Blunsom P. and Lukasiewicz T. WikiCREM: A Large Unsupervised Corpus for Coreference Resolution. <i>Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP) (2019)</i> <a href="https://aclanthology.org/D19-1439/">[Paper]</a> 
  </li>
  
  <li> 
    Kocijan V., <b>Crețu A.-M.</b>, Camburu O.-M., Yordanov Y. and Lukasiewicz T. A Surprisingly Robust Trick for the Winograd Schema Challenge. <i>Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics (ACL 2019)</i> <a href="https://aclanthology.org/P19-1478/">[Paper]</a>
  </li>
</ol>

## Preprints

<ol reversed>
  
 </ol>

# Awards and scholarships {#awards}

<ul>
  <li> I am recipient of the USENIX '22 Diversity grant, which generously supported my trip to the conference in Boston. </li>
  <li> I am a recipient of the <a href="https://www.epfl.ch/education/studies/en/financing-study/grants/excellence-fellowships/">EPFL Excellence Fellowship</a> (awarded to students with outstanding academic records), which generously supported my studies at EPFL.</li>
  <li> My studies in France were supported by a competitive 2-year full scholarship from the <i>Fondation Odon Vallet</i> and by a 2.5-year scholarship from the <i> Fondation de l'Ecole Polytechnique</i>.</li>
  <li> I was born and grew up in Romania. There, I participated in many mathematics contests, including the Romanian National Olympiad, where I won one gold medal, three silver medals, and one bronze medal.</li>
</ul>
