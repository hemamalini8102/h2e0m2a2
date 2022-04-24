**PARKING SYSTEM IMPLEMENTED USING C++**


**INTRODUCTION**
A car parking system is a mechanical device that multip lies parking capacity inside a parking
lot. Parking systems are generally powered by electric motors or hydraulic pumps that move
vehicles into a storage position.
Car parking systems may be traditional or automated. Automatic multi-storey automated car
park systems are less expensive per park ing slot, since they tend to require less building
volume and less ground area than a conventional facility with the same capacity. In the long
term, automated car parking systems are likely to be more cost effective than traditional
parking garages. Both automated car parking systems and automated parking garage systems
reduce exhaust gas- cars do not drive around in search of parking spaces.
Service intervals vary for automated car parking systems, depending on the type of machine s
used and their usage. Parking systems should be serviced at least once a year, and up to four
times a year for high traffic areas or for valet parking. In addition, regular ckaning is
mandatory to keep the car parking system in great working order, especially with the problems
posed by weather (salt on the road can spread to lifter platforms and cause severe damage if not  removed. A reputable car parking company will regularly cean all critical elements of is
automated parking system, including the car lifters top and bottom, all concrete pits, all posts
resting on the concrete, and the entire concrete fbor in the parking area
There is a need to promote the commercial parking by private sector. .. Impact Statement:
Since there are many cases when vehicles are parked on roads, so if there are
proper parking places then traffic problem woukl be less.

**PROBLEM DEFINITION:**
THE SOURCE CODE DECLARED ABOVE FOR THE PROGRAM OF CAR PARKING
SYSTEM HAS BEEN TESTED AND IT HAS BEEN FOUND THAT THE ABOVE
SOURCE CODE IS OKAY AND CORRECT. THE PROGRAM INVOLVES MANY
TYPE OF CONVERSIONS. THESE CONVERSIONS HAS TO DONE CAREFULLY.
MAINLY THERE ARE TWO TYPES OF TESTING:
1-SYSTEM TESTING AND
2-INTEGRATION TESTING
SYSTEM TESTING INVOLVES WHOLE TESTING OF PROGRAM AT ONCE AND
INTEGRATION TESTING
INVOLVES THE BREAKING OF PROGRAM INTO MODULES & THEN TEST.

**Algorithm / Step (Explain the different modules/functions used)**
To start the process of car parking system we have login the user id.
• After entering the correct password we woukd get a total no. of 4 choices
• To enter a new car details and to store the data
To get the the total no. of cars arrived with their car details and their parking charges.
• After that we can aso remove the data when the payment process is finished
• At the end the payment slip is generated and submitted to the client.

**IMPLEMENTATION**

#include<iostream.h>
#include<conio.h>
#include<stdlib.h>
class parking{
public:
int v,d;
float count;
char dn[20];
public:
void car();
void bike();
void bus();
void space();
};
void parking::car(){
if(count<=50){
cout<<endl<<"You can park your car";
for(int i=0;i<1;i++)
{
cout<<endl<<"Enter the name of driver:";
cin>>dn;
cout<<endl<<"Enter the car number:";
cin>>v;
cout<<endl<<"Enter the number of days:";
cin>>d;
cout<<"Amount you should pay: "<<d*200;
}
}
else{
cout<<"Sorry,Parking not available";
}
count++;
}
void parking::bike(){
if(count<=50){
cout<<endl<<"You can park your bike:";
for(int i=0;i<1;i++){
cout<<endl<<"Enter your name:";
cin>>dn;
cout<<endl<<"Enter bike number:";
cin>>v;
cout<<endl<<"Enter number of days:";
cin>>d;
cout<<"Amount you should pay: "<<d*100;
}
}
else{
cout<<"Sorry,parking not available";
}
count++;
}
void parking::bus(){
if(count<=50){
cout<<endl<<"You can park your bus";
for(int i=0;i<1;i++){
cout<<endl<<"enter the driver name:";
cin>>dn;
cout<<endl<<"Enter bus number: ";
cin>>v;
cout<<"Enter number of days: ";
cin>>d;
cout<<"Amount you should pay:"<<d*300;
}
}
else{
cout<<"Sorry,parking not available";
}
count++;
}
void parking::space(){
if(count<=50){
cout<<"Total number of available space are: "<<50-count;
}
else{
cout<<"Sorry, parking not available";
}
}
int main(){
clrscr();
int x;
parking p;
while(1){
cout<<endl<<"******** welcome *******";
cout<<endl<<"select vechical you need to park";
cout<<endl<<"1.Car";
cout<<endl<<"2.Bike";
cout<<endl<<"3.Bus";
cout<<endl<<"4.Space available to park:";
cout<<endl<<"5.Exit";
cout<<endl<<"Enter your choice:";
cin>>x;
switch(x){
case 1:
p.car();
break;
case 2:
p.bike();
break;
case 3:
p.bus();
break;
case 4:
p.space();
break;
case 5:
cout<<"process completed....";
exit(1);
default:
cout<<"invalid choice";
}
}
}

**RESULT**
 ****** Welcome ******
select vechical you need to park
1.Car
2.Bike
3. Bus
4.Space available to park:
5.Exit
Enter your choice:1
You can park your car
Enter the name of driver:hema
Enter the car number:9872
Enter the mumber of days:2
Amount you should pay: 400
******* elcome ******
select vechical you need to park
1.Car
2.Bike
3. Bus
4.Space available to park:
5.Exit
Enter your choice:2
 You can park your bike:
Enter your name:rani
Enter bike number:8723
Enter number of days:1
Amount you should pay: 100
******** welcome *******
select vechical you need to park
1.Car
2.Bike
3. Bus
4.Space available to park:
5.Exit
Enter your choice:3
You can park your bus
enter the driver name:ramu
Enter bus mumber: 9238
Enter number of days:3
 Amount you should pay:900
******** welcome *******
select vechical you need to park
1.Car
2.Bike
3. Bus
4.Space available to park:
5.Exit
Enter your choice:4
Total number of available space are: 47
******** welcome *****
select vechical you need to park
1.Car
2.Bike
3. Bus
4.Space available to park:
5.Exit
Enter uour choice:





