# SI_2024_lab2_213103
Кристина Стефанова
213103

2.
![lab2_SI2024_213103](https://github.com/stefanovak51/SI_2024_lab2_213103/assets/109036969/2f8a5a17-d426-42e3-9f93-61fbf29ad992)

3. Цикломатската комплексност на кодот ја добив така што со формулата (E-N)+2=10, односно од бројот на ребра (32) го одземав бројот на јазли (24), додадов 2 и добив 10 како цикломатска комплексност. Исто така 10 сде добива и доколку на бројот на гранења им се додаде 1.

4. 
![си1](https://github.com/stefanovak51/SI_2024_lab2_213103/assets/109036969/0ed34b7c-8e21-45d1-abed-448197b12e75)
![си2](https://github.com/stefanovak51/SI_2024_lab2_213103/assets/109036969/a326ccaa-267c-490c-8b1d-c6f44750d2a4)
Тест случај 1
Доколку allItems == null ќе се изврши throw new RuntimeException("allItems list can't be null!"); и програмата ќе заврши.
Тест случај 2
if (item.getName() == null || item.getName().length() == 0) ќе се изврши item.setName("unknown"); и потоа ќе продолжи програмата.
Тест случај 3
if (item.getBarcode() != null) ќе се извршат
String allowed = "0123456789";
char chars[] = item.getBarcode().toCharArray(); и потоа ќ влезе програмата во фор циклус
Тест случај 4
if (allowed.indexOf(c) == -1) ќе се изврши throw new RuntimeException("Invalid character in item barcode!"); и програмата ќе заврши.
Тест случај 5
if (item.getDiscount() > 0) ќе се изврши   sum += item.getPrice()*item.getDiscount();, во сзпротивно  sum += item.getPrice();
Тест случај 6
if (item.getBarcode() == null) ќе се изврши                 throw new RuntimeException("No barcode!");



