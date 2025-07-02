# OSPF ভিত্তিক MPLS নেটওয়ার্ক কনফিগারেশন

R1(config)# router ospf 1
R1(config-router)# network 1.1.1.1 0.0.0.0 area 0
R1(config)# mpls ip

R2(config)# router ospf 1
R2(config-router)# network 2.2.2.2 0.0.0.0 area 0
R2(config)# mpls ip
