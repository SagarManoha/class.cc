#include <iostream>
using namespace std;
class room
{
	public:
		float length;
		float breadth;
		float height;
		float calcultae_area()
	{
		return length*breadth;
	}
	float calculate_volume()
	{
	return length*breadth*height;	
	}			
};
int main()
{
	//to calculate the area of 1st room out of two rooms.
	room r1;
	r1.length=40.5;
	r1.breadth=50.6;
	r1.height=80.6;
	cout<<"the area of 1st room :"<<r1.calcultae_area()<<endl;
	cout<<"the volume of 1st room :"<<r1.calculate_volume()<<endl;
	//to calculate the area of 2nd room out of two rooms.
	room r2;
	r2.length=40.5;
	r2.breadth=50.6;
	r2.height=80.6;
	cout<<"the area of 2nd room :"<<r2.calcultae_area()<<endl;
	cout<<"the volume of 2nd room :"<<r2.calculate_volume()<<endl;
	return 0;
}


