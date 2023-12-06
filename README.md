# A Simple Battery Tender Service

Monitors you laptop battery charge and tries to keep it between 30% and 85% to
help extend its life.

## Features

-   [ ] Request Full charge
-   [ ] Request Full charge with a schedule
-   [ ] Configure charge level targets
-   [ ] Polling? Frequency
-   [ ] Event listening?

## Python might not be the way to go...

This is an event listening daemon that is going to need to call some windows C
api. So maybe it should be written in something else, like zig?
