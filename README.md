# CharacterCreator

Task: Create a commandline driven character creator.

## First iteration:
1. Create a attribute system. The system should contain 3 primary attributes: Strength, Agility and Intelligence.
2. Create a class system. The system should contain 3 classes: Warrior, Rogue and Mage.
3. Create a character object. A character should have a name, level, attributes, damage (baseline 1), dps (baseline: damage * 100 / 60), armor (baseline 0) and a equipment list
4. Create a equipment system. The system should allow for the creation of items in the following slots: Head, body, pant and weapon. Each item should have its own stats and level.

## Second iteration
1. Connect the attribute system to each class. Each class should have a diffrent attribute distribution:

  *Warrior: 3, 1, 1*
  
  *Rogue: 1, 3, 1*
  
  *Mage: 1, 1, 3*
  
2. Create a level up method, that increases a characters level and attributes. Use the following template to determine attribute scaling:

  *Warrior: 2, 1, 1*
  
  *Rogue: 1, 2, 1*
  
  *Mage: 1, 1, 2*
  
3. Create a method that displays a characters information.
4. Create a commandline interface that allows the user to create a character by giving a name and choosing a class.
  
## Third iteration
1. Implement a armor type system (Mail, Leather, Cloth). Each armor piece should have a armor value.
2. Implement a weapon type system (Sword, Bow, Staff). Each weapon should have a damage value.
3. Implement a inventory system, that allows a character to equip a item. Each item should only be equipable in their respective slot: Head item in head slot etc.
4. Implement a equipment restriction system. Restrict what item types each class can equip:
  
  *Warrior: Mail and Sword*
  
  *Rogue: Leather and Bow*
  
  *Mage: Cloth and Staff*
  
5. Implement attribute, damage and armor scaling based on what items are equipped.
