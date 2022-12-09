+++
title= "Generative Garment Design for Circularity: Parametric Patterns and Transformative Algorithms for Enabling Circular Fashion Design"
date= 2021-03-15
draft= false
series= ["fashion"]
+++

Presented at the [23rd Annual Sustainable Innovation Conference: Accelerating Sustainability in Fashion](https://cfsd.org.uk/events/sustainable-innovation-2021/programme/).


# abstract 
Generative garment design for circularity (GGD4C) proposes utilizing generative algorithms to include lifecycle, material use, and circularity data at the garment design phase, shifting towards a more environmentally conscious fashion industry and radically increasing the adoption of circular design. Computational tools and data used in the fashion industry are discussed with traditional and generative workflows. A generative garment design workflow was developed and tested in an early experiment trial of a jumpsuit design and parametric patterns using Grasshopper’s evolutionary solver Galapagos in Rhinoceros 3d software. 

# Premise: Generative Garment Design for Circularity Impact

The fashion industry exhibits growing traits of a wicked problem1 with a carbon footprint representing 5-10% of global greenhouse gas2(GHG) emissions annually (Quantis 2020). Generative garment design for circularity (GGD4C) proposes utilizing generative algorithms to include lifecycle, material use, and circularity data at the garment design phase, shifting towards a more environmentally conscious fashion industry and radically increasing the adoption of circular design. While advanced garment tools3(AGTs) and data analytics have become a driving force in the modern fashion industry, they often omit a sincere environmental design analysis. Most attempts in the industry to reduce waste occur at the marker making4 stage, and not at the design stage where the majority of waste is determined (McQuillan 2020). 
The design determines the garment lifecycle and thus determines the potential environmental impact from producing the garment. The goal of an apparel designer is to create aesthetically pleasing garments according to Davis (in Jung & Jirousek 2015) while functional clothing focuses on what clothing does before considering how it looks (Watkin & Dunne 2015) and applies evaluation to on body and in environment performance objectives. Whether fashion apparel or functional apparel, the design process implies multiple design choices of textile, silhouette, color, waste, etc. Garment user care contributes to over 60% of the indicators for human toxicity, freshwater and marine ecotoxicity, metal depletion, ionizing radiation, and water depletion (Beton et al. 2014). A single pair of used jeans can release 56000 ± 4100 microfibers per wash (Athey et al. 2020) with an average garment lifespan of 5 to 10 years. The GGD4C workflow proposes different ways of integrating design analytics into fashion design for optimizing multiple objectives simultaneously, for example, circularity. Quantitative knowledge of a garment during the design phase could help promote the transition to circular design 

# Computational Tools and Data in Fashion Design 

Advanced computational tools within fashion 4.0 (Bertola & Teunissen 2018) span from artificial intelligence (AI) and machine learning (ML) strategies (such as generative adversarial networks (GANs)) for exploratory design, predicting consumer behavior, fit, and recommendation systems. Gamification through virtual reality (VR) and augmented reality (AR) are utilized for extracting data, tracking,prediction, altering consumer behaviour, and hyper-personalized marketing. Digital twining of fashion accessories, shoes, and garments allow for the creation of intricate 3D computer aided design (CAD) renderings with textile simulations for marketing, design to production, or the immediate virtual consumption of the item allowing it to be ‘digitally worn’ via AR. The use of computational tools in fashion is increasing rapidly while addressing environmental concerns and circularity have not been adequately addressed, as even virtual fashion worn in AR creates a carbon footprint. Experimental GANs for fashion design are computationally expensive, currently estimated to need a month of training on the current state-of-the art GAN algorithm to create an image detail similar to a fashion designer's sketch (Kato et al. 2019). Product service systems for fashion include servicizing6the garment, adding new digital carbon footprints and physical electronic waste to each garment from radio frequency identification (RFID) tags meant to promote sustainable traceability when studies repeatedly report issues of recyclability, privacy concerns, and use case problems for real implementation of RFID (Schindler et al. 2012). 3D CAD tools have been utilized in sustainable fashion design for 3D printed garments using recycled filaments and zero waste design methodologies (BCN3D 2020 & McQuillan 2020). Fashion’s wicked problem is created by the entire lifecycle of the garment, with many state of the art technologies not addressing the varied types of environmental footprints left by each garment. Fashion design needs tools that allow for the inclusion of circular design analytics and enable the designer to address the multiple objectives of the wicked problem at the garment design stage. 

# Data informed Fashion Design 

The data driven 
design7 revolution continues to flourish. Focused on various aspects, such as performance, customization, marketing, and manufacturing, data driven design has become a driving force in modern fashion design. Design analytics inform advanced computational tools whether they include demand-side data from consumers, or supply-side data from production and operating systems (Cantamessa, M. et al, 2020). Design analytics, in particular, is the process of inspecting, cleaning, transforming, and modelling data to extract knowledge which could be valuable to generate and evaluate new design solutions (King et al. 2013). Functional clothing focuses on what clothing does before considering how it looks (Watkins & Dunne 2015) and applies design analytics to evaluate on body and in environment performance objectives. Athletes are ensured customized fit for both body and performance goals of the specific sport, while astronauts are ensured movement goals for antigravity of their protective spacesuit. On the ground, sportswear companies like Nike and Adidas have been integrating customization analytics and generative design into their footwear and apparel for both professional and non professional athletes (Follet 2018). Adidas recently commissioned research for sports bra design in which, in order to create a data set of parametrically defined bra designs to test and evaluate, a generative design method was implemented as a prototype tool in Robert McNeel and Associates Grasshopper 3D plugin for Rhinoceros 3d (Bosquet et al. 2020). The use of design analytics has spread beyond professionals in test cases such as the limited edition garments like NIKE’s 2017 Advanced Apparel Exploration 1.0 tshirt. The tshirt began with Nike’s archive of digital data, which tracks the trajectory of the chest, back, and arms in forward motion in an inclusive algorithm to produce a single-layer, seamless knit tee shirt that delivered ventilation where needed and coverage where desired (Nike 2017). The data analytics and methods used for functional garment design can be a useful reference for how to use circular design analytics to inform fashion 

# Generative Garment Design for Circularity Methodology 

Generative garment design for circularity (GGD4C) proposes using genetic algorithms and a workflow for the inclusion of circular design analytics, enabling multi-objective optimization9(MOO) for climate positive fashion designs. To empower designers, computer algorithms are being developed to generate desired designs under given design objectives and constraints. These algorithm-driven design processes are now known as generative design (Wu et al, 2019). John Holland introduced the genetic algorithm in the 1970’s, or evolving computer programs, resembling the biology of natural selection and the ability of certain traits or genes to evolve through generations of organisms naturally (Holland 1992). For circular fashion, multiple design objectives or ‘genes’ should be considered for climate impact such as textile waste amount, estimated microfiber and effluent release. More subjective ‘genes’ such as modesty, aesthetic, and sales appeal can also be considered. The goal of the optimized fashion design is defined by the ‘fitness function’ of the algorithm centered around a single or multiple objective optimization. Circular design analytics for GGD4C can be applied as parameters in designing the fitness function of the algorithm towards minimizing the negative environmental output of the design. A single metric of surface area can allow for the evaluation of circular design methodologies such as dematerialization10 and/or zero-waste fashion design11. The design’s parametric garment pattern allows for variable values to be set for design attributes such as silhouette, appliques, hem lengths, as well as sizing. The process visualizes various design modifications to the garment or block/sloper12 which depend on several geometric rules such as dynamic seam lines altering silhouette, textile variables, fit, or construction rules. The possibly infinite number of generative garment design outputs leads to the opportunity to select solutions which align with the garment life cycle and climate impact goals. Sorting these options via parallel coordinates allows the designer to visualize the influence of each parameter on the design as well as choose multiple metrics to further circularity. This would allow for the discussion of fashion design versus environmental impact in real time, the designer able to actively choose what is the more vital need for the garment. Being able to evaluate and play with the design options within the parallel coordinates interface allows for a selection of optimized designs, referred to as Pareto optimal solutions (Gerber et al 2012), which would then benefit from further evaluation for reviewing subjective design features such as aesthetics, modesty, and design appeal. While the human designer plays a critical role to the generative garment design process the integration with circular design analytics and computational analysis systems aid in addressing multiple aspects of fashion’s wicked problem within the design stage. 

>>image workflows 

# Workflow Development for Generative Garment Design for Circularity 

Fashion and garment design workflows vary greatly, some starting the design process with a “kernel” idea (Omwami 2020) and some an image database (Kato et al. 2018). Many researchers have discussed the workflow process of fashion and garment design, few have discussed the transition to using computational tools for circular design. Fig 1, shows a selection of relevant design and fashion design workflows: functional clothing, GANs, 3D CAD, and generative processes. Fig. 1a shows the traditional fashion design process of conceptual idea, sketch, pattern, toile, and sample developed by Timo Rissanen in 2007 (in McQuillan 2020). Fig.1b shows the traditional design process used in functional apparel design in 1981 from Koberg & Bagnall, (in Watkins & Dunne 2015). Fig. 1c shows two versions of the transition from Rissanen’s 2D workflow to a 3D CAD workflow for the zero-waste fashion method featuring the hybridization of the multiple iterative steps of 2D sketching, 3D draping, 2D pattern cutting, and 3D toileting, into a single 2D/3D design process (McMillian 2020). Fig. 1d shows the 3D fashion design process for Puma SE (Nina, V.T.K.N. 2019) Fig.1e is the design workflow for GANs fashion design discussing machine versus human roles. Fig. 1f is a basic
generative workflow (Tang & Cui 2017). Fig. 1g is the workflow for the creation of sports bras using generative design (Bosquet et al. 2020). Fig. 1h shows the The concept generator from Knapp 1988 (in Watkins & Dunne 2015) for an integrated protective clothing and equipment ensemble for the Canadian soldier which was projected for the year 2005. Knapp’s Concept Generator can be seen as the beginning in generative garment design comparable to Cedric Price’s Generator (Sopeoglou 2019) seen as one of the beginnings of generative design in architecture. 
Figure 2 shows the proposed workflows for use of advanced garment tools including generative garment design tools with circularity goals. The four proposed workflows are similar in nature with the initial stages differing depending on the start point of the design process. If the process includes a 2D/3D design or a 3D virtual draping process, then the design is mathematically translated into a parametric fashion pattern or derived from a parametric pattern block/sloper. Parametric patterns and parametric pattern block/slopers are a draft of a pattern's curves represented by functions and variables. Circularity goals are then applied through circular design analytics used to create transformative algorithms. The workflow progresses to an evaluation of the optimization and towards either the selection from the algorithm (natural selection) or selection by the designer (artificial selection). If the optimized design is satisfactory, the process moves on to virtual fitting and tech pack13 creation, and finally to sample. In considering the previous workflows from fig. 1 it was important to keep an iterative process allowing for the continuous refinement of a design, as designers don’t follow a linear process, that design is necessarily messy and iterative (Davis 2020). The inclusion of the discussion of machines, humans, and designers was also important as advanced garment tools continue to be integrated in workflows. Many 3D workflows include the body scan processing as a design step, however automated processing of a body scan will become available for regular use and therefore unnecessary as part of future design workflow. 

<<fig. 3a complete parametric pattern of the jumpsuit >>

# Early Experimentation of Generative Garment Design for Circularity 

Early experiments of GGD4C (fig. 3) begin with the kernel of a sustainable silhouette that can meet broad global cultural needs for modesty and be gender agnostic. The silhouette of a jumpsuit was decided upon and appropriate parametric pattern blocks were selected from GenCloth’s pattern database (GenCloth 2020). The pattern blocks were then drafted using the Grasshopper 3d tool transforming into the jumpsuit pattern. Parametric sizing was set to the body scan measurements and the neckline, sleeve, and pant hem lengths were then parameterized. Collar and center front facings were added to the parameters, and pocket patterns for realistic usability and further consideration of a complete design generation (fig. 3a). Within Grasshopper 3d, the Galapagos evolutionary solver program ran a simple algorithm to test combined surface area of the design and minimize the textile use. The generative process created 62 epochs with 50 generations in each, producing 3,100 design variations (fig. 3b). Sorting the jumpsuit data provided a visual of the best and worst outcomes in each epoch (fig. 3c). Future work for GGD4C includes defining specific circular design goals for multi-objective design impact, including manufacturing stages and use care stages. The development of GGD4C tools should focus on the straightforward introduction of new scientific impact data to continue filtering out the negative impacts from the fashion design stage and test use case scenarios. 

<<fig. 3b The 3,100 design variations from 62 epochs with 50 generations in each. >>


# Discussion, Interpretations, and Challenges 

Generative design workflows are currently used in several related industries such as in engineering for optimization and simulation, industrial and product design, and with limited success in architectural applications. Applying data and new technologies remains a slow process within fashion. The setup of circular data and cohesive environmental goals for GGD4C is critical. There is an argument of what to
measure using generative design, with the possibility of using arbitrary metrics and ending up optimizing for the wrong thing...or ignoring the metrics and wading through a lot of unfiltered options (Davis 2020). Environmental regulations organizations that label and certify products as sustainable (European Commission 2020) could aid in narrowing the design analytics needed for GGD4C. These certifications typically happen after the design stage. Applying circular design analytics within the industry could prove difficult as, comparatively, the apparel industry lags behind in embracing analytics, often favoring merchant-and designer-driven “gut-feel” over insight driven decision making (Fox et al. 2018). It will be of importance for designers to understand how the multi-objective design analytics interact with each other and how to balance with subjective evaluations that may go against environmental impact goals. 


<<Fig.3c Array of generated jumpsuit patterns. 

GGD4C involves tools and methods from many fields of study, making co-design and collaboration a necessary central theme for the success of the workflow and also possibly problematic for quick implementation. There are future opportunities in the workflow for upskilling some of the 70.8% of the 300 million garment workforce that are women (Euratex 2019, Global Fashion Agenda 2018). Doing so can achieve a “multiplier effect, and helps drive up economic growth and development across the board,”(UNDP 2016). AGT training for women could capacitate them to use new communication and information technologies, enabling women to become primary stakeholders within the garment industry (Bigger 2019).
While conscientious consumption continues to trend in fashion, the decrease of ill informed designs is needed. The use of GGD4C could help transition towards slow fashion14. A circular design method was recently found to have rebounded in regards to the dematerization and servicizing of music streaming, finding the music industry now has a larger GHG emissions footprint due to digital infrastructure needs of streaming versus physical vinyl, cassettes and compact discs eras (Brennan, M., Devine, K. 2019.). Circular design methods such as dematerialization could be used as a marker for silhouette range, but is not realistic in balancing the materiality needs of a garment. A complete view of data analytics included in the GGD4C impact of the environmental goals and circular design methodologies used is critical inorder to prevent the rebound effect. A pathway could be created for customizing the data to include the environmental goals of both the locality of manufacturing and consumer use case, focusing on cleaning up many areas of the manufacturing supply chain. It could become cumbersome to evaluate multi-objectives at the design stage, but it may be worth it to create faster impact decreasing fashion’s wicked problem. 

# Conclusion 

Generative garment design for circularity is a multi-objective optimization process that can aid in design driven climate impact. Utilizing circular data to aid in the design process is an opportunity for knowledge growth in fashion design that allows for multiple planetary goals to be considered within the design phase concurrently. Advanced garment tools, technologies and data used in fashion have been discussed and the GGD4C methodology and workflows have been presented and early experiments tested and discussed. 


# Notes

1. A wicked problem has complex interdependencies, with various stakeholders attempting to solve pieces of the problem from different angles, creating and exposing further problems. 
.2 Referencing Fashion’s greenhouse gas emission is recommended to be done so using ranges as the exact amount of the problem is unknown (Quantis 2020). 
3. Advanced garment tools (AGTs) process; textile simulation, 3D body scans, 3D to 2D garment creation and marker making, nesting, user garment and design data, manufacturing transparency data and are typically used with computer aided design (Bigger 2019). 
4. Marker making is the process of determining efficient layout of pattern pieces for a style, fabric and distribution of sizes and circular collaborative customization5 business models in industry 4.0. 
5. Circular collaborative customization business model combines user-centric design, advanced garment technologies and circularity within a microfactory typology (Bigger 2019). 
6. Servicizing is a transaction through which value is provided by a combination of products and services in which the satisfaction of customer needs is achieved either by selling the function of the product rather than the product itself, or by increasing the service component of a product offer. 
7. Design driven data is design that is informed by data.
design. Parameters for generative garment design can vary from simple single metrics, such as surface area, to multiple parameters with the inclusion of use case data such as expected wash amount, dye and chemical effluent release rate, microfiber release rate, and lifetime expectancy. 
Additional design parameters can be defined from customization in fit, clothing insulation values (CLO or Togs8), durability of the textile as well as seam efficiency values from both traditional stitching and sealing methods. Clear environmental impact goals in accordance with the appropriate regulatory standards can be defined at the design stage, allowing the designer to understand the full impact of a design while continuously improving the design’s circularity. 
8. CLO or Togs are the unit of measurements for clothing insulation 
9. Multi-objective optimization uses mathematics to involve more than one objective function to be optimized simultaneously 
10. Dematerialization of a product is a circular design method to subtract material from the product, or to offer the same product using no material at all such as music compact discs transformed to music streaming. 
11. Zero-waste fashion is a sustainable design method where the pattern pieces of the design fit together so that no fabric is wasted during the cutting phase. 
12. Pattern block/sloper is a simple master pattern used to make more detailed patterns.
13. A tech pack is a blueprint for a garment created by a technical designer, containing everything needed to turn the design into a finished product including materials, gradings, seams, colorways, measurements, trim, labels, etc.


# References 

Amoozegar-Montero, A.X., & Rodriguez Ramirez, E., 2017, “Parametric modelling for better bra fit and design.”, Western Decision Sciences Institute Conference, Vancouver, Canada. 

Anaraki, N. A. T. (ed) 2017, Fashion Design Aid System with Application of Interactive Genetic Algorithms, Texas Tech University. 

Athey, S., Adams, J., Erdle, L., Jantunen, L., Helm, P., Finkelstein, S., & Diamond, M., 2020, “The Widespread Environmental Footprint of Indigo Denim Microfibers from Blue Jeans.”, Environmental Science and Technology, vol 10.

Bertola, P. and Teunissen, J., 2018, "Fashion 4.0. Innovating fashion industry through digital transformation.", Research Journal of Textile and Apparel, vol. 22, no. 4, pp. 352-369. https://doi.org/10.1108/RJTA-03-2018-0023 

BCN3D, 2020, 9 January 2021-last update, The future of fashion can be worn today: ZER Collection unites style and sustainability through 3D printing [Online]. Available: 
https://www.bcn3d.com/sustainability-in-fashion-through-3d-printing/ [January 2020]. 

Beton, A., Dias, D., Farrant, L., Gibon, T., Guern, Y.L., Desaxce, M., Perwueltz, A., Boufateh, I. 2014, Environmental Improvement Potential of Textiles (Impro-Textiles), JRC Scientific and Policy Reports, Publications Office of the European Union. [Online]. Available: 
http://ipts.jrc.ec.europa.eu/publications/pub.cfm?id=6960 [November 2018]. 

Bigger, E, 2019, “Circular Collaborative Customization within Microfactories: a viable business model for Fashion 2030.”, The 22nd Sustainable Innovation Conference, Epsom, Surrey, United Kingdom. 

Bosquet, A. & Mueller, C. & Hosoi, A.E. 2020, “Body Scan Processing, Generative Design, and Multiobjective Evaluation of Sports Bras.”, Applied Sciences, vol.10. 

14 Slow fashion involves local artisans and sustainable materials with the goal of preserving crafts and the environment.

Brennan, M., & Devine, K., 2019-last updated. “Music streaming has a far worse carbon footprint than the heyday of records and CDs – new findings.”, The Conversation. [Online]. Available: https://theconversation.com/music-streaming-has-a-far-worse-carbon-footprint-than-the-heyday-of-rec ords-and-cds-new-findings-114944 [October 2020]. 

Cantamessa, M., Montagna, F., Altavilla, S., & Casagrande-Seretti, A. 2020. “Data-driven design: The new challenges of digitalization on product design and development.”, Design Science, vol.6, E27. doi:10.1017/dsj.2020.25 
Churchman, C. 1967, “Free for All, Guest Editorial.”, Management Science, vol. 14, no.4, pp.B-141-B-146. https://doi.org/10.1287/mnsc.14.4.B141 

Davis, D. February 2020-last updated, “Generative design is doomed to fail,” [Online] Available: https://www.danieldavis.com/generative-design-doomed-to-fail/ [July 2020]. 

Eiben, A.E., Schoenauer, M. 2002, “Evolutionary computing.”, Information Processing Letters, vol. 82, issue 1, pp. 1-6. ISSN 0020-0190, https://doi.org/10.1016/S0020-0190(02)00204-1.

Ellen MacArthur Foundation, 2020-last updated. Vision of a circular economy for fashion. [Online]. Available:https://www.ellenmacarthurfoundation.org/assets/downloads/Vision-of-a-circular-economy-fo r-fashion.pdf [December 2020]. 

Ellen MacArthur Foundation, 2020-last updated. Circular Design, [Online]. Available: https://www.ellenmacarthurfoundation.org/explore/circular-design [December 2020]. 

European Commission, 2020-last updated. The EU Ecolabel for Textiles Factsheet, [Online]. Available: https://ec.europa.eu/environment/ecolabel/documents/textile_factsheet.pdf [November 2020]. 

Euratex, 2019-last updated. Facts & Key Figures of the European Textile and Clothing Industry, [Online]. Available: https://euratex.eu/wp-content/uploads/EURATEX-Facts-Key-Figures-2020-LQ.pdf [August 2020]. 

Eyekoot, M., 2019, This is a good guide for a sustainable lifestyle, BIS publishing, Amsterdam, the Netherlands. 

Fairtrade, 2020-last updated.Textile Standard, [Online]. Available: 
https://files.fairtrade.net/standards/TextileStandard_EN.pdf [January 2020]. 

Follet, L., July 2018-last updated. Generative Design in Nike's Innovation Department, [Online] Available:https://www.youtube.com/watch?v=vxiFEwAcqBc [August 2020]. 

Fox, F., Goldrick, M., Peng, A., & Whittington, K., October 2018-last updated, “Geek meets chic four actions to jump start advanced analytics in apparel,” [Online]. Available: 
https://www.mckinsey.com/industries/retail/our-insights/geek-meets-chic-four-actions-to-jump-start-adv anced-analytics-in-apparel# [July 2020]. 

GenCloth. 2020, Parametric pattern database, GenCloth, [Online] Available: www.gencloth.com [November 2020].

Gerber, D., Lin, E., Pan, B., Senel Solmaz, A., 2012, “Design optioneering: Multi-disciplinary design optimization through parameterization, domain integration and automation of a genetic algorithm.” Simulation Series, vol. 44. 

Gerber, D., 2007, Parametric Practices: Models for Design Exploration in Architecture. Harvard University Graduate School of Design, Massachusetts, United States of America. 

Global Fashion Agenda, 2018-last updated, Pulse of the fashion industry 2018, [Online]. Available: https://wordpress.globalfashionagenda.com/publications-and-policy/pulse-of-the-industry/ [November 2020]. 

Gurarda, A., 2019, “Seam Performance of Garments.”, Textile Manufacturing Processes. [Online]. https://www.intechopen.com/books/textile-manufacturing-processes/seam-performance-of-garments [October 2020]. DOI: 10.5772/intechopen.86436 

Holland, J.H., 1992, “Genetic Algorithms.”, Scientific American, vol. 267, no. 1, pp. 66–73. 

Jiang, Z., Guo, J. & Zhang, X., 2019, "Fast custom apparel design and simulation for future demand-driven manufacturing.", International Journal of Clothing Science and Technology, vol. 32, no. 2, pp. 255-270. 

Lee, J.S., & Jirousek, C., 2015, “The development of design ideas in the early apparel design process: a pilot study.”, International Journal of Fashion Design, Technology and Education, vol 8, no.2, pp.151-161, DOI: 10.1080/17543266.2015.1026411 

Kato, N. & Osone, H. & Oomori, K. & Ooi, C. & Ochiai, Y., 2019, GANs-based Clothes Design: Pattern Maker Is All You Need to Design Clothing”, The 10th Augmented Human International Conference, Reims, France. 

Kato, N., & Osone, H., & Sato, D., & Muramatsu, N., & Ochiai, Y., 2018, “DeepWear: a Case Study of Collaborative Design between Human and Artificial Intelligence”, The 12th International Conference on Tangible, Embedded and Embodied Interaction, ACM Proceedings, Stockholm Sweden. 

King, I., Lyu, M. R. & Yang, H., 2013, “Online learning for big data analytics.”, Tutorial Presentation at IEEE Big Data, [Online]. Available: 
http://cci.drexel.edu/bigdata/bigdata2013/ieee.bigdata.tutorial.1.slides.pdf [November 2020]. 

Levin, K., Cashore, B., Bernstein, S. & Auld, G., 2012, “Overcoming the tragedy of super wicked problems: constraining our future selves to ameliorate global climate change.”, Policy Sciences, vol. 45, pp.123–152. https://doi.org/10.1007/s11077-012-9151-0 

Liu, K., & Zhu, C., & Tao, X., & Bruniaux, P., & Zeng, X., 2019, “Parametric design of garment pattern based on body dimensions.”, International Journal of Industrial Ergonomics, vol. 72, pp. 212-221. 

McQuillan, H., 2020, “Digital 3D design as a tool for augmenting zero-waste fashion design practice.”, International Journal of Fashion Design, Technology and Education, vol. 13, no.1, pp.89-100. DOI: 10.1080/17543266.2020.1737248 

Nike, 2017-last updated, “A glimpse into the future by way of a shirt,” Nike News. [Online] Available: https://news.nike.com/news/nikelab-advanced-apparel-exploration-aae-1 [November 2020]. 

Nina, V.T.K.N., 2019, 3D Apparel Design Workflow for Puma SE, Metropolia University of Applied Sciences. Finland.

Omwami, A., Lahti, H., & Seitamaa-Hakkarainen, P., 2020, “The variation of the idea development process in apparel design: a multiple case study.”, International Journal of Fashion Design, Technology and Education, vol.13, no.3, pp.341-351. DOI: 10.1080/17543266.2020.1817573. 

Quantis, December 2020-last updated, “Measuring Fashion: FAQ.”, Quantis International, [Online]. Available: 
https://quantis-intl.com/wp-content/uploads/2020/12/quantis-measuring-fashion-report-faq.pdf [December 2020]. 

Quantis 2018. Environmental Impact of the Global Apparel and Footwear Industries Study, Quantis International, Zürich, Switzerland.

Rockstrom, J., Steffen W., Noone K., Persson A., Chapin III F. S., Lambin E., Lenton T. M., Scheffer M., Folke C., Schellnhuber H., Nykvist B., De Wit C. A., Hughes T., van der Leeuw S., Rodhe H., Sorlin S., Snyder P.K., Costanza R., Svedin U., Falkenmark M., Karlberg L., Corell R. W., Fabry V. J., Hansen J. , Walker J., Liverman D., Richardson K., Crutzen P., Foley J. 2009, Planetary boundaries: exploring the safe operating space for humanity, Ecology and Society, vol. 14, no. 2. [Online]. Available: http://www.ecologyandsociety.org/vol14/iss2/art32/ [December 2018]. 

Rothenberg, S., 2007, “Sustainability through servicizing.”, MIT Sloan Management Review, vol.48. [Online]. Available: 
https://www.researchgate.net/publication/228360037_Sustainability_through_servicizing [December 2020].

Singh, M., & Bajpai, U., & Vijayarajan, V., & Prasath, S., 2020, “Generation of fashionable clothes using generative adversarial networks: A preliminary feasibility study.”, International Journal of Clothing Science and Technology, vol. 32, pp. 177-187. 

Tang, M., & Cui, J., 2017, “Towards generative systems for supporting product design.”, International Journal of Design Engineering, vol. 7, no. 1. 

Vassilenko, K., Watkins, M., Chastain, S., Posacka, A., & Ross, P.S., 2019, “Me, my clothes and the ocean: The role of textiles in microfiber pollution.”, Science Feature. Ocean Wise Conservation Association, Vancouver, Canada. 

Sayem, A.S.M., Kennon, R., & Clarke, N., 2010, “3D CAD systems for the clothing industry.”, International Journal of Fashion Design, Technology and Education, vol. 3, no.2, pp. 45-53, DOI: 10.1080/17543261003689888 

Schindler, R., Schmalbein, N., Steltenkamp, V., Cave, J., Wens, B., & Anhalt, A., 2012, “Case studies of RFID as a green technology,” in SMART TRASH: Study on RFID tags and the recycling industry, RAND Corporation, pp. 187-214. 

Sopeoglou, Eva. 2019-last updated. The Curious Cube: Cedric Price Generator Archive. [Online] Available: http://www.evasopeoglou.com/portfolio/generator-cedric-price-archive/ [November 2020]. 

United Nations Development Program, 2016-last update, Sustainable Development Goals. [Online] Available: 
http://www.undp.org/content/undp/en/home/sustainable-development-goals.html [October 2020]. 

Watkin, S., Dunne, L., 2015, Functional Clothing Design: From Sportswear to Spacesuits. Bloomsbury Publishing Inc, New York, New York.

Wu, J., &Qian, X., &Wang, M., 2019, “Advances ingenerativedesign.”, Computer-AidedDesign, vol.116.
