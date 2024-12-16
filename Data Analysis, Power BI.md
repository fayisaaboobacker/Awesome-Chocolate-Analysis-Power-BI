From the given data we want to calculate different KPI's.

Toatal Sales = SUM(shipments[Sales])
Total Boxes = SUM(shipments[Boxes])
Total Cost = SUM(shipments[Cost])
Total Shipment = COUNTROWS(shipments)
Total Profit = [Toatal Sales] - [Total Cost]
Profit % = DIVIDE([Total Profit],[Toatal Sales])
