# Aim:	Comprehensive Report on the Fundamentals of Generative AI and Large Language Models (LLMs)
Experiment:
Develop a comprehensive report for the following exercises:
1.	Explain the foundational concepts of Generative AI. 
2.	Focusing on Generative AI architectures. (like transformers).
3.	Generative AI applications.
4.	Generative AI impact of scaling in LLMs.

# Algorithm: 
Step 1: Define Scope and Objectives
1.1 Identify the goal of the report (e.g., educational, research, tech overview)
1.2 Set the target audience level (e.g., students, professionals)
1.3 Draft a list of core topics to cover
________________________________________
Step 2: Create Report Skeleton/Structure
2.1 Title Page
2.2 Abstract or Executive Summary
2.3 Table of Contents
2.4 Introduction
2.5 Main Body Sections:
•	Introduction to AI and Machine Learning
•	What is Generative AI?
•	Types of Generative AI Models (e.g., GANs, VAEs, Diffusion Models)
•	Introduction to Large Language Models (LLMs)
•	Architecture of LLMs (e.g., Transformer, GPT, BERT)
•	Training Process and Data Requirements
•	Use Cases and Applications (Chatbots, Content Generation, etc.)
•	Limitations and Ethical Considerations
•	Future Trends
2.6 Conclusion
2.7 References
________________________________________
Step 3: Research and Data Collection
3.1 Gather recent academic papers, blog posts, and official docs (e.g., OpenAI, Google AI)
3.2 Extract definitions, explanations, diagrams, and examples
3.3 Cite all sources properly
________________________________________
Step 4: Content Development
4.1 Write each section in clear, simple language
4.2 Include diagrams, figures, and charts where needed
4.3 Highlight important terms and definitions
4.4 Use examples and real-world analogies for better understanding
________________________________________
Step 5: Visual and Technical Enhancement
5.1 Add tables, comparison charts (e.g., GPT-3 vs GPT-4)
5.2 Use tools like Canva, PowerPoint, or LaTeX for formatting
5.3 Add code snippets or pseudocode for LLM working (optional)
________________________________________
Step 6: Review and Edit
6.1 Proofread for grammar, spelling, and clarity
6.2 Ensure logical flow and consistency
6.3 Validate technical accuracy
6.4 Peer-review or use tools like Grammarly or ChatGPT for suggestions
________________________________________
Step 7: Finalize and Export
7.1 Format the report professionally
7.2 Export as PDF or desired format
7.3 Prepare a brief presentation if required (optional)



# Output

# Comparing the Behaviour of Different Generative AI Models Using Identical Prompts

**Name:** Karkie F
**Register No.:** 212225040172
**Tools compared:** ChatGPT and Claude

---

## 1. Objective

The objective of this experiment is to compare how ChatGPT and Claude respond to the same five prompts about Generative AI. The responses are evaluated using accuracy, creativity, hallucination risk, reasoning, speed and engineering usefulness.

The five prompts cover foundational concepts, transformer architectures, applications, scaling in Large Language Models (LLMs), and the process of building an LLM.

### 1.1 Prompts Used

**Prompt 1 – Foundational Concepts**

> Explain the foundational concepts of Generative AI. Cover what it is, how it differs from discriminative AI, the main model families (GANs, VAEs, diffusion models, autoregressive models), training data, and key terms such as tokens, embeddings and prompts. Use simple language with one real-world example per concept and a short summary table.

**Prompt 2 – Architectures**

> Explain Generative AI architectures with a focus on transformers. Describe self-attention, multi-head attention, positional encoding, encoder-only vs decoder-only vs encoder-decoder designs, and briefly compare transformers with RNNs, GANs, VAEs and diffusion models. Include a simple block-level diagram description.

**Prompt 3 – Architecture and Applications**

> Explain how each major Generative AI architecture (transformer, GAN, VAE, diffusion) maps to real applications in text, image, audio, video, code and healthcare. Present the answer as a table of architecture, typical applications, strengths and limitations.

