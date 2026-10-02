# Визуальные ресурсы проекта

## Канонические пути

```text
assets/
  brand/
    photocka-logo.svg
  models/
    reference-sheets/
      F01_reference.png
      F02_reference.png
      F03_reference.png
      M01_reference.png
      M02_reference.png
      M03_reference.png
      T01_reference.png   # отдельная взрослая модель педагога
  product-references/       # реальные фотографии изготовленных лент
  people-references/        # реальные фотографии посадки лент на людях
  showroom-references/      # реальные фото офиса/шоурума
  campaigns/2027/           # готовые рекламные изображения и варианты креативов
```

## Обязательные правила

- Для брендинга использовать только `assets/brand/photocka-logo.svg`.
- Логотип не генерировать средствами AI; накладывать отдельно после генерации.
- Reference sheets — визуальный источник истины для соответствующего `model_id`.
- Не реконструировать лицо модели по памяти и не заменять отсутствующий reference sheet похожим персонажем.
- Новые рекламные изображения складывать в `assets/campaigns/2027/` с указанием номера кадра и состава моделей.
