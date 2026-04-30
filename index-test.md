---
layout: default
title: LIQCS 2026
subtitle: "1st International Workshop on Logic in Quantum Computer Science"
---

# LIQCS 2026  
**Logic in Quantum Computer Science**  
**17–19 June 2026 – Inria de Paris, 48 Rue Barrault**

<style>
.navbar {
  display: none;
}

.top-nav {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;

  margin: 20px 0 30px 0;
  padding: 10px;

  border-bottom: 1px solid #ddd;
  border-radius: 8px;

  position: sticky;
  top: 0;
  background: white;
  z-index: 1000;

  box-shadow: 0 2px 4px rgba(0,0,0,0.05);
}

.top-nav a {
  text-decoration: none;
  color: #0366d6;
  font-size: 0.95em;
}

.top-nav a:hover {
  text-decoration: underline;
}

.btn-cfp {
  display: inline-block;
  margin-top: 15px;
  padding: 8px 16px;
  background-color: #f6f8fa;
  color: #0366d6;
  border: 1px solid #d1d5da;
  border-radius: 6px;
  font-weight: 500;
  text-decoration: none;
  font-size: 0.9em;
}

.btn-cfp:hover {
  background-color: #0366d6;
  color: #ffffff;
  text-decoration: none;
  border-color: #0366d6;
}
</style>

<div class="top-nav">
  <a href="#about">About</a>
  <a href="#schedule">Schedule</a>
  <a href="#talks">Accepted talks</a>
  <a href="#venue">Venue</a>
  <a href="#organisers">Organisers</a>
  <a href="#pc">PC</a>
</div>


## About LIQCS {#about}

**LIQCS** is a workshop dedicated to the logical and mathematical foundations of
quantum computer science.  
Its goal is to bring together researchers working on rigorous frameworks for
quantum computation, including logic, type theory,
semantics, algebraic and categorical methods, and formal verification.

The workshop welcomes contributions presenting new ideas, work in progress,
recently published results, and perspectives on emerging research directions.

<a href="cfp.html" class="btn-cfp">View Call for Papers & Detailed Topics</a>

---

## Schedule {#schedule}

<style>
  .schedule-wrapper {
    overflow-x: auto;
    margin: 20px 0;
  }

  .schedule-table {
    border-collapse: collapse;
    width: 100%;
    min-width: 700px;
    table-layout: fixed;
    font-size: 0.95em;
  }

  .schedule-table th,
  .schedule-table td {
    text-align: center;
    vertical-align: middle;
    border: 1px solid #ddd;
    padding: 6px;
    transition: background 0.2s ease;
  }

  .schedule-table th {
    background: #000;
    color: #fff;
    font-weight: 600;
  }

  .time-col {
    background: #f5f5f5;
    font-weight: 500;
    width: 18%;
  }

  .day-col {
    width: 27%;
  }

.schedule-table tr:nth-child(even),
.schedule-table tr:nth-child(odd) {
  background: transparent !important;
}