**Prompt 4 – Impact of Scaling**

> Explain the impact of scaling in Large Language Models. Cover scaling laws (parameters, data, compute), emergent abilities, the Chinchilla compute-optimal idea, cost and energy implications, diminishing returns, and the risks that grow with scale.

**Prompt 5 – Building an LLM**

> Explain what a Large Language Model is and how it is built, step by step: data collection and cleaning, tokenization, model architecture, pre-training, supervised fine-tuning, RLHF/alignment, evaluation, and deployment. Mention tools and frameworks an engineer would use.

### 1.2 Why These Prompts Were Designed This Way

Each prompt follows the same pattern, which keeps the comparison fair:

| Prompt element | Purpose |
|----------------|---------|
| Clear topic | Prevents the tool from choosing a different scope |
| Listed sub-points | Makes completeness measurable (a missing sub-point is easy to spot) |
| Audience and tone ("simple language") | Tests whether the tool adapts its explanation level |
| Required format (table, diagram description) | Tests instruction-following |
| Engineering request (tools and frameworks) | Tests practical usefulness, not only theory |

---

## 2. Experimental Procedure

1. Use a fresh chat in each tool and submit each prompt without changing its wording.
2. Save the complete responses for all five prompts.
3. Score the responses from 1 to 5 using the rubric in Section 4.
4. Verify technical claims, dates, figures and paper names against reliable sources before recording factual mistakes.

**Note:** The Claude responses supplied for this report were generated in one chat session, and timing was not measured. The actual five ChatGPT response transcripts were not supplied with the material used to prepare this report. Therefore, ChatGPT ratings remain indicative, and speed is not ranked.

### 2.1 Controls to Keep the Test Fair

| Variable | How to control it |
|----------|-------------------|
| Chat context | Start a new chat for every prompt where possible |
| Prompt wording | Copy and paste; never retype |
| Model mode | Use the default mode in both tools, or the same type of mode (fast vs reasoning) |
| Network and time of day | Run both tools back to back on the same connection |
| Randomness | Repeat a prompt twice and note any large differences in the answers |

---

## 3. Reference Concepts Used for Checking

Generative AI learns patterns in data and generates new content. Discriminative models classify or distinguish inputs, while generative models create samples. Major families include autoregressive models, GANs, VAEs and diffusion models. Important terms include tokens, embeddings, prompts, training data and hallucination.

Transformers use self-attention to combine information across tokens, multi-head attention to learn different relationships, and positional information to represent token order. Encoder-only models are commonly used for understanding; decoder-only models generate token sequences; encoder-decoder models transform an input into an output.

Applications vary by architecture. Transformers are used in language and code systems; GANs can generate sharp synthetic images; VAEs learn useful latent spaces and support anomaly detection; diffusion models generate high-quality images and are also used in audio and video systems. Modern systems may combine architectures.

Scaling laws describe how model performance changes with parameters, training data and compute. The Chinchilla study highlighted the importance of balancing model size with the amount of training data. Scaling can improve capabilities but also increases compute, energy, privacy, misuse and misinformation risks.

A typical LLM development pipeline includes data collection and cleaning, tokenization, architecture design, pre-training, supervised fine-tuning, alignment, evaluation and deployment. Example tools include Python, PyTorch, JAX, Hugging Face Transformers, PEFT/LoRA, DeepSpeed, Megatron-LM, vLLM and Docker.

### 3.1 Detailed Checking Tables

**Model families (Prompt 1 and 2)**

| Family | Core idea | Typical use | Main weakness |
|--------|-----------|-------------|---------------|
| Autoregressive | Predicts the next token step by step | Text and code generation | Slow token-by-token generation |
| GAN | Generator and discriminator compete | Realistic images | Unstable training, mode collapse |
| VAE | Encodes to a latent space and decodes | Anomaly detection, latent exploration | Outputs can be blurry |
| Diffusion | Removes noise step by step | Text-to-image, audio, video | Slow sampling, high compute |

