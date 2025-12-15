---
title: "Артефакт 4 — Карта зависимостей (таблица)"
permalink: /artifacts/case_3/artifact_4/
---

<div class="d-flex flex-wrap justify-content-between align-items-center gap-2 mb-3">
  <a class="btn btn-outline-secondary btn-sm" href="{{ '/artifacts/case_3/' | relative_url }}">← К артефактам кейса</a>
  <a class="btn btn-outline-primary btn-sm" href="{{ '/projects/case_3/' | relative_url }}">К кейсу</a>
</div>

# Карта зависимостей

<div class="card border shadow-sm">
  <div class="card-body">
    <div class="table-responsive">
      <table class="table align-middle mb-0">
        <thead>
          <tr>
            <th style="width:70px;">ID</th>
            <th style="min-width:240px;">Функция</th>
            <th style="min-width:260px;">Зависит от</th>
            <th style="min-width:220px;">Если зависимость “плохая”</th>
            <th style="min-width:220px;">Влияние</th>
            <th style="min-width:260px;">Меры</th>
            <th style="min-width:220px;">Контроль</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td><span class="badge text-bg-light border">D1</span></td>
            <td class="fw-semibold">Автопилот / движение по маршруту</td>
            <td>RTK GPS; условия на участке (рельеф/уклоны/грунт)</td>
            <td class="text-muted">Потеря RTK/точности → отклонения</td>
            <td class="text-muted">Падение качества обработки/безопасности</td>
            <td>Режим деградации: переход в ручной режим/останов</td>
            <td>Логи качества навигации (TBD)</td>
          </tr>

          <tr>
            <td><span class="badge text-bg-light border">D2</span></td>
            <td class="fw-semibold">Обнаружение препятствий</td>
            <td>Камеры/ультразвук (в плане)</td>
            <td class="text-muted">Нет детекции → риск столкновения</td>
            <td class="text-muted">Риск инцидентов/повреждений</td>
            <td>План внедрения сенсоров; сценарии остановки</td>
            <td>Инциденты/аварийные остановки</td>
          </tr>

          <tr>
            <td><span class="badge text-bg-light border">D3</span></td>
            <td class="fw-semibold">Качество обработки (перекрытия/пропуски)</td>
            <td>Навигация; управление нормой; стабильность движения</td>
            <td class="text-muted">Дрейф/рывки → качество падает</td>
            <td class="text-muted">Пропуски/перекрытия</td>
            <td>Фиксация режимов, тесты на стабильность скорости</td>
            <td>Метрики в % — TBD</td>
          </tr>

          <tr>
            <td><span class="badge text-bg-light border">D4</span></td>
            <td class="fw-semibold">Предиктивная оценка “хватит ли химии на ряд”</td>
            <td>Датчик уровня + расход (в плане)</td>
            <td class="text-muted">Нет точных данных → неверные решения</td>
            <td class="text-muted">Простой/неполная обработка</td>
            <td>План внедрения датчиков и валидация на испытаниях</td>
            <td>События дозаправки / остановки</td>
          </tr>

          <tr>
            <td><span class="badge text-bg-light border">D5</span></td>
            <td class="fw-semibold">Управление (web/планшет/мобильное)</td>
            <td>Доступность интерфейса/связь (TBD)</td>
            <td class="text-muted">Нет контроля → рост ручных ошибок</td>
            <td class="text-muted">Падение эффективности</td>
            <td>Чёткие сценарии управления и аварийные процедуры</td>
            <td>Журнал действий пользователя</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</div>
