---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
# To see the site locally:
# Run
# To view changes run: bundle exec jekyll serve
#layout: home
---


<div class="example-container" style="border: 2px solid #ddd; border-radius: 8px; padding: 20px; margin: 20px 0; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
  <div style="text-align: center;">
    <img src="/assets/WicksTheoremScreenShot.png"
         alt="Screenshot of Wick's theorem implementation in PhysLean"
         style="width: 100%; height: auto; border-radius: 4px;">
    <p style="margin-top: 10px; font-style: italic; color: #666;">
      The above screenshot demonstrates how theorems are formalized in PhysLean.
    </p>
  </div>
</div>

# 1. What is Lean? 

Lean is a computer programming language in a class of languages 
called interactive theorem provers (ITP). In an ITP one can write down mathematical definitions, 
theorems and proofs, and the ITP will ensure mathematical correctness and consistency of 
those things.  It does this using a mathematical foundation called type theory. 

Lean is increasingly being used by AI companies to reason about, and prove mathematical theorems. 

# 2. Mission of PhysLean

To create a library of digitalized physics results in the theorem prover Lean 4, 
in a way which is useful to the broad physics community.


# 3. Vision of PhysLean

**Statement**: PhysLean aspires to be the definitive library for physics in Lean, 
akin to Mathlib for mathematics,
with both the Lean and physics communities behind it and a potential formal collaboration.

**Detailed Vision**:
- A comprehensive repository containing fundamental definitions, theorems, and calculations from physics.
- An interface between experimental data, simulations, and formal theoretical frameworks.
- Extensive, physics-focused documentation to support adoption.
- Accessibility for physicists at all levels, including and especially to those new to formal methods.
- An intuitive set-up that aligns with the way physicists think and work.
- A large and active team, with the potential for structured, high-energy physics-style collaborations.

# 4. Values of PhysLean
The three core values of PhysLean are:

- *Welcoming*:  PhysLean strives to foster an environment where contributors of all academic backgrounds and experience levels feel valued, supported, and empowered to make meaningful contributions.
- *Open and Transparent*: PhysLean and its outputs will always be openly accessible, freely available, and developed with transparency to benefit the broader physics and Lean communities.
- *Accessibility and Practicality*: PhysLean is designed to be intuitive, well-documented, and directly useful to physicists, regardless of their familiarity with formal methods.

# 5. Potential impact of the PhysLean

PhysLean has the potential to have the following impact on the physics community:
- Make it easier to find results.
- Make it easier to automate the creation of new results using, e.g., machine learning methods.
- Make it easier to check papers and results for mathematical correctness.
- Create new avenues through which physics can be taught.
- Open up new ways to interface between theory and computer programs.

# 6. Beneficiaries of the project 

The beneficiaries of PhysLean are those people or companies which will directly or indirectly 
benefit from the project. 

We foresee the *academic* beneficiaries of PhysLean including: 
- Students in physics, mathematics, or computer science.
- Research physicists. 
- Researchers in artificial intelligence. 

We foresee the *industrial* beneficiaries of PhysLean including: 
- Companies with an interest in artificial intelligence and its use in reasoning. 
- Companies with an interest in proving correctness of theory behind physical processes.  

# 7. Benefits of a monolithic library 

PhysLean is a monolithic library for physics, similar to how Mathlib serves mathematics. It aims to cover the entire field of physics within a single, unified framework. Here are some key motivations for adopting a monolithic approach:
- **Prevents duplication of work**: A single, comprehensive library ensures that contributors don’t waste effort reinventing the wheel.
- **Facilitates shared improvements**: When everyone works within the same library, enhancements to one part can be easily propagated to others.
- **Simplifies maintenance**: A unified library keeps everything up to date together. Individual contributors don’t have to manually update their code to stay compatible with new versions of Mathlib or other dependencies—that responsibility is shared by the community.
- **Encourages standardization**: A single library fosters consistency in notation, conventions, and methodology, reducing fragmentation in the ecosystem. 
- **Improves discoverability and usability**: With all physics in one place, users can more easily find and apply existing results rather than searching through scattered libraries.

# 8. Where to learn more

You can learn more about PhysLean by reading: [2405.08863](https://inspirehep.net/literature/2787050), or contacting [Joseph Tooby-Smith](https://josephtoobysmith.com).
