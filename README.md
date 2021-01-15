# send_files_on_mail
Send any files via mail.

<hr>
You need input data:

15    addr_from = ""                 
16    password  = ""    

29    server = smtplib.SMTP('', 587) 

75    addr_to   = "" 

77    #files =[]               # List of files, if there are no attachments, then files=[]
78     files = [r"C:\Users\...",
79               r"C:\Users\..."]
80               #"dir1_path"]    # If you need to send all files from a given folder, you need to specify it
81 
82 send_email(addr_to, "", "", files)
<hr>
