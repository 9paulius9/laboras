# laboras
V0.1
----
Atlikta:
Nuskaitymas:Vardas,Pavarde,nd ir egzamino rezultatas
Isvedama: suskaiciuotas galutinis balas su vidurkiu arba mediana
Galimybe sugeneruoti nd.\n
Paleidimas:Paleidžiama Program.cs, Main;(1 arba 3 pasirinkimas switch'e)
![0.1 versija] (https://github.com/9paulius9/laboras/tree/74fd09c239228f86fed55e7d11c9215481ac59fc)

V0.2
----
Atlikta
Nuskaitymas iš failo
Paleidimas:Paleidžiama Program.cs, Main;(2 pasirinkimas switch'e
![0.2 versija] (https://github.com/9paulius9/laboras/tree/33a9e9f5aafd4a1d6097b45cc5b169fb9f2601f9)

V0.3
----
Atlikta:Kodo reorganizavimas(Metodu sukurimas, .cs failu nauju sukurimas ir panaudojimas)
![0.3 versija] (https://github.com/9paulius9/laboras/tree/ad2cc32f37490ac01d9caf00f25871b36a4afc3d)

V0.4
----
Atlikta:
Sugeneruojami 5 failai su 10,100,1000,10000,100000 studentu
Rušiuojami studentai į vargšiukus ir kietiakus
Paleidimas:
Paleidžiama Program.cs, Main;(2 pasirinkimas switch'e);
{Užkomentuot: FailoNuskaitymas.nuskaitymas();//Listas v0.2
Užkomentuot: Spausdinimas.rezspausdinimasfailas();//Listas v0.2
Atkomentuoti: //FailuSarasai.failuGeneravimas();v0.4}
![0.4 versija] (https://github.com/9paulius9/laboras/tree/6db5eff5f210ca8e0346c65d6b30767628031afb)

V0.5
----
Atlikta:Konteineriu testavimas;
Nieko nekeitus(List):
1.stopwatch:00:00:00.6347371 Timer:0,6370377
Naudojant LinkedList:
1.stopwatch:00:00:45.9768189 Timer:45,9820075
Naudojant Queue:
1.stopwatch:00:00:35.6830414 Timer:35,6932467

Paleidimas:Program.cs, Main;(2 pasirinkimas switch'e)
Norint laika patikrint, reik atitinkamai atkomentuoti norimus konteinerius:

//FailoNuskaitymas.nuskaitymas();//Listas v0.2;
//Spausdinimas.rezspausdinimasfailas();//Listas v0.2;
Arba 
//FailoNuskaitymas.linkedListFailoNuskaitymas();//LinkedListas;
//Spausdinimas.rezspausdinimasSuLinkedList();//LinkedListas;
Arba 
//FailoNuskaitymas.queueFailoNuskaitymas();//Queue;
//Spausdinimas.rezspausdinimasSuQueue();//Queue;
![0.5 versija] (https://github.com/9paulius9/laboras/tree/27bc0603b5c0af216d21622727a6f0dd1acd0abf)

V1.0
----
Atlikta:Konteineriu testavimas, organizavimas
Išmatuota tris konteineriu tipai pagal strategijas:
Saugant studentus ir atskirai saugant kietiakus ir vargšiukus:
Rušiavimas į:Vargšiukus, Kietiakus
Nieko nekeitus(List):
1.stopwatch:00:00:00.8269568 Timer:0,8263706
Naudojant LinkedList:
1.stopwatch:00:54:38.8911224 Timer:3279,0111369
Naudojant Queue:
1.stopwatch:00:14:02.5729085 Timer:842,5985726

Saugant tik vargšiukus (tad lieka tik kietiakai):
Rušiavimas tik į:Vargšiukus
Nieko nekeitus(List):
1.stopwatch:00:00:00.6331473 Timer:0,6349657
Naudojant LinkedList:
1.stopwatch:00:34:12.7617182 Timer:2052,7951432
Naudojant Queue:
1.stopwatch:00:14:08.5381347 Timer:848,5474987

Naudojant konteinerio salinimo algoritma:
Naudojant Remove
Nieko nekeitus(List):
1.stopwatch:00:00:00.5829708 Timer:0,5843584
Paleidimas:Program.cs, Main;(2 pasirinkimas switch'e)

Atkomentuoti kažkuri konteinriu tipa:
//FailuSarasai.failuGeneravimas();//Listas 
arba 
//FailuSarasai.failuGenerimvasSuLInkedList();//LinkedList 
arba 
//FailuSarasai.failuGenerimvasSuQueue();//Queue
 
 
ARBA(BeKietiaku) 

//BeKietiaku(Atkomentuojant šitą pasirinkimą Be kietiaku FailuSarasai.cs faile (kiekvieno metodo apačioje atkomentuoti ir pasirinkti //kita spausdinimo metoda pvz.Spausdinimas.reziFailaBeKietiaku();

//FailuSarasai.failuGeneravimas();//Listas 
arba 
//FailuSarasai.failuGenerimvasSuLInkedList();//LinkedList 
arba 
//FailuSarasai.failuGenerimvasSuQueue();//Queue

ARBA

//SuRemove 
//FailuSarasai.failuGeneravimas();//Listas
![1.0 versija] (https://github.com/9paulius9/laboras)
