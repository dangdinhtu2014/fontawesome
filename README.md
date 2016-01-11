# fontawesome plugin for ckeditor using in Nukeviet 4
    Font awesome 4.4.0
    Ckeditor 4.5.4
    Nukeviet 4.0.24

#SETTING
    Extract the downloaded file (fontawesome.zip)
    
    Copy the "fontawesome" folder to "assets/editors/ckeditor/plugins/" folder
    
    Open the file "assets/editors/ckeditor/config.js"
    
    See the code "config.extraPlugins" in file config and add "fontawesome" after comm at last line as 
    
    config.extraPlugins = 'video,eqneditor,switchbar,tbvdownload,googledocs,fontawesome';
    
    * In your HTML's <head> section add this code:
        <script>CKEDITOR.dtd.$removeEmpty['span'] = false;</script>
    * OR add this code to the last file themes/admin_default/js/main.js
        CKEDITOR.dtd.$removeEmpty['span'] = false; 
 
![ScreenShot](https://lh3.googleusercontent.com/JXbGoHDz1xe0Rw11mnT4vAkaSWKsJBKpfV3kGinMoADmz3k3ZDPugGhuzhTDIDR4OaXhfuS5E9Qg3yzVQJ18uo6x_XGMCQSKe9-AGA8KmCMKK0fcMQNXiEJBC5h-ur7qowWF6eU_3P0N3e6zT9ok4FvZr6pBqamvo_uPXRNxX-GdcU9kqS4LDYbEAPLNQjQHymqXWAUyRNjbJRXOMDhaujs0Oypeo-k0YOQZQwLHCbObYqUiWuitx3Wf0UEuMtRkbyj6CnyzjPIN97zARrg9veQI7e6aaVGv2faQ3cvfYi49uFH_DmzC3jDrvPLhdlxUMXqQWA4UKEH_RVLdhaJPb-UYHsiDAnY8ioFm1jLX5CtvvaTx1Z8D0BISufKfFMwpZpx0WY6Gcl7_WYre8phIWziByhXtIG5k6gegojAeqtB9WAVytl4NKatQuTQOee7A_fJe_rvp7tKGoMUyNZpi1LZHrMXSh9x3rzaN87ttFP2PBgBp5aMxEJQtIK1PgnbAUHRtN3r-b200ekyPH3fIaBDhVygsLVvlbvvpeq47fWK9bQorE_HzobJ2iYDzSwTrBrBE=w629-h670-no?raw=true)
 
