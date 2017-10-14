# Selector

React multi select component

Adds selectability to a list of items

Ctrl/Command to select a single item
Shift to select a grouping of items

## Props

This component takes the following props.

| Prop              | Type       | Description |
|-------------------|------------|-------------|
| `selectedClass`   | _string_   | Class to add to a selected item
| `selectedStyle`   | _object_   | Style to add to a selected item
| `actionBox`       | _function_ | Called on render with the selected items
| `selected`        | _array_    | Which items should start selected

Example usage
```
<Selector
  selectedClass="selected"
  actionBox={(selectedItems) => <div>selectedItems.join(,)</div>}
  selected={['image1', 'image2']}
>
  <Image key="image1">
  <Image key="image2">
  <Image key="image3">
  <Image key="image4">
</Selector>
```
