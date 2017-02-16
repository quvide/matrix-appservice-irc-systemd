Get a copy.

`curl -O https://git.io/vDyUm | sudo tee /lib/systemd/system/matrix-appservice-irc.service > /dev/null`

Then modify it to match the location of your config and registration files.

`$EDITOR /lib/systemd/system/matrix-appservice-irc-systemd.service`

Finally, enable and start it.

```
sudo systemctl enable matrix-appservice-irc
sudo systemctl start matrix-appservice-irc
```
