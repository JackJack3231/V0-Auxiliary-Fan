# 7530 Blower Fan Duct

![7530 Duct Assembled](images/Assembled.png)

## BOM

| Part                  | Quantity | Notes                                              |
| --------------------- | -------- | -------------------------------------------------- |
| M3x5x4 Heatset Insert | 5        |                                                    |
| 7530 Blower Fan       | 1        | 5V or 24V depending on your setup                  |
| M3x16 BHCS            | 3        |                                                    |
| M3x35 BHCS            | 2        |                                                    |
| M3 Washer             | 2        | optional, only to make better contact with the fan |
| Superglue             |          | only for the 2-piece shroud                        |
| VHB-Tape              |          | for extra mounting security if needed              |

SHCS instead of BHCS will also work.

The Fan I used was this [GDSTIME 7530 24V Dual Ball Bearing Blower Fan](https://www.aliexpress.com/item/1005002663971820.html)

## Printed Parts

You'll need to print 1x[7530_Clamp.stl](STL/7530_Clamp.stl), 2x[7530_spacer_1.6mm.stl](STL/7530_spacer_1.6mm.stl) and either the [7530_Unibody_Shroud.stl](STL/7530_Unibody_Shroud.stl) if you have a large enough printer, or [7530_2Part_Shroud_Bottom.stl](STL/7530_2Part_Shroud_Bottom.stl) and [7530_2Part_Shroud_Top.stl](STL/7530_2Part_Shroud_Top.stl) if you print it on a V0-sized printer.

## Assembly Instructions

#### Remove the built-in Supports from the shroud, use some Flush-Cutters for the supports inside the ducts:

![Universal](images/Support_Duct.png)

- Unibody Version
  ![unibody](images/Support_Unibody.png)
- 2 Piece Version:
  ![2 Piece Bottom](images/Support_2Part.png)

#### 2 Piece Version only: Apply Glue to the contact surfaces of the bottom part duct and glue the two pieces together.

![Bottom Glue Faces](images/Glue_2Part.png)

#### Insert 2x Heatsets for the fan from the front. **CAUTION** the printed part is 4mm thick, so the Heatset is exactly the same length as the part. Don't push the Heatset through by accident.

![Heatset Locations for Fan](images/7530_Heatsets_Front.png)

#### Insert 3x Heatsets for the clamping-block into the shroud from the back.

![Heatset Location for Clamp](images/7530_Heatsets_Rear.png)

#### Put the Fan into the shroud and secure with 2x M3x35 BHCS and one of the printed spacers each.

![Fan Installation](images/7530_Fan_Insert.png)
![Fan Screws](images/7530_Fan_Screws.png)

#### Insert the shroud into the bottom extrusion of your printer and clamp it down with the clamp block and 3x M3x16BHCS. If you want add some VHB-Tape to the bottom of the shroud. For reference see the [5015 duct](/ducts/5015/README.md#slide-the-shroud-into-the-frame-on-whichever-side-you-prefer-align-it-with-the-center-of-the-print-bed) Assembly instructions
