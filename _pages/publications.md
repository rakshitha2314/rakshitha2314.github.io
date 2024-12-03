---
permalink: /publications/
title: "Publications"
---

<div class="publication-list">
  <div class="publication">
    <h3 class="publication-title">
       <a href="https://doi.org/10.48550/arXiv.2411.19881" target="_blank">EF1 Allocations for Identical Trilean and Separable Single-Peaked Valuations </a>
      <span class="status">[Under Review]</span>
    </h3>
    <p class="authors"><strong>Authors:</strong> Umang Bhaskar, Gunjan Kumar, Yeshwant Pandit, Rakshitha</p>
    <button class="toggle-abstract" onclick="toggleAbstract('abstract1', this)">View Abstract</button>
    <div id="abstract1" class="abstract-content hidden">
      <p>In the fair division of items among interested agents, envy-freeness is possibly the most favoured
and widely studied formalisation of fairness. For indivisible items, envy-free allocations may not
exist in trivial cases, and hence research and practice focus on relaxations, particularly envy-freeness
up to one item (EF1), which allows the removal of an item to resolve envy. A significant reason
for the popularity of EF1 allocations is its simple fact of existence, which supports research into
combining EF1 with other properties such as efficiency, or research into stronger properties such as
ex-ante envy-freeness. It is known that EF1 allocations exist for two agents with arbitrary valuations;
agents with doubly-monotone valuations; agents with Boolean valuations; and identical agents with
negative Boolean valuations. In fact the last two results were shown for the more stringent EFX
fairness requirement.
We consider two new but natural classes of valuations, and partly extend results on the existence
of EF1 allocations to these valuations. Firstly, we consider trilean valuations — an extension of
Boolean valuations — when the value of any subset is 0, a, or b for any integers a and b. Secondly,
we define separable single-peaked valuations, when the set of items is partitioned into types. For
each type, an agent’s value is a single-peaked function of the number of items of the type. The value
for a set of items is the sum of values for the different types. We prove EF1 existence for identical
trilean valuations for any number of agents, and for separable single-peaked valuations for three
agents. For both classes of valuations, we also show that EFX allocations do not exist.</p>
    </div>
  </div>
  <hr>
</div>

<style>
/* General Page Styling */
body {
  /* font-family: 'Georgia', serif; */
  line-height: 1.6;
  color: #333333;
  background-color: #f9f9f9;
  margin: 0;
  padding: 0;
}

.publication-list {
  max-width: 800px;
  margin: 50px auto;
  padding: 0 20px;
}

.publication {
  margin-bottom: 20px;
}

.publication-title {
  font-size: 18px;
  margin: 0 0 5px;
  color: #222222;
}

.status {
  font-size: 14px;
  color: #888888;
  font-style: italic;
}

.authors {
  margin: 5px 0 10px;
  font-size: 15px;
  color: #555555;
}

.toggle-abstract {
  background-color: transparent;
  color: #555555;
  border: 1px solid #cccccc;
  padding: 6px 12px;
  font-size: 14px;
  border-radius: 4px;
  cursor: pointer;
  transition: background-color 0.3s ease, color 0.3s ease, border-color 0.3s ease;
}

.toggle-abstract:hover {
  background-color: #f1f1f1;
  color: #222222;
  border-color: #999999;
}

.abstract-content {
  margin-top: 10px;
  font-size: 15px;
  color: #444444;
  line-height: 1.6;
  display: none; /* Hidden by default */
  border-left: 3px solid #dddddd;
  padding-left: 10px;
}

.abstract-content.show {
  display: block; /* Ensure content is shown when toggled */
}

hr {
  border: 0;
  border-top: 1px solid #dddddd;
  margin: 20px 0;
}
</style>

<script>
function toggleAbstract(abstractId, button) {
  const abstract = document.getElementById(abstractId);

  // Toggle display of abstract content
  if (abstract.classList.contains("hidden")) {
    abstract.classList.remove("hidden");
    abstract.classList.add("show");
    button.innerText = "Hide Abstract";
  } else {
    abstract.classList.remove("show");
    abstract.classList.add("hidden");
    button.innerText = "View Abstract";
  }
}
</script>