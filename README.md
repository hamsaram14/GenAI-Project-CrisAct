# GenAI-Project-CrisAct


CrisAct: Leveraging Large Language Models for
Crisis Detection and Response
Hamsalakshmi Ramachandran, Sugandha Chauhan
Department of Applied Data Sciences
San Jose State University
Abstract—The increasing severity and frequency of wildfires
necessitate efficient crisis detection and accurate situational
awareness to streamline emergency responses. This project
presents an advanced wildfire crisis detection framework integrating
instruction-fine-tuned Large Language Models (LLMs)
with Retrieval-Augmented Generation (RAG) for precise multimodal
tweet classification and distress identification. Utilizing
the CrisisMMD dataset comprising over 16,000 annotated
tweet texts and 18,000 images, we systematically preprocess
textual data through cleaning steps, including emoji removal,
hashtag filtering, and special-character normalization, to build
robust instruction-context-response (ICR) datasets. Fine-tuning
the LLaMA-2-7b-chat-hf model with 4-bit quantization and
Parameter-Efficient Fine-Tuning (PEFT) via LoRA significantly
enhances classification performance, elevating distress-detection
accuracy from approximately 56% to over 99%. Incorporating
semantic retrieval through FAISS indexing of all-mpnet-basev2
embeddings further augments context and reduces model
hallucinations. Our evaluation demonstrates strong disaster-type
classification (F1-score of 0.814), reliable distress detection (F1-
score of 0.840), action recommendation (F1-score of 0.895) and a
commendable semantic alignment (BLEU score of 0.5818). This
integrated LLM and RAG pipeline provides a robust foundation
for real-time crisis response, supporting emergency management
teams with rapid and accurate decision-making during wildfire
emergencies.
Index Terms—Crisis Management, Large Language Models,
Disaster Response, Emergency Communication, Situational
Awareness, Instruction Fine-Tuning, RAG, ICR Triplet, Wildfire,
California, Social Media.
