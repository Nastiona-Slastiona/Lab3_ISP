# Lab3_ISP
3 semester
В данной лабораторной работе представлена сервис-служба, которая отслеживает изменения в папке SourceDirectory. Служба позволяет переименовывать, шифровать, переносить, расшифровывать и архивировать файлы, находящиеся в отслеживаемой папке. Для этого создается объект класса Options, который является моделью, созданной для десериализации в нее файла конфигурации. По условию система конфигурации сервиса реализована в формате json и xml. В зависимости от расширения файла создается объект класса JSON_parser или XML_parser. В каждом из этих классов имеется метод Parse(), который и позволяет произвести десериализацию файла конфигурации в нашу модель. Модель определяет опции, которые будет выполнять служба относительно файлов находящихся в папке, а так же определяет путь к этой папке/файлу.
