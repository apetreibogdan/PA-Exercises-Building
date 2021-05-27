# PA-Exercises-Building
First step

A building is described by an address (string), an area, and the number of rooms

    Create the Building class described above.

    Write a new class, Launcher, with a printBuildingsWithMoreThan3Rooms method, which, given a list of buildings, will display buildings with more than 3 rooms.

    In Launcher class add a main method that will:

    Creates 5 new building instances

    Call the printBuildingsWithMoreThan3Rooms method on this list
  
Second step

    The building has several rooms, and for each room more data is needed. Each room is painted in one color, and has a type (enum: LIVING_ROOM, BEDROOM, KITCHEN). The camera color can NOT be changed after initialization.

    You are allowed to modify only the Building class for the new functionality (and in Launcher, for initializing the buildings)

    We are not allowed to change the code in printBuildingsWithMoreThan3Rooms.

    On Building class, implement a method that finds (returns) only red-painted rooms

Third step

    We have a special type of room, Library, in which we have several books. Each book has a title, an author (string) and a category (name: SF, DRAMA, etc)

      Library rooms have the type set as `LIBRARY`, and we cannot modify it
      
    When we initialize an object of type Library, we must be able to give it the list of books in that library, but we can also omit the list.
    
    On Library, we need to be able to add books to the list
    
    On the Library, write a method that returns the author who wrote the most books
    
    
Fourth step

    A person has a house (Building), with several rooms, some of which are of the Library type. In addition, he also has zero or more tablets / ebook readers where he has books in digital format

    Extract the common functionality between Library and EbookReader

    Write a method, which, given a list that can have both Library and EbookReader objects, finds the book with a given title.

    Use the method above to determine if a Person has a particular book



    
