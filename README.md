# Интерационная-стохастическая модель фильтруемости эритроцитов
В данной папке находятся последние версии модели, разработанной мной с нуля для описания процесса фильтруемости эритроцитов.
Идея эксперимента в том, чтобы взяв пробу у пациента, определеить тип заболевания по изменению фильтруемости его крови, относительно нормы. Ряд заболеваний изменяет кинетические свойства эритроцитов. 
Данная модель была создана для аналитики процесса, для выявления ряда закономерностей и явлений играющих критическую роль в нем.
На основе работы этой модели процесс был описан системой дифференциальных уравнений, которые считаются численными методами (расчет идет на несколько порядков быстрее)
и точно описывают процесс. Закономерности выявленые за время работы с моделью - четко прослеживаются и в реальном эксперименте.

В репозитории представлены финальные на данном этапе версии 6.1.2 и 5.2 с разными подходами введениями стохастики в модель, а так же файл сверки работы этих двух моделей. 
Данные модели сами по себе являеются не информативными, поэтому я привожу их как пример ознакомительного кода, написанного мной в рамках моей научной работы.
