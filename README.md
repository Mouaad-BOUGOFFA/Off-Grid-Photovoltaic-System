# Off-Grid-Photovoltaic-System
This dataset contains 13 days of real-world measurements from a 2kWp off-grid photovoltaic system. 
The system is installed at the GEII Department of Aix-Marseille University, located in Salon-de-Provence, including both normal and faulty operation.

The PV plant consists of three independent strings equipped with 3 different technologies of 16 modules, forming a three-string group:   
	- Three modules of Polycrystalline (SW 260 POLY) 
	- Three modules of Monocrystalline (PM060M02)  
	- Eight modules of Amorphous Silicon (GS-50). 
	
Each monitored by dedicated MPPT regulators, environmental sensors, and high-precision electrical instrumentation. 		
The dataset includes DC/AC electrical signals, battery behavior, irradiance and temperature, recorded at one-minute intervals, 
along with labeled fault scenarios such as open-circuit faults, partial disconnections, shadowing, and sensor faults. 
This collection provides a valuable resource for machine learning, deep learning, and fault diagnosis research in photovoltaic systems.


Note:This dataset is raw and has not undergone any preprocessing; tasks such as data augmentation and concatenation still need to be applied.

__________________________________________________

F.x.y


F= Fault

x= 0: No Fault
   1: Open Circuit Fault
   2: Partial Open Circuit Fault
   3: Shadowing
   4: Sonsor Fault 


y= 1: Chaine 1
   2: Chaine 2
   3: Chaine 3
