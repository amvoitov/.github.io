---
title: "Артефакт 2 — Story Map (MVP → v1 → v2)"
permalink: /artifacts/case_3/artifact_2/
---

<div class="d-flex flex-wrap justify-content-between align-items-center gap-2 mb-3">
  <a class="btn btn-outline-secondary btn-sm" href="{{ '/artifacts/case_3/' | relative_url }}">← К артефактам кейса</a>
  <a class="btn btn-outline-primary btn-sm" href="{{ '/projects/case_3/' | relative_url }}">К кейсу</a>
</div>

# Story Map (MVP → v1 → v2)

<div class="card shadow-sm mb-4">
  <div class="card-body text-muted">
    Сценарий работы платформы в виноградниках/садах: подготовка миссии → проход по ряду → опрыскивание → контроль/вмешательство → сервис и дозаправка.
  </div>
</div>

<div class="card border shadow-sm">
  <div class="card-body">
    <div class="table-responsive">
      <table class="table align-middle mb-0">
        <thead>
          <tr>
            <th style="width:260px;">Активность</th>
            <th>MVP</th>
            <th>v1</th>
            <th>v2</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td class="fw-semibold">A. Подготовить работу</td>
            <td class="text-muted">Маршрут на карте, запуск миссии</td>
            <td class="text-muted">Поддержка движения по ряду (сенсоры) — в плане</td>
            <td class="text-muted">Оценка “хватит ли химии на ряд” — в плане</td>
          </tr>

          <tr>
            <td class="fw-semibold">B. Двигаться по ряду</td>
            <td class="text-muted">Ручной / автопилот / маршрут на карте (работает в испытаниях)</td>
            <td class="text-muted">Камеры/ультразвук для рядов/препятствий — в плане</td>
            <td class="text-muted">Уточнение качества движения по данным датчиков — в плане</td>
          </tr>

          <tr>
            <td class="fw-semibold">C. Выполнять опрыскивание</td>
            <td class="text-muted">Бак/насос/форсунки/секции, управление нормой</td>
            <td class="text-muted">Связка с сенсорами рядов/препятствий — в плане</td>
            <td class="text-muted">Измерение расхода химии — в плане</td>
          </tr>

          <tr>
            <td class="fw-semibold">D. Контроль и вмешательство</td>
            <td class="text-muted">Web/планшет/мобильное</td>
            <td class="text-muted">Сигналы препятствий/границ — в плане</td>
            <td class="text-muted">Предиктивные уведомления по расходу/уровню — в плане</td>
          </tr>

          <tr>
            <td class="fw-semibold">E. Сервис</td>
            <td class="text-muted">Базовые процедуры обслуживания (описание в документации)</td>
            <td class="text-muted">Контроль датчиков/калибровки — в плане</td>
            <td class="text-muted">Метрики надёжности/простоев — TBD</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</div>