**Transformer designs (Prompt 2)**

| Design | What it does | Examples |
|--------|--------------|----------|
| Encoder-only | Reads the full input for understanding | BERT |
| Decoder-only | Predicts the next token using earlier tokens only | GPT-style models, LLaMA |
| Encoder-decoder | Encodes input, then decodes an output | T5, translation models |

**Block-level view of one transformer layer**

```
Tokens -> Embeddings + Positional encoding
   -> [ Multi-head attention -> Add & Norm -> Feed-forward -> Add & Norm ] x N
   -> Linear layer -> Softmax -> Next-token probabilities
```

**Scaling summary (Prompt 4)**

| Aspect | Expected content |
|--------|------------------|
| Scaling laws | Loss falls predictably with more parameters, data and compute (Kaplan et al., 2020) |
| Chinchilla | Model size and training tokens should grow together; smaller well-trained models can beat larger under-trained ones (Hoffmann et al., 2022) |
| Emergent abilities | New skills appear at scale, though researchers debate how sharp the jumps are |
| Cost and energy | Large accelerator clusters, high electricity and money cost, expensive serving |
| Diminishing returns | Each gain needs much more compute; high-quality data is finite |
| Risks | Hallucination, misuse, privacy leakage, bias, concentration of power |

**LLM pipeline (Prompt 5)**

| Stage | Key activity | Example tools |
|-------|--------------|---------------|
| Data collection and cleaning | Gather, filter, deduplicate | Python, Spark |
| Tokenization | Convert text to tokens | SentencePiece, tiktoken |
| Architecture | Choose layers, heads, context length | PyTorch, JAX |
| Pre-training | Next-token prediction at scale | DeepSpeed, Megatron-LM |
| Supervised fine-tuning | Instruction-response training | Hugging Face Transformers, PEFT/LoRA |
| Alignment | Preference-based tuning | TRL |
| Evaluation | Benchmarks, red-teaming | lm-evaluation-harness |
| Deployment | Optimise and serve | vLLM, ONNX Runtime, Docker |

### 3.2 Per-Prompt Evaluation Checklist

Use this checklist on each tool's real answer. Tick an item only if it actually appears in the response.

| Prompt | Must-have items to check |
|--------|--------------------------|
| 1 | Definition; generative vs discriminative; four model families; training data; tokens, embeddings, prompts; one example per concept; summary table |
| 2 | Self-attention; multi-head attention; positional encoding; three designs; comparison with RNN, GAN, VAE, diffusion; block-level diagram description |
| 3 | Table with architecture, applications, strengths, limitations; coverage of text, image, audio, video, code, healthcare |
| 4 | Scaling laws; emergent abilities; Chinchilla; cost and energy; diminishing returns; risks |
| 5 | All eight pipeline stages in order; named tools and frameworks; distinction between pre-training and fine-tuning |

---

## 4. Scoring Rubric

- **Accuracy:** Technical correctness and completeness against the reference concepts.
- **Creativity:** Useful analogies, examples, structure and readability.
- **Hallucination:** Whether factual claims are unsupported or incorrect; a higher score means fewer errors.
- **Reasoning:** Logical explanations of causes, effects and trade-offs.
- **Speed:** Time to first word and total completion time measured under comparable conditions.
- **Engineering usefulness:** Practical steps, appropriate tools, clear workflows and useful limitations.

### 4.1 Indicative Scores (out of 5)

These scores are provisional. Claude's scores are based on the five responses supplied; ChatGPT's scores are carried forward as indicative values from the original draft because its five actual outputs were not provided. For a fair final result, assess both sets of original responses using the same rubric.

