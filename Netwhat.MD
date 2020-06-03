# 1. Что такое IP-адрес?
  IP-адрес (Internet Protocol Address) – это `уникальный числовой идентификатор конкретного устройства в сети`,<br>
  построенной на основе протокола TCP/IP.<br>
  Для работы в `Интернете` требуется его `глобальная уникальность`.<br>
  Для `частной сети` достаточно, чтобы были `исключены совпадения в локальном пространстве`.<br>
  Сетевые устройства взаимодействуют друг с другом, используя IP-адреса.<br>
  На данный момент применяется два типа — v4 и v6. <br>
  Пример IP-адреса v4: 192.168.0.1. <br>
  Пример IP-адреса v6: 2a00:15f8:a000:5:1:12:1:847f.
  
# 2. Что такое маска сети?
  Для точной идентификации устройства кроме IP-адреса необходима также маска, которая задает границы сети.<br>
  Маска сети — `числовой показатель, который определяет размер сети`, построенной на базе TCP/IP. <br>
  Имеет двоичное представление, например, 11111111 11111111 11111111 00000000 (единицы всегда слева, нули — справа). <br>
  Однако, для удобства, записывается в десятичном виде как xxx.xxx.xxx.xxx. <br>
  Пример маски для стандартной домашней сети — 255.255.255.0 (сеть IPv4). Она означает, что в IP-адресах всех компьютеров<br>
  локальной сети первые 3 октета должны совпадать, а последний быть своим у каждого компьютера.<br>
  Всего в такой сети может быть 254 компьютера.

# 3. Что такое подсеть IP-адреса с маской сети?
  Подсеть — это логическое разделение сети IP.<br>
  Маска подсети — битовая маска для определения по IP-адресу адреса подсети и адреса узла этой подсети. <br>
  Благодаря маске можно узнать, какая часть IP-адреса узла сети относится к адресу сети,<br>
  а какая — к адресу самого узла в этой сети.


What is the subnet of an IP with Netmask? 
◦ What is the broadcast address of a subnet
◦ What are the different ways to represent an ip address with the Netmask
◦ What are the differences between public and private IPs
◦ What is a class of IP addresses
What is TCP
◦ What is UDP
◦ What are the network layers
◦ What is the OSI model
◦ What is a DHCP server and the DHCP protocol
◦ What is a DNS server and the DNS protocol
◦ What are the rules to make 2 devices communicate using IP addresses
◦ How does routing work with IP
◦ What is a default gateway for routing
◦ What is a port from an IP point of view and what is it used for when connecting
to another device
