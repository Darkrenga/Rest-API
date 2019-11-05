# Rest-API

&#x200B;

* GET 
   * Få fat I data
      * Alle brugere (functions.php / Kalder GET uden parametere)
      * Specifik bruger (functions.php?id=x / Kalder GET med ID, skal være INT)

&#x200B;

* PUT
   * Skab ny bruger
      * Create (functions.php / Kalder PUT uden parametre)
      * I bodye'en skal $username og etc. parses.
   * Opdater eksisterende
      * Update(functions.php?id=x / Kalder PUT med ID, skal være INT)

&#x200B;

* DELETE
   * Slet en bruger
      * Delete (functions.php?id=x / Kalder DELETE med ID, skal være INT)
