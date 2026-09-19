#Ağ Temelleri

##IP-PORT-DNS-TCP-UDP Nedir

IP adresi,ağdaki cihazın dijital kimlik numarasıdır
	     örn.192.168.1.10
		 
PORT,cihazdaki hangi uygulama/hizmetle iletişim kurulacağı belirtir
	     örn: 80-HTTP
		      443-HTTPS
		IP-hangi cihazdak
		PORT-o cihadaki hangi hizmetle
		
DNS, web sitesi isimlerini IP adresine çevirir
         örn:google.com-142.100....  (telefon rehberi gibi)
		 
TCP,verinin karşı tarafa güvenilir ve sıralı şekilde ulaşmasını sağlar
	    veri kaybolursa tekrar gönderebilir
		
UDP,veriyi daha hızlı gönderir ama ulaşacağının garantisini vermez
	
	
##Paket Yapısı Nasıl Çalışır

   Gönderdiğimiz veri ağda tek parça halinde gitmek yerine küçük parçalara(paket)ayrılabilir
        
		veri-paketlere ayrılır-ağ üzerinden gönderilir-karşı tarafta birleştirilir
		
		
##Ping ne işe yarar
  
   Bir cihazın/sunucunun ulaşılabilir olup olmadığını kontrol eder
        örn: ping google.com 
		
		
## Traceroute Ne İşe Yarar

   Verinin hedefine giderken hangi ağ cihazlarından geçtiğini gösterir
   
   
## Nslookup Ne İşe Yarar

   Bir alan adının hangi IP adresine karşılık geldigini ögrenmek için kullanılır
   
