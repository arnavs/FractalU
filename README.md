# FractalU: Computational and Behavioral Economics

I'm teaching a class on _computational, behavioral economics_. Details are below; signup link is [here]()

tl/dr
  - **Class**: Learn behavioral economics using math and code. Model and code up an economic/social situation you're interested in. 
  - **Instructor**: [Arnav Sood](https://arnavsood.com). I'm a 5th year Econ PhD student at [Carnegie Mellon](https://www.cmu.edu) and former open-source econ developer at [QuantEcon](https://quantecon.org). My thesis is on learning and deception involving "behavioral" (not strictly rational) economic agents.
  - **Time**: Tuesdays 7-9PM. 
  - **Duration**: 7 weeks, from 1.20.26 to 3.10.26 (skipping 2.17.26)
  - **Location**: Lower Manhattan (in-person only)
  - **Cost**: $120 (scholarship), $210 (standard), $300 (supporter). Send me an email at [`arnavs@alumni.cmu.edu`](mailto:arnavs@alumni.cmu.edu) if none of these work.

### Summary 

Over 7 weeks, we're going to use modern machinery (math and code) to explore behavioral economics. By the end, you'll have written a small interactive paper[^1] where you apply these tools to a problem you're interested in. 

"Economics" means that people are trying to maximize something, subject to some constraint. It may sound rigid (and we'll explore the limits), but this framework is already very permissive. People could be deciding: 
  * Whether or not to accept a job (or spouse), or wait for a better one tomorrow. 
  * How much lying they can get away with before reputation effects kick in and punish them. 
  * If it's best to follow the crowd, or act on their own beliefs. 
  * Whether they're comfortable living in a given neighborhood, or if they should move.

"Behavioral" means that people are not the [precisely rational creatures](https://en.wikipedia.org/wiki/Homo_economicus) required by neoclassical theory. They might [make mistakes](https://en.wikipedia.org/wiki/Trembling_hand_perfect_equilibrium) when carrying out their plans. They might not be perfect Bayesians (we'll discuss what that means), or they might face hard limits on the amount of information they can process. 

An increasingly large part of modern economics is realizing that these "behavioral frictions" aren't just small annoyances that we can model away. In many cases they lead to startlingly different behavior. 

But we can't see clearly what that behavior is by sticking to the "literary" economics of (say) Keynes. We need to model people mathematically, and then implement our models on a computer.  

### Requirements

You should have **some familiarity** with coding (but you don't need to work as a SWE or have majored in CS, for example.) Experience with math/stats and git/commandline is a plus, but not a requirement. **No prior economics experience is required**. 

You should be willing to learn and work hard. The course is fast-paced, and you'll get out what you put in. 

### Class Format 

Each class will be 1.5 hours of new material, followed by at least 0.5 hours of coworking and "office hours." (There's no hard stop after 0.5 hours.) We'll usually present the "standard model" of the topic first, and then the version with more realistic/complex behavior. 

Office hours are a good time to get help from me (and other students) on your individual projects. 

There will be homework, but no grades. 

Once everyone is registered, I'll add you all to this repo and make it private. The GitHub will be our main digital space/sandbox. 

After the class is over, anyone who wants to can remove their material or interim products, and I'll make it public again. 

### Syllabus 

Exact topics and order subject to change. **Don't worry if stuff in links seems too advanced**; it's just a reference.

| Class | Topic | Details and "Standard Model" | Alternatives
| -------- | ------- | ------- | ------- | 
| Week 1 (1.20.26) | Setup and tooling. Intro to Julia language. Math refresher. | N/A | Sparse max. 
| Week 2 (1.27.26) | Bayes, Nash, and beyond | Defining rationality and implications of Bayesian rationality. Writing a game formally and defining Nash equilibrium. | Cognitive distortions and "flaws" in updating. Trembles and "near-Nash" behavior.
| Week 3 (2.3.26) | Consumption and savings | [Neoclassical growth model](https://julia.quantecon.org/dynamic_programming/optgrowth.html). | Introducing info constraints, addictive goods, etc. 
| Week 4 (2.10.26)| Herds and learning from the crowd | Social learning with perfect recall and Bayesian agents. | Versions with bounded memory, deviant agents (overconfident, conformist, malicious), etc. 
| Week 5 **(2.24.26)** | Optimal stopping | [McCall search model](https://julia.quantecon.org/dynamic_programming/mccall_model.html). | Recency bias and imperfect recall. 
| Week 6 (3.3.26) | Persuasion, communication, and lying | Defining lying mathematically. Bayesian persuasion and cheap talk. | **My own research ("frequentist persuasion.'')** Hard limits on info processing and precision of communication. 
| Week 7 (3.10.26) | Special topics (TBD, based on class preferences.) | Racial discrimination. International development and growth. | 


[^1]: A bit on [what this means](https://paulromer.net/jupyter-mathematica-and-the-future-of-the-research-paper/), and an [example](https://github.com/QuantEcon/notebook-gallery/blob/main/ipynb/john_stachurski-coase.ipynb).