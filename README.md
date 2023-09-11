# YASWANTH KANAKALA
### My favourite vacation spot is Maldives.

The Maldives is renowed for its perfect **natural beauty and stunning landscapes**.<br>
This is a perfect vacation spot with luxurious resorts and also popular for diverse marine life.<br>
Apart from natural beauty, one can enjoy various **water sports and adventure activities**.  

---

### Things You must do at Maldives 
1. Water sports is the number one thing to do in the Maldives with friends. 
2. Scuba Diving at Maaya Thila
3. Snorkeling at Maafushi Island
4. Enjoy Sunset Cruise 
5. Para Sailing in maldives gives the best experience ever.

 ### Dishes you must try at Maldives

 * Garudhiya - Fish Soup
 * Mas Huni - Shredded Smoked Tuna
 * Masroshi - Tuna Stuffed Chapati
 * Maldivian Live Lobster
 * Biyadhoo Special & Lucky And AI

 [My Status](my2-kanakala/MyStats.md)
  
---
### Sports one must play

|Name of the Sport |Reason | Time_Spent |
| :--- |:--- |:--- |
| Badminton |This game is a workout for the entire body and increases focus.|28hrs per week  |
| Cricket |This game allows to gain team co-ordination and mental and physical strength|15hrs per week |
| Basket Ball |Increase Strength and Endurance and hand eye co-ordination |14hrs per week  |
| Boxing |Helps to increase Self Defense techniques, mobility and physical Strength |10hrs per week  |

---
### Pithy Quotes 

>“If we knew what it was we were doing, it would not be called research, would it?” – *Albert Einstein*<br>
>“The scientist only imposes two things, namely truth and sincerity, imposes them upon himself and upon other scientists.” – *Erwin Schrödinger*

---
### Code Fencing with jquery 

>Calculate distance between Mouse and the Edges of a DOM element? <https://stackoverflow.com/questions/50906224/calculate-distance-between-mouse-and-the-edges-of-a-dom-element>

```
(function() {
    
    var mX, mY, distance,
        $distance = $('#distance span'),
        $element  = $('#element');

    function calculateDistance(elem, mouseX, mouseY) {
        return Math.floor(Math.sqrt(Math.pow(mouseX - (elem.offset().left+(elem.width()/2)), 2) + Math.pow(mouseY - (elem.offset().top+(elem.height()/2)), 2)));
    }

    $(document).mousemove(function(e) {  
        mX = e.pageX;
        mY = e.pageY;
        distance = calculateDistance($element, mX, mY);
        $distance.text(distance);         
    });

})(); 
```
**Source:**<https://css-tricks.com/snippets/jquery/calculate-distance-between-mouse-and-element/>
