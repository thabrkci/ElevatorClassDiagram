`12 Katlı Bir Binanın Asansör Simülasyon Sistemi`
>* Kodluyoruz Sigorta Şirketi 12 katlı bir ofis binası inşa etmek ve onu en son asansör teknolojisi ile donatmak istiyor. Şirket, bina içindeki trafik akışı ihtiyaçlarını karşılayıp karşılamayacaklarını görmek için binanın asansörlerinin işlemlerini modelleyen bir yazılım simülatörü oluşturmanızı istiyor.

>* Binada, her biri binanın 12 katına çıkabilecek beş asansör bulunacaktır. Her asansörün yaklaşık altı yetişkin yolcu kapasitesi vardır. Asansörler enerji tasarruflu olacak şekilde tasarlanmıştır, bu nedenle yalnızca gerektiğinde hareket ederler. Her asansörün kendi kapısı, kat gösterge ışığı ve kontrol paneli vardır. Kontrol panelinde hedef düğmeleri, kapı açma ve kapama düğmeleri ve bir acil durum sinyal düğmesi bulunur.

>* Binadaki her katta, beş asansör boşluğunun her biri için bir kapı ve her kapı için bir varış zili vardır. Varış zili, asansörlerin bir kata vardığını gösterir. Her kapının üzerinde bulunan bir sinyal ışığı, asansörün gelişini ve asansörün hareket ettiği yönü gösterir. Her katta ayrıca üç set asansör çağrı düğmesi vardır.

>* Bir kişi uygun çağrı düğmesine (yukarı veya aşağı) basarak bir asansörü çağırır. Bir programlayıcı, aramanın başladığı kata gitmek için beş asansörden birini görevlendirir. Asansöre girdikten sonra, bir yolcu tipik olarak bir veya daha fazla hedef düğmesine basar. Asansör kattan kata hareket ederken, asansörün içindeki bir gösterge ışığı yolcuları asansörün konumu hakkında bilgilendirir. Bir asansörün bir kata varması, dış asansör kapısının üzerindeki gösterge lambasının yakılması ve kat zilinin çalmasıyla belirtilir. Bir asansör bir katta durduğunda, her iki kapı grubu da önceden belirlenmiş bir süre boyunca otomatik olarak açılarak yolcuların asansöre girip çıkmalarına izin verir.

>* Simülatör, gerçek zaman geçişini simüle etmek ve simülasyonda meydana gelen olayları zaman damgası ve günlüğe kaydetmek için bir "saat" kullanır. Simülatör tarafından yolcu oluşturmak ve her yolcu için kalkış ve varış katlarını belirlemek için rastgele bir sayı üreteci kullanılır.
***
***
`Elevator Simulation System for a 12-story Building`
>* Kodluyoruz Insurance Company wants to build a 12-story office building and equip it with the latest elevator technology. The company wants you to create a software simulator that models the operations of the building's elevators to see if they will meet the traffic flow needs within the building.

>* The building will have five elevators, each capable of going up to 12 floors of the building. Each elevator has a capacity of approximately six adult passengers. The elevators are designed to be energy efficient, so they only move when needed. Each elevator has its own door, floor indicator light and control panel. The control panel has destination buttons, door open and close buttons and an emergency signal button.

>* Each floor in the building has a door for each of the five elevator shafts and an arrival bell for each door. The arrival bell indicates that the elevators have arrived at a floor. A signal light above each door indicates the arrival of the elevator and the direction in which the elevator is moving. Each floor also has three sets of elevator call buttons.

>* A person calls an elevator by pressing the appropriate call button (up or down). A programmer assigns one of the five elevators to go to the floor where the call started. Once in the elevator, a passenger typically presses one or more destination buttons. As the elevator moves from floor to floor, an indicator light inside the elevator informs passengers of the elevator's location. The arrival of an elevator on a floor is indicated by the indicator light above the outer elevator door being lit and the floor bell ringing. When an elevator stops on a floor, both sets of doors open automatically for a predetermined period of time, allowing passengers to enter and exit the elevator.

>* The simulator uses a "clock" to simulate the passage of real time and time stamp and log the events that occur in the simulation. A random number generator is used by the simulator to generate passengers and determine the departure and arrival floors for each passenger.

***
![ElevatorClassDiagram](ElevatorClassDiagram.jpg)