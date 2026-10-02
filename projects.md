---
title: Projects
layout: default
---

# Highlighted Projects &amp; Coursework

A selection of projects and coursework I've done across several domains.

<div class="entry-list">
  <div class="entry">
    <div class="entry-info">
      <div class="entry-title">Explainable Client Onboarding for Private Banking</div>
      <div class="entry-meta">ETH Data Analytics Club Datathon, Julius Bär challenge</div>
      <ul class="entry-desc">
        <li>In a 24-hour hackathon, we built a pipeline that combined explainable rules, the OpenAI API to turn free-text client forms into structured JSON, and a fine-tuned LLM as the final decision layer. We won the challenge.</li>
      </ul>
    </div>
    <div class="entry-date">2025</div>
  </div>
  <div class="entry">
    <div class="entry-info">
      <div class="entry-title">Agentic RAG for PDFs</div>
      <div class="entry-meta">Side project · <a href="https://github.com/JP-Amboage/llm-pdfs-qa">GitHub</a></div>
      <ul class="entry-desc">
        <li>A small project I built to get hands-on with agentic retrieval, inspired by LlamaIndex's post <a href="https://www.llamaindex.ai/blog/rag-is-dead-long-live-agentic-retrieval">"RAG is dead, long live agentic retrieval"</a>.</li>
        <li>A FastAPI service answers questions over uploaded PDFs and says so when the documents don't contain the answer. The embedding model and the LLM are swappable (OpenAI or Hugging Face), with a Chroma vector store and Docker deployment.</li>
      </ul>
    </div>
    <div class="entry-date">2025</div>
  </div>
  <div class="entry">
    <div class="entry-info">
      <div class="entry-title">Uncertainty in Nanopore Base Calling</div>
      <div class="entry-meta">Semester project · <a href="https://bmi.inf.ethz.ch/">Biomedical Informatics Group</a>, ETH Zürich · Supervised by André Kahles</div>
      <ul class="entry-desc">
        <li>Modified the greedy decoding of CTC-CRF base-calling models so that, besides the DNA sequence, they output a probability distribution over the four bases at each position. The decoding was implemened both in Python and Rust.</li>
        <li>Trained and compared 15 variants of the Bonito model (1–3 convolutional layers, 1–5 LSTM blocks) on accuracy, uncertainty and base-calling time. The LSTM blocks mattered most, and less accurate models were also less confident.</li>
      </ul>
    </div>
    <div class="entry-date">2024</div>
  </div>
  <div class="entry">
    <div class="entry-info">
      <div class="entry-title">Predicting Gene Expression from Histone Marks</div>
      <div class="entry-meta">Group course project · <a href="https://video.ethz.ch/lectures/d-infk/2024/autumn/263-5351-00L">Machine Learning for Genomics</a>, ETH Zürich · <a href="https://github.com/JP-Amboage/ml4g-P1">GitHub</a></div>
      <ul class="entry-desc">
        <li>Predicted gene expression in an unseen cell line from six histone-mark tracks around each gene's start site, using a 1D CNN trained on two other cell lines.</li>
      </ul>
    </div>
    <div class="entry-date">2024</div>
  </div>
  <div class="entry">
    <div class="entry-info">
      <div class="entry-title">Rocket Path Planning</div>
      <div class="entry-meta">Group course project · <a href="https://idsc.ethz.ch/education/lectures/PDM4AR.html">Planning and Decision Making for Autonomous Robots</a>, ETH Zürich</div>
      <ul class="entry-desc">
        <li>Implemented a planner that takes the environment description (planets, moving satellites, start, goal and other constraints) and computes a feasible trajectory for the rocket.</li>
        <li>Built it with successive convexification (SCvx), implemented on top of CVXPY with the ECOS solver.</li>
        <li>Evaluated on three scenarios of increasing difficulty, up to docking while dodging moving satellites.</li>
      </ul>
    </div>
    <div class="entry-date">2024</div>
  </div>
  <div class="entry">
    <div class="entry-info">
      <div class="entry-title">Autonomous Highway Driving</div>
      <div class="entry-meta">Group course project · <a href="https://idsc.ethz.ch/education/lectures/PDM4AR.html">Planning and Decision Making for Autonomous Robots</a>, ETH Zürich</div>
      <ul class="entry-desc">
        <li>Built a lane-change agent for a car in dense, reactive highway traffic, simulated with dg-commons on CommonRoad scenarios and evaluated on three scenarios of increasing difficulty.</li>
        <li>The car follows its lane with pure pursuit, slows down while a lidar-based gap check looks for space, and merges once the target lane is clear.</li>
      </ul>
    </div>
    <div class="entry-date">2024</div>
  </div>
  <div class="entry">
    <div class="entry-info">
      <div class="entry-title">Scripting Calculator</div>
      <div class="entry-meta">Course project · Compilers, University of Santiago de Compostela · <a href="https://github.com/JP-Amboage/scripting_calculator">GitHub</a></div>
      <ul class="entry-desc">
        <li>An interpreter for a small calculator language, written in C with Flex and Bison. It supports variables, script files and plugins loaded at runtime as shared libraries.</li>
      </ul>
    </div>
    <div class="entry-date">2022</div>
  </div>
  <div class="entry">
    <div class="entry-info">
      <div class="entry-title">Peer-to-Peer Chat</div>
      <div class="entry-meta">Course project · Distributed Computing, University of Santiago de Compostela · <a href="https://github.com/JP-Amboage/p2p-chat">GitHub</a></div>
      <ul class="entry-desc">
        <li>A chat app in Java where a central server handles accounts and friend requests (Java RMI, PostgreSQL in Docker), while messages go directly between clients. JavaFX interface.</li>
      </ul>
    </div>
    <div class="entry-date">2022</div>
  </div>
</div>
