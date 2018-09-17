# LEGO_POSTMAN

1. Vi specifierar en koordinat som är "1, 2.5" för uppgift 1, "1, -2.5" för uppgift 2, "0, 2.5" för uppgift 3 och "0, -2.5" för uppgift 4.
2.5 betyder höger om vägen, -2.5 betyder till vänster. 1 betyder närmsta väggen och 0 betyder väggen som är tvärsom.
2. Om koordinaten är "1" så roterar roboten och mäter distans med sonicmätaren i 1 grader interval 
tills den hittar ett min värde mellan 40 cm < x < 60 cm och roterar tillbaka till mindistansen. Distanserna kan läggas i en array.
3. Annars om koordinaten är "0" blir mindistansen 60 > x > max så att den riktas mot mitten av andra väggen.
4. Vi använder distansen "2.5" eller "-2.5" och mindistansen för att räkna ut hypotenusa och vinkeln mellan roboten och leveransplatsen.
5. Roboten roterar enligt vinkeln och sedan kör fram enligt hypotenusans längd, den släpper boken och sedan backar tillbaka samma distans.