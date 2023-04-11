# Keeping Track of Affordable Language Models

This repository is dedicated to organizing affordable but powerful language models (LLMs). The repository providing valuable insights into the latest models, including number of parameters, fine-tuning datasets and techniques, and hardware specifications. With this repository, you can quickly and easily access all the vital information you need for your affordable LLM needs.

# Model Spec (reformating)

| date |   model   | param |   data   | finetune |  hardware | references |
|------|-----------|--------|---------|-----------|-------------|-------------|
|04/08| Vicuna-7B |7B|
|04/01| Vicuna-13B|13B|
|04/07|Chinese-LLaMA-Alpaca|13B|
|03/28|Chinese-LLaMA-Alpaca|7B|

---

# News about 🦙 Cult and other AIGC models

- 04/09: SVDiff, diffusion fine-tune method like LoRA ([tweet](https://twitter.com/mk1stats/status/1644830152118120448), [repo](https://github.com/mkshing/svdiff-pytorch))
- 04/09: RPTQ, new 3 bit quantization ([repo](https://github.com/hahnyuan/RPTQ4LLM), [paper](https://arxiv.org/abs/2304.01089))
- 04/08: Wonder Studio, robot beat human with kongfu ([tweet](https://twitter.com/WonderDynamics/status/1644376317595615233))
- 04/08: chatGDB, chatgpt for GDB ([tweet](https://twitter.com/gdb/status/1644452849018077185), [repo](https://github.com/pgosar/ChatGDB))
- 04/08: Vicuna-7B, small yet capable ([repo](https://github.com/lm-sys/FastChat/#vicuna-7b)), Vicuna shows impressive performance against GPT4 by lastest paper of MSFTResearch ([tweet](https://twitter.com/lmsysorg/status/1644439032074768384))
- 04/07: Instruction tuning with GPT4, academic self-instruct guide from microsoft research ([tweet](https://twitter.com/omarsar0/status/1644143324192751616), [blog](https://instruction-tuning-with-gpt-4.github.io/), [repo](https://github.com/Instruction-Tuning-with-GPT-4/GPT-4-LLM), [paper](https://arxiv.org/pdf/2304.03277.pdf))
- 04/07: Chinese-LLaMA-Alpaca release its 13B model ([tweet](https://twitter.com/KCrosner/status/1644285818058731522))
- 04/07: MathPrompter, How to chatwith GPT3 Davinci API and archive better on math benmark ([paper](https://arxiv.org/pdf/2303.05398.pdf))
- 04/07: engshell, interact with your shell using english language ([tweet](https://twitter.com/omarsar0/status/1644333121540698112))
- 04/07: a chinese geek fine-tune a chatglm-6b model on his wechat dialogue and blog to produce a digital version of him self ([tweet](https://greatdk.com/1908.html))
- 04/06: StackLLaMA, A hands-on guide to train LLaMA with RLHF, fine-tuned on stack exchange QA data ([blog](https://huggingface.co/blog/stackllama), [demo](https://huggingface.co/spaces/trl-lib/stack-llama))
- 04/06: Arxiv Chat, chat with the lastest papers ([tweet](https://twitter.com/bhutanisanyam1/status/1643811531233148929))
- 04/06: Firefly, a 1.4B/2.6B chinese chat LLM, finetune on 1.1M multi-task dataset ([repo](https://github.com/yangjianxin1/Firefly))
- 04/06: a chinese guide of chatgpt [repo](https://gitlab.com/awesomeai/awesome-chatgpt-zh)
- 04/06: LamaCleaner, segment anything and inpaint anything ([tweet](https://twitter.com/sfjccz/status/1643992289294057472))
- 04/05: SAM, Meta AI release Segment Anything Model as foundation model for image segmentation, and SA-1B dataset, which is 400x larger than any existing segmentation dataset ([tweet](https://twitter.com/MetaAI/status/1643599800414380038))
- 04/04: a beautiful cli for chatgpt ([tweet](https://twitter.com/niceoe/status/1642920630445297664))
- 04/04: Baize, fine-tune with LoRA using 100K dialogs ChatGPT self-chat and other opensource dataset, released 7B, 13B and 30B models ([repo](https://github.com/project-baize/baize), [tweet](https://twitter.com/XuCanwen/status/1643074086485086208), [demo](https://huggingface.co/spaces/project-baize/baize-lora-7B), [model](https://huggingface.co/project-baize/baize-lora-13B))
- 04/03: Koala-13B, fine-tuned from LLaMA on user-shared conversations and open-source datasets, performs similarly to Vicuna ([blog](https://bair.berkeley.edu/blog/2023/04/03/koala/), [demo](https://chat.lmsys.org/?model=koala-13b), [repo](https://github.com/young-geng/EasyLM))
- 04/02: LMFlow, train on single 3090 for 5 hours and get your own chatgpt ([blog](https://www.jiqizhixin.com/articles/2023-04-02), [repo](https://github.com/OptimalScale/LMFlow))
- 04/01: Alpaca-CoT, extend CoT data to Alpaca to boost its reasoning ability, provide gathered datasets ([repo](https://github.com/PhoebusSi/Alpaca-CoT))
- 04/01: Vicuna-13B, An Open-Source Chatbot Impressing GPT-4 with 90% ChatGPT Quality, fine-tune LLaMA on ~70K conversations from ShareGPT ([blog](https://vicuna.lmsys.org/), [repo](https://github.com/lm-sys/FastChat), [demo](https://chat.lmsys.org/), [data](https://github.com/lm-sys/FastChat/issues/90#issuecomment-1493250773), [gptq-4-bit](https://huggingface.co/elinas/vicuna-13b-4bit))
- 04/01: Official Apple Core ML Stable Diffusion Library, M-series chips beat 4090, ([repo](https://github.com/apple/ml-stable-diffusion), [MochiDiffusion](https://github.com/godly-devotion/MochiDiffusion), [swift-coreml-diffusers](https://github.com/huggingface/swift-coreml-diffusers))
- 03/31: BloombergGPT, 50B LLM outperform existing models on financial tasks ([tweet](https://twitter.com/omarsar0/status/1641787456436547584))
- 03/31: HuggingGPT, as an interface for LLMs to connect AI Models for solving comlicated AI tasks ([tweet](https://twitter.com/johnjnay/status/1641609645713129473), [demo](https://huggingface.co/spaces/microsoft/HuggingGPT))
- 03/31: Llama-X ([repo](https://github.com/AetherCortex/Llama-X))
- 03/30: ColossalChat, from [ColossalAI](https://github.com/hpcaitech/ColossalAI) ([demo](https://chat.colossalai.org/), [tweet](https://twitter.com/omarsar0/status/1641070883497205761), [medium](https://medium.com/@yangyou_berkeley/colossalchat-an-open-source-solution-for-cloning-chatgpt-with-a-complete-rlhf-pipeline-5edf08fb538b), [repo](https://github.com/hpcaitech/ColossalAI/tree/main/applications/Chat), [serve](https://github.com/hpcaitech/ColossalAI/blob/main/applications/Chat/inference/server.py))
- 03/30: ChatGLM-6B, from THUDM(Tsinghua University), code and data not release ([repo](https://github.com/THUDM/ChatGLM-6B), [model](https://huggingface.co/THUDM/chatglm-6b))
- 03/29: LLaMA-Adapter, fine-tuning LLaMA with 1.2M learnable parameters in 1 hour on 8 A100 ([tweet](https://twitter.com/lupantech/status/1644024402215051265), [repo](https://github.com/ZrrSkywalker/LLaMA-Adapter), [demo](https://huggingface.co/spaces/csuhan/LLaMA-Adapter))
- 03/28: Chinese-LLaMA-Alpaca, add 20K chinese sentencepiece tokens to vocab and pre-trained LLaMA in 2 steps, fine-tuned LLaMA on a 2M chinese corpus using Alpaca-LoRA, 7B model released, dataset not ([repo](https://github.com/ymcui/Chinese-LLaMA-Alpaca), [tweet](https://twitter.com/KCrosner/status/1640641475909423104), [blog](https://ymcui.com/), [model](https://huggingface.co/ziqingyang/chinese-alpaca-lora-7b))
- 03/28: gpt4all, fine-tune LLaMa using LoRA with ~800k gpt3.5-turbo generations, include clean assistant data including code, stories and dialogue ([repo](https://github.com/nomic-ai/gpt4all), [model](https://huggingface.co/nomic-ai/gpt4all-lora), [data](https://huggingface.co/datasets/nomic-ai/gpt4all_prompt_generations))
- 03/22: Alpaca-LoRA-Serve, gradio based chatbot service ([tweet](https://twitter.com/algo_diver/status/1638525828773576704), [repo](https://github.com/deep-diver/Alpaca-LoRA-Serve))
- 03/22: Alpaca-LoRA, reproducing the Stanford Alpaca results using [low-rank adaptation(LoRA)](https://arxiv.org/pdf/2106.09685.pdf) on RTX4090 and run on a Raspberry Pi 4 ([tweet](https://twitter.com/miolini/status/1634982361757790209), [repo](https://github.com/tloen/alpaca-lora), [demo](https://huggingface.co/spaces/tloen/alpaca-lora), [model](https://huggingface.co/tloen/alpaca-lora-7b), [blog](https://replicate.com/blog/fine-tune-alpaca-with-lora), [reproduce tweet](https://twitter.com/nash_su/status/1639404405811478528), [zhihu](https://zhuanlan.zhihu.com/p/615227156), [sina](https://finance.sina.com.cn/tech/roll/2023-03-26/doc-imynemwf9000026.shtml))
- 03/22: BELLE, fine-tune BLOOMZ-7B1-mt and LLaMA(7B/13B) on a 1.5M chinese dataset generate in a alpaca way, ([repo](https://github.com/LianjiaTech/BELLE), [model](https://huggingface.co/BelleGroup))
- 03/17: instruct-gpt-j, NLPCloud team fine-tune GPT-J using Alpaca's dataset ([blog](https://nlpcloud.com/instruct-version-of-gpt-j-using-stanford-alpaca-dataset.html), [model](https://huggingface.co/nlpcloud/instruct-gpt-j-fp16))
- 03/13: Stanford Alpaca, fine-tune LLaMA 7B with a 52K single-turn instruction-followling dataset generate from OpenAI’s text-davinci-003  ([blog](https://crfm.stanford.edu/2023/03/13/alpaca.html), [repo](https://github.com/tatsu-lab/stanford_alpaca))
- 03/11: ChatIE, solving Zero-Shot Information Extraction problem by enhancing ChatGPT with CoT prompting, achieve good performance on primary IE benchmarks ([repo](https://github.com/cocacola-lab/ChatIE))
- peft: State-of-the-art Parameter-Efficient Fine-Tuning (PEFT) methods ([repo](https://github.com/huggingface/peft))
- GPTQ-for-LLaMa: 4 bits quantization of LLaMA using [GPTQ](https://arxiv.org/abs/2210.17323) ([repo](https://github.com/qwopqwop200/GPTQ-for-LLaMa)) 
- llama.cpp: Inference of LLaMA model in pure C/C++, support different hardware platform & models, support 4-bit quantization using [ggml](https://github.com/ggerganov/ggml) format ([repo](https://github.com/ggerganov/llama.cpp), [alpaca.cpp](https://github.com/antimatter15/alpaca.cpp)); support python bindings ([llama-cpp-python](https://github.com/abetlen/llama-cpp-python), [pyllamacpp](https://github.com/nomic-ai/pyllamacpp), [llamacpp-python](https://github.com/thomasantony/llamacpp-python) )
- llama-dl: high speed download of LLaMA model ([repo(deprecated)](https://github.com/shawwn/llama-dl), [model](https://huggingface.co/decapoda-research/llama-7b-hf))
- text-generation-webui: A gradio web UI for deploy LLMs like GPT-J, LLaMA ([repo](https://github.com/oobabooga/text-generation-webui))

  
# Applications

- 04/03: prompt engineering guide ([blog](https://www.promptingguide.ai/zh)), openai best practices ([blog](https://help.openai.com/en/articles/6654000-best-practices-for-prompt-engineering-with-openai-api)), prompt prefect ([blog](https://promptperfect.jina.ai/)), prompt searching ([repo](https://github.com/MaHuanAAA/g_fair_prompting)), PromptInject ([repo](https://github.com/agencyenterprise/PromptInject)), auto prompt engineering ([blog](https://www.promptingguide.ai/zh/techniques/ape))
- 04/01: PolyglotSiri Apple Shortcut, ([tweet](https://twitter.com/Munntein/status/1641683629968592897), [repo](https://github.com/Munntein/PolyglotSiri-Apple-Shortcut))
- 04/01: Twitter's Recommendation Algorithm ([repo](https://github.com/twitter/the-algorithm))
- 03/31: GPT4 UI generation ([tweet](https://twitter.com/gdb/status/1641496253572997123))
- 03/30: ChatExplore ([tweet](https://twitter.com/omarsar0/status/1641444447304011776))
- 03/29: Uncle Rabbit, the first conversational holographic AI ([tweet](https://twitter.com/ArturoJReal/status/1641129170100011035), [blog](https://feld.com/archives/2023/03/do-ai-rabbits-dream-of-holographic-carrots/))
- 03/29: chatgpt instead of siri ([tweet](https://twitter.com/punk2898/status/1641063874186346496))
- 03/27: LLaMA voice chat + Siri TTS ([tweet](https://twitter.com/ggerganov/status/1640416314773700608))
- 03/26: LLaMA voice chat ([tweet](https://twitter.com/ggerganov/status/1640022482307502085))
- 03/15: llama_index: connect LLM with external data ([repo](https://github.com/jerryjliu/llama_index))
- 03/15 tldream/lama-cleaner: tiny little diffusion drawing app ([repo1](https://github.com/Sanster/tldream), [repo2](https://github.com/Sanster/lama-cleaner))
- A1111-Web-UI-Installer: A gradio web UI for deploy stable diffusion models ([repo](https://github.com/EmpireMediaScience/A1111-Web-UI-Installer))
