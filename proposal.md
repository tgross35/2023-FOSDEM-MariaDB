# FOSDEM 2023 Rust Devroom Application: MariaDB

## Abstract

This presentation will discuss Rust usage as it relates to the
[MariadDB Server](https://mariadb.org/about/) project. The relationship started
with the [`udf`] crate which makes it easy to write dynamically loaded callable
SQL functions (user-defined functions or UDFs) in Rust, where C and C++ have
been the precedent. There is now a work in progress to provide a safe Rust
interface for the plugin API which will enable writing encryption and
authentication protocols, information schemas, and even storage engines in Rust;
areas that can easily lead to exploits if not written correctly. These plugins
can be compiled in or dynamically loaded.  

MariaDB is one of the most popular open-source databases, so these projects will
bring some exciting possibilities in that area. Our presentation will discuss
the state of these ongoing projects including project design, basic usage with
examples, work that lies ahead, and information on how to contribute. We will
also talk about evaluation of the future of the Rust-MariaDB relationship.

[`udf`]: https://docs.rs/udf/latest/udf/

## Session type

We would prefer to do a live presentation remotely.


## Session length

We would prefer a 20 minute time slot.


## Expected prior knowledge / intended audience

This presentation will be rather general, and expected knowledge is minimal. We
aim to cater to those who have a basic understanding of Rust at least a general
familiarity of SQL, but neither is required.


## Speaker bios

### Trevor Gross

Trevor is an electrical engineer who works at the boundary of embedded software
and hardware. He has had the opportunity to work extensively with web backend
development, which led to an involvement with open source. Recently Rust has
become his language of choice, and he has been working to leverage its benefits
for the improvement of existing software developments.

### Daniel Black

After a reasonable amount of time doing development and IT security work, Daniel
landed a DBA Consultant job and loved it. After writing a few too many bug fixes
without a client to bill them to, he joined IBM to make MariaDB and MySQL scale
on IBM POWER. The love for the community brought him to MariaDB Foundation where
he embraces the innovation of contributors and users to make MariaDB better for
everyone.


## Links to material

* [UDF wrapper library source](https://github.com/pluots/sql-udf)
* [UDF wrapper library docs](https://docs.rs/udf/latest/udf/)
* [WIP branch for MariaDB+Rust plugins API](https://github.com/pluots/mariadb-server/tree/rust)


## Links to previous talks by the speaker

Daniel has done [a number of talks](https://www.youtube.com/results?search_query=daniel+black+mariadb)
relating to MariaDB. Trevor has not done a talk before.
