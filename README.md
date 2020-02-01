![NPM](https://img.shields.io/npm/l/self-service-calendar) ![Version](https://img.shields.io/github/package-json/v/joshualmitchell/self-service-calendar?color=g) [![tested with jest](https://img.shields.io/badge/tested_with-jest-99424f.svg)](https://github.com/facebook/jest) ![build](https://img.shields.io/travis/joshualmitchell/self-service-calendar) ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/joshualmitchell/self-service-calendar?color=blue)

# self-service-calendar

TODO: Insert GIF

A calendar designed to allow users to book their own appointments with each other in your React app.

* See times you can book
* See times you've already booked
* Book a request (reoccuring supported)

## Getting Started
* Install by executing `npm install self-service-calendar` or `yarn add self-service-calendar`.
* Import by adding `import SSCalendar from 'self-service-calendar'`.
* Use by adding `<SSCalendar />`. Use `onChange` prop for getting new values.

## Demo

TODO: Minimal demo page is included in sample directory.

TODO: [Online demo](http://projects.wojtekmaj.pl/react-calendar/) is also available!


### Compatibility

TODO: Your project needs to use React BLANK or later.

### Usage

Here's an example of basic usage:

```js
import React, { Component } from 'react';
import SSCalendar from 'self-service-calendar';

class MyApp extends Component {
  ...
  // TODO
  ...
}
```

TODO: Check the [sample directory](https://github.com/joshualmitchell/self-service-calendar/tree/master/sample) in this repository for a full working example. For more examples and more advanced use cases, check [Recipes](https://github.com/joshualmitchell/self-service-calendar/wiki/Recipes) in Self-Service-Calendar Wiki.

### Custom styling

TODO: If you want to use default Self-Service-Calendar styling to build upon it, you can import React-Calendar's styles by using:

```js
import 'self-service-calendar/dist/SSCalendar.css';
```

instead.

## User guide

### Calendar

Displays a complete, interactive calendar.

#### Props

|Prop name|Description|Default value|Example values|
|----|----|----|----|
|todo |todo|todo|todo|

### MonthView, YearView, DecadeView, CenturyView

Displays a given month, year, decade and a century, respectively.

#### Props

|Prop name|Description|Default value|Example values|
|----|----|----|----|
|todo |todo|todo|todo|
## Author

<table>
  <tr>
    <td>
      <img src="https://github.com/joshualmitchell/joshualmitchell.github.io/raw/master/assets/images/profile.jpeg" width="100">
    </td>
    <td>
      Joshua Lelon Mitchell<br />
      <a href="mailto:jlelonmitchell@gmail.com">jlelonmitchell@gmail.com</a><br />
      <a href="https://lelon.io">https://lelon.io</a>
    </td>
  </tr>
</table>

## Thanks for checking my package out!