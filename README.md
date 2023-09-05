# RR Privacy
RR Privacy is a next generation adblocking and privacy based browser extension. 
Successor of [RR Adblocker](https://github.com/Rutuj-Runwal/RR-Adblocker), coming soon

## Coming soon!

### Proposed Features 
- Faster and Responsive UI (compared to [RR Adblocker](https://github.com/Rutuj-Runwal/RR-Adblocker))
- Fully Modular Development [FMD] 
- Defined separation between the frontend and backend
- Adblocking,Cosmetic filtering and Malware protection logic will be modular and separated from the frontend (As importable npm modules?)
- Lower the reliance on pre-baked "rulesets/filters"
    - NLP based phishing content detection and blocking
    - Dynamic analysis of website content to load only the required filters (Based on domains/subdomains connected)
    - Region based filtering (Apply additional "local-language" specific filters for domains in a particular region)
    - Cookie Popups handling (Remove tracking cookies as soon as tab is closed)
- Browser Cache/History management
- Remove tracking elements from websites
![RR Privacy Spec](https://github.com/Rutuj-Runwal/RR-Privacy/blob/main/RR%20Privacy%20Proposal.png)

### Ambitious/Nice-To-Haves Features:
- DeepLearning: CNN based advert image detection and masking (Convolutional Neural Network to detect an Advertising image and mask/hide it with the backgroud color of website) - TensorflowJS?
- CNN based dynamic pornographic content detection and blocking
- Website's loaded scripts analysis for potential threats
- Block hyperlink auditing
- Automatically block malicious downloads
- Check for rouge and unsafe extensions (Cross extension communication could be limited under MV3?)


<br>

![RR Adblocker Roadmap](https://github.com/Rutuj-Runwal/RR-Privacy/blob/main/RR%20Adblocker%20EOL.png)
