# Login
#include <iostream>
#include <fstream>
#include <vector>
#include <algorithm>
#include <functional>
#include <math.h>

    //Piocent Software
    /*Copyright (C) 2021 Soren R. Stauss - All Rights Reserved
     *You many use, distribute or modify any or all this code under the terms of the fully executed 
     *Piocent software license agreement.
    */ 
    //Add #include <bits/stdc++.h special header for experiment model, though not ideal for r/w use. 


void printThis (int d) {
    std::cout << "The current year is " << d << std::endl;

}

int main()
{

    int a = {2024};
    int b = {2000};
    int c = {2018};
    int d = {2019};
    int e = {2020};
    int f = {2021};
    

    printThis (d); //Figure out end line issue.

    if (f>b) {
        std::cout << "Domain age is definitely acceptable. \n \n";
    }

    decltype(a+b) sum = a > b;

    std::cout << "Hey there, Soren! \n \n";
    std::cout << "First, what year was the domain registered? \n \n";   //eventually will scrape WHOIS for domain age.
    
    if (2020) {
        std::cout << "Since it was just registered in 2020, the domain age is suspicious. \n \n";
    }

    if (1999) {
        std::cout <<"The domain age is acceptable, as it has been registered since 1999. \n \n";

    }
        std::cout << "Copyright (C) 2021 Soren R. Stauss - All Rights Reserved";

    return 0;
}
