---
title: "Артефакт 6 — Испытания и критерии готовности (таблица)"
permalink: /artifacts/case_3/artifact_6/
---

<div class="d-flex flex-wrap justify-content-between align-items-center gap-2 mb-3">
  <a class="btn btn-outline-secondary btn-sm" href="{{ '/artifacts/case_3/' | relative_url }}">← К артефактам кейса</a>
  <a class="btn btn-outline-primary btn-sm" href="{{ '/projects/case_3/' | relative_url }}">К кейсу</a>
</div>

# Испытания и критерии готовности

<div class="alert alert-light border mb-4">
  Испытания проводились в <strong>ноябре 2025</strong>. В управлении в испытаниях работают: <strong>ручной режим / маршрут на карте / автопилот</strong>.
</div>

## DoD (Definition of Done) для этапа “Испытания”
<ul>
  <li>Платформа управляется: ручной / маршрут на карте / автопилот.</li>
  <li>Стабильное движение в рабочем диапазоне <strong>1–10 км/ч</strong>.</li>
  <li>Базовые целевые метрики доступны: <strong>1 га/час</strong>, <strong>10 часов</strong> автономности.</li>
  <li>Есть безопасные сценарии (останов/ручной режим) при проблемах навигации/условий.</li>
</ul>

<div class="card border shadow-sm">
  <div class="card-body">
    <div class="table-responsive">
      <table class="table align-middle mb-0">
        <thead>
          <tr>
            <th style="width:70px;">ID</th>
            <th style="min-width:220px;">Сценарий</th>
            <th style="min-width:320px;">Шаги</th>
            <th style="min-width:260px;">Ожидаемый результат</th>
            <th style="min-width:260px;">Критерии приёмки</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td><span class="badge text-bg-light border">T1</span></td>
            <td class="fw-semibold">Ручной режим</td>
            <td>
              <ol class="mb-0">
                <li>Запуск платформы</li>
                <li>Ручное управление на участке</li>
                <li>Остановка/безопасное завершение</li>
              </ol>
            </td>
            <td class="text-muted">Платформа устойчиво управляется человеком</td>
            <td class="text-muted">Безопасная остановка; движение в диапазоне 1–10 км/ч</td>
          </tr>

          <tr>
            <td><span class="badge text-bg-light border">T2</span></td>
            <td class="fw-semibold">Маршрут на карте</td>
            <td>
              <ol class="mb-0">
                <li>Задать маршрут на карте</li>
                <li>Запустить выполнение</li>
                <li>Контроль прогресса</li>
              </ol>
            </td>
            <td class="text-muted">Маршрут выполняется, прогресс контролируется</td>
            <td class="text-muted">Переход в ручной режим при необходимости</td>
          </tr>

          <tr>
            <td><span class="badge text-bg-light border">T3</span></td>
            <td class="fw-semibold">Автопилот (RTK)</td>
            <td>
              <ol class="mb-0">
                <li>Активировать автопилот</li>
                <li>Движение по заданному маршруту</li>
                <li>Проверка реакции на ухудшение навигации</li>
              </ol>
            </td>
            <td class="text-muted">Устойчивое движение, контролируемая деградация</td>
            <td class="text-muted">Понятные сценарии остановки/ручного управления</td>
          </tr>

          <tr>
            <td><span class="badge text-bg-light border">T4</span></td>
            <td class="fw-semibold">Опрыскивание (базовый контур)</td>
            <td>
              <ol class="mb-0">
                <li>Запуск модуля опрыскивания</li>
                <li>Работа форсунок/секций</li>
                <li>Остановка и фиксация состояния</li>
              </ol>
            </td>
            <td class="text-muted">Опрыскивание выполняется в заданных режимах</td>
            <td class="text-muted">Безопасное включение/выключение, отсутствие критических сбоев</td>
          </tr>

          <tr>
            <td><span class="badge text-bg-light border">T5</span></td>
            <td class="fw-semibold">Автономность</td>
            <td>
              <ol class="mb-0">
                <li>Нагрузка/работа в течение смены</li>
                <li>Контроль времени работы</li>
              </ol>
            </td>
            <td class="text-muted">Достигается целевая автономность</td>
            <td class="text-muted"><strong>10 часов</strong> (как целевой показатель)</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</div>
