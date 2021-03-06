## ttn router

The Things Network router

### Synopsis


ttn router starts the Router component of The Things Network.

The Router accepts connections from gateways and forwards uplink packets to one
or more brokers. The router is also responsible for monitoring gateways,
collecting statistics from gateways and for enforcing TTN's fair use policy when
the gateway's duty cycle is (almost) full.

```
ttn router
```

### Options

```
      --brokers string            Comma-separated list of brokers (default "localhost:1881")
      --db-brokers string         Database connection of known brokers (default "boltdb:/tmp/ttn_router_brokers.db")
      --db-duty string            Database connection of managed dutycycles (default "boltdb:/tmp/ttn_router_duty.db")
      --db-gateways string        Database connection of managed gateways (default "boltdb:/tmp/ttn_router_gateways.db")
      --downlink-address string   The IP address to listen for downlink communication (default "0.0.0.0")
      --downlink-port int         The port for downlink communication (default 1780)
      --status-address string     The IP address to listen for serving status information (default "0.0.0.0")
      --status-port int           The port of the status server, use 0 to disable (default 10700)
      --uplink-address string     The IP address to listen for uplink communication from gateways (default "0.0.0.0")
      --uplink-port int           The UDP port for uplink communication from gateways (default 1700)
```

### Options inherited from parent commands

```
      --config string   config file (default "$HOME/.ttn.yaml")
```

### SEE ALSO
* [ttn](ttn)	 - The Things Network's backend servers

###### Auto generated by spf13/cobra on 2-May-2016
