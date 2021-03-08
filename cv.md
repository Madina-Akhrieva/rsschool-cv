# Madina Akhrieva
## Contacts  
Telegram: [Madina Akhrieva](https://t.me/MadinaAR1)  
GitHub: [Madina Akhrieva](https://github.com/Madina-Akhrieva)  
E-mail: <akhrieva03@gmail.com>   
Telephone number: +375336970506
## Summary
In order to achieve goals,  do everything in my power. I am very focused. If there is some unsolved task, I can't stop until succeed in it. Now I am determined to learn hard and become a front-end developer. 
## Skills  
- C/C++
- OOP  
- HTML/CSS
- Manual testing 
- English(B1)  
## Code example
~~~ 
void Room_inf::sortirovka(Room_inf& room, ifstream& file_name)
{
  vector<Room_inf>room_inf;
  room.fill_vector<Room_inf>("room_information.txt", room_inf, file_name,room);
  cout << "\tВывод номеров по порядку" << endl;

  for (auto& left : room_inf)
  
    for (auto& right : room_inf)
    
      if (left.number_of_places < right.number_of_places)
        swap(left, right);
    
  
  fort::char_table table;
  table << fort::header << "№" << "Кол-во мест" << "Тип" << "Цена";
  for (const auto& inf_room : room_inf)
  {

    table << fort::endr << inf_room.room_number << inf_room.number_of_places <<
      inf_room.type << inf_room.price << fort::endr;

  }
  cout << table.to_string() << endl;
}
~~~
## Working experience
- Course in Software testing in IQ LAB  
- Second course in Belarussian State University of Informatics and Radio electronics
- IT Academy "Front-end developer"
## Education
University: Belarasian State University of Information and Radioelectronics  
Speciality: Information Systems and Technologies (in economics)  
Graduation year: 2023
