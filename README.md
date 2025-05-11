# kenyan-agriculture-db
ENTITY RELATIONSHIP DIAGRAM (Simplified)

Counties ────┐
            │
Farmers ────┼──── Farms ───┬──── Farm_Crops ─── Crops
            │              │
Extension_Officers ────────┴──── Farmer_Training
            │
Farms ──────┴──── Farm_Livestock ─── Livestock
│
└──── Sales ─── Buyers
