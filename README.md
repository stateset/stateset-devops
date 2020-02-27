# Stateset Network DevOps

Stateset is a financial network for digital commerce working capital automation.

```
git clone https://github.com/stateset/stateset-docker-compose

docker-compose up

```

This will provision a 8 node network and in addition to 1 notary node.

```
	   8 Node Network Graph | 28 Edges | 1 Notary
-------------------------------------------------------------------

	 /--------\   /--------\   /--------\                                   
	|	   | |	        | |          |                  
	|  PartyB  | |  PartyC  | |  PartyD  | 
	|          | |	   	| |          |                   
 	 \--------/   \--------/   \--------/

 /--------\	      /--------\	   /--------\
|	   |	     |	        |	  |	     |
|  PartyA  |	     |  Notary  |	  |  PartyE  | 
|	   |	     |	        |	  |	     | 
 \--------/	      \--------/           \--------/

	 /--------\   /--------\   /--------\                                   
	|	   | |	        | |          |                            
	|  PartyH  | |  PartyG  | |  PartyF  | 
	|          | |	        | |          |                             
 	 \--------/   \--------/   \--------/

--------------------------------------------------------------------


```
