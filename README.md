react-panels-extended
=======================

## This is a work in Progress. Not to be used currently for production.

### Extended from [react-panels] (https://github.com/Theadd/react-panels) 
A multipurpose tabbed panel component with many features. Using [React](http://facebook.github.io/react/) **v0.13.1** with addons.

## Install

**Using bower**
```sh
bower install react-panels
```
Include ```bower_components/react-panels/dist/react-panels[.min].js``` after ```react-with-addons[.min].js```

**Using npm**
```sh
npm install react-panels-extended
```
```js
var ReactPanels = require('react-panels-extended')
// or
var ReactPanels = require('react-panels-extended/addons')
```


## Usage

*Example usage:*

```jsx
var Panel = ReactPanels.Panel;
var Tab = ReactPanels.Tab;
var Toolbar = ReactPanels.Toolbar;
var Content = ReactPanels.Content;
var Footer = ReactPanels.Footer;

var MyPanel = React.createClass({
  render: function () {
    return (
      <Panel theme="chemical">
        <Tab title="One" icon="fa fa-plane">
          <Toolbar>Toolbar content of One</Toolbar>
          <Content>Content of One</Content>
          <Footer>Footer content of One</Footer>
        </Tab>
        <Tab title="Two" icon="fa fa-fire">
          <Content>Content of Two</Content>
        </Tab>
      </Panel>
    );
  }
});
```
[License](https://github.com/topgun743/react-panels-extended/blob/master/LICENSE)

The MIT License (MIT)
