---
title: Projects
layout: page
permalink: /projects/
---

<h2>Personal Projects</h2>


<div class="card">
  <span class="card-title">&nbsp;libDNS</span>
  <div class="card-content">
    libDNS is a C header library I am building for building and parsing
    DNS requests and responses. The guiding principles for it are:

    <ul class="browser-default">
	<li>Simple</li>
	<li>Fast</li>
	<li>No dynamic allocation</li>
    </ul>

    The current goal is just to implement basic DNS resolving in
    accordance with RFC 1035 but I hope to extend is with DNS over
    HTTPS and DNSSEC in the future.

  </div>
  <div class="card-action">
    <strong>Language:</strong> C<br>
    <strong>Repo:</strong> <a href="https://github.com/nick96/dns-resolver">dns-resolver</a>
  </div>
</div>


<div class="card">
  <span class="card-title">&nbsp;Conway's Game of Life</span>
  <div class="card-content">
    Conyway's Game of Life is
    a <a href="https://en.wikipedia.org/wiki/Cellular_automaton">cellular
      automaton</a> with the following rules:

    <ul class="browser-default">
      <li>Any live cell with fewer than two live neighbours dies</li>
      <li>Any live cell with two or three live neighbours lives</li>
      <li>Any live cell with more than three live neightbours dies</li>
      <li>Any dead cell with exactly three live neighbors becomes a live cell</li>
    </ul>

    This rule set can produce some interesting patterns.

    I modelled the rule set using C++ and created two viewing
    interfaces.

    <ol>
      <li>Terminal view using the Ncurses library</li>
      <li>Graphical view using SFML</li>
    </ol>
  </div>

  <div class="card-action">
    <span><strong>Language:</strong> C++</span><br>
    <span><strong>Repo:</strong>
      <a class="browser-default" href="https://github.com/nick96/game-of-life">
	Game of Life
      </a>
    </span>
  </div>

</div>

<h2>Open-source Contributions</h2>

<div class="card">
</div>
