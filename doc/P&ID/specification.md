# Piping and Instrumentation Diagram/Drawing (P&ID) #
## О языке ##

Язык P&ID основывается на International Society of Automation (ISA) Standard S5.1 и предназначен для описания диаграмм, которые показывают взаимосвязь технологического оборудования и приборов, используемых для управления процессом.  
Основной чертеж или схема на языке P&ID используются для изображения установки управления технологическими процессами.

## Элементы P&ID ##

Рассмотрим элементы схем, которые необходимы для составления узла нагрева.

| Номер | Символ                                              | Описание       |
| ----- |:---------------------------------------------------:| :--------------|
| 1     | ![трубопровод](images/pipe.svg)                     | Трубопровод <br/> (pipe). |
| 1     | ![нормально закрытый клапан](images/valve_nc.svg)   | Нормально закрытый двухходовой клапан <br/> (generic two-way normally open valve). |
| 2     | ![нормально открытый клапан](images/valve_no.svg)   | Нормально открытый двухходовой клапан <br/> (generic two-way normally closed valve).|
| 3     | ![ручной н.о. клапан ](images/hand_valve_nc.svg)    | Ручной нормально закрытый двухходовой клапан <br/> (generic two-way normally closed valve with manual actuator).|
| 4     | ![ручной н.з. клапан](images/hand_valve_no.svg)     | Ручной нормально открытый двухходовой клапан <br/> (generic two-way normally closed valve with manual actuator).|
| 5     | ![н.о. клапан с активатором](images/actuator_valve_no.svg)     | Нормально открытый двухходовой клапан с активатором<br/> (generic actuator normally open valve).|
| 6     | ![измерительное устройство](images/instr_device.svg)| Измерительное устройство <br/> (instrumentation device).|
| 7     | ![вертикальный танк](images/vertical_vessel.svg)    | Вертикальный танк <br/> (vertical vessel).|

## Узел нагрева ##

Упрощенная P&ID-схема узла нагрева.

![узел нагрева](images/heating_node.svg)

Полная P&ID-схема узла нагрева.

![узел нагрева](images/heating_node.png)