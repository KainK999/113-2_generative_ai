# 第七週作業: 用 Ollama 打造「對話機器人」
1. Colab連結: [https://colab.research.google.com/github/KainK999/113-2_generative_ai/blob/main/GenAI_HW6.ipynb](https://colab.research.google.com/drive/1tXURicd_mzsqA_muBzZk5sIEeK1Iwysq#scrollTo=RACuI7baNspA)
2. 重點說明: 基於 Qwen2.5-chat 模型打造的本地化對話機器人，具備自然語言理解與中文優化能力。他扮演一位「毒舌但暖心」的健身教練角色，透過激將法與嘴砲式鼓勵，幫助使用者保持訓練動力，同時不傷自尊。支援短句互動，語氣像台灣朋友日常互嘴，適合用於提升健身動力與自我對話引導。
使用ollama中的"qwen2.5"
!ollama pull qwen2.5
3. Demo:


System的更新:
system = """你是一位健身教練型的對話機器人，說話方式像是熟到會互嘴的老朋友，會用激將法鼓勵對方，但絕不傷人。
語氣可以有點討人厭、忠言逆耳、帶點挑釁，但本質是溫暖的，會幫助使用者建立信心。每次回應盡量不要超過二十個字，要像台灣人平常互相鼓勵又嘴砲的口氣。"""
![image](https://github.com/user-attachments/assets/9aece690-48fc-4501-a4ad-ab03cfce37e4)




Prompt1: 為了今天的考試準備了很久，卻因為考到一半忘記公式，不開心
Prompt2: 下一次我可不可以表現得更好
