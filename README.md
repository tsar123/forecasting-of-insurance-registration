# forecasting-of-insurance-registration

# О наборе данных

1 policy_rk -- Уникальный номер выпущенного полиса

2 total_premium_amt -- Сумма премии выпущенного полиса

3 coverage -- Покрытие полиса

4 repair_option -- Выбранный ремонт по полису

5 paid_flg -- Флаг оплаты полиса: 1 – оплачен; 0 – не оплачен.

6 region -- Регион использования авто

7 auto_make -- Марка авто

8 auto_model -- Модель авто

9 auto_cost -- Цена авто

10 vehicle_mileage_km_amt -- Пробег авто

11 vehicle_new_flg -- Флаг нового авто: 1 – новое авто; 0 – Б\у.

12 audatex_claim_cnt -- Количество убытков за предыдущие периоды

13 audatex_total_cost_amt -- Сумма убытков за предыдущие периоды

14 vehicle_issue_year -- Год выпуска авто

15 vehicle_credit_flg -- Флаг кредитного авто: 1 – кредитное авто 0 – не кредитное.

16 min_driver_experience_years_cnt -- Стаж вождения

17 insurant_gender_cd -- Пол водителя: F – женский; M - мужкой.

18 age -- Возраст водителя

19 issue_flg -- Флаг выпуски полиса: 1 – выпущен; 0 – не выпущен.

20 expected_loss_amt -- Сумма предполагаемого убытка по полису

21 transition_flg -- Флаг наличия предыдущего полиса другой страховой: 1 – есть полис; 0 – нет полиса.

22 premium_transition_amt -- Стоимость предыдущего полиса страховой

23 renewed_issue_flg -- Флаг выпуска пролонгации: 1 – пролонгация выпущена; 0 – пролонгация не выпущена.

24 renewed_paid_flg -- Флаг оплаты пролонгации: 1 – оплачено; 0 – не оплачено.

# Предварительный анализ данных
Результаты:
![image](https://github.com/user-attachments/assets/90e64ded-dc2b-4b0c-8d96-93f0fa87bb14)




# Корреляционный анализ данных
Столбчатая диаграмма корреляций:
![image](https://github.com/user-attachments/assets/3c38346e-4d36-4177-ab73-e4e0ef69d150)


Тепловая карта корреляции:
![image](https://github.com/user-attachments/assets/326eb5b3-0ba5-4d5d-98d7-7f4fda7ea1f5)


# Матрица путаницы
RandomForestClassifier:

![image](https://github.com/user-attachments/assets/9aa2d74f-bf1e-4aed-8403-a0c888dce9f2)


LogisticRegression:

![image](https://github.com/user-attachments/assets/825e9835-406a-4834-8138-2ec137100e76)
