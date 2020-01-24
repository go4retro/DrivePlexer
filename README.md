# DrivePlexer - A Floppy Drive Multiplexer system
The PCB converts the DRIVE1,2,3 lines of the standard floppy controller from discrete signals to a binary floppy drive "address"

## Assumptions
* MOTOR_ON can be used to enable the drives, so all 8 selects can be used.  If this is not true, the MOTOR_EN signal going to the decoder can be strapped to ground, which means DRIVE8 must be not connected (all high lines will be treated as no drive selected)

## License
Copyright (C) 2018  RETRO Innovations

These files are free designs; you can redistribute them and/or modify
them under the terms of the Creative Commons Attribution-ShareAlike 
4.0 International License.

You should have received a copy of the license along with this
work. If not, see <http://creativecommons.org/licenses/by-sa/4.0/>.

These files are distributed in the hope that they will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
license for more details.


