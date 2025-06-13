# llava-med-reg2025

# Prepare REG_2025 Challenge with MTS Company 

REport Generation in pathology using Pan-Asia Giga-pixel WSIs
ℹ️ Notice
🟢 You are allowed to use pre-trained weights without restriction.
🚫 The use of additional training datasets is strictly prohibited.
⚠️ Some TIFF files were found to be corrupted during the data cleaning process. Reconstructing and redistributing the dataset would take considerable time and could lead to fairness issues among participants. Therefore, we have decided to exclude these files from the challenge.

You can check the list of excluded files in the following CSV file:
corrupted_id.csv

⚠️ We have identified color distortion issues in several .tiff files. The corrected versions of these files have been uploaded to the /REG_train_revised directory on servers 104–107. Please re-download and use the revised files from this directory.
If re-downloading is inconvenient, you can repair the files locally with: tiffset -s 262 6 PIT_file_name.tiff

You can find the list of affected files in the revised_list.csv file available at the following CSV file:
revised_list.csv

🔔 Updates
📢 Now open for registration!
📢 Now the TrainDataset is available for download! [Reg2025-Traindataset]
📢 Due to a network upgrade to improve FTP download speed, server access will be temporarily unavailable on May 26, 2025 (KST) from 09:00 to 10:00 AM. If you are downloading data via FTP, please resume the download after the maintenance period.

⚠️ The challenge schedule has been extended by one week; please refer to the updated Important Dates section.
✅ The Data Description section has been updated — you can now check the dataset overview and format details.
✅ The Debug Phase has been added — In this phase, you can check whether your submission follows the correct format.
✅ We have opened 3 additional servers for downloading the training dataset. If you experience download errors due to high traffic, we recommend using these servers. [Reg2025-Traindataset]
✅ You can evaluate the generated results by referring to the following GitHub repository: Evaluation code [Submission & Evaluation]

⭐ Important Dates:
Training data release: 13/05/2025 > 20/05/2025
Registration deadline: 27/06/2025 > 04/07/2025
Debug Phase opens: 27/06/2025
Debug Phase deadline: 03/07/2025
Test Phase 1 opens & Test Phase 1 data release: 27/06/2025 > 04/07/2025
Test Phase 1 deadline: 18/07/2025 > 25/07/2025
Test Phase 2 opens & Test Phase 2 data release: 19/07/2025 > 26/07/2025
Test Phase 2 deadline: 09/08/2025 > 16/08/2025
Announcement of winners: 09/09/2025
(All times are 10:00 AM, KST)

🔍 Challenge overview
Recent advances in vision-language foundation models have opened new possibilities in medical applications, particularly in image captioning, which generates textual descriptions from images. When applied to gigapixel-scale pathology images, this task demands advanced image analysis methods like slide-level feature extraction to process and interpret vast visual data. Automated pathology report generation, despite its complexities, has gained attention for its potential to address labor shortages, improve diagnostic accuracy, and enhance patient care. However, current evaluation methods relying on traditional NLP metrics such as BLEU, METEOR, and ROUGE are inadequate for the medical domain, where clinical relevance and content accuracy are paramount.

To address these limitations, this initiative focuses on:
1) evaluating report generation models with standardized datasets encompassing diverse pathological cases.
2) comparing generated reports with expert assessments to measure clinical alignment.
3) dentifying and adopting evaluation metrics tailored to medical standards.
4) exploring the integration of generated reports into diagnostic workflows, informed by clinical feedback.

Our ultimate goal is to enhance the practicality and reliability of pathology report generation models by ensuring they produce clinically meaningful and high-quality content. Furthermore, this initiative aims to address the limitations of current AI models in reflecting racial and ethnic diversity by utilizing a broader dataset that includes both Pan-Asia and European data. The challenge dataset comprises approximately 20,500 cases collected from six medical centers across five countries—Korea, Japan, India, Turkey, and Germany—contributing to the development of multicultural and multiethnic medical AI technologies.
