
<img src="https://github.com/talos-robotics/Pocket-breille-project/blob/main/images/pocketbreille.png" width="350" height="500">

# The Pocket breille project

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d3/Cc_by-nc_icon.svg/1920px-Cc_by-nc_icon.svg.png" alt="" width="150" height="50"/>

<div>
  
## <u>Το πρόβλημα</u>

Όλες οι αισθήσεις στη ζωή του κάθε ανθρώπου είναι πολύ σημαντικές. Μια από τις σημαντικότερες όμως, που η στέρησή της επηρεάζει πολύ σημαντικά τη ζωή του ατόμου είναι η όραση. Έχουμε φανταστεί άραγε τον εαυτό μας χωρίς αυτή; Έχουμε κλείσει έστω και για λίγο τα μάτια μας και να προσπαθήσουμε να κάνουμε ακόμα και το πιο απλό πράγμα της καθημερινότητας μας; Σίγουρα θα είναι πάρα πολύ δύσκολο ακόμα και να περπατήσουμε.
Με αυτό το project θα προσπαθήσουμε να βοηθήσουμε τους ανθρώπους αυτούς στην καθημερινότητα τους.


## <u>Η λύση</u>

Το project αναφέρεται στη δημιουργία ενός φορητού, μικρού σε μέγεθος και εύχρηστου πληκτρολογίου για τη μέθοδο γραφής breille.  Το σύστημα θα ενσωματώνει λειτουργίες αναγνώρισης του κώδικα breille, αυτόματη μετατροπή του κώδικα σε γράμμα ή σύμβολο, αποστολή του κάθε γράμματος μέσω της θύρας usb σε αντίστοιχο λογισμικό στον υπολογιστή που είναι συνδεμένη η συσκευή. 
Στη μεριά του υπολογιστή θα κατασκευάσουμε λογισμικό το οποίο θα λειτουργεί σαν απλός κειμενογράφος για ανθρώπους με προβλήματα όρασης. Θα ενσωματώσουμε τεχνολογία τεχνητής νοημοσύνης TTS (Text to speech) έτσι ώστε το άτομο να μπορεί να ακούει αυτά που γράφει και να διαχειρίζεται το περιβάλλον ακουστικά.
Το σύστημα θα υποστηρίζεται από φορητό υπολογιστή παλάμης.

Θα ασχοληθούμε με,

- Μικροελεγκτές Arduino
- Γλώσσα προγραμματισμού C++
- Γλώσσα προγραμματισμού Python
- Κατασκευή GUI με τη χρήση Tkinter
- Κατασκευή υπολογιστή παλάμης με τη χρήση raspberry pi για την ενσωμάτωση του λογισμικού
- Χρήση τεχνολογίας TTS
- Linux distributions σαν βασικό περιβάλλον εργασίας και δημιουργίας
- 3d εκτυπώσεις για τη φιλοξενία του εξοπλισμού


</div>

<div style="text-align: left; ">

## <u>Συμμετέχοντες</u>

### Υπεύθυνος εκπαιδευτικός

Μανούσακας Μανούσος - Εκπαιδευτικός Πληροφορικής ΠΕ86

### Μαθητές



</div>

<div>

# <u>Γενικά στοιχεία σεναρίου</u>

## Σενάριο δραστηριότητας

Αριθμός μαθητών: 8  
Αριθμός Ομάδων: 4  
Αριθμός ατόμων ανά ομάδα: 2  
Είδος δραστηριότητας: Ομαδοσυνεργατική  
Ρόλοι: Δεν υπάρχουν διακριτοί ρόλοι στην ομάδα.  
Ηλικιακή ομάδα: 12-15  

## Φάση προετοιμασίας

Οι μαθητές θα πρέπει να:  
- Διερευνήσουν στο διαδίκτυο σχετικά με το θέμα.
- Να αναζητήσουν τις ανάγκες που μπορεί να έχουν οι άνθρωποι με τύφλωση.
- Να αναζητήσουν τη μέθοδο γραφής breille και να ανακαλύψουν τον κώδικά της.
- Συντάξουν ένα έντυπο όπου θα περιγράφουν τις προδιαγραφές του project.
- Να αναζητήσουν στο διαδίκτυο πληροφορίες για τον τρόπο λύσης και τις επιλογές του υλικού.  

