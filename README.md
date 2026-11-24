# Booking form

A single page that opens inside Telegram from a bot's **New booking** button. It collects who
a booking is for, the dates and a job name, and hands them to the bot through Telegram itself
(`Telegram.WebApp.sendData`). The page talks to no server of its own and holds no data.

Opened anywhere else it does nothing: the fields are greyed out and a note says where to open it.

Hosted with GitHub Pages from the `main` branch.