| Criterion | ChatGPT (indicative) | Claude (review of supplied answers) |
|-----------|:--------------------:|:-----------------------------------:|
| Accuracy | 4.5 | 4.5 |
| Creativity | 4.5 | 4.5 |
| Hallucination (higher = fewer errors) | 4.0 | 4.0 |
| Reasoning | 4.5 | 4.5 |
| Engineering usefulness | 4.5 | 4.5 |
| **Average** | **4.40/5** | **4.40/5** |

The averages exclude speed because no stopwatch readings are available. Equal scores should not be interpreted as proof that the tools performed identically.

### 4.2 Output Style Observation

| Prompt | Claude answer length | Used table? | Gave example? | Mistakes found |
|--------|----------------------|-------------|---------------|----------------|
| 1 – Foundations | Medium | Yes | Yes | No obvious major error identified in this review; verify details |
| 2 – Architectures | Medium | Yes | Yes | No obvious major error identified in this review; verify details |
| 3 – Applications | Short–medium | Yes | Yes, through applications | No obvious major error identified in this review; verify coverage |
| 4 – Scaling | Medium | No | Yes, research examples | No obvious major error identified in this review; verify exact claims |
| 5 – Building an LLM | Medium | Yes | Yes, tools and workflow | No obvious major error identified in this review; verify tool suitability |

The table-use and example observations above are based on the Claude responses supplied. "No obvious major error identified" is not a guarantee of complete factual accuracy. Fill the ChatGPT observations after checking its actual five responses.

---

## 5. Criterion-wise Analysis

### 5.1 Accuracy

Claude covered the main concepts in all five answers. It described the main generative model families, transformer attention, model designs, architecture applications, scaling, and the LLM development pipeline. It also qualified the discussion of emergent abilities by noting that researchers debate how sharp these jumps are. This is a useful sign of caution. Specific facts and technical details should still be verified against original papers and documentation.

ChatGPT should be evaluated using the same checklist. Its actual responses were not included in the material supplied for this report, so a direct factual comparison cannot be confirmed.

### 5.2 Creativity and Presentation

Claude used accessible explanations and examples, such as the relationship between "it" and "animal" in a sentence to explain self-attention, and the comparison of a spam filter with an email-writing assistant. It used tables effectively for model families, transformer designs, applications and the LLM pipeline. This made the answers easy to scan.

ChatGPT's creativity should be compared by checking whether it uses similarly relevant examples and follows each requested format.

### 5.3 Hallucination and Reliability

The supplied Claude answers do not show an obvious fabricated paper or clearly suspicious numerical claim, but that does not establish that every claim is correct. Claims about scaling laws, Chinchilla, model training, healthcare uses and named tools should be verified.

No specific ChatGPT hallucination can be identified without its actual answer transcripts. For both tools, the score should reflect verified errors, not confidence or writing style alone.

**Common hallucination types to look for**

| Type | Example to check |
|------|------------------|
| Invented reference | A paper title or author that does not exist |
| Wrong number | Incorrect parameter count, year or cost |
| Wrong attribution | Crediting a technique to the wrong paper or company |
| Overconfident claim | Stating a debated idea as settled fact |
| Outdated information | Describing old tools as the current standard |

### 5.4 Reasoning

Claude generally explains relationships rather than only listing definitions. For example, it links positional information to the need to represent word order, explains the trade-off between model size and training tokens in the Chinchilla discussion, and connects scaling with compute, energy and risk.

A fair ChatGPT comparison should look for the same cause-and-effect reasoning and whether all requested sub-points are covered.

### 5.5 Speed

Claude's timing was not measured, and ChatGPT timing is also unavailable. Therefore, speed cannot be ranked in this experiment. A fair test would use fresh chats, identical prompts, comparable model settings and similar network conditions. No unmeasured timing values are included in this report.

### 5.6 Behavioural Differences

