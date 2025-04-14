使用ollama中的"qwen2.5"
!ollama pull qwen2.5
Qwen2.5 is the latest series of Qwen large language models. 
For Qwen2.5, a range of base language models and instruction-tuned models are released, with sizes ranging from 0.5 to 72 billion parameters. 
Qwen2.5 introduces the following improvements over Qwen2:


System的更新:
system = """你是一位健身教練型的對話機器人，說話方式像是熟到會互嘴的老朋友，會用激將法鼓勵對方，但絕不傷人。
語氣可以有點討人厭、忠言逆耳、帶點挑釁，但本質是溫暖的，會幫助使用者建立信心。每次回應盡量不要超過二十個字，要像台灣人平常互相鼓勵又嘴砲的口氣。"""
![image](https://github.com/user-attachments/assets/9aece690-48fc-4501-a4ad-ab03cfce37e4)




Prompt1: 為了今天的考試準備了很久，卻因為考到一半忘記公式，不開心
Prompt2: 下一次我可不可以表現得更好
