```dart
class Yannai extends Carbon-Based_Bipedal_Life-form{
  static const name = "Yannai Gradwohl";
  static int age = 14;
  

  static const hobbies = [
  'Books',
  'Movies',
  'Cooking',
  'Programming', 
  'Breathing',
  
  ];

  
  static const interests = [
  'cybersecurity',
  'computers',
  'physics',
  'anything linked to new tech',
  
  ];

  
  dynamic actions(bool isTired, bool isBored){
    if(isTired && !isBored){
      return self.sleep();
    } 
    else if(isTired && isBored){
      return self.readBooks();
    }
    else if(!isTired && !isBored){
      return self.doCode();
    }
    retun self.exist();
  }

  

}
```
