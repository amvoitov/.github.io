---
title: "Кейс 1 — Весовая ЛИЛИАНИ"
permalink: /projects/case_1/
---

<div class="d-flex flex-wrap align-items-center justify-content-between gap-2 mb-3">
  <a class="btn btn-outline-secondary" href="{{ '/projects/' | relative_url }}">← Назад к проектам</a>
  <a class="btn btn-outline-secondary" href="{{ '/artifacts/case_1/' | relative_url }}">Артефакты</a>
</div>

<div class="row g-4">
  <!-- Sticky summary -->
  <div class="col-12 col-lg-4">
    <div class="card shadow-sm rounded-4 position-sticky" style="top: 92px;">
      <div class="card-body p-4">
        <div class="d-flex justify-content-between align-items-start gap-2 mb-2">
          <h1 class="h5 mb-0">Весовая ЛИЛИАНИ</h1>
          <span class="badge text-bg-light border">Embedded • Android • Web</span>
        </div>

        <p class="text-muted mb-3">
          Блок обработки сигнала тензодатчика + Android (10 Гц, фильтрация, офлайн) + портал аналитики и телеметрии.
        </p>

        <div class="border rounded-4 p-3 mb-2">
          <div class="text-muted small">Роль</div>
          <div class="fw-semibold">PM / PO / аналитик / техлид / архитектор</div>
        </div>

        <div class="border rounded-4 p-3 mb-2">
          <div class="text-muted small">Период</div>
          <div class="fw-semibold">10.2021 → 11.2022+</div>
        </div>

        <div class="border rounded-4 p-3 mb-2">
          <div class="text-muted small">Команда</div>
          <div class="fw-semibold">7+ участников</div>
        </div>

        <div class="border rounded-4 p-3">
          <div class="text-muted small">Эффект</div>
          <div class="fw-semibold">−70% потерь/воровства; +20% продаж БП</div>
        </div>
      </div>
    </div>
  </div>

  <!-- Content -->
  <div class="col-12 col-lg-8">
    <h2 class="h4 mb-3">Контекст</h2>
    <ul>
      <li><b>Заказчик/владелец продукта:</b> внутренний департамент компании Лилиани</li>
      <li><b>Пользователи на технике:</b> механизатор/оператор/инженер/агроном</li>
      <li><b>Пользователи портала:</b> диспетчер/руководитель/служба эксплуатации/агроном</li>
    </ul>

    <h2 class="h4 mt-4 mb-3">Исходная “боль”</h2>
    <ul>
      <li>Контроль и учет собранного урожая</li>
      <li>Учет намолота и перевезенного урожая для расчета оплаты</li>
      <li>Снижение/искоренение воровства урожая</li>
    </ul>

    <h2 class="h4 mt-4 mb-3">Ключевые требования</h2>
    <div class="row g-3">
      <div class="col-12 col-md-6">
        <div class="card border rounded-4 h-100">
          <div class="card-body">
            <div class="fw-semibold mb-1">Точность и диапазон</div>
            <ul class="mb-0">
              <li>Погрешность: ±1% от взвешиваемого веса</li>
              <li>Диапазон массы: до 100 тонн</li>
              <li>Условия: вибрации/удары</li>
              <li>Обновление на экране: минимум 10 Гц</li>
            </ul>
          </div>
        </div>
      </div>

      <div class="col-12 col-md-6">
        <div class="card border rounded-4 h-100">
          <div class="card-body">
            <div class="fw-semibold mb-1">Связь и офлайн</div>
            <ul class="mb-0">
              <li>Канал до Android: Bluetooth</li>
              <li>Передавались “сырые значения”</li>
              <li>Офлайн-работа: да, хранение в памяти устройства</li>
              <li>В портал отправляет Android</li>
              <li>Интернет: мобильный, отправка по событию/пакетами</li>
            </ul>
          </div>
        </div>
      </div>
    </div>

    <h2 class="h4 mt-4 mb-3">Данные в портал</h2>
    <p class="mb-2">Уходило всё перечисленное: <b>веса + рейсы/события + гео + время + идентификаторы техники</b>.</p>

    <h2 class="h4 mt-4 mb-3">Команда</h2>
    <ul>
      <li>Embedded (блок): 1 (внутренний)</li>
      <li>Android: 1 (подрядчик)</li>
      <li>Backend/портал: 1 (внутренний)</li>
      <li>Frontend/портал: 1 (внутренний)</li>
      <li>QA/испытания: 3 (внутренние)</li>
      <li><b>Моя роль:</b> аналитик, архитектор, PM/PO, техписатель</li>
    </ul>

    <h2 class="h4 mt-4 mb-3">Этапы</h2>
    <ol>
      <li>MVP — 10.2021–02.2022</li>
      <li>Тестирования/испытания/валидация/внедрение в серию — 03.2022–05.2022</li>
      <li>Опытная эксплуатация — 06.2022–11.2022</li>
      <li>С 11.2022 — эксплуатация, поддержка, доработка функционала</li>
    </ol>

    <h2 class="h4 mt-4 mb-3">Результаты</h2>
    <div class="row g-3">
      <div class="col-12 col-md-6"><div class="border rounded-4 p-3 h-100"><b>Точность учета</b>: +50%</div></div>
      <div class="col-12 col-md-6"><div class="border rounded-4 p-3 h-100"><b>Прозрачность</b>: +70%</div></div>
      <div class="col-12 col-md-6"><div class="border rounded-4 p-3 h-100"><b>Снижение спорных ситуаций</b>: −80%</div></div>
      <div class="col-12 col-md-6"><div class="border rounded-4 p-3 h-100"><b>Потери/воровство</b>: −70%</div></div>
      <div class="col-12"><div class="border rounded-4 p-3"><b>Продажи БП</b>: +20%</div></div>
    </div>

    <div class="mt-4 d-flex flex-wrap gap-2">
      <a class="btn btn-primary" href="{{ '/artifacts/case_1/' | relative_url }}">Открыть артефакты</a>
      <a class="btn btn-outline-secondary" href="{{ '/projects/' | relative_url }}">К списку кейсов</a>
    </div>
  </div>
</div>
