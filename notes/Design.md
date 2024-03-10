# Design

High concept: magical computer engineering

A spell consists of spell pieces connected with data flow tubes, some of which need to be powered by mana flow tubes (magical energy cables)

Spell pieces, every tick, consume, transform, or produce datum items; each datum represents either 16 bits of binary data or something else (e.g. entity handles)

Data emitted by a spell piece is sent (broadcast) to every other piece connected via data flow tube

Datum items are unstackable and uncraftable, and can be conjured and destroyed directly with special spell pieces

Principle: spell pieces and datum items are opaque without the right discoveries and equipment

Principle: progression is locked behind solving mathematical puzzles (probably works up to requiring a full turing complete computer)
