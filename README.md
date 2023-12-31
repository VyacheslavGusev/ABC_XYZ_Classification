# ABC_XYZ_Classification
ABC_XYZ анализ, товарная аналитика для крупной торговой Компании. Входящими данными служит стандартный отчет по продажам в фомате EXCEL, в разрезе временного периода.\
Выходными данными является отчет в формате EXCEL с расчитанными критериями классификации. 
Посредством библиотеки Pandas формируется Data Frame с необходимыми данными для построения Классификаций ABC и XYZ\
В первом блоке скрипта классификация ABC строится по трем основным метрикам: Товарообороту, Валовой Прибыли, Количеству шт.\
В итоге расчитываются классы AAA, ABA, ABB, ........... CCC. в нескольких разрезах ассортиментных срезов: Товарной Категории, Товарной Группы, Ассортиментной Группы. 
Рассчет по нескольким срезам необходим, поскольку ассортиментные группы не являются однородными по наполнению и равнозначными по количеству SKU.\
В блоке XYZ применен стандартный подход классификации товарных позиций по волотильности спроса, основанный на среднеквадратичном отклонении продаж.\ 
Совмещенная аналитика ABC_XYZ в разрезе Товарных Категорий дает представление, как о ликвидности товарных позиций, так и о способах логистического управления ими. Является расширенной альтернативой первому 
методу расчета.\
Анализ позволяет сделать следующие выводы и принять управленчиские решения:
- Причина нахождения позиции в конкретной группе;
- Целесообразность поддержания складских остатков по позиции, вопрос о выводе из ассортимента;
- Способы оптимизации работы с товарами  категории, для уменьшения издержек (акции, распродажи, cross-sale и up-sele предложения) в он-лайн и оф-лайн продажах.
 ![image](https://github.com/VyacheslavGusev/ABC_XYZ_Classification/assets/117516863/4bd5726f-f07d-4860-96ae-831e4908739a)
 ![image](https://github.com/VyacheslavGusev/ABC_XYZ_Classification/assets/117516863/c7d7eed1-59cc-4edc-bd15-82c69862a02e)
 ![image](https://github.com/VyacheslavGusev/ABC_XYZ_Classification/assets/117516863/a32ac7ce-7275-4123-872f-ef01e55687f3)




