# Assignment 2

 1. Erstellen Sie ein neues Projekt 
 2. Löschen sie den vorhandenen ViewController  
 3. Erstellen Sie einen neuen SplitViewController. Weisen Sie dem Master- und dem Detail ViewController eigene Klassen zu (hierfür müssen 2 neue ViewContoller erstellt werden). 
	Achten Sie darauf einen TableViewController und einen  Normalen ViewController zu verwenden  
 4. Erstellen Sie eine Klasse, die einen beliebigen String in den NSUserDefaults in ein Array ablegt und dieses Array auch wieder auslesen kann. Dies ist ihr Model. 
 5. Fügen Sie Ihrem MasterViewController (Ihr TableViewController) ein UIBarButtonItem hinzu (Tipp: System – Add) 
 6. Durch click auf Add soll ein Segue in den DetailsViewController passieren 
 7. Erweitern Sie den DetailViewController um ein Textfeld und einen Button. 
 8. Beim betätigen des Buttons soll der String des Textfelds in die NSUserDefaults abgelegt werden. 
 9. Beim zurück navigieren (iPhone) oder speichern soll sich die Liste neu Laden. Das Datenmodell für ihren TableViewController ist das gespeicherte Array in den NSUserDefaults !Denken Sie daran tableview:numberOfRowsInSection: und tableview:CellForRowAtIndexPath: korrekt zu implementieren.