.empty { background: #fff; }

.talk { background: #d9ead3; }
.coffee { background: #fff2cc; }
.lunch { background: #fce5cd; }
.meeting { background: #d0e0e3; }


</style>

<div class="schedule-wrapper">
<table class="schedule-table">
  <thead>
    <tr>
      <th class="time-col">Time Slot</th>
      <th class="day-col">Wednesday (17/06)</th>
      <th class="day-col">Thursday (18/06)</th>
      <th class="day-col">Friday (19/06)</th>
    </tr>
  </thead>
  <tbody>

    <tr style="height:90px;">
      <td class="time-col">09:00 - 10:30</td>
      <td class="empty"></td>
      <td class="talk">3 talks</td>
      <td class="talk">3 talks</td>
    </tr>

    <tr style="height:30px;">
      <td class="time-col coffee">10:30 - 11:00</td>
      <td class="coffee">Coffee Break</td>
      <td class="coffee">Coffee Break</td>
      <td class="coffee">Coffee Break</td>
    </tr>

    <tr style="height:90px;">
      <td class="time-col">11:00 - 12:30</td>
      <td class="talk">3 talks</td>
      <td class="talk">3 talks</td>
      <td class="talk">3 talks</td>
    </tr>

    <tr style="height:90px;">
      <td class="time-col lunch">12:30 - 14:00</td>
      <td class="lunch">Lunch Break</td>
      <td class="lunch">Lunch Break</td>
      <td class="lunch">Lunch Break</td>
    </tr>

    <tr style="height:90px;">
      <td class="time-col">14:00 - 15:30</td>
      <td class="talk">3 talks</td>
      <td class="talk">3 talks</td>
      <td class="talk">3 talks</td>
    </tr>

    <tr style="height:30px;">
      <td class="time-col coffee">15:30 - 16:00</td>
      <td class="coffee">Coffee Break</td>
      <td class="coffee">Coffee Break</td>
      <td class="empty"></td>
    </tr>

    <tr style="height:30px;">
      <td class="time-col">16:00 - 16:30</td>
      <td rowspan="2" class="talk">3 talks</td>
      <td class="talk">1 talk</td>
      <td class="empty"></td>
    </tr>

    <tr style="height:60px;">
      <td class="time-col">16:30 - 17:30</td>
      <td class="meeting">Business Meeting</td>
      <td class="empty"></td>
    </tr>

  </tbody>
</table>
</div>

---

## Accepted Talks {#talks}

- *What are quantum measurable spaces?* Tobias Fritz and Antonio Lorenzin.
- *Resource-Aware Quantum Programming with General Recursion and Quantum Control.* Thomas Vinet, Kostia Chardonnet, Emmanuel Hainry, and Romain Péchoux.
- *Basis-Sensitive Quantum Typing via Realizability.* Alejandro Díaz-Caro, Octavio Malherbe, and Rafael Romero.
- *Quantum Control and General Recursion beyond the Unitary Case.* Kathleen Barsse, Romain Péchoux, and Simon Perdrix.
- *An Algebraic Extension of Intuitionistic Linear Logic: the L-S-!-Calculus and Its Categorical Model.* Alejandro Díaz-Caro, Malena Ivnisky, and Octavio Malherbe.
- *Quantum Coherence Spaces Revisited: A von Neumann (Co)Algebraic Approach.* Thea Li and Vladimir Zamdzhiev.
- *Higher-order circuits.* Matt Wilson.
- *Higher-order quantum objects are strong profunctors.* Matt Wilson and James Hefford.
- *BV-Categories of Spacetime Interventions.* Matt Wilson and James Hefford.
- *Static Resource Analysis of Hybrid Programs with Unbounded Loops.* Jad Issa, Christophe Chareton, and Romain Péchoux.
- *Higher order maps in operational probabilistic theories.* Alessandro Bisio, Luca Apadula, Marco Erba, and Paolo Perinotti.
- *Denotational semantics for stabiliser quantum programs.* Robert Booth and Cole Comfort.
- *Graphical Algebraic Geometry: From Ideals and Varieties to Qudit ZH Completeness.* Dichuan Gao, Razin A. Shaikh, and Aleks Kissinger.
- *Quantum Bayesian Networks: Compositionality and Typing via Linear Logic.* Rémi Di Guardia, Thomas Ehrhard, and Claudia Faggian.
- *One rig to control them all.* Chris Heunen, Robin Kaarsgaard, and Louis Lemonnier.
- *Towards a New Logic for Higher Order Quantum Computation.* Julien Lamiroy.
- *Programming with Quantum-Controlled Quantum Channels.* Kengo Hirata and Takeshi Tsukada.
- *Finite Observations, Infinite Behaviour: categorical semantics for stateful quantum processes.* Cole Comfort and Giovanni de Felice.
- *Noncommutative models of quantum computing.* Bert Lindenhovius.
- *Completeness Is Not Enough: Simpler Presentations and Minimality for Near-Clifford Circuit Fragments.* Colin Blake.
- *A Complete and Natural Rule Set for Multi-Qudit Clifford Circuits in All Odd Prime Dimensions.* Xiaoning Bian, Sarah Meng Li, Neil J. Ross, John van de Wetering, and Yuming Zhao.
- *Quantum instruments are a quantum effect monad.* Robert I. Booth, Dominik Leichtle, Alex Rice and Kim Worrall.
- *Polynomial Spectral Semantics for Magic-State Distillation.* Dongho Lee.
- *Quantum Programming in Polylogarithmic Time.* Florent Ferrari, Emmanuel Hainry, Romain Péchoux, and Mário Silva.
- *Towards Quantum Inference on Higher-Order Bayesian Networks.* Jérôme Evrard, Claudia Faggian, Giacomo Gatti, and Gabriele Vanoni.
- *Structure and geometry complete completeness.* Chris Heunen, Nicolas Heurtel, Robin Kaarsgaard, and Louis Lemonnier.
- *Symbolic Verification of Quantum Protocols via Quantum Distributions -- Early Ideas.* Gabriele Tedeschi, Lorenzo Ceragioli, Giuseppe Lomurno, and Fabio Gadducci.
- *Operator Spaces, Linear Logic and the Heisenberg-Schrödinger Duality of Quantum Theory.* Bert Lindenhovius and Vladimir Zamdzhiev.

---

## Venue {#venue}

**Inria de Paris**  
**Auditorium Jacques-Louis Lions (Building A, ground floor)**  
**48 Rue Barrault, Paris**

Information on access, accommodation and local logistics will be added later.


---

## Organisers and PC Chairs {#organisers}

- [Alejandro Díaz-Caro](https://members.loria.fr/ADiazCaro/)
- [Romain Péchoux](https://members.loria.fr/RPechoux/)
- [Benoît Valiron](https://www.monoidal.net/)
- [Vladimir Zamdzhiev](https://zamdzhiev.github.io/)

---

## Program Committee {#pc}

- Kostia Chardonnet
- Ugo Dal Lago
- Kinnari Dave
- Alejandro Díaz-Caro
- Claudia Faggian
- Emmanuel Hainry
- Chris Heunen
- Octavio Malherbe
- Romain Péchoux
- Peter Selinger
- Sam Staton
- Takeshi Tsukada
- Benoît Valiron
- Vladimir Zamdzhiev

