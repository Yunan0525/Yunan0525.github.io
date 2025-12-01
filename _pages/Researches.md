---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
toc: false
---

<style>
/* Top local navigation bar */
.research-top-nav {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin: 10px 0 25px 0;
  padding: 10px 0;
  border-bottom: 1px solid #e0e0e0;
}

.research-top-nav a {
  padding: 6px 12px;
  border-radius: 999px;
  background: #f3f3f3;
  text-decoration: none;
  color: #333;
  font-size: 0.9rem;
  font-weight: 500;
  transition: background 0.2s, transform 0.1s;
}

.research-top-nav a:hover {
  background: #e0e0e0;
  transform: translateY(-1px);
}

/* Project cards: text left, figure right */
.project-card {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-between;
  gap: 24px;
  margin: 25px 0 35px 0;
  padding: 20px 22px;
  border-radius: 14px;
  background: #fafafa;
  box-shadow: 0 2px 10px rgba(0,0,0,0.06);
  border: 1px solid #e3e3e3;
}

.project-text {
  flex: 1.2;
  min-width: 260px;
}

.project-text h2 {
  font-size: 1.45rem;
  margin-top: 0;
  margin-bottom: 10px;
}

.project-text p {
  margin: 0 0 8px 0;
}

.project-text ul {
  margin-top: 6px;
}

/* Right-side figure */
.project-image {
  flex: 0.9;
  min-width: 220px;
  text-align: center;
}

.project-image img {
  width: 100%;
  max-width: 340px;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.10);
}

.project-image .caption {
  margin-top: 8px;
  font-size: 0.9rem;
  color: #666;
  font-style: italic;
}

/* Learn more button */
.learn-more-btn {
  display: inline-block;
  margin-top: 10px;
  padding: 6px 14px;
  border-radius: 999px;
  background: #0056b3;
  color: #ffffff !important;
  text-decoration: none;
  font-size: 0.9rem;
  font-weight: 500;
  transition: background 0.2s, transform 0.1s;
}

.learn-more-btn:hover {
  background: #003f82;
  transform: translateY(-1px);
}

/* Mobile: stack text and image vertically */
@media (max-width: 900px) {
  .project-card {
    flex-direction: column;
    align-items: flex-start;
  }
  .project-image {
    text-align: left;
  }
  .project-image img {
    max-width: 100%;
  }
}
</style>

<!-- Local navigation bar at the top -->
<nav class="research-top-nav">
  <a href="#rdc">Rationally Designed Consortia (RDC)</a>
  <a href="#lacto">Prebiotic-Driven Lactobacillus Dynamics</a>
  <a href="#mucus">Prebiotics & Intestinal Mucus Remodeling</a>
</nav>

---

<div id="rdc" class="project-card">
  <div class="project-text">
    <h2>🦠 Rationally Designed Consortia (RDC) to Prevent <i>C. difficile</i> Infection</h2>

    <p>
    The gut microbiome is a competitive ecosystem where timing, nutrient availability, and community structure shape colonization success. Our group engineered a Rationally Designed Consortium (RDC)—a defined, sequenced, and highly cohesive microbial community developed in prebiotic-fed bioreactors.
    </p>

    <p>
    Aging disrupts intestinal barrier integrity and weakens colonization resistance, increasing susceptibility to <i>C. difficile</i> infection (CDI). We found that GOS and hGOS create nutritional niches that enhance RDC persistence while suppressing <i>C. difficile</i> growth. In mouse models, GOS + RDC significantly reduced pathogen burden.
    </p>

    <p><b>Key goals:</b></p>
    <ul>
      <li>Test synbiotic (GOS/hGOS + RDC) protection across age groups</li>
      <li>Determine how prebiotics reshape microbial competition and nutrient use</li>
      <li>Develop mechanistic foundations for next-generation synbiotics for CDI prevention</li>
    </ul>
  </div>

  <div class="project-image">
    <img src="/images/research/study1.jpg" alt="Hypothesis: prebiotics + RDC for CDI prevention">
    <div class="caption">Working model of how prebiotic-conditioned RDC enhances colonization resistance against <i>C. difficile</i>.</div>
  </div>
</div>

---

<div id="lacto" class="project-card">
  <div class="project-text">
    <h2>🧬 Prebiotic-Driven Dynamics of <i>Lactobacillus</i> Co-Cultures</h2>

    <p>
    Probiotics such as <i>Lactobacillus</i> interact dynamically within microbial communities. 
    We examined how different carbohydrates—glucose, lactose, GOS, and our humanized GOS (hGOS)—shape the growth and competition of three fluorescently labeled strains: <b>LGG</b>, <b>AMC143</b>, and <b>L. plantarum</b> (Lp).
    </p>

    <p>
    Lp dominated co-cultures with fast growth rates in GOS and hGOS, while LGG and AMC143 grew more slowly. hGOS uniquely induced <i>nagB</i> upregulation in LGG, improving tolerance to lysozyme and mechanical stress. 
    These results reveal carbohydrate-specific competitive advantages and stress responses.
    </p>

    <p><b>Implications:</b></p>
    <ul>
      <li>Strain-specific metabolism shapes fitness and coexistence in co-culture</li>
      <li>Carbohydrate structure can be leveraged to tune probiotic function and resilience</li>
      <li>Findings guide synbiotic design for targeted microbial modulation</li>
    </ul>
  </div>

  <div class="project-image">
    <img src="/images/research/study2.jpg" alt="Lactobacillus co-culture study design">
    <div class="caption">Experimental design for fluorescently labeled <i>Lactobacillus</i> co-cultures across carbohydrate conditions.</div>
  </div>
</div>

---

<div id="mucus" class="project-card">
  <div class="project-text">
    <h2>🧫 How Prebiotics Remodel Intestinal Mucus and Barrier Function</h2>

    <p>
    The colonic mucus layer forms a critical barrier that separates microbes from the epithelium. Aging reduces mucus thickness and alters glycan composition, contributing to inflammation and increased susceptibility to pathogens.
    </p>

    <p>
    We investigate how GOS and hGOS regulate Muc2 production, mucus architecture, and O-glycan profiles using both in vitro (HT29-MTX, primary monolayers) and in vivo mouse models. Our work aims to determine how prebiotics enhance barrier integrity and facilitate beneficial bacteria colonization.
    </p>

    <p><b>Focus areas:</b></p>
    <ul>
      <li>Quantification of mucus secretion and goblet cell responses</li>
      <li>Changes in O-glycan motifs that support beneficial bacterial adhesion</li>
      <li>Mucus–microbiota spatial organization (histology + FISH)</li>
    </ul>

    <!-- Learn more button: replace the href with your real paper link -->
    <a class="learn-more-btn"
       href="https://your-paper-link-or-doi-here"
       target="_blank"
       rel="noopener">
      Learn more →
    </a>
  </div>

  <div class="project-image">
    <img src="/images/research/study3.jpg" alt="Goblet cells and mucus architecture">
    <div class="caption">Goblet cells and mucus architecture in prebiotic-treated aging models.</div>
  </div>
</div>
