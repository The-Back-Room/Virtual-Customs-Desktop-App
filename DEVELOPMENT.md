## Development
This section is for developers to manually build and test the app. For the current release this is also how to obtain the app on macos and linux. Android support is currently not available.

#### Prerequisites
1. Install tauri-cli version 1.6.6 (later versions are currently don't work with the web2app plugin used to build the app):
```sh
cargo install tauri-cli --version 1.6.6
```
2. Install web2app:
```sh
cargo install web2app
```
#### Instructions
1. Clone the repo:
```sh
git clone https://gitlab.com/the-back-room/tauri-apps/virtual-customs-desktop-app.git
```
2. CD into the cloned repo:
```sh
cd virtual-customs-desktop-app
```
3. Test the app:
```sh
cargo tauri dev
```
4. Build the app:
```sh
cargo tauri build
```