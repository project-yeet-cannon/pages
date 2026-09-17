# Binary Clock

Tell time in binary, lit up like old Edison bulbs.

Six columns of bulbs show the current time as HH:MM:SS in binary-coded
decimal — one column per digit, each a stack of four bulbs worth 8, 4, 2,
and 1. A lit bulb is a 1; read a column top-to-bottom and add up the lit
values to get that digit. A plain digital readout underneath confirms
what you're looking at.

Pure web app, no build step, no server, no dependencies. Just open
`index.html` in a browser.
