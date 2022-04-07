```mermaid
gantt
    dateFormat  MM-DD
    title       Example Gantt Chart
	
	section Office Furniture
		Research New Furniture	:done, 05-09, 3d
                Order and Purchase Furniture  :crit, 05-18, 1d
		Furniture Delivered to Office	: a1, 06-06, 2d
		Distribute Furniture	:a2, after a1, 5d
		Treat Furniture with Scotchgard	:after a2, 3d
	
	section Computer Upgrades
		Research New Computers	:done, 05-09, 3d
                Order and Purchase Computers  :crit, 05-18, 1d
		Computers Delivered to Office	: a1, 06-06, 2d
		Install Computers	:a2, after a1, 3d
		Image and Update Computers	:after a2, 5d
```
