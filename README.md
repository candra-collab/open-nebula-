# open-nebula-
1. Setting open nebula in your server : 
opennebula :


               wget -q -O- https://downloads.opennebula.io/repo/repo.key | apt-key add -  
               echo "deb https://downloads.opennebula.io/repo/5.12/Ubuntu/20.04 stable opennebula" > /etc/apt/sources.list.d/opennebula.list 
               apt update   
               apt install opennebula opennebula-sunstone opennebula-gate opennebula-flow
               oneuser show
               systemctl enable --now opennebula opennebula-sunstone
               oneuser show
               su - oneadmin
               ls -al
               logout
               passwd oneadmin
               nano /etc/hosts
              	  10.10.10.140 opennebula
               NOTE : if your ip private you want to access public : you use IP PORT FORWARDING 
               su - oneadmin
               ssh-keygen -t -rsa
               ping opennebula
               ssh-copy-id opennebula
               Lupa pass :
               su - oneadmin
               cat .one/one_auth
        
2. Access open nebula dan use port : 
      using your IP : http:10.10.10.10:9869
