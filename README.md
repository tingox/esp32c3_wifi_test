# Wi-Fi examples

I used esp-generate to generate the boilerplate for this

```
esp-generate -c esp32c3 -o alloc -o wifi esp32c3_wifi_test
```

the examples are taken from the esp-wifi crate in [esp-hal](https://github.com/esp-rs/esp-hal/)

to build and run the example, you can use something like

```
env SSID=mySSID PASSWORD=myPASSWORD cargo run --example wifi_dhcp
```

to avoid storing credentials in a file.