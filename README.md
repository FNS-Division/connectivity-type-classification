### Instructions for the Enumerator:  

As an enumerator tasked with filling out a data questionnaire on connectivity types, please follow the detailed classification structure provided in [connectivity_type.txt](https://github.com/FNS-Division/connectivity-type-classification/blob/main/connectivity_type.txt) file. Your goal is to capture the most specific information available for each connectivity instance you encounter. Use the hierarchical classification to guide your data entry, starting from the broad category and narrowing down to the specific technology and its attributes.  
Here are the steps you should follow:  
1. Determine the main category of the connectivity type: wired or wireless. If this cannot be identified, use "unknown_connectivity_type".  
2. For wired connectivity:  
   a. Identify if it's fiber, metallic, or other. If uncertain, use "unknown_wired".  
   b. Specify the technology standard if known, using examples such as GPON for fiber or ADSL for metallic.  
3. For wireless connectivity:  
   a. Determine if it's terrestrial, non-terrestrial, or unknown. If terrestrial, further identify as point-to-area (cellular) or point-to-point.  
   b. For point-to-area (cellular), classify by generation (2g, 3g, 4g, 5g, or other). Provide the frequency band and technology standard if known. If uncertain, use "unknown_p2a".  
   c. For point-to-point, specify if it's radio, optical, or other. Provide the frequency band and technology standard if known. If uncertain, use "unknown_p2p".  
   d. For non-terrestrial, identify if it's satellite (including orbit type: leo, meo, geo, or other), haps, drones, or other. Provide the technology standard and frequency band if known. If uncertain, use "unknown_non-terrestrial".  
   e. If the wireless category doesn't fit any subcategory, use "unknown_wireless".  
4. When providing the connectivity type, aim for the most detailed description possible. For example:  
   - If you identify a fiber connection using GPON technology, record it as "wired > fiber > GPON" or simply "GPON".  
   - If you encounter a 4G LTE cellular connection operating at 900 MHz, record it as "wireless > terrestrial > point-to-area > 4g > frequency_band: 900 > technology_standard: LTE" or "LTE 900".  
   - For a low Earth orbit satellite using Starlink technology in the Ku-band, record as "wireless > satellite > leo > technology_standard: Starlink > frequency_band: Ku-band" or "leo Starlink Ku-band".  
5. If you come across a connectivity type that is not listed or known, use the appropriate "unknown" label from the classification.     
Remember that the more specific and accurate the information you provide, the more useful it will be for the analysis of connectivity types. If you encounter any uncertainties or have questions about the classification, do not hesitate to ask for clarification.


