## Setup

Frist of all, make sure your TV and iPhone are in the same WiFi network.

### Remote Start

If you'd like `Remote for BRAVIA TV` to control the power / sleep of your TV. You need to turn the `Remote Start` option ON.

**On Your TV**

- Set Remote start to ON 
  
  [Home] Settings -> Network -> Remote Start
  
### Check Your TV's Host Name / IP Address

For the Remote app to find your TV, you need to tell it the host name, typcally the IP address of your TV.

**On Your TV**

- Check IP Address of BRAVIA TV

  [HOME] Settings > Network > Advanced settings > Network status > IP address

*If you cannot find the options in your `Settings` menu. You may need to enable [Pro settings mode](https://pro-bravia.sony.net/guides/mode/index.html).*

**In the App**

Fill your TV's `IP address` to the `HOST NAME / IP` field.

### Setup a Pre-Shared Key (PSK)

For the Remote app to securely communicate with your TV. You need to setup a Pre-Shared Key (a.k.a PSK).

**On Your TV**

- Change Authentication to Normal and Pre-Shared Key 
    
  [Home] Settings -> Network -> IP Control -> Authentication

- Enter a Pre-Shared Key
    
  [Home] Settings -> Network -> IP control -> Pre-Shared Key

*If you cannot find the options in your `Settings` menu. You may need to enable [Pro settings mode](https://pro-bravia.sony.net/guides/mode/index.html).*

**In the App**

Fill your TV's `Pre-Shared Key` to the `PRE-SHARED KEY` field.

### Test Your Setup

**In the App**

Open `Settings` (The upper left icon on the app's main screen)

Tap the `Toggle TV Power` button on the bottom of the list.

## x-callback-url

Remote for BRAVIA TV supports x-callback-url, allowing the calling app to receive a response (a callback) when a particular interaction has completed.

Here’s an example for sending IRCC code:

```
bravia-remote://x-callback-url/send?code=...&repeat=...
```

The following parameters can be provided:

- `name`

- `code`

- `repeat`

Per the x-callback-url standard, the following additional parameters can be provided:

- `x-success` (optional): A URL that opens when the interaction is successful.

- `x-error` (optional): A URL that opens when the interaction fails because an error occurred.

## Working with the Shortcuts App


## Privacy Policy

We don’t store any your data, period.

What happens on your device stays on your device.

---

*\* BRAVIA is a trademark of Sony Visual Products Inc.*