## Φάση σχεδιασμού

Οι μαθητές θα πρέπει να:
- Να αναζητήσουν στο διαδίκτυο πληροφορίες για τη συνδεσμολογία του υλικού με το Arduino.
- Να αναζητήσουν στο διαδίκτυο πληροφορίες για τις προδιαγραφές των αισθητήρων.
- Να δημιουργήσουν στο Fritzing τις παραπάνω συνδεσμολογίες.  

## Φάση υλοποίησης

Οι μαθητές θα πρέπει να:  
- Δημιουργήσουν τις φυσικές συνδέσεις των υλικών τους.
- Να προγραμματίσουν το Arduino χρησιμοποιώντας το περιβάλλον Arduino IDE έτσι ώστε να μετατρέπει κάθε γράμμα σε breille σε γράμμα της αλφαβήτου και να το στέλνουν μέσω usb σειριακά στον υπολογιστή.
- Να δημιουργήσουν πρόγραμμα με τη χρήση της γλώσσας python που θα λαμβάνει το γράμμα που εχει αποσταλεί σειριακά
- Να δημιουργήσουν πρόγραμμα με τη χρήση του python interface έτσι ώστε να δημιουργήσουν ενα GUI καλάληλα κατασκευασμένο για χρήση απο τυφλά άτομα.
- Να ενσωματώσουν τεχνολογία τεχνιτής νοημοσύνης TTS έτσι ώστε να γίνεται η λειτουργία του προγράμματος ακουστικά. Για παράδειγμα σε περίπρωση που το ποντίκι περάσει πάνω απο κάποιο κουμπί να γίνεται ανάγνωση της επιγραφής του.


## Φάση Δοκιμών

Οι μαθητές θα πρέπει να:  
- Δοκιμάσουν τον εξοπλισμό τους και να επιβεβαιώσουν τη σωστή λειτουργία του.  
  
  
## Open Educational Resources
  <img src="/images/oer.jpg" style="width:70%;">

# Υλικά ηλεκτρονικά

|Είδος|Ποσότητα|Τιμή Μονάδας|Σύνολο|Περιγραφή|
|---|---|---|---|---|
|<img src="https://grobotronics.com/images/thumbnails/350/350/detailed/116/shop-google-4gb-images_1024x1024_grobo.jpg" style="width:30%;"></BR>Raspberry Pi 4 - Model B - 4GB|1|79.90|79.90|https://grobotronics.com/raspberry-pi-4-model-b-4gb.html|
|<img src="https://grobotronics.com/images/thumbnails/350/350/detailed/100/df3f83b0-040d-438e-b989-b8f4a0c5cb84_gd7c-al_grobo.jpg" style="width:30%;"></BR>Push Button Latching - 12.5mm Red|8|0.50|4.00|https://grobotronics.com/push-button-latching-12.5mm-red.html|
|<img src="https://grobotronics.com/images/thumbnails/350/350/detailed/125/arduino-proto-shield-rev3-uno-size-arduino-tsx00083-30396168798403_700x_grobo.jpg" style="width:30%;"></BR>Proto Shield Rev3 (Uno Size)|1|14.80|14.80|https://grobotronics.com/proto-shield-rev3-uno-size.html|
|<img src="https://grobotronics.com/images/thumbnails/350/350/detailed/127/hr0064-1_grobo.jpg" style="width:30%;"></BR>Uno SMD Compatible - CH340|1|9.90|9.90|https://grobotronics.com/compatible-uno-smd-ch340.html|
|<img src="https://grobotronics.com/images/thumbnails/350/350/detailed/103/4inch-hdmi-lcd-5_-_%CE%91%CE%BD%CF%84%CE%AF%CE%B3%CF%81%CE%B1%CF%86%CE%BF_grobo.jpg" style="width:30%;"></BR>Pi Display 4" HDMI 800x480 IPS Resistive Touchscreen|1|44.90|44.90|https://grobotronics.com/pi-display-4-hdmi-800x480-ips-resistive-touchscreen.html|
|<img src="https://grobotronics.com/images/thumbnails/350/350/detailed/126/primaselect-pla-chameleon-1-75mm-750-g-blue-green-ps-plac-175-0750-bg-26992_3_grobo.jpg" style="width:30%;"></BR>Νήμα PLA Chameleon 1.75mm PrimaSelect - Μπλε/Πράσινο 750g|1|34.90|34.90|https://grobotronics.com/primaselect-pla-chameleon-1.75mm-750g-spool-blue-green.html|
||||||
|||Σύνολο|188.4||
|||||| 

  
</div>


