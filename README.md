# Классификация объектов строительной техники по изображениям со стройплощадки (для МФТИ)


Задание конкурса:
Строительная область представляет собой одну из главных отраслей материального производства. Ведь именно она создаёт базу для развития многих других направлений, предназначенных для удовлетворения первоочередных потребностей жизнедеятельности человека. Цифровизация этого направления является чрезвычайно важной, так как может также сократить сроки реализации строительных объектов, помочь в логистических вопросах, усилить контроль производственных процессов.

Повсеместное распространение камер видеонаблюдения позволяет постоянно собирать большие объемы данных, которые требуют непрерывной обработки алгоритмами. В частности, регулярно встает задача определения типа объекта, который был детектирован на изображении камеры. Подобные данные позволяют контролировать технику на строительных площадках, определять, какая техника движется по дорогам, что впоследствии позволяет вычислять как эффект от вредных выбросов, так и нагрузку на дорожное полотно.

Участникам чемпионата предлагается разработать модель классификации техники на изображениях со стройплощадки, что значительно упростит процессы автоматизации производства и позволит избежать необходимости хранения избыточных фото- и видеоматериалов, которые будут заменены простыми текстовыми метаданными.

Предлагаемое решение предлагает модель для обработки и классификации изображений на фотографиях.

В решении использовались библиотеки keras, numpy, pandas.

model.evaluate(xtest, ytest)

16/16 [==============================] - 1s 24ms/step - loss: 0.3744 - accuracy: 0.9719
