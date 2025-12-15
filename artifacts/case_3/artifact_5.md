---
title: "Артефакт 5 — Top-риски и меры (таблица)"
permalink: /artifacts/case_3/artifact_5/
---

<div class="d-flex flex-wrap justify-content-between align-items-center gap-2 mb-3">
  <a class="btn btn-outline-secondary btn-sm" href="{{ '/artifacts/case_3/' | relative_url }}">← К артефактам кейса</a>
  <a class="btn btn-outline-primary btn-sm" href="{{ '/projects/case_3/' | relative_url }}">К кейсу</a>
</div>

# Top-риски (короткий реестр)

<div class="card border shadow-sm">
  <div class="card-body">
    <div class="table-responsive">
      <table class="table align-middle mb-0">
        <thead>
          <tr>
            <th style="width:70px;">ID</th>
            <th style="min-width:260px;">Риск</th>
            <th style="min-width:220px;">Последствие</th>
            <th style="min-width:280px;">Меры</th>
            <th style="min-width:220px;">Контроль</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td><span class="badge text-bg-light border">R1</span></td>
            <td class="fw-semibold">Риски безопасности при работе с химией</td>
            <td class="text-muted">Инциденты/остановы/ущерб</td>
            <td>Аварийные сценарии (останов), регламенты, контроль доступа и процедур</td>
            <td>0 критических инцидентов; журнал аварийных остановок</td>
          </tr>

          <tr>
            <td><span class="badge text-bg-light border">R2</span></td>
            <td class="fw-semibold">Потеря RTK/снижение точности навигации</td>
            <td class="text-muted">Отклонения, падение качества обработки</td>
            <td>Деградация режима: ручной режим/останов; правила реакции</td>
            <td>Логи качества навигации (TBD)</td>
          </tr>

          <tr>
            <td><span class="badge text-bg-light border">R3</span></td>
            <td class="fw-semibold">Препятствия/непредвиденные объекты в ряду</td>
            <td class="text-muted">Столкновение/повреждения</td>
            <td>Камеры/ультразвук (в плане), сценарии безопасной остановки</td>
            <td>Инциденты/срабатывания остановки</td>
          </tr>

          <tr>
            <td><span class="badge text-bg-light border">R4</span></td>
            <td class="fw-semibold">Неизвестная точность дозирования / перекрытия/пропуски</td>
            <td class="text-muted">Нестабильное качество обработки</td>
            <td>Формализация метрик, испытания на качество, измерение расхода (в плане)</td>
            <td>Метрики в % — TBD</td>
          </tr>

          <tr>
            <td><span class="badge text-bg-light border">R5</span></td>
            <td class="fw-semibold">Отказы/простои (привод/насос/узлы)</td>
            <td class="text-muted">Потери времени, стоимость владения растёт</td>
            <td>Регламенты обслуживания, фиксация причин простоев</td>
            <td>Статистика простоев/отказов — TBD</td>
          </tr>

          <tr>
            <td><span class="badge text-bg-light border">R6</span></td>
            <td class="fw-semibold">Не хватит химии на проход по ряду</td>
            <td class="text-muted">Прерывание, неполная обработка</td>
            <td>Датчик уровня + оценка “хватит ли” (в плане)</td>
            <td>События дозаправки/остановок</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</div>
