#include <iostream>
using namespace std;
int main(){

    int metros,metrosf;
    float cm,cmf,res,res1,res4,res2,res3,res5;

    cout<<"Metros Inicial:";
        cin>>metros;
    cout<<"Cemtrimetros Iniciales:";
        cin>>cm;
    cout<<"Metros Finales:";
        cin>>metrosf;
    cout<<"Cemtrimetros Finales:";
        cin>>cmf;

    res=cm/100.00;
    res1=cmf/100.00;
	res3=metros+res;
    res4=metrosf+res1;

    res2=res4-res3;

    if (res2==0)
    {
        cout<<"No avanzaste nada";
    }
    else if (res2>=0)
    {
        cout<<"Avanzaste:"<<res2<<" m";
    }
    else
    {
        res5=res2*(-1.00);
        cout<<"Retrocediste:"<<res5<<" m";
    }
    return 0;
}
