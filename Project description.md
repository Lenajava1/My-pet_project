# My-pet_project
Examples of my code in Java

1) Создать интерфейс Stack - абстрактный тип данных (использовать реализацию Stack из Java SE запрещено), 
представляющий собой список элементов, организованных по принципу LIFO («последним пришёл — первым вышел»). 

Определить методы в данном интерфейсе Stack  для хранения целых чисел (значений типа int):
// поместить число в стек        (вершина стека перемещается на новый элемент)
void push(int value);   

// извлечь число с вершины стека (вершина стека перемещается на новый элемент)      
int pop();    

// проверяет, есть ли еще элементы в данном стеке 
(если в стеке,  нет ни одного элемента, то метод возвращает значение равное true)               
boolean isEmpty();          
  
// проверяет, что стек уже заполнен (если нет возможности помещать новые элементы в стек, то метод возвращает значение равное true)
boolean isFull();      

// возвращает количество элементов в стеке на текущий момент            
int size();        
 
// удаляет все элементы из стека (очистка стека)                    
void clear();                          


2) Создать класс SimpleStack реализующий интерфейс Stack с помощью массива элементов типа int[] (int[] array)

Определить конструктор класса в классе SimpleStack  с параметром - максимальное количество элементов в стеке (значение типа int).
Реализовать методы интерфейса Stack в данном классе.
Переопределить метод toString() класса Object для получения строки содержащей все элементы стека.
Строка должна быть составлена из элементов стека начиная с ее вершины. 

3) Создать статический метод в отдельном классе (StackUtil) для создания нового стека на основе стека - параметра метода, 
содержащего все элементы исходного стека в обратном порядке. 
public static Stack createStack(Stack s) {

}

Продемонстрировать работу стека и данного статического метода createStack в методе main.  
