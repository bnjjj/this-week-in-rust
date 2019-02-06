Title: This Week in Rust 272
Number: 272
Date: 2019-02-05
Category: This Week in Rust

Hello and welcome to another issue of *This Week in Rust*!
[Rust](http://rust-lang.org) is a systems language pursuing the trifecta: safety, concurrency, and speed.
This is a weekly summary of its progress and community.
Want something mentioned? Tweet us at [@ThisWeekInRust](https://twitter.com/ThisWeekInRust) or [send us a pull request](https://github.com/cmr/this-week-in-rust).
Want to get involved? [We love contributions](https://github.com/rust-lang/rust/blob/master/CONTRIBUTING.md).

*This Week in Rust* is openly developed [on GitHub](https://github.com/cmr/this-week-in-rust).
If you find any errors in this week's issue, [please submit a PR](https://github.com/cmr/this-week-in-rust/pulls).

# Updates from Rust Community

## News & Blog Posts

# Crate of the Week

This week's crate is [log-derive](https://crates.io/crates/log-derive), a procedural macro to log function outputs. Thanks to [elichai2](https://users.rust-lang.org/t/crate-of-the-week/2704/482) for the suggestion!

[Submit your suggestions and votes for next week][submit_crate]!

[submit_crate]: https://users.rust-lang.org/t/crate-of-the-week/2704

# Call for Participation

Always wanted to contribute to open-source projects but didn't know where to start?
Every week we highlight some tasks from the Rust community for you to pick and get started!

Some of these tasks may also have mentors available, visit the task page for more information.

* [Request for implementation - Crates that don't exist, but should](https://github.com/dtolnay/request-for-implementation).

If you are a Rust project owner and are looking for contributors, please submit tasks [here][guidelines].

[guidelines]: https://users.rust-lang.org/t/twir-call-for-participation/4821

# Updates from Rust Core

157 pull requests were [merged in the last week][merged]

[merged]: https://github.com/search?q=is%3Apr+org%3Arust-lang+is%3Amerged+merged%3A2019-01-28..2019-02-04

* [HirIdification: add key HirId methods](https://github.com/rust-lang/rust/pull/58090)
* [don't panic when accessing enum variant ctor using `Self` in match](https://github.com/rust-lang/rust/pull/58007)
* [use LLVM intrinsics for saturating add/sub](https://github.com/rust-lang/rust/pull/58003)
* [add MOVBE x86 CPU feature](https://github.com/rust-lang/rust/pull/57999)
* [NVPTX target specification](https://github.com/rust-lang/rust/pull/57937)
* [fix bug in integer range matching](https://github.com/rust-lang/rust/pull/57978)
* [unused variable suggestions apply on all patterns](https://github.com/rust-lang/rust/pull/57899)
* [add information to higher-ranked lifetimes conflicts error messages](https://github.com/rust-lang/rust/pull/57901)
* [rustc: use multiple threads by default](https://github.com/rust-lang/rust/pull/57948)
* [misc performance tweaks](https://github.com/rust-lang/rust/pull/57916)
* [simplify `ConstValue::ScalarPair`](https://github.com/rust-lang/rust/pull/57442)
* [mark `str::trim*` functions as `#[must_use]`](https://github.com/rust-lang/rust/pull/57106)
* [override `VecDeque`'s `Iter::try_fold`](https://github.com/rust-lang/rust/pull/57974)
* [introduce `into_raw_non_null` on `Rc` and `Arc`](https://github.com/rust-lang/rust/pull/57934)
* [implement `Weak::`{`strong_count`, `weak_count`}](https://github.com/rust-lang/rust/pull/56696)
* [rename `iter::unfold` to `iter::from_fn` and remove explicit state](https://github.com/rust-lang/rust/pull/58062)
* [stabilize `std::error::Error::type_id`](https://github.com/rust-lang/rust/pull/58048)
* [stabilize `split_ascii_whitespace`](https://github.com/rust-lang/rust/pull/58047)
* [cargo: fix overlapping progress with stdout](https://github.com/rust-lang/cargo/pull/6618)
* [cargo: improve progress bar flickering](https://github.com/rust-lang/cargo/pull/6615)

## Approved RFCs

Changes to Rust follow the Rust [RFC (request for comments)
process](https://github.com/rust-lang/rfcs#rust-rfcs). These
are the RFCs that were approved for implementation this week:

*No RFCs were approved this week.*

## Final Comment Period

Every week [the team](https://www.rust-lang.org/team.html) announces the
'final comment period' for RFCs and key PRs which are reaching a
decision. Express your opinions now.

### [RFCs](https://github.com/rust-lang/rfcs/labels/final-comment-period)

* [disposition: merge] [stabilize `std::task` and `std::future::Future`](https://github.com/rust-lang/rfcs/pull/2592).
* [disposition: postpone] [RFC for anonymous variant types, a minimal ad-hoc sum type](https://github.com/rust-lang/rfcs/pull/2587).

### [Tracking Issues & PRs](https://github.com/rust-lang/rust/labels/final-comment-period)

* [disposition: merge] [Deprecate the unstable Vec::resize_default](https://github.com/rust-lang/rust/pull/57656).
* [disposition: merge] [Error on duplicate matcher bindings](https://github.com/rust-lang/rust/pull/57617).
* [disposition: merge] [syntax: Remove warning for unnecessary path disambiguators](https://github.com/rust-lang/rust/pull/57565).
* [disposition: merge] [Automatically open an issue when a tool breaks](https://github.com/rust-lang/rust/pull/56951).
* [disposition: merge] [[WIP] Unsized rvalues: implement boxed closure impls.](https://github.com/rust-lang/rust/pull/55431).
* [disposition: merge] [Tracking issue for Range*::contains](https://github.com/rust-lang/rust/issues/32311).

## New RFCs

* [RFC for a formalized notion on where to enforce reference propertes in MIR](https://github.com/rust-lang/rfcs/pull/2631).
* [proc-macro-attribute-recursion](https://github.com/rust-lang/rfcs/pull/2628).

# Upcoming Events

### Online

* [Feb  6. Rust Community Team Meeting on Discord](https://discordapp.com/channels/442252698964721669/443773747350994945).
* [Feb 13. Rust Events Team Meeting on Telegram](https://t.me/joinchat/EkKINhHCgZ9llzvPidOssA).

### Africa

* [Feb  6. Sandown, ZA - Johannesburg meetup](https://www.meetup.com/Johannesburg-Rust-Meetup/events/qbhxmqyzdbjb/).

### Asia Pacific

* [Feb 13. Melbourne, AU - Melbourne hack night](https://www.meetup.com/Rust-Melbourne/events/257974991/).

### Europe

* [Jan 31. Helsinki, FI - Helsinki Rust meetup](https://www.meetup.com/Finland-Rust-Meetup/events/257863678/).
* [Jan 31. Copenhagen, DK - [cph.rs] Copenhagen Rust Hack Night #12 ](http://cph.rs/).
* [Jan 31. Oslo, NO - Rust Oslo - Hack & Learn](https://www.meetup.com/Rust-Oslo/events/258150829/).
* [Jan 31. Torino, IT - Turin Rust meetup](https://www.meetup.com/Mozilla-Torino/events/sbtclqyzcbgc/).
* [Feb  3. Bruxelles, BG - Rust Dev Room @ FOSDEM](https://fosdem.org/2019/).
* [Feb  6. Berlin, DE - Berlin Rust Hack and Learn](https://www.meetup.com/opentechschool-berlin/events/rjgkhqyzdbjb/).

### North America

* [Jan 31. Phoenix, US - Phoenix Rust: Games](https://www.meetup.com/Desert-Rustaceans/events/257976456).
* [Feb  6. Atlanta, US - Rust Atlanta Meetup](https://www.meetup.com/Rust-ATL/events/cbcmbqyzdbjb/).
* [Feb  6. Vancouver, CN - Vancouver Rust meetup](https://www.meetup.com/Vancouver-Rust/events/hkllqqyzdbjb/).
* [Feb  7. Indianapolis, US - Indy.rs](https://www.meetup.com/indyrs/events/246726699/).
* [Feb 12. Seattle, US - Seattle Rust Meetup](https://www.meetup.com/Seattle-Rust-Meetup/events/nzfspqyzdbpb/).
* [Feb 12. Utah, US - Utah Rust monthly meetup](https://www.meetup.com/utahrust/events/257819656/).

If you are running a Rust event please add it to the [calendar] to get
it mentioned here. Please remember to add a link to the event too.
Email the [Rust Community Team][community] for access.

[calendar]: https://www.google.com/calendar/embed?src=apd9vmbc22egenmtu5l6c5jbfc%40group.calendar.google.com
[community]: mailto:community-team@rust-lang.org

# Rust Jobs

* [Senior Embedded Systems Engineer at SpanIO, San Francisco, US](https://www.span.io/careers/embedded-linux).
* [Senior Software Engineer at Prevoty, Los Angeles, US](https://www.prevoty.com/about/careers?gh_jid=4032159002).

*Tweet us at [@ThisWeekInRust](https://twitter.com/ThisWeekInRust) to get your job offers listed here!*

# Quote of the Week

This time, we have two quotes for the price of one:

> The borrow checker breaks you down so that it can build you back up, stronger and more resilient than you once were. It also had me do all sorts of weird things like catch flies with chopsticks and scrub counters to a polish.

– /u/bkv on /r/rust

> I always think of borrowck as an angel sitting on your shoulder, advising you not to sin against the rules of ownership and borrowing, so your design will be obvious and your code simple and fast.

– llogiq on [/r/rust](https://www.reddit.com/r/rust/comments/ampvvt/as_a_new_selftaught_student_to_programming_this/efo074d)

– Brook Heisler [on discord](https://discordapp.com/channels/442252698964721669/448238009733742612/536406836178583562) (login needed, sorry!)

Thanks to [Christopher Durham](https://users.rust-lang.org/t/twir-quote-of-the-week/328/617) for the suggestion!

[Please submit your quotes for next week](http://users.rust-lang.org/t/twir-quote-of-the-week/328)!

*This Week in Rust is edited by: [nasa42](https://github.com/nasa42), [llogiq](https://github.com/llogiq), and [Flavsditz](https://github.com/Flavsditz).*

<small>[Discuss on r/rust]().</small>