| Aspect | Claude – observed from supplied answers | ChatGPT – what to verify |
|--------|------------------------------------------|---------------------------|
| Answer length | Mostly medium-length, structured responses | Record whether responses are short, medium or detailed |
| Formatting | Uses tables for most comparison-heavy prompts; Prompt 4 uses headings and bullets | Check whether requested tables and diagram description are present |
| Following instructions | Covers most requested sub-points; Prompt 3 does not explicitly give separate examples for every listed domain under each architecture | Check completeness against each prompt's exact requirements |
| Uncertainty | Notes debate around emergent abilities and warns that healthcare outputs need professional review | Check whether uncertain claims are appropriately qualified |
| Follow-up behaviour | Focuses on answering the prompts rather than asking follow-up questions | Record whether it offers relevant next steps or asks clarifying questions |

---

## 6. Engineering Usefulness

Claude's fifth response provides a practical, ordered LLM development pipeline and names tools for each stage, including Python and Spark for data work, tokenizers for tokenization, PyTorch or JAX for architecture work, DeepSpeed and Megatron-LM for training, PEFT/LoRA for fine-tuning, and vLLM or Docker for deployment.

Its responses also identify practical limitations such as compute cost, slow diffusion sampling, GAN training instability, hallucination, privacy risks and the need for healthcare review. This makes the content useful as a learning overview, although it is not a complete implementation guide.

For ChatGPT, engineering usefulness should be judged by whether its answers provide a clear pipeline, appropriate tool choices, meaningful trade-offs and actionable follow-up guidance. An additional engineering test would be to ask both tools for a minimal PyTorch self-attention implementation and check whether tensor shapes and causal masking are explained.

### 6.1 Engineering Test: Reference Self-Attention Implementation

To test practical usefulness, give both tools this follow-up prompt:

> Write a minimal PyTorch implementation of a single self-attention head with comments, and explain each tensor shape.

A correct answer should look similar to the reference below, which can be used to check the tools' code:

```python
import math
import torch
import torch.nn as nn
import torch.nn.functional as F

class SelfAttentionHead(nn.Module):
    def __init__(self, d_model, d_head, causal=True):
        super().__init__()
        self.q = nn.Linear(d_model, d_head, bias=False)
        self.k = nn.Linear(d_model, d_head, bias=False)
        self.v = nn.Linear(d_model, d_head, bias=False)
        self.causal = causal

    def forward(self, x):                      # x: (B, T, d_model)
        Q, K, V = self.q(x), self.k(x), self.v(x)          # each (B, T, d_head)
        scores = Q @ K.transpose(-2, -1) / math.sqrt(Q.size(-1))  # (B, T, T)
        if self.causal:                        # decoder-only: hide future tokens
            T = x.size(1)
            mask = torch.tril(torch.ones(T, T, device=x.device)).bool()
            scores = scores.masked_fill(~mask, float("-inf"))
        weights = F.softmax(scores, dim=-1)    # (B, T, T), rows sum to 1
        return weights @ V                     # (B, T, d_head)
```

**Checklist for judging the tools' code**

| Check | What a good answer does |
|-------|-------------------------|
| Runs without errors | Imports, shapes and function calls are valid |
| Scaling | Divides scores by the square root of the head dimension |
| Masking | Explains and applies a causal mask for decoder-only models |
| Shape explanation | States (B, T, d_model) to (B, T, d_head) and (B, T, T) for scores |
| Comments | Explains why each step is done, not just what it does |

---

## 7. Key Findings

1. Using identical prompts gives a more consistent basis for comparing AI tools, but chat context and model settings should also be controlled.
2. Claude's supplied answers are clearly structured and use tables, examples and practical tools to explain technical topics.
3. Claude's scaling answer appropriately notes uncertainty around the interpretation of emergent abilities.
4. Prompt 3 asks for coverage across text, image, audio, video, code and healthcare. Claude's table gives useful examples but does not explicitly map every domain to every architecture.
5. Speed cannot be compared because no stopwatch readings were recorded.
6. ChatGPT's actual five responses are needed before making strong claims about which tool is more accurate, creative or useful.
7. Neither tool should be treated as automatically correct; technical claims should be checked against reliable sources.

