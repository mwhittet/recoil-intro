## Using Recoil instead of Redux For State Management In React Applications

The tutorial for this can be found [here](https://blog.openreplay.com/using-recoil-instead-of-redux-for-state-management-in-react-applications), it's very straight forward and gives a brief intoduction into using [Recoil](https://recoiljs.org/).

### Adjustments

Tweaked the pagination slightly as it seemed like to much on the page

### Issues and fixes

`react-router-dom` version 6 required a few modifications:

- Replacement of `Switch` to `Routes`
- Update the `Route component` prop to `element` and adjust the syntax of the rendered element
- Removal of `exact` as it's no longer needed
