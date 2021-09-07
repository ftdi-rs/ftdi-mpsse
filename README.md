# ftdi-mpsse

The FT2232D, FT232H, FT2232H and FT4232H devices incorporate a command processor called the
Multi-Protocol Synchronous Serial Engine (MPSSE). The purpose of MPSSE is to communicate
with devices using synchronous protocols such as SPI and I2C.

This crate implements various helper structures and functions that simplify MPSSE processor
configuration and construction of MPSSE commands.

Originally all these MPSSE helpers were a part of [libftd2xx-rs] crate. Then it has been
split into a separate crate to allow re-using it by other FTDI crates such as [ftdi-rs].



[libftd2xx-rs]: https://github.com/newAM/libftd2xx-rs
[ftdi-rs]: https://github.com/tanriol/ftdi-rs