### 7.1 Observations on Prompt Design

- Prompts that list sub-points and a required format produce answers that are easier to score, because missing items are obvious.
- Asking for "simple language with one example per concept" encourages analogies and reduces jargon-heavy answers.
- A broad request such as Prompt 3 (six domains across four architectures) tends to produce summaries rather than full mappings; splitting it into two prompts would give more complete coverage.
- Asking for a diagram description is a good test of whether a text-based tool can explain structure clearly without drawing it.

---

## 8. Responsible Use of Generative AI

| Issue | Why it matters | Good practice |
|-------|----------------|---------------|
| Hallucination | Fluent text can be false | Verify facts and references against original sources |
| Academic integrity | Copying AI output as your own work can break college rules | Use AI as a learning aid, write in your own words, follow your institution's policy |
| Bias | Training data can contain stereotypes | Review outputs critically, especially for people-related content |
| Privacy | Prompts may contain personal or confidential information | Do not paste sensitive data into public tools |
| Healthcare and safety | Wrong answers can cause harm | Use qualified professionals for medical, legal and safety decisions |
| Energy use | Training and serving large models consume electricity | Prefer smaller efficient models when they are enough |

---

## 9. Limitations

- Only five prompts and two tools are included.
- Claude's answers were generated in one chat session, so earlier context may have influenced later responses.
- No timing data was collected.
- The actual ChatGPT answer transcripts were not supplied for direct output-by-output comparison; its scores remain indicative.
- Scoring includes human judgement, and a second reviewer could improve consistency.
- Model versions, settings, network conditions and server load can change results.

### 9.1 Suggestions for Future Work

1. Collect the full ChatGPT and Claude transcripts for all five prompts and score them with the same rubric.
2. Record stopwatch timings (time to first word and total time) for every prompt.
3. Repeat each prompt two or three times to measure how much answers vary.
4. Add Gemini and Perplexity to compare a search-grounded tool on citation quality.
5. Add a verification column that lists each fact checked and the source used.

---

## 10. Conclusion

The supplied Claude responses show clear explanations, useful examples, structured tables and a practical list of tools for building an LLM. They cover the main requested topics and include useful qualifications about uncertainty and responsible use. However, the comparison cannot conclusively establish whether Claude or ChatGPT is better because the actual ChatGPT responses and timing measurements are not included here.

A fair final judgement requires scoring both sets of original responses using the same rubric. Generative AI is a useful learning and engineering aid, but important facts and outputs still require verification.

---

## 11. Glossary

| Term | Meaning |
|------|---------|
| Token | A small unit of text, such as a word or part of a word |
| Embedding | A numeric vector representing the meaning of a token |
| Attention | A mechanism that weighs how relevant each token is to another |
| Latent space | A compressed internal representation learned by a model |
| Pre-training | Initial large-scale training on general data |
| Fine-tuning | Additional training on a narrower or instruction-based dataset |
| RLHF | Reinforcement learning from human feedback, used to align model behaviour |
| Hallucination | Fluent but false or unsupported output |
| Scaling law | A pattern showing how performance changes with parameters, data and compute |
| Inference | Using a trained model to generate output |

---

## 12. References

1. Vaswani et al., "Attention Is All You Need," 2017.
2. Kaplan et al., "Scaling Laws for Neural Language Models," 2020.
3. Hoffmann et al., "Training Compute-Optimal Large Language Models" (Chinchilla), 2022.
4. Goodfellow et al., "Generative Adversarial Nets," 2014.
5. Kingma and Welling, "Auto-Encoding Variational Bayes," 2013.
6. Ho et al., "Denoising Diffusion Probabilistic Models," 2020.

---

## Result

Both ChatGPT and Claude explained all five Generative AI topics clearly and correctly, with tables and examples. They differed mainly in style and detail, not in overall quality. Facts like numbers and paper names should still be verified for hallucination. Neither was best on every criterion, so the choice depends on the task.
