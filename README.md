# UM-PDPTW


Instances for the unpaired multi-pickup and delivery problem with time windows used in the paper: 

Yu, M., Du, M., Shang, J., Hu, X. Collaborative Order Fulfillment in Omni-Channel Retailing: Unpaired Multi-Pickup and Delivery with Time Windows, submitted, 2025.


** Instance type**

Each instance type is defined by three main elements: the number of pharmacies, the number of orders, and the number of the deliverymen.

An example about how to read the instance's type: the instances of 15_20_10 represent 15 pharmacies, 20 orders, and 10 deliverymen.

**Instance data**

The data in each instance file is organized as follows:

    First section: fixed cost of using a deliveryman, capacity of each deliveryman, time deadline of orders, travel cost coefficient with distance, travel time coefficient with distance.
    
    Second section: volume of each drug.

    Three section: pharmacy ID, coordinate X, coordinate Y, drug categories stocked in pharmacy, the number of each category stocked in pharmacy.

    Four section: order ID, coordinate X, coordinate Y, drug categories required in order, the number of each category required in order.

    Five section: deliveryman ID, coordinate X, coordinate Y.
