#include<iostream>
#include<iomanip>
using namespace std;
void Length ( );
void Time ( );
void Temp ( );
void Speed( );
void Mass ( );
void Storage( );
int main( )
{
  int x;
  
  char ch;
  cout<<setw(28)<<"UNIT CONVERTER"<<endl<<endl<<endl;
  cout<<setw(5)<<"Converter Types"<<endl<<endl;
  cout<<"....................................."<<endl;
  cout<<setw(0)<<"1.TIME"<<setw(20)<<"2.DIGITAL STORAGE"<<setw(13)<<"3.SPEED ""\n" "\n" 
      <<setw(0)<<"4.MASS"<<setw(16)<<"5.TEMPERATURE"<<setw(15)<<" 6.LENGTH"<<endl;
      cout<<"....................................."<<endl;
 
  do{
  cout<<"Choose one you want to Converter Type=";
  cin>>x;
  cout<<endl<<endl;
  switch (x) { 
            case 1:
                   Time ( );
                   break;
            case 2:
                   Storage( );
                   break;  
            case 3:
                   Speed ( );
                   break;   
            case 4:
                   Mass ( );
                   break;      
            case 5:
                   Temp ( );    
                   break;    
            case 6:
                   Length( );
                   break;
                 
                   default:
                   cout<<setw(25)<<"[Invalid Choice]"<<endl;
                   break;
            }
  
   
  cout<<endl;
  cout<<" Do another Converter type (y or n)=";
  cin>>ch;
  }while(ch=='y');
  
  
 } 
 
  
  
  
  void Time ( )
  {
    int x;
    char ch;
    float day,hr,min,sec;
    cout<<setw(22)<<"[ TIME ]"<<endl;
    cout<<"....................................."<<endl;
    cout<<setw(10)<<"1.hr-min"<<setw(10)<<"2.hr-sec"<<setw(11)<<"3.min-sec"<<endl<<endl
        <<setw(10)<<"4.min-hr" <<setw(10)<<"5.sec-hr"<<setw(11)<<"6.sec-min"<<endl<<endl
        <<setw(11)<<"7.day-min"<<setw(10)<<"8.min-day"<<setw(10)<<"9.day-sec"<<endl<<endl
        <<setw(12)<<"10.sec-day"<<endl;
        
    do{ 
    cout<<"....................................."<<endl;   
    cout<<"Choose one you  want to Convert="<<endl;
    cin>>x;
    
    
    if (x==1) 
    {
      cout<<setw(20)<<".............." "( hr-min )""............." <<endl<<"Enter your hours=";
      cin>>hr;
      min=hr*60;
      cout<<"Converted Hours to Minutes="<<min<<"min";
    }  
    
    else if (x==2) 
    {
      cout<<setw(20)<<".............." "( hr-sec )""............." <<endl<<"Enter your hours=";
      cin>>hr;
      sec=hr*3600;
      cout<<"Converted Hours to Second="<<sec<<"sec";
    }  
    
     else if (x==3) 
    {
      cout<<setw(20)<<"............." "( min-sec )""............." <<endl<<"Enter your Minutes=";
      cin>>min;
      sec=min*60;
      cout<<"Converted Minutes to second ="<<sec<<"sec";
    }  
   
    else if (x==4) 
    {
      cout<<setw(20)<<"............." "( min-hr )"".............." <<endl<<"Enter your Minutes=";
      cin>>min;
      hr=min/60;
      cout<<"Converted  Minutes to Hours="<<hr<<"hr";
    }  
   
    else if (x==5) 
    {
      cout<<setw(20)<<"............." "( sec-hr )"".............." <<endl<<"Enter your Second=";
      cin>>sec;
      hr=sec/3600;
      cout<<"Converted Second to Hours ="<<hr <<"hr";
    }  
   
    else if (x==6) 
    {
      cout<<setw(20)<<"............." "( sec-min )""............." <<endl<<"Enter your Second=";
      cin>>sec;
      min=sec/60;
      cout<<"Converted Second to Minutes="<<min<<"min";
    }  
    
    else if (x==7) 
    {
      cout<<setw(20)<<"............." "( day-min )""............." <<endl<<"Enter your days=";
      cin>>day;
      min=day*24*60;
      cout<<"Converted Days to Minutes="<<min<<"min";
    }  
   
    else if (x==8) 
    {
      cout<<setw(20)<<"............." "( min-day )""............." <<endl<<"Enter your minutes=";
      cin>>min;
      day=(min/60)/24;
      cout<<"Converted  Minutes to Days="<<day<<"day";
    }  
   
    else if (x==9) 
    {
      cout<<setw(20)<<"............." "( day-sec )""............." <<endl<<"Enter your Days=";
      cin>>day;
      sec=(day*24)*3600;
      cout<<"Converted Days to Second="<<sec<<"sec";
    }  
   
    else if (x==10) 
    {
      cout<<setw(20)<<"............." "( sec-day )""............." <<endl<<"Enter your second=";
      cin>>sec;
      day=(sec/3600)/24;
      cout<<"Converted Second to Days="<<day<<"day";
    }  
    
    else
    {
    cout<<endl;
    cout<<setw(25)<<"(Invalid Choice)"<<endl;
    }
    cout<<endl;
    cout<<" Do another y or n=";
    cin>>ch;
    }while(ch=='y');
   }     
  
  
  void Temp ( )
  {
    
    int x;
    char ch;
    float C,F,K;
    cout<<setw(26)<<"[ TEMPERATURE ]"<<endl;
    cout<<"....................................."<<endl;
    cout<<setw(10)<<"1.(°C - °F)"<<setw(15)<<"2.(°F - °C)"<<setw(13)<<"3.(°F - K)"<<endl<<endl
        <<setw(10)<<"4.(K - °F)" <<setw(14)<<"5.(°C - K)"<<setw(14)<<"6.(K - °C)"<<endl;
        
        
    do{ 
    cout<<"....................................."<<endl;   
    cout<<"Choose one you  want to Convert="<<endl;
    cin>>x;
    
    
    if (x==1) 
    {
      cout<<setw(20)<<"............." "( °C - °F )""............." <<endl<<"Enter your Celsius=";
      cin>>C;
      F=(C*9/5)+32;
      cout<<"Converted Celsius to Fahrenheit="<<F<<"°F";
    }  
    
    else if (x==2) 
    {
      cout<<setw(20)<<"............." "( °F - °C )""............." <<endl<<"Enter your Fahrenheit=";
      cin>>F;
      C=(F-32)*5/9;
      cout<<"Converted Fahrenheit to  Celsius ="<<C<<"°C";
    }  
    
     else if (x==3) 
    {
      cout<<setw(20)<<"............." "( °F - K  )""............." <<endl<<"Enter your Fahrenheit=";
      cin>>F;
      K=(F-32)*5/9+273.15;
      cout<<"Converted Fahrenheit to Kelvin ="<<K<<"kelvin";
    }  
   
    else if (x==4) 
    {
      cout<<setw(20)<<"............." "( K - °F )"".............." <<endl<<"Enter your Kelvin=";
      cin>>K;
      F=(K-273.15)*9/5+32;
      cout<<"Converted  Kelvin to Fahrenheit="<<F<<"°F";
    }  
   
    else if (x==5) 
    {
      cout<<setw(20)<<"............." "( °C - K )"".............." <<endl<<"Enter your Celsius=";
      cin>>C;
      K=C+273.15;
      cout<<"Converted Celsius to Kelvin ="<<K<<"kelvin";
    }  
   
    else if (x==6) 
    {
      cout<<setw(20)<<"............." "( K - °C)""............." <<endl<<"Enter your Kelvin=";
      cin>>K;
      C=K-273.15;
      cout<<"Converted Kelvin to Celsius="<<C<<"°C";
    }  
    
    
    else
    {
    cout<<endl;
    cout<<setw(25)<<"(Invalid Choice)"<<endl;
    }
    cout<<endl;
    cout<<" Do another y or n=";
    cin>>ch;
    }while(ch=='y');
   }     
   
  void Speed ( )
  {
    int x;
    char ch;
    float M,K,F,m;
    cout<<setw(22)<<"[ SPEED ]"<<endl;
    cout<<"....................................."<<endl;
    cout<<setw(0)<<"1.(mile/hr)-(km/hr)"<<setw(21)<<"2.(km/hr)-(mile/hr)"<<endl<<endl
        <<setw(0)<<"3.(mile/hr)-(ft/s)" <<setw(21)<<"4.(ft/s)-(mile/hr)"<<endl<<endl
        <<setw(0)<<"5.(mile/hr)-(m/s)"<<setw(21)<<"6.(m/s)-(mile/hr)"<<endl<<endl
        <<setw(0)<<"7.(ft/s)-(m/s)"<<setw(21)<<"8.(m/s)-(ft/s)"<<endl<<endl
        <<setw(0)<<"9.(ft/s)-(km/hr)"<<setw(22)<<"10.(km/hr)-(ft/s)"<<endl<<endl
        <<setw(0)<<"11.(m/s)-(km/hr)"<<setw(21)<<"12.(km/hr)-(m/s)"<<endl;
        
    do{ 
    cout<<"....................................."<<endl;   
    cout<<"Choose one you  want to Convert="<<endl;
    cin>>x;
    
    
    if (x==1) 
    {
      cout<<setw(20)<<"..........." "(mile/hr - km/hr)""........." <<endl<<"Enter your Mile per hour=";
      cin>>M;
      K=M*1.609;
      cout<<"Converted Mile/hr to Kilometer/hr="<<K<<"km/hr";
    }  
    
    else if (x==2) 
    {
      cout<<setw(20)<<".........." "(km/hr - mile/hr)"".........." <<endl<<"Enter your Kilometer per hour=";
      cin>>K;
      M=K/1.609;
      cout<<"Converted Kilometer/hr to Mile/hr="<<M<<"m/hr";
    }  
    
     else if (x==3) 
    {
      cout<<setw(20)<<"..........." "(mile/hr - ft/s)"".........." <<endl<<"Enter your Mile per hour=";
      cin>>M;
      F=M*1.467;
      cout<<"Converted Mile/hr to Foot/s="<<F<<"f/s";
    }  
   
    else if (x==4) 
    {
      cout<<setw(20)<<"..........." "(ft/s - mile/hr)"".........." <<endl<<"Enter your Foot per Second=";
      cin>>F;
      M=F/1.467;
      cout<<"Converted  Foot/s to Mile/hr="<<M<<"m/hr";
    }  
   
    else if (x==5) 
    {
      cout<<setw(20)<<"..........." "(mile/hr - m/s)"".........." <<endl<<"Enter your Mile per hours=";
      cin>>M;
      m=M/2.237;
      cout<<"Converted Mile/hr to Metre/s ="<<m<<"m/s";
    }  
   
    else if (x==6) 
    {
      cout<<setw(20)<<"..........." "(m/s - mile/hr)""..........." <<endl<<"Enter your Metre per Second=";
      cin>>m;
      M=m*2.237;
      cout<<"Converted Metre/s to Mile/h="<<M<<"m/hr";
    }  
    
    else if (x==7) 
    {
      cout<<setw(20)<<"............." "(ft/s - m/s )""..........." <<endl<<"Enter your Foot per second=";
      cin>>F;
      m=F/3.281;
      cout<<"Converted Foot/s to Metre/s="<<m<<"m/s";
    }  
   
    else if (x==8) 
    {
      cout<<setw(20)<<"............." "(m/s - ft/s)""............" <<endl<<"Enter your Metre per second=";
      cin>>m;
      F=m*3.281;
      cout<<"Converted  Metre/s to Foot/s="<<F<<"ft/s";
    }  
   
    else if (x==9) 
    {
      cout<<setw(20)<<"............." "(ft/s - km/hr)"".........." <<endl<<"Enter your Foot per Second=";
      cin>>F;
      K=F*1.097;
      cout<<"Converted Foot/s  to Kilometer/hr="<<K<<"km/hr";
    }  
   
    else if (x==10) 
    {
      cout<<setw(20)<<"............" "(km/hr - ft/s)""..........." <<endl<<"Enter your Kilometer per hour=";
      cin>>K;
      F=K/1.097;
      cout<<"Converted Kilometer/hr to Foot/s="<<F<<"ft/s";
    }  
    
    
    else if (x==11) 
    {
      cout<<setw(20)<<"............" "(m/s - km/hr )""..........." <<endl<<"Enter your Metre per Second=";
      cin>>m;
      K=m*3.6;
      cout<<"Converted Metre/s to Kilometer/hr="<<K<<"km/hr";
    }  
   
    else if (x==12) 
    {
      cout<<setw(20)<<"............." "(km/hr - m/s)""..........." <<endl<<"Enter your Kilometer per hour=";
      cin>>K;
      m=K/3.6;
      cout<<"Converted Kilometer/hr to Metre/s="<<m<<"m/s";
    }  
    
    else
    {
    cout<<endl;
    cout<<setw(25)<<"(Invalid Choice)"<<endl;
    }
    cout<<endl;
    cout<<" Do another y or n=";
    cin>>ch;
    }while(ch=='y');
   }     
  
   
   void Mass ( )
  {
    int x;
    char ch;
    float k,g,m,p;
    cout<<setw(22)<<"[ MASS ]"<<endl;
    cout<<"....................................."<<endl;
    cout<<setw(5)<<"1.kg-g"<<setw(13)<<"2.g-kg"<<setw(15)<<"3.kg-mg"<<endl<<endl
        <<setw(5)<<"4.mg-kg" <<setw(13)<<"5.kg-lb"<<setw(15)<<"6.lb-min"<<endl<<endl
        <<setw(5)<<"7.g-mg"<<setw(13)<<"8.mg-g"<<setw(14)<<"9.g-lb"<<endl<<endl
        <<setw(5)<<"10.lb-g"<<setw(14)<<"11.mg-lb"<<setw(14)<<"12.lb-mg"<<endl;
        
    do{ 
    cout<<"....................................."<<endl;   
    cout<<"Choose one you  want to Convert="<<endl;
    cin>>x;
    
    
    if (x==1) 
    {
      cout<<setw(20)<<"..............." "( kg-g )"".............." <<endl<<"Enter your Kilograms=";
      cin>>k;
      g=k*1000;
      cout<<"Converted Kilogram to Gram="<<g<<"g";
    }  
    
    else if (x==2) 
    {
      cout<<setw(20)<<"..............." "( g-kg )"".............." <<endl<<"Enter your Grams=";
      cin>>g;
      k=g/1000;
      cout<<"Converted Gram to Kilograms="<<k<<"kg";
    }  
    
     else if (x==3) 
    {
      cout<<setw(20)<<".............." "( kg-mg )"".............." <<endl<<"Enter your Kilograms=";
      cin>>k;
      m=k*(1e+6);
      cout<<"Converted Kilogram to Miligram ="<<m<<"mg";
    }  
   
    else if (x==4) 
    {
      cout<<setw(20)<<".............." "( mg-kg )"".............." <<endl<<"Enter your Miligram=";
      cin>>m;
      k=m/(1e+6);
      cout<<"Converted  Miligram to Kilogram="<<k<<"kg";
    }  
   
    else if (x==5) 
    {
      cout<<setw(20)<<".............." "( kg-lb )"".............." <<endl<<"Enter your Kilograms=";
      cin>>k;
      p=k*2.205;
      cout<<"Converted Kilogram to Pound ="<<p<<"lb";
    }  
   
    else if (x==6) 
    {
      cout<<setw(20)<<".............." "( lb-kg )"".............." <<endl<<"Enter your Pound=";
      cin>>p;
      k=p/2.205;
      cout<<"Converted Pound to Kilogram="<<k<<"kg";
    }  
    
    else if (x==7) 
    {
      cout<<setw(20)<<"..............." "( g-mg )"".............." <<endl<<"Enter your Gram=";
      cin>>g;
      m=g*1000;
      cout<<"Converted Gram to Miligram="<<m<<"mg";
    }  
   
    else if (x==8) 
    {
      cout<<setw(20)<<"..............." "( mg-g )"".............." <<endl<<"Enter your Miligram=";
      cin>>m;
      g=m/1000;
      cout<<"Converted  Miligram to Gram="<<g<<"g";
    }  
   
    else if (x==9) 
    {
      cout<<setw(20)<<"..............." "( g-lb )"".............." <<endl<<"Enter your Gram=";
      cin>>g;
      p=g/453.6;
      cout<<"Converted Gram to Pound="<<p<<"lb";
    }  
   
    else if (x==10) 
    {
      cout<<setw(20)<<"..............." "( lb-g )"".............." <<endl<<"Enter your Pound=";
      cin>>p;
      g=p*453.6;
      cout<<"Converted Pound to Gram="<<g<<"g";
    }  
    
    else if (x==11) 
    {
      cout<<setw(20)<<".............." "( mg-lb )"".............." <<endl<<"Enter your Miligram=";
      cin>>m;
      p=m/453600;
      cout<<"Converted Miligram to Pound="<<p<<"lb";
    }  
   
    else if (x==12) 
    {
      cout<<setw(20)<<".............." "( lb-mg )"".............." <<endl<<"Enter your Pound=";
      cin>>p;
      m=p*453600;
      cout<<"Converted Pound to Miligam="<<g<<"g";
    }  
    
    else
    {
    cout<<endl;
    cout<<setw(25)<<"(Invalid Choice)"<<endl;
    }
    cout<<endl;
    cout<<" Do another y or n=";
    cin>>ch;
    }while(ch=='y');
   }     
  
  
  void Length ( )
  {
    int x;
    char ch;
    float k,M,m,c,f,i,y,I;
    cout<<setw(22)<<"[ LENGTH ]"<<endl;
    cout<<"....................................."<<endl;
    cout<<setw(0)<<"1.km-m"<<setw(10)<<"2.m-km"<<setw(11)<<"3.km-cm" <<setw(10)<<"4.cm-km" <<endl<<endl
        <<setw(0)<<"5.km-mm"<<setw(10)<<"6.mm-km"<<setw(9)<<"7.m-cm"<<setw(10)<<"8.cm-m"<<endl<<endl
        <<setw(0)<<"9.cm-mm"<<setw(11)<<"10.mm-cm"<<setw(10)<<"11.mi-yd"<<setw(10)<<"12.yd-mi"<<endl<<endl
       <<setw(0)<<"13.in-ft"<<setw(10)<<"14.ft-in"<<setw(10)<<"15.in-yd" <<setw(10)<<"16.yd-in" <<endl<<endl
        <<setw(0)<<"17.ft-yd"<<setw(10)<<"18.yd-ft"<<setw(10)<<"19.ft-mi"<<setw(10)<<"20.mi-ft"<<endl;
        
        
    do{ 
    cout<<"....................................."<<endl;   
    cout<<"Choose one you  want to Convert="<<endl;
    cin>>x;
    
    
    if (x==1) 
    {
      cout<<setw(20)<<"..............." "( km-m )"".............." <<endl<<"Enter your Kilometer=";
      cin>>k;
      M=k*1000;
      cout<<"Converted Kilmeter to Meter="<<M<<"m";
    }  
    
    else if (x==2) 
    {
      cout<<setw(20)<<"..............." "( m-km )"".............." <<endl<<"Enter your Meter=";
      cin>>M;
      k=M/1000;
      cout<<"Converted Meter to Kilometer="<<k<<"km";
    }  
    
     else if (x==3) 
    {
      cout<<setw(20)<<".............." "( km-cm )"".............." <<endl<<"Enter your Kilometer=";
      cin>>k;
      c=k*100000;
      cout<<"Converted Kilometer to centimeter ="<<c<<"cm";
    }  
   
    else if (x==4) 
    {
      cout<<setw(20)<<".............." "( cm-km )"".............." <<endl<<"Enter your Centimeter=";
      cin>>c;
      k=c/100000;
      cout<<"Converted  Centimeter to Kilometer="<<k<<"km";
    }  
   
    else if (x==5) 
    {
      cout<<setw(20)<<".............." "( km-mm )"".............." <<endl<<"Enter your Kilometer=";
      cin>>k;
      m=k*(1e+6);
      cout<<"Converted Kilometer to Milimeter="<<m<<"mm";
    }  
   
    else if (x==6) 
    {
      cout<<setw(20)<<".............." "( mm-km )"".............." <<endl<<"Enter your Milimeter=";
      cin>>m;
      k=m/(1e+6);
      cout<<"Converted Milimeter to Kilometer="<<k<<"km";
    }  
    
    else if (x==7) 
    {
      cout<<setw(20)<<"................" "( m-cm)"".............." <<endl<<"Enter your Meter=";
      cin>>M;
      c=M*100;
      cout<<"Converted Meter to Centimeter="<<c<<"cm";
    }  
   
    else if (x==8) 
    {
      cout<<setw(20)<<"..............." "( cm-m )"".............." <<endl<<"Enter your Centimeter=";
      cin>>c;
      M=c/100;
      cout<<"Converted  Centimeter to Meter="<<M<<"m";
    }  
   
    else if (x==9) 
    {
      cout<<setw(20)<<".............." "( cm-mm )"".............." <<endl<<"Enter your Centimeter=";
      cin>>c;
      m=c*10;
      cout<<"Converted Centimeter to Milimeter="<<m<<"mm";
    }  
   
    else if (x==10) 
    {
      cout<<setw(20)<<".............." "( mm-cm )"".............." <<endl<<"Enter your Milimeter=";
      cin>>m;
      c=m/10;
      cout<<"Converted Milimeter to Centimeter="<<c<<"cm";
    }  
    
    else if (x==11) 
    {
      cout<<setw(20)<<".............." "( mi-yd )"".............." <<endl<<"Enter your Mile=";
      cin>>I;
      y=I*1760;
      cout<<"Converted Mile to Yard="<<y<<"yd";
    }  
   
    else if (x==12) 
    {
      cout<<setw(20)<<".............." "( yd-mi )"".............." <<endl<<"Enter your Yard=";
      cin>>y;
      I=y/1760;
      cout<<"Converted Yard to Mile="<<I<<"mile";
    }  
    
    if (x==13) 
    {
      cout<<setw(20)<<".............." "( in-ft )"".............." <<endl<<"Enter your Inches=";
      cin>>i;
      f=i/12;
      cout<<"Converted Inches to Feet="<<f<<"ft";
    }  
    
    else if (x==14) 
    {
      cout<<setw(20)<<".............." "( ft-in )"".............." <<endl<<"Enter your Feet=";
      cin>>f;
      i=f*12;
      cout<<"Converted Feet to Inches="<<i<<"in";
    }  
    
     else if (x==15) 
    {
      cout<<setw(20)<<".............." "( in-yd )"".............." <<endl<<"Enter your Inches=";
      cin>>i;
      y=i/36;
      cout<<"Converted Inches to Yard ="<<y<<"yd";
    }  
   
    else if (x==16) 
    {
      cout<<setw(20)<<".............." "( yd-in )"".............." <<endl<<"Enter your Yard=";
      cin>>y;
      i=y*36;
      cout<<"Converted  Yard to Inches="<<i<<"in";
    }  
   
    else if (x==17) 
    {
      cout<<setw(20)<<".............." "( ft-yd )"".............." <<endl<<"Enter your Feet=";
      cin>>f;
      y=f*3;
      cout<<"Converted Feet  to Yard="<<y<<"yd";
    }  
   
    else if (x==18) 
    {
      cout<<setw(20)<<".............." "( yd-ft )"".............." <<endl<<"Enter your Yard=";
      cin>>y;
      f=y/3;
      cout<<"Converted Yard to Feet="<<f<<"ft";
    }  
    
    else if (x==19) 
    {
      cout<<setw(20)<<".............." "( ft-mi )"".............." <<endl<<"Enter your Feet=";
      cin>>f;
      I=f/5280;
      cout<<"Converted Feet to Mile="<<I<<"mile";
    }  
   
    else if (x==20) 
    {
      cout<<setw(20)<<".............." "( mi-ft )"".............." <<endl<<"Enter your Mile=";
      cin>>I;
      f=I*5280;
      cout<<"Converted  Mile to Feet="<<f<<"ft";
    }  
    
      else if (x>20)
    {
       cout<<endl;
       cout<<setw(25)<<"(Invalid Choice)"<<endl;
    }
    
    cout<<endl;
    cout<<" Do another y or n=";
    cin>>ch;
    }while(ch=='y');
   }     
  
  
  
    void Storage ( )
  {
    int x;
    char ch;
    float k,g,t,m;
    cout<<setw(28)<<"[ DIGITAL STORAGE ]"<<endl;
    cout<<"....................................."<<endl;
    cout<<setw(5)<<"1.Kb-Mb"<<setw(14)<<"2.Mb-Kb"<<setw(14)<<"3.Kb-Gb"<<endl<<endl
        <<setw(5)<<"4.Gb-Kb" <<setw(14)<<"5.Kb-Tb"<<setw(14)<<"6.Tb-Kb" <<endl<<endl
        <<setw(5)<<"7.Mb-Gb"<<setw(14)<<"8.Gb-Mb"<<setw(14)<<"9.Mb-Tb"<<endl<<endl
        <<setw(6)<<"10.Tb-Mb"<<setw(14)<<"11.Gb-Tb"<<setw(14)<<"12.Tb-Gb"<<endl;
        
    do{ 
    cout<<"....................................."<<endl;   
    cout<<"Choose one you  want to Convert="<<endl;
    cin>>x;
    
    
    if (x==1) 
    {
      cout<<setw(20)<<"..............." "( Kb-Mb )""............." <<endl<<"Enter your Kilobyte=";
      cin>>k;
      m=k/1000;
      cout<<"Converted Kilobyte to Migabyte="<<m<<"mb";
    }  
    
    else if (x==2) 
    {
      cout<<setw(20)<<"..............." "( Mb-Kb )""............." <<endl<<"Enter your Megabyte=";
      cin>>m;
      k=m*1000;
      cout<<"Converted Megabyte to Kilobyte="<<k<<"kb";
    }  
    
     else if (x==3) 
    {
      cout<<setw(20)<<".............." "( Kb-Gb )"".............." <<endl<<"Enter your Kilobyte=";
      cin>>k;
      g=k/(1e+6);
      cout<<"Converted Kilobyte to Gigabyte ="<<g<<"gb";
    }  
   
    else if (x==4) 
    {
      cout<<setw(20)<<".............." "( Gb-Kb )"".............." <<endl<<"Enter your Gigabyte=";
      cin>>g;
      k=g*(1e+6);
      cout<<"Converted  Gigabyte to Kilobyte="<<k<<"kb";
    }  
   
    else if (x==5) 
    {
      cout<<setw(20)<<".............." "( Kb-Tb )"".............." <<endl<<"Enter your Kilobyte=";
      cin>>k;
      t=k/(1e+9);
      cout<<"Converted Kilobyte to Terabyte ="<<t <<"tb";
    }  
   
    else if (x==6) 
    {
      cout<<setw(20)<<"..............." "( Tb-Kb )""............." <<endl<<"Enter your Terabyte=";
      cin>>t;
      k=t*(1e+9);
      cout<<"Converted Terabyte to Kilobyte="<<k<<"kb";
    }  
    
    else if (x==7) 
    {
      cout<<setw(20)<<"..............." "( Mb-Gb)"".............." <<endl<<"Enter your Megabyte=";
      cin>>m;
      g=m/1000;
      cout<<"Converted Megabyte to Gigabyte="<<g<<"gb";
    }  
   
    else if (x==8) 
    {
      cout<<setw(20)<<"..............." "( Gb-Mb )""............." <<endl<<"Enter your Gigabyte=";
      cin>>g;
      m=g*1000;
      cout<<"Converted  Gigabyte to Megabyte="<<m<<"mb";
    }  
   
    else if (x==9) 
    {
      cout<<setw(20)<<"..............." "( Mb-Tb )""............." <<endl<<"Enter your Megabyte=";
      cin>>m;
      t=m/(1e+6);
      cout<<"Converted Megabyte to Terabyte="<<t<<"tb";
    }  
   
    else if (x==10) 
    {
      cout<<setw(20)<<"..............." "( Tb-Mb)"".............." <<endl<<"Enter your Terabyte=";
      cin>>t;
      m=t*(1e+6);
      cout<<"Converted Terabyte to Megabyte="<<m<<"mb";
    }  
    
    else if (x==11) 
    {
      cout<<setw(20)<<"..............." "( Gb-Tb )""............." <<endl<<"Enter your Gigabyte=";
      cin>>g;
      t=g/1000;
      cout<<"Converted Gigabyte to Terabyte="<<t<<"tb";
    }  
   
    else if (x==12) 
    {
      cout<<setw(20)<<"..............." "( Tb-Gb)"".............." <<endl<<"Enter your Terabyte=";
      cin>>t;
      g=t*1000;
      cout<<"Converted Terabyte to Gigabyte="<<g<<"gb";
    }  
    
    else
    {
    cout<<endl;
    cout<<setw(25)<<"(Invalid Choice)"<<endl;
    }
    cout<<endl;
    cout<<" Do another y or n=";
    cin>>ch;
    }while(ch=='y');
   }     
  
  
  
  
   
  
    
