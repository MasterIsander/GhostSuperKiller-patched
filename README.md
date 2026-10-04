Changes:
It doesn't try to load nonexistent library now
It doesn't delete your saves package now
Previously, a harmony item replaced other items in the inventory with itself via HotSpot Klass replacement; this inevitably led to a ClassCastException. Now, instead, it replaces the items with a normal minecraft procedure.
Previously, it deleted the registration of minecraft items; this inevitably led to the crash of Minecraft Forge. Now it's gone.
