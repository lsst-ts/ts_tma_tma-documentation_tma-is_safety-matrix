# TMA IS Safety Matrix

This repo contains the safety matrix for the TMA IS, named as [TMA IS TABLE.csv](TMA%20IS%20TABLE.csv)

Actuation description:

| ACRONYMS | DEFINITION                 | DESCRIPTION                                                                                                                       |
| -------- | -------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| N        | Not Store                  | If the cause is active, the effect is tripped                                                                                     |
| S        | Store                      | If the cause is active, the effect is tripped and stored. If the effect is no longer tripped, the operator must manually clear it |
| V        | Overridable                | The cause is active, the effect is tripped. It can bypass the tripping of the effect                                              |
| R        | Resettable and Overridable | Combination of the S and V                                                                                                        |

The numbers with some of the letters are:

| NUMBERS | DESCRIPTION                                                                       |
| ------- | --------------------------------------------------------------------------------- |
| (1)     | Override with cabinet switch for main axis                                        |
| (2)     | Fault conditioned with low pressure and brake active with delayed activation time |
| (3)     | Override with switch in elevation ring                                            |
| (4)     | If AZ brake actuated only not stored operation (N or V)                           |
| (5)     | If EL and AZ  brake actuated only not stored operation (N or V)                   |

List of abbreviation:

| ACRONYMS | DEFINITION                 |
| -------- | -------------------------- |
| CW       | Clockwise                  |
| CCW      | Counterclockwise           |
| ETPB     | Emergency Trip Push Button |
| GIS      | Global Interlock System    |
| OSS      | Oil Supply System          |
| STO      | Safe Torque Off            |
