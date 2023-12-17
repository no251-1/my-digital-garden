---
{"dg-publish":true,"permalink":"/microelectronics-failure-analysis-desk-reference-7th-edition/section-5-fib-technique-and-circuit-edit/fib/"}
---


原文标题：FIB Overview

Chris Park, Amir Avishai, David Pan, Brett Lewis, Alex Buxbaum 
Carl Zeiss SMT PCS, Pleasanton, CA

# I. Introduction

# II. FIB Technology Updates

## A. Commercially Available FIB Sources

### Liquid Metal Ion Source (LMIS) FIB

The liquid metal ion source has been widely utilized since the 1980s for mask repair, microelectronics failure analysis, and circuit edit [^1]. The gallium focused ion beam (FIB) is the most commonly equipped LMIS in commercial microscopes. The tunability of the beam energy, spot size, and beam current makes it well-suited for a broad range of tasks from large volume excavation to site-specific nanoscale fabrication. FIB sources of other species are also available. Ion species of different masses extends the range of milling rates, spot size, interaction volume, and signal yield achievable by FIB instruments. For comparison, Figure 1 shows simulated models of beam interactions and sputter yield values on silicon for a variety of ion species.

![Pasted image 20230222205015.png|500](/img/user/Microelectronics%20Failure%20Analysis%20Desk%20Reference(7th%20Edition)/Section%205%20FIB%20Technique%20and%20Circuit%20Edit/attachments/Pasted%20image%2020230222205015.png)
Figure 1: Modeled sputter yield (ƴ) and implant depth of Cs+, Xe+, Ga+, Ar+, Ne+, and He+ with a beam energy of 30keV in silicon. For each ion, 30 trajectories are shown in red, while the resulting silicon atom recoils are shown in green. The xaxis radial spread shown for each individual plot is 100nm. All collision data and sputter yield were calculated using TRIM.

### Plasma FIB

氙(Xe)是一种重元素，它在商用等离子体聚焦离子束(PFIB)仪器中广泛使用，可以快速去除材料，比传统的Ga离子源FIB快20倍。Xe PFIB技术在微电子失效分析中有重要应用，可以制备封装和后段(BEOL)组件的截面。目前最常见的Xe PFIB源[^2][^3]有感应耦合等离子体(ICP)和电子回旋共振(ECR)，它们都利用电磁场将气体电离成等离子体，并从中提取离子束。表1列出了ICP Xe PFIB源的主要参数。 

[^1]: Soden, Jerry M. and Anderson, Richard E. Microelectron. Reliab., Vol. 35, No. 3 (1995): 429-453. 
[^2]: Smith, Noel S., John A. Notte, and Adam V. Steele. “Advances in Source Technology for Focused Ion Beam Instruments.” MRS Bulletin 39, no. 4 (2014): 329–335. 
[^3]: Smith, N. S., W. P. Skoczylas, S. M. Kellogg, D. E. Kinion, P. P. Tesch, O. Sutherland, Ane Aanesland, and R. W. Boswell. “High Brightness Inductively Coupled Plasma Source for High Current Focused Ion Beam Applications.” Journal of Vacuum Science & Technology B: Microelectronics and Nanometer Structures Processing, Measurement, and Phenomena 24, no. 6 (2006): 2902– 2906. 
### Gas Field Ion Source (GFIS) FIB

## B. Complementary Technology

### FIB-SEM

### GIS

### In situ manipulator

### Electron Flood Gun

## C. Secondary Ion Mass Spectroscopy (SIMS)

### SIMS Applications in Failure Analysis

### Future Challenges for SIMS

## D. Patterning Engine

# III. FIB Applications

## A. FIB Circuit Edit

### Sample preparation for FIB Circuit Edit

### Future challenges for FIB Circuit Edit

## B. FIB Sample Preparation

### Cross-Sectioning

### Sample Preparation for Surface Analysis

### TEM Lamella Sample Preparation

### Low KV FIB applications for amorphous layer removal

### Curtaining Mitigation Schemes

### Backside Milling

### Atom Probe Tomography Sample Preparation

### Future Challenges for FIB Sample Preparation

