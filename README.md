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
 

