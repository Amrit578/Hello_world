#include <iostream>

using namespace std;

void bubbleSort(int arr[], int num)
{
    for( int i = 0; i < num;i++)
    {
        for(int j = 0; j < num-i-1;j++)
        {
            if(arr[j] > arr[j+1])
            {
                int temp = arr[j];
                arr[j] = arr[j+1];
                arr[j+1] = temp;
            }
        }
    }
}

int main()
{
    int num;
    cout<<"Enter the size of array : ";
    cin>>num;

    int arr[num];
    cout<<"Enter the element : ";
    for(int i = 0; i < num; i++)
    {
        cin>>arr[i];
    }
    cout<<"Before sorting :" <<endl;

    for(int i = 0; i < num; i++ )
    {
        cout<< arr[i] << "  ";

    }

    bubbleSort(arr,num);

    cout<< endl << "After sorting : " << endl;

    for(int i = 0; i < num; i++)
    {
        cout<<arr[i] << "  ";
    }
    return 0;
}
