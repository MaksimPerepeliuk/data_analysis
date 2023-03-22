<p>Данный репозиторий представляет из себя портфолио моих проектов по анализу данных.</p>
<p>В каждой папке с названием проекта находится описание проекта, его целей, задач и исходных данных.</p>
<h1>Проекты:</h1>
<table>
	<thead>
		<tr>
		<td><b>№</b></td>
		<td><p><b>Название проекта (ссылка)</b></p></td>
		<td><p><b>Краткое описание</b></p></td>
		<td><p><b>Задачи проекта</b></p></td>
		<td><p><b>Навыки и инструменты</b></p></td>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td><b>1</b></td>
			<td><a href="https://github.com/MaksimPerepeliuk/data_analysis/blob/main/rus_offenders_victims_profiles/rus_offenders_victims_profiles.ipynb" target="_blank"><b>Анализ признаков преступников и потерпевших в Российской Федерации</b></a></td>
			<td>Правоохранительные органы Российской Федерации осуществляют сбор статистики по лицам совершившими преступления, а так же лицам, которые признаны потерпевшими в результате противоправной деятельности</td>
			<td> 
				<ul>
					<li>Исследовать половозрастной портрет преступников и потерпевших в Российской Федерации</li>
					<li>Исследовать динамику изменения значений половозрастных признаков по годам</li>
					<li>Выявить регионы Российской Федерации, которые отличаются от общих тенденций по половозрастным признакам преступников и потерпевших</li>
				</ul>
			</td>
			<td>pandas, numpy, matplotlib, scipy, seaborn, когортный анализ, проверка гипотез</td>
		</tr>
		<tr>
			<td><b>2</b></td>
			<td><a href="https://github.com/MaksimPerepeliuk/data_analysis/blob/main/mobile_scan_app_product_analysis/mobile_scan_app_product_analysis.ipynb" target="_blank"><b>Анализ и прогнозирование метрик юнит-экономики мобильного приложения для сканирования документов</b></a></td>
			<td>Приложение - мобильная утилита для сканирования документов. Модель монетизации подписочная, есть пробный период 7 дней с дальнейшим переходом в оплату 4.99 USD в неделю</td>
			<td>
				<ul>
					<li>Необходимо рассчитать текущий LTV юзера, используя когортный анализ</li>
					<li>Спрогнозировать, каким будет LTV на полгода</li>
					<li>Построить график, который будет отображать кривую фактического LTV на фоне кривой прогнозируемого LTV</li>
					<li>Рассчитать ROMI на 4 недели и спрогнозировать его на полгода, если стоимость привлечения платящего пользователя 6 USD</li>
				</ul>
			</td>
			<td>pandas, numpy, matplotlib, scipy, seaborn, когортный анализ, продуктовый анализ</td>
		</tr>
		<tr>
			<td><b>3</b></td>
			<td><a href="https://github.com/MaksimPerepeliuk/data_analysis/blob/main/ab_test_analysis_game_currency_spending/ab_test_gamedev.ipynb" target="_blank"><b>Анализ результатов A/B теста расходов внутриигровой валюты</b></a></td>
			<td>Игра содержит особое событие – ивент, для прохождения которого пользователи могут тратить внутриигровую валюту. Группа дизайнеров решила поменять вид окошка покупки ивентовых продуктов. Чтобы оценить результат нововведения, провели АБ тест</td>
			<td><ul><li>Исследовать какая из A/B групп лучше себя показала по результатам проведенного теста</li></ul></td>
			<td>pandas, numpy, matplotlib, scipy, seaborn, A/B тестирование, проверка гипотез</td>
		</tr>
		<tr>
			<td><b>4</b></td>
			<td><a href="https://github.com/MaksimPerepeliuk/data_analysis/blob/main/ab_test_website_design/ab_test_website_design.ipynb" target="_blank"><b>A/B тестирование нового дизайна продающей страницы сайта</b></a></td>
			<td>На сайте по продаже книг есть раздел с предложениями о покупке набора сразу из нескольких книг по более выгодной цене, чем при покупке их по отдельности.<br> Дизайнером сайта было предложено изменить эту страницу, так как по его мнению она слишком громоздкая и отпугивает некоторых потенциальных покупателей</td>
			<td><ul><li>Рассчет размера выборки, по достижению которой мы остановим тест;</li><li>Анализ результатов A/B тестирования и проверка гипотез о значимой разнице конверсий в группах теста.</li></ul></td>
			<td>pandas, numpy, seaborn, statsmodels, A/B тестирование, проверка гипотез</td>
		</tr>
		<tr>
			<td><b>5</b></td>
			<td><a href="https://github.com/MaksimPerepeliuk/data_analysis/blob/main/retention_rate_store_app/retention_rate_store_app.ipynb" target="_blank"><b>Анализ коэффициента удержания в приложении покупок магазина</b></a></td>
			<td>В июле 2015 года провели специальную акцию, направленную на улучшение ретеншена. Новым юзерам слали письмо с купоном на скидку</td>
			<td>
				<ul>
					<li>Выяснить, сработала ли акция?</li>
					<li>Как повел себя коэффициент удержания после проведения акции?</li>
				</ul>
			</td>
			<td>pandas, numpy, matplotlib, когортный анализ, продуктовый анализ</td>
		</tr>
		<tr>
			<td><b>6</b></td>
			<td><a href="https://github.com/MaksimPerepeliuk/data_analysis/blob/main/football_weather_analysis/football_weather_analysis.ipynb" target="_blank"><b>Влияние погоды на количество голов в матчах Английской Премьер Лиги</b></a></td>
			<td>Нам предстоит исследовать влияние погоды на количество голов в матчах АПЛ. Для этого был написан парсер, для сбора данных с сайта футбольной статистики <a href="https://www.nowgoal6.com/">https://www.nowgoal6.com/</a> за сезоны 2018-2019, 2019-2020, 2020-2021, 2021-2022</td>
			<td>
				<ul>
					<li>Различие количества голов между матчами проходившими при плохой и нормальной погоде</li>
					<li>Различие количества голов между матчами проходившими в разные интервалы температур воздуха</li>
				</ul>
			</td>
			<td>pandas, numpy, matplotlib, seaborn, scipy, множественные проверки гипотез</td>
		</tr>
		<tr>
			<td><b>7</b></td>
			<td><a href="https://github.com/MaksimPerepeliuk/data_analysis/blob/main/ltv_calc_and_forecasting/ltv_calc_and_forecasting.ipynb" target="_blank"><b>Исследование методов расчета и прогнозирования Customer Lifetime Value</b></a></td>
			<td>Существует множество способов расчета и прогнозирования метрики Customer Lifetime Value (CLV) - пожизненной ценности клиента. В данном исследовании мы попробуем рассчитать и спрогнозировать данную метрику несколькими способами</td>
			<td>
				<ul>
					<li>Расчет CLV с помощью выручки</li>
					<li>Расчет CLV с помощью валовой прибыли</li>
					<li>Прогнозирование CLV на основе анализа графика и аппроксимации функции, описывающей связь на данном графике</li>
					<li>Прогнозирование CLV с помощью алгоритмов регрессии</li>
				</ul>
			</td>
			<td>pandas, numpy, matplotlib, scipy, sklearn, CatBoost</td>
		</tr>
		<tr>
			<td><b>8</b></td>
			<td><a href="https://github.com/MaksimPerepeliuk/data_analysis/blob/main/split_func_test/split_func_test.ipynb" target="_blank"><b>Создание и тестирование функции разделения пользователей на группы</b></a></td>
			<td>Для того чтобы мы могли проводить A/B тестирование, нам нужна функция, которая будет разделять пользователей на группы</td>
			<td>
				<ul>
					<li>Написать функцию разделения пользователей на произвольное количество групп</li>
					<li>Протестировать функцию и сделать вывод о корректности деления пользователей</li>
				</ul>
			</td>
			<td>pandas, numpy, seaborn, scipy</td>
		</tr>
		<tr>
			<td><b>9</b></td>
			<td><a href="https://github.com/MaksimPerepeliuk/data_analysis/blob/main/rfm_segmentation_for_marketing/rfm_segmentation_for_marketing.ipynb" target="_blank"><b>Сегментирование клиентов онлайн магазина с помощью RFM-Score</b></a></td>
			<td>Есть ограниченный бюджет для проведения рекламной компании. Для экономии бюджета и увеличения эффективности компании, требуется выделить сегменты клииентов, наиболее лояльных к нашему онлайн магазину, на которых и будет нацелена рекламная компания</td>
			<td>
				<ul>
					<li>Выгрузить необходимые данные из БД</li>
					<li>Провести RFM анализ и на его основе выделить сегменты клиентов, на которые будет нацелена рекламная компания</li>
				</ul>
			</td>
			<td>pandas, numpy, matplotlib, sqlalchemy, PostgreSQL</td>
		</tr>
		<tr>
			<td><b>10</b></td>
			<td><a href="https://github.com/MaksimPerepeliuk/data_analysis/blob/main/ml_clustering_online_app_users/ml_clustering_online_app_users.ipynb" target="_blank"><b>Кластеризация пользователей с помощью алгоритмов обучения без учителя</b></a></td>
			<td>В нашем распоряжении база данных онлайн магазина, где хранятся данные о пользователях зарегистрировавшихся в приложении магазина, данные о покупках и сессиях. Нам требуется провести кластеризацию пользователей для дальнейшего выделения целевых групп в маркетинговых активностях</td>
			<td>
				<ul>
					<li>Выгрузить необходимые данные из БД</li>
					<li>Провести кластеризацию пользователей</li>
					<li>Интерпретация результатов кластеризации</li>
				</ul>
			</td>
			<td>pandas, numpy, matplotlib, seaborn, plotly, sqlalchemy, PostgreSQL, Sklearn (K-means, PCA), scipy (hierarchy clustering)</td>
		</tr>
		<tr>
			<td><b>11</b></td>
			<td><a href="https://github.com/MaksimPerepeliuk/data_analysis/blob/main/aa_ab_test_with_bootstrap/aa_ab_test_with_bootstrap.ipynb" target="_blank"><b>A/A и A/B тестирование с помощью bootstrap</b></a></td>
			<td>Отделом разработки был интегрирован более новый видеоплеер в мобильное приложение. Теперь нам предстоит удостовериться, что новый видеоплеер положительно повлияет на лояльность пользователей. Для этого были сформированы выборки для A/A и A/B тестирования. В качестве целевого показателя решено использовать медианную продолжительность сессий пользователей в мобильном приложении.</td>
			<td>
				<ul>
					<li>Проведение A/A теста</li>
					<li>Проверка гипотезы о значимой разнице медианной продолжительности сессий, в A B выборках</li>
				</ul>
			</td>
			<td>pandas, numpy, matplotlib, scipy</td>
		</tr>
		<tr>
			<td><b>12</b></td>
			<td><a href="https://github.com/MaksimPerepeliuk/data_analysis/blob/main/cohort_analysis_sql/cohort_analysis_sql.ipynb" target="_blank"><b>Когортный анализ онлайн магазина с помощью PostgreSQL</b></a></td>
			<td>С помощью postgreSQL провести когортный анализ данных онлайн магазина</td>
			<td>
				<ul>
					<li>Рассчитать коэффициент конверсии в первую покупку по когортам</li>
					<li>Рассчитать коэффициент удержания пользователей по когортам</li>
				</ul>
			</td>
			<td>pandas, seaborn, PostgreSQL, sqlalchemy</td>
		</tr>
		<tr>
			<td><b>13</b></td>
			<td><a href="https://github.com/MaksimPerepeliuk/data_analysis/blob/main/unit_economic_calc_excel/unit_economic_calc.xlsx"target="_blank"><b>Калькулятор юнит-экономики в Excel</b></a></td>
			<td>С помощью postgreSQL провести когортный анализ данных онлайн магазина</td>
			<td>
				<ul>
					<li>Расчет LTV на основе валовой прибыли</li>
					<li>Расчет ROMI</li>
					<li>Расчет метрик по относительным изменениям</li>
				</ul>
			</td>
			<td>Excel</td>
		</tr>
	</tbody>
</table>
