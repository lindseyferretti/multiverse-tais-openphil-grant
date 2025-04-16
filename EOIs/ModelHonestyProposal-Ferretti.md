**Name:** Lindsey Ferretti

**Contact Email:** lindsey.ferretti@gmail.com

**URL for Google Scholar, Linkedin profile, or other online presence:**
https://www.linkedin.com/in/lindseyferretti/

**Would you like to share information about any collaborators you plan to work with?**
- [x] Yes
- [ ] No

---
**If yes, please list each collaborator on a separate line.** 
>For each one, separate their info with commas: Name, role, and optionally, email and URL to online presence.

TBD, members of the Multiverse School research team (https://themultiverse.school/).

---
#### What kind of costs are you applying to fund?
> We plan to expedite the review of grants that only fund research expenses. By research expenses we mean e.g. cloud GPUs, OpenAI API credits, stipends for human subjects, etc. Travel costs and equipment purchases (e.g. laptops) count as incidentals, not research expenses. 

- [x] Research expenses only
- [ ] Research expenses, salaries, incidentals, etc.

---
#### Is this proposal for an academic grant?
> I.e. would the main recipient of grant funds be a university?

- [ ] Academic grant
- [x] Non-academic grant

---
#### For which research area(s) does your project fit the eligibility criteria?
> We strongly encourage you to review our RFP, which describes distinct research aims and eligibility criteria for each research area. 
> Feel free to select multiple areas, if your project would be eligible under several.

- [ ] Jailbreaks and unintentional misalignment
- [ ] Black-box LLM psychology
- [ ] Alternatives to adversarial training
- [ ] Robust unlearning
- [x] Activation monitoring
- [x] Experiments on alignment-faking
- [x] Control evaluations
- [ ] Backdoors and other alignment stress-tests
- [x] Encoded reasoning in CoT and inter-model communication
- [ ] Evaluating whether models can hide dangerous behaviors
- [ ] Externalizing reasoning
- [ ] Reward hacking of human oversight
- [ ] Applications of mechanistic interpretability
- [ ] White-box estimation of rare misbehavior 
- [ ] Finding feature representations
- [ ] Toy models for interpretability
- [ ] Interpretability benchmarks
- [ ] Theoretical study of inductive biases
- [ ] Conceptual clarity about risks from powerful AI
- [ ] Developing more transparent paradigms
- [ ] New moonshots for superalignment
- [ ] None of the above

---
#### Short project name (Maximum: 7 words)
> There will be an opportunity to add a longer description later. This question just helps us refer to the proposal internally.

Evaluating Honesty in Language Models

---
#### Project overview (Maximum: 300 words)
> What is your project, in one sentence?

We propose to develop methods for detecting dishonest behavior in language models, even when ground-truth accuracy is unavailable. Building on the 2025 MASK Benchmark, we will evaluate and improve three promising avenues:
(1) Belief consistency testing, probing for internal belief contradictions under adversarial prompts;
(2) Truth representation probing, using techniques like contrast-consistent search and linear probes to surface latent honesty-related activations;
(3) Chain-of-thought (CoT) faithfulness, identifying when generated rationales deviate from a model’s internal computation.

Additionally, we will test the robustness of these techniques against jailbreaks, multi-agent deception, and reward hacking scenarios. Our goal is to produce scalable methods for honesty evaluation in frontier models and provide the empirical foundations for honesty-aware alignment interventions. 

---
#### What specific actions are you and/or your collaborators planning to do as part of this project? Concrete descriptions of experiments or questions you hope to answer are especially helpful. How will you measure success?
> What research outputs will this project generate, if successful? What impact would those outputs have?

Our research will contribute tools and evaluation protocols that can scale to frontier models and multimodal systems. Particular attention will be paid to distinguishing hallucination from deception and characterizing model uncertainty through confidence-aware prompting. We expect this project to yield actionable metrics for scalable oversight and inform alignment strategies that focus on model honesty under pressure.

Potential success metrics include: 
- Honesty Detection Accuracy: Classification accuracy in distinguishing honest vs. dishonest responses on curated and adversarial datasets.
- Pressure Robustness Gap: Difference in model honesty between neutral and adversarial prompting conditions.
- Intervention Effectiveness: Pre/post intervention comparison using honesty probes on known deception tasks.
- Scalability to Frontier Models: Ability to reproduce detection methods on large-scale models by applying methods to at least one open-weight LLM and one API frontier model.
- False Positive/Negative Rate in Hallucination vs. Deception: Precision and recall of tools in distinguishing honest mistakes from deliberate dishonesty.
- Cross-task Generalization: Evaluate whether trained honesty detectors generalize to unseen tasks or domains (e.g., legal vs. medical QA).

---
#### Is your project well-described by any of the specific [example projects](https://www.openphilanthropy.org/tais-rfp-research-areas/) we mentioned in our RFP? If so, which? If not, feel free to leave this box blank. (Maximum: 100 words)

Yes, this project overlaps with “Encoded reasoning in CoT and inter-model communication” by probing how models might embed deceptive reasoning steps within internal or cross-model dialogue. It also directly builds on “Experiments on alignment faking” by testing when and how models produce statements inconsistent with their internal beliefs under adversarial conditions.

---
#### If you selected “None of the above” earlier, please describe how your project contributes to the goal of developing techniques to make the advanced AIs of the future more safe, aligned, controlled, trustworthy, etc. (Maximum: 300 words)
> As a reminder, we are less likely to fund projects that fall outside of our list of research areas.

---
#### Estimated budget range
> This should be a **very rough** estimate, and doesn't require additional explanation e.g. “$100,000 to $500,000". 
> Spending a minute thinking “What’s the most that this could realistically cost?” and “What’s the least that this could realistically cost?” then writing down both numbers is sufficient.

$200,000 to $400,000

---
**About the confidentiality of your application**
> By checking the box below, you agree that we may share your application with our outside advisors for evaluation purposes, and with other potential funders who may be interested in supporting your work.
- [x] Agree

---
**How did you hear about this RFP?**
- [ ] Twitter
- [ ] Word of mouth
- [ ] Article/blog post
- [ ] Newsletter
- [ ] Email from Open Philanthropy
- [x] Other

---
**Please provide further details**
> e.g. The name of the person whose twitter or blog you heard about this RFP through.

Through AI safety research discussions facilitated at the Multiverse School (https://themultiverse.school/).
