#База данных железнодорожный вокзал
##Сущности:
Пассажир: 
*	ID пассажира 
*	ФИО 
*	Паспортные данные 
 
Станция: 
*	ID станции 
*	Наименование 
 
Билет: 
*	ID билета 
*	ID пассажира 
*	ID поезда 
*	Номер вагона 
*	Номер места 
*	ID станции отправления 
*	ID станции прибытия 
*	Дата и время отправления 
*	Дата и время прибытия 
 
Поезд: 
*	ID поезда 
*	Номер поезда 
*	Количество вагонов 
*	Тип поезда 
 
##Функционал: 
Пассажир: 
- Ввод личных данных и их редактирование 
- Выбор поезда, вагона, места, станций отправления и прибытия, времени отбытия и прибывания)  
 
Персонал ж/д вокзала: 
- Ввод и редактирование данных о поезде 
- Ввод данных пассажира и заполнение билета(роль кассира) 