## C. 3D Tomography

### Future Challenges for 3D Tomography

# IV. Automation

### Sample Preparation Automation

### 3D Tomography Automation

### Future Challenges in 3D Analytics

# V. Summary


# VI. Acknowledgments

# VII. References

[4] Hlawacek, Gregor, and Armin Gölzhäuser, eds. Helium Ion Microscopy. Switzerland: Springer International Publishing, 2016.
[5] Notte, John, Bill Ward, Nick Economou, Ray Hill, Randy Percival, Lou Farkas, and Shawn McVey. “An Introduction to the Helium Ion Microscope.” In AIP Conference Proceedings, 931:489–496. AIP, 2007. 
[6] Stanford, Michael G., Brett B. Lewis, Kyle Mahady, Jason D. Fowlkes, and Philip D. Rack. “Advanced Nanoscale Patterning and Material Synthesis with Gas Field Helium and Neon Ion Beams.” Journal of Vacuum Science & Technology B, Nanotechnology and Microelectronics: Materials, Processing, Measurement, and Phenomena 35, no. 3 (2017): 030802. 
[7] Tan, Shida, Richard Livengood, Darryl Shima, John Notte, and Shawn McVey. “Gas Field Ion Source and Liquid Metal Ion Source Charged Particle Material Interaction Study for Semiconductor Nanomachining Applications.” Journal of Vacuum Science & Technology B, Nanotechnology and Microelectronics: Materials, Processing, Measurement, and Phenomena 28, no. 6 (2010): C6F15–C6F21. 
[8] Shorubalko, Ivan, Lex Pillatsch, and Ivo Utke. “Direct– Write Milling and Deposition with Noble Gases.” In Helium Ion Microscopy, 355–393. Springer, 2016. 
[9] Castaldo, Vincenzo, Josephus Withagen, Cornelius Hagen, Pieter Kruit, and Emile van Veldhoven. “Angular Dependence of the Ion-Induced Secondary Electron Emission for He+ and Ga+ Beams.” Microscopy and Microanalysis 17, no. 4 (2011): 624–636. 
[10] Burnett, T. L., R. Kelley, B. Winiarski, L. Contreras, M. Daly, A. Gholinia, M. G. Burke, and P. J. Withers. “Large Volume Serial Section Tomography by Xe Plasma FIB Dual Beam Microscopy.” Ultramicroscopy 161 (2016): 119–129. 
[11] Iberi, Vighter, Liangbo Liang, Anton V. Ievlev, Michael G. Stanford, Ming-Wei Lin, Xufan Li, Masoud Mahjouri-Samani, et al. “Nanoforging Single Layer MoSe2 Through Defect Engineering with Focused Helium Ion Beams.” Scientific Reports 6 (2016): 30481. 
[12] Cybart, Shane A., E. Y. Cho, T. J. Wong, Björn H. Wehlin, Meng K. Ma, Chuong Huynh, and R. C. Dynes. “Nano Josephson Superconducting Tunnel Junctions in YBa 2 Cu 3 O 7–δ Directly Patterned with a Focused Helium Ion Beam.” Nature Nanotechnology 10, no. 7 (2015): 598.
[13] Stanford, Michael G., Pushpa Raj Pudasaini, Alex Belianinov, Nicholas Cross, Joo Hyon Noh, Michael R. Koehler, David G. Mandrus, et al. “Focused Helium-Ion Beam Irradiation Effects on Electrical Transport Properties of Few-Layer WSe2: Enabling Nanoscale Direct Write Homo-Junctions.” Scientific Reports 6 (2016): 27276. 
[14] Nakaharai, Shu, Tomohiko Iijima, Shinichi Ogawa, Shingo Suzuki, Song-Lin Li, Kazuhito Tsukagoshi, Shintaro Sato, and Naoki Yokoyama. “Conduction Tuning of Graphene Based on Defect-Induced Localization.” ACS Nano 7, no. 7 (2013). 
[15] Scholder, Olivier, Konstantins Jefimovs, Ivan Shorubalko, Christian Hafner, Urs Sennhauser,
and Gian-Luca Bona. “Helium Focused Ion Beam Fabricated Plasmonic Antennas with Sub-5 Nm Gaps.” Nanotechnology 24, no. 39 (2013): 395301. 
[16] Marshall, Michael M., Jijin Yang, and Adam R. Hall. “Direct and Transmission Milling of Suspended Silicon Nitride Membranes with a Focused Helium Ion Beam.” Scanning 34, no. 2 (2012): 101–106. 
[17] Abbas, Ahmad N., Gang Liu, Bilu Liu, Luyao Zhang, He Liu, Douglas Ohlberg, Wei Wu, and Chongwu Zhou. “Patterning, Characterization, and Chemical Sensing Applications of Graphene Nanoribbon Arrays down to 5 Nm Using Helium Ion Beam Lithography.” ACS Nano 8, no. 2 (2014): 1538–1546. 
[18] Winston, D., B. Ming Cord, B. Ming, D. C. Bell, W. F. DiNatale, L. A. Stern, A. E. Vladar, M. T. Postek, M. K. Mondol, and J. K. W. Yang. “Scanning-Helium-Ion-Beam Lithography with Hydrogen Silsesquioxane Resist.” Journal of Vacuum Science & Technology B: Microelectronics and Nanometer Structures Processing, Measurement, and Phenomena 27, no. 6 (2009): 2702–2706. 
[19] Winston, Donald, Vitor R. Manfrinato, Samuel M. Nicaise, Lin Lee Cheong, Huigao Duan, David Ferranti, Jeff Marshman, Shawn McVey, Lewis Stern, and John Notte. “Neon Ion Beam Lithography (NIBL).” Nano Letters 11, no. 10 (2011): 4443–4347. 
[20] Giannuzzi, Lucille A. Introduction to Focused Ion Beams: Instrumentation, Theory, Springer Science & Business Media, 2004. 
[21] Cantoni, Marco, and Lorenz Holzer. “Advances in 3D Focused Ion Beam Tomography.” MRS Bulletin 39, no. 4 (2014): 354–360. 
[22] Bassim, Nabil, Keana Scott, and Lucille A. Giannuzzi. “Recent Advances in Focused Ion Beam Technology and Applications.” Mrs Bulletin 39, no. 4 (2014): 317–325. 
[23] Thomson, Joseph John. Rays of Positive Electricity and Their Application to Chemical Longmans, Green and Company, 1921.
Analyses. Vol. 1.
[24] Arnot, F. L., and J. C. Milligan. “A New Process of Negative Ion Formation.” Proceedings of the Royal Society of London. Series A-Mathematical and Physical Sciences 156, no. 889 (1936): 538–560.
[25] Herzog, R. F. K., and F. P. Viehböck. “Ion Source for Mass Spectrography.” Physical Review 76, no. 6 (1949): 855.
[26] Liebl, Helmut J., and Richard FK Herzog. “Sputtering Ion Source for Solids.” Journal of Applied Physics 34, no. 9 (1963): 2893–2896.
Techniques and Practice.
[27] Notte, John. “Focused Ion Beams for Imaging, Analysis, and Fabrication-Where Did They Come From and Where Are They Going?” Microscopy and Microanalysis 23, no. S1 (2017): 1004–1005. 
[28] Giannuzzi, Lucille A., and M. Utlaut. “A Review of Ga+ FIB/SIMS.” Surface and Interface Analysis 43, no. 1–2 (2011): 475–478. 
[29] Wirtz, T.; Dowsett, D.; Philipp, P., SIMS on the Helium Ion Microscope: a Powerful Tool for High-Resolution High-Sensitivity Nano-Analytics. In Helium Ion Microscopy, Springer: 2016); pp 297-323. 
[30] Klingner, N.; Heller, R.; Hlawacek, G.; von Borany, J.; Notte, J.; Huang, J.; Facsko, S., "Nanometer scale elemental analysis in the helium ion microscope using time of flight spectrometry," Ultramicroscopy 162, (2016), pp. 91-97. 
[31] Whitby, J. A.; Östlund, F.; Horvath, P.; Gabureac, M.; Riesterer, J. L.; Utke, I.; Hohl, M.; Sedláček, L.; Jiruše, J.; Friedli, V., "High spatial resolution time-of-flight secondary ion mass spectrometry for the masses: a novel orthogonal ToF SIMS instrument with in situ AFM," Advances in Materials Science and Engineering 2012, (2012) 
[32] Pillatsch, L.; Östlund, F.; Michler, J., "FIBSIMS: A review of secondary ion mass spectrometry for analytical dual beam focused ion beam instruments," Progress in Crystal Growth and Characterization of Materials, (2018) 
[33] Briggs, D.; Brown, A.; Vickerman, J. C., Handbook of static secondary ion mass spectrometry. Wiley Chichester etc: (1989). 
[34] Liebl, H., "Secondary−ion mass spectrometry and its use in depth profiling," Journal of Vacuum Science Technology 12 1, (1975), pp. 385-391. 
[35] Priebe, A.; Michler, J., "Application of a novel compact Cs evaporator prototype for enhancing negative ion yields during FIB-TOF-SIMS analysis in high vacuum," Ultramicroscopy 196, (2019), pp. 10-17. 
[36] Smith, N.; Tesch, P.; Martin, N.; Kinion, D., "A high brightness source for nano-probe secondary ion mass spectrometry," Applied surface science 255 4, (2008), pp. 1606-1609. 
[37] Ward, B.; Notte, J. A.; Economou, N., "Helium ion microscope: A new tool for nanoscale microscopy and metrology," JVSTB 24 6, (2006), pp. 2871-2874. 
[38] Livengood, R. H.; Tan, S.; Hallstein, R.; Notte, J.; McVey, S.; Faridur Rahman, F. H. M., "The neon gas field ion source—a first characterization of neon nanomachining properties," NIMPRSA 645 1, (2011), pp. 136-140. 
[39] Wagner, L. C., Failure analysis of integrated circuits: tools and techniques. Springer Science & Business Media: 1999); Vol. 494, pp 229-240. 
[40] Dowsett, M. G.; Barlow, R. D., "Characterization of sharp interfaces and delta doped layers in semiconductors using secondary ion mass spectrometry," Analytica Chimica Acta 297 1, (1994), pp. 253-275. 
[41] Boden, Stuart, and Xiaoqing Shi. “Scanning Helium Ion Beam Lithography.” In Materials and Processes for Next Generation Lithography, 11:563–94. Elsevier, 2016. 
[42] Scheffler, Christopher M., Richard H. Livengood, Haripriya E. Prakasam, Michael W. Phaneuf, and Ken Lagarec. “Patterning in an Imperfect World: Limitations of Focused Ion Beam Systems and Their Effects on Advanced Applications at the 14nm Process Node.” Proceedings from the 42nd International Symposium for Testing and Failure Analysis, 2016.
[43] F. Altmann, S. Klengel, J. Schischka, M. Petzold, in 2013 IEEE 63rd Electronic Components and Technology Conference (IEEE, 2013), pp. 1940–1945 
[44] Leer, B. Van, and L. A. Giannuzzi. “Advances in TEM Sample Preparation Using a Focused Ion Beam.” Microscopy and Microanalysis 14, no. S2 (August 2008): 380–81.
[45] Giannuzzi, LA, Stevie, FA, “A review of focused ion beam milling techniques for TEM specimen preparation,” Micron, vol. 30, no. 3, pp. 197–204, Jun. 1999. 
[46] Tomus, D., and H. P. Ng. “In Situ Lift-out Dedicated Techniques Using FIB-SEM System for TEM Specimen Preparation.” Micron (Oxford, England: 1993) 44 (January 2013): 115–19.
[47] Moore, Mary V., Steve Rozeveld, and Elvin Beach. “Using FIB for TEM Analysis of Semiconductor Materials. (Metrology).” Solid State Technology 45, no. 9 (2002): S18–S18.
[48] A. Denisyuk, T. Hrnčíř, J. V. Oboňa, M. Petrenec, Jan Michalička, Curtaining-Free Top-Down TEM Lamella Preparation from a Cutting Edge Integrated Circuit. Microsc. Microanal. 22, 196–197 (2016). 
[49] H.-J. Kang, J. Kim, J. Oh, T. Back, H. Kim, Ultra-thin TEM Sample Preparation with Advanced Backside FIB Milling Method. Microsc. Microanal. 16, 170–171 (2010). 
[50] S. Rubanov, P. R. Munroe, in Journal of Microscopy (2004).
[51] M. Schaffer, B. Schaffer, Q. Ramasse, Sample preparation for atomic-resolution STEM at low voltages by FIB. Ultramicroscopy. 114, 62–71 (2012). 
[52] W. van Mierlo et al., Practical aspects of the use of the X2 holder for HRTEM-quality TEM sample preparation by FIB. Ultramicroscopy. 147, 149–155 (2014). 
[53] J. Jiruse, M. Havelka, J. Polster, T. Hrncif, Xe Plasma FIB-SEM with Improved Resolution of Both Ion and Electron Columns. Microsc. Microanal. 21, 1995–1996 (2015).
[54] M. Simon-Najasek, S. Huebner, F. Altmann, A. Graff, Advanced FIB sample preparation techniques for high resolution TEM investigations of HEMT structures. Microelectron. Reliab. 54, 1785–1789 (2014). 
[55] T. J. Prosa, D. J. Larson, Modern Focused-Ion-Beam-Based Site-Specific Specimen Preparation for Atom Probe Tomography. Microsc. Microanal. 23, 194–209 (2017). 
[56] T. Vermeij, E. Plancher, C. C. Tasan, Preventing damage and redeposition during focused ion beam milling: The “umbrella” method. Ultramicroscopy. 186, 35–41 (2018). 
[57] Kelley, R. D., Kai Song, Brandon Van Leer, David Wall, and Laurens Kwakman. “Xe+ FIB milling and measurement of amorphous silicon damage.” Microscopy and Microanalysis 19, no. S2 (2013): 862-863. 
[58] Peddie, Christopher J., and Lucy M. Collinson. “Exploring the Third Dimension: Volume Electron Microscopy Comes of Age.” Micron 61 (2014): 9–19.
[59] Mustafi, Debarshi, Amir Avishai, Nanthawan Avishai, Andreas Engel, Arthur Heuer, and Krzysztof Palczewski. “Serial Sectioning for Examination of Photoreceptor Cell Architecture by Focused Ion Beam Technology.” Journal of Neuroscience Methods 198, no. 1 (2011): 70–76.
[60] Kidd, Grahame J., Amir Avishai, Xinghua Yin, and Bruce D. Trapp. “Three-Dimensional Analysis of Optic Nerve Axons Using a Focused Ion Beam-Based Approach.” Microscopy Today 18, no. 1 (2010): 18–22.
[61] Holzer, Lorenz, and Marco Cantoni. “Review of FIB-Tomography.” Nanofabrication Using Focused Ion and Electron Beams: Principles and Applications 559201222 (2012): 410–435.
[62] Hrnčíř, T., F. Lopour, M. Zadražil, A. Delobbe, O. Salord, and P. Sudraud. "Novel plasma FIB/SEM for high speed failure analysis and real time imaging of large volume removal." In ISTFA: conference proceedings from the 38th international symposium for testing and failure analysis, p. 26, 2012.
[63] Kotula, Paul G., Gregory S. Rohrer, and Michael P. Marsh. "Focused ion beam and scanning electron microscopy for 3D materials characterization." MRS Bulletin 39, no. 4 (2014): 361-365.
[64] Zhu, Jie, Soo Sien Seah, Irene Tee, Bing Hai Liu, Eddie Er, Si Ping Zhao, Jeffrey Lam, Mark Najarian, and Valerie Brogden. “Application of Automated FIB for TEM Sample Preparation in Semiconductor Failure Analysis,” 40th International Symposium for Testing and Failure Analysis American Society for Metals, 2014.
[65] Schulmeyer, Ingo, et al., Fraunhofer IMWS CAM-Workshop Apr. 25, 2018, Halle, Germany.
