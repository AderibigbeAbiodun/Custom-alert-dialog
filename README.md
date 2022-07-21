# Custom-alert-dialog
Custom Javascript Alert Dialog
    
    
    // Call aleart dialog function
    alert_dialog({
        title: "Title",
        content: "Hello World!!!",
        action: true,
        actionBtn: ['NO','YES'],
        actionColor: ['#89f302','#000000'],
        actionSize: ['8px','8px'],
        onapprove: function(){
            console.log("Okay click");
        }
    });

    
    
<h3>NOTE:</h3>

<b>title</b> - Set alert dialog title leave it empty if not title is not need

<b>content</b> - Set alert dialog body, can contain both text and html elements

<b>action</b> - Set to "true" or "false" to show action buttons and vice-versa

<b>actionBtn</b> - Accpect two button in array cancel and approve action, leave empty to remove either of the buttons

<b>actionColor</b> - Set both button colors

<b>actionSize</b> - Set both button text size

<b>onapprove</b> - callback function on click approved action button


<h3>Screenshoot</h3>



<img style="width: 30%; object-fit: 100%;" src="https://user-images.githubusercontent.com/24917368/180100976-e8000dd6-4a5b-4d16-9827-90168b9abeeb.png" alt="Screenshoot"/>
