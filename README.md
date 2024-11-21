# A Deep Cross-Modal Prompt Learning Network for AI-Generated Image Quality Assessment

<div align="center">
  <img src="./figures/Model.jpg" style="width:90%;">
</div>

*Abstract: In recent years, the application of multimodal vision-language pre-trained models (such as CLIP) to AI-Generated Image Quality Assessment (AGIQA) tasks has become increasingly prevalent. Related methods have made significant contributions to the study of AGIQA through text and visual prompt learning. However, existing AGIQA methods only focus on a single modality (either language or vision) without fully considering the synergy between text and image. To address this, we propose a Deep Cross-Modal Prompt Learning Network for AGIQA, dubbed DCMPLN. This method designs an auxiliary task that connects multi-head attention modules to gradually enhance the coupling between learnable text and visual prompts. The knowledge of visual-language synergy acquired from the auxiliary task is utilized to guide multimodal prompt learning in the main task. Additionally, we introduce an extra bottleneck layer in the visual branch to learn new features and refine the original pretrained features through residual-style feature fusion. Experimental results on multiple generated image datasets (such as AGIQA-3K, AIGCIQA2023, and AGIQA-1K) demonstrate that the proposed method outperforms existing state-of-the-art image quality assessment models.*

**The paper is currently under review. We have made a partial release of the code, including the model's trained weights (in .pth format). The complete code and dataset are ready and will be made available upon acceptance of the paper.**

# Datasets
You can download datasets AGIQA-3K, AIGCIQA2023 and AGIQA-1K. Next, updata the dataset path accordingly.
  - AGIQA-3K download [here](https://drive.google.com/file/d/1M27YasIoItRFdRRBrQKwXmNWCSDxa3fF/view?usp=sharing)
  - AGIQA-1K download [here](https://drive.google.com/file/d/1Qdd5lrcD1T8U1mjKJlPk6SmI830-XtaP/view?usp=sharing)
  - AIGCIQA2023 download [here](https://drive.google.com/file/d/1FgIMvpsCBAVU7_ldMT5kww70RG5pK18D/view?usp=sharing)
  
# Checkpoint
You can download the trained model weights [checkpoint](https://drive.google.com/file/d/1WnYMxHxnkMYgYNZiTVl0Xczl5LmehszN/view?usp=sharing) for testing.
