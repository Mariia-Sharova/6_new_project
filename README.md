Имеются следующие данные о транзакциях в период с 01.12.2010 по 12.09.2011:

InvoiceNo — номер транзакции
StockCode — код товара
Description — описание товара
Quantity — количество единиц товара, добавленных в заказ
InvoiceDate — дата транзакции 
UnitPrice — цена за единицу товара
CustomerID — id клиента
Country — страна, где проживает клиент

Данные содержат в себе записи как об успешных транзакциях, так и об отмененных.
Если пользователь отменил заказ, в начале номера транзакции (InvoiceNo) ставится C (canceled). 
Сколько всего транзакций отменили пользователи? Считайте, что каждая строка - это отдельная транзакция.

Посчитайте число заказов для каждого пользователя (CustomerID) из Германии (Germany).
Оставьте только тех, кто совершил более N транзакций (InvoiceNo), где N – 80% процентиль.
Запишите полученные id пользователей в germany_top (не весь датафрейм, только id).

Какой из продуктов добавляли в корзину чаще всего, кроме POST? 

