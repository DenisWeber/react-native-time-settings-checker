# react-native-time-settings-checker

## Getting started

`$ npm install @secullum/react-native-time-settings-checker --save`

### Mostly automatic installation

`$ react-native link @secullum/react-native-time-settings-checker`

## Usage

```javascript
import TimeSettingsChecker from '@secullum/react-native-time-settings-checker';

const isEnabledAutoDateTime = await TimeSettingsChecker.getAutomaticDateTimeEnabledAsync();
const isEnabledAutoTimezone = await TimeSettingsChecker.getAutomaticTimezoneEnabledAsync();
```
