# AIT Native apt repository

Exact rc route: `testing`; signing fingerprint:
`F3A43E51AB73AD580ADE43634D84B16BA88BC9BD`.

```sh
curl -fsSL https://raw.githubusercontent.com/weita2026/apt-ait-native/main/ait-native-archive-keyring.gpg \
  | sudo tee /usr/share/keyrings/ait-native-archive-keyring.gpg >/dev/null
echo "deb [signed-by=/usr/share/keyrings/ait-native-archive-keyring.gpg] https://raw.githubusercontent.com/weita2026/apt-ait-native/main testing main" \
  | sudo tee /etc/apt/sources.list.d/ait-native.list
sudo apt update
apt-cache search --names-only "^ait-native$"
apt-cache search --names-only "^ait-runner$"
sudo apt install ait-native
```
