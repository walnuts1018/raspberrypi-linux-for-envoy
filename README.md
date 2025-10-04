# raspberrypi-linux-for-envoy

```bash
curl -fsSL https://walnuts1018.github.io/raspberrypi-linux-for-envoy/public.key | sudo gpg --dearmor -o /etc/apt/keyrings/raspberrypi-linux-for-envoy-apt-keyring.gpg
echo "deb [signed-by=/etc/apt/keyrings/raspberrypi-linux-for-envoy-apt-keyring.gpg] https://walnuts1018.github.io/raspberrypi-linux-for-envoy stable InRelease" | sudo tee /etc/apt/sources.list.d/raspberrypi-linux-for-envoy.list
```
