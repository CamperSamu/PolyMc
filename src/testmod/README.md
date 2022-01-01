# PolyMc Test Mod

This is a mod to test PolyMc. Run it using the `runTestmodServer` and `runTestmodClient` tasks.
It has tests for PolyMc's automatic generation and tests for PolyMc's apis. 
Things testing the automatic generation should function on their own, without PolyMc present.

# Auto-gen tests
## `test_block`
A generic full block

## `test_block_glowing`
A generic full block that emits light. It has a luminance of 9.

## `test_item`
A generic item. Prints debug info when clicking with it. It also has an epic rarity and it's name should be coloured as such.

## `test_enchantment`
An enchantment that does nothing and can be applied to *any* item. Including blocks and such. Should range from level 1-4.

# Api tests
## `test_block_wizard`
Test block for the wizard system. Its poly is set to replace it with red stained glass and 
its wizard should spawn a diamond at its center. It is also affected by gravity.