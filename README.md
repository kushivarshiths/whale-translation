# whale-translation
a code that makes you understand to look nested loops as two different loops working independently and also add concept of vectors

#include<iostream>
#include<vector>
int main(){
std::string input = "hi, human\n";
std::vector <char> vowels = {'a','e','i','o','u'};
std::vector <char> result;
for(int i = 0; i < input.size(); i++){
for(int j = 0; j < vowels.size(); j++){
if(input[i] == vowels[j]){
  result.push_back(input[i]);
}
}
if(input[i] == 'e' || input[i] == 'u'){
   result.push_back(input[i]);
}
}
for(int i = 0; i < result.size(); i++){
std::cout << result[i];}


}

