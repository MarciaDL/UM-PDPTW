# UM-PDPTD


Instances for the An unpaired multiple pickup and delivery problem with time windows used in the paper: 

Yu, M., Shang, J., Du, M., Hu, X. Collaborative Order Fulfillment in Omni-Channel Retailing: Unpaired Multi-Pickup and Delivery with Time Windows, submitted, 2023.


** Instance type**

Each instance type is defined by three main elements: the number of pharmacies, the number of the vehicles, and the number of orders.

An example about how to read the instance's type: the instances of 15_20_10 represent 15 pharmacies, 20 orders, and 10 vehicles.

**Instance data**

The data in each instance file is organized as follows:

    First section: fixed cost of using a vehicle , capacity of each vehicle, time deadline of orders, vehicle travel cost coefficient with distance, vehicle travel time coefficient with distance.
    
    Second section: volume of each drug.

    Three section: pharmacy ID, coordinate X, coordinate Y, drug categories stocked in pharmacy, the number of each category stocked in pharmacy.

    Four section: order ID, coordinate X, coordinate Y, drug categories required in order, the number of each category required in order.

    Five section: vehicle ID, coordinate X, coordinate Y.
