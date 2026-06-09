---
layout: default
title: LIQCS 2026
subtitle: "1st International Workshop on Logic in Quantum Computer Science"
---

<link rel="stylesheet" href="/assets/css/program.css?v=3">

# LIQCS 2026
**Logic in Quantum Computer Science**

**17–19 June 2026**  
**Inria de Paris, Auditorium Jacques-Louis Lions (Building A, ground floor)**  
**48 Rue Barrault, Paris**

<a href="https://www.inria.fr/en/how-reach-us" class="btn-venue">
  Venue Information & Directions
</a>

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

.btn-venue {
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

.btn-venue:hover {
  background-color: #0366d6;
  color: #ffffff;
  text-decoration: none;
  border-color: #0366d6;
}

.btn-reg {
  display: inline-block;
  margin-top: 15px;
  padding: 8px 16px;
  background-color: #24292e;
  color: #ffffff !important;
  border: 1px solid #24292e;
  border-radius: 6px;
  font-weight: 600;
  text-decoration: none;
  font-size: 0.9em;
}

.btn-reg:hover {
  background-color: #2f363d;
  border-color: #2f363d;
  text-decoration: none;
}

.reg-note {
  font-size: 0.9em;
  color: #586069;
  margin-top: 10px;
  display: block;
}

.reg-deadline {
  color: #d73a49; 
  font-weight: 600;
  background-color: #ffeef0; 
  padding: 2px 4px;
  border-radius: 3px;
}
</style>

<div class="top-nav">
  <a href="#about">About</a>
  <a href="#schedule">Overall Schedule</a>
  <a href="#talks">Detailed Program</a>
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

<p>
  <a href="cfp.html">Call for Papers & Detailed Topics</a>
</p>

---

<p class="reg-note" style="font-size:1em;">
  <strong>Registration is now closed.</strong>
</p>

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
      <td class="talk"><a href="#session-4">Session 4</a></td>
      <td class="talk"><a href="#session-8">Session 8</a></td>
    </tr>

    <tr style="height:30px;">
      <td class="time-col coffee">10:30 - 11:00</td>
      <td class="coffee">Coffee Break</td>
      <td class="coffee">Coffee Break</td>
      <td class="coffee">Coffee Break</td>
    </tr>

    <tr style="height:90px;">
      <td class="time-col">11:00 - 12:30</td>
      <td class="talk"><a href="#session-1">Session 1</a></td>
      <td class="talk"><a href="#session-5">Session 5</a></td>
      <td class="talk"><a href="#session-9">Session 9</a></td>
    </tr>

    <tr style="height:90px;">
      <td class="time-col lunch">12:30 - 14:00</td>
      <td class="lunch">Lunch Break</td>
      <td class="lunch">Lunch Break</td>
      <td class="lunch">Lunch Break</td>
    </tr>

    <tr style="height:90px;">
      <td class="time-col">14:00 - 15:30</td>
      <td class="talk"><a href="#session-2">Session 2</a></td>
      <td class="talk"><a href="#session-6">Session 6</a></td>
      <td class="talk"><a href="#session-10">Session 10</a></td>
    </tr>

    <tr style="height:30px;">
      <td class="time-col coffee">15:30 - 16:00</td>
      <td class="coffee">Coffee Break</td>
      <td class="coffee">Coffee Break</td>
      <td class="empty"></td>
    </tr>

    <tr style="height:30px;">
      <td class="time-col">16:00 - 16:30</td>
      <td rowspan="2" class="talk"><a href="#session-3">Session 3</a></td>
      <td class="talk"><a href="#session-7">Session 7</a></td>
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

## Detailed Program {#talks}

{% assign days = "Wednesday,Thursday,Friday" | split: "," %}

{% for day in days %}

<div class="program-day">
  <h3>{{ day }}</h3>

  {% for session in site.data.program.sessions %}
    {% if session.day == day %}

      <div class="session-card" id="{{ session.id }}">

        <div class="session-header">
          <div class="session-title">
            {{ session.title }}
          </div>

          <div class="session-time">
            {{ session.start }} -- {{ session.end }}
          </div>
        </div>

        <div class="talk-list">

          {% for talk in session.talks %}

          <div class="talk-card" data-modal="modal-{{ talk.id }}">
            <div class="talk-title">
              {{ talk.title }}
            </div>

            <div class="talk-authors">
              {{ talk.authors | join: ", " }}
            </div>
          </div>

          {% endfor %}

        </div>
      </div>

    {% endif %}
  {% endfor %}

</div>

{% endfor %}


{% for session in site.data.program.sessions %}
  {% for talk in session.talks %}

  <dialog class="abstract-modal" id="modal-{{ talk.id }}">
    <div class="modal-content">

      <button class="modal-close">&times;</button>

      <div class="modal-title">
        {{ talk.title }}
      </div>

      <div class="modal-authors">
        {{ talk.authors | join: ", " }}
      </div>

      {% if talk.pdf %}
      <div class="modal-pdf">
        <a href="{{ talk.pdf }}" target="_blank">
           📄 Download extended abstract
        </a>
      </div>
      {% endif %}

      <div class="modal-abstract">
        {{ talk.abstract | markdownify }}
      </div>

    </div>
  </dialog>

  {% endfor %}
{% endfor %}

<script>
document.addEventListener('DOMContentLoaded', () => {

  document.querySelectorAll('.talk-card').forEach(card => {
    card.addEventListener('click', () => {
      const modalId = card.dataset.modal;
      const modal = document.getElementById(modalId);

      if (modal) {
        modal.showModal();
      }
    });
  });

  document.querySelectorAll('.modal-close').forEach(button => {
    button.addEventListener('click', () => {
      button.closest('dialog').close();
    });
  });

  document.querySelectorAll('dialog').forEach(dialog => {
    dialog.addEventListener('click', (event) => {
      const rect = dialog.getBoundingClientRect();
      const inside = (
        event.clientX >= rect.left &&
        event.clientX <= rect.right &&
        event.clientY >= rect.top &&
        event.clientY <= rect.bottom
      );

      if (!inside) {
        dialog.close();
      }
    });
  });

});
</script>


---

## Organisers and PC Chairs {#organisers}

- [Alejandro Díaz-Caro](https://members.loria.fr/ADiazCaro/)
- [Romain Péchoux](https://members.loria.fr/RPechoux/)
- [Benoît Valiron](https://www.monoidal.net/)
- [Vladimir Zamdzhiev](https://zamdzhiev.github.io/)

---

## Program Committee {#pc}

- [Kostia Chardonnet](https://kostiachardonnet.github.io/)
- [Ugo Dal Lago](https://udallago.github.io/)
- [Kinnari Dave](https://www.au.dk/en/kinnari.dave@cs.au.dk)
- [Alejandro Díaz-Caro](https://members.loria.fr/ADiazCaro/)
- [Claudia Faggian](https://www.irif.fr/~faggian/)
- [Emmanuel Hainry](https://members.loria.fr/ehainry/)
- [Chris Heunen](https://homepages.inf.ed.ac.uk/cheunen/)
- [Octavio Malherbe](https://scholar.google.com/citations?user=1G5UzkMAAAAJ)
- [Romain Péchoux](https://members.loria.fr/RPechoux/)
- [Peter Selinger](https://www.mathstat.dal.ca/~selinger/)
- [Sam Staton](https://www.cs.ox.ac.uk/people/samuel.staton/main.html)
- [Takeshi Tsukada](https://takeshi-tsukada.github.io/)
- [Benoît Valiron](https://www.monoidal.net/)
- [Vladimir Zamdzhiev](https://zamdzhiev.github.io/)

