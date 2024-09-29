# RS for Netflix

Реализуем несложную рекомендательную систему на основе content-based подхода. Работа с [датасетом](https://lms-cdn.skillfactory.ru/assets/courseware/v1/747dae7bf99b18ce3b24bd34aa7bc29b/asset-v1:SkillFactory+DSPR-2.0+14JULY2021+type@asset+block/netflix_titles.zip) (прямая ссылка), содержащим информацию об оценивании фильмов на платформе Netflix.

Закидываем описания фильмов в TF-IDF векторизатор и считаем косинусную близость.
