# send_files_on_mail
Send any files via mail.


You need input data:
<hr>
15    addr_from = ""   
<hr>
16    password  = ""
<hr>

29    server = smtplib.SMTP('', 587) 
<hr>
75    addr_to   = "" 
<hr>
77    #files =[]               # List of files, if there are no attachments, then files=[]
<hr>
78     files = [r"C:\Users\...",
<hr>
79               r"C:\Users\..."]
<hr>
80               #"dir1_path"]    # If you need to send all files from a given folder, you need to specify it
<hr>
81 
<hr>
82 send_email(addr_to, "", "", files)
