# ftdi-mpsse

The FT2232D, FT232H, FT2232H and FT4232H devices incorporate a command processor called the
Multi-Protocol Synchronous Serial Engine (MPSSE). The purpose of MPSSE is to communicate
with devices using synchronous protocols such as SPI and I2C.

This crate implements various helper structures and functions that simplify MPSSE processor
configuration and construction of MPSSE commands.

Originally all these MPSSE helpers were a part of the [libftd2xx] crate. Then it has been
split into a separate crate to allow reuse it by other FTDI crates such as [ftdi-rs].


[libftd2xx]: https://github.com/ftdi-rs/libftd2xx
[ftdi-rs]: https://github.com/tanriol/ftdi-rs
