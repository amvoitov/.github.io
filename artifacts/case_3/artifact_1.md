---
title: "Артефакт 1 — North Star и KPI-дерево"
permalink: /artifacts/case_3/artifact_1/
---

<div class="d-flex flex-wrap justify-content-between align-items-center gap-2 mb-3">
  <a class="btn btn-outline-secondary btn-sm" href="{{ '/artifacts/case_3/' | relative_url }}">← К артефактам кейса</a>
  <a class="btn btn-outline-primary btn-sm" href="{{ '/projects/case_3/' | relative_url }}">К кейсу</a>
</div>

# North Star и KPI-дерево

<div class="alert alert-light border">
  <strong>Важно:</strong> метрики ниже — модель для управления продуктом и испытаниями.
  Часть показателей (точность дозирования/перекрытия/надёжность) пока без численных целей.
</div>

## North Star Metric (NSM)
<div class="card shadow-sm mb-4">
  <div class="card-body">
    <div class="fw-semibold mb-1">“Эффективно обработанная площадь за смену”</div>
    <div class="text-muted">
      Площадь (га), обработанная с заданными режимами, при соблюдении требований безопасности и без критических простоев.
    </div>
  </div>
</div>

## KPI-дерево (драйверы)
<div class="card border shadow-sm">
  <div class="card-body">
    <div class="table-responsive">
      <table class="table align-middle mb-0">
        <thead>
          <tr>
            <th style="width:220px;">Ветка</th>
            <th>Метрика</th>
            <th style="width:220px;">Цель/диапазон</th>
            <th>Комментарий</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td class="fw-semibold">Производительность</td>
            <td>Площадь за час</td>
            <td><strong>1 га/час</strong></td>
            <td class="text-muted">Базовая метрика эффективности выполнения работ.</td>
          </tr>

          <tr>
            <td class="fw-semibold">Автономность</td>
            <td>Время работы без “критической остановки”</td>
            <td><strong>10 часов</strong></td>
            <td class="text-muted">Ограничение для сменной работы/логистики.</td>
          </tr>

          <tr>
            <td class="fw-semibold">Динамика движения</td>
            <td>Скорость движения</td>
            <td><strong>1–10 км/ч</strong></td>
            <td class="text-muted">Операционный диапазон для задач на участках/рядах.</td>
          </tr>

          <tr>
            <td class="fw-semibold">Качество обработки</td>
            <td>Перекрытия/пропуски, равномерность</td>
            <td>в % — TBD</td>
            <td class="text-muted">Метрики будут формализованы по результатам испытаний/требований заказчика.</td>
          </tr>

          <tr>
            <td class="fw-semibold">Дозирование</td>
            <td>Точность нормы внесения</td>
            <td>в % — TBD</td>
            <td class="text-muted">Планируется дополнение измерением расхода химии.</td>
          </tr>

          <tr>
            <td class="fw-semibold">Безопасность</td>
            <td>Инциденты / аварийные остановки / зоны</td>
            <td>0 критических</td>
            <td class="text-muted">Контролируется на испытаниях и в эксплуатационных сценариях.</td>
          </tr>

          <tr>
            <td class="fw-semibold">Надёжность</td>
            <td>Простои / отказы</td>
            <td>TBD</td>
            <td class="text-muted">Будет формализовано, когда появится статистика испытаний.</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</div>
