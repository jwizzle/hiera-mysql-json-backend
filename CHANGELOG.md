### 0.0.1
- Initial Release

### 0.0.2 - 0.0.3
- Minor Updates

### 0.0.4
- Connection strings can now be defined per hierarchy file instead of being global

### 0.0.5
- Added port as one of the settings that can be defined, thanks [Dave Seff](https://github.com/daveseff)

### 0.0.6

- Made improvements to the connection Hash
- Fixed an issue where if no port was defined nill would be passed
- Added defaults for hostname and port, hostname will default to `localhost` port to `3306`

### 2.0.0

- If we cannot parse JSON as json, do something nasty to try if the value is a
  boolean

### 2.1.0

- Host/domain constraints can now be defined per hierarchy file instead of being global only

### 2.2.0

- Proper connection closing and previous patches
