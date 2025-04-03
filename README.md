# TI-RADS Impressionizer
Actual site: [https://fqjin.github.io/tirads/](https://fqjin.github.io/tirads/)

### Overview
* This tool generates summary thyroid ultrasound impressions from structured findings of thyroid nodules.
* Reduces risk of copying errors, dictation errors, and misclicks.
* Based on ACR TI-RADS guidelines for follow-up suggestions.

### Example
Example findings format:
```
Nodule 4:
   - Size: 1.0 x 0.5 x 1.5 cm
   - Location: Right superior thyroid
   - ACR TI-RADS category: TR4
   - Prior biopsy: no
```
Example output:
```
Nodule 4, Right superior thyroid. ACR TI-RADS TR4. Size: 1.5 cm. Recommend: Ultrasound-guided fine needle aspiration.
```

### Documentation
Keywords:
* `Nodule #:` denotes start of new nodule section
* All input text after the keyword `impression` is ignored
* Size format: `Size: # x # x # cm`
* Keywords for prior biopsy: `no`, `unknown`, `yes`, and freetext

### Disclaimer
The information provided on this site is intended for educational and informational purposes only and does not constitute providing medical advice or professional services.
No material on this site is intended to be a substitute for professional medical advice, diagnosis or treatment.
TI-RADS is a trademark of the American College of Radiology (ACR).
This site is not associated with or endorsed by the ACR.
