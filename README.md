
![MeshtasticRouterNode](doc/MeshtasticNode-pcb.jpg)

## What is this thing?

This is a Heltec HT-CT62 based Meshtastic Router which can be integrated into a IP68 protected case.

Combined with a solar panel this device can be placed in remote areas to cover a wide range.

For power managementa TI BQ24074 is being used which offers pseudo-MPPT and load switching (= battery being deactivated if the sun offers us enough energy to power the device alone).

### Box

![MeshtasticRouterNode](doc/MeshtasticNode-Box.jpg)


### Cabeling

![MeshtasticRouterNode](doc/MeshtasticNode-Cabeling.jpg)

### Flashing

![MeshtasticRouterNode](doc/MeshtasticNode-Setup.jpg)


## Lessons learned

Never ever use hot glue even when if the promise that it's UV resistant. It will fail and then the environment will kill all of your electronics.

Professional glue for construction work and water pools/boat seem to survive every kind of weather as long you keep it within its specs.

Using venting plugs with Gore protection.

## Future Changes

The solar charging IC will be replaced with    the new TI BQ25308 which will enable us to utilize solar panels from 4.5-17V without burning a single mA into heat.
