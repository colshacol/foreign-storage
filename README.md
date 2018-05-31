# AppBar

_AppBar is not meant to be used as a specifically imported and utilized component within a yard-app._ Its primary use case is to be utilized by `yard-app-frame` to offload the work and management from the developer.

---

## Module Exports

 <table>
   <tr>
      <th align="left">name</th>
      <th align="left">typeof</th>
      <th align="left">export</th>
  </tr>
  <tr>
      <td>AppBar</td>
      <td>component</td>
      <td>named</td>
  </tr>
</table>

## Usage

### Props

 <table>
   <tr>
      <th align="left">name</th>
      <th align="left">typeof</th>
      <th align="left">required</th>
      <th align="left">default</th>
  </tr>
  <tr>
    <td>handlers</td>
    <td><a href="/fp-001.md#pure-functions">ObjectOfFunctionsT</a></td>
    <td>n/a</td>
    <td>n/a</td>
  </tr>
</table>

### Importing

```js
import { AppBar } from '@copart/ops-core-yard-app-frame'
```

### Implementation

```js
<AppBar />
```

### Types

[ObjectOfFunctionsT]: foodbar

#### ObjectOfFunctionsT


```js
type ObjectOfFunctions = {
  [name string]: Function
}
```
