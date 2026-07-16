# Changelog

## 0.6.2-draft — 2026-07-16

- Rewrote the preface around the book's central progression from exact and
  approximate DP to offline approximation and online policy improvement.
- Reworked ``How to Read This Book'' with a five-question reading lens,
  terminology and evidence conventions, an updated chapter map, and routes for
  readers entering from control, AI/RL, or a mobility project.
- Prepared the syllabus-facing public distribution with aligned citation,
  rights, version, and landing-page metadata.

## 0.6.1-draft — 2026-07-15

- Selected the public subtitle, *Approximate Dynamic Programming,
  Reinforcement Learning, and Online Lookahead*, and aligned the PDF and
  citation metadata.
- Moved finite-action policy classification from the linear Q-feature
  subsection to the general policy-approximation architecture discussion.
- Clarified that the three Chapter 6 online-improvement mechanisms generate
  five execution patterns once the direct-actor baseline, safety-filter
  wrapper, and alternative actor-centered implementations are separated.
- Added rollout, MPC, and predictive-safety-filter provenance to the execution
  comparison table.
- Hid editorial chapter-status boxes in the public-facing build while retaining
  a source toggle for internal review.

## 0.6.0-draft — 2026-07-15

- Replaced the Chapter 6 placeholder with a substantive policy-space chapter
  covering supervised and rollout policy fitting, stochastic and deterministic
  policy gradients, actor--critic API, PPO, DDPG/TD3, SAC, and CEM.
- Made actor-as-base-policy/warm-start/local-search-center and
  critic-as-terminal-value the chapter's organizing link to online lookahead.
- Added a reproducible continuous-control experiment with CEM actor search,
  Monte Carlo critic fitting, model-shift audit, and one-/three-step online
  improvement.
- Added chapter-roadmap diagrams to Chapters 2, 3, and 5 and concept diagrams
  for DQN, PPO, TD3, and SAC to the extended-topics appendix.
- Reworked the Chapter 4 MC/TD experiment to show that its high one-step API
  cost matches exact PI's first intermediate policy and that repeated API
  approaches or reaches the optimum.

## 0.5.1-draft — 2026-07-15

- Reorganized Chapter 4 around an explicit optimality branch and an
  evaluation--improvement branch, and expanded approximate PI with uniform
  evaluation/improvement errors, asymptotic and converged-policy bounds, and a
  Chapter 5 geometric bridge.
- Expanded MC, TD($\lambda$), TD/LSTD/LSPE, Q-learning, Double DQN, dueling
  advantages, truncated rollout, and approximate LP with explicit equations,
  model-use classifications, and source provenance.
- Extended the lane-keeping experiment with exact PI and one-step MC/TD-based
  approximate PI; added a third generated figure and machine-readable API
  metrics.
- Added a self-contained DQN/PPO/TD3/SAC appendix bridge and a living homework
  and project-candidate file covering DQN, slalom, and multi-agent coordination.

## 0.5.0-draft — 2026-07-14

- Replaced the Chapter 4 placeholder with a substantive value-space chapter
  connecting fitted VI, MC/TD/LSTD evaluation, approximate PI, Q-learning,
  SARSA, DQN variants, rollout/lookahead, and approximate linear programming.
- Added a reproducible lane-keeping experiment that separates representation
  approximation from sampled Bellman approximation and audits learned policies
  against the declared finite model.
- Added explicit update equations for all five Chapter 3 optimizer families
  and positioned CNN, RNN, graph, and attention networks as alternative
  approximation architectures rather than separate DP algorithms.

## 0.4.1-draft — 2026-07-14

- Expanded Chapter 3 with an architecture map, explicit feature equations,
  feature-shape and MLP diagrams, target-error lineage, and optimization
  updates through minibatch Adam.
- Distinguished literature-derived claims from authorial validation guidance,
  defined one-step decision regret, and connected the constant-offset versus
  error-slope observation to Bertsekas (2019).
- Unified the car-following architecture names and redesigned its generated
  value-comparison figure to include all four models and the declared data
  split; repaired explicit LaTeX interpretation for colorbar labels.

## 0.4.0-draft — 2026-07-14

- Replaced the Chapter 3 placeholder with a substantive treatment of
  parametric approximation for values, Q-factors, policies, and models.
- Added an original, reproducible car-following experiment comparing
  quadratic, safety-aware, RBF, and shallow-neural value surrogates using both
  prediction and control-decision metrics.
- Added `EDITORIAL_CONTEXT.md` as the persistent record of author feedback to
  be enforced across subsequent chapters.

## 0.1.1-draft — 2026-07-14

- Increased the body size to 12pt and adopted Times-compatible text and math fonts.
- Fixed theorem-style and semantic cross-reference errors.
- Strengthened the finite-horizon bridge, LQR policy-loss proof, nominal-MPC
  shift theorem, and lateral-error-model derivation with explicit sources.
- Reordered Chapter 5 from unconstrained LQR examples to constrained MPC.
- Enlarged all generated-figure labels and added numerical regression checks.
- Established the cross-chapter notation policy and DRL integration map.
- Replaced “What Can Fail?” with “Design Conditions and Limitations.”

## 0.1.0-draft — 2026-07-01

- Created the KOMA-Script/LuaLaTeX textbook skeleton.
- Added the style guide, notation policy, design decisions, rights policy, and figure ledger.
- Added structural placeholders for the planned chapters and appendices.
- Added the pilot chapter, “LQR and MPC Through the DP Lens.”
- Added reproducible scalar Riccati and lateral-control figures.