# Θεωρητικό μέρος
___


# :memo: **Ενότητα 1**:<br>
 ## Τεχνητή Νοημοσύνη
  <div align="left">
      <a href="https://www.youtube.com/watch?v=i0Ig3LdG-p4">
         <img src="https://img.youtube.com/vi/i0Ig3LdG-p4/0.jpg" style="width:30%;">
      </a>
      <a href="https://www.youtube.com/watch?v=0dKkMS5-0jA">
         <img src="https://img.youtube.com/vi/0dKkMS5-0jA/0.jpg" style="width:30%;">
      </a>
      <a href="https://www.youtube.com/watch?v=7a2aNF-dRo8">
         <img src="https://img.youtube.com/vi/7a2aNF-dRo8/0.jpg" style="width:30%;">
      </a>
      <a href="https://www.youtube.com/watch?v=20VNny661UY">
         <img src="https://img.youtube.com/vi/20VNny661UY/0.jpg" style="width:30%;">
      </a>
      <a href="https://www.youtube.com/watch?v=67ik8tnxqlE">
         <img src="https://img.youtube.com/vi/67ik8tnxqlE/0.jpg" style="width:30%;">
      </a>
      <a href="https://www.youtube.com/watch?v=yUSj9VsM82U">
         <img src="https://img.youtube.com/vi/yUSj9VsM82U/0.jpg" style="width:30%;">
      </a>
      <a href="https://www.youtube.com/watch?v=PVDguCvRwEs">
         <img src="https://img.youtube.com/vi/PVDguCvRwEs/0.jpg" style="width:30%;">
      </a>
   
 </div>

___



# :memo: **Ενότητα 2**:<br>

## Δημιουργία και ενεργοποίηση εικονικού περιβάλλοντος Python
  <div align="left">
    
- python3 -m venv /home/manos/venv/myenv/
- source /home/manos/venv/myenv/bin/activate
  
 </div>


 ## Εγκατάσταση Βιβλιοθηκών Python
  <div align="left">
    
- pip3 install python-vlc
- pip3 install serial
- pip3 install serial-tool
- pip3 install playsound
- pip3 install gtts
   
 </div>

## Εγκατάσταση Thonny
  <div align="left">

https://github.com/thonny/thonny/releases/download/v4.1.3/thonny-4.1.3-x86_64.tar.gz

cd ~/Λήψεις/thonny/
./install
Tools/options/interpreter
   
 </div>


<div>

# $\fbox{Περιγραφή λειτουργίας συστήματος}$
  

  
</div>


  
 <div>

# $\fbox{Χαρακτηριστικά πειράματος και ολοκληρωμένος τελικός κώδικας}$


  

### Διάγραμμα ροής
  

  
  
 ### Σύνδεση
   
|Sensor side|->|Arduino side|
   
   
### Τελικός κώδικας ενιαίο
  
### Κώδικας mega
  
  
</div>
  
  
  <div>

# $\fbox{Τι να προσέξω - Αστοχίες και λάθη}$

  
</div>
  

 

<div>

# $\fbox{Φωτογραφικό υλικό}$



### Εργαστήριο πληροφορικής - Προγραμματισμός και σύνδεση αισθητήρων

  
 

### Εργαστήριο πληροφορικής 
  


### Δοκιμές και παραμετροποίηση
  


### Εργαστήριο πληροφορικής - Βίντεο παρουσίαση
  


# $\fbox{ΕΥΧΑΡΙΣΤΙΕΣ}$


  
</div>
