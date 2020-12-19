import smtplib
server = smtplib.SMTP('smtp.gmail.com', 587)
server.starttls()
server.login('joypurhat53@gmail.com', 'computer') #email and password
server.sendmail('joypurhat53@gmail.com', #send mail
                'dev3sakib@gmail.com', #received mail
                'I ami developer alamin.')
