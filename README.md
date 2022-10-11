# Classes
class Car{
protected:
int id=0;
string model="";
public:
Car(){
this->id=id;
this->model=model;
}
};

class BMW : public Car{
private:
int speed=0;
public:
BMW(){
this->speed=speed;
}
};