# 9733 Blower Fan Duct

![9733 Duct Assembled](images/Assembled.png)

## BOM

| Part                  | Quantity | Notes                                              |
| --------------------- | -------- | -------------------------------------------------- |
| M3x5x4 Heatset Insert | 5        |                                                    |
| 9733 Blower Fan       | 1        | 5V or 24V depending on your setup                  |
| M3x16 BHCS            | 3        |                                                    |
| M3x35 BHCS            | 2        |                                                    |
| M3 Washer             | 2        | optional, only to make better contact with the fan |
| Superglue             |          | only for the 2-piece shroud                        |
| VHB-Tape              |          | for extra mounting security if needed              |

SHCS instead of BHCS will also work.

The Fan I used was this [GDSTIME 9733 24V Dual Ball Bearing Blower Fan](https://www.aliexpress.com/item/32622626365.html)

## Printed Parts

You'll need to print 1 [9733_Clamp.stl](STL/9733_Clamp.stl) and either the [9733_Unibody_Shroud.stl](STL/9733_Unibody_Shroud.stl) if you have a large enough printer, or [9733_2Part_Shroud_Bottom.stl](STL/9733_2Part_Shroud_Bottom.stl) and [9733_2Part_Shroud_Top.stl](STL/9733_2Part_Shroud_Top.stl) if you print it on a V0-sized printer.

## Assembly Instructions

#### Remove the built-in Supports from the shroud, use some Flush-Cutters for the supports inside the ducts:

![Duct Supports](images/Support_Duct.png)

- Unibody Version
  ![unibody](images/Support_Unibody.png)
- 2 Piece Version:
  ![2 Piece Bottom](images/Support_2Part.png)

#### 2 Piece Version only: Apply Glue to the contact surfaces of the bottom part duct and glue the two pieces together.

![Bottom Glue Faces](images/Glue_2Part.png)

#### The remaining steps are the same as for the [5015 duct](/ducts/5015/README.md#insert-2x-heatsets-for-the-fan-from-the-front-caution-the-printed-part-is-4mm-thick-so-the-heatset-is-exactly-the-same-length-as-the-part-dont-push-the-heatset-through-by-accident), except that you use M3x35 BHCS to secure the fan.