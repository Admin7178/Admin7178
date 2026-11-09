```dart
class Yannai extends CarbonBased_Bipedal_Lifeform{
  static const name = "Yannai Gradwohl";
  static int age = 14;
  static final preferredOS = "Kali Linux";

  static final traits = [
    'nerd',
    'bookworm',
    'book/movie geek',
    'Doctor who fan',
    'bad at remembering names',
  ];

  static const hobbies = {
  'Books': 'Addicted since i was four',
  'Movies': 'sucker for fantasy/sci-fi',
  'Music': 'most any kind is awesome',
  'Cooking': 'food is incredible',
  'Programming': 'interested since i was 9',
  'Breathing': 'since i left my moms womb, procceeding nicely',
  };

  
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
