#include<iostream>
#include<string>
using namespace std;
class Book
   {
    private:
    string title;
    string author;
    string ISBN;
    double price;
    
    public:
    void recordbook()
    {
        cout<<"Enter book title:";
        getline(cin,title);
        cout<<"Enter Author name:";
        getline(cin,author);
        cout<<"Enter ISBM:";
        getline(cin,ISBN);
        cout<<"Enter book price:";
        cin>>price;
        cin.ignore();  
    }
       void displaybook()
       {
       cout<<"\n====BOOK DETAILS====\n";
       cout<<"BOOK TITLE:"<<title<<endl;
       cout<<"AUTHOR NAME:"<<author<<endl;
       cout<<"ISBN:"<<ISBN<<endl;
       cout<<"BOOK PRICE:"<<price<<endl;
       }
};

int main()
{
    Book b;
    b.recordbook();
    b.displaybook();
    
    return 0;
}
