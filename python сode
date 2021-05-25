import socket

ip = "" 
port_list = []  

for port in port_list:
    s = socket.socket(socket.AF_INET, socket.SOCK_STREAM)
    result = s.connect_ex((ip, port))

    if result == 0:
        print('Port ', port, 'open')
    else:
        print('Port ', port, 'closed')
