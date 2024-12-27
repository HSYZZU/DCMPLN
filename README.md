# A Deep Cross-Modal Prompt Learning Network for Artificial Intelligence Generated Image Quality Assessment

<div align="center">
  <img src="./figs/Model.jpg" style="width:95%;">
</div>

*Abstract: In recent years, multi-modal vision-language pre-trained models have been widely used to build high-performance Artificial Intelligence (AI) systems
for computer vision applications. Previous approaches have advanced Artificial Intelligence Generated Image Quality Assessment (AGIQA) research via text-based or visual prompt learning, yet most methods remain constrained to a single modality (language or vision), overlooking the interplay between text and image. To address this issue, we propose a Deep Cross-Modal Prompt Learning Network (DCMPLN) for AGIQA. This model introduces a Multi-modal Prompt Attention (MPA) module, employing multi-head attention to enhance the integration of textual and visual prompts. Furthermore, an Image Adapter module is incorporated into the visual pathway to extract novel features and fine-tune pre-trained ones using residual-style fusion. Experimental results on multiple generated image datasets demonstrate that
the proposed method outperforms existing state-of-the-art image quality assessment models.*

**The paper is currently under review. We have made a partial release of the code, including the model's trained weights (in .pth format). The complete code and dataset are ready and will be made available upon acceptance of the paper.**

# Datasets
You can download datasets AGIQA-3K, AIGCIQA2023, and AGIQA-1K. Next, update the dataset path accordingly.
  - AGIQA-3K download [here](https://drive.google.com/file/d/1M27YasIoItRFdRRBrQKwXmNWCSDxa3fF/view?usp=sharing)
  - AGIQA-1K download [here](https://drive.google.com/file/d/1Qdd5lrcD1T8U1mjKJlPk6SmI830-XtaP/view?usp=sharing)
  - AIGCIQA2023 download [here](https://drive.google.com/file/d/1FgIMvpsCBAVU7_ldMT5kww70RG5pK18D/view?usp=sharing)
  
# Checkpoint
You can download the trained model weights checkpoint for testing.
  - checkpoint download [here](https://drive.google.com/file/d/1WnYMxHxnkMYgYNZiTVl0Xczl5LmehszN/view?usp=sharing) 
