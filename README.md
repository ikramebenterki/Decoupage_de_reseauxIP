# Decoupage_de_reseauxIP
## 1\Decoupage symetrique :
* pole informatique :
adresse réseau : 172.16.1.0/26
adresse de diffusion : 172.16.1.63/26
plage d'adresses disponibles : 172.16.1.1 à 172.16.1.62

* pole développement :
adresse résea : 172.16.1.64/26
adresse de diffusion : 172.16.1.127/26
plage d'adresses disponibles : 172.16.1.65 à 172.16.1.126

* pole Administratif :
adresse réseau : 172.16.1.128/26
adresse de diffusion : 172.16.1.191/26
plage d'adresses disponibles : 172.16.1.129 à 172.16.1.190

* pole Technicien :
adresse réseau : 172.16.1.192/26
adresse de diffusion : 172.16.1.255/26
plage d'adresses disponibles : 172.16.1.193 à 172.16.1.254

## 2\Decoupage asymetrique :
* pole informatique (50équipements) :
  adresse réseau : 172.16.1.0/26
  adresse de diffusion : 172.16.1.63/26
  plage d'adresses disponibles : 172.16.1.1 à 172.16.1.62
Le masque de sous-réseau doit permettre d'adresser au moins 50 équipements, soit 2^x >= 50.
2^6 = 64 (le masque /26 permet d'adresser 64 adresses IP, dont 62 utilisables).


* pole administratif (20 équipements ) :
  adresse réseau : 172.16.1.64/27
  adresse de diffusion : 172.16.1.95/27
  plage d'adresses disponibles : 172.16.1.65 à 172.16.1.94
2^5 = 32

* pole technicien (15 équipements )
  adresse resau : 172.16.1.96/28
  adressse de diffusion : 172.16.1.111
  plage d'adresses disponible : 172.16.1.97 a 172.16.110
2^4 = 16

* pole developpement (12 équipements ) :
  aresse reseau : 172.16.1.112/28
  adresse de diffusion : 172.16.127
  plage d'adresses disponibles : 172.16.1.113 à 172.16.1.126
  2^4 = 16

  

  

