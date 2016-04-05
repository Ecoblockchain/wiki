## ttnctl applications

Show applications

### Synopsis


ttnctl applications retrieves the applications of the logged on user.

```
ttnctl applications
```

### Options inherited from parent commands

```
      --app-eui string              The app EUI to use (default "0102030405060708")
      --config string               config file (default is $HOME/.ttnctl.yaml)
      --mqtt-broker string          The address of the MQTT broker (default "staging.thethingsnetwork.org:1883")
      --ttn-account-server string   The address of the OAuth 2.0 server (default "https://account.thethingsnetwork.org")
      --ttn-handler string          The net address of the TTN Handler (default "staging.thethingsnetwork.org:1782")
      --ttn-router string           The net address of the TTN Router (default "staging.thethingsnetwork.org:1700")
```

### SEE ALSO
* [ttnctl](ttnctl)	 - Control The Things Network from the command line
* [ttnctl applications authorize](ttnctl_applications_authorize)	 - Authorize a user for the application
* [ttnctl applications create](ttnctl_applications_create)	 - Create a new application
* [ttnctl applications delete](ttnctl_applications_delete)	 - Delete an application

###### Auto generated by spf13/cobra on 5-Apr-2016